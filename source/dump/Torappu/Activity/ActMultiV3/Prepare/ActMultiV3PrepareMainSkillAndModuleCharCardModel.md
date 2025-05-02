# ActMultiV3PrepareMainSkillAndModuleCharCardModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `Int32 <innerInstId>k__BackingField`

- `Param baseViewModel`

- `String <selectedSkillId>k__BackingField`

- `String <selectedEquipId>k__BackingField`


## Properties

- `Int32 innerInstId`

- `String selectedSkillId`

- `String selectedEquipId`

- `Boolean isEmpty`

- `Int32 selectedEquipIndex`


## Methods

- `Int32 get_innerInstId()`

- `Void set_innerInstId(Int32)`

- `String get_selectedSkillId()`

- `Void set_selectedSkillId(String)`

- `String get_selectedEquipId()`

- `Void set_selectedEquipId(String)`

- `Boolean get_isEmpty()`

- `Int32 get_selectedEquipIndex()`

- `Void LoadData(Int32, CharacterCardViewModel, ActMultiV3IdentityType)`

- `Void _LoadSkill(CharacterCardViewModel)`

- `PlayerCharSkill _GetPlayerSkillData(PlayerCharSkill[], String)`

- `Void _LoadEquip(CharacterCardViewModel)`

- `Int32 _GetSelectEquipIndex()`

- `Void UpdateSelectSkill(String)`

- `Void UpdateSelectEquip(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSkillAndModuleCharCardModel : IHotfixable
{
	private Int32 <innerInstId>k__BackingField; // 0x10
	public Param baseViewModel; // 0x18
	public ListDict`2 skills; // 0x20
	public ListDict`2 equips; // 0x28
	private String <selectedSkillId>k__BackingField; // 0x30
	private String <selectedEquipId>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_innerInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_innerInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedSkillId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedSkillId; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedEquipId; // 0x20
	private static DelegateBridge __Hotfix0_set_selectedEquipId; // 0x28
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x30
	private static DelegateBridge __Hotfix0_get_selectedEquipIndex; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__LoadSkill; // 0x48
	private static DelegateBridge __Hotfix0__GetPlayerSkillData; // 0x50
	private static DelegateBridge __Hotfix0__LoadEquip; // 0x58
	private static DelegateBridge __Hotfix0__GetSelectEquipIndex; // 0x60
	private static DelegateBridge __Hotfix0_UpdateSelectSkill; // 0x68
	private static DelegateBridge __Hotfix0_UpdateSelectEquip; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int32 innerInstId { get; set; }
	public String selectedSkillId { get; set; }
	public String selectedEquipId { get; set; }
	public Boolean isEmpty { get; }
	public Int32 selectedEquipIndex { get; }

	// RVA: 0x3160520 VA: 0x7595778520
	public Int32 get_innerInstId() { }
	// RVA: 0x3161314 VA: 0x7595779314
	private Void set_innerInstId(Int32 value) { }
	// RVA: 0x31608f4 VA: 0x75957788f4
	public String get_selectedSkillId() { }
	// RVA: 0x3161390 VA: 0x7595779390
	private Void set_selectedSkillId(String value) { }
	// RVA: 0x316095c VA: 0x759577895c
	public String get_selectedEquipId() { }
	// RVA: 0x3161414 VA: 0x7595779414
	private Void set_selectedEquipId(String value) { }
	// RVA: 0x31604a0 VA: 0x75957784a0
	public Boolean get_isEmpty() { }
	// RVA: 0x31609c4 VA: 0x75957789c4
	public Int32 get_selectedEquipIndex() { }
	// RVA: 0x31615b0 VA: 0x75957795b0
	public Void LoadData(Int32 instId, CharacterCardViewModel cardViewModel, ActMultiV3IdentityType identityType) { }
	// RVA: 0x31616c4 VA: 0x75957796c4
	private Void _LoadSkill(CharacterCardViewModel charModel) { }
	// RVA: 0x3161e6c VA: 0x7595779e6c
	private PlayerCharSkill _GetPlayerSkillData(PlayerCharSkill[] playerSkills, String skillId) { }
	// RVA: 0x3161930 VA: 0x7595779930
	private Void _LoadEquip(CharacterCardViewModel charModel) { }
	// RVA: 0x3161498 VA: 0x7595779498
	private Int32 _GetSelectEquipIndex() { }
	// RVA: 0x3161cd4 VA: 0x7595779cd4
	public Void UpdateSelectSkill(String selectId) { }
	// RVA: 0x3161da0 VA: 0x7595779da0
	public Void UpdateSelectEquip(String selectId) { }
	// RVA: 0x3161fec VA: 0x7595779fec
	public Void .ctor() { }
}
```