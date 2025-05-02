# DIYThemeItemViewData

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
public class DIYThemeItemViewData
{
	private DIYItemViewData <itemViewData>k__BackingField; // 0x10
	private IDIYShopItem <shopItem>k__BackingField; // 0x18
	public Int32 count; // 0x20
	public Int32 comfort; // 0x24

	public DIYItemViewData itemViewData { get; set; }
	public IDIYShopItem shopItem { get; set; }

	// RVA: 0x381048c VA: 0x7595e2848c
	public DIYItemViewData get_itemViewData() { }
	// RVA: 0x3810494 VA: 0x7595e28494
	public Void set_itemViewData(DIYItemViewData value) { }
	// RVA: 0x381049c VA: 0x7595e2849c
	public IDIYShopItem get_shopItem() { }
	// RVA: 0x38104a4 VA: 0x7595e284a4
	public Void set_shopItem(IDIYShopItem value) { }
	// RVA: 0x38104ac VA: 0x7595e284ac
	public Void Uninitialize() { }
	// RVA: 0x38104c8 VA: 0x7595e284c8
	public Void .ctor() { }
}
```