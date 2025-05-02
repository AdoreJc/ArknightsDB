# SharedCharData

**Namespace:** `Torappu`


## Fields

- `String charId`

- `Int32 potentialRank`

- `Int32 m_skillIndex`

- `String m_skinId`

- `String m_selectEquip`

- `Int32 mainSkillLvl`

- `Int32 evolvePhase`

- `Int32 level`

- `Int32 favorPoint`

- `String currentTmpl`

- `Int32 overrideSkillIndex`

- `String overrideEquipId`


## Properties

- `Int32 FBOnly_skillIndex`

- `String FBOnly_skinId`

- `String FBOnly_currentEquip`


## Methods

- `Int32 get_FBOnly_skillIndex()`

- `Void set_FBOnly_skillIndex(Int32)`

- `String get_FBOnly_skinId()`

- `Void set_FBOnly_skinId(String)`

- `Void set_FBOnly_skills(SharedCharSkillData[])`

- `String get_FBOnly_currentEquip()`

- `Void set_FBOnly_currentEquip(String)`

- `Void set_FBOnly_equip(ListDict`2)`

- `TmplData SafeTmpl(String)`

- `Int32 GetSkillIndex(Boolean)`

- `String GetSkinId()`

- `SharedCharSkillData GetSelectSkill(Boolean)`

- `Boolean HaveEquip()`

- `String GetSelectEquipId(Boolean)`

- `CharEquipInfo GetSelectEquipInfo(Boolean)`

- `Void SetSelectEquipId(String)`

- `Void SetOverrideSkillIndex(Int32)`

- `Void SetOverrideEquipId(String)`

- `Void ApplyModifiedCharData()`

- `Int32 _TryGetOverrideSkillIndex(Boolean)`

- `String _TryGetOverrideEquipId(Boolean)`

- `Void _SetSelectedSkillIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SharedCharData : IHotfixable
{
	private const Int32 INVALID_SKILL_INDEX; // 0x0
	public String charId; // 0x10
	public Int32 potentialRank; // 0x18
	private Int32 m_skillIndex; // 0x1c
	private String m_skinId; // 0x20
	private SharedCharSkillData[] m_skills; // 0x28
	private String m_selectEquip; // 0x30
	private ListDict`2 m_equips; // 0x38
	public Int32 mainSkillLvl; // 0x40
	public Int32 evolvePhase; // 0x44
	public Int32 level; // 0x48
	public Int32 favorPoint; // 0x4c
	public Dictionary`2 crisisRecord; // 0x50
	public Dictionary`2 crisisV2Record; // 0x58
	public String currentTmpl; // 0x60
	public ListDict`2 tmpl; // 0x68
	public Int32 overrideSkillIndex; // 0x70
	public String overrideEquipId; // 0x78
	private static DelegateBridge __Hotfix0_get_FBOnly_skillIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_FBOnly_skillIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_FBOnly_skinId; // 0x10
	private static DelegateBridge __Hotfix0_set_FBOnly_skinId; // 0x18
	private static DelegateBridge __Hotfix0_get_FBOnly_skills; // 0x20
	private static DelegateBridge __Hotfix0_set_FBOnly_skills; // 0x28
	private static DelegateBridge __Hotfix0_get_FBOnly_currentEquip; // 0x30
	private static DelegateBridge __Hotfix0_set_FBOnly_currentEquip; // 0x38
	private static DelegateBridge __Hotfix0_get_FBOnly_equip; // 0x40
	private static DelegateBridge __Hotfix0_set_FBOnly_equip; // 0x48
	private static DelegateBridge __Hotfix0_SafeTmpl; // 0x50
	private static DelegateBridge __Hotfix0_GetSkillIndex; // 0x58
	private static DelegateBridge __Hotfix0_GetSkinId; // 0x60
	private static DelegateBridge __Hotfix0_GetSkills; // 0x68
	private static DelegateBridge __Hotfix0_GetSelectSkill; // 0x70
	private static DelegateBridge __Hotfix0_HaveEquip; // 0x78
	private static DelegateBridge __Hotfix0_GetEquips; // 0x80
	private static DelegateBridge __Hotfix0_GetSelectEquipId; // 0x88
	private static DelegateBridge __Hotfix0_GetSelectEquipInfo; // 0x90
	private static DelegateBridge __Hotfix0_SetSelectEquipId; // 0x98
	private static DelegateBridge __Hotfix0_SetOverrideSkillIndex; // 0xa0
	private static DelegateBridge __Hotfix0_SetOverrideEquipId; // 0xa8
	private static DelegateBridge __Hotfix0_ApplyModifiedCharData; // 0xb0
	private static DelegateBridge __Hotfix0__SafeGet; // 0xb8
	private static DelegateBridge __Hotfix0__TryGetOverrideSkillIndex; // 0xc0
	private static DelegateBridge __Hotfix0__TryGetOverrideEquipId; // 0xc8
	private static DelegateBridge __Hotfix0__SetSelectedSkillIndex; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public Int32 FBOnly_skillIndex { get; set; }
	public String FBOnly_skinId { get; set; }
	public SharedCharSkillData[] FBOnly_skills { get; set; }
	public String FBOnly_currentEquip { get; set; }
	public ListDict`2 FBOnly_equip { get; set; }

	// RVA: 0x34a0f4c VA: 0x7595ab8f4c
	public Int32 get_FBOnly_skillIndex() { }
	// RVA: 0x34a0fb4 VA: 0x7595ab8fb4
	public Void set_FBOnly_skillIndex(Int32 value) { }
	// RVA: 0x34a1030 VA: 0x7595ab9030
	public String get_FBOnly_skinId() { }
	// RVA: 0x34a1098 VA: 0x7595ab9098
	public Void set_FBOnly_skinId(String value) { }
	// RVA: 0x34a111c VA: 0x7595ab911c
	public SharedCharSkillData[] get_FBOnly_skills() { }
	// RVA: 0x34a1184 VA: 0x7595ab9184
	public Void set_FBOnly_skills(SharedCharSkillData[] value) { }
	// RVA: 0x34a1208 VA: 0x7595ab9208
	public String get_FBOnly_currentEquip() { }
	// RVA: 0x34a1270 VA: 0x7595ab9270
	public Void set_FBOnly_currentEquip(String value) { }
	// RVA: 0x34a12f4 VA: 0x7595ab92f4
	public ListDict`2 get_FBOnly_equip() { }
	// RVA: 0x34a135c VA: 0x7595ab935c
	public Void set_FBOnly_equip(ListDict`2 value) { }
	// RVA: 0x34a13e0 VA: 0x7595ab93e0
	public TmplData SafeTmpl(String tmplId) { }
	// RVA: 0x34a148c VA: 0x7595ab948c
	public Int32 GetSkillIndex(Boolean forceFriendSet) { }
	// RVA: 0x34a15fc VA: 0x7595ab95fc
	public String GetSkinId() { }
	// RVA: 0x34a168c VA: 0x7595ab968c
	public SharedCharSkillData[] GetSkills() { }
	// RVA: 0x34a171c VA: 0x7595ab971c
	public SharedCharSkillData GetSelectSkill(Boolean forceFriendSet) { }
	// RVA: 0x34a17cc VA: 0x7595ab97cc
	public Boolean HaveEquip() { }
	// RVA: 0x34a1880 VA: 0x7595ab9880
	public ListDict`2 GetEquips() { }
	// RVA: 0x34a1910 VA: 0x7595ab9910
	public String GetSelectEquipId(Boolean forceFriendSet) { }
	// RVA: 0x34a1ab4 VA: 0x7595ab9ab4
	public CharEquipInfo GetSelectEquipInfo(Boolean forceFriendSet) { }
	// RVA: 0x34a1b98 VA: 0x7595ab9b98
	public Void SetSelectEquipId(String equipId) { }
	// RVA: 0x34a1c5c VA: 0x7595ab9c5c
	public Void SetOverrideSkillIndex(Int32 index) { }
	// RVA: 0x34a1d34 VA: 0x7595ab9d34
	public Void SetOverrideEquipId(String equip) { }
	// RVA: 0x34a1df8 VA: 0x7595ab9df8
	public Void ApplyModifiedCharData() { }
	// RVA: 0x VA: 0x0
	private static T _SafeGet(IList`1 list, Int32 index, T defaultVal) { }
	// RVA: 0x34a1554 VA: 0x7595ab9554
	private Int32 _TryGetOverrideSkillIndex(Boolean forceFriendSet) { }
	// RVA: 0x34a19e4 VA: 0x7595ab99e4
	private String _TryGetOverrideEquipId(Boolean forceFriendSet) { }
	// RVA: 0x34a1eb0 VA: 0x7595ab9eb0
	private Void _SetSelectedSkillIndex(Int32 index) { }
	// RVA: 0x34a1f54 VA: 0x7595ab9f54
	public Void .ctor() { }
}
```