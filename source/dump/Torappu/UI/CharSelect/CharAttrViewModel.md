# CharAttrViewModel

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `Boolean isFocused`

- `BasicCharInfoModel basicInfo`

- `String nickName`

- `AttackRangeDescModel attackRange`

- `CharSelectSkillGroupViewModel skillGroupModel`

- `CharSelectBranchGroupViewModel branchModel`

- `Boolean <showCharInfoEntry>k__BackingField`

- `Boolean <showPredefinedCharInfo>k__BackingField`

- `CharAttrTabType attryTabType`


## Properties

- `Int32 chrInstId`

- `String realName`

- `Int32 currentLevel`

- `Int32 maxLevel`

- `Int32 maxHp`

- `Int32 atk`

- `Int32 def`

- `Int32 res`

- `String respawnTimeDesc`

- `Int32 cost`

- `Int32 blockNum`

- `String attackSpeedDesc`

- `Boolean showCharInfoEntry`

- `Boolean showPredefinedCharInfo`


## Methods

- `Int32 get_chrInstId()`

- `String get_realName()`

- `Int32 get_currentLevel()`

- `Int32 get_maxLevel()`

- `Int32 get_maxHp()`

- `Int32 get_atk()`

- `Int32 get_def()`

- `Int32 get_res()`

- `String get_respawnTimeDesc()`

- `Int32 get_cost()`

- `Int32 get_blockNum()`

- `String get_attackSpeedDesc()`

- `Boolean get_showCharInfoEntry()`

- `Void set_showCharInfoEntry(Boolean)`

- `Boolean get_showPredefinedCharInfo()`

- `Void set_showPredefinedCharInfo(Boolean)`

- `Void LoadAttrByInstId(Int32, String, String, IPlugin)`

- `Void LoadAttrByCardViewModel(PredefinedCharStruct, String)`

- `Void ReloadAttrByEquipChange(String)`

- `Void _LoadUniqEquip(CharacterData, CharQuery, EvolvePhase, Int32, Int32, String, ListDict`2)`

- `Void _LoadAttrWithEquipInternal(CharacterData, CharQuery, EvolvePhase, Int32, Int32, Int32, String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharAttrViewModel : IHotfixable
{
	public Boolean isFocused; // 0x10
	public BasicCharInfoModel basicInfo; // 0x18
	public String nickName; // 0x20
	public AttackRangeDescModel attackRange; // 0x28
	public CharSelectSkillGroupViewModel skillGroupModel; // 0x38
	public CharSelectBranchGroupViewModel branchModel; // 0x40
	private Boolean <showCharInfoEntry>k__BackingField; // 0x48
	private Boolean <showPredefinedCharInfo>k__BackingField; // 0x49
	public CharAttrTabType attryTabType; // 0x4c
	private static DelegateBridge __Hotfix0_get_chrInstId; // 0x0
	private static DelegateBridge __Hotfix0_get_realName; // 0x8
	private static DelegateBridge __Hotfix0_get_currentLevel; // 0x10
	private static DelegateBridge __Hotfix0_get_maxLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_maxHp; // 0x20
	private static DelegateBridge __Hotfix0_get_atk; // 0x28
	private static DelegateBridge __Hotfix0_get_def; // 0x30
	private static DelegateBridge __Hotfix0_get_res; // 0x38
	private static DelegateBridge __Hotfix0_get_respawnTimeDesc; // 0x40
	private static DelegateBridge __Hotfix0_get_cost; // 0x48
	private static DelegateBridge __Hotfix0_get_blockNum; // 0x50
	private static DelegateBridge __Hotfix0_get_attackSpeedDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_showCharInfoEntry; // 0x60
	private static DelegateBridge __Hotfix0_set_showCharInfoEntry; // 0x68
	private static DelegateBridge __Hotfix0_get_showPredefinedCharInfo; // 0x70
	private static DelegateBridge __Hotfix0_set_showPredefinedCharInfo; // 0x78
	private static DelegateBridge __Hotfix0_LoadAttrByInstId; // 0x80
	private static DelegateBridge __Hotfix0_LoadAttrByCardViewModel; // 0x88
	private static DelegateBridge __Hotfix0_ReloadAttrByEquipChange; // 0x90
	private static DelegateBridge __Hotfix0__LoadUniqEquip; // 0x98
	private static DelegateBridge __Hotfix0__GenTalentGroup; // 0xa0
	private static DelegateBridge __Hotfix0__LoadAttrWithEquipInternal; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Int32 chrInstId { get; }
	public String realName { get; }
	public Int32 currentLevel { get; }
	public Int32 maxLevel { get; }
	public Int32 maxHp { get; }
	public Int32 atk { get; }
	public Int32 def { get; }
	public Int32 res { get; }
	public String respawnTimeDesc { get; }
	public Int32 cost { get; }
	public Int32 blockNum { get; }
	public String attackSpeedDesc { get; }
	public Boolean showCharInfoEntry { get; set; }
	public Boolean showPredefinedCharInfo { get; set; }

	// RVA: 0x2ceeb18 VA: 0x7595306b18
	public Int32 get_chrInstId() { }
	// RVA: 0x2ceeb8c VA: 0x7595306b8c
	public String get_realName() { }
	// RVA: 0x2ceec00 VA: 0x7595306c00
	public Int32 get_currentLevel() { }
	// RVA: 0x2ceec74 VA: 0x7595306c74
	public Int32 get_maxLevel() { }
	// RVA: 0x2ceece8 VA: 0x7595306ce8
	public Int32 get_maxHp() { }
	// RVA: 0x2ceed5c VA: 0x7595306d5c
	public Int32 get_atk() { }
	// RVA: 0x2ceedd0 VA: 0x7595306dd0
	public Int32 get_def() { }
	// RVA: 0x2ceee44 VA: 0x7595306e44
	public Int32 get_res() { }
	// RVA: 0x2ceeed4 VA: 0x7595306ed4
	public String get_respawnTimeDesc() { }
	// RVA: 0x2ceef50 VA: 0x7595306f50
	public Int32 get_cost() { }
	// RVA: 0x2ceefc4 VA: 0x7595306fc4
	public Int32 get_blockNum() { }
	// RVA: 0x2cef038 VA: 0x7595307038
	public String get_attackSpeedDesc() { }
	// RVA: 0x2cef0b4 VA: 0x75953070b4
	public Boolean get_showCharInfoEntry() { }
	// RVA: 0x2cef11c VA: 0x759530711c
	private Void set_showCharInfoEntry(Boolean value) { }
	// RVA: 0x2cef19c VA: 0x759530719c
	public Boolean get_showPredefinedCharInfo() { }
	// RVA: 0x2cef204 VA: 0x7595307204
	private Void set_showPredefinedCharInfo(Boolean value) { }
	// RVA: 0x2cef284 VA: 0x7595307284
	public Void LoadAttrByInstId(Int32 chrInstId, String selectedSkillId, String selectedEquip, IPlugin plugin) { }
	// RVA: 0x2ced56c VA: 0x759530556c
	public Void LoadAttrByCardViewModel(PredefinedCharStruct charStruct, String selectedSkillId) { }
	// RVA: 0x2cf042c VA: 0x759530842c
	public Void ReloadAttrByEquipChange(String equipId) { }
	// RVA: 0x2cef8cc VA: 0x75953078cc
	private Void _LoadUniqEquip(CharacterData charData, CharQuery charQuery, EvolvePhase evolvePhase, Int32 level, Int32 potentialRank, String playerCharEquipId, ListDict`2 playerCharEquipInfos) { }
	// RVA: 0x2cefef4 VA: 0x7595307ef4
	private CharacterTalentViewModel[] _GenTalentGroup(CharacterData charData, Int32 playerCharLevel, EvolvePhase playerEvolvePhase, Int32 playerPotentialRank, String equipId, Int32 equipLevel) { }
	// RVA: 0x2cf0020 VA: 0x7595308020
	private Void _LoadAttrWithEquipInternal(CharacterData charData, CharQuery charQuery, EvolvePhase evolvePhase, Int32 potentialRank, Int32 level, Int32 favorPoint, String equipId, Int32 equipLevel) { }
	// RVA: 0x2cf06ec VA: 0x75953086ec
	public Void .ctor() { }
}
```