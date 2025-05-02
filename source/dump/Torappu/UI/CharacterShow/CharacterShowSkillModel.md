# CharacterShowSkillModel

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `SkillData m_skillData`

- `String m_rawDesc`

- `String m_displayDesc`

- `Boolean m_isUnlock`

- `Int32 m_mainSkillLv`

- `Int32 m_specializeLv`

- `UnlockCondition m_unlockCond`

- `String m_tokenKey`


## Properties

- `String skillId`

- `Boolean isUnlock`

- `String name`

- `Int32 spCost`

- `Int32 initCost`

- `String desc`

- `String rawDesc`

- `Int32 mainSkillLv`

- `Int32 specLevel`

- `UnlockCondition unlockCond`

- `String tokenKey`


## Methods

- `String get_skillId()`

- `Boolean get_isUnlock()`

- `String get_name()`

- `Int32 get_spCost()`

- `Int32 get_initCost()`

- `String get_desc()`

- `String get_rawDesc()`

- `Int32 get_mainSkillLv()`

- `Int32 get_specLevel()`

- `UnlockCondition get_unlockCond()`

- `String get_tokenKey()`

- `Void LoadData(SkillData, Boolean, Int32, Int32, UnlockCondition, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowSkillModel : IHotfixable
{
	private SkillData m_skillData; // 0x10
	private List`1 m_tags; // 0x18
	private String m_rawDesc; // 0x20
	private String m_displayDesc; // 0x28
	private Boolean m_isUnlock; // 0x30
	private Int32 m_mainSkillLv; // 0x34
	private Int32 m_specializeLv; // 0x38
	private UnlockCondition m_unlockCond; // 0x3c
	private String m_tokenKey; // 0x48
	private static DelegateBridge __Hotfix0_get_skillId; // 0x0
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_get_spCost; // 0x18
	private static DelegateBridge __Hotfix0_get_initCost; // 0x20
	private static DelegateBridge __Hotfix0_get_desc; // 0x28
	private static DelegateBridge __Hotfix0_get_rawDesc; // 0x30
	private static DelegateBridge __Hotfix0_get_tags; // 0x38
	private static DelegateBridge __Hotfix0_get_mainSkillLv; // 0x40
	private static DelegateBridge __Hotfix0_get_specLevel; // 0x48
	private static DelegateBridge __Hotfix0_get_unlockCond; // 0x50
	private static DelegateBridge __Hotfix0_get_tokenKey; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String skillId { get; }
	public Boolean isUnlock { get; }
	public String name { get; }
	public Int32 spCost { get; }
	public Int32 initCost { get; }
	public String desc { get; }
	public String rawDesc { get; }
	public List`1 tags { get; }
	public Int32 mainSkillLv { get; }
	public Int32 specLevel { get; }
	public UnlockCondition unlockCond { get; }
	public String tokenKey { get; }

	// RVA: 0x2ce2c98 VA: 0x75952fac98
	public String get_skillId() { }
	// RVA: 0x2ce2c30 VA: 0x75952fac30
	public Boolean get_isUnlock() { }
	// RVA: 0x2ce4c8c VA: 0x75952fcc8c
	public String get_name() { }
	// RVA: 0x2ce4d04 VA: 0x75952fcd04
	public Int32 get_spCost() { }
	// RVA: 0x2ce4d80 VA: 0x75952fcd80
	public Int32 get_initCost() { }
	// RVA: 0x2ce4e58 VA: 0x75952fce58
	public String get_desc() { }
	// RVA: 0x2ce4ec0 VA: 0x75952fcec0
	public String get_rawDesc() { }
	// RVA: 0x2ce4f28 VA: 0x75952fcf28
	public List`1 get_tags() { }
	// RVA: 0x2ce42d8 VA: 0x75952fc2d8
	public Int32 get_mainSkillLv() { }
	// RVA: 0x2ce4340 VA: 0x75952fc340
	public Int32 get_specLevel() { }
	// RVA: 0x2ce4f90 VA: 0x75952fcf90
	public UnlockCondition get_unlockCond() { }
	// RVA: 0x2ce45d0 VA: 0x75952fc5d0
	public String get_tokenKey() { }
	// RVA: 0x2ce4040 VA: 0x75952fc040
	public Void LoadData(SkillData skillData, Boolean isUnlock, Int32 mainSkillLv, Int32 specializeLevel, UnlockCondition unlockCond, String tokenKey) { }
	// RVA: 0x2ce3fd0 VA: 0x75952fbfd0
	public Void .ctor() { }
}
```