# LuaEnv

**Namespace:** `XLua`


## Fields

- `LuaTable _G`

- `Int32 last_check_point`

- `Int32 max_check_per_tick`

- `Boolean disposed`

- `String init_xlua`


## Properties

- `LuaTable Global`

- `Int32 GcPause`

- `Int32 GcStepmul`

- `Int32 Memroy`


## Methods

- `LuaTable get_Global()`

- `T LoadString(Byte[], String, LuaTable)`

- `T LoadString(String, String, LuaTable)`

- `LuaFunction LoadString(String, String, LuaTable)`

- `Void AddSearcher(lua_CSFunction, Int32)`

- `Void Alias(Type, String)`

- `Void Tick()`

- `Void GC()`

- `LuaTable NewTable()`

- `Void Dispose()`

- `Void ThrowExceptionFromError(Int32)`

- `Void AddLoader(CustomLoader)`

- `Void AddBuildin(String, lua_CSFunction)`

- `Int32 get_GcPause()`

- `Void set_GcPause(Int32)`

- `Int32 get_GcStepmul()`

- `Void set_GcStepmul(Int32)`

- `Void FullGc()`

- `Void StopGc()`

- `Void RestartGc()`

- `Boolean GcStep(Int32)`

- `Int32 get_Memroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class LuaEnv : IDisposable
{
	public const String CSHARP_NAMESPACE; // 0x0
	public const String MAIN_SHREAD; // 0x0
	internal IntPtr rawL; // 0x10
	private LuaTable _G; // 0x18
	internal ObjectTranslator translator; // 0x20
	internal Int32 errorFuncRef; // 0x28
	internal Object luaLock; // 0x30
	private const Int32 LIB_VERSION_EXPECT; // 0x0
	private static List`1 initers; // 0x0
	private Int32 last_check_point; // 0x38
	private Int32 max_check_per_tick; // 0x3c
	private Func`2 object_valid_checker; // 0x40
	private Boolean disposed; // 0x48
	private Queue`1 refQueue; // 0x50
	private String init_xlua; // 0x58
	internal List`1 customLoaders; // 0x60
	internal Dictionary`2 buildin_initer; // 0x68

	internal IntPtr L { get; }
	internal Object luaEnvLock { get; }
	public LuaTable Global { get; }
	public Int32 GcPause { get; set; }
	public Int32 GcStepmul { get; set; }
	public Int32 Memroy { get; }

	// RVA: 0x3ed9d3c VA: 0x75964f1d3c
	internal IntPtr get_L() { }
	// RVA: 0x3eda1ec VA: 0x75964f21ec
	internal Object get_luaEnvLock() { }
	// RVA: 0x3eda1f4 VA: 0x75964f21f4
	public Void .ctor() { }
	// RVA: 0x3ebeac4 VA: 0x75964d6ac4
	public static Void AddIniter(Action`2 initer) { }
	// RVA: 0x3edb3d4 VA: 0x75964f33d4
	public LuaTable get_Global() { }
	// RVA: 0x VA: 0x0
	public T LoadString(Byte[] chunk, String chunkName, LuaTable env) { }
	// RVA: 0x VA: 0x0
	public T LoadString(String chunk, String chunkName, LuaTable env) { }
	// RVA: 0x3edb3dc VA: 0x75964f33dc
	public LuaFunction LoadString(String chunk, String chunkName, LuaTable env) { }
	// RVA: 0x3edb44c VA: 0x75964f344c
	public Object[] DoString(Byte[] chunk, String chunkName, LuaTable env) { }
	// RVA: 0x3edb2b0 VA: 0x75964f32b0
	public Object[] DoString(String chunk, String chunkName, LuaTable env) { }
	// RVA: 0x3edb098 VA: 0x75964f3098
	private Void AddSearcher(lua_CSFunction searcher, Int32 index) { }
	// RVA: 0x3edb818 VA: 0x75964f3818
	public Void Alias(Type type, String alias) { }
	// RVA: 0x3edb834 VA: 0x75964f3834
	private static Boolean ObjectValidCheck(Object obj) { }
	// RVA: 0x3edb8fc VA: 0x75964f38fc
	public Void Tick() { }
	// RVA: 0x3edbb2c VA: 0x75964f3b2c
	public Void GC() { }
	// RVA: 0x3edbb30 VA: 0x75964f3b30
	public LuaTable NewTable() { }
	// RVA: 0x3edbd14 VA: 0x75964f3d14
	public Void Dispose() { }
	// RVA: 0x3edbe70 VA: 0x75964f3e70
	public virtual Void Dispose(Boolean dispose) { }
	// RVA: 0x3edb640 VA: 0x75964f3640
	public Void ThrowExceptionFromError(Int32 oldTop) { }
	// RVA: 0x3ed9de8 VA: 0x75964f1de8
	internal Void equeueGCAction(GCAction action) { }
	// RVA: 0x3edc050 VA: 0x75964f4050
	public Void AddLoader(CustomLoader loader) { }
	// RVA: 0x3edb310 VA: 0x75964f3310
	public Void AddBuildin(String name, lua_CSFunction initer) { }
	// RVA: 0x3edc100 VA: 0x75964f4100
	public Int32 get_GcPause() { }
	// RVA: 0x3edc200 VA: 0x75964f4200
	public Void set_GcPause(Int32 value) { }
	// RVA: 0x3edc2d8 VA: 0x75964f42d8
	public Int32 get_GcStepmul() { }
	// RVA: 0x3edc3d8 VA: 0x75964f43d8
	public Void set_GcStepmul(Int32 value) { }
	// RVA: 0x3edbd9c VA: 0x75964f3d9c
	public Void FullGc() { }
	// RVA: 0x3edc4b0 VA: 0x75964f44b0
	public Void StopGc() { }
	// RVA: 0x3edc584 VA: 0x75964f4584
	public Void RestartGc() { }
	// RVA: 0x3edc658 VA: 0x75964f4658
	public Boolean GcStep(Int32 data) { }
	// RVA: 0x3edc740 VA: 0x75964f4740
	public Int32 get_Memroy() { }
}
```