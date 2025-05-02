# DetailCommonViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `String goodId`

- `String giftPackageId`

- `ShopType shopType`

- `ShopDetailType type`

- `ShopDetailPriceType m_priceType`

- `UIItemViewModel m_priceItem`

- `Int32 price`

- `Int32 originPrice`

- `Single discount`

- `Int64 endTime`

- `Int32 soldCount`

- `Int32 ableToBuyCount`

- `String displayName`

- `ItemBundle soldItem`


## Properties

- `ShopDetailPriceType priceType`

- `UIItemViewModel priceItem`


## Methods

- `ShopDetailPriceType get_priceType()`

- `Void set_priceType(ShopDetailPriceType)`

- `UIItemViewModel get_priceItem()`

- `Void set_priceItem(UIItemViewModel)`

- `ShopCashInfo GetCashInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class DetailCommonViewModel : IHotfixable
{
	public String goodId; // 0x10
	public String giftPackageId; // 0x18
	public ShopType shopType; // 0x20
	public ShopDetailType type; // 0x24
	private ShopDetailPriceType m_priceType; // 0x28
	private UIItemViewModel m_priceItem; // 0x30
	public Int32 price; // 0x38
	public Int32 originPrice; // 0x3c
	public Single discount; // 0x40
	public Int64 endTime; // 0x48
	public Int32 soldCount; // 0x50
	public Int32 ableToBuyCount; // 0x54
	public String displayName; // 0x58
	public ItemBundle soldItem; // 0x60
	private static DelegateBridge __Hotfix0_get_priceType; // 0x0
	private static DelegateBridge __Hotfix0_set_priceType; // 0x8
	private static DelegateBridge __Hotfix0_get_priceItem; // 0x10
	private static DelegateBridge __Hotfix0_set_priceItem; // 0x18
	private static DelegateBridge __Hotfix0_GetCashInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ShopDetailPriceType priceType { get; set; }
	public UIItemViewModel priceItem { get; set; }

	// RVA: 0x242b510 VA: 0x7594a43510
	public ShopDetailPriceType get_priceType() { }
	// RVA: 0x2427bc4 VA: 0x7594a3fbc4
	public Void set_priceType(ShopDetailPriceType value) { }
	// RVA: 0x242b578 VA: 0x7594a43578
	public UIItemViewModel get_priceItem() { }
	// RVA: 0x242b744 VA: 0x7594a43744
	public Void set_priceItem(UIItemViewModel value) { }
	// RVA: 0x242b7c8 VA: 0x7594a437c8
	public ShopCashInfo GetCashInfo() { }
	// RVA: 0x2427b54 VA: 0x7594a3fb54
	public Void .ctor() { }
}
```