# Formula

**Namespace:** ` `


## Fields

- `WorkshopFormula m_workshopFormula`

- `FormulaItem m_outcome`

- `FormulaItem m_ingredient1`

- `FormulaItem m_ingredient2`

- `FormulaItem m_ingredient3`

- `String m_unlockString`

- `Int32 m_cachedId`


## Properties

- `Int32 id`

- `IFormulaItem outcome`

- `IFormulaItem ingredient1`

- `IFormulaItem ingredient2`

- `IFormulaItem ingredient3`

- `Int32 costGoldCount`

- `Int64 moodCost`

- `Boolean canBeProtected`

- `Int32 filterIndex`

- `Int32 extraOutcomePercent`

- `Boolean unlocked`

- `String unlockMessage`

- `Int32 apCost`

- `FormulaItemType formulaType`

- `String buffType`

- `Int32 sortId`

- `String itemId`


## Methods

- `Int32 get_id()`

- `IFormulaItem get_outcome()`

- `IFormulaItem get_ingredient1()`

- `IFormulaItem get_ingredient2()`

- `IFormulaItem get_ingredient3()`

- `Int32 get_costGoldCount()`

- `Int64 get_moodCost()`

- `Boolean get_canBeProtected()`

- `Int32 get_filterIndex()`

- `Int32 get_extraOutcomePercent()`

- `Boolean get_unlocked()`

- `String get_unlockMessage()`

- `Int32 get_apCost()`

- `FormulaItemType get_formulaType()`

- `String get_buffType()`

- `Int32 get_sortId()`

- `String get_itemId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Formula : IWorkshopFormula, IHotfixable
{
	private WorkshopFormula m_workshopFormula; // 0x10
	private FormulaItem m_outcome; // 0x18
	private FormulaItem m_ingredient1; // 0x20
	private FormulaItem m_ingredient2; // 0x28
	private FormulaItem m_ingredient3; // 0x30
	private String m_unlockString; // 0x38
	private Int32 m_cachedId; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_id; // 0x8
	private static DelegateBridge __Hotfix0_get_outcome; // 0x10
	private static DelegateBridge __Hotfix0_get_ingredient1; // 0x18
	private static DelegateBridge __Hotfix0_get_ingredient2; // 0x20
	private static DelegateBridge __Hotfix0_get_ingredient3; // 0x28
	private static DelegateBridge __Hotfix0_get_costGoldCount; // 0x30
	private static DelegateBridge __Hotfix0_get_moodCost; // 0x38
	private static DelegateBridge __Hotfix0_get_canBeProtected; // 0x40
	private static DelegateBridge __Hotfix0_get_filterIndex; // 0x48
	private static DelegateBridge __Hotfix0_get_extraOutcomePercent; // 0x50
	private static DelegateBridge __Hotfix0_get_unlocked; // 0x58
	private static DelegateBridge __Hotfix0_get_unlockMessage; // 0x60
	private static DelegateBridge __Hotfix0_get_apCost; // 0x68
	private static DelegateBridge __Hotfix0_get_formulaType; // 0x70
	private static DelegateBridge __Hotfix0_get_buffType; // 0x78
	private static DelegateBridge __Hotfix0_get_sortId; // 0x80
	private static DelegateBridge __Hotfix0_get_itemId; // 0x88

	public Int32 id { get; }
	public IFormulaItem outcome { get; }
	public IFormulaItem ingredient1 { get; }
	public IFormulaItem ingredient2 { get; }
	public IFormulaItem ingredient3 { get; }
	public Int32 costGoldCount { get; }
	public Int64 moodCost { get; }
	public Boolean canBeProtected { get; }
	public Int32 filterIndex { get; }
	public Int32 extraOutcomePercent { get; }
	public Boolean unlocked { get; }
	public String unlockMessage { get; }
	public Int32 apCost { get; }
	public FormulaItemType formulaType { get; }
	public String buffType { get; }
	public Int32 sortId { get; }
	public String itemId { get; }

	// RVA: 0x3d64e40 VA: 0x759637ce40
	public Void .ctor(WorkshopFormula workshopFormula) { }
	// RVA: 0x3d612a0 VA: 0x75963792a0
	public Int32 get_id() { }
	// RVA: 0x3d64ef0 VA: 0x759637cef0
	public IFormulaItem get_outcome() { }
	// RVA: 0x3d64fc8 VA: 0x759637cfc8
	public IFormulaItem get_ingredient1() { }
	// RVA: 0x3d65114 VA: 0x759637d114
	public IFormulaItem get_ingredient2() { }
	// RVA: 0x3d65260 VA: 0x759637d260
	public IFormulaItem get_ingredient3() { }
	// RVA: 0x3d63338 VA: 0x759637b338
	public Int32 get_costGoldCount() { }
	// RVA: 0x3d61330 VA: 0x7596379330
	public Int64 get_moodCost() { }
	// RVA: 0x3d653ac VA: 0x759637d3ac
	public Boolean get_canBeProtected() { }
	// RVA: 0x3d65410 VA: 0x759637d410
	public Int32 get_filterIndex() { }
	// RVA: 0x3d60b7c VA: 0x7596378b7c
	public Int32 get_extraOutcomePercent() { }
	// RVA: 0x3d654b8 VA: 0x759637d4b8
	public Boolean get_unlocked() { }
	// RVA: 0x3d65524 VA: 0x759637d524
	public String get_unlockMessage() { }
	// RVA: 0x3d6558c VA: 0x759637d58c
	public Int32 get_apCost() { }
	// RVA: 0x3d6562c VA: 0x759637d62c
	public FormulaItemType get_formulaType() { }
	// RVA: 0x3d6122c VA: 0x759637922c
	public String get_buffType() { }
	// RVA: 0x3d656a0 VA: 0x759637d6a0
	public Int32 get_sortId() { }
	// RVA: 0x3d65714 VA: 0x759637d714
	public String get_itemId() { }
}
```