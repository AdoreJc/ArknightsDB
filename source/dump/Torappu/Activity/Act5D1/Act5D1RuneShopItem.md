# Act5D1RuneShopItem

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Button _button`

- `Sprite _rarityBG1`

- `Sprite _rarityBG2`

- `Sprite _rarityBG3`

- `Image _bg`

- `Text _cardName`

- `Text _offsetPercent`

- `Transform _itemContainer`

- `Text _remainCount`

- `GameObject _remainCountPart`

- `Text _price`

- `GameObject _offsetPricePart`

- `Single _itemScale`

- `CanvasGroup _soldOutCanvasGroup`

- `GameObject _soldOutObj`

- `Act5D1RuneShopState m_shop`

- `Act5D1ShopGood m_good`

- `UIItemCard m_itemCard`


## Methods

- `Void ApplyData(Act5D1RuneShopState, Act5D1ShopGood, Act5D1ProgressGoodItem[])`

- `Void _SynContent()`

- `Void OpenItemDetail()`

- `Act5D1ShopCommonViewModel _CalculateDetailModel()`

- `Act5D1ProgressGoodItem _GetCurPrgGoodItem()`

- `Void _SetSoldOutObj(Boolean)`

- `Void _HandleBuy()`

- `Void _HandleBuy(Int32)`

- `IEnumerator _ReceiveItemsCoroutine(RewardItemModel)`

- `Void EnterDetailEvent()`

- `Void OnClick()`

- `Void <_HandleBuy>b__26_0(Act5D1BuyGoodsResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneShopItem : MonoBehaviour, IHotfixable
{
	private Button _button; // 0x18
	private Sprite _rarityBG1; // 0x20
	private Sprite _rarityBG2; // 0x28
	private Sprite _rarityBG3; // 0x30
	private Image _bg; // 0x38
	private Text _cardName; // 0x40
	private Text _offsetPercent; // 0x48
	private Transform _itemContainer; // 0x50
	private Text _remainCount; // 0x58
	private GameObject _remainCountPart; // 0x60
	private Text _price; // 0x68
	private GameObject _offsetPricePart; // 0x70
	private Single _itemScale; // 0x78
	private CanvasGroup _soldOutCanvasGroup; // 0x80
	private GameObject _soldOutObj; // 0x88
	private Act5D1RuneShopState m_shop; // 0x90
	private Act5D1ShopGood m_good; // 0x98
	private Act5D1ProgressGoodItem[] m_progress; // 0xa0
	private UIItemCard m_itemCard; // 0xa8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__SynContent; // 0x8
	private static DelegateBridge __Hotfix0_OpenItemDetail; // 0x10
	private static DelegateBridge __Hotfix0__CalculateDetailModel; // 0x18
	private static DelegateBridge __Hotfix0__GetCurPrgGoodItem; // 0x20
	private static DelegateBridge __Hotfix0__SetSoldOutObj; // 0x28
	private static DelegateBridge __Hotfix0__HandleBuy; // 0x30
	private static DelegateBridge __Hotfix1__HandleBuy; // 0x38
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_EnterDetailEvent; // 0x48
	private static DelegateBridge __Hotfix0_OnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x31d4558 VA: 0x75957ec558
	public Void ApplyData(Act5D1RuneShopState shop, Act5D1ShopGood good, Act5D1ProgressGoodItem[] progress) { }
	// RVA: 0x31d4620 VA: 0x75957ec620
	private Void _SynContent() { }
	// RVA: 0x31d4de8 VA: 0x75957ecde8
	public Void OpenItemDetail() { }
	// RVA: 0x31d5028 VA: 0x75957ed028
	private Act5D1ShopCommonViewModel _CalculateDetailModel() { }
	// RVA: 0x31d4be8 VA: 0x75957ecbe8
	private Act5D1ProgressGoodItem _GetCurPrgGoodItem() { }
	// RVA: 0x31d4cfc VA: 0x75957eccfc
	private Void _SetSoldOutObj(Boolean isSoldOut) { }
	// RVA: 0x31d52c0 VA: 0x75957ed2c0
	private Void _HandleBuy() { }
	// RVA: 0x31d532c VA: 0x75957ed32c
	private Void _HandleBuy(Int32 buyCount) { }
	// RVA: 0x31d56f0 VA: 0x75957ed6f0
	private IEnumerator _ReceiveItemsCoroutine(RewardItemModel rewarditem) { }
	// RVA: 0x31d57e8 VA: 0x75957ed7e8
	public Void EnterDetailEvent() { }
	// RVA: 0x31d5850 VA: 0x75957ed850
	public Void OnClick() { }
	// RVA: 0x31d58b8 VA: 0x75957ed8b8
	public Void .ctor() { }
	// RVA: 0x31d5934 VA: 0x75957ed934
	private Void <_HandleBuy>b__26_0(Act5D1BuyGoodsResponse response) { }
}
```