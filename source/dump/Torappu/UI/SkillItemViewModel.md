# SkillItemViewModel

**Namespace:** `Torappu.UI`


## Fields

- `String id`

- `String name`

- `Int32 spCost`

- `Int32 initCost`

- `Int32 specLevel`

- `Boolean isUnlocked`

- `String desc`

- `String rawDesc`

- `String initialUnlockCond`

- `EvolvePhase initialUnlockPhase`

- `Int32 skillAllLevel`

- `Int32 specializedState`

- `Boolean ableToSpec`

- `Int32 trainingSlotLevel`

- `String tokenKey`

- `Boolean isSkillHideOnUI`

- `Sprite <skillIcon>k__BackingField`


## Properties

- `Sprite skillIcon`


## Methods

- `Sprite get_skillIcon()`

- `Void set_skillIcon(Sprite)`

- `Void FillGameData(SkillData, Boolean)`

- `SkillItemViewModel UplevelGameData()`

- `String GetCantSpecializeReason()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SkillItemViewModel
{
	public String id; // 0x10
	public String name; // 0x18
	public Int32 spCost; // 0x20
	public Int32 initCost; // 0x24
	public Int32 specLevel; // 0x28
	public Boolean isUnlocked; // 0x2c
	public List`1 tags; // 0x30
	public String desc; // 0x38
	public String rawDesc; // 0x40
	public String initialUnlockCond; // 0x48
	public EvolvePhase initialUnlockPhase; // 0x50
	public Int32 skillAllLevel; // 0x54
	public Int32 specializedState; // 0x58
	public Boolean ableToSpec; // 0x5c
	public Int32 trainingSlotLevel; // 0x60
	public String tokenKey; // 0x68
	public Boolean isSkillHideOnUI; // 0x70
	private Sprite <skillIcon>k__BackingField; // 0x78

	public Sprite skillIcon { get; set; }

	// RVA: 0x21976b4 VA: 0x75947af6b4
	public Sprite get_skillIcon() { }
	// RVA: 0x21976bc VA: 0x75947af6bc
	private Void set_skillIcon(Sprite value) { }
	// RVA: 0x21976c4 VA: 0x75947af6c4
	public Void FillGameData(SkillData skillData, Boolean skipIconLoad) { }
	// RVA: 0x219789c VA: 0x75947af89c
	public SkillItemViewModel UplevelGameData() { }
	// RVA: 0x2197974 VA: 0x75947af974
	public String GetCantSpecializeReason() { }
	// RVA: 0x219796c VA: 0x75947af96c
	public Void .ctor() { }
}
```