# GrocerySellView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text _textGoodName`

- `Image _imgGoodIcon`

- `Text _textStock`

- `Text _textSellDesc`

- `Text _textCustomerCount`

- `GameObject _panelShopIcon`

- `SimpleLayoutContent _shopIconContent`

- `GameObject _panelShopBtn`

- `SimpleLayoutContent _shopBtnContent`

- `CanvasGroup _canvasShopIcon`

- `CanvasGroup _canvasShopBtn`

- `SimpleLayoutContent _progressDotContent`

- `Slider _progressSlider`

- `Text _inquireCount`

- `Text _inquireMax`

- `CanvasGroup _canvasInquireBtn`

- `GameObject _panelTitle`

- `GameObject _panelInquire`

- `GameObject _panelSlider`

- `GameObject _panelCustomer`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `SellGoodState m_cacheGoodState`

- `Boolean m_cachedCanInquire`

- `Int32 m_cacheMaxProgress`

- `Adapter m_iconAdapter`

- `Adapter m_btnAdapter`

- `ProgressDotAdapter m_dotAdapter`

- `InquireFadeSwitchTween m_switchTween`


## Methods

- `Void StateOnlyRegisterTutorialGO()`

- `Void EventOnSellBtnClicked()`

- `Void EventOnInquireBtnClicked()`

- `Void EventOnInquireDetailBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellView : DataBinder`1, IHotfixable
{
	private static readonly Color PROGRESS_DOT_LIGHT_COLOR; // 0x0
	private static readonly Color PROGRESS_DOT_UNLIGHT_COLOR; // 0x10
	public const Single ALPHA_CANNOT_INQUIRE; // 0x0
	public const Single ALPHA_CAN_INQUIRE; // 0x0
	private GameObject[] _panelTitleImg; // 0x20
	private Text _textGoodName; // 0x28
	private Image _imgGoodIcon; // 0x30
	private Text _textStock; // 0x38
	private Text _textSellDesc; // 0x40
	private Text _textCustomerCount; // 0x48
	private GameObject _panelShopIcon; // 0x50
	private SimpleLayoutContent _shopIconContent; // 0x58
	private GameObject _panelShopBtn; // 0x60
	private SimpleLayoutContent _shopBtnContent; // 0x68
	private CanvasGroup _canvasShopIcon; // 0x70
	private CanvasGroup _canvasShopBtn; // 0x78
	private SimpleLayoutContent _progressDotContent; // 0x80
	private Slider _progressSlider; // 0x88
	private Text _inquireCount; // 0x90
	private Text _inquireMax; // 0x98
	private CanvasGroup _canvasInquireBtn; // 0xa0
	private GameObject _panelTitle; // 0xa8
	private GameObject _panelInquire; // 0xb0
	private GameObject _panelSlider; // 0xb8
	private GameObject _panelCustomer; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd0
	private List`1 m_cachedShopList; // 0xe0
	private SellGoodState m_cacheGoodState; // 0xe8
	private Boolean m_cachedCanInquire; // 0xec
	private Int32 m_cacheMaxProgress; // 0xf0
	private Adapter m_iconAdapter; // 0xf8
	private Adapter m_btnAdapter; // 0x100
	private ProgressDotAdapter m_dotAdapter; // 0x108
	private InquireFadeSwitchTween m_switchTween; // 0x110
	private static DelegateBridge __Hotfix0_StateOnlyRegisterTutorialGO; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_EventOnSellBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnInquireBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnInquireDetailBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x289cd0c VA: 0x7594eb4d0c
	public Void StateOnlyRegisterTutorialGO() { }
	// RVA: 0x289dd10 VA: 0x7594eb5d10
	public override Void OnValueChanged(GrocerySellProperty property) { }
	// RVA: 0x289e504 VA: 0x7594eb6504
	public Void EventOnSellBtnClicked() { }
	// RVA: 0x289e5b8 VA: 0x7594eb65b8
	public Void EventOnInquireBtnClicked() { }
	// RVA: 0x289e66c VA: 0x7594eb666c
	public Void EventOnInquireDetailBtnClicked() { }
	// RVA: 0x289e09c VA: 0x7594eb609c
	private Void _InitIfNot() { }
	// RVA: 0x289e8dc VA: 0x7594eb68dc
	public Void .ctor() { }
	// RVA: 0x289e97c VA: 0x7594eb697c
	private static Void .cctor() { }
}
```