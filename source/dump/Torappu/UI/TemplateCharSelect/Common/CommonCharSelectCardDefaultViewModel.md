# CommonCharSelectCardDefaultViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `String m_skillId`

- `String m_skillName`

- `String m_skillIconId`

- `String m_equipId`

- `BasicCharInfoModel m_basicInfo`

- `AttackRangeDescModel m_attackRange`

- `String portraitId`

- `String professionIconId`

- `Int32 mainSkillLvl`

- `Int32 defaultSkillIndex`


## Properties

- `Int32 chrInstId`

- `RarityRank rarity`

- `ProfessionCategory profession`

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

- `String skillIconId`

- `CharStarMarkState starMark`


## Methods

- `Int32 get_chrInstId()`

- `RarityRank get_rarity()`

- `ProfessionCategory get_profession()`

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

- `String get_skillIconId()`

- `CharStarMarkState get_starMark()`

- `Void set_skills(PlayerCharSkill[])`

- `Void set_equips(ListDict`2)`

- `Boolean FillViewModel(PlayerCharacter, Boolean, String, String)`

- `Void SetSkillInfo(String)`

- `Void <>xLuaBaseProxy_OnEquipChanged(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectCardDefaultViewModel : TemplateCharSelectCardViewModel
{
	private String m_skillId; // 0x18
	private String m_skillName; // 0x20
	private String m_skillIconId; // 0x28
	private String m_equipId; // 0x30
	private BasicCharInfoModel m_basicInfo; // 0x38
	private AttackRangeDescModel m_attackRange; // 0x40
	public String portraitId; // 0x50
	public String professionIconId; // 0x58
	public Int32 mainSkillLvl; // 0x60
	public Int32 defaultSkillIndex; // 0x64
	private PlayerCharSkill[] <skills>k__BackingField; // 0x68
	private ListDict`2 <equips>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_chrInstId; // 0x0
	private static DelegateBridge __Hotfix0_get_rarity; // 0x8
	private static DelegateBridge __Hotfix0_get_profession; // 0x10
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x18
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0x20
	private static DelegateBridge __Hotfix0_get_description; // 0x28
	private static DelegateBridge __Hotfix0_get_name; // 0x30
	private static DelegateBridge __Hotfix0_get_level; // 0x38
	private static DelegateBridge __Hotfix0_get_expPercent; // 0x40
	private static DelegateBridge __Hotfix0_get_gainTime; // 0x48
	private static DelegateBridge __Hotfix0_get_cost; // 0x50
	private static DelegateBridge __Hotfix0_get_maxHp; // 0x58
	private static DelegateBridge __Hotfix0_get_atk; // 0x60
	private static DelegateBridge __Hotfix0_get_def; // 0x68
	private static DelegateBridge __Hotfix0_get_res; // 0x70
	private static DelegateBridge __Hotfix0_get_charId; // 0x78
	private static DelegateBridge __Hotfix0_get_tmplId; // 0x80
	private static DelegateBridge __Hotfix0_get_skinId; // 0x88
	private static DelegateBridge __Hotfix0_get_skillIconId; // 0x90
	private static DelegateBridge __Hotfix0_get_starMark; // 0x98
	private static DelegateBridge __Hotfix0_get_skills; // 0xa0
	private static DelegateBridge __Hotfix0_set_skills; // 0xa8
	private static DelegateBridge __Hotfix0_get_equips; // 0xb0
	private static DelegateBridge __Hotfix0_set_equips; // 0xb8
	private static DelegateBridge __Hotfix0_FillViewModel; // 0xc0
	private static DelegateBridge __Hotfix0_SetSkillInfo; // 0xc8
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0xd0
	private static DelegateBridge __Hotfix0_GetAttackRange; // 0xd8
	private static DelegateBridge __Hotfix0_get_skillId; // 0xe0
	private static DelegateBridge __Hotfix0_set_skillId; // 0xe8
	private static DelegateBridge __Hotfix0_get_equipId; // 0xf0
	private static DelegateBridge __Hotfix0_set_equipId; // 0xf8
	private static DelegateBridge __Hotfix0_GetInstId; // 0x100
	private static DelegateBridge __Hotfix0_SynWithPlayerData; // 0x108
	private static DelegateBridge __Hotfix0_OnEquipChanged; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	public Int32 chrInstId { get; }
	public RarityRank rarity { get; }
	public ProfessionCategory profession { get; }
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
	public String skillIconId { get; }
	public CharStarMarkState starMark { get; }
	public PlayerCharSkill[] skills { get; set; }
	public ListDict`2 equips { get; set; }
	public override BasicCharInfoModel basicCharInfo { get; }
	public override String skillId { get; set; }
	public override String equipId { get; set; }

	// RVA: 0x2c52844 VA: 0x759526a844
	public Int32 get_chrInstId() { }
	// RVA: 0x2c5218c VA: 0x759526a18c
	public RarityRank get_rarity() { }
	// RVA: 0x2c51ebc VA: 0x7595269ebc
	public ProfessionCategory get_profession() { }
	// RVA: 0x2c52438 VA: 0x759526a438
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2c523c4 VA: 0x759526a3c4
	public Int32 get_potentialRank() { }
	// RVA: 0x2c528b8 VA: 0x759526a8b8
	public String get_description() { }
	// RVA: 0x2c51e48 VA: 0x7595269e48
	public String get_name() { }
	// RVA: 0x2c52268 VA: 0x759526a268
	public Int32 get_level() { }
	// RVA: 0x2c522dc VA: 0x759526a2dc
	public Single get_expPercent() { }
	// RVA: 0x2c5292c VA: 0x759526a92c
	public DateTime get_gainTime() { }
	// RVA: 0x2c529a0 VA: 0x759526a9a0
	public Int32 get_cost() { }
	// RVA: 0x2c52a14 VA: 0x759526aa14
	public Int32 get_maxHp() { }
	// RVA: 0x2c52a88 VA: 0x759526aa88
	public Int32 get_atk() { }
	// RVA: 0x2c52afc VA: 0x759526aafc
	public Int32 get_def() { }
	// RVA: 0x2c52b70 VA: 0x759526ab70
	public Single get_res() { }
	// RVA: 0x2c52be4 VA: 0x759526abe4
	public String get_charId() { }
	// RVA: 0x2c52c58 VA: 0x759526ac58
	public String get_tmplId() { }
	// RVA: 0x2c52ccc VA: 0x759526accc
	public String get_skinId() { }
	// RVA: 0x2c52200 VA: 0x759526a200
	public String get_skillIconId() { }
	// RVA: 0x2c52350 VA: 0x759526a350
	public CharStarMarkState get_starMark() { }
	// RVA: 0x2c52d40 VA: 0x759526ad40
	public PlayerCharSkill[] get_skills() { }
	// RVA: 0x2c52da8 VA: 0x759526ada8
	private Void set_skills(PlayerCharSkill[] value) { }
	// RVA: 0x2c52e2c VA: 0x759526ae2c
	public ListDict`2 get_equips() { }
	// RVA: 0x2c52e94 VA: 0x759526ae94
	private Void set_equips(ListDict`2 value) { }
	// RVA: 0x2c50960 VA: 0x7595268960
	public Boolean FillViewModel(PlayerCharacter playerChar, Boolean instAble, String selectSkillId, String selectEquipId) { }
	// RVA: 0x2c52f18 VA: 0x759526af18
	public Void SetSkillInfo(String skillId) { }
	// RVA: 0x2c5306c VA: 0x759526b06c
	public override BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x2c530d4 VA: 0x759526b0d4
	public override AttackRangeDescModel GetAttackRange() { }
	// RVA: 0x2c53138 VA: 0x759526b138
	public override String get_skillId() { }
	// RVA: 0x2c531a0 VA: 0x759526b1a0
	public override Void set_skillId(String value) { }
	// RVA: 0x2c53220 VA: 0x759526b220
	public override String get_equipId() { }
	// RVA: 0x2c53288 VA: 0x759526b288
	public override Void set_equipId(String value) { }
	// RVA: 0x2c5330c VA: 0x759526b30c
	public override Int32 GetInstId() { }
	// RVA: 0x2c53380 VA: 0x759526b380
	public override Void SynWithPlayerData() { }
	// RVA: 0x2c53474 VA: 0x759526b474
	protected override Void OnEquipChanged(String equipId) { }
	// RVA: 0x2c508b8 VA: 0x75952688b8
	public Void .ctor() { }
	// RVA: 0x2c5378c VA: 0x759526b78c
	private Void <>xLuaBaseProxy_OnEquipChanged(String P0) { }
}
```