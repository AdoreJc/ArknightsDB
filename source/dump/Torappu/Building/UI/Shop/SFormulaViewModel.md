# SFormulaViewModel

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Int32 formulaSortId`

- `ShopFormula formula`

- `String itemId`

- `ItemType itemType`

- `ItemBundle gainItem`

- `Boolean isUnlocked`

- `ItemRarity rarity`

- `Int64 costTime`

- `Int32 availableCount`

- `String name`

- `String unlockCond`

- `Boolean isAccelerated`


## Methods

- `Void LoadData(ShopFormula, ShopStockSnapshot, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SFormulaViewModel
{
	public Int32 formulaSortId; // 0x10
	public ShopFormula formula; // 0x18
	public String itemId; // 0x20
	public ItemType itemType; // 0x28
	public ItemBundle gainItem; // 0x30
	public Boolean isUnlocked; // 0x38
	public ItemRarity rarity; // 0x3c
	public Int64 costTime; // 0x40
	public Int32 availableCount; // 0x48
	public String name; // 0x50
	public String unlockCond; // 0x58
	public Boolean isAccelerated; // 0x60


	// RVA: 0x3db7e6c VA: 0x75963cfe6c
	public Void LoadData(ShopFormula formula, ShopStockSnapshot snapshot, Single speed) { }
	// RVA: 0x3db850c VA: 0x75963d050c
	public static Int32 CompareShopFormula(SFormulaViewModel a, SFormulaViewModel b, FormulaSortType focusType, Boolean isInverse) { }
	// RVA: 0x3db7e64 VA: 0x75963cfe64
	public Void .ctor() { }
}
```