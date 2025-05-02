# LocalResourceManager

**Namespace:** `Torappu.Resource.Local`


## Fields

- `String m_resLangFolder`

- `String m_commonLangFolder`

- `ILocalResourceEvents m_resEvents`


## Properties

- `Boolean inited`

- `Int32 loadedAssetCnt`


## Methods

- `Boolean get_inited()`

- `Int32 get_loadedAssetCnt()`

- `Void InitIfNot()`

- `Void ForceReInit()`

- `Void _InitImpl(Boolean)`

- `String GetDebugStr()`

- `T Load(String)`

- `Object Load(String)`

- `AsyncResource LoadAsync(String)`

- `AsyncResource LoadAsync(String)`

- `Void LoadAsync(String, Action`2)`

- `Void LoadAsync(String, Action`2)`

- `Boolean TryLoad(String, out)`

- `Boolean TryLoad(String, out)`

- `Void UnloadAsset(Object)`

- `Void UnloadAssetByInstanceId(Int32)`

- `Boolean CheckExists(String)`

- `AsyncOperation LoadSceneAsync(String, LoadSceneMode)`

- `Boolean LoadScene(String, LoadSceneMode)`

- `Void UnloadScene(String, Boolean)`

- `AsyncOperation UnloadUnusedAssets()`

- `IEnumerator UnloadAllAssets(Boolean)`

- `IEnumerator UnloadAllAssetsExcept(String[], Boolean)`

- `Void RegisterListener(IResourceListener)`

- `Void UnregisterListener(IResourceListener)`

- `Void MarkAssetInvalid(String)`

- `String GenerateAssetFullPath(String, out)`

- `Void _InitResLangFolder()`

- `Void _OnAssetLoaded(Object, String)`

- `Void _HandleAsyncResource(AsyncResource, String)`

- `IEnumerator _LoadAsync(String, Action`2)`

- `IEnumerator _LoadAsync(String, Action`2)`

- `String _PreprocessAssetPath(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource.Local
public class LocalResourceManager : PersistentSingleton`1, IResourceManager
{
	private Dictionary`2 m_loadedAssets; // 0x18
	private ListSet`1 m_listeners; // 0x20
	private String m_resLangFolder; // 0x28
	private String m_commonLangFolder; // 0x30
	private ILocalResourceEvents m_resEvents; // 0x38
	private static DelegateBridge __Hotfix0_get_inited; // 0x0
	private static DelegateBridge __Hotfix0_get_loadedAssetCnt; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_ForceReInit; // 0x28
	private static DelegateBridge __Hotfix0__InitImpl; // 0x30
	private static DelegateBridge __Hotfix0_GetDebugStr; // 0x38
	private static DelegateBridge __Hotfix0_Load; // 0x40
	private static DelegateBridge __Hotfix1_Load; // 0x48
	private static DelegateBridge __Hotfix0_LoadAsync; // 0x50
	private static DelegateBridge __Hotfix1_LoadAsync; // 0x58
	private static DelegateBridge __Hotfix2_LoadAsync; // 0x60
	private static DelegateBridge __Hotfix3_LoadAsync; // 0x68
	private static DelegateBridge __Hotfix0_LoadAll; // 0x70
	private static DelegateBridge __Hotfix1_LoadAll; // 0x78
	private static DelegateBridge __Hotfix0_TryLoad; // 0x80
	private static DelegateBridge __Hotfix1_TryLoad; // 0x88
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x90
	private static DelegateBridge __Hotfix0_UnloadAssetByInstanceId; // 0x98
	private static DelegateBridge __Hotfix0_CheckExists; // 0xa0
	private static DelegateBridge __Hotfix0_LoadSceneAsync; // 0xa8
	private static DelegateBridge __Hotfix0_LoadScene; // 0xb0
	private static DelegateBridge __Hotfix0_UnloadScene; // 0xb8
	private static DelegateBridge __Hotfix0_UnloadUnusedAssets; // 0xc0
	private static DelegateBridge __Hotfix0_UnloadAllAssets; // 0xc8
	private static DelegateBridge __Hotfix0_UnloadAllAssetsExcept; // 0xd0
	private static DelegateBridge __Hotfix0_RegisterListener; // 0xd8
	private static DelegateBridge __Hotfix0_UnregisterListener; // 0xe0
	private static DelegateBridge __Hotfix0_MarkAssetInvalid; // 0xe8
	private static DelegateBridge __Hotfix0_GenerateAssetFullPath; // 0xf0
	private static DelegateBridge __Hotfix0__InitResLangFolder; // 0xf8
	private static DelegateBridge __Hotfix0__OnAssetLoaded; // 0x100
	private static DelegateBridge __Hotfix0__HandleAsyncResource; // 0x108
	private static DelegateBridge __Hotfix0__LoadAsync; // 0x110
	private static DelegateBridge __Hotfix1__LoadAsync; // 0x118
	private static DelegateBridge __Hotfix0__PreprocessAssetPath; // 0x120

	public Boolean inited { get; }
	public Int32 loadedAssetCnt { get; }

	// RVA: 0x3745238 VA: 0x7595d5d238
	public Boolean get_inited() { }
	// RVA: 0x37452a0 VA: 0x7595d5d2a0
	public Int32 get_loadedAssetCnt() { }
	// RVA: 0x3745328 VA: 0x7595d5d328
	private Void .ctor() { }
	// RVA: 0x374545c VA: 0x7595d5d45c
	protected override Void OnInit() { }
	// RVA: 0x374550c VA: 0x7595d5d50c
	public Void InitIfNot() { }
	// RVA: 0x37456e0 VA: 0x7595d5d6e0
	public Void ForceReInit() { }
	// RVA: 0x3745578 VA: 0x7595d5d578
	private Void _InitImpl(Boolean isInit) { }
	// RVA: 0x374585c VA: 0x7595d5d85c
	public String GetDebugStr() { }
	// RVA: 0x VA: 0x0
	public T Load(String path) { }
	// RVA: 0x3745924 VA: 0x7595d5d924
	public Object Load(String path) { }
	// RVA: 0x VA: 0x0
	public AsyncResource LoadAsync(String path) { }
	// RVA: 0x3745cd8 VA: 0x7595d5dcd8
	public AsyncResource LoadAsync(String path) { }
	// RVA: 0x VA: 0x0
	public Void LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x3745f68 VA: 0x7595d5df68
	public Void LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x VA: 0x0
	public T[] LoadAll(String path) { }
	// RVA: 0x37460ec VA: 0x7595d5e0ec
	public Object[] LoadAll(String path) { }
	// RVA: 0x VA: 0x0
	public Boolean TryLoad(String path, out T obj) { }
	// RVA: 0x3746280 VA: 0x7595d5e280
	public Boolean TryLoad(String path, out Object obj) { }
	// RVA: 0x3746390 VA: 0x7595d5e390
	public Void UnloadAsset(Object obj) { }
	// RVA: 0x37464bc VA: 0x7595d5e4bc
	public Void UnloadAssetByInstanceId(Int32 instanceId) { }
	// RVA: 0x374655c VA: 0x7595d5e55c
	public Boolean CheckExists(String path) { }
	// RVA: 0x3746680 VA: 0x7595d5e680
	public AsyncOperation LoadSceneAsync(String path, LoadSceneMode mode) { }
	// RVA: 0x3746748 VA: 0x7595d5e748
	public Boolean LoadScene(String path, LoadSceneMode mode) { }
	// RVA: 0x3746810 VA: 0x7595d5e810
	public Void UnloadScene(String path, Boolean forceUnloadEvenUsed) { }
	// RVA: 0x3746890 VA: 0x7595d5e890
	public AsyncOperation UnloadUnusedAssets() { }
	// RVA: 0x37468f4 VA: 0x7595d5e8f4
	public IEnumerator UnloadAllAssets(Boolean forceUnloadEvenUsed) { }
	// RVA: 0x37469dc VA: 0x7595d5e9dc
	public IEnumerator UnloadAllAssetsExcept(String[] excludedPrefixes, Boolean forceUnloadEvenUseds) { }
	// RVA: 0x3746adc VA: 0x7595d5eadc
	public Void RegisterListener(IResourceListener listener) { }
	// RVA: 0x3746b7c VA: 0x7595d5eb7c
	public Void UnregisterListener(IResourceListener listener) { }
	// RVA: 0x3746c1c VA: 0x7595d5ec1c
	public Void MarkAssetInvalid(String path) { }
	// RVA: 0x3746cec VA: 0x7595d5ecec
	public String GenerateAssetFullPath(String path, out Boolean isStreaming) { }
	// RVA: 0x374574c VA: 0x7595d5d74c
	private Void _InitResLangFolder() { }
	// RVA: 0x3745bd0 VA: 0x7595d5dbd0
	private Void _OnAssetLoaded(Object asset, String path) { }
	// RVA: 0x3745e30 VA: 0x7595d5de30
	private Void _HandleAsyncResource(AsyncResource asyncRes, String path) { }
	// RVA: 0x3746004 VA: 0x7595d5e004
	private IEnumerator _LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x3745a00 VA: 0x7595d5da00
	private String _PreprocessAssetPath(String path) { }
}
```