# OverlapOptions

**Namespace:** ` `


## Fields

- `Boolean _verifySourceId`

- `Boolean _verifySourceProfession`

- `ProfessionCategory _verifySourceProfessions`

- `Boolean _isAllConditionOR`

- `OnOverlapPriority _overlapPriority`

- `Boolean _changeTargetGraphicColor`


## Properties

- `Boolean verifySourceID`

- `Boolean verifySourceProfession`

- `Int32 overlapPriority`

- `Boolean changeTargetGraphicColor`


## Methods

- `Boolean get_verifySourceID()`

- `Boolean get_verifySourceProfession()`

- `Int32 get_overlapPriority()`

- `Boolean get_changeTargetGraphicColor()`

- `Boolean VerifyOverlap(Character, BattleCharacterData)`

- `Void AddOverlapSourceId(String)`

- `Void RemoveOverlapSourceId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class OverlapOptions : IHotfixable
{
	private Boolean _verifySourceId; // 0x10
	private List`1 _verifySourceIds; // 0x18
	private Boolean _verifySourceProfession; // 0x20
	private ProfessionCategory _verifySourceProfessions; // 0x24
	private Boolean _isAllConditionOR; // 0x28
	private OnOverlapPriority _overlapPriority; // 0x2c
	private Boolean _changeTargetGraphicColor; // 0x30
	private HashSet`1 m_additionalSourceIds; // 0x38
	private static DelegateBridge __Hotfix0_get_verifySourceID; // 0x0
	private static DelegateBridge __Hotfix0_get_verifySourceProfession; // 0x8
	private static DelegateBridge __Hotfix0_get_overlapPriority; // 0x10
	private static DelegateBridge __Hotfix0_get_changeTargetGraphicColor; // 0x18
	private static DelegateBridge __Hotfix0_VerifyOverlap; // 0x20
	private static DelegateBridge __Hotfix0_AddOverlapSourceId; // 0x28
	private static DelegateBridge __Hotfix0_RemoveOverlapSourceId; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Boolean verifySourceID { get; }
	private Boolean verifySourceProfession { get; }
	public Int32 overlapPriority { get; }
	public Boolean changeTargetGraphicColor { get; }

	// RVA: 0x1c44a18 VA: 0x759425ca18
	private Boolean get_verifySourceID() { }
	// RVA: 0x1c44ab4 VA: 0x759425cab4
	private Boolean get_verifySourceProfession() { }
	// RVA: 0x1c44b1c VA: 0x759425cb1c
	public Int32 get_overlapPriority() { }
	// RVA: 0x1c44b84 VA: 0x759425cb84
	public Boolean get_changeTargetGraphicColor() { }
	// RVA: 0x1c44130 VA: 0x759425c130
	public Boolean VerifyOverlap(Character target, BattleCharacterData source) { }
	// RVA: 0x1c44c84 VA: 0x759425cc84
	public Void AddOverlapSourceId(String sourceId) { }
	// RVA: 0x1c44d44 VA: 0x759425cd44
	public Void RemoveOverlapSourceId(String sourceId) { }
	// RVA: 0x1c44e04 VA: 0x759425ce04
	public Void .ctor() { }
}
```