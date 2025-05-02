# Act27sideBattleFailedState

**Namespace:** `Torappu.Activity.Act20side.Battle.UI`


## Fields

- `Transform _battleFailedPanel`

- `BattleFailedStateParam m_stateParam`


## Methods

- `Void OnClick()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side.Battle.UI
public class Act27sideBattleFailedState : UIStateNode
{
	private Transform _battleFailedPanel; // 0x20
	private BattleFailedStateParam m_stateParam; // 0x28
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_OnClick; // 0x30
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x3308698 VA: 0x7595920698
	public override UIStateEnum get_uiState() { }
	// RVA: 0x330872c VA: 0x759592072c
	public override Boolean get_enablePause() { }
	// RVA: 0x3308790 VA: 0x7595920790
	public override Boolean get_enableShowRange() { }
	// RVA: 0x33087f4 VA: 0x75959207f4
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x3308858 VA: 0x7595920858
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3308988 VA: 0x7595920988
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3308a00 VA: 0x7595920a00
	public Void OnClick() { }
	// RVA: 0x3308a90 VA: 0x7595920a90
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x3308b10 VA: 0x7595920b10
	public Void .ctor() { }
	// RVA: 0x3308b80 VA: 0x7595920b80
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x3308b88 VA: 0x7595920b88
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x3308b90 VA: 0x7595920b90
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x3308b98 VA: 0x7595920b98
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3308ba0 VA: 0x7595920ba0
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```