# SandboxV2DungeonCrossDayState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonCrossDayView _view`

- `Boolean m_isInited`

- `SandboxV2DungeonCrossDayStateBean m_stateBean`

- `Int32 m_calcDetailDialogInst`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnContinueFromCalcClick()`

- `Void _OnCalcPanelExitComplete()`

- `Void _RefreshViewStatus(SandboxV2DungeonCrossDayViewStatus)`

- `Void _OnContinueSettleDay()`

- `Void _OnSettleDayRequestProceed(SandboxV2SettleDayResponse)`

- `Void _OnSupplyBtnClick()`

- `Void _OnDrinkTipsBtnClick()`

- `Void _OnCalcDetailClick()`

- `Void _OnContinueNormalDay()`

- `Void _OnExitBtnClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayState : PopupFadeState, IValueMsgReceiver
{
	private SandboxV2DungeonCrossDayView _view; // 0x70
	private Boolean m_isInited; // 0x78
	private SandboxV2DungeonCrossDayStateBean m_stateBean; // 0x80
	private Int32 m_calcDetailDialogInst; // 0x88
	public const Int32 MSG_CALC_DETAIL_CLICK; // 0x0
	public const Int32 MSG_CONTINUE_FROM_CALC_CLICK; // 0x0
	public const Int32 MSG_SUPPLY_BTN_CLICK; // 0x0
	public const Int32 MSG_DRINK_BTN_CLICK; // 0x0
	public const Int32 MSG_CONTINUE_SETTLE_DAY_BTN_CLICK; // 0x0
	public const Int32 MSG_CONTINUE_NORMAL_DAY; // 0x0
	public const Int32 MSG_EXIT_DAILY_BTN_CLICK; // 0x0
	public const Int32 MSG_CALC_PANEL_EXIT_FINISH; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__OnContinueFromCalcClick; // 0x20
	private static DelegateBridge __Hotfix0__OnCalcPanelExitComplete; // 0x28
	private static DelegateBridge __Hotfix0__RefreshViewStatus; // 0x30
	private static DelegateBridge __Hotfix0__OnContinueSettleDay; // 0x38
	private static DelegateBridge __Hotfix0__OnSettleDayRequestProceed; // 0x40
	private static DelegateBridge __Hotfix0__OnSupplyBtnClick; // 0x48
	private static DelegateBridge __Hotfix0__OnDrinkTipsBtnClick; // 0x50
	private static DelegateBridge __Hotfix0__OnCalcDetailClick; // 0x58
	private static DelegateBridge __Hotfix0__OnContinueNormalDay; // 0x60
	private static DelegateBridge __Hotfix0__OnExitBtnClick; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2521d5c VA: 0x7594b39d5c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2521dc4 VA: 0x7594b39dc4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2522ce0 VA: 0x7594b3ace0
	protected override Void OnEnter() { }
	// RVA: 0x252319c VA: 0x7594b3b19c
	protected override Void OnResume() { }
	// RVA: 0x25221f8 VA: 0x7594b3a1f8
	private Void _OnContinueFromCalcClick() { }
	// RVA: 0x2522c74 VA: 0x7594b3ac74
	private Void _OnCalcPanelExitComplete() { }
	// RVA: 0x2523450 VA: 0x7594b3b450
	private Void _RefreshViewStatus(SandboxV2DungeonCrossDayViewStatus status) { }
	// RVA: 0x25226d4 VA: 0x7594b3a6d4
	private Void _OnContinueSettleDay() { }
	// RVA: 0x2523680 VA: 0x7594b3b680
	private Void _OnSettleDayRequestProceed(SandboxV2SettleDayResponse response) { }
	// RVA: 0x2522264 VA: 0x7594b3a264
	private Void _OnSupplyBtnClick() { }
	// RVA: 0x2522418 VA: 0x7594b3a418
	private Void _OnDrinkTipsBtnClick() { }
	// RVA: 0x2521f2c VA: 0x7594b39f2c
	private Void _OnCalcDetailClick() { }
	// RVA: 0x252290c VA: 0x7594b3a90c
	private Void _OnContinueNormalDay() { }
	// RVA: 0x2522a6c VA: 0x7594b3aa6c
	private Void _OnExitBtnClick() { }
	// RVA: 0x2523764 VA: 0x7594b3b764
	public Void .ctor() { }
	// RVA: 0x25238c0 VA: 0x7594b3b8c0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25238c8 VA: 0x7594b3b8c8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```