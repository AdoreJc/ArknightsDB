# RoguelikeShopDetailView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _panelWidgets`

- `CanvasGroup _alphaHandler`

- `Single _fadeDuration`

- `Text _textName`

- `Text _textUsage`

- `Text _textDesc`

- `Text _textPrice`

- `Color _priceColorAffordable`

- `Color _priceColorLack`

- `Color _priceColorRecycle`

- `Text _textBuyName`

- `Image _imageIcon`

- `Vector2 _hidePos`

- `Vector2 _showPos`

- `CanvasGroup _btnAlphaHandler`

- `Single _btnInactiveAlpha`

- `Button _btnConfirm`

- `TwoStateToggle _toggleConfirmText`

- `RoguelikeShopDetailExtraInfoView _extraInfoView`

- `RectTransform _iconPluginContainer`

- `Boolean m_inited`

- `RoguelikeGameShopSwitchTween m_switchTween`

- `UIStateFinder m_finder`

- `RoguelikeShopDetailControllerBindings m_controllerBindings`

- `RoguelikeGoodsObjPlugin m_pluginIcon`


## Methods

- `RoguelikeGameShopStatusEnum GetShopStatus()`

- `RoguelikeGameShopStatusEnum GetRivalStatus()`

- `Void Render(RoguelikeGoodsViewModel)`

- `Single SetShow(Boolean, Boolean, RoguelikeGameShopStatusEnum)`

- `Void BindShopController(RoguelikeShopDetailControllerBindings)`

- `Void _InitIfNot()`

- `Void _InjectExtraInfoPlugin(RoguelikeShopDetailExtraInfoPlugin)`

- `Void _SetupIconPluginIfNeed()`

- `Void _RenderIcon(RoguelikeGoodsViewModel)`

- `Void OnBtnConfirm()`

- `Void OnBtnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopDetailView : MonoBehaviour, IHotfixable, IRoguelikeGameShopVisibility
{
	private RectTransform _panelWidgets; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private Single _fadeDuration; // 0x28
	private Text _textName; // 0x30
	private Text _textUsage; // 0x38
	private Text _textDesc; // 0x40
	private Text _textPrice; // 0x48
	private Color _priceColorAffordable; // 0x50
	private Color _priceColorLack; // 0x60
	private Color _priceColorRecycle; // 0x70
	private Text _textBuyName; // 0x80
	private Image _imageIcon; // 0x88
	private List`1 _buyPanels; // 0x90
	private List`1 _recyclePanels; // 0x98
	private Vector2 _hidePos; // 0xa0
	private Vector2 _showPos; // 0xa8
	private CanvasGroup _btnAlphaHandler; // 0xb0
	private Single _btnInactiveAlpha; // 0xb8
	private Button _btnConfirm; // 0xc0
	private TwoStateToggle _toggleConfirmText; // 0xc8
	private RoguelikeShopDetailExtraInfoView _extraInfoView; // 0xd0
	private RectTransform _iconPluginContainer; // 0xd8
	private Boolean m_inited; // 0xe0
	private RoguelikeGameShopSwitchTween m_switchTween; // 0xe8
	private UIStateFinder m_finder; // 0xf0
	private RoguelikeShopDetailControllerBindings m_controllerBindings; // 0x100
	private RoguelikeGoodsObjPlugin m_pluginIcon; // 0x108
	private static DelegateBridge __Hotfix0_GetShopStatus; // 0x0
	private static DelegateBridge __Hotfix0_GetRivalStatus; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SetShow; // 0x18
	private static DelegateBridge __Hotfix0_BindShopController; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__InjectExtraInfoPlugin; // 0x30
	private static DelegateBridge __Hotfix0__SetupIconPluginIfNeed; // 0x38
	private static DelegateBridge __Hotfix0__RenderIcon; // 0x40
	private static DelegateBridge __Hotfix0_OnBtnConfirm; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnCancel; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2ae81b8 VA: 0x75951001b8
	public RoguelikeGameShopStatusEnum GetShopStatus() { }
	// RVA: 0x2ae8220 VA: 0x7595100220
	public RoguelikeGameShopStatusEnum GetRivalStatus() { }
	// RVA: 0x2ae8284 VA: 0x7595100284
	public Void Render(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae89a0 VA: 0x75951009a0
	public Single SetShow(Boolean isShow, Boolean fastMode, RoguelikeGameShopStatusEnum current) { }
	// RVA: 0x2ae8a68 VA: 0x7595100a68
	public Void BindShopController(RoguelikeShopDetailControllerBindings bindings) { }
	// RVA: 0x2ae8580 VA: 0x7595100580
	private Void _InitIfNot() { }
	// RVA: 0x2ae8b7c VA: 0x7595100b7c
	private Void _InjectExtraInfoPlugin(RoguelikeShopDetailExtraInfoPlugin plugin) { }
	// RVA: 0x2ae86b8 VA: 0x75951006b8
	private Void _SetupIconPluginIfNeed() { }
	// RVA: 0x2ae87f4 VA: 0x75951007f4
	private Void _RenderIcon(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae8c6c VA: 0x7595100c6c
	public Void OnBtnConfirm() { }
	// RVA: 0x2ae8d68 VA: 0x7595100d68
	public Void OnBtnCancel() { }
	// RVA: 0x2ae8e64 VA: 0x7595100e64
	public Void .ctor() { }
}
```