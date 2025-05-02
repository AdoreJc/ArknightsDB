# RoguelikeCharSelectBranchGroupViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String featureDescBasic`

- `String rawFeatureDesc`

- `String featureDescAdditive`

- `String m_currentEquipId`

- `String defaultEquipId`

- `Boolean haveAvailEquip`

- `Boolean haveEquip`

- `Boolean havePlayerEquipUnlocked`

- `Boolean ableToSelect`

- `String subProfessionInfo`


## Properties

- `String currentEquipId`


## Methods

- `String get_currentEquipId()`

- `Void SetEquipId(String, String)`

- `Sprite GetCurrentEquipIcon()`

- `Int32 GetEquipLevelById(String)`

- `RoguelikeCharSelectBranchItemViewModel AchieveBranchModelById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectBranchGroupViewModel : IHotfixable
{
	public String featureDescBasic; // 0x10
	public String rawFeatureDesc; // 0x18
	public String featureDescAdditive; // 0x20
	private String m_currentEquipId; // 0x28
	public String defaultEquipId; // 0x30
	public Boolean haveAvailEquip; // 0x38
	public Boolean haveEquip; // 0x39
	public Boolean havePlayerEquipUnlocked; // 0x3a
	public Boolean ableToSelect; // 0x3b
	public String subProfessionInfo; // 0x40
	public RoguelikeTalentViewModel[] talentDescs; // 0x48
	public List`1 branchModels; // 0x50
	private static DelegateBridge __Hotfix0_get_currentEquipId; // 0x0
	private static DelegateBridge __Hotfix0_SetEquipId; // 0x8
	private static DelegateBridge __Hotfix0_GetCurrentEquipIcon; // 0x10
	private static DelegateBridge __Hotfix0_GetEquipLevelById; // 0x18
	private static DelegateBridge __Hotfix0_AchieveBranchModelById; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String currentEquipId { get; }

	// RVA: 0x2aca77c VA: 0x75950e277c
	public String get_currentEquipId() { }
	// RVA: 0x2ad143c VA: 0x75950e943c
	public Void SetEquipId(String i_equipId, String i_defaultEquipId) { }
	// RVA: 0x2ad1520 VA: 0x75950e9520
	public Sprite GetCurrentEquipIcon() { }
	// RVA: 0x2ad1680 VA: 0x75950e9680
	public Int32 GetEquipLevelById(String equipId) { }
	// RVA: 0x2ad1794 VA: 0x75950e9794
	public RoguelikeCharSelectBranchItemViewModel AchieveBranchModelById(String branchId) { }
	// RVA: 0x2ad18a4 VA: 0x75950e98a4
	public Void .ctor() { }
}
```