# ShopInfoViewModel

**Namespace:** `Torappu.Building`


## Fields

- `Int32 capacity`

- `Int32 unlockStockNum`


## Methods

- `Void LoadData(RoomSlotModel, PlayerBuildingShop)`

- `Int32 CalcTotalOutputCount()`

- `Void UpdateCountDownForStocks(ref, ref, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class ShopInfoViewModel
{
	public ListDict`2 serverOutput; // 0x10
	public Int32 capacity; // 0x18
	public Int32 unlockStockNum; // 0x1c
	public List`1 stocks; // 0x20


	// RVA: 0x379a6ec VA: 0x7595db26ec
	public Void LoadData(RoomSlotModel slotModel, PlayerBuildingShop playerShop) { }
	// RVA: 0x379a9d4 VA: 0x7595db29d4
	public Int32 CalcTotalOutputCount() { }
	// RVA: 0x379ac48 VA: 0x7595db2c48
	public Void UpdateCountDownForStocks(ref CountDownTask[] countDowns, ref ShopStockSnapshot[] snapshots, Action onCountDownTimeout) { }
	// RVA: 0x379af3c VA: 0x7595db2f3c
	public ListDict`2 CalcTotalOutputE() { }
	// RVA: 0x379b1a4 VA: 0x7595db31a4
	public Void .ctor() { }
}
```