# ShopGPState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopGPStateBean _stateBean`

- `ShopGPRightPanelView _rightPanel`

- `ShopGPLeftTabListView _leftTabList`

- `Boolean m_isInited`

- `Int32 m_enterSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void _NotifyEnter()`

- `Void _UpdateGPState()`

- `Void _TryOpenItemDetail()`

- `Void _OnOpenDetail(String)`

- `Void _TryOpenMonthCard(ShopGPViewModel, ShopGPCommonItemViewModel)`

- `Void ApplyData(GetGPGoodListResponse)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SelectTab(String)`

- `Void <_UpdateGPState>b__10_0(GetGPGoodListResponse, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPState : ShopCommonState, IValueMsgReceiver
{
	private ShopGPStateBean _stateBean; // 0x68
	private ShopGPRightPanelView _rightPanel; // 0x70
	private ShopGPLeftTabListView _leftTabList; // 0x78
	private Boolean m_isInited; // 0x80
	private Int32 m_enterSeqNum; // 0x84
	public const Int32 SHOP_GP_TAB_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__NotifyEnter; // 0x20
	private static DelegateBridge __Hotfix0__UpdateGPState; // 0x28
	private static DelegateBridge __Hotfix0__TryOpenItemDetail; // 0x30
	private static DelegateBridge __Hotfix0__OnOpenDetail; // 0x38
	private static DelegateBridge __Hotfix0__TryOpenMonthCard; // 0x40
	private static DelegateBridge __Hotfix0_ApplyData; // 0x48
	private static DelegateBridge __Hotfix0_OnMessage; // 0x50
	private static DelegateBridge __Hotfix0__SelectTab; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2444580 VA: 0x7594a5c580
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24445e8 VA: 0x7594a5c5e8
	private Void _InitIfNot() { }
	// RVA: 0x2444784 VA: 0x7594a5c784
	protected override Void OnEnter() { }
	// RVA: 0x24449e4 VA: 0x7594a5c9e4
	protected override Void OnResume() { }
	// RVA: 0x2444808 VA: 0x7594a5c808
	private Void _NotifyEnter() { }
	// RVA: 0x24448c4 VA: 0x7594a5c8c4
	private Void _UpdateGPState() { }
	// RVA: 0x2444acc VA: 0x7594a5cacc
	private Void _TryOpenItemDetail() { }
	// RVA: 0x2444e08 VA: 0x7594a5ce08
	protected Void _OnOpenDetail(String goodId) { }
	// RVA: 0x24450dc VA: 0x7594a5d0dc
	protected Void _TryOpenMonthCard(ShopGPViewModel viewModel, ShopGPCommonItemViewModel itemViewModel) { }
	// RVA: 0x24452bc VA: 0x7594a5d2bc
	public Void ApplyData(GetGPGoodListResponse response) { }
	// RVA: 0x2445b8c VA: 0x7594a5db8c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2445c34 VA: 0x7594a5dc34
	private Void _SelectTab(String tabId) { }
	// RVA: 0x2445d14 VA: 0x7594a5dd14
	public Void .ctor() { }
	// RVA: 0x2445d84 VA: 0x7594a5dd84
	private Void <_UpdateGPState>b__10_0(GetGPGoodListResponse response, Boolean isDataUpdated) { }
	// RVA: 0x2445da4 VA: 0x7594a5dda4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2445dac VA: 0x7594a5ddac
	private Void <>xLuaBaseProxy_OnResume() { }
}
```