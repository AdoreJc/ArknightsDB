# ActMultiV3CharViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `CharacterCardViewModel m_cardModel`

- `Int32 m_charInstId`

- `String m_skillId`

- `String m_equipId`

- `Int32 m_mainSkillLv`

- `ActMultiV3IdentityType <identityType>k__BackingField`


## Properties

- `ActMultiV3IdentityType identityType`

- `CharacterCardViewModel cardModel`

- `String charId`

- `String skillId`

- `Int32 mainSkillLv`

- `Int32 currSkillSpecLv`

- `String equipId`

- `Int32 currEquipLv`

- `Int32 charInstId`

- `CharQuery charQuery`


## Methods

- `ActMultiV3IdentityType get_identityType()`

- `Void set_identityType(ActMultiV3IdentityType)`

- `CharacterCardViewModel get_cardModel()`

- `String get_charId()`

- `String get_skillId()`

- `Int32 get_mainSkillLv()`

- `Int32 get_currSkillSpecLv()`

- `String get_equipId()`

- `Int32 get_currEquipLv()`

- `Int32 get_charInstId()`

- `CharQuery get_charQuery()`

- `Void LoadData(ActMultiV3IdentityType, Int32)`

- `Void InitSkillEquip(SquadItem)`

- `Int32 FindCurrSkillIndex()`

- `Void SetSkill(String)`

- `Void SetEquip(String)`

- `Void UpdatePlayerData()`

- `Void _UpdatePlayerData()`

- `Boolean CheckIfMemberChanged(SquadItem)`

- `Int32 _FindCurrSkillIndex()`

- `Int32 ExtraTmplCount()`

- `String GetDefaultEquipId()`

- `String GetSelectEquipId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3CharViewModel : IHotfixable, ISquadMemberCompInfo
{
	private CharacterCardViewModel m_cardModel; // 0x10
	private Int32 m_charInstId; // 0x18
	private String m_skillId; // 0x20
	private String m_equipId; // 0x28
	private Int32 m_mainSkillLv; // 0x30
	private List`1 m_skillIdList; // 0x38
	private Dictionary`2 m_skillLvDict; // 0x40
	private Dictionary`2 m_equipLvDict; // 0x48
	private ActMultiV3IdentityType <identityType>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_identityType; // 0x0
	private static DelegateBridge __Hotfix0_set_identityType; // 0x8
	private static DelegateBridge __Hotfix0_get_cardModel; // 0x10
	private static DelegateBridge __Hotfix0_get_charId; // 0x18
	private static DelegateBridge __Hotfix0_get_skillId; // 0x20
	private static DelegateBridge __Hotfix0_get_mainSkillLv; // 0x28
	private static DelegateBridge __Hotfix0_get_currSkillSpecLv; // 0x30
	private static DelegateBridge __Hotfix0_get_equipId; // 0x38
	private static DelegateBridge __Hotfix0_get_currEquipLv; // 0x40
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x48
	private static DelegateBridge __Hotfix0_get_charQuery; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0_InitSkillEquip; // 0x60
	private static DelegateBridge __Hotfix0_FindCurrSkillIndex; // 0x68
	private static DelegateBridge __Hotfix0_SetSkill; // 0x70
	private static DelegateBridge __Hotfix0_SetEquip; // 0x78
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x80
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x88
	private static DelegateBridge __Hotfix0_CheckIfMemberChanged; // 0x90
	private static DelegateBridge __Hotfix0__FindCurrSkillIndex; // 0x98
	private static DelegateBridge __Hotfix0_ExtraTmplInfo; // 0xa0
	private static DelegateBridge __Hotfix0_ExtraTmplCount; // 0xa8
	private static DelegateBridge __Hotfix0_GetDefaultEquipId; // 0xb0
	private static DelegateBridge __Hotfix0_GetSelectEquipId; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public ActMultiV3IdentityType identityType { get; set; }
	public CharacterCardViewModel cardModel { get; }
	public String charId { get; }
	public String skillId { get; }
	public Int32 mainSkillLv { get; }
	public Int32 currSkillSpecLv { get; }
	public String equipId { get; }
	public Int32 currEquipLv { get; }
	public Int32 charInstId { get; }
	public CharQuery charQuery { get; }

	// RVA: 0x3142c70 VA: 0x759575ac70
	public ActMultiV3IdentityType get_identityType() { }
	// RVA: 0x31439c4 VA: 0x759575b9c4
	private Void set_identityType(ActMultiV3IdentityType value) { }
	// RVA: 0x3143a40 VA: 0x759575ba40
	public CharacterCardViewModel get_cardModel() { }
	// RVA: 0x3143aa8 VA: 0x759575baa8
	public String get_charId() { }
	// RVA: 0x3143b38 VA: 0x759575bb38
	public String get_skillId() { }
	// RVA: 0x3143ba0 VA: 0x759575bba0
	public Int32 get_mainSkillLv() { }
	// RVA: 0x3143c08 VA: 0x759575bc08
	public Int32 get_currSkillSpecLv() { }
	// RVA: 0x3142aa4 VA: 0x759575aaa4
	public String get_equipId() { }
	// RVA: 0x3143cb0 VA: 0x759575bcb0
	public Int32 get_currEquipLv() { }
	// RVA: 0x314292c VA: 0x759575a92c
	public Int32 get_charInstId() { }
	// RVA: 0x3142994 VA: 0x759575a994
	public CharQuery get_charQuery() { }
	// RVA: 0x3143378 VA: 0x759575b378
	public Void LoadData(ActMultiV3IdentityType idType, Int32 charInstId) { }
	// RVA: 0x3143420 VA: 0x759575b420
	public Void InitSkillEquip(SquadItem playerSquadItem) { }
	// RVA: 0x3142a3c VA: 0x759575aa3c
	public Int32 FindCurrSkillIndex() { }
	// RVA: 0x314424c VA: 0x759575c24c
	public Void SetSkill(String skillId) { }
	// RVA: 0x31442d0 VA: 0x759575c2d0
	public Void SetEquip(String equipId) { }
	// RVA: 0x314318c VA: 0x759575b18c
	public Void UpdatePlayerData() { }
	// RVA: 0x3143d58 VA: 0x759575bd58
	private Void _UpdatePlayerData() { }
	// RVA: 0x3143808 VA: 0x759575b808
	public Boolean CheckIfMemberChanged(SquadItem playerChar) { }
	// RVA: 0x3144144 VA: 0x759575c144
	private Int32 _FindCurrSkillIndex() { }
	// RVA: 0x3144354 VA: 0x759575c354
	public IEnumerator`1 ExtraTmplInfo() { }
	// RVA: 0x3144428 VA: 0x759575c428
	public Int32 ExtraTmplCount() { }
	// RVA: 0x31444b0 VA: 0x759575c4b0
	public String GetDefaultEquipId() { }
	// RVA: 0x3144518 VA: 0x759575c518
	public String GetSelectEquipId() { }
	// RVA: 0x31431f4 VA: 0x759575b1f4
	public Void .ctor() { }
}
```