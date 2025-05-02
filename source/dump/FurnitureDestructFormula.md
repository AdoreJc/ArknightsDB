# FurnitureDestructFormula

**Namespace:** ` `


## Fields

- `String m_ingredientId`

- `String m_outcomeId`

- `Int32 m_outcomeCount`

- `Int32 m_byProductPercentage`

- `FormulaItem m_outcomeItem`

- `FormulaItem m_ingredientItem`


## Properties

- `Int32 id`

- `IFormulaItem outcome`

- `IFormulaItem ingredient1`

- `IFormulaItem ingredient2`

- `IFormulaItem ingredient3`

- `Int32 costGoldCount`

- `Boolean canBeProtected`

- `Int32 filterIndex`

- `Boolean unlocked`

- `String unlockMessage`

- `Int32 byProductPercentage`

- `String furniId`

- `Int32 apCost`

- `Int64 moodCost`

- `Int32 sortId`


## Methods

- `Int32 get_id()`

- `IFormulaItem get_outcome()`

- `IFormulaItem get_ingredient1()`

- `IFormulaItem get_ingredient2()`

- `IFormulaItem get_ingredient3()`

- `Int32 get_costGoldCount()`

- `Boolean get_canBeProtected()`

- `Int32 get_filterIndex()`

- `Boolean get_unlocked()`

- `String get_unlockMessage()`

- `Int32 get_byProductPercentage()`

- `String get_furniId()`

- `Int32 get_apCost()`

- `Int64 get_moodCost()`

- `Int32 get_sortId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FurnitureDestructFormula : IWorkshopFormula, IHotfixable
{
	private String m_ingredientId; // 0x10
	private String m_outcomeId; // 0x18
	private Int32 m_outcomeCount; // 0x20
	private Int32 m_byProductPercentage; // 0x24
	private FormulaItem m_outcomeItem; // 0x28
	private FormulaItem m_ingredientItem; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_id; // 0x8
	private static DelegateBridge __Hotfix0_get_outcome; // 0x10
	private static DelegateBridge __Hotfix0_get_ingredient1; // 0x18
	private static DelegateBridge __Hotfix0_get_ingredient2; // 0x20
	private static DelegateBridge __Hotfix0_get_ingredient3; // 0x28
	private static DelegateBridge __Hotfix0_get_costGoldCount; // 0x30
	private static DelegateBridge __Hotfix0_get_canBeProtected; // 0x38
	private static DelegateBridge __Hotfix0_get_filterIndex; // 0x40
	private static DelegateBridge __Hotfix0_get_unlocked; // 0x48
	private static DelegateBridge __Hotfix0_get_unlockMessage; // 0x50
	private static DelegateBridge __Hotfix0_get_byProductPercentage; // 0x58
	private static DelegateBridge __Hotfix0_get_furniId; // 0x60
	private static DelegateBridge __Hotfix0_get_apCost; // 0x68
	private static DelegateBridge __Hotfix0_get_moodCost; // 0x70
	private static DelegateBridge __Hotfix0_get_sortId; // 0x78

	public Int32 id { get; }
	public IFormulaItem outcome { get; }
	public IFormulaItem ingredient1 { get; }
	public IFormulaItem ingredient2 { get; }
	public IFormulaItem ingredient3 { get; }
	public Int32 costGoldCount { get; }
	public Boolean canBeProtected { get; }
	public Int32 filterIndex { get; }
	public Boolean unlocked { get; }
	public String unlockMessage { get; }
	public Int32 byProductPercentage { get; }
	public String furniId { get; }
	public Int32 apCost { get; }
	public Int64 moodCost { get; }
	public Int32 sortId { get; }

	// RVA: 0x3d65788 VA: 0x759637d788
	public Void .ctor(String ingredientId, String outcomeId, Int32 outcomeCount, Int32 byProductPercentage) { }
	// RVA: 0x3d65858 VA: 0x759637d858
	public Int32 get_id() { }
	// RVA: 0x3d658bc VA: 0x759637d8bc
	public IFormulaItem get_outcome() { }
	// RVA: 0x3d6598c VA: 0x759637d98c
	public IFormulaItem get_ingredient1() { }
	// RVA: 0x3d65a4c VA: 0x759637da4c
	public IFormulaItem get_ingredient2() { }
	// RVA: 0x3d65ab0 VA: 0x759637dab0
	public IFormulaItem get_ingredient3() { }
	// RVA: 0x3d65b14 VA: 0x759637db14
	public Int32 get_costGoldCount() { }
	// RVA: 0x3d65b78 VA: 0x759637db78
	public Boolean get_canBeProtected() { }
	// RVA: 0x3d65be0 VA: 0x759637dbe0
	public Int32 get_filterIndex() { }
	// RVA: 0x3d65c48 VA: 0x759637dc48
	public Boolean get_unlocked() { }
	// RVA: 0x3d65cb0 VA: 0x759637dcb0
	public String get_unlockMessage() { }
	// RVA: 0x3d60ab0 VA: 0x7596378ab0
	public Int32 get_byProductPercentage() { }
	// RVA: 0x3d63bec VA: 0x759637bbec
	public String get_furniId() { }
	// RVA: 0x3d65d34 VA: 0x759637dd34
	public Int32 get_apCost() { }
	// RVA: 0x3d60b18 VA: 0x7596378b18
	public Int64 get_moodCost() { }
	// RVA: 0x3d65d98 VA: 0x759637dd98
	public Int32 get_sortId() { }
}
```