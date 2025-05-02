# CharacterShowV2Model

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `Boolean m_isAllSlotVisible`

- `Boolean m_isUnlockHintVisible`

- `Boolean m_isBuildingBuffVisible`

- `Boolean m_isValid`

- `Boolean m_isEquipCntOverLimit`

- `String m_charId`

- `String m_tmplId`

- `EvolvePhase m_evolvePhase`

- `String m_skinId`

- `Int32 m_level`

- `Int32 m_favorPoint`

- `Int32 m_potentialRank`

- `Int32 m_exp`

- `String m_tagsContent`

- `String m_position`

- `String m_selectedSkillId`

- `String m_selectedEquipId`

- `Single m_equipScrollNormalizedPos`

- `CharacterData m_charData`

- `SubProfessionData m_subProfData`

- `FavorData m_favorData`

- `String m_traitDesc`

- `BattleInfoViewModel m_battleInfoModel`

- `Int32 m_maxHp`

- `Int32 m_atk`

- `Int32 m_def`

- `Single m_res`

- `String m_respawnTime`

- `Int32 m_cost`

- `String m_atkSpeed`

- `Int32 m_blockNum`

- `AttributesData m_favorDelta`

- `CharTokenViewModel m_charTokenViewModel`

- `Int32 m_refreshEquipSeqNum`


## Properties

- `Boolean isAllSlotVisible`

- `Boolean isUnlockHintVisible`

- `Boolean isEquipCntOverLimit`

- `Int32 favorPercent`

- `Boolean hasEquip`

- `Boolean hasTalent`

- `Boolean isBuildingBuffVisible`

- `Int32 level`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `Int32 maxHp`

- `Int32 atk`

- `Int32 def`

- `Single res`

- `String respawnTime`

- `Int32 cost`

- `String atkSpeed`

- `Int32 blockNum`

- `BattleInfoViewModel battleInfoModel`

- `Boolean isValid`

- `String charId`

- `String skinId`

- `CharacterData charData`

- `String subProfId`

- `String subProfName`

- `String traitDesc`

- `AttributesData favorDelta`

- `String position`

- `String tagsContent`

- `ProfessionCategory profession`

- `String selectedSkillId`

- `String selectedEquipId`

- `Single equipScrollNormalizedPos`

- `CharTokenViewModel charTokenViewModel`

- `Int32 refreshEquipSeqNum`


## Methods

- `Boolean get_isAllSlotVisible()`

- `Boolean get_isUnlockHintVisible()`

- `Boolean get_isEquipCntOverLimit()`

- `Int32 get_favorPercent()`

- `Boolean get_hasEquip()`

- `Boolean get_hasTalent()`

- `Boolean get_isBuildingBuffVisible()`

- `Int32 get_level()`

- `EvolvePhase get_evolvePhase()`

- `Int32 get_potentialRank()`

- `Int32 get_maxHp()`

- `Int32 get_atk()`

- `Int32 get_def()`

- `Single get_res()`

- `String get_respawnTime()`

- `Int32 get_cost()`

- `String get_atkSpeed()`

- `Int32 get_blockNum()`

- `BattleInfoViewModel get_battleInfoModel()`

- `Boolean get_isValid()`

- `String get_charId()`

- `String get_skinId()`

- `CharacterData get_charData()`

- `String get_subProfId()`

- `String get_subProfName()`

- `String get_traitDesc()`

- `AttributesData get_favorDelta()`

- `String get_position()`

- `String get_tagsContent()`

- `ProfessionCategory get_profession()`

- `String get_selectedSkillId()`

- `String get_selectedEquipId()`

- `Single get_equipScrollNormalizedPos()`

- `CharTokenViewModel get_charTokenViewModel()`

- `Int32 get_refreshEquipSeqNum()`

- `Void LoadData(CharacterShowViewModel)`

- `CharacterShowEquipModel GetSelectedEquipModel()`

- `CharacterShowSkillModel GetSelectedSkillModel()`

- `String _GenerateTagContent(CharacterData)`

- `Boolean TryUpdateDataWithSKillId(String)`

- `Void _UpdateDataWithSKill(CharacterShowSkillModel)`

- `Boolean TryUpdateDataWithEquipId(String)`

- `Void _UpdateDataWithEquip(CharacterShowEquipModel)`

- `Void _SetEquipListFocus(Int32)`

- `Void _UpdateTalentList(CharacterShowEquipModel)`

- `Void _UpdateAttributes(CharacterShowEquipModel)`

- `Void _UpdateBattleInfoModel(CharacterShowEquipModel)`

- `Void _UpdateTraitDesc(CharacterShowEquipModel)`

- `String _CalcTraitDesc(CharacterShowEquipModel)`

- `CharacterShowSkillModel _GetSkillModel(String)`

- `CharacterShowEquipModel _GetEquipModel(String)`

- `Void _CalcTraitVariantList()`

- `CharQuery GetCharQuery()`

- `Void _InitUniEquipList(List`1)`

- `Void _InitSkillModelList(List`1, Int32, CharacterData)`

- `Void _LoadTokenModel()`

- `String _CalcTokenId()`

- `String _GetSkillTokenId()`

- `String _GetTalentTokenId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowV2Model : IHotfixable
{
	private const Int32 TAG_LINE_WIDTH; // 0x0
	private const Int32 EQUIP_MIN_SHOW_CNT; // 0x0
	private Boolean m_isAllSlotVisible; // 0x10
	private Boolean m_isUnlockHintVisible; // 0x11
	private Boolean m_isBuildingBuffVisible; // 0x12
	private Boolean m_isValid; // 0x13
	private Boolean m_isEquipCntOverLimit; // 0x14
	private String m_charId; // 0x18
	private String m_tmplId; // 0x20
	private EvolvePhase m_evolvePhase; // 0x28
	private String m_skinId; // 0x30
	private Int32 m_level; // 0x38
	private Int32 m_favorPoint; // 0x3c
	private Int32 m_potentialRank; // 0x40
	private Int32 m_exp; // 0x44
	private String m_tagsContent; // 0x48
	private String m_position; // 0x50
	private List`1 m_talentModelList; // 0x58
	private List`1 m_skillModelList; // 0x60
	private String m_selectedSkillId; // 0x68
	private List`1 m_equipModelList; // 0x70
	private String m_selectedEquipId; // 0x78
	private Single m_equipScrollNormalizedPos; // 0x80
	private CharacterData m_charData; // 0x88
	private SubProfessionData m_subProfData; // 0x90
	private FavorData m_favorData; // 0x98
	private String m_traitDesc; // 0xa0
	private BattleInfoViewModel m_battleInfoModel; // 0xa8
	private List`1 m_traitVariantList; // 0xb0
	private List`1 m_buildingBuffList; // 0xb8
	private Int32 m_maxHp; // 0xc0
	private Int32 m_atk; // 0xc4
	private Int32 m_def; // 0xc8
	private Single m_res; // 0xcc
	private String m_respawnTime; // 0xd0
	private Int32 m_cost; // 0xd8
	private String m_atkSpeed; // 0xe0
	private Int32 m_blockNum; // 0xe8
	private AttributesData m_favorDelta; // 0xf0
	private CharTokenViewModel m_charTokenViewModel; // 0xf8
	private Int32 m_refreshEquipSeqNum; // 0x100
	private static DelegateBridge __Hotfix0_get_isAllSlotVisible; // 0x0
	private static DelegateBridge __Hotfix0_get_isUnlockHintVisible; // 0x8
	private static DelegateBridge __Hotfix0_get_isEquipCntOverLimit; // 0x10
	private static DelegateBridge __Hotfix0_get_favorPercent; // 0x18
	private static DelegateBridge __Hotfix0_get_buildingBuffList; // 0x20
	private static DelegateBridge __Hotfix0_get_talentModelLsit; // 0x28
	private static DelegateBridge __Hotfix0_get_hasEquip; // 0x30
	private static DelegateBridge __Hotfix0_get_hasTalent; // 0x38
	private static DelegateBridge __Hotfix0_get_isBuildingBuffVisible; // 0x40
	private static DelegateBridge __Hotfix0_get_level; // 0x48
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x50
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0x58
	private static DelegateBridge __Hotfix0_get_maxHp; // 0x60
	private static DelegateBridge __Hotfix0_get_atk; // 0x68
	private static DelegateBridge __Hotfix0_get_def; // 0x70
	private static DelegateBridge __Hotfix0_get_res; // 0x78
	private static DelegateBridge __Hotfix0_get_respawnTime; // 0x80
	private static DelegateBridge __Hotfix0_get_cost; // 0x88
	private static DelegateBridge __Hotfix0_get_atkSpeed; // 0x90
	private static DelegateBridge __Hotfix0_get_blockNum; // 0x98
	private static DelegateBridge __Hotfix0_get_battleInfoModel; // 0xa0
	private static DelegateBridge __Hotfix0_get_isValid; // 0xa8
	private static DelegateBridge __Hotfix0_get_charId; // 0xb0
	private static DelegateBridge __Hotfix0_get_skinId; // 0xb8
	private static DelegateBridge __Hotfix0_get_charData; // 0xc0
	private static DelegateBridge __Hotfix0_get_subProfId; // 0xc8
	private static DelegateBridge __Hotfix0_get_subProfName; // 0xd0
	private static DelegateBridge __Hotfix0_get_traitDesc; // 0xd8
	private static DelegateBridge __Hotfix0_get_favorDelta; // 0xe0
	private static DelegateBridge __Hotfix0_get_position; // 0xe8
	private static DelegateBridge __Hotfix0_get_tagsContent; // 0xf0
	private static DelegateBridge __Hotfix0_get_profession; // 0xf8
	private static DelegateBridge __Hotfix0_get_equipList; // 0x100
	private static DelegateBridge __Hotfix0_get_skillList; // 0x108
	private static DelegateBridge __Hotfix0_get_selectedSkillId; // 0x110
	private static DelegateBridge __Hotfix0_get_selectedEquipId; // 0x118
	private static DelegateBridge __Hotfix0_get_equipScrollNormalizedPos; // 0x120
	private static DelegateBridge __Hotfix0_get_charTokenViewModel; // 0x128
	private static DelegateBridge __Hotfix0_get_refreshEquipSeqNum; // 0x130
	private static DelegateBridge __Hotfix0_LoadData; // 0x138
	private static DelegateBridge __Hotfix0_GetSelectedEquipModel; // 0x140
	private static DelegateBridge __Hotfix0_GetSelectedSkillModel; // 0x148
	private static DelegateBridge __Hotfix0__GenerateTagContent; // 0x150
	private static DelegateBridge __Hotfix0_TryUpdateDataWithSKillId; // 0x158
	private static DelegateBridge __Hotfix0__UpdateDataWithSKill; // 0x160
	private static DelegateBridge __Hotfix0_TryUpdateDataWithEquipId; // 0x168
	private static DelegateBridge __Hotfix0__UpdateDataWithEquip; // 0x170
	private static DelegateBridge __Hotfix0__SetEquipListFocus; // 0x178
	private static DelegateBridge __Hotfix0__UpdateTalentList; // 0x180
	private static DelegateBridge __Hotfix0__UpdateAttributes; // 0x188
	private static DelegateBridge __Hotfix0__UpdateBattleInfoModel; // 0x190
	private static DelegateBridge __Hotfix0__UpdateTraitDesc; // 0x198
	private static DelegateBridge __Hotfix0__CalcTraitDesc; // 0x1a0
	private static DelegateBridge __Hotfix0__GetSkillModel; // 0x1a8
	private static DelegateBridge __Hotfix0__GetEquipModel; // 0x1b0
	private static DelegateBridge __Hotfix0_FetchTraitVariantList; // 0x1b8
	private static DelegateBridge __Hotfix0__CalcTraitVariantList; // 0x1c0
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0x1c8
	private static DelegateBridge __Hotfix0__InitUniEquipList; // 0x1d0
	private static DelegateBridge __Hotfix0__InitSkillModelList; // 0x1d8
	private static DelegateBridge __Hotfix0__LoadTokenModel; // 0x1e0
	private static DelegateBridge __Hotfix0__CalcTokenId; // 0x1e8
	private static DelegateBridge __Hotfix0__GetSkillTokenId; // 0x1f0
	private static DelegateBridge __Hotfix0__GetTalentTokenId; // 0x1f8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x200

	public Boolean isAllSlotVisible { get; }
	public Boolean isUnlockHintVisible { get; }
	public Boolean isEquipCntOverLimit { get; }
	public Int32 favorPercent { get; }
	public List`1 buildingBuffList { get; }
	public List`1 talentModelLsit { get; }
	public Boolean hasEquip { get; }
	public Boolean hasTalent { get; }
	public Boolean isBuildingBuffVisible { get; }
	public Int32 level { get; }
	public EvolvePhase evolvePhase { get; }
	public Int32 potentialRank { get; }
	public Int32 maxHp { get; }
	public Int32 atk { get; }
	public Int32 def { get; }
	public Single res { get; }
	public String respawnTime { get; }
	public Int32 cost { get; }
	public String atkSpeed { get; }
	public Int32 blockNum { get; }
	public BattleInfoViewModel battleInfoModel { get; }
	public Boolean isValid { get; }
	public String charId { get; }
	public String skinId { get; }
	public CharacterData charData { get; }
	public String subProfId { get; }
	public String subProfName { get; }
	public String traitDesc { get; }
	public AttributesData favorDelta { get; }
	public String position { get; }
	public String tagsContent { get; }
	public ProfessionCategory profession { get; }
	public List`1 equipList { get; }
	public List`1 skillList { get; }
	public String selectedSkillId { get; }
	public String selectedEquipId { get; }
	public Single equipScrollNormalizedPos { get; }
	public CharTokenViewModel charTokenViewModel { get; }
	public Int32 refreshEquipSeqNum { get; }

	// RVA: 0x2ce0c30 VA: 0x75952f8c30
	public Boolean get_isAllSlotVisible() { }
	// RVA: 0x2ce0c98 VA: 0x75952f8c98
	public Boolean get_isUnlockHintVisible() { }
	// RVA: 0x2ce0d00 VA: 0x75952f8d00
	public Boolean get_isEquipCntOverLimit() { }
	// RVA: 0x2ce0d68 VA: 0x75952f8d68
	public Int32 get_favorPercent() { }
	// RVA: 0x2ce0de0 VA: 0x75952f8de0
	public List`1 get_buildingBuffList() { }
	// RVA: 0x2ce0e48 VA: 0x75952f8e48
	public List`1 get_talentModelLsit() { }
	// RVA: 0x2ce0eb0 VA: 0x75952f8eb0
	public Boolean get_hasEquip() { }
	// RVA: 0x2ce0f3c VA: 0x75952f8f3c
	public Boolean get_hasTalent() { }
	// RVA: 0x2ce0fc8 VA: 0x75952f8fc8
	public Boolean get_isBuildingBuffVisible() { }
	// RVA: 0x2ce1030 VA: 0x75952f9030
	public Int32 get_level() { }
	// RVA: 0x2ce1098 VA: 0x75952f9098
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2ce1100 VA: 0x75952f9100
	public Int32 get_potentialRank() { }
	// RVA: 0x2ce1168 VA: 0x75952f9168
	public Int32 get_maxHp() { }
	// RVA: 0x2ce11d0 VA: 0x75952f91d0
	public Int32 get_atk() { }
	// RVA: 0x2ce1238 VA: 0x75952f9238
	public Int32 get_def() { }
	// RVA: 0x2ce12a0 VA: 0x75952f92a0
	public Single get_res() { }
	// RVA: 0x2ce1308 VA: 0x75952f9308
	public String get_respawnTime() { }
	// RVA: 0x2ce1370 VA: 0x75952f9370
	public Int32 get_cost() { }
	// RVA: 0x2ce13d8 VA: 0x75952f93d8
	public String get_atkSpeed() { }
	// RVA: 0x2ce1440 VA: 0x75952f9440
	public Int32 get_blockNum() { }
	// RVA: 0x2ce14a8 VA: 0x75952f94a8
	public BattleInfoViewModel get_battleInfoModel() { }
	// RVA: 0x2ce1510 VA: 0x75952f9510
	public Boolean get_isValid() { }
	// RVA: 0x2ce1578 VA: 0x75952f9578
	public String get_charId() { }
	// RVA: 0x2ce15e0 VA: 0x75952f95e0
	public String get_skinId() { }
	// RVA: 0x2ce1648 VA: 0x75952f9648
	public CharacterData get_charData() { }
	// RVA: 0x2ce16b0 VA: 0x75952f96b0
	public String get_subProfId() { }
	// RVA: 0x2ce1744 VA: 0x75952f9744
	public String get_subProfName() { }
	// RVA: 0x2ce17d8 VA: 0x75952f97d8
	public String get_traitDesc() { }
	// RVA: 0x2ce1840 VA: 0x75952f9840
	public AttributesData get_favorDelta() { }
	// RVA: 0x2ce18a8 VA: 0x75952f98a8
	public String get_position() { }
	// RVA: 0x2ce1910 VA: 0x75952f9910
	public String get_tagsContent() { }
	// RVA: 0x2ce1978 VA: 0x75952f9978
	public ProfessionCategory get_profession() { }
	// RVA: 0x2ce19f0 VA: 0x75952f99f0
	public List`1 get_equipList() { }
	// RVA: 0x2ce1a58 VA: 0x75952f9a58
	public List`1 get_skillList() { }
	// RVA: 0x2ce1ac0 VA: 0x75952f9ac0
	public String get_selectedSkillId() { }
	// RVA: 0x2ce1b28 VA: 0x75952f9b28
	public String get_selectedEquipId() { }
	// RVA: 0x2ce1b90 VA: 0x75952f9b90
	public Single get_equipScrollNormalizedPos() { }
	// RVA: 0x2ce1bf8 VA: 0x75952f9bf8
	public CharTokenViewModel get_charTokenViewModel() { }
	// RVA: 0x2ce1c60 VA: 0x75952f9c60
	public Int32 get_refreshEquipSeqNum() { }
	// RVA: 0x2cdff70 VA: 0x75952f7f70
	public Void LoadData(CharacterShowViewModel input) { }
	// RVA: 0x2ce2928 VA: 0x75952fa928
	public CharacterShowEquipModel GetSelectedEquipModel() { }
	// RVA: 0x2ce2aac VA: 0x75952faaac
	public CharacterShowSkillModel GetSelectedSkillModel() { }
	// RVA: 0x2ce1cc8 VA: 0x75952f9cc8
	private String _GenerateTagContent(CharacterData charData) { }
	// RVA: 0x2ce0720 VA: 0x75952f8720
	public Boolean TryUpdateDataWithSKillId(String skillId) { }
	// RVA: 0x2ce2188 VA: 0x75952fa188
	private Void _UpdateDataWithSKill(CharacterShowSkillModel skillModel) { }
	// RVA: 0x2ce0800 VA: 0x75952f8800
	public Boolean TryUpdateDataWithEquipId(String equipId) { }
	// RVA: 0x2ce25d4 VA: 0x75952fa5d4
	private Void _UpdateDataWithEquip(CharacterShowEquipModel equipModel) { }
	// RVA: 0x2ce26a4 VA: 0x75952fa6a4
	private Void _SetEquipListFocus(Int32 defaultEquipIndex) { }
	// RVA: 0x2ce2e80 VA: 0x75952fae80
	private Void _UpdateTalentList(CharacterShowEquipModel equipModel) { }
	// RVA: 0x2ce3304 VA: 0x75952fb304
	private Void _UpdateAttributes(CharacterShowEquipModel equipModel) { }
	// RVA: 0x2ce3224 VA: 0x75952fb224
	private Void _UpdateBattleInfoModel(CharacterShowEquipModel equipModel) { }
	// RVA: 0x2ce2df0 VA: 0x75952fadf0
	private Void _UpdateTraitDesc(CharacterShowEquipModel equipModel) { }
	// RVA: 0x2ce3950 VA: 0x75952fb950
	private String _CalcTraitDesc(CharacterShowEquipModel equipModel) { }
	// RVA: 0x2ce2b18 VA: 0x75952fab18
	private CharacterShowSkillModel _GetSkillModel(String skillId) { }
	// RVA: 0x2ce2994 VA: 0x75952fa994
	private CharacterShowEquipModel _GetEquipModel(String equipId) { }
	// RVA: 0x2ce3be4 VA: 0x75952fbbe4
	public List`1 FetchTraitVariantList() { }
	// RVA: 0x2ce3c54 VA: 0x75952fbc54
	private Void _CalcTraitVariantList() { }
	// RVA: 0x2ce3890 VA: 0x75952fb890
	public CharQuery GetCharQuery() { }
	// RVA: 0x2ce2228 VA: 0x75952fa228
	private Void _InitUniEquipList(List`1 equipList) { }
	// RVA: 0x2ce1e5c VA: 0x75952f9e5c
	private Void _InitSkillModelList(List`1 skillList, Int32 mainSkillLv, CharacterData charData) { }
	// RVA: 0x2ce2778 VA: 0x75952fa778
	private Void _LoadTokenModel() { }
	// RVA: 0x2ce41d4 VA: 0x75952fc1d4
	private String _CalcTokenId() { }
	// RVA: 0x2ce43a8 VA: 0x75952fc3a8
	private String _GetSkillTokenId() { }
	// RVA: 0x2ce44c8 VA: 0x75952fc4c8
	private String _GetTalentTokenId() { }
	// RVA: 0x2ce46a0 VA: 0x75952fc6a0
	public Void .ctor() { }
}
```