# ResourceManifest

**Namespace:** `Torappu.Resource`


## Fields

- `Int32 rawCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class ResourceManifest
{
	public Int32 rawCount; // 0x10
	public List`1 bundles; // 0x18
	public List`1 assetToBundleList; // 0x20
	private Dictionary`2 m_bundleIndexMap; // 0x28

	public static String VERSION { get; }
	public Dictionary`2 bundleIndexMap { get; }

	// RVA: 0x3741bac VA: 0x7595d59bac
	public static String get_VERSION() { }
	// RVA: 0x3741bfc VA: 0x7595d59bfc
	public Dictionary`2 get_bundleIndexMap() { }
	// RVA: 0x3741d28 VA: 0x7595d59d28
	public String[] GetAllAssetBundles() { }
	// RVA: 0x3741e50 VA: 0x7595d59e50
	public String[] GetAllDependencies(String assetBundleName) { }
	// RVA: 0x3742010 VA: 0x7595d5a010
	public Void .ctor() { }
}
```