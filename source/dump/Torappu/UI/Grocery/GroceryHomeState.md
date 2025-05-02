# GroceryHomeState

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Transform _topMenuContainer`

- `GroceryHomeView _homeView`

- `GroceryHomeLaunchView _launchPanel`

- `AnimationWrapper _animEnter`

- `GroceryHomeStateBean m_stateBean`

- `Boolean m_hasInited`

- `Tween m_cachedAnim`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _TriggerTutorialAVG()`

- `Void _TryConsumeGuidebook(Story)`

- `Void _InitIfNot()`

- `Void _SetLaunchPanelShown(Int32)`

- `Void _OnBackBtnClicked()`

- `Void _OnMileStoneBtnClicked()`

- `Void _OnSaleBtnClicked()`

- `Void _TryStartSale(String)`

- `Void _SendStartSaleRequestAndOpenOrderState(String)`

- `Void _SendSattleRequestAndShowGainItems(String)`

- `Void _OnShowSattleGainItems(GrocerySaleSettleResponse)`

- `Void _OnStartSaleProceed(GroceryStartSaleResponse)`

- `Void _OpenOrderState()`

- `Void _OpenSellState()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeState : PopupFadeState, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_MSG_SET_LAUNCH_PANEL_SHOWN; // 0x0
	public const Int32 ON_MSG_OPEN_MILE_STONE_STATE; // 0x0
	public const Int32 ON_MSG_SALE; // 0x0
	private const String ENTER_ANIM_NAME; // 0x0
	private const Int32 FIRST_DAY; // 0x0
	private Transform _topMenuContainer; // 0x70
	private GroceryHomeView _homeView; // 0x78
	private GroceryHomeLaunchView _launchPanel; // 0x80
	private AnimationWrapper _animEnter; // 0x88
	private GroceryHomeStateBean m_stateBean; // 0x90
	private Boolean m_hasInited; // 0x98
	private Tween m_cachedAnim; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x20
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__SetLaunchPanelShown; // 0x38
	private static DelegateBridge __Hotfix0__OnBackBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnMileStoneBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnSaleBtnClicked; // 0x50
	private static DelegateBridge __Hotfix0__TryStartSale; // 0x58
	private static DelegateBridge __Hotfix0__SendStartSaleRequestAndOpenOrderState; // 0x60
	private static DelegateBridge __Hotfix0__SendSattleRequestAndShowGainItems; // 0x68
	private static DelegateBridge __Hotfix0__OnShowSattleGainItems; // 0x70
	private static DelegateBridge __Hotfix0__OnStartSaleProceed; // 0x78
	private static DelegateBridge __Hotfix0__OpenOrderState; // 0x80
	private static DelegateBridge __Hotfix0__OpenSellState; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x2860b04 VA: 0x7594e78b04
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2860b6c VA: 0x7594e78b6c
	protected override Void OnEnter() { }
	// RVA: 0x2861288 VA: 0x7594e79288
	protected override Void OnResume() { }
	// RVA: 0x2861878 VA: 0x7594e79878
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2861668 VA: 0x7594e79668
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x28617b4 VA: 0x7594e797b4
	private Void _TryConsumeGuidebook(Story story) { }
	// RVA: 0x2860d88 VA: 0x7594e78d88
	private Void _InitIfNot() { }
	// RVA: 0x2861984 VA: 0x7594e79984
	private Void _SetLaunchPanelShown(Int32 isShow) { }
	// RVA: 0x2861d6c VA: 0x7594e79d6c
	private Void _OnBackBtnClicked() { }
	// RVA: 0x2861a58 VA: 0x7594e79a58
	private Void _OnMileStoneBtnClicked() { }
	// RVA: 0x2861be0 VA: 0x7594e79be0
	private Void _OnSaleBtnClicked() { }
	// RVA: 0x286214c VA: 0x7594e7a14c
	private Void _TryStartSale(String actId) { }
	// RVA: 0x28627b8 VA: 0x7594e7a7b8
	private Void _SendStartSaleRequestAndOpenOrderState(String actId) { }
	// RVA: 0x2861f20 VA: 0x7594e79f20
	private Void _SendSattleRequestAndShowGainItems(String actId) { }
	// RVA: 0x28629e4 VA: 0x7594e7a9e4
	private Void _OnShowSattleGainItems(GrocerySaleSettleResponse response) { }
	// RVA: 0x2862be4 VA: 0x7594e7abe4
	private Void _OnStartSaleProceed(GroceryStartSaleResponse response) { }
	// RVA: 0x28623e0 VA: 0x7594e7a3e0
	private Void _OpenOrderState() { }
	// RVA: 0x28625c8 VA: 0x7594e7a5c8
	private Void _OpenSellState() { }
	// RVA: 0x2862cc8 VA: 0x7594e7acc8
	public Void .ctor() { }
	// RVA: 0x2862e20 VA: 0x7594e7ae20
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2862e28 VA: 0x7594e7ae28
	private Void <>xLuaBaseProxy_OnResume() { }
}
```