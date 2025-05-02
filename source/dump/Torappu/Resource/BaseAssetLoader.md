# BaseAssetLoader

**Namespace:** `Torappu.Resource`


## Fields

- `AssetGroupRecord m_groupRecord`

- `UnloadManager m_unloadManager`

- `Boolean m_isInited`

- `Boolean <disableDelayedUnload>k__BackingField`


## Properties

- `Boolean disableDelayedUnload`


## Methods

- `Boolean get_disableDelayedUnload()`

- `Void set_disableDelayedUnload(Boolean)`

- `T LoadAsset(String)`

- `T LoadAsset(String, Int32)`

- `T _LoadAsset(String, Int32)`

- `Boolean TryLoad(String, out, Int32)`

- `Boolean TryLoad(String, out, Int32)`

- `Void _OnAssetLoaded(String, Object, Int32)`

- `Void UnloadAsset(Object, Int32)`

- `Void UnloadAssetGroup(Int32)`

- `Void Legacy_RemoveAsset(String)`

- `Void ForceUnloadPending()`

- `Void NotifyCurrentTime(Int64)`

- `Void _InitIfNot()`

- `Void Dispose()`

- `EditorInterface CreateEditorInterface()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Resource
public class BaseAssetLoader : IHotfixable, IDisposable
{
	public const Int32 DEFAULT_GROUP; // 0x0
	private Dictionary`2 m_pathToAsset; // 0x10
	private AssetGroupRecord m_groupRecord; // 0x18
	private Dictionary`2 m_loadedAssets; // 0x20
	private UnloadManager m_unloadManager; // 0x28
	private Boolean m_isInited; // 0x30
	private static BaseAssetLoader s_baseAssetLoader; // 0x0
	private Boolean <disableDelayedUnload>k__BackingField; // 0x31
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x8
	private static __XLua_Gen_Delegate145 __Hotfix0_get_instanceOrNull; // 0x10
	private static __XLua_Gen_Delegate4 __Hotfix0_PolicyOnly_CreateInstance; // 0x18
	private static __XLua_Gen_Delegate4 __Hotfix0_PolicyOnly_DestroyInstance; // 0x20
	private static __XLua_Gen_Delegate8 __Hotfix0_get_disableDelayedUnload; // 0x28
	private static __XLua_Gen_Delegate9 __Hotfix0_set_disableDelayedUnload; // 0x30
	private static __XLua_Gen_Delegate146 __Hotfix0_TryLoad; // 0x38
	private static __XLua_Gen_Delegate147 __Hotfix0__OnAssetLoaded; // 0x40
	private static __XLua_Gen_Delegate141 __Hotfix0_UnloadAsset; // 0x48
	private static __XLua_Gen_Delegate11 __Hotfix0_UnloadAssetGroup; // 0x50
	private static __XLua_Gen_Delegate0 __Hotfix0_Legacy_RemoveAsset; // 0x58
	private static __XLua_Gen_Delegate1 __Hotfix0_ForceUnloadPending; // 0x60
	private static __XLua_Gen_Delegate22 __Hotfix0_NotifyCurrentTime; // 0x68
	private static __XLua_Gen_Delegate1 __Hotfix0__InitIfNot; // 0x70
	private static __XLua_Gen_Delegate1 __Hotfix0_Dispose; // 0x78
	private static __XLua_Gen_Delegate148 __Hotfix0_CreateEditorInterface; // 0x80

	public static BaseAssetLoader instanceOrNull { get; }
	private Boolean disableDelayedUnload { get; set; }

	// RVA: 0x6793c6c VA: 0x7598dabc6c
	private Void .ctor() { }
	// RVA: 0x6793e8c VA: 0x7598dabe8c
	public static BaseAssetLoader get_instanceOrNull() { }
	// RVA: 0x6793ef4 VA: 0x7598dabef4
	public static Void PolicyOnly_CreateInstance() { }
	// RVA: 0x679405c VA: 0x7598dac05c
	public static Void PolicyOnly_DestroyInstance() { }
	// RVA: 0x67941b0 VA: 0x7598dac1b0
	private Boolean get_disableDelayedUnload() { }
	// RVA: 0x6794220 VA: 0x7598dac220
	public Void set_disableDelayedUnload(Boolean value) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path, Int32 group) { }
	// RVA: 0x VA: 0x0
	private T _LoadAsset(String path, Int32 group) { }
	// RVA: 0x VA: 0x0
	public Boolean TryLoad(String path, out T obj, Int32 group) { }
	// RVA: 0x67942a8 VA: 0x7598dac2a8
	public Boolean TryLoad(String path, out Object obj, Int32 group) { }
	// RVA: 0x67943dc VA: 0x7598dac3dc
	private Void _OnAssetLoaded(String path, Object asset, Int32 group) { }
	// RVA: 0x67949a0 VA: 0x7598dac9a0
	public Void UnloadAsset(Object asset, Int32 group) { }
	// RVA: 0x6794d38 VA: 0x7598dacd38
	public Void UnloadAssetGroup(Int32 group) { }
	// RVA: 0x6795008 VA: 0x7598dad008
	public Void Legacy_RemoveAsset(String path) { }
	// RVA: 0x6795218 VA: 0x7598dad218
	public Void ForceUnloadPending() { }
	// RVA: 0x6795414 VA: 0x7598dad414
	public Void NotifyCurrentTime(Int64 curTs) { }
	// RVA: 0x6793f98 VA: 0x7598dabf98
	private Void _InitIfNot() { }
	// RVA: 0x VA: 0x0
	public static Ref GetPoolListRef() { }
	// RVA: 0x67940e4 VA: 0x7598dac0e4
	public Void Dispose() { }
	// RVA: 0x6795804 VA: 0x7598dad804
	public EditorInterface CreateEditorInterface() { }
}
```