# ShopStockInfoViewModel

**Namespace:** `Torappu.Building`


## Fields

- `ShopStockSnapshot serviceSnapshot`

- `Int32 index`

- `Single buffSpeed`

- `Single baseSpeed`

- `Boolean isWorking`

- `BuildingCharModel character`

- `ShopFormula formula`

- `Int32 maxCount`

- `Boolean isUnlocked`

- `Int32 secsPerItem`


## Methods

- `Void LoadData(Int32, RoomSlotModel, ShopPhase, PlayerBuildingShopStock)`

- `ShopStockSnapshot CurrentSnapshot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class ShopStockInfoViewModel
{
	public ShopStockSnapshot serviceSnapshot; // 0x10
	public Int32 index; // 0x48
	public Single buffSpeed; // 0x4c
	public Single baseSpeed; // 0x50
	public Boolean isWorking; // 0x54
	public BuildingCharModel character; // 0x58
	public ShopFormula formula; // 0xc8
	public Int32 maxCount; // 0xd0
	public Boolean isUnlocked; // 0xd4
	public Int32 secsPerItem; // 0xd8


	// RVA: 0x3799dd0 VA: 0x7595db1dd0
	public Void LoadData(Int32 index, RoomSlotModel slotModel, ShopPhase shopData, PlayerBuildingShopStock playerStock) { }
	// RVA: 0x379a22c VA: 0x7595db222c
	public ShopStockSnapshot CurrentSnapshot() { }
	// RVA: 0x379a624 VA: 0x7595db2624
	public Void .ctor() { }
}
```