# SandboxV2BasementUpgradeItemAdapter

**Namespace:** ` `


## Fields

- `ILoadAsset <assetLoader>k__BackingField`

- `String <topicId>k__BackingField`

- `Single <scaler>k__BackingField`


## Properties

- `ILoadAsset assetLoader`

- `String topicId`

- `Single scaler`


## Methods

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `Single get_scaler()`

- `Void set_scaler(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxV2BasementUpgradeItemAdapter : SimpleLayoutAdapter
{
	public List`1 dataSet; // 0x20
	public Action`1 onItemClick; // 0x28
	private ILoadAsset <assetLoader>k__BackingField; // 0x30
	private String <topicId>k__BackingField; // 0x38
	private Single <scaler>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x8
	private static DelegateBridge __Hotfix0_get_topicId; // 0x10
	private static DelegateBridge __Hotfix0_set_topicId; // 0x18
	private static DelegateBridge __Hotfix0_get_count; // 0x20
	private static DelegateBridge __Hotfix0_get_scaler; // 0x28
	private static DelegateBridge __Hotfix0_set_scaler; // 0x30
	private static DelegateBridge __Hotfix0_RenderView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public ILoadAsset assetLoader { get; set; }
	public String topicId { get; set; }
	public override Int32 count { get; }
	public Single scaler { get; set; }

	// RVA: 0x2510988 VA: 0x7594b28988
	public ILoadAsset get_assetLoader() { }
	// RVA: 0x250ff08 VA: 0x7594b27f08
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x25109f0 VA: 0x7594b289f0
	public String get_topicId() { }
	// RVA: 0x250ff8c VA: 0x7594b27f8c
	public Void set_topicId(String value) { }
	// RVA: 0x2510a58 VA: 0x7594b28a58
	public override Int32 get_count() { }
	// RVA: 0x2510ad8 VA: 0x7594b28ad8
	public Single get_scaler() { }
	// RVA: 0x250fe8c VA: 0x7594b27e8c
	public Void set_scaler(Single value) { }
	// RVA: 0x2510b40 VA: 0x7594b28b40
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x250fe1c VA: 0x7594b27e1c
	public Void .ctor() { }
}
```