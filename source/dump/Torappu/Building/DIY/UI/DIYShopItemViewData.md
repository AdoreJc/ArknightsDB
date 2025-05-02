# DIYShopItemViewData

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYItemViewData <itemViewData>k__BackingField`

- `IDIYShopItem <shopItem>k__BackingField`

- `Int32 count`

- `Int32 comfort`


## Properties

- `DIYItemViewData itemViewData`

- `IDIYShopItem shopItem`


## Methods

- `DIYItemViewData get_itemViewData()`

- `Void set_itemViewData(DIYItemViewData)`

- `IDIYShopItem get_shopItem()`

- `Void set_shopItem(IDIYShopItem)`

- `Void Uninitialize()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopItemViewData
{
	private DIYItemViewData <itemViewData>k__BackingField; // 0x10
	private IDIYShopItem <shopItem>k__BackingField; // 0x18
	public Int32 count; // 0x20
	public Int32 comfort; // 0x24

	public DIYItemViewData itemViewData { get; set; }
	public IDIYShopItem shopItem { get; set; }

	// RVA: 0x3805210 VA: 0x7595e1d210
	public DIYItemViewData get_itemViewData() { }
	// RVA: 0x3805218 VA: 0x7595e1d218
	public Void set_itemViewData(DIYItemViewData value) { }
	// RVA: 0x3805220 VA: 0x7595e1d220
	public IDIYShopItem get_shopItem() { }
	// RVA: 0x3805228 VA: 0x7595e1d228
	public Void set_shopItem(IDIYShopItem value) { }
	// RVA: 0x3805230 VA: 0x7595e1d230
	public Void Uninitialize() { }
	// RVA: 0x3803484 VA: 0x7595e1b484
	public Void .ctor() { }
}
```