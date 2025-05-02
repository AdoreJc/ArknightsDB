# UICooperateBattleFailedState

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `BattleFailedStateParam m_stateParam`

- `UIAnimationPerform m_panel`

- `Vector3 m_offset`


## Methods

- `Void _ResetPerformPositionByCameraPos()`

- `Void <OnEnter>b__14_0(Boolean)`

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
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleFailedState : CommonUIStateNode
{
	private BattleFailedStateParam m_stateParam; // 0x50
	private UIAnimationPerform m_panel; // 0x58
	private Vector3 m_offset; // 0x60
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge __Hotfix0__ResetPerformPositionByCameraPos; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x20dacec VA: 0x75946f2cec
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20dad80 VA: 0x75946f2d80
	public override Boolean get_enablePause() { }
	// RVA: 0x20dade4 VA: 0x75946f2de4
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20dae48 VA: 0x75946f2e48
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20daeac VA: 0x75946f2eac
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x20daf14 VA: 0x75946f2f14
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x20db24c VA: 0x75946f324c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20db6c0 VA: 0x75946f36c0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20db738 VA: 0x75946f3738
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20db51c VA: 0x75946f351c
	private Void _ResetPerformPositionByCameraPos() { }
	// RVA: 0x20db7b8 VA: 0x75946f37b8
	public Void .ctor() { }
	// RVA: 0x20db828 VA: 0x75946f3828
	private Void <OnEnter>b__14_0(Boolean _) { }
	// RVA: 0x20db880 VA: 0x75946f3880
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20db888 VA: 0x75946f3888
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20db890 VA: 0x75946f3890
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20db898 VA: 0x75946f3898
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20db8a0 VA: 0x75946f38a0
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20db8a8 VA: 0x75946f38a8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20db8b0 VA: 0x75946f38b0
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```