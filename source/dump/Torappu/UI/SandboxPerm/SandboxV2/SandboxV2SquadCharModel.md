# SandboxV2SquadCharModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean m_isTutorial`

- `Int32 m_instId`

- `String m_topicId`

- `SandboxV2CharInfoHolder m_charInfoHolder`

- `String m_currentTmpl`

- `Int32 m_selectSkillIndex`

- `String m_selectEquipId`

- `String m_defaultEquipId`

- `Color m_rarityColor`

- `SandboxV2CharStatus m_charStatus`


## Properties

- `SandboxV2CharInfoHolder infoHolder`

- `Int32 instId`

- `SandboxV2CharStatus charStatus`

- `CharQuery charQuery`

- `Int32 selectSkillIdx`

- `String selectEquipId`

- `String selectSkillId`

- `Color rarityColor`


## Methods

- `SandboxV2CharInfoHolder get_infoHolder()`

- `Int32 get_instId()`

- `SandboxV2CharStatus get_charStatus()`

- `CharQuery get_charQuery()`

- `Int32 get_selectSkillIdx()`

- `String get_selectEquipId()`

- `String get_selectSkillId()`

- `Color get_rarityColor()`

- `CharUISkinStruct CreateCharSkinStruct()`

- `SandboxV2CharEquipModel GetSelectEquipModel()`

- `Int32 ExtraTmplCount()`

- `String GetDefaultEquipId()`

- `String GetSelectEquipId()`

- `Void _LoadData(String, Int32, SandboxV2CharInfoHolder, Int32, String, Boolean)`

- `Void UpdatePlayerData()`

- `Void _UpdateCharStatus()`

- `Void _LoadAdditionData()`

- `Void SelectSkill(String)`

- `Boolean CheckIfMemberChanged(PlayerSquadItem)`

- `Boolean CanBattle()`

- `AdvancedCharacterInst GenAdvancedCharInst()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadCharModel : ISquadMemberCompInfo, IHotfixable
{
	private Boolean m_isTutorial; // 0x10
	private Int32 m_instId; // 0x14
	private String m_topicId; // 0x18
	private SandboxV2CharInfoHolder m_charInfoHolder; // 0x20
	private String m_currentTmpl; // 0x28
	private Int32 m_selectSkillIndex; // 0x30
	private String m_selectEquipId; // 0x38
	private String m_defaultEquipId; // 0x40
	private Color m_rarityColor; // 0x48
	private SandboxV2CharStatus m_charStatus; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_infoHolder; // 0x8
	private static DelegateBridge __Hotfix0_get_instId; // 0x10
	private static DelegateBridge __Hotfix0_get_charStatus; // 0x18
	private static DelegateBridge __Hotfix0_get_skillList; // 0x20
	private static DelegateBridge __Hotfix0_get_charQuery; // 0x28
	private static DelegateBridge __Hotfix0_get_selectSkillIdx; // 0x30
	private static DelegateBridge __Hotfix0_get_selectEquipId; // 0x38
	private static DelegateBridge __Hotfix0_get_selectSkillId; // 0x40
	private static DelegateBridge __Hotfix0_get_rarityColor; // 0x48
	private static DelegateBridge __Hotfix0_CreateCharSkinStruct; // 0x50
	private static DelegateBridge __Hotfix0_GetSelectEquipModel; // 0x58
	private static DelegateBridge __Hotfix0_ExtraTmplInfo; // 0x60
	private static DelegateBridge __Hotfix0_ExtraTmplCount; // 0x68
	private static DelegateBridge __Hotfix0_GetDefaultEquipId; // 0x70
	private static DelegateBridge __Hotfix0_GetSelectEquipId; // 0x78
	private static DelegateBridge __Hotfix0_Create; // 0x80
	private static DelegateBridge __Hotfix0_CreateFromInstId; // 0x88
	private static DelegateBridge __Hotfix0__LoadData; // 0x90
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x98
	private static DelegateBridge __Hotfix0__UpdateCharStatus; // 0xa0
	private static DelegateBridge __Hotfix0__LoadAdditionData; // 0xa8
	private static DelegateBridge __Hotfix0_SelectSkill; // 0xb0
	private static DelegateBridge __Hotfix0_CheckIfMemberChanged; // 0xb8
	private static DelegateBridge __Hotfix0_CanBattle; // 0xc0
	private static DelegateBridge __Hotfix0_GenAdvancedCharInst; // 0xc8

	public SandboxV2CharInfoHolder infoHolder { get; }
	public Int32 instId { get; }
	public SandboxV2CharStatus charStatus { get; }
	public List`1 skillList { get; }
	public CharQuery charQuery { get; }
	public Int32 selectSkillIdx { get; }
	public String selectEquipId { get; }
	public String selectSkillId { get; }
	public Color rarityColor { get; }

	// RVA: 0x261b144 VA: 0x7594c33144
	private Void .ctor() { }
	// RVA: 0x260fc8c VA: 0x7594c27c8c
	public SandboxV2CharInfoHolder get_infoHolder() { }
	// RVA: 0x26101a4 VA: 0x7594c281a4
	public Int32 get_instId() { }
	// RVA: 0x260fc24 VA: 0x7594c27c24
	public SandboxV2CharStatus get_charStatus() { }
	// RVA: 0x26105c8 VA: 0x7594c285c8
	public List`1 get_skillList() { }
	// RVA: 0x261a7e0 VA: 0x7594c327e0
	public CharQuery get_charQuery() { }
	// RVA: 0x261a8b4 VA: 0x7594c328b4
	public Int32 get_selectSkillIdx() { }
	// RVA: 0x261a91c VA: 0x7594c3291c
	public String get_selectEquipId() { }
	// RVA: 0x2610638 VA: 0x7594c28638
	public String get_selectSkillId() { }
	// RVA: 0x260fcf4 VA: 0x7594c27cf4
	public Color get_rarityColor() { }
	// RVA: 0x261ad28 VA: 0x7594c32d28
	public CharUISkinStruct CreateCharSkinStruct() { }
	// RVA: 0x260fd5c VA: 0x7594c27d5c
	public SandboxV2CharEquipModel GetSelectEquipModel() { }
	// RVA: 0x261b1b4 VA: 0x7594c331b4
	public IEnumerator`1 ExtraTmplInfo() { }
	// RVA: 0x261b288 VA: 0x7594c33288
	public Int32 ExtraTmplCount() { }
	// RVA: 0x261b300 VA: 0x7594c33300
	public String GetDefaultEquipId() { }
	// RVA: 0x26156d0 VA: 0x7594c2d6d0
	public String GetSelectEquipId() { }
	// RVA: 0x261a6a0 VA: 0x7594c326a0
	public static SandboxV2SquadCharModel Create(String topicId, PlayerSquadItem playerSquadItem, Boolean isTutorial) { }
	// RVA: 0x2619a94 VA: 0x7594c31a94
	public static SandboxV2SquadCharModel CreateFromInstId(String topicId, SandboxV2CharSquad charConfig, Boolean isTutorial) { }
	// RVA: 0x261b368 VA: 0x7594c33368
	private Void _LoadData(String topicId, Int32 charInstId, SandboxV2CharInfoHolder charInfoHolder, Int32 skillIndex, String equipId, Boolean isTutorial) { }
	// RVA: 0x2619988 VA: 0x7594c31988
	public Void UpdatePlayerData() { }
	// RVA: 0x261b598 VA: 0x7594c33598
	private Void _UpdateCharStatus() { }
	// RVA: 0x261b4dc VA: 0x7594c334dc
	private Void _LoadAdditionData() { }
	// RVA: 0x26140c8 VA: 0x7594c2c0c8
	public Void SelectSkill(String skillId) { }
	// RVA: 0x2619354 VA: 0x7594c31354
	public Boolean CheckIfMemberChanged(PlayerSquadItem playerItem) { }
	// RVA: 0x260fe78 VA: 0x7594c27e78
	public Boolean CanBattle() { }
	// RVA: 0x261aa00 VA: 0x7594c32a00
	public AdvancedCharacterInst GenAdvancedCharInst() { }
}
```