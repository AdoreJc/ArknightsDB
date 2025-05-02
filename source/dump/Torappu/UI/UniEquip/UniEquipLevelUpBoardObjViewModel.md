# UniEquipLevelUpBoardObjViewModel

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Int32 <equipLevel>k__BackingField`

- `Boolean <isIncludedInLevelUp>k__BackingField`

- `Boolean <isLastTargetLevel>k__BackingField`

- `Boolean <isCurLevel>k__BackingField`

- `UniEquipNormalInfoViewModel basicInfoViewModel`

- `UniEquipSubProfessionViewModel subProfessionViewModel`

- `UniEquipNormalInfoViewModel talentViewModel`


## Properties

- `Int32 equipLevel`

- `Boolean isIncludedInLevelUp`

- `Boolean isLastTargetLevel`

- `Boolean isCurLevel`


## Methods

- `Void set_equipLevel(Int32)`

- `Int32 get_equipLevel()`

- `Void set_isIncludedInLevelUp(Boolean)`

- `Boolean get_isIncludedInLevelUp()`

- `Void set_isLastTargetLevel(Boolean)`

- `Boolean get_isLastTargetLevel()`

- `Void set_isCurLevel(Boolean)`

- `Boolean get_isCurLevel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpBoardObjViewModel : IHotfixable
{
	private Int32 <equipLevel>k__BackingField; // 0x10
	private Boolean <isIncludedInLevelUp>k__BackingField; // 0x14
	private Boolean <isLastTargetLevel>k__BackingField; // 0x15
	private Boolean <isCurLevel>k__BackingField; // 0x16
	public UniEquipNormalInfoViewModel basicInfoViewModel; // 0x18
	public UniEquipSubProfessionViewModel subProfessionViewModel; // 0x30
	public UniEquipNormalInfoViewModel talentViewModel; // 0x68
	private static DelegateBridge __Hotfix0_set_equipLevel; // 0x0
	private static DelegateBridge __Hotfix0_get_equipLevel; // 0x8
	private static DelegateBridge __Hotfix0_set_isIncludedInLevelUp; // 0x10
	private static DelegateBridge __Hotfix0_get_isIncludedInLevelUp; // 0x18
	private static DelegateBridge __Hotfix0_set_isLastTargetLevel; // 0x20
	private static DelegateBridge __Hotfix0_get_isLastTargetLevel; // 0x28
	private static DelegateBridge __Hotfix0_set_isCurLevel; // 0x30
	private static DelegateBridge __Hotfix0_get_isCurLevel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 equipLevel { get; set; }
	public Boolean isIncludedInLevelUp { get; set; }
	public Boolean isLastTargetLevel { get; set; }
	public Boolean isCurLevel { get; set; }

	// RVA: 0x2309464 VA: 0x7594921464
	private Void set_equipLevel(Int32 value) { }
	// RVA: 0x2308f0c VA: 0x7594920f0c
	public Int32 get_equipLevel() { }
	// RVA: 0x23094e0 VA: 0x75949214e0
	private Void set_isIncludedInLevelUp(Boolean value) { }
	// RVA: 0x2309560 VA: 0x7594921560
	public Boolean get_isIncludedInLevelUp() { }
	// RVA: 0x23095c8 VA: 0x75949215c8
	private Void set_isLastTargetLevel(Boolean value) { }
	// RVA: 0x2309648 VA: 0x7594921648
	public Boolean get_isLastTargetLevel() { }
	// RVA: 0x23096b0 VA: 0x75949216b0
	private Void set_isCurLevel(Boolean value) { }
	// RVA: 0x2309730 VA: 0x7594921730
	public Boolean get_isCurLevel() { }
	// RVA: 0x2306fd4 VA: 0x759491efd4
	public Void .ctor(Int32 equipLevel, Int32 curLevel, Int32 tarLevel) { }
}
```