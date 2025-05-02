# GrocerySellShopButtonView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelNotEmpty`

- `GameObject _panelUnknown`

- `GameObject _panelKnown`

- `Image _imgUnknownShopIcon`

- `Image _imgKnownShopIcon`

- `Text _textCustomerCount`

- `Text _textPrice`

- `CanvasGroup _canvasInquireBtn`

- `CanvasGroup _canvasAfterInquire`

- `UIStateFinder m_stateFinder`

- `Boolean m_cacheCanInquire`

- `InquireFadeSwitchTween m_switchTween`

- `Boolean m_hasInited`


## Methods

- `Void EventOnInquireBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellShopButtonView : GrocerySellShopButtonBaseView, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelNotEmpty; // 0x20
	private GameObject _panelUnknown; // 0x28
	private GameObject _panelKnown; // 0x30
	private Image _imgUnknownShopIcon; // 0x38
	private Image _imgKnownShopIcon; // 0x40
	private Text _textCustomerCount; // 0x48
	private Text _textPrice; // 0x50
	private CanvasGroup _canvasInquireBtn; // 0x58
	private CanvasGroup _canvasAfterInquire; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private Boolean m_cacheCanInquire; // 0x78
	private InquireFadeSwitchTween m_switchTween; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnInquireBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2899158 VA: 0x7594eb1158
	public override Void Render(GrocerySellResultShopModel viewModel, Boolean showSplitLine, Boolean canInquire) { }
	// RVA: 0x2899450 VA: 0x7594eb1450
	public Void EventOnInquireBtnClicked() { }
	// RVA: 0x2899380 VA: 0x7594eb1380
	private Void _InitIfNot() { }
	// RVA: 0x2899588 VA: 0x7594eb1588
	public Void .ctor() { }
}
```