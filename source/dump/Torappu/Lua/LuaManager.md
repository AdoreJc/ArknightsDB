# LuaManager

**Namespace:** `Torappu.Lua`


## Fields

- `Boolean m_inited`

- `LuaEnv m_env`

- `String m_folder`

- `IConverter m_decrypter`

- `PeriodicTimer m_tickTimer`

- `ILoadAsset m_assetLoader`

- `TextAsset m_holdLuaAsset`


## Properties

- `LuaEnv luaEnv`


## Methods

- `LuaEnv get_luaEnv()`

- `Void _DoInitIfNot()`

- `Void _DoLoadEntryScript(LuaOptions)`

- `Void _DoReloadScripts()`

- `Void _DoUpdate(Single)`

- `Void _DoLoad(String)`

- `String _ConvertToFullPath(String)`

- `Void _ClearCachedLuaAsset()`

- `Void _DoCreateLuaEnv()`

- `Boolean _DoDisposeLuaEnv()`

- `Boolean _CallLuaDisposeInAnotherStackFrame()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaManager : Singleton`1
{
	private const Single TICK_INTERVAL; // 0x0
	private const String MOCK_EXTENSION; // 0x0
	private Boolean m_inited; // 0x10
	private LuaEnv m_env; // 0x18
	private String m_folder; // 0x20
	private IConverter m_decrypter; // 0x28
	private PeriodicTimer m_tickTimer; // 0x30
	private ILoadAsset m_assetLoader; // 0x38
	private TextAsset m_holdLuaAsset; // 0x40
	private static DelegateBridge __Hotfix0_get_luaEnv; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_ReloadScripts; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_Dispose; // 0x20
	private static DelegateBridge __Hotfix0_FullGC; // 0x28
	private static DelegateBridge __Hotfix0__DoInitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__DoLoadEntryScript; // 0x38
	private static DelegateBridge __Hotfix0__DoReloadScripts; // 0x40
	private static DelegateBridge __Hotfix0__DoUpdate; // 0x48
	private static DelegateBridge __Hotfix0__DoLoad; // 0x50
	private static DelegateBridge __Hotfix0__CustomLoader; // 0x58
	private static DelegateBridge __Hotfix0__ConvertToFullPath; // 0x60
	private static DelegateBridge __Hotfix0__ClearCachedLuaAsset; // 0x68
	private static DelegateBridge __Hotfix0__DoCreateLuaEnv; // 0x70
	private static DelegateBridge __Hotfix0__DoDisposeLuaEnv; // 0x78
	private static DelegateBridge __Hotfix0__CallLuaDisposeInAnotherStackFrame; // 0x80
	private static DelegateBridge __Hotfix0__InjectDefinesToLuaEnv; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public LuaEnv luaEnv { get; }

	// RVA: 0x35ae30c VA: 0x7595bc630c
	public LuaEnv get_luaEnv() { }
	// RVA: 0x35ae374 VA: 0x7595bc6374
	public static Void InitIfNot() { }
	// RVA: 0x35ae518 VA: 0x7595bc6518
	public static Void ReloadScripts() { }
	// RVA: 0x35ae648 VA: 0x7595bc6648
	public static Void Update(Single deltaTime) { }
	// RVA: 0x35ae864 VA: 0x7595bc6864
	public static Void Dispose() { }
	// RVA: 0x35aecd4 VA: 0x7595bc6cd4
	public static Void FullGC() { }
	// RVA: 0x35ae3f4 VA: 0x7595bc63f4
	private Void _DoInitIfNot() { }
	// RVA: 0x35aed80 VA: 0x7595bc6d80
	private Void _DoLoadEntryScript(LuaOptions options) { }
	// RVA: 0x35ae598 VA: 0x7595bc6598
	private Void _DoReloadScripts() { }
	// RVA: 0x35ae6e0 VA: 0x7595bc66e0
	private Void _DoUpdate(Single deltaTime) { }
	// RVA: 0x35af140 VA: 0x7595bc7140
	private Void _DoLoad(String filePath) { }
	// RVA: 0x35af4e0 VA: 0x7595bc74e0
	private Byte[] _CustomLoader(ref String filePath) { }
	// RVA: 0x35afb58 VA: 0x7595bc7b58
	private String _ConvertToFullPath(String filePath) { }
	// RVA: 0x35af3a0 VA: 0x7595bc73a0
	private Void _ClearCachedLuaAsset() { }
	// RVA: 0x35af210 VA: 0x7595bc7210
	private Void _DoCreateLuaEnv() { }
	// RVA: 0x35ae8e4 VA: 0x7595bc68e4
	private Boolean _DoDisposeLuaEnv() { }
	// RVA: 0x35afd7c VA: 0x7595bc7d7c
	private Boolean _CallLuaDisposeInAnotherStackFrame() { }
	// RVA: 0x35afc44 VA: 0x7595bc7c44
	private static Void _InjectDefinesToLuaEnv(LuaEnv env) { }
	// RVA: 0x35afe74 VA: 0x7595bc7e74
	private Void .ctor() { }
}
```