# CharacterCardViewModel

**Namespace:** `Torappu.UI`


## Fields

- `String m_skillId`

- `String m_skillName`

- `String m_skillIconId`

- `String m_equipId`

- `BasicCharInfoModel m_basicInfo`

- `String portraitId`

- `String professionIconId`

- `Int32 mainSkillLvl`

- `Int32 defaultSkillIndex`

- `Boolean isInSquad`

- `Sprite <chrProfessionIconSprite>k__BackingField`

- `Boolean <isAllSpecMax>k__BackingField`

- `String m_profIdCache`


## Properties

- `BasicCharInfoModel basicCharInfo`

- `Int32 chrInstId`

- `RarityRank rarity`

- `ProfessionCategory profession`

- `String subProfessionId`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `String description`

- `String name`

- `Int32 level`

- `Single expPercent`

- `DateTime gainTime`

- `Int32 cost`

- `Int32 maxHp`

- `Int32 atk`

- `Int32 def`

- `Single res`

- `String charId`

- `String tmplId`

- `String skinId`

- `String skillId`

- `String skillName`

- `String skillIconId`

- `String equipId`

- `CharStarMarkState starMark`

- `Sprite chrProfessionIconSprite`

- `Boolean isAllSpecMax`


## Methods

- `BasicCharInfoModel get_basicCharInfo()`

- `Void set_basicCharInfo(BasicCharInfoModel)`

- `Int32 get_chrInstId()`

- `RarityRank get_rarity()`

- `ProfessionCategory get_profession()`

- `String get_subProfessionId()`

- `EvolvePhase get_evolvePhase()`

- `Int32 get_potentialRank()`

- `String get_description()`

- `String get_name()`

- `Int32 get_level()`

- `Single get_expPercent()`

- `DateTime get_gainTime()`

- `Int32 get_cost()`

- `Int32 get_maxHp()`

- `Int32 get_atk()`

- `Int32 get_def()`

- `Single get_res()`

- `String get_charId()`

- `String get_tmplId()`

- `String get_skinId()`

- `String get_skillId()`

- `String get_skillName()`

- `String get_skillIconId()`

- `String get_equipId()`

- `CharStarMarkState get_starMark()`

- `CharQuery GetCharQuery()`

- `VoiceQuery GetVoiceQuery()`

- `Sprite get_chrProfessionIconSprite()`

- `Void set_chrProfessionIconSprite(Sprite)`

- `Void set_skills(PlayerCharSkill[])`

- `Boolean get_isAllSpecMax()`

- `Void set_isAllSpecMax(Boolean)`

- `Void set_equips(ListDict`2)`

- `Void LoadNecessarySprites(SpriteHub)`

- `Void ClearSprites()`

- `Boolean FillViewModel(PlayerCharacter, Boolean)`

- `CharacterCardViewModel ShallowCopy()`

- `Void SetSkillInfo(String)`

- `Void SetEquipInfo(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CharacterCardViewModel : IBasicCharInfo, IHotfixable
{
	private String m_skillId; // 0x10
	private String m_skillName; // 0x18
	private String m_skillIconId; // 0x20
	private String m_equipId; // 0x28
	private BasicCharInfoModel m_basicInfo; // 0x30
	public String portraitId; // 0x38
	public String professionIconId; // 0x40
	public Int32 mainSkillLvl; // 0x48
	public Int32 defaultSkillIndex; // 0x4c
	public Boolean isInSquad; // 0x50
	private Sprite <chrProfessionIconSprite>k__BackingField; // 0x58
	private PlayerCharSkill[] <skills>k__BackingField; // 0x60
	private Boolean <isAllSpecMax>k__BackingField; // 0x68
	private ListDict`2 <equips>k__BackingField; // 0x70
	private String m_profIdCache; // 0x78
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_basicCharInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_chrInstId; // 0x10
	private static DelegateBridge __Hotfix0_get_rarity; // 0x18
	private static DelegateBridge __Hotfix0_get_profession; // 0x20
	private static DelegateBridge __Hotfix0_get_subProfessionId; // 0x28
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x30
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0x38
	private static DelegateBridge __Hotfix0_get_description; // 0x40
	private static DelegateBridge __Hotfix0_get_name; // 0x48
	private static DelegateBridge __Hotfix0_get_level; // 0x50
	private static DelegateBridge __Hotfix0_get_expPercent; // 0x58
	private static DelegateBridge __Hotfix0_get_gainTime; // 0x60
	private static DelegateBridge __Hotfix0_get_cost; // 0x68
	private static DelegateBridge __Hotfix0_get_maxHp; // 0x70
	private static DelegateBridge __Hotfix0_get_atk; // 0x78
	private static DelegateBridge __Hotfix0_get_def; // 0x80
	private static DelegateBridge __Hotfix0_get_res; // 0x88
	private static DelegateBridge __Hotfix0_get_charId; // 0x90
	private static DelegateBridge __Hotfix0_get_tmplId; // 0x98
	private static DelegateBridge __Hotfix0_get_skinId; // 0xa0
	private static DelegateBridge __Hotfix0_get_skillId; // 0xa8
	private static DelegateBridge __Hotfix0_get_skillName; // 0xb0
	private static DelegateBridge __Hotfix0_get_skillIconId; // 0xb8
	private static DelegateBridge __Hotfix0_get_equipId; // 0xc0
	private static DelegateBridge __Hotfix0_get_starMark; // 0xc8
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0xd0
	private static DelegateBridge __Hotfix0_GetVoiceQuery; // 0xd8
	private static DelegateBridge __Hotfix0_get_chrProfessionIconSprite; // 0xe0
	private static DelegateBridge __Hotfix0_set_chrProfessionIconSprite; // 0xe8
	private static DelegateBridge __Hotfix0_get_skills; // 0xf0
	private static DelegateBridge __Hotfix0_set_skills; // 0xf8
	private static DelegateBridge __Hotfix0_get_isAllSpecMax; // 0x100
	private static DelegateBridge __Hotfix0_set_isAllSpecMax; // 0x108
	private static DelegateBridge __Hotfix0_get_equips; // 0x110
	private static DelegateBridge __Hotfix0_set_equips; // 0x118
	private static DelegateBridge __Hotfix0_LoadNecessarySprites; // 0x120
	private static DelegateBridge __Hotfix0_ClearSprites; // 0x128
	private static DelegateBridge __Hotfix0_FillViewModel; // 0x130
	private static DelegateBridge __Hotfix0_ShallowCopy; // 0x138
	private static DelegateBridge __Hotfix0_SetSkillInfo; // 0x140
	private static DelegateBridge __Hotfix0_SetEquipInfo; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public BasicCharInfoModel basicCharInfo { get; set; }
	public Int32 chrInstId { get; }
	public RarityRank rarity { get; }
	public ProfessionCategory profession { get; }
	public String subProfessionId { get; }
	public EvolvePhase evolvePhase { get; }
	public Int32 potentialRank { get; }
	public String description { get; }
	public String name { get; }
	public Int32 level { get; }
	public Single expPercent { get; }
	public DateTime gainTime { get; }
	public Int32 cost { get; }
	public Int32 maxHp { get; }
	public Int32 atk { get; }
	public Int32 def { get; }
	public Single res { get; }
	public String charId { get; }
	public String tmplId { get; }
	public String skinId { get; }
	public String skillId { get; }
	public String skillName { get; }
	public String skillIconId { get; }
	public String equipId { get; }
	public CharStarMarkState starMark { get; }
	public Sprite chrProfessionIconSprite { get; set; }
	public PlayerCharSkill[] skills { get; set; }
	public Boolean isAllSpecMax { get; set; }
	public ListDict`2 equips { get; set; }

	// RVA: 0x2121a84 VA: 0x7594739a84
	public BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x2121aec VA: 0x7594739aec
	public Void set_basicCharInfo(BasicCharInfoModel value) { }
	// RVA: 0x2120f30 VA: 0x7594738f30
	public Int32 get_chrInstId() { }
	// RVA: 0x2121b70 VA: 0x7594739b70
	public RarityRank get_rarity() { }
	// RVA: 0x2121be4 VA: 0x7594739be4
	public ProfessionCategory get_profession() { }
	// RVA: 0x2121c58 VA: 0x7594739c58
	public String get_subProfessionId() { }
	// RVA: 0x2121ccc VA: 0x7594739ccc
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2121d40 VA: 0x7594739d40
	public Int32 get_potentialRank() { }
	// RVA: 0x2121db4 VA: 0x7594739db4
	public String get_description() { }
	// RVA: 0x2121e28 VA: 0x7594739e28
	public String get_name() { }
	// RVA: 0x2121e9c VA: 0x7594739e9c
	public Int32 get_level() { }
	// RVA: 0x2121f10 VA: 0x7594739f10
	public Single get_expPercent() { }
	// RVA: 0x2121f84 VA: 0x7594739f84
	public DateTime get_gainTime() { }
	// RVA: 0x2121ff8 VA: 0x7594739ff8
	public Int32 get_cost() { }
	// RVA: 0x2122068 VA: 0x759473a068
	public Int32 get_maxHp() { }
	// RVA: 0x21220d8 VA: 0x759473a0d8
	public Int32 get_atk() { }
	// RVA: 0x2122148 VA: 0x759473a148
	public Int32 get_def() { }
	// RVA: 0x21221b8 VA: 0x759473a1b8
	public Single get_res() { }
	// RVA: 0x21206c4 VA: 0x75947386c4
	public String get_charId() { }
	// RVA: 0x2122228 VA: 0x759473a228
	public String get_tmplId() { }
	// RVA: 0x212229c VA: 0x759473a29c
	public String get_skinId() { }
	// RVA: 0x2122310 VA: 0x759473a310
	public String get_skillId() { }
	// RVA: 0x2122378 VA: 0x759473a378
	public String get_skillName() { }
	// RVA: 0x21223e0 VA: 0x759473a3e0
	public String get_skillIconId() { }
	// RVA: 0x2122448 VA: 0x759473a448
	public String get_equipId() { }
	// RVA: 0x21224b0 VA: 0x759473a4b0
	public CharStarMarkState get_starMark() { }
	// RVA: 0x2122524 VA: 0x759473a524
	public CharQuery GetCharQuery() { }
	// RVA: 0x21225f4 VA: 0x759473a5f4
	public VoiceQuery GetVoiceQuery() { }
	// RVA: 0x21226c4 VA: 0x759473a6c4
	public Sprite get_chrProfessionIconSprite() { }
	// RVA: 0x212272c VA: 0x759473a72c
	private Void set_chrProfessionIconSprite(Sprite value) { }
	// RVA: 0x21227b0 VA: 0x759473a7b0
	public PlayerCharSkill[] get_skills() { }
	// RVA: 0x2122818 VA: 0x759473a818
	private Void set_skills(PlayerCharSkill[] value) { }
	// RVA: 0x212289c VA: 0x759473a89c
	public Boolean get_isAllSpecMax() { }
	// RVA: 0x2122904 VA: 0x759473a904
	private Void set_isAllSpecMax(Boolean value) { }
	// RVA: 0x2122984 VA: 0x759473a984
	public ListDict`2 get_equips() { }
	// RVA: 0x21229ec VA: 0x759473a9ec
	private Void set_equips(ListDict`2 value) { }
	// RVA: 0x2122a70 VA: 0x759473aa70
	public Void LoadNecessarySprites(SpriteHub professionHub) { }
	// RVA: 0x2122c2c VA: 0x759473ac2c
	public Void ClearSprites() { }
	// RVA: 0x2122c98 VA: 0x759473ac98
	public Boolean FillViewModel(PlayerCharacter playerChar, Boolean instAble) { }
	// RVA: 0x2123340 VA: 0x759473b340
	public CharacterCardViewModel ShallowCopy() { }
	// RVA: 0x21231ec VA: 0x759473b1ec
	public Void SetSkillInfo(String skillId) { }
	// RVA: 0x21233e8 VA: 0x759473b3e8
	public Void SetEquipInfo(String equipId) { }
	// RVA: 0x2123490 VA: 0x759473b490
	public Void .ctor() { }
}
```