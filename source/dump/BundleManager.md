# BundleManager

**Namespace:** ` `


## Fields

- `ABResourceManager m_resManager`


## Properties

- `Int32 activeBundleCnt`

- `ResourceManifest resManifest`

- `BundleRouter router`

- `ResourceOptions options`

- `Manager assetMetas`


## Methods

- `Int32 get_activeBundleCnt()`

- `ResourceManifest get_resManifest()`

- `BundleRouter get_router()`

- `ResourceOptions get_options()`

- `Manager get_assetMetas()`

- `Boolean TryGetInfo(String, out)`

- `Boolean TryGetOrLoadBundle(BundleInfo, out)`

- `BundleHolder GetOrLoadBundle(BundleInfo)`

- `Void UnloadAssetAndDecBundleRef(String, Object)`

- `Void DecBundleRef(String, BundleInfo)`

- `Void _DecRef(BundleHolder, Boolean, Boolean)`

- `Boolean CheckBundleInvalid(BundleHolder)`

- `Void Unload(String, Boolean)`

- `Void UnloadAll(Boolean, out)`

- `Void UnloadAllExcept(ICollection`1, Boolean)`

- `Void _UnloadAllImpl(Boolean)`

- `Void _UnloadBatchImpl(Boolean, List`1)`

- `Void UnloadUnusedBundles()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BundleManager : IEnumerable`1, IEnumerable
{
	private static List`1 s_tempBundleList; // 0x0
	private ABResourceManager m_resManager; // 0x10
	private Dictionary`2 m_bundleNameToBundleInfoMap; // 0x18
	private Dictionary`2 m_activeBundlesMap; // 0x20
	private List`1[] m_activeBundleSCCGroups; // 0x28

	public Int32 activeBundleCnt { get; }
	public Dictionary`2 activeBundles { get; }
	private ResourceManifest resManifest { get; }
	private BundleRouter router { get; }
	private ResourceOptions options { get; }
	private Manager assetMetas { get; }

	// RVA: 0x3747984 VA: 0x7595d5f984
	public Int32 get_activeBundleCnt() { }
	// RVA: 0x374d0a4 VA: 0x7595d650a4
	public Dictionary`2 get_activeBundles() { }
	// RVA: 0x374d0ac VA: 0x7595d650ac
	private ResourceManifest get_resManifest() { }
	// RVA: 0x374d0c4 VA: 0x7595d650c4
	private BundleRouter get_router() { }
	// RVA: 0x374d0dc VA: 0x7595d650dc
	private ResourceOptions get_options() { }
	// RVA: 0x374d0f4 VA: 0x7595d650f4
	private Manager get_assetMetas() { }
	// RVA: 0x374c610 VA: 0x7595d64610
	public Void .ctor(ABResourceManager resManager) { }
	// RVA: 0x374ca80 VA: 0x7595d64a80
	public Boolean TryGetInfo(String bundleName, out BundleInfo info) { }
	// RVA: 0x37491e4 VA: 0x7595d611e4
	public Boolean TryGetOrLoadBundle(BundleInfo info, out BundleHolder bundle) { }
	// RVA: 0x374d110 VA: 0x7595d65110
	public BundleHolder GetOrLoadBundle(BundleInfo info) { }
	// RVA: 0x374a50c VA: 0x7595d6250c
	public Void UnloadAssetAndDecBundleRef(String name, Object obj) { }
	// RVA: 0x374d854 VA: 0x7595d65854
	public Void DecBundleRef(String bundleName, BundleInfo source) { }
	// RVA: 0x374d650 VA: 0x7595d65650
	private Void _DecRef(BundleHolder bundle, Boolean isAssetRef, Boolean sameSCC) { }
	// RVA: 0x374bdcc VA: 0x7595d63dcc
	public Boolean CheckBundleInvalid(BundleHolder bundle) { }
	// RVA: 0x374acf4 VA: 0x7595d62cf4
	public Void Unload(String bundleName, Boolean forceUnloadEvenUsed) { }
	// RVA: 0x374dac8 VA: 0x7595d65ac8
	public Void UnloadAll(Boolean forceUnloadEvenUsed, out Boolean hasBundleRetained) { }
	// RVA: 0x374e16c VA: 0x7595d6616c
	public Void UnloadAllExcept(ICollection`1 excludedBundles, Boolean forceUnloadEvenUsed) { }
	// RVA: 0x374dda8 VA: 0x7595d65da8
	private Void _UnloadAllImpl(Boolean forceUnloadEvenUsed) { }
	// RVA: 0x374dfb8 VA: 0x7595d65fb8
	private Void _UnloadBatchImpl(Boolean forceUnloadEvenUsed, List`1 bundles) { }
	// RVA: 0x374ae8c VA: 0x7595d62e8c
	public Void UnloadUnusedBundles() { }
	// RVA: 0x374e4b4 VA: 0x7595d664b4
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x374e548 VA: 0x7595d66548
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x374e54c VA: 0x7595d6654c
	private static Void .cctor() { }
}
```