# ShopDetailProgressItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Transform _itemContainer`

- `Image _priceSprite`

- `Text _priceText`

- `Text _index`

- `Text _count`

- `Image _backImage`

- `GameObject _isSoldOut`

- `GameObject _pricePart`

- `Single _uiScaler`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`


## Methods

- `Void _InitIfNot()`

- `Void InitCommonPart(Int32, QCProgressGoodItem)`

- `Void InitActiveData(Int32, ShopDetailPriceType, QCProgressGoodItem, SpriteHub, Int32)`

- `Void InitUnActiveData(Int32, ShopDetailPriceType, QCProgressGoodItem, Boolean, SpriteHub, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailProgressItem : MonoBehaviour, IHotfixable
{
	private const Int32 SPLIT_COUNT; // 0x0
	private const Single ACTIVE_5_WIDTH; // 0x0
	private const Single ACTIVE_MORE_THAN_5_WIDTH; // 0x0
	private const Single UNACTIVE_5_WIDTH; // 0x0
	private const Single UNACTIVE_MORE_THAN_5_WIDTH; // 0x0
	private Transform _itemContainer; // 0x18
	private Image _priceSprite; // 0x20
	private Text _priceText; // 0x28
	private Text _index; // 0x30
	private Text _count; // 0x38
	private Image _backImage; // 0x40
	private GameObject _isSoldOut; // 0x48
	private GameObject _pricePart; // 0x50
	private Single _uiScaler; // 0x58
	private Boolean m_isInited; // 0x5c
	private UIItemCard m_itemCard; // 0x60
	private static readonly Single[] BACKIMAGEBLACKTYPE; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitCommonPart; // 0x10
	private static DelegateBridge __Hotfix0_InitActiveData; // 0x18
	private static DelegateBridge __Hotfix0_InitUnActiveData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x243b5fc VA: 0x7594a535fc
	private Void _InitIfNot() { }
	// RVA: 0x243b760 VA: 0x7594a53760
	private Void InitCommonPart(Int32 index, QCProgressGoodItem item) { }
	// RVA: 0x243b934 VA: 0x7594a53934
	public Void InitActiveData(Int32 index, ShopDetailPriceType priceType, QCProgressGoodItem item, SpriteHub priceTypeHub, Int32 allCount) { }
	// RVA: 0x243bbdc VA: 0x7594a53bdc
	public Void InitUnActiveData(Int32 index, ShopDetailPriceType priceType, QCProgressGoodItem item, Boolean isSoldOut, SpriteHub priceTypeHub, Int32 allCount) { }
	// RVA: 0x243befc VA: 0x7594a53efc
	public Void .ctor() { }
	// RVA: 0x243bf88 VA: 0x7594a53f88
	private static Void .cctor() { }
}
```