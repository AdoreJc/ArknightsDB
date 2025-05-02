# SandboxV2BasementUpgradeFuncGroupAdapter

**Namespace:** ` `


## Fields

- `ILoadAsset <assetLoader>k__BackingField`


## Properties

- `ILoadAsset assetLoader`


## Methods

- `Void set_dataSet(List`1)`

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxV2BasementUpgradeFuncGroupAdapter : SimpleLayoutAdapter
{
	private List`1 <dataSet>k__BackingField; // 0x20
	private ILoadAsset <assetLoader>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x10
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x18
	private static DelegateBridge __Hotfix0_get_count; // 0x20
	private static DelegateBridge __Hotfix0_RenderView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 dataSet { get; set; }
	public ILoadAsset assetLoader { get; set; }
	public override Int32 count { get; }

	// RVA: 0x2510670 VA: 0x7594b28670
	public List`1 get_dataSet() { }
	// RVA: 0x25102a4 VA: 0x7594b282a4
	public Void set_dataSet(List`1 value) { }
	// RVA: 0x25106d8 VA: 0x7594b286d8
	public ILoadAsset get_assetLoader() { }
	// RVA: 0x250fd98 VA: 0x7594b27d98
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x2510740 VA: 0x7594b28740
	public override Int32 get_count() { }
	// RVA: 0x25107c4 VA: 0x7594b287c4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x250fd28 VA: 0x7594b27d28
	public Void .ctor() { }
}
```