# PlayerBuildingTradingOrder

**Namespace:** `Torappu`


## Fields

- `Int64 instId`

- `OrderType type`

- `ItemBundle gain`

- `Boolean extraCost`

- `TradingGoldTag specGoldTag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerBuildingTradingOrder
{
	public Int64 instId; // 0x10
	public OrderType type; // 0x18
	public ItemBundle[] delivery; // 0x20
	public ItemBundle gain; // 0x28
	public TradingOrderBuff[] buff; // 0x30
	public Boolean extraCost; // 0x38
	public TradingGoldTag specGoldTag; // 0x40


	// RVA: 0x32d7224 VA: 0x75958ef224
	public Void .ctor() { }
}
```