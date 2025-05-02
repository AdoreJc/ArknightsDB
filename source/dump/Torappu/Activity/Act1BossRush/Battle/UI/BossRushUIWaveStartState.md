# BossRushUIWaveStartState

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Fields

- `BossRushWaveStartPanel _perform`

- `Vector3 m_offset`

- `Vector3 m_originLocalPosition`

- `BossRushWaveStartPanel m_panel`


## Methods

- `Void _ResetPerformPositionByCameraPos()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushUIWaveStartState : UIStateNode
{
	private BossRushWaveStartPanel _perform; // 0x20
	private Vector3 m_offset; // 0x28
	private Vector3 m_originLocalPosition; // 0x34
	private BossRushWaveStartPanel m_panel; // 0x40
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0__ResetPerformPositionByCameraPos; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x3198208 VA: 0x75957b0208
	public override UIStateEnum get_uiState() { }
	// RVA: 0x319829c VA: 0x75957b029c
	public override Boolean get_enablePause() { }
	// RVA: 0x3198300 VA: 0x75957b0300
	public override Boolean get_enableShowRange() { }
	// RVA: 0x3198364 VA: 0x75957b0364
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x31983c8 VA: 0x75957b03c8
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x3198430 VA: 0x75957b0430
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x3198630 VA: 0x75957b0630
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3198988 VA: 0x75957b0988
	private Void _ResetPerformPositionByCameraPos() { }
	// RVA: 0x3198c34 VA: 0x75957b0c34
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3198cac VA: 0x75957b0cac
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x3198d2c VA: 0x75957b0d2c
	public Void .ctor() { }
	// RVA: 0x3198d9c VA: 0x75957b0d9c
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x3198da4 VA: 0x75957b0da4
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x3198dac VA: 0x75957b0dac
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x3198db4 VA: 0x75957b0db4
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x3198dbc VA: 0x75957b0dbc
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x3198dc4 VA: 0x75957b0dc4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3198dcc VA: 0x75957b0dcc
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```