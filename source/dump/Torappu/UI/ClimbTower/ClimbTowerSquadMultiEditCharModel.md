# ClimbTowerSquadMultiEditCharModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 m_cardId`

- `TowerCardType m_cardType`

- `CharacterCardViewModel m_cardModel`

- `String m_selectSkillId`

- `String m_selectEquipId`

- `Sprite m_charMarkSprite`

- `Boolean m_isEquipCntOverLimit`

- `Boolean m_isEquipScrollPositionNeedAnchor`


## Properties

- `Int32 cardId`

- `TowerCardType cardType`

- `Sprite charMarkSprite`

- `String charId`

- `CharacterCardViewModel cardModel`

- `String curSkillId`

- `String curEquipId`

- `Boolean isEquipCntOverLimit`

- `Boolean isEquipScrollNeedPresetPosition`


## Methods

- `Int32 get_cardId()`

- `TowerCardType get_cardType()`

- `Sprite get_charMarkSprite()`

- `String get_charId()`

- `CharacterCardViewModel get_cardModel()`

- `String get_curSkillId()`

- `String get_curEquipId()`

- `Boolean get_isEquipCntOverLimit()`

- `Boolean get_isEquipScrollNeedPresetPosition()`

- `Void LoadData(UIPage, GameCard, ClimbTowerCharEditCacheModel)`

- `Void _LoadCharMarkSprite(UIPage)`

- `Void _LoadEquipList()`

- `Void _LoadSkillList()`

- `PlayerCharSkill _GetPlayerSkillData(PlayerCharSkill[], String)`

- `Int32 _GetSelectEquipPosition()`

- `Void UpdateSelectSkill(String)`

- `Void UpdateSelectEquip(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditCharModel
{
	private const Int32 EQUIP_MIN_SHOW_CNT; // 0x0
	private const Int32 SELECT_EQUIP_POSITION_NO_NEED_PRESET_POSITION; // 0x0
	private Int32 m_cardId; // 0x10
	private TowerCardType m_cardType; // 0x14
	private CharacterCardViewModel m_cardModel; // 0x18
	private String m_selectSkillId; // 0x20
	private String m_selectEquipId; // 0x28
	private List`1 m_skills; // 0x30
	private List`1 m_equips; // 0x38
	private Sprite m_charMarkSprite; // 0x40
	private Boolean m_isEquipCntOverLimit; // 0x48
	private Boolean m_isEquipScrollPositionNeedAnchor; // 0x49

	public Int32 cardId { get; }
	public TowerCardType cardType { get; }
	public Sprite charMarkSprite { get; }
	public String charId { get; }
	public CharacterCardViewModel cardModel { get; }
	public String curSkillId { get; }
	public String curEquipId { get; }
	public List`1 skillList { get; }
	public List`1 equipList { get; }
	public Boolean isEquipCntOverLimit { get; }
	public Boolean isEquipScrollNeedPresetPosition { get; }

	// RVA: 0x2cc6258 VA: 0x75952de258
	public Int32 get_cardId() { }
	// RVA: 0x2cc6260 VA: 0x75952de260
	public TowerCardType get_cardType() { }
	// RVA: 0x2cc6268 VA: 0x75952de268
	public Sprite get_charMarkSprite() { }
	// RVA: 0x2cc2d74 VA: 0x75952dad74
	public String get_charId() { }
	// RVA: 0x2cc6270 VA: 0x75952de270
	public CharacterCardViewModel get_cardModel() { }
	// RVA: 0x2cc6278 VA: 0x75952de278
	public String get_curSkillId() { }
	// RVA: 0x2cc6280 VA: 0x75952de280
	public String get_curEquipId() { }
	// RVA: 0x2cc6288 VA: 0x75952de288
	public List`1 get_skillList() { }
	// RVA: 0x2cc6290 VA: 0x75952de290
	public List`1 get_equipList() { }
	// RVA: 0x2cc6298 VA: 0x75952de298
	public Boolean get_isEquipCntOverLimit() { }
	// RVA: 0x2cc2d5c VA: 0x75952dad5c
	public Boolean get_isEquipScrollNeedPresetPosition() { }
	// RVA: 0x2cc6030 VA: 0x75952de030
	public Void LoadData(UIPage page, GameCard gameCard, ClimbTowerCharEditCacheModel editModel) { }
	// RVA: 0x2cc6a18 VA: 0x75952dea18
	private Void _LoadCharMarkSprite(UIPage page) { }
	// RVA: 0x2cc65d8 VA: 0x75952de5d8
	private Void _LoadEquipList() { }
	// RVA: 0x2cc6364 VA: 0x75952de364
	private Void _LoadSkillList() { }
	// RVA: 0x2cc6b98 VA: 0x75952deb98
	private PlayerCharSkill _GetPlayerSkillData(PlayerCharSkill[] playerSkills, String skillId) { }
	// RVA: 0x2cc62a0 VA: 0x75952de2a0
	private Int32 _GetSelectEquipPosition() { }
	// RVA: 0x2cc54c4 VA: 0x75952dd4c4
	public Void UpdateSelectSkill(String skillId) { }
	// RVA: 0x2cc560c VA: 0x75952dd60c
	public Void UpdateSelectEquip(String equipId) { }
	// RVA: 0x2cc5f58 VA: 0x75952ddf58
	public Void .ctor() { }
}
```