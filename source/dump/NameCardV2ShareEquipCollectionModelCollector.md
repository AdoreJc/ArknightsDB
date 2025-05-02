# NameCardV2ShareEquipCollectionModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareEquipCollectionStartLayoutElement m_closure`

- `CrossAppShareImageModel <bgRectModel>k__BackingField`

- `CrossAppShareImageModel <bgIconModel>k__BackingField`

- `CrossAppShareLayoutContentModel <infoItemModel>k__BackingField`


## Properties

- `CrossAppShareImageModel bgRectModel`

- `CrossAppShareImageModel bgIconModel`

- `CrossAppShareLayoutContentModel infoItemModel`


## Methods

- `Void InitCollector(NameCardV2ShareEquipCollectionStartLayoutElement)`

- `CrossAppShareImageModel get_bgRectModel()`

- `Void set_bgRectModel(CrossAppShareImageModel)`

- `CrossAppShareImageModel get_bgIconModel()`

- `Void set_bgIconModel(CrossAppShareImageModel)`

- `CrossAppShareLayoutContentModel get_infoItemModel()`

- `Void set_infoItemModel(CrossAppShareLayoutContentModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardV2ShareEquipCollectionModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareEquipCollectionStartLayoutElement m_closure; // 0x28
	private CrossAppShareImageModel <bgRectModel>k__BackingField; // 0x30
	private CrossAppShareImageModel <bgIconModel>k__BackingField; // 0x38
	private CrossAppShareLayoutContentModel <infoItemModel>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_InitCollector; // 0x0
	private static DelegateBridge __Hotfix0_get_bgRectModel; // 0x8
	private static DelegateBridge __Hotfix0_set_bgRectModel; // 0x10
	private static DelegateBridge __Hotfix0_get_bgIconModel; // 0x18
	private static DelegateBridge __Hotfix0_set_bgIconModel; // 0x20
	private static DelegateBridge __Hotfix0_get_infoItemModel; // 0x28
	private static DelegateBridge __Hotfix0_set_infoItemModel; // 0x30
	private static DelegateBridge __Hotfix0_CollectModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public CrossAppShareImageModel bgRectModel { get; set; }
	public CrossAppShareImageModel bgIconModel { get; set; }
	public CrossAppShareLayoutContentModel infoItemModel { get; set; }

	// RVA: 0x28d71f4 VA: 0x7594eef1f4
	public Void InitCollector(NameCardV2ShareEquipCollectionStartLayoutElement closure) { }
	// RVA: 0x28d6f2c VA: 0x7594eeef2c
	public CrossAppShareImageModel get_bgRectModel() { }
	// RVA: 0x28d72e8 VA: 0x7594eef2e8
	private Void set_bgRectModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d6f94 VA: 0x7594eeef94
	public CrossAppShareImageModel get_bgIconModel() { }
	// RVA: 0x28d736c VA: 0x7594eef36c
	private Void set_bgIconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d6ffc VA: 0x7594eeeffc
	public CrossAppShareLayoutContentModel get_infoItemModel() { }
	// RVA: 0x28d73f0 VA: 0x7594eef3f0
	private Void set_infoItemModel(CrossAppShareLayoutContentModel value) { }
	// RVA: 0x28d7474 VA: 0x7594eef474
	public override Void CollectModel() { }
	// RVA: 0x28d7184 VA: 0x7594eef184
	public Void .ctor() { }
}
```