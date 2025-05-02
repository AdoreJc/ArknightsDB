# ActivityFirstShopDetailComplexView

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `Text _shopBuyCount`

- `Text _shopItemName`

- `Text _shopItemTitle`

- `Text _shopPerCount`

- `Text _shopAvailCount`

- `Text _totalPrice`

- `Text _singlePrice`

- `Image _finalPriceIcon`

- `ShopDetailItemPileView _pileView`

- `Text _itemDetail`

- `Text _itemDetail_2`

- `ActivityShopData m_cacheViewModel`

- `Int32 m_shopBuyCount`

- `Int32 m_perPrice`


## Properties

- `Int32 ShopCount`


## Methods

- `Int32 get_ShopCount()`

- `Void ApplyData(ActivityShopData)`

- `Int32 RefreshNum(Int32)`

- `Void _RefreshClick()`

- `Void AddOne()`

- `Void MinusOne()`

- `Void AddToMax()`

- `Int32 GetMaxPrice(Int32, Int32)`

- `Void MinusToOne()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstShopDetailComplexView : MonoBehaviour, IHotfixable
{
	private Text _shopBuyCount; // 0x18
	private Text _shopItemName; // 0x20
	private Text _shopItemTitle; // 0x28
	private Text _shopPerCount; // 0x30
	private Text _shopAvailCount; // 0x38
	private Text _totalPrice; // 0x40
	private Text _singlePrice; // 0x48
	private Image _finalPriceIcon; // 0x50
	private ShopDetailItemPileView _pileView; // 0x58
	protected Text _itemDetail; // 0x60
	protected Text _itemDetail_2; // 0x68
	protected ActivityShopData m_cacheViewModel; // 0x70
	private Int32 m_shopBuyCount; // 0x78
	private Int32 m_perPrice; // 0x7c
	private static DelegateBridge __Hotfix0_get_ShopCount; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshNum; // 0x10
	private static DelegateBridge __Hotfix0__RefreshClick; // 0x18
	private static DelegateBridge __Hotfix0_AddOne; // 0x20
	private static DelegateBridge __Hotfix0_MinusOne; // 0x28
	private static DelegateBridge __Hotfix0_AddToMax; // 0x30
	private static DelegateBridge __Hotfix0_GetMaxPrice; // 0x38
	private static DelegateBridge __Hotfix0_MinusToOne; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 ShopCount { get; }

	// RVA: 0x348bc08 VA: 0x7595aa3c08
	public Int32 get_ShopCount() { }
	// RVA: 0x348bc70 VA: 0x7595aa3c70
	public Void ApplyData(ActivityShopData viewModel) { }
	// RVA: 0x348bf94 VA: 0x7595aa3f94
	public Int32 RefreshNum(Int32 currCount) { }
	// RVA: 0x348c04c VA: 0x7595aa404c
	private Void _RefreshClick() { }
	// RVA: 0x348c228 VA: 0x7595aa4228
	public Void AddOne() { }
	// RVA: 0x348c2a4 VA: 0x7595aa42a4
	public Void MinusOne() { }
	// RVA: 0x348c320 VA: 0x7595aa4320
	public Void AddToMax() { }
	// RVA: 0x348c120 VA: 0x7595aa4120
	public Int32 GetMaxPrice(Int32 price, Int32 availCount) { }
	// RVA: 0x348c3bc VA: 0x7595aa43bc
	public Void MinusToOne() { }
	// RVA: 0x348c434 VA: 0x7595aa4434
	public Void .ctor() { }
}
```