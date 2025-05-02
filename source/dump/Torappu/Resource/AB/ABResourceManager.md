# ABResourceManager

**Namespace:** `Torappu.Resource.AB`


## Fields

- `Boolean m_inited`

- `BundleManager m_manager`

- `IConverter m_manifestDecrypter`

- `String m_resLangFolder`

- `String m_commonLangFolder`

- `ResourceOptions <options>k__BackingField`

- `BundleRouter <router>k__BackingField`

- `Manager assetMetas`

- `ResourceManifest <resManifest>k__BackingField`

- `Boolean isStreamingManifest`


## Properties

- `IConverter manifestDecrypter`

- `Boolean inited`

- `Int32 loadedBundleCnt`

- `Int32 loadedAssetCnt`

- `ResourceOptions options`

- `BundleRouter router`

- `ResourceManifest resManifest`


## Methods

- `IConverter get_manifestDecrypter()`

- `Boolean get_inited()`

- `Int32 get_loadedBundleCnt()`

- `Int32 get_loadedAssetCnt()`

- `ResourceOptions get_options()`

- `Void set_options(ResourceOptions)`

- `BundleRouter get_router()`

- `Void set_router(BundleRouter)`

- `ResourceManifest get_resManifest()`

- `Void set_resManifest(ResourceManifest)`

- `Void InitIfNot()`

- `Void ForceReInit()`

- `String GetDebugStr()`

- `ResourceManifest LoadResourceManifest(out, out)`

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

- `Void _RemoveAssetsWithoutBundle()`

- `IEnumerator UnloadAllAssetsExcept(String[], Boolean)`

- `Void RegisterListener(IResourceListener)`

- `Void UnregisterListener(IResourceListener)`

- `Void MarkAssetInvalid(String)`

- `String GenerateAssetFullPath(String, out)`

- `IEnumerator _LoadAsync(String, Action`2)`

- `IEnumerator _LoadAsync(String, Action`2)`

- `IEnumerator _WaitForUnfinishedAsyncResources()`

- `Void _HandleAsyncResource(AsyncResource, BundleHolder, String)`

- `Void _OnAssetLoaded(Object, BundleHolder, String)`

- `Void _DoInitIfNot(Boolean)`

- `Void _InitResLangFolder(ResourceOptions)`

- `Void _InitResourceManifest()`

- `Void _InitBundleManager()`

- `String _PreprocessAssetPath(String)`

- `Void _LogWhenLoadBundleFailed(String, BundleInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource.AB
public class ABResourceManager : PersistentSingleton`1, IResourceManager
{
	private Boolean m_inited; // 0x18
	private Dictionary`2 m_assetNameToBundleInfoMap; // 0x20
	private LocalGenericPool`1 m_assetEntryPool; // 0x28
	private Dictionary`2 m_loadedAssetInstanceIdMap; // 0x30
	private BundleManager m_manager; // 0x38
	private ListSet`1 m_listeners; // 0x40
	private HashSet`1 m_unfinishedAsyncResources; // 0x48
	private List`1 m_tempAsyncResList; // 0x50
	private IConverter m_manifestDecrypter; // 0x58
	private String m_resLangFolder; // 0x60
	private String m_commonLangFolder; // 0x68
	private ResourceOptions <options>k__BackingField; // 0x70
	private BundleRouter <router>k__BackingField; // 0x78
	private Manager assetMetas; // 0x80
	private ResourceManifest <resManifest>k__BackingField; // 0x88
	private Boolean isStreamingManifest; // 0x90
	private static DelegateBridge __Hotfix0_get_manifestDecrypter; // 0x0
	private static DelegateBridge __Hotfix0_get_inited; // 0x8
	private static DelegateBridge __Hotfix0_get_loadedBundleCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_loadedAssetCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_allAssets; // 0x20
	private static DelegateBridge __Hotfix0_get_loadedBundles; // 0x28
	private static DelegateBridge __Hotfix0_get_loadedBundleNames; // 0x30
	private static DelegateBridge __Hotfix0_get_options; // 0x38
	private static DelegateBridge __Hotfix0_set_options; // 0x40
	private static DelegateBridge __Hotfix0_get_router; // 0x48
	private static DelegateBridge __Hotfix0_set_router; // 0x50
	private static DelegateBridge __Hotfix0_get_resManifest; // 0x58
	private static DelegateBridge __Hotfix0_set_resManifest; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x70
	private static DelegateBridge __Hotfix0_ForceReInit; // 0x78
	private static DelegateBridge __Hotfix0_GetDebugStr; // 0x80
	private static DelegateBridge __Hotfix0_LoadResourceManifest; // 0x88
	private static DelegateBridge __Hotfix0_FetchLoadedAssets; // 0x90
	private static DelegateBridge __Hotfix0_Load; // 0x98
	private static DelegateBridge __Hotfix1_Load; // 0xa0
	private static DelegateBridge __Hotfix0_LoadAsync; // 0xa8
	private static DelegateBridge __Hotfix1_LoadAsync; // 0xb0
	private static DelegateBridge __Hotfix2_LoadAsync; // 0xb8
	private static DelegateBridge __Hotfix3_LoadAsync; // 0xc0
	private static DelegateBridge __Hotfix0_LoadAll; // 0xc8
	private static DelegateBridge __Hotfix1_LoadAll; // 0xd0
	private static DelegateBridge __Hotfix0_TryLoad; // 0xd8
	private static DelegateBridge __Hotfix1_TryLoad; // 0xe0
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0xe8
	private static DelegateBridge __Hotfix0_UnloadAssetByInstanceId; // 0xf0
	private static DelegateBridge __Hotfix0_CheckExists; // 0xf8
	private static DelegateBridge __Hotfix0_LoadSceneAsync; // 0x100
	private static DelegateBridge __Hotfix0_LoadScene; // 0x108
	private static DelegateBridge __Hotfix0_UnloadScene; // 0x110
	private static DelegateBridge __Hotfix0_UnloadUnusedAssets; // 0x118
	private static DelegateBridge __Hotfix0_UnloadAllAssets; // 0x120
	private static DelegateBridge __Hotfix0__RemoveAssetsWithoutBundle; // 0x128
	private static DelegateBridge __Hotfix0_UnloadAllAssetsExcept; // 0x130
	private static DelegateBridge __Hotfix0_RegisterListener; // 0x138
	private static DelegateBridge __Hotfix0_UnregisterListener; // 0x140
	private static DelegateBridge __Hotfix0_MarkAssetInvalid; // 0x148
	private static DelegateBridge __Hotfix0_GenerateAssetFullPath; // 0x150
	private static DelegateBridge __Hotfix0__LoadAsync; // 0x158
	private static DelegateBridge __Hotfix1__LoadAsync; // 0x160
	private static DelegateBridge __Hotfix0__WaitForUnfinishedAsyncResources; // 0x168
	private static DelegateBridge __Hotfix0__HandleAsyncResource; // 0x170
	private static DelegateBridge __Hotfix0__OnAssetLoaded; // 0x178
	private static DelegateBridge __Hotfix0__DoInitIfNot; // 0x180
	private static DelegateBridge __Hotfix0__InitResLangFolder; // 0x188
	private static DelegateBridge __Hotfix0__InitResourceManifest; // 0x190
	private static DelegateBridge __Hotfix0__InitBundleManager; // 0x198
	private static DelegateBridge __Hotfix0_UnloadABAsset; // 0x1a0
	private static DelegateBridge __Hotfix0__PreprocessAssetPath; // 0x1a8
	private static DelegateBridge __Hotfix0__LogWhenLoadBundleFailed; // 0x1b0
	private static DelegateBridge __Hotfix0__IsAuditMode; // 0x1b8
	private static DelegateBridge __Hotfix0__DeleteABFileDelayed; // 0x1c0

	private IConverter manifestDecrypter { get; }
	public Boolean inited { get; }
	public Int32 loadedBundleCnt { get; }
	public Int32 loadedAssetCnt { get; }
	internal IEnumerable`1 allAssets { get; }
	internal IEnumerable`1 loadedBundles { get; }
	internal IEnumerable`1 loadedBundleNames { get; }
	private ResourceOptions options { get; set; }
	private BundleRouter router { get; set; }
	private ResourceManifest resManifest { get; set; }

	// RVA: 0x3747818 VA: 0x7595d5f818
	private IConverter get_manifestDecrypter() { }
	// RVA: 0x37478a4 VA: 0x7595d5f8a4
	public Boolean get_inited() { }
	// RVA: 0x374790c VA: 0x7595d5f90c
	public Int32 get_loadedBundleCnt() { }
	// RVA: 0x37479d4 VA: 0x7595d5f9d4
	public Int32 get_loadedAssetCnt() { }
	// RVA: 0x3747a5c VA: 0x7595d5fa5c
	internal IEnumerable`1 get_allAssets() { }
	// RVA: 0x3747ae4 VA: 0x7595d5fae4
	internal IEnumerable`1 get_loadedBundles() { }
	// RVA: 0x3747b9c VA: 0x7595d5fb9c
	internal IEnumerable`1 get_loadedBundleNames() { }
	// RVA: 0x3747c68 VA: 0x7595d5fc68
	private ResourceOptions get_options() { }
	// RVA: 0x3747cd0 VA: 0x7595d5fcd0
	private Void set_options(ResourceOptions value) { }
	// RVA: 0x3747d54 VA: 0x7595d5fd54
	private BundleRouter get_router() { }
	// RVA: 0x3747dbc VA: 0x7595d5fdbc
	private Void set_router(BundleRouter value) { }
	// RVA: 0x3747e40 VA: 0x7595d5fe40
	private ResourceManifest get_resManifest() { }
	// RVA: 0x3747ea8 VA: 0x7595d5fea8
	private Void set_resManifest(ResourceManifest value) { }
	// RVA: 0x3747f2c VA: 0x7595d5ff2c
	private Void .ctor() { }
	// RVA: 0x3748380 VA: 0x7595d60380
	public Void InitIfNot() { }
	// RVA: 0x37486ec VA: 0x7595d606ec
	public Void ForceReInit() { }
	// RVA: 0x374875c VA: 0x7595d6075c
	public String GetDebugStr() { }
	// RVA: 0x3748848 VA: 0x7595d60848
	public ResourceManifest LoadResourceManifest(out String manifestName, out Boolean isStreaming) { }
	// RVA: 0x3748c88 VA: 0x7595d60c88
	internal Void FetchLoadedAssets(List`1 results) { }
	// RVA: 0x VA: 0x0
	public T Load(String path) { }
	// RVA: 0x3748ecc VA: 0x7595d60ecc
	public Object Load(String path) { }
	// RVA: 0x VA: 0x0
	public AsyncResource LoadAsync(String path) { }
	// RVA: 0x37496fc VA: 0x7595d616fc
	public AsyncResource LoadAsync(String path) { }
	// RVA: 0x VA: 0x0
	public Void LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x3749bc4 VA: 0x7595d61bc4
	public Void LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x VA: 0x0
	public T[] LoadAll(String path) { }
	// RVA: 0x3749d48 VA: 0x7595d61d48
	public Object[] LoadAll(String path) { }
	// RVA: 0x VA: 0x0
	public Boolean TryLoad(String path, out T obj) { }
	// RVA: 0x374a25c VA: 0x7595d6225c
	public Boolean TryLoad(String path, out Object obj) { }
	// RVA: 0x374a380 VA: 0x7595d62380
	public Void UnloadAsset(Object obj) { }
	// RVA: 0x374a5e8 VA: 0x7595d625e8
	public Void UnloadAssetByInstanceId(Int32 instanceId) { }
	// RVA: 0x374a75c VA: 0x7595d6275c
	public Boolean CheckExists(String path) { }
	// RVA: 0x374a830 VA: 0x7595d62830
	public AsyncOperation LoadSceneAsync(String path, LoadSceneMode mode) { }
	// RVA: 0x374aa0c VA: 0x7595d62a0c
	public Boolean LoadScene(String path, LoadSceneMode mode) { }
	// RVA: 0x374abe0 VA: 0x7595d62be0
	public Void UnloadScene(String path, Boolean forceUnloadEvenUsed) { }
	// RVA: 0x374ae14 VA: 0x7595d62e14
	public AsyncOperation UnloadUnusedAssets() { }
	// RVA: 0x374b038 VA: 0x7595d63038
	public IEnumerator UnloadAllAssets(Boolean forceUnloadEvenUsed) { }
	// RVA: 0x374b128 VA: 0x7595d63128
	private Void _RemoveAssetsWithoutBundle() { }
	// RVA: 0x374b67c VA: 0x7595d6367c
	public IEnumerator UnloadAllAssetsExcept(String[] excludedPrefixes, Boolean forceUnloadEvenUsed) { }
	// RVA: 0x374b784 VA: 0x7595d63784
	public Void RegisterListener(IResourceListener listener) { }
	// RVA: 0x374b824 VA: 0x7595d63824
	public Void UnregisterListener(IResourceListener listener) { }
	// RVA: 0x374b8c4 VA: 0x7595d638c4
	public Void MarkAssetInvalid(String path) { }
	// RVA: 0x374bb90 VA: 0x7595d63b90
	public String GenerateAssetFullPath(String path, out Boolean isStreaming) { }
	// RVA: 0x3749c60 VA: 0x7595d61c60
	private IEnumerator _LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x374bcd0 VA: 0x7595d63cd0
	private IEnumerator _WaitForUnfinishedAsyncResources() { }
	// RVA: 0x37499bc VA: 0x7595d619bc
	private Void _HandleAsyncResource(AsyncResource asyncRes, BundleHolder bundle, String path) { }
	// RVA: 0x37493d4 VA: 0x7595d613d4
	private Void _OnAssetLoaded(Object asset, BundleHolder bundle, String path) { }
	// RVA: 0x37483ec VA: 0x7595d603ec
	private Void _DoInitIfNot(Boolean isFirstInit) { }
	// RVA: 0x374c014 VA: 0x7595d64014
	private Void _InitResLangFolder(ResourceOptions options) { }
	// RVA: 0x374c120 VA: 0x7595d64120
	private Void _InitResourceManifest() { }
	// RVA: 0x374c344 VA: 0x7595d64344
	private Void _InitBundleManager() { }
	// RVA: 0x374cda8 VA: 0x7595d64da8
	public static Void UnloadABAsset(Object asset, Boolean allowDestroyingAssets) { }
	// RVA: 0x3749050 VA: 0x7595d61050
	private String _PreprocessAssetPath(String path) { }
	// RVA: 0x374958c VA: 0x7595d6158c
	private Void _LogWhenLoadBundleFailed(String path, BundleInfo info) { }
	// RVA: 0x374cef8 VA: 0x7595d64ef8
	private static Boolean _IsAuditMode() { }
	// RVA: 0x374bae4 VA: 0x7595d63ae4
	private static IEnumerator _DeleteABFileDelayed(String abFilePath) { }
}
```