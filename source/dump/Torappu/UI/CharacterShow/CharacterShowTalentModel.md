# CharacterShowTalentModel

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `UnlockType m_unlockType`

- `TalentData m_initTalentData`

- `TalentData m_finalTalentData`

- `String m_tokenKey`


## Properties

- `String name`

- `String desc`

- `UnlockCondition initUnlockCondition`

- `UnlockType unlockType`

- `String tokenKey`


## Methods

- `String get_name()`

- `String get_desc()`

- `UnlockCondition get_initUnlockCondition()`

- `UnlockType get_unlockType()`

- `String get_tokenKey()`

- `Void LoadData(TalentData, TalentData)`

- `Void LoadEquipNewTalent(EquipTalentData)`

- `UnlockType _UpdateUnlockType(TalentData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowTalentModel : IHotfixable
{
	private UnlockType m_unlockType; // 0x10
	private TalentData m_initTalentData; // 0x18
	private TalentData m_finalTalentData; // 0x20
	private String m_tokenKey; // 0x28
	private static DelegateBridge __Hotfix0_get_name; // 0x0
	private static DelegateBridge __Hotfix0_get_desc; // 0x8
	private static DelegateBridge __Hotfix0_get_initUnlockCondition; // 0x10
	private static DelegateBridge __Hotfix0_get_unlockType; // 0x18
	private static DelegateBridge __Hotfix0_get_tokenKey; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_LoadEquipNewTalent; // 0x30
	private static DelegateBridge __Hotfix0__UpdateUnlockType; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String name { get; }
	public String desc { get; }
	public UnlockCondition initUnlockCondition { get; }
	public UnlockType unlockType { get; }
	public String tokenKey { get; }

	// RVA: 0x2ce49bc VA: 0x75952fc9bc
	public String get_name() { }
	// RVA: 0x2ce4a50 VA: 0x75952fca50
	public String get_desc() { }
	// RVA: 0x2ce4af0 VA: 0x75952fcaf0
	public UnlockCondition get_initUnlockCondition() { }
	// RVA: 0x2ce4b68 VA: 0x75952fcb68
	public UnlockType get_unlockType() { }
	// RVA: 0x2ce4638 VA: 0x75952fc638
	public String get_tokenKey() { }
	// RVA: 0x2ce3714 VA: 0x75952fb714
	public Void LoadData(TalentData initTalentData, TalentData finalTalentData) { }
	// RVA: 0x2ce37d8 VA: 0x75952fb7d8
	public Void LoadEquipNewTalent(EquipTalentData equipTalentData) { }
	// RVA: 0x2ce4bd0 VA: 0x75952fcbd0
	private UnlockType _UpdateUnlockType(TalentData initTalentData) { }
	// RVA: 0x2ce36a4 VA: 0x75952fb6a4
	public Void .ctor() { }
}
```