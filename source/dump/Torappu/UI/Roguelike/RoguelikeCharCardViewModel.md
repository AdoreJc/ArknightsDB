# RoguelikeCharCardViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `ShowType showType`

- `RoguelikeBasicCharInfoModel basicInfo`

- `Int32 populationCost`

- `Int32 upgradePhase`

- `Boolean upgradeLimited`

- `Boolean isUpgrade`

- `String conflictSpCharId`

- `Int32 troopInstId`

- `Boolean availToSelect`

- `Int32 isThird`

- `Int32 isThirdElite`

- `Int32 isElite`

- `Int32 isAddition`

- `Int32 isFriendAssist`

- `Int32 isMonthlyTeam`

- `RoguelikeCharState state`

- `String attackSpeedDesc`

- `String respawnDesc`

- `AttackRangeDescModel attackRange`

- `EvolvePhase maxStateEvolve`

- `Int32 maxStateLevel`

- `RoguelikeCharSelectSkillGroupViewModel skillGroup`

- `RoguelikeCharSelectBranchGroupViewModel branchGroup`

- `CharAttrTabType attryTabType`

- `Int32 skillIndex`

- `Int32 lastSkillCount`

- `String m_cachedTopicId`

- `String m_cachedMonthSquadId`

- `RoguelikeTopicMonthSquad m_cachedMonthSquadData`

- `String m_cachedMonthCharCardTag`


## Properties

- `Int32 instId`

- `String charId`

- `String tmplId`

- `String skinId`

- `String name`

- `RarityRank rarity`

- `ProfessionCategory profession`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `Int32 level`

- `Int32 favorPoint`

- `Int32 mainSkillLvl`

- `Int32 defaultSkillIndex`


## Methods

- `Int32 get_instId()`

- `String get_charId()`

- `String get_tmplId()`

- `String get_skinId()`

- `String get_name()`

- `RarityRank get_rarity()`

- `ProfessionCategory get_profession()`

- `EvolvePhase get_evolvePhase()`

- `Int32 get_potentialRank()`

- `Int32 get_level()`

- `Int32 get_favorPoint()`

- `Int32 get_mainSkillLvl()`

- `Int32 get_defaultSkillIndex()`

- `String GetDefaultEquipId()`

- `Void EnsureSkill()`

- `Void _LoadUniqEquip(CharacterData, CharQuery, EvolvePhase, Int32, Int32, Int32, String, ListDict`2)`

- `Void _LoadUniequipAttr(CharacterData, CharQuery, EvolvePhase, Int32, Int32, Int32, String, Int32)`

- `Void _ReloadUniequip()`

- `Void LoadData(Char, ShowType)`

- `Void LoadData(RecruitChar, ShowType)`

- `Void SetSkill(String)`

- `Void SetBranch(String, String)`

- `String GetSkillId(Int32)`

- `Void UpdateLastSkillCount()`

- `CharQuery GetCharQuery()`

- `UniqueEquipPair GetEquipQuery()`

- `VoiceQuery GetVoiceQuery()`

- `RoguelikeTopicMonthSquad GetMonthSquadData()`

- `String GetMonthCharCardTagName()`

- `Int32 ExtraTmplCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharCardViewModel : ISquadMemberCompInfo, IHotfixable
{
	public ShowType showType; // 0x10
	public RoguelikeBasicCharInfoModel basicInfo; // 0x18
	public Int32 populationCost; // 0x20
	public Int32 upgradePhase; // 0x24
	public Boolean upgradeLimited; // 0x28
	public Boolean isUpgrade; // 0x29
	public String conflictSpCharId; // 0x30
	public Int32 troopInstId; // 0x38
	public Boolean availToSelect; // 0x3c
	public Int32 isThird; // 0x40
	public Int32 isThirdElite; // 0x44
	public Int32 isElite; // 0x48
	public Int32 isAddition; // 0x4c
	public Int32 isFriendAssist; // 0x50
	public Int32 isMonthlyTeam; // 0x54
	public RoguelikeCharState state; // 0x58
	public String attackSpeedDesc; // 0x60
	public String respawnDesc; // 0x68
	public AttackRangeDescModel attackRange; // 0x70
	public EvolvePhase maxStateEvolve; // 0x80
	public Int32 maxStateLevel; // 0x84
	public RoguelikeCharSelectSkillGroupViewModel skillGroup; // 0x88
	public RoguelikeCharSelectBranchGroupViewModel branchGroup; // 0x90
	public CharAttrTabType attryTabType; // 0x98
	public Int32 skillIndex; // 0x9c
	public Int32 lastSkillCount; // 0xa0
	private String m_cachedTopicId; // 0xa8
	private String m_cachedMonthSquadId; // 0xb0
	private RoguelikeTopicMonthSquad m_cachedMonthSquadData; // 0xb8
	private String m_cachedMonthCharCardTag; // 0xc0
	private static DelegateBridge __Hotfix0_get_instId; // 0x0
	private static DelegateBridge __Hotfix0_get_charId; // 0x8
	private static DelegateBridge __Hotfix0_get_tmplId; // 0x10
	private static DelegateBridge __Hotfix0_get_skinId; // 0x18
	private static DelegateBridge __Hotfix0_get_name; // 0x20
	private static DelegateBridge __Hotfix0_get_rarity; // 0x28
	private static DelegateBridge __Hotfix0_get_profession; // 0x30
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x38
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0x40
	private static DelegateBridge __Hotfix0_get_level; // 0x48
	private static DelegateBridge __Hotfix0_get_favorPoint; // 0x50
	private static DelegateBridge __Hotfix0_get_mainSkillLvl; // 0x58
	private static DelegateBridge __Hotfix0_get_defaultSkillIndex; // 0x60
	private static DelegateBridge __Hotfix0_get_skills; // 0x68
	private static DelegateBridge __Hotfix0_GetDefaultEquipId; // 0x70
	private static DelegateBridge __Hotfix0_EnsureSkill; // 0x78
	private static DelegateBridge __Hotfix0__GenTalentGroup; // 0x80
	private static DelegateBridge __Hotfix0__LoadUniqEquip; // 0x88
	private static DelegateBridge __Hotfix0__LoadUniequipAttr; // 0x90
	private static DelegateBridge __Hotfix0__ReloadUniequip; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix1_LoadData; // 0xa8
	private static DelegateBridge __Hotfix0_SetSkill; // 0xb0
	private static DelegateBridge __Hotfix0_SetBranch; // 0xb8
	private static DelegateBridge __Hotfix0_GetSkillId; // 0xc0
	private static DelegateBridge __Hotfix0_UpdateLastSkillCount; // 0xc8
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0xd0
	private static DelegateBridge __Hotfix0_GetEquipQuery; // 0xd8
	private static DelegateBridge __Hotfix0_GetVoiceQuery; // 0xe0
	private static DelegateBridge __Hotfix0_GetMonthSquadData; // 0xe8
	private static DelegateBridge __Hotfix0_GetMonthCharCardTagName; // 0xf0
	private static DelegateBridge __Hotfix0_ExtraTmplInfo; // 0xf8
	private static DelegateBridge __Hotfix0_ExtraTmplCount; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public Int32 instId { get; }
	public String charId { get; }
	public String tmplId { get; }
	public String skinId { get; }
	public String name { get; }
	public RarityRank rarity { get; }
	public ProfessionCategory profession { get; }
	public EvolvePhase evolvePhase { get; }
	public Int32 potentialRank { get; }
	public Int32 level { get; }
	public Int32 favorPoint { get; }
	public Int32 mainSkillLvl { get; }
	public Int32 defaultSkillIndex { get; }
	public PlayerCharSkill[] skills { get; }

	// RVA: 0x2aef22c VA: 0x759510722c
	public Int32 get_instId() { }
	// RVA: 0x2aef2a0 VA: 0x75951072a0
	public String get_charId() { }
	// RVA: 0x2aef314 VA: 0x7595107314
	public String get_tmplId() { }
	// RVA: 0x2aef388 VA: 0x7595107388
	public String get_skinId() { }
	// RVA: 0x2aef3fc VA: 0x75951073fc
	public String get_name() { }
	// RVA: 0x2aef470 VA: 0x7595107470
	public RarityRank get_rarity() { }
	// RVA: 0x2aef4e4 VA: 0x75951074e4
	public ProfessionCategory get_profession() { }
	// RVA: 0x2aef558 VA: 0x7595107558
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2aef5cc VA: 0x75951075cc
	public Int32 get_potentialRank() { }
	// RVA: 0x2aef640 VA: 0x7595107640
	public Int32 get_level() { }
	// RVA: 0x2aef6b4 VA: 0x75951076b4
	public Int32 get_favorPoint() { }
	// RVA: 0x2aef728 VA: 0x7595107728
	public Int32 get_mainSkillLvl() { }
	// RVA: 0x2aef79c VA: 0x759510779c
	public Int32 get_defaultSkillIndex() { }
	// RVA: 0x2aef810 VA: 0x7595107810
	public PlayerCharSkill[] get_skills() { }
	// RVA: 0x2aef884 VA: 0x7595107884
	public String GetDefaultEquipId() { }
	// RVA: 0x2aef8f8 VA: 0x75951078f8
	public Void EnsureSkill() { }
	// RVA: 0x2aefc18 VA: 0x7595107c18
	private RoguelikeTalentViewModel[] _GenTalentGroup(CharacterData charData, Int32 playerCharLevel, EvolvePhase playerEvolvePhase, Int32 playerPotentialRank) { }
	// RVA: 0x2af035c VA: 0x759510835c
	private Void _LoadUniqEquip(CharacterData charData, CharQuery charQuery, EvolvePhase evolvePhase, Int32 level, Int32 favorPoint, Int32 potentialRank, String playerCharEquipId, ListDict`2 playerCharEquipInfos) { }
	// RVA: 0x2af0c9c VA: 0x7595108c9c
	private Void _LoadUniequipAttr(CharacterData charData, CharQuery charQuery, EvolvePhase evolvePhase, Int32 level, Int32 favorPoint, Int32 potentialRank, String equipId, Int32 equiplevel) { }
	// RVA: 0x2af10f0 VA: 0x75951090f0
	private Void _ReloadUniequip() { }
	// RVA: 0x2af1420 VA: 0x7595109420
	public Void LoadData(Char playerChar, ShowType showType) { }
	// RVA: 0x2af19f8 VA: 0x75951099f8
	public Void LoadData(RecruitChar playerChar, ShowType showType) { }
	// RVA: 0x2aefac0 VA: 0x7595107ac0
	public Void SetSkill(String skillId) { }
	// RVA: 0x2af0a9c VA: 0x7595108a9c
	public Void SetBranch(String equipId, String defaultEquipId) { }
	// RVA: 0x2aef9f0 VA: 0x75951079f0
	public String GetSkillId(Int32 index) { }
	// RVA: 0x2af1fe0 VA: 0x7595109fe0
	public Void UpdateLastSkillCount() { }
	// RVA: 0x2af1020 VA: 0x7595109020
	public CharQuery GetCharQuery() { }
	// RVA: 0x2af02ac VA: 0x75951082ac
	public UniqueEquipPair GetEquipQuery() { }
	// RVA: 0x2af20d4 VA: 0x759510a0d4
	public VoiceQuery GetVoiceQuery() { }
	// RVA: 0x2af21a4 VA: 0x759510a1a4
	public RoguelikeTopicMonthSquad GetMonthSquadData() { }
	// RVA: 0x2af23bc VA: 0x759510a3bc
	public String GetMonthCharCardTagName() { }
	// RVA: 0x2af242c VA: 0x759510a42c
	public IEnumerator`1 ExtraTmplInfo() { }
	// RVA: 0x2af2500 VA: 0x759510a500
	public Int32 ExtraTmplCount() { }
	// RVA: 0x2af257c VA: 0x759510a57c
	public Void .ctor() { }
}
```