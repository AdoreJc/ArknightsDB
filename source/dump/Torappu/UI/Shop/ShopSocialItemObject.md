# ShopSocialItemObject

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _cardName`

- `GameObject _offsetPart`

- `Text _offsetPercent`

- `GameObject _endTimePart`

- `Text _endTimeText`

- `UIItemCard _itemCard`

- `Transform _itemContainer`

- `Text _remainCount`

- `GameObject _remainCountPart`

- `Text _originPrice`

- `Text _price`

- `GameObject _offsetPricePart`

- `Image _priceIcon`

- `Single _itemScale`

- `CanvasGroup _soldOutCanvasGroup`

- `GameObject _soldOutObj`

- `ShopCreditViewModel m_cacheObj`

- `ShopDetailPriceType m_cachePriceType`

- `UIItemCard m_itemCard`


## Methods

- `Void ApplySocialData(ShopCreditViewModel, SpriteHub)`

- `Void OnClick()`

- `UIItemCard _EnsureItemCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopSocialItemObject : MonoBehaviour
{
	private Text _cardName; // 0x18
	private GameObject _offsetPart; // 0x20
	private Text _offsetPercent; // 0x28
	private GameObject _endTimePart; // 0x30
	private Text _endTimeText; // 0x38
	private UIItemCard _itemCard; // 0x40
	private Transform _itemContainer; // 0x48
	private Text _remainCount; // 0x50
	private GameObject _remainCountPart; // 0x58
	private Text _originPrice; // 0x60
	private Text _price; // 0x68
	private GameObject _offsetPricePart; // 0x70
	private Image _priceIcon; // 0x78
	private Single _itemScale; // 0x80
	private CanvasGroup _soldOutCanvasGroup; // 0x88
	private GameObject _soldOutObj; // 0x90
	private ShopCreditViewModel m_cacheObj; // 0x98
	private ShopDetailPriceType m_cachePriceType; // 0xa0
	private UIItemCard m_itemCard; // 0xa8


	// RVA: 0x246d04c VA: 0x7594a8504c
	public Void ApplySocialData(ShopCreditViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x246d61c VA: 0x7594a8561c
	public Void OnClick() { }
	// RVA: 0x246d4d4 VA: 0x7594a854d4
	private UIItemCard _EnsureItemCard() { }
	// RVA: 0x246d628 VA: 0x7594a85628
	public Void .ctor() { }
}
```