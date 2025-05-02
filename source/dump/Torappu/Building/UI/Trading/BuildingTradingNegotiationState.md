# BuildingTradingNegotiationState

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `TradingNegoiationBean m_stateBean`

- `OrderType m_strategyWhenEnter`


## Methods

- `Void _OnTypeSelected(TradingOrderViewType)`

- `Void _UpdateOrderType()`

- `Void <DismissSelf>b__6_0(BuildingTradingChangeStrategyResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_DismissSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingNegotiationState : PopupFloatState
{
	private BuildingTradingNegotiationItem[] _typeItems; // 0x70
	private TradingNegoiationBean m_stateBean; // 0x78
	private OrderType m_strategyWhenEnter; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_DismissSelf; // 0x18
	private static DelegateBridge __Hotfix0__OnTypeSelected; // 0x20
	private static DelegateBridge __Hotfix0__UpdateOrderType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d811c8 VA: 0x75963991c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d81230 VA: 0x7596399230
	protected override Void OnEnter() { }
	// RVA: 0x3d8150c VA: 0x759639950c
	protected override Void OnResume() { }
	// RVA: 0x3d81580 VA: 0x7596399580
	public override Void DismissSelf() { }
	// RVA: 0x3d81858 VA: 0x7596399858
	private Void _OnTypeSelected(TradingOrderViewType viewType) { }
	// RVA: 0x3d813cc VA: 0x75963993cc
	private Void _UpdateOrderType() { }
	// RVA: 0x3d81a34 VA: 0x7596399a34
	public Void .ctor() { }
	// RVA: 0x3d81ae0 VA: 0x7596399ae0
	private Void <DismissSelf>b__6_0(BuildingTradingChangeStrategyResponse response) { }
	// RVA: 0x3d81ae8 VA: 0x7596399ae8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d81af0 VA: 0x7596399af0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3d81af8 VA: 0x7596399af8
	private Void <>xLuaBaseProxy_DismissSelf() { }
}
```