# CachedAssetLoader

**Namespace:** `Torappu.Resource`


## Methods

- `Void ClearAll(Boolean)`

- `Int32 GetAssetsCountByPathRule(Func`2)`

- `String _GetKeyFromPath(String)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Resource
public class CachedAssetLoader : AbstractAssetLoader
{
	private Dictionary`2 m_cachedAssets; // 0x10
	private Dictionary`2 m_instanceIdToName; // 0x18


	// RVA: 0x6797348 VA: 0x7598daf348
	public override Void ClearAll() { }
	// RVA: 0x6797350 VA: 0x7598daf350
	public Void ClearAll(Boolean unloadUnusedAssets) { }
	// RVA: 0x67975c8 VA: 0x7598daf5c8
	public Int32 GetAssetsCountByPathRule(Func`2 pathChecker) { }
	// RVA: 0x67976b4 VA: 0x7598daf6b4
	protected override Void OnAssetLoaded(String path, Object asset) { }
	// RVA: 0x67978b8 VA: 0x7598daf8b8
	protected override Void OnAssetUnloading(Object asset) { }
	// RVA: 0x67979cc VA: 0x7598daf9cc
	protected override Boolean TryGetAsset(String path, out Object asset) { }
	// RVA: 0x VA: 0x0
	protected override Boolean TryGetAsset(String path, out T asset) { }
	// RVA: 0x6797afc VA: 0x7598dafafc
	protected override Boolean TryGetAssets(String path, out Object[] assets) { }
	// RVA: 0x VA: 0x0
	protected override Boolean TryGetAssets(String path, out T[] assets) { }
	// RVA: 0x67977d4 VA: 0x7598daf7d4
	private HashSet`1 _EnsureCachedAsset(String key) { }
	// RVA: 0x67977bc VA: 0x7598daf7bc
	private String _GetKeyFromPath(String path) { }
	// RVA: 0x6797bd0 VA: 0x7598dafbd0
	public Void .ctor() { }
}
```