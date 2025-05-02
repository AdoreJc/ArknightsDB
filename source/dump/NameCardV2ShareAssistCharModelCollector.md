# NameCardV2ShareAssistCharModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareAssistCharStartLayoutElement m_closure`

- `Boolean isShow`

- `CrossAppShareObjectActiveModel <charEmptyModel>k__BackingField`

- `CrossAppShareObjectActiveModel <charObjectModel>k__BackingField`

- `CrossAppShareImageModel <charEliteIconModel>k__BackingField`

- `CrossAppShareObjectActiveModel <charSpecMaxPartModel>k__BackingField`

- `CrossAppShareUIAtlasImageModel <charPortraitModel>k__BackingField`

- `CrossAppShareTextModel <charLevelModel>k__BackingField`

- `CrossAppShareImageModel <charPotentialIconModel>k__BackingField`

- `CrossAppShareImageModel <charSkillIconModel>k__BackingField`

- `CrossAppShareImageModel <charEquipIconModel>k__BackingField`

- `CrossAppShareObjectActiveModel <charHaveEquipObjectModel>k__BackingField`

- `CrossAppShareObjectActiveModel <charNoEquipObjectModel>k__BackingField`


## Properties

- `CrossAppShareObjectActiveModel charEmptyModel`

- `CrossAppShareObjectActiveModel charObjectModel`

- `CrossAppShareImageModel charEliteIconModel`

- `CrossAppShareObjectActiveModel charSpecMaxPartModel`

- `CrossAppShareUIAtlasImageModel charPortraitModel`

- `CrossAppShareTextModel charLevelModel`

- `CrossAppShareImageModel charPotentialIconModel`

- `CrossAppShareImageModel charSkillIconModel`

- `CrossAppShareImageModel charEquipIconModel`

- `CrossAppShareObjectActiveModel charHaveEquipObjectModel`

- `CrossAppShareObjectActiveModel charNoEquipObjectModel`


## Methods

- `Void InitCollector(NameCardV2ShareAssistCharStartLayoutElement)`

- `CrossAppShareObjectActiveModel get_charEmptyModel()`

- `Void set_charEmptyModel(CrossAppShareObjectActiveModel)`

- `CrossAppShareObjectActiveModel get_charObjectModel()`

- `Void set_charObjectModel(CrossAppShareObjectActiveModel)`

- `CrossAppShareImageModel get_charEliteIconModel()`

- `Void set_charEliteIconModel(CrossAppShareImageModel)`

- `CrossAppShareObjectActiveModel get_charSpecMaxPartModel()`

- `Void set_charSpecMaxPartModel(CrossAppShareObjectActiveModel)`

- `CrossAppShareUIAtlasImageModel get_charPortraitModel()`

- `Void set_charPortraitModel(CrossAppShareUIAtlasImageModel)`

- `CrossAppShareTextModel get_charLevelModel()`

- `Void set_charLevelModel(CrossAppShareTextModel)`

- `CrossAppShareImageModel get_charPotentialIconModel()`

- `Void set_charPotentialIconModel(CrossAppShareImageModel)`

- `CrossAppShareImageModel get_charSkillIconModel()`

- `Void set_charSkillIconModel(CrossAppShareImageModel)`

- `CrossAppShareImageModel get_charEquipIconModel()`

- `Void set_charEquipIconModel(CrossAppShareImageModel)`

- `CrossAppShareObjectActiveModel get_charHaveEquipObjectModel()`

- `Void set_charHaveEquipObjectModel(CrossAppShareObjectActiveModel)`

- `CrossAppShareObjectActiveModel get_charNoEquipObjectModel()`

- `Void set_charNoEquipObjectModel(CrossAppShareObjectActiveModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardV2ShareAssistCharModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareAssistCharStartLayoutElement m_closure; // 0x28
	public Boolean isShow; // 0x30
	private CrossAppShareObjectActiveModel <charEmptyModel>k__BackingField; // 0x38
	private CrossAppShareObjectActiveModel <charObjectModel>k__BackingField; // 0x40
	private CrossAppShareImageModel <charEliteIconModel>k__BackingField; // 0x48
	private CrossAppShareObjectActiveModel <charSpecMaxPartModel>k__BackingField; // 0x50
	private CrossAppShareUIAtlasImageModel <charPortraitModel>k__BackingField; // 0x58
	private CrossAppShareTextModel <charLevelModel>k__BackingField; // 0x60
	private CrossAppShareImageModel <charPotentialIconModel>k__BackingField; // 0x68
	private CrossAppShareImageModel <charSkillIconModel>k__BackingField; // 0x70
	private CrossAppShareImageModel <charEquipIconModel>k__BackingField; // 0x78
	private CrossAppShareObjectActiveModel <charHaveEquipObjectModel>k__BackingField; // 0x80
	private CrossAppShareObjectActiveModel <charNoEquipObjectModel>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_InitCollector; // 0x0
	private static DelegateBridge __Hotfix0_get_charEmptyModel; // 0x8
	private static DelegateBridge __Hotfix0_set_charEmptyModel; // 0x10
	private static DelegateBridge __Hotfix0_get_charObjectModel; // 0x18
	private static DelegateBridge __Hotfix0_set_charObjectModel; // 0x20
	private static DelegateBridge __Hotfix0_get_charEliteIconModel; // 0x28
	private static DelegateBridge __Hotfix0_set_charEliteIconModel; // 0x30
	private static DelegateBridge __Hotfix0_get_charSpecMaxPartModel; // 0x38
	private static DelegateBridge __Hotfix0_set_charSpecMaxPartModel; // 0x40
	private static DelegateBridge __Hotfix0_get_charPortraitModel; // 0x48
	private static DelegateBridge __Hotfix0_set_charPortraitModel; // 0x50
	private static DelegateBridge __Hotfix0_get_charLevelModel; // 0x58
	private static DelegateBridge __Hotfix0_set_charLevelModel; // 0x60
	private static DelegateBridge __Hotfix0_get_charPotentialIconModel; // 0x68
	private static DelegateBridge __Hotfix0_set_charPotentialIconModel; // 0x70
	private static DelegateBridge __Hotfix0_get_charSkillIconModel; // 0x78
	private static DelegateBridge __Hotfix0_set_charSkillIconModel; // 0x80
	private static DelegateBridge __Hotfix0_get_charEquipIconModel; // 0x88
	private static DelegateBridge __Hotfix0_set_charEquipIconModel; // 0x90
	private static DelegateBridge __Hotfix0_get_charHaveEquipObjectModel; // 0x98
	private static DelegateBridge __Hotfix0_set_charHaveEquipObjectModel; // 0xa0
	private static DelegateBridge __Hotfix0_get_charNoEquipObjectModel; // 0xa8
	private static DelegateBridge __Hotfix0_set_charNoEquipObjectModel; // 0xb0
	private static DelegateBridge __Hotfix0_CollectModel; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public CrossAppShareObjectActiveModel charEmptyModel { get; set; }
	public CrossAppShareObjectActiveModel charObjectModel { get; set; }
	public CrossAppShareImageModel charEliteIconModel { get; set; }
	public CrossAppShareObjectActiveModel charSpecMaxPartModel { get; set; }
	public CrossAppShareUIAtlasImageModel charPortraitModel { get; set; }
	public CrossAppShareTextModel charLevelModel { get; set; }
	public CrossAppShareImageModel charPotentialIconModel { get; set; }
	public CrossAppShareImageModel charSkillIconModel { get; set; }
	public CrossAppShareImageModel charEquipIconModel { get; set; }
	public CrossAppShareObjectActiveModel charHaveEquipObjectModel { get; set; }
	public CrossAppShareObjectActiveModel charNoEquipObjectModel { get; set; }

	// RVA: 0x28d1a1c VA: 0x7594ee9a1c
	public Void InitCollector(NameCardV2ShareAssistCharStartLayoutElement closure) { }
	// RVA: 0x28d13fc VA: 0x7594ee93fc
	public CrossAppShareObjectActiveModel get_charEmptyModel() { }
	// RVA: 0x28d1b10 VA: 0x7594ee9b10
	private Void set_charEmptyModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d1464 VA: 0x7594ee9464
	public CrossAppShareObjectActiveModel get_charObjectModel() { }
	// RVA: 0x28d1b94 VA: 0x7594ee9b94
	private Void set_charObjectModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d14cc VA: 0x7594ee94cc
	public CrossAppShareImageModel get_charEliteIconModel() { }
	// RVA: 0x28d1c18 VA: 0x7594ee9c18
	private Void set_charEliteIconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d1534 VA: 0x7594ee9534
	public CrossAppShareObjectActiveModel get_charSpecMaxPartModel() { }
	// RVA: 0x28d1c9c VA: 0x7594ee9c9c
	private Void set_charSpecMaxPartModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d159c VA: 0x7594ee959c
	public CrossAppShareUIAtlasImageModel get_charPortraitModel() { }
	// RVA: 0x28d1d20 VA: 0x7594ee9d20
	private Void set_charPortraitModel(CrossAppShareUIAtlasImageModel value) { }
	// RVA: 0x28d1604 VA: 0x7594ee9604
	public CrossAppShareTextModel get_charLevelModel() { }
	// RVA: 0x28d1da4 VA: 0x7594ee9da4
	private Void set_charLevelModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d166c VA: 0x7594ee966c
	public CrossAppShareImageModel get_charPotentialIconModel() { }
	// RVA: 0x28d1e28 VA: 0x7594ee9e28
	private Void set_charPotentialIconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d16d4 VA: 0x7594ee96d4
	public CrossAppShareImageModel get_charSkillIconModel() { }
	// RVA: 0x28d1eac VA: 0x7594ee9eac
	private Void set_charSkillIconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d173c VA: 0x7594ee973c
	public CrossAppShareImageModel get_charEquipIconModel() { }
	// RVA: 0x28d1f30 VA: 0x7594ee9f30
	private Void set_charEquipIconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d17a4 VA: 0x7594ee97a4
	public CrossAppShareObjectActiveModel get_charHaveEquipObjectModel() { }
	// RVA: 0x28d1fb4 VA: 0x7594ee9fb4
	private Void set_charHaveEquipObjectModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d180c VA: 0x7594ee980c
	public CrossAppShareObjectActiveModel get_charNoEquipObjectModel() { }
	// RVA: 0x28d2038 VA: 0x7594eea038
	private Void set_charNoEquipObjectModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d20bc VA: 0x7594eea0bc
	public override Void CollectModel() { }
	// RVA: 0x28d19ac VA: 0x7594ee99ac
	public Void .ctor() { }
}
```