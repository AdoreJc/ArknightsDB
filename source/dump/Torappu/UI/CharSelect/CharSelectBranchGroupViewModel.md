# CharSelectBranchGroupViewModel

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `String featureDescBasic`

- `String rawFeatureDesc`

- `String featureDescAdditive`

- `String currentEquipId`

- `Boolean haveAvailEquip`

- `Boolean haveEquip`

- `String subProfessionInfo`


## Methods

- `Sprite GetCurrentEquipIcon()`

- `CharSelectBranchItemViewModel AchieveBranchModelById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectBranchGroupViewModel
{
	public String featureDescBasic; // 0x10
	public String rawFeatureDesc; // 0x18
	public String featureDescAdditive; // 0x20
	public String currentEquipId; // 0x28
	public Boolean haveAvailEquip; // 0x30
	public Boolean haveEquip; // 0x31
	public String subProfessionInfo; // 0x38
	public CharacterTalentViewModel[] talentDescs; // 0x40
	public List`1 branchModels; // 0x48


	// RVA: 0x2cee7d0 VA: 0x75953067d0
	public Sprite GetCurrentEquipIcon() { }
	// RVA: 0x2cee8d4 VA: 0x75953068d4
	public CharSelectBranchItemViewModel AchieveBranchModelById(String branchId) { }
	// RVA: 0x2cee9a0 VA: 0x75953069a0
	public Void .ctor() { }
}
```