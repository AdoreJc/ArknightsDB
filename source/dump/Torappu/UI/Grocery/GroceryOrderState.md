# GroceryOrderState

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GroceryOrderView _view`

- `AnimationWrapper _entryAnim`

- `RectTransform _rectBackBtn`

- `RectTransform _inquireConfirmFloatContainer`

- `GroceryInquireConfirmFloatPanel _prefabInquireConfirmFloat`

- `RectTransform _inquireDetailFloatContainer`

- `GrocerySellInquireFloatPanel _prefabInquireDetailFloat`

- `GroceryOrderResultView _resultViewPrefab`

- `Transform _resultViewParent`

- `Boolean m_hasInited`

- `GroceryOrderStateBean m_stateBean`

- `Tween m_cacheEntry`

- `GroceryInquireConfirmFloatPanel m_cachedInquireConfirmFloatPanel`

- `UIFadeFloatPanel m_cachedInquireDetailFloatPanel`

- `GroceryOrderResultView m_resultView`

- `AnimationWrapper m_resultEnterAnim`

- `Tween m_cacheResultEntry`

- `Boolean m_canResultBackClick`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnBackBtnPressed()`

- `Void _TriggerTutorialAVG()`

- `Void _OnInquireShopClick(String, String)`

- `IEnumerator _PlayOrderViewEnterAnim()`

- `Void _TryInquireOrder(String, String)`

- `Void _ConfirmInquire(String, String)`

- `Void _OnChangeSelfShopStrategyClick(String, Int64)`

- `Void _OnConfirmOrderClick()`

- `Void _OnInquireDetailClick()`

- `Void _InitInquireConfirmFloatPanelIfNeed()`

- `Void _InitInquireDetailFloatPanelIfNeed(String)`

- `Void _InitIfNot()`

- `Void _PlayEntryAnim(String)`

- `Void _ShowResultView()`

- `IEnumerator _PlayResultEntryAnim(String)`

- `Void _TryCloseSelf()`

- `Void <_OnConfirmOrderClick>b__37_0(GroceryOrderPurchaseResponse)`

- `Void <_PlayEntryAnim>b__42_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_MSG_INQUIRE_SHOP; // 0x0
	public const Int32 ON_MSG_CHANGE_SELF_SHOP_STRATEGY; // 0x0
	public const Int32 ON_MSG_CONFIRM_ORDER; // 0x0
	public const Int32 ON_MSG_INQUIRE_DETAIL; // 0x0
	public const Int32 ON_MSG_RESULT_BACK_CLICK; // 0x0
	private GroceryOrderView _view; // 0x70
	private AnimationWrapper _entryAnim; // 0x78
	private RectTransform _rectBackBtn; // 0x80
	private RectTransform _inquireConfirmFloatContainer; // 0x88
	private GroceryInquireConfirmFloatPanel _prefabInquireConfirmFloat; // 0x90
	private RectTransform _inquireDetailFloatContainer; // 0x98
	private GrocerySellInquireFloatPanel _prefabInquireDetailFloat; // 0xa0
	private GroceryOrderResultView _resultViewPrefab; // 0xa8
	private Transform _resultViewParent; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private GroceryOrderStateBean m_stateBean; // 0xc0
	private Tween m_cacheEntry; // 0xc8
	private GroceryInquireConfirmFloatPanel m_cachedInquireConfirmFloatPanel; // 0xd0
	private UIFadeFloatPanel m_cachedInquireDetailFloatPanel; // 0xd8
	private GroceryOrderResultView m_resultView; // 0xe0
	private AnimationWrapper m_resultEnterAnim; // 0xe8
	private Tween m_cacheResultEntry; // 0xf0
	private Boolean m_canResultBackClick; // 0xf8
	private const String ENTRY_ANIM; // 0x0
	private const String RESULT_ENTRY_ANIM; // 0x0
	private const Single CUSTOMER_CNT_ENTER_SHOW_DELAY; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_OnBackBtnPressed; // 0x20
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x28
	private static DelegateBridge __Hotfix0__OnInquireShopClick; // 0x30
	private static DelegateBridge __Hotfix0__PlayOrderViewEnterAnim; // 0x38
	private static DelegateBridge __Hotfix0__TryInquireOrder; // 0x40
	private static DelegateBridge __Hotfix0__ConfirmInquire; // 0x48
	private static DelegateBridge __Hotfix0__OnChangeSelfShopStrategyClick; // 0x50
	private static DelegateBridge __Hotfix0__OnConfirmOrderClick; // 0x58
	private static DelegateBridge __Hotfix0__OnInquireDetailClick; // 0x60
	private static DelegateBridge __Hotfix0__InitInquireConfirmFloatPanelIfNeed; // 0x68
	private static DelegateBridge __Hotfix0__InitInquireDetailFloatPanelIfNeed; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x80
	private static DelegateBridge __Hotfix0__ShowResultView; // 0x88
	private static DelegateBridge __Hotfix0__PlayResultEntryAnim; // 0x90
	private static DelegateBridge __Hotfix0__TryCloseSelf; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2889cb8 VA: 0x7594ea1cb8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2889d20 VA: 0x7594ea1d20
	protected override Void OnEnter() { }
	// RVA: 0x288a25c VA: 0x7594ea225c
	protected override Void OnResume() { }
	// RVA: 0x288ab50 VA: 0x7594ea2b50
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x288b4b8 VA: 0x7594ea34b8
	public Void OnBackBtnPressed() { }
	// RVA: 0x288a040 VA: 0x7594ea2040
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x288accc VA: 0x7594ea2ccc
	private Void _OnInquireShopClick(String goodId, String shopId) { }
	// RVA: 0x288aaa4 VA: 0x7594ea2aa4
	private IEnumerator _PlayOrderViewEnterAnim() { }
	// RVA: 0x288b798 VA: 0x7594ea3798
	private Void _TryInquireOrder(String goodId, String shopId) { }
	// RVA: 0x288bac4 VA: 0x7594ea3ac4
	private Void _ConfirmInquire(String goodId, String shopId) { }
	// RVA: 0x288ae18 VA: 0x7594ea2e18
	private Void _OnChangeSelfShopStrategyClick(String goodId, Int64 index) { }
	// RVA: 0x288af18 VA: 0x7594ea2f18
	private Void _OnConfirmOrderClick() { }
	// RVA: 0x288b26c VA: 0x7594ea326c
	private Void _OnInquireDetailClick() { }
	// RVA: 0x288a550 VA: 0x7594ea2550
	private Void _InitInquireConfirmFloatPanelIfNeed() { }
	// RVA: 0x288a68c VA: 0x7594ea268c
	private Void _InitInquireDetailFloatPanelIfNeed(String actId) { }
	// RVA: 0x2889dbc VA: 0x7594ea1dbc
	private Void _InitIfNot() { }
	// RVA: 0x288a10c VA: 0x7594ea210c
	private Void _PlayEntryAnim(String animName) { }
	// RVA: 0x288c310 VA: 0x7594ea4310
	private Void _ShowResultView() { }
	// RVA: 0x288c6d0 VA: 0x7594ea46d0
	private IEnumerator _PlayResultEntryAnim(String animName) { }
	// RVA: 0x288b328 VA: 0x7594ea3328
	private Void _TryCloseSelf() { }
	// RVA: 0x288c874 VA: 0x7594ea4874
	public Void .ctor() { }
	// RVA: 0x288ca04 VA: 0x7594ea4a04
	private Void <_OnConfirmOrderClick>b__37_0(GroceryOrderPurchaseResponse response) { }
	// RVA: 0x288ca08 VA: 0x7594ea4a08
	private Void <_PlayEntryAnim>b__42_0() { }
	// RVA: 0x288ca2c VA: 0x7594ea4a2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x288ca34 VA: 0x7594ea4a34
	private Void <>xLuaBaseProxy_OnResume() { }
}
```