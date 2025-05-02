# SFormulaGroupViewModel

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `FormulaOrderStruct m_orderStruct`

- `String selectedFormulaId`


## Properties

- `FormulaOrderStruct orderStruct`


## Methods

- `FormulaOrderStruct get_orderStruct()`

- `Void set_orderStruct(FormulaOrderStruct)`

- `Int32 <get_restrictedList>b__9_0(SFormulaViewModel, SFormulaViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SFormulaGroupViewModel
{
	private FormulaOrderStruct m_orderStruct; // 0x10
	private List`1 m_cachedList; // 0x20
	private readonly SFormulaViewModel UNSELECTED_FORMULA; // 0x28
	public List`1 rawFormulas; // 0x30
	public String selectedFormulaId; // 0x38

	public FormulaOrderStruct orderStruct { get; set; }
	public List`1 restrictedList { get; }

	// RVA: 0x3db89b8 VA: 0x75963d09b8
	public FormulaOrderStruct get_orderStruct() { }
	// RVA: 0x3db8264 VA: 0x75963d0264
	public Void set_orderStruct(FormulaOrderStruct value) { }
	// RVA: 0x3db89c4 VA: 0x75963d09c4
	public List`1 get_restrictedList() { }
	// RVA: 0x3db7d70 VA: 0x75963cfd70
	public Void .ctor() { }
	// RVA: 0x3db8bfc VA: 0x75963d0bfc
	private Int32 <get_restrictedList>b__9_0(SFormulaViewModel a, SFormulaViewModel b) { }
}
```