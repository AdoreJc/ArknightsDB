# GrocerySellState

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GrocerySellView _sellView`

- `GrocerySellSliderController _slider`

- `AnimationWrapper _entryAnim`

- `RectTransform _rectBackBtn`

- `RectTransform _inquireFloatContainer`

- `GrocerySellInquireFloatPanel _prefabInquireFloat`

- `RectTransform _inquireConfirmFloatContainer`

- `GroceryInquireConfirmFloatPanel _prefabInquireConfirmFloat`

- `Boolean m_hasInited`

- `GrocerySellStateBean m_stateBean`

- `Tween m_cacheEntry`

- `UIFadeFloatPanel m_cachedInquireFloatPanel`

- `GroceryInquireConfirmFloatPanel m_cachedInquireConfirmFloatPanel`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnBackBtnClicked()`

- `Void _TriggerTutorialAVG()`

- `Void _RefreshModel(Boolean)`

- `Boolean _RemoveToHomeStateIfNecessary()`

- `Void _InitFloatPanelIfNeed(String)`

- `Void _OnInquireBtnClicked()`

- `Void _ConfirmInquire(String, String)`

- `Void _OnSellBtnClicked()`

- `Void _OnSellRequestProceed(GrocerySellResponse)`

- `Void _OnInquireDetailBtnClicked()`

- `Void _OnPriceSliderChanged(Int32)`

- `Void _TryAddPriceSelectIndex(Int32)`

- `Void _PlayEntryAnim(String)`

- `Void _InitIfNot()`

- `Void <_ConfirmInquire>b__32_0(GrocerySellInquireResponse)`

- `Void <_PlayEntryAnim>b__38_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellState : PopupFadeState, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_PRICE_SLIDER_CHANGED; // 0x0
	public const Int32 ON_INQUIRE; // 0x0
	public const Int32 ON_SELL; // 0x0
	public const Int32 ON_INQUIRE_DETAIL; // 0x0
	public const Int32 ON_PRICE_ADD_BTN_CLICKED; // 0x0
	public const Int32 ON_PRICE_MIN_BTN_CLICKED; // 0x0
	private const String ENTRY_ANIM_LONG; // 0x0
	private const String ENTRY_ANIM_SHORT; // 0x0
	private GrocerySellView _sellView; // 0x70
	private GrocerySellCustomerView[] _customerView; // 0x78
	private GrocerySellSliderController _slider; // 0x80
	private AnimationWrapper _entryAnim; // 0x88
	private RectTransform _rectBackBtn; // 0x90
	private RectTransform _inquireFloatContainer; // 0x98
	private GrocerySellInquireFloatPanel _prefabInquireFloat; // 0xa0
	private RectTransform _inquireConfirmFloatContainer; // 0xa8
	private GroceryInquireConfirmFloatPanel _prefabInquireConfirmFloat; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private GrocerySellStateBean m_stateBean; // 0xc0
	private Tween m_cacheEntry; // 0xc8
	private UIFadeFloatPanel m_cachedInquireFloatPanel; // 0xd0
	private GroceryInquireConfirmFloatPanel m_cachedInquireConfirmFloatPanel; // 0xd8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_OnBackBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x28
	private static DelegateBridge __Hotfix0__RefreshModel; // 0x30
	private static DelegateBridge __Hotfix0__RemoveToHomeStateIfNecessary; // 0x38
	private static DelegateBridge __Hotfix0__InitFloatPanelIfNeed; // 0x40
	private static DelegateBridge __Hotfix0__OnInquireBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__ConfirmInquire; // 0x50
	private static DelegateBridge __Hotfix0__OnSellBtnClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnSellRequestProceed; // 0x60
	private static DelegateBridge __Hotfix0__OnInquireDetailBtnClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnPriceSliderChanged; // 0x70
	private static DelegateBridge __Hotfix0__TryAddPriceSelectIndex; // 0x78
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x289b89c VA: 0x7594eb389c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x289b904 VA: 0x7594eb3904
	protected override Void OnEnter() { }
	// RVA: 0x289be34 VA: 0x7594eb3e34
	protected override Void OnResume() { }
	// RVA: 0x289c268 VA: 0x7594eb4268
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x289cb84 VA: 0x7594eb4b84
	public Void OnBackBtnClicked() { }
	// RVA: 0x289bc18 VA: 0x7594eb3c18
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x289c0d4 VA: 0x7594eb40d4
	private Void _RefreshModel(Boolean resetPrice) { }
	// RVA: 0x289bf04 VA: 0x7594eb3f04
	private Boolean _RemoveToHomeStateIfNecessary() { }
	// RVA: 0x289ce78 VA: 0x7594eb4e78
	private Void _InitFloatPanelIfNeed(String actId) { }
	// RVA: 0x289c4c0 VA: 0x7594eb44c0
	private Void _OnInquireBtnClicked() { }
	// RVA: 0x289d5b4 VA: 0x7594eb55b4
	private Void _ConfirmInquire(String goodId, String shopId) { }
	// RVA: 0x289c72c VA: 0x7594eb472c
	private Void _OnSellBtnClicked() { }
	// RVA: 0x289d838 VA: 0x7594eb5838
	private Void _OnSellRequestProceed(GrocerySellResponse response) { }
	// RVA: 0x289c998 VA: 0x7594eb4998
	private Void _OnInquireDetailBtnClicked() { }
	// RVA: 0x289c398 VA: 0x7594eb4398
	private Void _OnPriceSliderChanged(Int32 targetIndex) { }
	// RVA: 0x289ca54 VA: 0x7594eb4a54
	private Void _TryAddPriceSelectIndex(Int32 addCount) { }
	// RVA: 0x289bce4 VA: 0x7594eb3ce4
	private Void _PlayEntryAnim(String animName) { }
	// RVA: 0x289b9a0 VA: 0x7594eb39a0
	private Void _InitIfNot() { }
	// RVA: 0x289da9c VA: 0x7594eb5a9c
	public Void .ctor() { }
	// RVA: 0x289dbf4 VA: 0x7594eb5bf4
	private Void <_ConfirmInquire>b__32_0(GrocerySellInquireResponse response) { }
	// RVA: 0x289dc70 VA: 0x7594eb5c70
	private Void <_PlayEntryAnim>b__38_0() { }
	// RVA: 0x289dc94 VA: 0x7594eb5c94
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x289dc9c VA: 0x7594eb5c9c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```