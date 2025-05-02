# QCShopEPGSItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Button _button`

- `Text _cardName`

- `Transform _itemContainer`

- `Text _remainCount`

- `GameObject _remainCountPart`

- `Text _price`

- `Image _priceIcon`

- `Single _itemScale`

- `CanvasGroup _soldOutCanvasGroup`

- `GameObject _soldOutObj`

- `UIItemCard m_itemCard`

- `EPGSViewModel m_cacheViewModel`


## Properties

- `EPGSViewModel cacheViewModel`


## Methods

- `UIItemCard _EnsureItemCard()`

- `Void Render(EPGSViewModel)`

- `EPGSViewModel get_cacheViewModel()`

- `Void TryOpenDetail()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopEPGSItem : MonoBehaviour, IHotfixable
{
	private Button _button; // 0x18
	private Text _cardName; // 0x20
	private Transform _itemContainer; // 0x28
	private Text _remainCount; // 0x30
	private GameObject _remainCountPart; // 0x38
	private Text _price; // 0x40
	private Image _priceIcon; // 0x48
	private Single _itemScale; // 0x50
	private CanvasGroup _soldOutCanvasGroup; // 0x58
	private GameObject _soldOutObj; // 0x60
	private UIItemCard m_itemCard; // 0x68
	private EPGSViewModel m_cacheViewModel; // 0x70
	private static DelegateBridge __Hotfix0__EnsureItemCard; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_get_cacheViewModel; // 0x10
	private static DelegateBridge __Hotfix0_TryOpenDetail; // 0x18
	private static DelegateBridge __Hotfix0_OnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public EPGSViewModel cacheViewModel { get; }

	// RVA: 0x245227c VA: 0x7594a6a27c
	private UIItemCard _EnsureItemCard() { }
	// RVA: 0x2452430 VA: 0x7594a6a430
	public Void Render(EPGSViewModel viewModel) { }
	// RVA: 0x2452748 VA: 0x7594a6a748
	public EPGSViewModel get_cacheViewModel() { }
	// RVA: 0x24527b0 VA: 0x7594a6a7b0
	public Void TryOpenDetail() { }
	// RVA: 0x245281c VA: 0x7594a6a81c
	public Void OnClick() { }
	// RVA: 0x245289c VA: 0x7594a6a89c
	public Void .ctor() { }
}
```