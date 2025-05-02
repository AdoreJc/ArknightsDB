# NameCardV2ShareEquipInfoItemModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareEquipInfoItemStartLayoutElement m_closure`

- `Boolean isShow`

- `CrossAppShareObjectActiveModel <totalModel>k__BackingField`

- `CrossAppShareTextModel <curCountModel>k__BackingField`

- `CrossAppShareTextModel <totalCountModel>k__BackingField`

- `CrossAppShareTextModel <nameModel>k__BackingField`


## Properties

- `CrossAppShareObjectActiveModel totalModel`

- `CrossAppShareTextModel curCountModel`

- `CrossAppShareTextModel totalCountModel`

- `CrossAppShareTextModel nameModel`


## Methods

- `Void InitCollector(NameCardV2ShareEquipInfoItemStartLayoutElement)`

- `CrossAppShareObjectActiveModel get_totalModel()`

- `Void set_totalModel(CrossAppShareObjectActiveModel)`

- `CrossAppShareTextModel get_curCountModel()`

- `Void set_curCountModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_totalCountModel()`

- `Void set_totalCountModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_nameModel()`

- `Void set_nameModel(CrossAppShareTextModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardV2ShareEquipInfoItemModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareEquipInfoItemStartLayoutElement m_closure; // 0x28
	public Boolean isShow; // 0x30
	private CrossAppShareObjectActiveModel <totalModel>k__BackingField; // 0x38
	private CrossAppShareTextModel <curCountModel>k__BackingField; // 0x40
	private CrossAppShareTextModel <totalCountModel>k__BackingField; // 0x48
	private CrossAppShareTextModel <nameModel>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_InitCollector; // 0x0
	private static DelegateBridge __Hotfix0_get_totalModel; // 0x8
	private static DelegateBridge __Hotfix0_set_totalModel; // 0x10
	private static DelegateBridge __Hotfix0_get_curCountModel; // 0x18
	private static DelegateBridge __Hotfix0_set_curCountModel; // 0x20
	private static DelegateBridge __Hotfix0_get_totalCountModel; // 0x28
	private static DelegateBridge __Hotfix0_set_totalCountModel; // 0x30
	private static DelegateBridge __Hotfix0_get_nameModel; // 0x38
	private static DelegateBridge __Hotfix0_set_nameModel; // 0x40
	private static DelegateBridge __Hotfix0_CollectModel; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public CrossAppShareObjectActiveModel totalModel { get; set; }
	public CrossAppShareTextModel curCountModel { get; set; }
	public CrossAppShareTextModel totalCountModel { get; set; }
	public CrossAppShareTextModel nameModel { get; set; }

	// RVA: 0x28d7ae0 VA: 0x7594eefae0
	public Void InitCollector(NameCardV2ShareEquipInfoItemStartLayoutElement closure) { }
	// RVA: 0x28d779c VA: 0x7594eef79c
	public CrossAppShareObjectActiveModel get_totalModel() { }
	// RVA: 0x28d7c3c VA: 0x7594eefc3c
	private Void set_totalModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d7804 VA: 0x7594eef804
	public CrossAppShareTextModel get_curCountModel() { }
	// RVA: 0x28d7cc0 VA: 0x7594eefcc0
	private Void set_curCountModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d786c VA: 0x7594eef86c
	public CrossAppShareTextModel get_totalCountModel() { }
	// RVA: 0x28d7d44 VA: 0x7594eefd44
	private Void set_totalCountModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d78d4 VA: 0x7594eef8d4
	public CrossAppShareTextModel get_nameModel() { }
	// RVA: 0x28d7dc8 VA: 0x7594eefdc8
	private Void set_nameModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d7e4c VA: 0x7594eefe4c
	public override Void CollectModel() { }
	// RVA: 0x28d7a70 VA: 0x7594eefa70
	public Void .ctor() { }
}
```