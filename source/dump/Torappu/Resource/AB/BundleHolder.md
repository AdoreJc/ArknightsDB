# BundleHolder

**Namespace:** `Torappu.Resource.AB`


## Fields

- `AssetBundle <ab>k__BackingField`

- `BundleInfo <info>k__BackingField`

- `Boolean <isSceneBundle>k__BackingField`

- `Boolean <isDestroyed>k__BackingField`


## Properties

- `AssetBundle ab`

- `BundleInfo info`

- `Boolean isCached`

- `Boolean isSceneBundle`

- `Boolean isDestroyed`

- `String name`


## Methods

- `AssetBundle get_ab()`

- `Void set_ab(AssetBundle)`

- `BundleInfo get_info()`

- `Void set_info(BundleInfo)`

- `Boolean get_isCached()`

- `Boolean get_isSceneBundle()`

- `Void set_isSceneBundle(Boolean)`

- `Boolean get_isDestroyed()`

- `Void set_isDestroyed(Boolean)`

- `String get_name()`

- `Void LateInit(ResourceOptions)`

- `T Load(AssetKey)`

- `Object Load(AssetKey)`

- `AsyncResource LoadAsync(AssetKey)`

- `AsyncResource LoadAsync(AssetKey)`

- `Void Unload(Boolean)`

- `Boolean _TryCacheAssets(ResourceOptions)`

- `Boolean _CheckStreamingAsset(Object)`

- `T _LoadAssetFromAB(AssetKey)`

- `Object _LoadAssetFromAB(AssetKey)`

- `T _LoadAssetFromCache(AssetKey)`

- `Object _LoadAssetFromCache(AssetKey)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource.AB
public class BundleHolder : BundleRef
{
	private Object[] m_cachedAssets; // 0x20
	private Object[][] m_cachedAssetsWithSubAssets; // 0x28
	private AssetBundle <ab>k__BackingField; // 0x30
	private BundleInfo <info>k__BackingField; // 0x38
	private Boolean <isSceneBundle>k__BackingField; // 0x40
	private Boolean <isDestroyed>k__BackingField; // 0x41

	public AssetBundle ab { get; set; }
	public BundleInfo info { get; set; }
	public Boolean isCached { get; }
	public Boolean isSceneBundle { get; set; }
	public Boolean isDestroyed { get; set; }
	public String name { get; }

	// RVA: 0x374f37c VA: 0x7595d6737c
	public AssetBundle get_ab() { }
	// RVA: 0x374f384 VA: 0x7595d67384
	private Void set_ab(AssetBundle value) { }
	// RVA: 0x374f38c VA: 0x7595d6738c
	public BundleInfo get_info() { }
	// RVA: 0x374f394 VA: 0x7595d67394
	private Void set_info(BundleInfo value) { }
	// RVA: 0x374d5f0 VA: 0x7595d655f0
	public Boolean get_isCached() { }
	// RVA: 0x374f39c VA: 0x7595d6739c
	public Boolean get_isSceneBundle() { }
	// RVA: 0x374f3a4 VA: 0x7595d673a4
	private Void set_isSceneBundle(Boolean value) { }
	// RVA: 0x374f3b0 VA: 0x7595d673b0
	public Boolean get_isDestroyed() { }
	// RVA: 0x374f3b8 VA: 0x7595d673b8
	private Void set_isDestroyed(Boolean value) { }
	// RVA: 0x374d9b0 VA: 0x7595d659b0
	public String get_name() { }
	// RVA: 0x374d42c VA: 0x7595d6542c
	public static BundleHolder Create(BundleInfo info, IBundleRouter router) { }
	// RVA: 0x374f3c4 VA: 0x7595d673c4
	private Void .ctor(AssetBundle ab, BundleInfo info) { }
	// RVA: 0x374d5ec VA: 0x7595d655ec
	public Void LateInit(ResourceOptions options) { }
	// RVA: 0x VA: 0x0
	public T Load(AssetKey key) { }
	// RVA: 0x3749370 VA: 0x7595d61370
	public Object Load(AssetKey key) { }
	// RVA: 0x VA: 0x0
	public AsyncResource LoadAsync(AssetKey key) { }
	// RVA: 0x3749898 VA: 0x7595d61898
	public AsyncResource LoadAsync(AssetKey key) { }
	// RVA: 0x VA: 0x0
	public T[] LoadAll(AssetKey key) { }
	// RVA: 0x3749ed4 VA: 0x7595d61ed4
	public Object[] LoadAll(AssetKey key) { }
	// RVA: 0x374da08 VA: 0x7595d65a08
	public Void Unload(Boolean unloadAllLoadedAssets) { }
	// RVA: 0x374f840 VA: 0x7595d67840
	protected override Void OnDestroy() { }
	// RVA: 0x374f474 VA: 0x7595d67474
	private Boolean _TryCacheAssets(ResourceOptions options) { }
	// RVA: 0x374f848 VA: 0x7595d67848
	private Boolean _CheckStreamingAsset(Object obj) { }
	// RVA: 0x VA: 0x0
	private T _LoadAssetFromAB(AssetKey key) { }
	// RVA: 0x374f6bc VA: 0x7595d676bc
	private Object _LoadAssetFromAB(AssetKey key) { }
	// RVA: 0x VA: 0x0
	private T _LoadAssetFromCache(AssetKey key) { }
	// RVA: 0x374f76c VA: 0x7595d6776c
	private Object _LoadAssetFromCache(AssetKey key) { }
}
```