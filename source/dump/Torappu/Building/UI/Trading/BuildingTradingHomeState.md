# BuildingTradingHomeState

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `BuildingTradingRoomTitleView _roomTitle`

- `BuildingTradingTabGroup _roomTabGroup`

- `BuildingTradingStationView _stationView`

- `BuildingTradingStatusView _statusView`

- `BuildingTradingOrderList _orderList`

- `TradingStateBean m_stateBean`

- `Int64 m_laborAccelOrderCache`


## Methods

- `Void EventOnNegotiationClicked()`

- `Void _OnCharClicked(BuildingCharModel, Int32)`

- `Void _OnRoomSelected(String)`

- `Void _OnFinishOrder(Int64)`

- `Void _OnDeleteOrder(Int64)`

- `Void _OnLaborAccelClicked()`

- `Void _OnPlayerDataChanged()`

- `Void _InitTopMenu()`

- `Void _OnJumpToLaborAccel(LaborAccelStateBean)`

- `Void _OnJumpToNegotiationState(TradingNegoiationBean)`

- `IEnumerator _DeliveryOrderEffectCoroutine()`

- `Void _SendDeleteOrderService(String, Int64)`

- `Void <RegisterToDataListener>b__12_0(IStateBean)`

- `Void <RegisterToDataListener>b__12_1(IStateBean)`

- `Void <_OnFinishOrder>b__16_0(BuildingTradingDeliveryResponse)`

- `Void <_InitTopMenu>b__20_0(GameObject)`

- `Void <_InitTopMenu>b__20_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingHomeState : State
{
	private PrefabInstHolder _topMenuHolder; // 0x50
	private BuildingTradingRoomTitleView _roomTitle; // 0x58
	private BuildingTradingTabGroup _roomTabGroup; // 0x60
	private BuildingTradingStationView _stationView; // 0x68
	private BuildingTradingStatusView _statusView; // 0x70
	private BuildingTradingOrderList _orderList; // 0x78
	private TradingStateBean m_stateBean; // 0x80
	private Int64 m_laborAccelOrderCache; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_EventOnNegotiationClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnCharClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnRoomSelected; // 0x30
	private static DelegateBridge __Hotfix0__OnFinishOrder; // 0x38
	private static DelegateBridge __Hotfix0__OnDeleteOrder; // 0x40
	private static DelegateBridge __Hotfix0__OnLaborAccelClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x50
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToLaborAccel; // 0x60
	private static DelegateBridge __Hotfix0__OnJumpToNegotiationState; // 0x68
	private static DelegateBridge __Hotfix0__DeliveryOrderEffectCoroutine; // 0x70
	private static DelegateBridge __Hotfix0__SendDeleteOrderService; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x3d7e038 VA: 0x7596396038
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d7e0a0 VA: 0x75963960a0
	protected override Void OnEnter() { }
	// RVA: 0x3d7ed78 VA: 0x7596396d78
	protected override Void OnResume() { }
	// RVA: 0x3d7f1cc VA: 0x75963971cc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3d7f3c0 VA: 0x75963973c0
	public Void EventOnNegotiationClicked() { }
	// RVA: 0x3d7f4d8 VA: 0x75963974d8
	private Void _OnCharClicked(BuildingCharModel model, Int32 index) { }
	// RVA: 0x3d7f5bc VA: 0x75963975bc
	private Void _OnRoomSelected(String slotId) { }
	// RVA: 0x3d7f648 VA: 0x7596397648
	private Void _OnFinishOrder(Int64 orderId) { }
	// RVA: 0x3d7fa1c VA: 0x7596397a1c
	private Void _OnDeleteOrder(Int64 orderId) { }
	// RVA: 0x3d7fed8 VA: 0x7596397ed8
	private Void _OnLaborAccelClicked() { }
	// RVA: 0x3d80014 VA: 0x7596398014
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3d7e56c VA: 0x759639656c
	private Void _InitTopMenu() { }
	// RVA: 0x3d80084 VA: 0x7596398084
	private Void _OnJumpToLaborAccel(LaborAccelStateBean stateBean) { }
	// RVA: 0x3d802c4 VA: 0x75963982c4
	private Void _OnJumpToNegotiationState(TradingNegoiationBean stateBean) { }
	// RVA: 0x3d8038c VA: 0x759639838c
	private IEnumerator _DeliveryOrderEffectCoroutine() { }
	// RVA: 0x3d7fc8c VA: 0x7596397c8c
	private Void _SendDeleteOrderService(String slotId, Int64 orderId) { }
	// RVA: 0x3d80460 VA: 0x7596398460
	public Void .ctor() { }
	// RVA: 0x3d80628 VA: 0x7596398628
	private Void <RegisterToDataListener>b__12_0(IStateBean stateBean) { }
	// RVA: 0x3d806a8 VA: 0x75963986a8
	private Void <RegisterToDataListener>b__12_1(IStateBean stateBean) { }
	// RVA: 0x3d80728 VA: 0x7596398728
	private Void <_OnFinishOrder>b__16_0(BuildingTradingDeliveryResponse response) { }
	// RVA: 0x3d80748 VA: 0x7596398748
	private Void <_InitTopMenu>b__20_0(GameObject instObj) { }
	// RVA: 0x3d80850 VA: 0x7596398850
	private Void <_InitTopMenu>b__20_1() { }
	// RVA: 0x3d80870 VA: 0x7596398870
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d80878 VA: 0x7596398878
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3d80880 VA: 0x7596398880
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```