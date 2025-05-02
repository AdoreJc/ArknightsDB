# LuaUIContext

**Namespace:** `Torappu.Lua`


## Fields

- `IContextHost m_host`

- `ILuaDialog m_child`

- `LuaTable <paramData>k__BackingField`


## Properties

- `Boolean opened`

- `LuaTable paramData`


## Methods

- `Void Open(IContextHost)`

- `Void Close()`

- `Void RequestClose(ILuaDialog)`

- `Boolean get_opened()`

- `Transform GetHookRoot()`

- `GameObject LoadPrefab(String)`

- `LuaLayout LoadLayout(String)`

- `Sprite LoadSprite(String)`

- `ScriptableObject LoadScriptableObject(String)`

- `Sprite LoadSpriteFromAutoPackHub(String, String)`

- `Void SaveData(String, String)`

- `Void SaveDataBundle(String, DataBundle)`

- `String GetData(String)`

- `DataBundle GetDataBundle(String)`

- `LuaTable get_paramData()`

- `Void set_paramData(LuaTable)`

- `Void ClosedByParent()`

- `LuaLayout GetLuaLayout()`

- `Void ShowEnterEffect()`

- `Boolean IsEnterEffectEnd()`

- `T LoadAsset(String)`

- `Object LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Object GetCompLuaBinder(String)`

- `Void _InitCompSystem(IContextHost)`

- `WeakReference GetComp(String)`

- `Void <Open>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaUIContext : ILuaCallCSharp, ILuaDialog, ILoadAsset
{
	private static ILuaDialogMgr s_mgr; // 0x0
	private IContextHost m_host; // 0x10
	private Dictionary`2 m_hostData; // 0x18
	private Dictionary`2 m_hostDataBundle; // 0x20
	private ILuaDialog m_child; // 0x28
	private LuaTable <paramData>k__BackingField; // 0x30
	private Dictionary`2 m_comps; // 0x38
	private IDictionary`2 m_compDeclaration; // 0x40

	public static Boolean inited { get; }
	public Boolean opened { get; }
	public LuaTable paramData { get; set; }

	// RVA: 0x35b7138 VA: 0x7595bcf138
	public static Void SetDialogMgr(ILuaDialogMgr dialogMgr) { }
	// RVA: 0x35b7190 VA: 0x7595bcf190
	public static Boolean get_inited() { }
	// RVA: 0x35b71e0 VA: 0x7595bcf1e0
	public Void Open(IContextHost host) { }
	// RVA: 0x35b765c VA: 0x7595bcf65c
	public Void Close() { }
	// RVA: 0x35b7884 VA: 0x7595bcf884
	public Void RequestClose(ILuaDialog child) { }
	// RVA: 0x35b7930 VA: 0x7595bcf930
	public Boolean get_opened() { }
	// RVA: 0x35b7940 VA: 0x7595bcf940
	public Transform GetHookRoot() { }
	// RVA: 0x35b79e4 VA: 0x7595bcf9e4
	public GameObject LoadPrefab(String path) { }
	// RVA: 0x35b7ab0 VA: 0x7595bcfab0
	public LuaLayout LoadLayout(String path) { }
	// RVA: 0x35b7b7c VA: 0x7595bcfb7c
	public Sprite LoadSprite(String path) { }
	// RVA: 0x35b7c48 VA: 0x7595bcfc48
	public ScriptableObject LoadScriptableObject(String path) { }
	// RVA: 0x35b7d14 VA: 0x7595bcfd14
	public Sprite LoadSpriteFromAutoPackHub(String hubPath, String spriteId) { }
	// RVA: 0x35b7f54 VA: 0x7595bcff54
	public Void SaveData(String key, String data) { }
	// RVA: 0x35b8014 VA: 0x7595bd0014
	public Void SaveDataBundle(String key, DataBundle data) { }
	// RVA: 0x35b80d4 VA: 0x7595bd00d4
	public String GetData(String key) { }
	// RVA: 0x35b814c VA: 0x7595bd014c
	public DataBundle GetDataBundle(String key) { }
	// RVA: 0x35b81c4 VA: 0x7595bd01c4
	public LuaTable get_paramData() { }
	// RVA: 0x35b81cc VA: 0x7595bd01cc
	public Void set_paramData(LuaTable value) { }
	// RVA: 0x35b81d4 VA: 0x7595bd01d4
	public Void ClosedByParent() { }
	// RVA: 0x35b81d8 VA: 0x7595bd01d8
	public LuaLayout GetLuaLayout() { }
	// RVA: 0x35b827c VA: 0x7595bd027c
	public Void ShowEnterEffect() { }
	// RVA: 0x35b8328 VA: 0x7595bd0328
	public Boolean IsEnterEffectEnd() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x35b83d8 VA: 0x7595bd03d8
	public Object LoadAsset(String path) { }
	// RVA: 0x35b8430 VA: 0x7595bd0430
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x35b84e4 VA: 0x7595bd04e4
	public Object GetCompLuaBinder(String key) { }
	// RVA: 0x35b7578 VA: 0x7595bcf578
	private Void _InitCompSystem(IContextHost host) { }
	// RVA: 0x35b8840 VA: 0x7595bd0840
	public WeakReference GetComp(String key) { }
	// RVA: 0x35b891c VA: 0x7595bd091c
	public Void .ctor() { }
	// RVA: 0x35b8924 VA: 0x7595bd0924
	private Void <Open>b__9_0() { }
}
```