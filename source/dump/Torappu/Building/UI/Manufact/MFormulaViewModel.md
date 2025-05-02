# MFormulaViewModel

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Int32 formulaSortId`

- `ManufactFormula formula`

- `FormulaItemType formulaType`

- `Boolean isUnlocked`

- `ItemRarity rarity`

- `Int64 costTime`

- `Int32 availableCount`

- `String name`

- `String unlockCond`

- `Boolean isAccelerated`


## Methods

- `Void LoadData(ManufactFormula, ManufactSnapshot, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class MFormulaViewModel
{
	public Int32 formulaSortId; // 0x10
	public ManufactFormula formula; // 0x18
	public List`1 costs; // 0x20
	public FormulaItemType formulaType; // 0x28
	public Boolean isUnlocked; // 0x2c
	public ItemRarity rarity; // 0x30
	public Int64 costTime; // 0x38
	public Int32 availableCount; // 0x40
	public String name; // 0x48
	public String unlockCond; // 0x50
	public Boolean isAccelerated; // 0x58


	// RVA: 0x3e01860 VA: 0x7596419860
	public Void LoadData(ManufactFormula formula, ManufactSnapshot snapshot, Single speed) { }
	// RVA: 0x3e01cb8 VA: 0x7596419cb8
	public static Int32 CompareManufactFormula(MFormulaViewModel a, MFormulaViewModel b, FormulaSortType focusType, Boolean isInverse) { }
	// RVA: 0x3e01e94 VA: 0x7596419e94
	public Void .ctor() { }
}
```