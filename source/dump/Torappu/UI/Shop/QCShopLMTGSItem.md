# QCShopLMTGSItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Button _button`

- `Text _cardName`

- `GameObject _endTimePart`

- `Text _endTimeText`

- `Transform _itemContainer`

- `Text _remainCount`

- `GameObject _remainCountPart`

- `Text _price`

- `Image _priceIcon`

- `Single _itemScale`

- `CanvasGroup _soldOutCanvasGroup`

- `GameObject _soldOutObj`

- `UIAtlasImage _portraitImg`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `LMTGSViewModel m_cacheViewModel`


## Methods

- `Void _InitIfNot()`

- `Void RenderItem(LMTGSViewModel)`

- `Void TryOpenDetail()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopLMTGSItem : MonoBehaviour, IHotfixable
{
	private Button _button; // 0x18
	private Text _cardName; // 0x20
	private GameObject _endTimePart; // 0x28
	private Text _endTimeText; // 0x30
	private Transform _itemContainer; // 0x38
	private Text _remainCount; // 0x40
	private GameObject _remainCountPart; // 0x48
	private Text _price; // 0x50
	private Image _priceIcon; // 0x58
	private Single _itemScale; // 0x60
	private CanvasGroup _soldOutCanvasGroup; // 0x68
	private GameObject _soldOutObj; // 0x70
	private UIAtlasImage _portraitImg; // 0x78
	private Boolean m_isInited; // 0x80
	private UIItemCard m_itemCard; // 0x88
	private LMTGSViewModel m_cacheViewModel; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderItem; // 0x8
	private static DelegateBridge __Hotfix0_TryOpenDetail; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2455d78 VA: 0x7594a6dd78
	private Void _InitIfNot() { }
	// RVA: 0x2455f38 VA: 0x7594a6df38
	public Void RenderItem(LMTGSViewModel viewModel) { }
	// RVA: 0x24564bc VA: 0x7594a6e4bc
	public Void TryOpenDetail() { }
	// RVA: 0x2456528 VA: 0x7594a6e528
	public Void OnClick() { }
	// RVA: 0x24565a8 VA: 0x7594a6e5a8
	public Void .ctor() { }
}
```