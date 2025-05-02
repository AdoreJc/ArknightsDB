# ManufactFormula

**Namespace:** ` `


## Fields

- `String formulaId`

- `String itemId`

- `Int32 count`

- `Int32 weight`

- `Int64 costPoint`

- `FormulaItemType formulaType`

- `String buffType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ManufactFormula
{
	public String formulaId; // 0x10
	public String itemId; // 0x18
	public Int32 count; // 0x20
	public Int32 weight; // 0x24
	public Int64 costPoint; // 0x28
	public FormulaItemType formulaType; // 0x30
	public String buffType; // 0x38
	public List`1 costs; // 0x40
	public List`1 requireRooms; // 0x48
	public List`1 requireStages; // 0x50


	// RVA: 0x33c7da8 VA: 0x75959dfda8
	public Void .ctor() { }
}
```