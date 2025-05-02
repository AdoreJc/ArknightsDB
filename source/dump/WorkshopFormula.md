# WorkshopFormula

**Namespace:** ` `


## Fields

- `Int32 sortId`

- `String formulaId`

- `Int32 rarity`

- `String itemId`

- `Int32 count`

- `Int64 goldCost`

- `Int64 apCost`

- `FormulaItemType formulaType`

- `String buffType`

- `Single extraOutcomeRate`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class WorkshopFormula
{
	public Int32 sortId; // 0x10
	public String formulaId; // 0x18
	public Int32 rarity; // 0x20
	public String itemId; // 0x28
	public Int32 count; // 0x30
	public Int64 goldCost; // 0x38
	public Int64 apCost; // 0x40
	public FormulaItemType formulaType; // 0x48
	public String buffType; // 0x50
	public Single extraOutcomeRate; // 0x58
	public List`1 extraOutcomeGroup; // 0x60
	public List`1 costs; // 0x68
	public List`1 requireRooms; // 0x70
	public List`1 requireStages; // 0x78


	// RVA: 0x33c7dc8 VA: 0x75959dfdc8
	public Void .ctor() { }
}
```