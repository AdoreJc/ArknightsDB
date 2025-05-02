# RoguelikeGoodsObjView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Color _normalTextColor`

- `Color _nonAffordableTextColor`

- `Color _normalGoldColor`

- `Single _soldoutAlpha`

- `GameObject _panelGoods`

- `GameObject _panelGoodSoldOut`

- `GameObject _panelBank`

- `GameObject _panelLockSlot`

- `CanvasGroup _canvasGroup`

- `Text _textName`

- `Text _textPrice`

- `Text _textPriceCaption`

- `UIAtlasImage _imgGold`

- `GameObject _recyclePanel`

- `UIAtlasImage _imgBkgNormal`

- `UIAtlasImage _imgBkgLack`

- `UIAtlasImage _imgBkgRecycle`

- `Image _imageIcon`

- `Button _buttonSelf`

- `RectTransform _panelWidgets`

- `CanvasGroup _canvasGroupWidgets`

- `Single _tweenDuration`

- `Single _tweenInternvalX`

- `Single _tweenInterval`

- `Ease _tweenShowEase`

- `Ease _tweenHideEase`

- `Text _textBankCurrent`

- `GameObject _faultyIconGo`

- `GameObject _normalPricePanel`

- `RectTransform _iconPluginContainer`

- `RectTransform _discountPluginContainer`

- `Int32 m_cachedIndex`

- `RoguelikeGoodsViewModel m_cacheModel`

- `RoguelikeGameShopSwitchTween m_switchTween`

- `Single m_tweenHideX`

- `RoguelikeGoodsObjPlugin m_pluginDiscount`

- `RoguelikeGoodsObjPlugin m_pluginIcon`

- `UIStateFinder m_finder`

- `Action <onBankClicked>k__BackingField`

- `SwitchPlayHandler <switchPlayHandler>k__BackingField`


## Properties

- `Action onBankClicked`

- `SwitchPlayHandler switchPlayHandler`

- `Single tweenDuration`

- `Single tweenInterval`


## Methods

- `Void set_onGoodsClicked(Action`1)`

- `Void set_onLockSlotClick(Action`1)`

- `Action get_onBankClicked()`

- `Void set_onBankClicked(Action)`

- `SwitchPlayHandler get_switchPlayHandler()`

- `Void set_switchPlayHandler(SwitchPlayHandler)`

- `Single get_tweenDuration()`

- `Single get_tweenInterval()`

- `Void EventOnGoodsClicked()`

- `Void EventOnBankClicked()`

- `Void EventOnLockSlotClick()`

- `Void InjectPlugins(List`1)`

- `Void Render(Int32, RoguelikeGoodsViewModel)`

- `Void _RenderLockSlotView(RoguelikeGoodsViewModel)`

- `Void _RenderBankEntryView(RoguelikeGoodsViewModel)`

- `Void _RenderGoodsItemView(RoguelikeGoodsViewModel)`

- `Void _SetupTween()`

- `Void _SetupPluginsIfNeeded()`

- `Void _SetupDiscountPluginIfNeed()`

- `Void _SetupIconPluginIfNeed()`

- `RoguelikeGoodsObjPlugin TryGetPluginByType(RoguelikeShopGoodPluginType)`

- `Void _RenderPlugins(RoguelikeGoodsViewModel)`

- `Void _RenderDiscountPlugin(RoguelikeGoodsViewModel)`

- `Void _RenderIconPlugin(RoguelikeGoodsViewModel)`

- `Void _UpdateSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGoodsObjView : MonoBehaviour, IHotfixable
{
	private const Int32 GOODS_COLUMN_CNT; // 0x0
	private Color _normalTextColor; // 0x18
	private Color _nonAffordableTextColor; // 0x28
	private Color _normalGoldColor; // 0x38
	private Single _soldoutAlpha; // 0x48
	private GameObject _panelGoods; // 0x50
	private GameObject _panelGoodSoldOut; // 0x58
	private GameObject _panelBank; // 0x60
	private GameObject _panelLockSlot; // 0x68
	private CanvasGroup _canvasGroup; // 0x70
	private Text _textName; // 0x78
	private Text _textPrice; // 0x80
	private Text _textPriceCaption; // 0x88
	private UIAtlasImage _imgGold; // 0x90
	private GameObject _recyclePanel; // 0x98
	private UIAtlasImage _imgBkgNormal; // 0xa0
	private UIAtlasImage _imgBkgLack; // 0xa8
	private UIAtlasImage _imgBkgRecycle; // 0xb0
	private Image _imageIcon; // 0xb8
	private Button _buttonSelf; // 0xc0
	private RectTransform _panelWidgets; // 0xc8
	private CanvasGroup _canvasGroupWidgets; // 0xd0
	private Single _tweenDuration; // 0xd8
	private Single _tweenInternvalX; // 0xdc
	private Single _tweenInterval; // 0xe0
	private Ease _tweenShowEase; // 0xe4
	private Ease _tweenHideEase; // 0xe8
	private Text _textBankCurrent; // 0xf0
	private GameObject _faultyIconGo; // 0xf8
	private GameObject _normalPricePanel; // 0x100
	private RectTransform _iconPluginContainer; // 0x108
	private RectTransform _discountPluginContainer; // 0x110
	private Int32 m_cachedIndex; // 0x118
	private RoguelikeGoodsViewModel m_cacheModel; // 0x120
	private RoguelikeGameShopSwitchTween m_switchTween; // 0x128
	private Single m_tweenHideX; // 0x130
	private List`1 m_pluginPrefabList; // 0x138
	private RoguelikeGoodsObjPlugin m_pluginDiscount; // 0x140
	private RoguelikeGoodsObjPlugin m_pluginIcon; // 0x148
	private UIStateFinder m_finder; // 0x150
	private Action`1 <onGoodsClicked>k__BackingField; // 0x160
	private Action`1 <onLockSlotClick>k__BackingField; // 0x168
	private Action <onBankClicked>k__BackingField; // 0x170
	private SwitchPlayHandler <switchPlayHandler>k__BackingField; // 0x178
	private static DelegateBridge __Hotfix0_get_onGoodsClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onGoodsClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onLockSlotClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onLockSlotClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onBankClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onBankClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_switchPlayHandler; // 0x30
	private static DelegateBridge __Hotfix0_set_switchPlayHandler; // 0x38
	private static DelegateBridge __Hotfix0_get_tweenDuration; // 0x40
	private static DelegateBridge __Hotfix0_get_tweenInterval; // 0x48
	private static DelegateBridge __Hotfix0_EventOnGoodsClicked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBankClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnLockSlotClick; // 0x60
	private static DelegateBridge __Hotfix0_InjectPlugins; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x70
	private static DelegateBridge __Hotfix0__RenderLockSlotView; // 0x78
	private static DelegateBridge __Hotfix0__RenderBankEntryView; // 0x80
	private static DelegateBridge __Hotfix0__RenderGoodsItemView; // 0x88
	private static DelegateBridge __Hotfix0__SetupTween; // 0x90
	private static DelegateBridge __Hotfix0__SetupPluginsIfNeeded; // 0x98
	private static DelegateBridge __Hotfix0__SetupDiscountPluginIfNeed; // 0xa0
	private static DelegateBridge __Hotfix0__SetupIconPluginIfNeed; // 0xa8
	private static DelegateBridge __Hotfix0_TryGetPluginByType; // 0xb0
	private static DelegateBridge __Hotfix0__RenderPlugins; // 0xb8
	private static DelegateBridge __Hotfix0__RenderDiscountPlugin; // 0xc0
	private static DelegateBridge __Hotfix0__RenderIconPlugin; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateSwitchTween; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	private Action`1 onGoodsClicked { get; set; }
	private Action`1 onLockSlotClick { get; set; }
	private Action onBankClicked { get; set; }
	private SwitchPlayHandler switchPlayHandler { get; set; }
	public Single tweenDuration { get; }
	public Single tweenInterval { get; }

	// RVA: 0x2ae4c3c VA: 0x75950fcc3c
	private Action`1 get_onGoodsClicked() { }
	// RVA: 0x2ae4ca4 VA: 0x75950fcca4
	public Void set_onGoodsClicked(Action`1 value) { }
	// RVA: 0x2ae4d28 VA: 0x75950fcd28
	private Action`1 get_onLockSlotClick() { }
	// RVA: 0x2ae4d90 VA: 0x75950fcd90
	public Void set_onLockSlotClick(Action`1 value) { }
	// RVA: 0x2ae4e14 VA: 0x75950fce14
	private Action get_onBankClicked() { }
	// RVA: 0x2ae4e7c VA: 0x75950fce7c
	public Void set_onBankClicked(Action value) { }
	// RVA: 0x2ae4f00 VA: 0x75950fcf00
	private SwitchPlayHandler get_switchPlayHandler() { }
	// RVA: 0x2ae4f68 VA: 0x75950fcf68
	public Void set_switchPlayHandler(SwitchPlayHandler value) { }
	// RVA: 0x2ae4fec VA: 0x75950fcfec
	public Single get_tweenDuration() { }
	// RVA: 0x2ae5054 VA: 0x75950fd054
	public Single get_tweenInterval() { }
	// RVA: 0x2ae50bc VA: 0x75950fd0bc
	public Void EventOnGoodsClicked() { }
	// RVA: 0x2ae515c VA: 0x75950fd15c
	public Void EventOnBankClicked() { }
	// RVA: 0x2ae51f8 VA: 0x75950fd1f8
	public Void EventOnLockSlotClick() { }
	// RVA: 0x2ae5298 VA: 0x75950fd298
	public Void InjectPlugins(List`1 plugins) { }
	// RVA: 0x2ae531c VA: 0x75950fd31c
	public Void Render(Int32 index, RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae58bc VA: 0x75950fd8bc
	private Void _RenderLockSlotView(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae54e4 VA: 0x75950fd4e4
	private Void _RenderBankEntryView(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae55b4 VA: 0x75950fd5b4
	private Void _RenderGoodsItemView(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae5b4c VA: 0x75950fdb4c
	private Void _SetupTween() { }
	// RVA: 0x2ae5474 VA: 0x75950fd474
	private Void _SetupPluginsIfNeeded() { }
	// RVA: 0x2ae5c78 VA: 0x75950fdc78
	private Void _SetupDiscountPluginIfNeed() { }
	// RVA: 0x2ae5db4 VA: 0x75950fddb4
	private Void _SetupIconPluginIfNeed() { }
	// RVA: 0x2ae5ef0 VA: 0x75950fdef0
	private RoguelikeGoodsObjPlugin TryGetPluginByType(RoguelikeShopGoodPluginType type) { }
	// RVA: 0x2ae5934 VA: 0x75950fd934
	private Void _RenderPlugins(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae6064 VA: 0x75950fe064
	private Void _RenderDiscountPlugin(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae6170 VA: 0x75950fe170
	private Void _RenderIconPlugin(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae59c0 VA: 0x75950fd9c0
	private Void _UpdateSwitchTween() { }
	// RVA: 0x2ae6290 VA: 0x75950fe290
	public Void .ctor() { }
}
```