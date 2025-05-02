# SandboxV2CharViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `BasicCharInfoModel m_basicInfoModel`

- `String topicId`

- `Int32 instId`

- `Boolean isInited`

- `Boolean ifFetchPlayerData`

- `String selectedSkillId`

- `String cacheCurrentEquipId`

- `String cacheTmplId`

- `Boolean isFocused`

- `Int32 selectIndex`

- `Int32 expedtionRemainTime`

- `Boolean showIndex`

- `Int32 logisticsBeanCount`

- `Color <rarityColor>k__BackingField`

- `SandboxV2CharFoodModel foodGroupViewModel`

- `CharSelectSkillGroupViewModel skillGroupViewModel`

- `CharSelectBranchGroupViewModel branchGroupViewModel`

- `AttackRangeDescModel attackRange`

- `SandboxV2CharStatus charStatus`


## Properties

- `Color rarityColor`

- `BasicCharInfoModel basicCharInfo`

- `String currentEquipId`


## Methods

- `Color get_rarityColor()`

- `Void set_rarityColor(Color)`

- `BasicCharInfoModel get_basicCharInfo()`

- `String get_currentEquipId()`

- `Void ApplyCharSelect(SandboxV2CharSquad)`

- `Void ApplySkillSelect(String)`

- `Void ApplyEquipId(String)`

- `Void InitSelectPartIfNot()`

- `Void UpdatePlayerData(Boolean)`

- `Void _UpdatePlayerData(PlayerSandboxV2, PlayerCharacter, CharacterData)`

- `Void _UpdateFoodModel(PlayerSandboxV2)`

- `Void _InitLogisticsRelatedData(String, CharacterData, PlayerCharacter)`

- `Int32 CompareTo(SandboxV2CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharViewModel : IBasicCharInfo, IHotfixable, IComparable`1
{
	private BasicCharInfoModel m_basicInfoModel; // 0x10
	public String topicId; // 0x18
	public Int32 instId; // 0x20
	public Boolean isInited; // 0x24
	public Boolean ifFetchPlayerData; // 0x25
	public String selectedSkillId; // 0x28
	public String cacheCurrentEquipId; // 0x30
	public String cacheTmplId; // 0x38
	public Boolean isFocused; // 0x40
	public Int32 selectIndex; // 0x44
	public Int32 expedtionRemainTime; // 0x48
	public Boolean showIndex; // 0x4c
	public Int32 logisticsBeanCount; // 0x50
	private Color <rarityColor>k__BackingField; // 0x54
	public SandboxV2CharFoodModel foodGroupViewModel; // 0x68
	public CharSelectSkillGroupViewModel skillGroupViewModel; // 0x70
	public CharSelectBranchGroupViewModel branchGroupViewModel; // 0x78
	public AttackRangeDescModel attackRange; // 0x80
	public SandboxV2CharStatus charStatus; // 0x90
	private static DelegateBridge __Hotfix0_get_rarityColor; // 0x0
	private static DelegateBridge __Hotfix0_set_rarityColor; // 0x8
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0x10
	private static DelegateBridge __Hotfix0_get_currentEquipId; // 0x18
	private static DelegateBridge __Hotfix0_ApplyCharSelect; // 0x20
	private static DelegateBridge __Hotfix0_ApplySkillSelect; // 0x28
	private static DelegateBridge __Hotfix0_ApplyEquipId; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38
	private static DelegateBridge __Hotfix0_InitSelectPartIfNot; // 0x40
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x48
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x50
	private static DelegateBridge __Hotfix0__UpdateFoodModel; // 0x58
	private static DelegateBridge __Hotfix0__InitLogisticsRelatedData; // 0x60
	private static DelegateBridge __Hotfix0_CompareTo; // 0x68

	public Color rarityColor { get; set; }
	public BasicCharInfoModel basicCharInfo { get; }
	public String currentEquipId { get; }

	// RVA: 0x24b40f4 VA: 0x7594acc0f4
	public Color get_rarityColor() { }
	// RVA: 0x24b415c VA: 0x7594acc15c
	private Void set_rarityColor(Color value) { }
	// RVA: 0x24ad328 VA: 0x7594ac5328
	public BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x24b3220 VA: 0x7594acb220
	public String get_currentEquipId() { }
	// RVA: 0x24b2518 VA: 0x7594aca518
	public Void ApplyCharSelect(SandboxV2CharSquad charSquad) { }
	// RVA: 0x24b3c3c VA: 0x7594acbc3c
	public Void ApplySkillSelect(String selectSkill) { }
	// RVA: 0x24b3ce4 VA: 0x7594acbce4
	public Void ApplyEquipId(String equipId) { }
	// RVA: 0x24b2104 VA: 0x7594aca104
	public Void .ctor(String topicId, PlayerCharacter playerChar) { }
	// RVA: 0x24b13a4 VA: 0x7594ac93a4
	public Void InitSelectPartIfNot() { }
	// RVA: 0x24b3704 VA: 0x7594acb704
	public Void UpdatePlayerData(Boolean skipLoadSkillIcon) { }
	// RVA: 0x24b4340 VA: 0x7594acc340
	private Void _UpdatePlayerData(PlayerSandboxV2 playerSandboxV2, PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x24b4760 VA: 0x7594acc760
	private Void _UpdateFoodModel(PlayerSandboxV2 playerSandbox) { }
	// RVA: 0x24b4200 VA: 0x7594acc200
	private Void _InitLogisticsRelatedData(String topicId, CharacterData characterData, PlayerCharacter playerChar) { }
	// RVA: 0x24b4874 VA: 0x7594acc874
	public Int32 CompareTo(SandboxV2CharViewModel obj) { }
}
```