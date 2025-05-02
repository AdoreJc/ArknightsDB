# DIYShop

**Namespace:** `Torappu.Building.DIY`


## Properties

- `Int32 currentCash`

- `Int32 currentFurnitureCoin`


## Methods

- `Int32 get_currentCash()`

- `Int32 get_currentFurnitureCoin()`

- `Void RefreshData(Action`1)`

- `Void TryBuyShopItem(IDIYShopItem, Int32, Int32, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYShop : IDIYShop
{
	private List`1 m_items; // 0x10

	public Int32 currentCash { get; }
	public Int32 currentFurnitureCoin { get; }

	// RVA: 0x37dee38 VA: 0x7595df6e38
	public Int32 get_currentCash() { }
	// RVA: 0x37dee9c VA: 0x7595df6e9c
	public Int32 get_currentFurnitureCoin() { }
	// RVA: 0x37def04 VA: 0x7595df6f04
	public Void RefreshData(Action`1 resultHandler) { }
	// RVA: 0x37df1b4 VA: 0x7595df71b4
	public IEnumerable`1 EnumShopItems() { }
	// RVA: 0x37df26c VA: 0x7595df726c
	public Void TryBuyShopItem(IDIYShopItem item, Int32 cashBuyCount, Int32 furnitureCoinBuyCount, Action`1 resultHandler) { }
	// RVA: 0x37df728 VA: 0x7595df7728
	public Void .ctor() { }
}
```