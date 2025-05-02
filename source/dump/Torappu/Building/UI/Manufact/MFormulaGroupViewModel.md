# MFormulaGroupViewModel

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `FormulaOrderStruct m_orderStruct`

- `String selectedItemId`


## Properties

- `FormulaOrderStruct orderStruct`


## Methods

- `FormulaOrderStruct get_orderStruct()`

- `Void set_orderStruct(FormulaOrderStruct)`

- `Void LoadRawFormulas(ManufactInfoViewModel)`

- `Int32 <get_restrictedList>b__8_0(MFormulaViewModel, MFormulaViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class MFormulaGroupViewModel
{
	private List`1 rawFormulas; // 0x10
	private FormulaOrderStruct m_orderStruct; // 0x18
	private List`1 m_cachedList; // 0x28
	public String selectedItemId; // 0x30

	public FormulaOrderStruct orderStruct { get; set; }
	public List`1 restrictedList { get; }

	// RVA: 0x3e021e0 VA: 0x759641a1e0
	public FormulaOrderStruct get_orderStruct() { }
	// RVA: 0x3e01500 VA: 0x7596419500
	public Void set_orderStruct(FormulaOrderStruct value) { }
	// RVA: 0x3e021ec VA: 0x759641a1ec
	public List`1 get_restrictedList() { }
	// RVA: 0x3e010f8 VA: 0x75964190f8
	public Void LoadRawFormulas(ManufactInfoViewModel manufactInfo) { }
	// RVA: 0x3e01050 VA: 0x7596419050
	public Void .ctor() { }
	// RVA: 0x3e023f8 VA: 0x759641a3f8
	private Int32 <get_restrictedList>b__8_0(MFormulaViewModel a, MFormulaViewModel b) { }
}
```