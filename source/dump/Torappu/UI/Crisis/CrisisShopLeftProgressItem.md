# CrisisShopLeftProgressItem

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `Image _itemSprite`

- `Image _priceSprite`

- `Sprite _priceIcon1`

- `Sprite _priceIconV2`

- `Text _priceText`

- `Text _index`

- `Text _count`

- `Image _backImage`

- `GameObject _charPart`

- `GameObject _isSoldOut`

- `GameObject _pricePart`

- `Transform _itemContainer`

- `Single _itemScaler`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void InitCommonPart(Int32, CrisisProgressShopItemViewModel)`

- `Void InitActiveData(Int32, Int32, CrisisProgressShopItemViewModel, CrisisShopVer)`

- `Void InitUnActiveData(Int32, Int32, CrisisProgressShopItemViewModel, Boolean)`

- `Single GetWidth(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopLeftProgressItem : MonoBehaviour, IHotfixable
{
	private Image _itemSprite; // 0x18
	private Image _priceSprite; // 0x20
	private Sprite _priceIcon1; // 0x28
	private Sprite _priceIconV2; // 0x30
	private Text _priceText; // 0x38
	private Text _index; // 0x40
	private Text _count; // 0x48
	private Image _backImage; // 0x50
	private GameObject _charPart; // 0x58
	private GameObject _isSoldOut; // 0x60
	private GameObject _pricePart; // 0x68
	private Transform _itemContainer; // 0x70
	private Single _itemScaler; // 0x78
	private UIItemCard m_itemCard; // 0x80
	private Boolean m_isInited; // 0x88
	private static readonly Single[] BACKIMAGEBLACKTYPE; // 0x0
	private const Single ACTIVE_SCALE; // 0x0
	private const Single TOTAL_WIDTH; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitCommonPart; // 0x10
	private static DelegateBridge __Hotfix0_InitActiveData; // 0x18
	private static DelegateBridge __Hotfix0_InitUnActiveData; // 0x20
	private static DelegateBridge __Hotfix0_GetWidth; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c3ba30 VA: 0x7595253a30
	private Void _InitIfNot() { }
	// RVA: 0x2c3bbe8 VA: 0x7595253be8
	private Void InitCommonPart(Int32 index, CrisisProgressShopItemViewModel item) { }
	// RVA: 0x2c3bed4 VA: 0x7595253ed4
	public Void InitActiveData(Int32 index, Int32 totalCount, CrisisProgressShopItemViewModel viewModel, CrisisShopVer shopVer) { }
	// RVA: 0x2c3c0d0 VA: 0x75952540d0
	public Void InitUnActiveData(Int32 index, Int32 totalCount, CrisisProgressShopItemViewModel viewModel, Boolean isSoldOut) { }
	// RVA: 0x2c3c010 VA: 0x7595254010
	public Single GetWidth(Int32 totalCount, Boolean isActive) { }
	// RVA: 0x2c3c294 VA: 0x7595254294
	public Void .ctor() { }
	// RVA: 0x2c3c320 VA: 0x7595254320
	private static Void .cctor() { }
}
```