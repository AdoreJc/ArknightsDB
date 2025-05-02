# CommonCharSelectCardViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `BasicCharInfoModel m_basicInfoModel`

- `Int32 instId`

- `String cacheSelectSkillId`

- `String cacheCurrentEquipId`

- `String cacheTmplId`

- `Boolean showIndex`

- `String portraitId`

- `AttackRangeDescModel attackRange`

- `Int32 selectMax`

- `String m_skillId`

- `Int32 skillLvl`

- `String m_currentEquipId`


## Properties

- `String charId`

- `String skinId`

- `Int32 currentSelectSkillSpecLvl`

- `Int32 currentEquipLvl`


## Methods

- `String get_charId()`

- `String get_skinId()`

- `Int32 get_currentSelectSkillSpecLvl()`

- `Int32 get_currentEquipLvl()`

- `Void SetSelectData(CommonSquadSquadCharSelectCharInputData)`

- `Void UpdatePlayerData(PlayerCharacter, CharacterData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectCardViewModel : TemplateCharSelectCardViewModel
{
	private BasicCharInfoModel m_basicInfoModel; // 0x18
	public Int32 instId; // 0x20
	public String cacheSelectSkillId; // 0x28
	public String cacheCurrentEquipId; // 0x30
	public String cacheTmplId; // 0x38
	public Boolean showIndex; // 0x40
	public String portraitId; // 0x48
	public AttackRangeDescModel attackRange; // 0x50
	public Int32 selectMax; // 0x60
	private String m_skillId; // 0x68
	public Int32 skillLvl; // 0x70
	private Dictionary`2 skillSpecLvlDict; // 0x78
	private String m_currentEquipId; // 0x80
	public Dictionary`2 equipLvlDict; // 0x88
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0x0
	private static DelegateBridge __Hotfix0_GetAttackRange; // 0x8
	private static DelegateBridge __Hotfix0_get_charId; // 0x10
	private static DelegateBridge __Hotfix0_get_skinId; // 0x18
	private static DelegateBridge __Hotfix0_get_skillId; // 0x20
	private static DelegateBridge __Hotfix0_set_skillId; // 0x28
	private static DelegateBridge __Hotfix0_get_currentSelectSkillSpecLvl; // 0x30
	private static DelegateBridge __Hotfix0_get_equipId; // 0x38
	private static DelegateBridge __Hotfix0_set_equipId; // 0x40
	private static DelegateBridge __Hotfix0_get_currentEquipLvl; // 0x48
	private static DelegateBridge __Hotfix0_SetSelectData; // 0x50
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x58
	private static DelegateBridge __Hotfix0_SynWithPlayerData; // 0x60
	private static DelegateBridge __Hotfix0_GetInstId; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override BasicCharInfoModel basicCharInfo { get; }
	public String charId { get; }
	public String skinId { get; }
	public override String skillId { get; set; }
	public Int32 currentSelectSkillSpecLvl { get; }
	public override String equipId { get; set; }
	public Int32 currentEquipLvl { get; }

	// RVA: 0x2c582e8 VA: 0x75952702e8
	public override BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x2c58350 VA: 0x7595270350
	public override AttackRangeDescModel GetAttackRange() { }
	// RVA: 0x2c583b4 VA: 0x75952703b4
	public String get_charId() { }
	// RVA: 0x2c58428 VA: 0x7595270428
	public String get_skinId() { }
	// RVA: 0x2c5849c VA: 0x759527049c
	public override String get_skillId() { }
	// RVA: 0x2c5851c VA: 0x759527051c
	public override Void set_skillId(String value) { }
	// RVA: 0x2c57ce8 VA: 0x759526fce8
	public Int32 get_currentSelectSkillSpecLvl() { }
	// RVA: 0x2c585a0 VA: 0x75952705a0
	public override String get_equipId() { }
	// RVA: 0x2c58620 VA: 0x7595270620
	public override Void set_equipId(String value) { }
	// RVA: 0x2c57ff8 VA: 0x759526fff8
	public Int32 get_currentEquipLvl() { }
	// RVA: 0x2c586a4 VA: 0x75952706a4
	public Void SetSelectData(CommonSquadSquadCharSelectCharInputData selectData) { }
	// RVA: 0x2c58748 VA: 0x7595270748
	public Void UpdatePlayerData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2c58e08 VA: 0x7595270e08
	public override Void SynWithPlayerData() { }
	// RVA: 0x2c59028 VA: 0x7595271028
	public override Int32 GetInstId() { }
	// RVA: 0x2c59090 VA: 0x7595271090
	public Void .ctor() { }
}
```