# UICooperateScoreAGoalState

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Vector3 m_offset`

- `Vector3 m_originLocalPosition`

- `UICooperateScoreAGoalPanel m_panel`


## Methods

- `Void _HideAllPerform(Object)`

- `Void OnFixedUpdate(FP)`

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
public class UICooperateScoreAGoalState : CommonUIStateNode, IFixedUpdateState
{
	private Vector3 m_offset; // 0x50
	private Vector3 m_originLocalPosition; // 0x5c
	private UICooperateScoreAGoalPanel m_panel; // 0x68
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0__HideAllPerform; // 0x40
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x48
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x20de480 VA: 0x75946f6480
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20de514 VA: 0x75946f6514
	public override Boolean get_enablePause() { }
	// RVA: 0x20de578 VA: 0x75946f6578
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20de5dc VA: 0x75946f65dc
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20de640 VA: 0x75946f6640
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x20de6a8 VA: 0x75946f66a8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x20de8f0 VA: 0x75946f68f0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20deb24 VA: 0x75946f6b24
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20deb9c VA: 0x75946f6b9c
	private Void _HideAllPerform(Object param) { }
	// RVA: 0x20dec30 VA: 0x75946f6c30
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20ded34 VA: 0x75946f6d34
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20dedc8 VA: 0x75946f6dc8
	public Void .ctor() { }
	// RVA: 0x20dee38 VA: 0x75946f6e38
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20dee40 VA: 0x75946f6e40
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20dee48 VA: 0x75946f6e48
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20dee50 VA: 0x75946f6e50
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20dee58 VA: 0x75946f6e58
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20dee60 VA: 0x75946f6e60
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20dee68 VA: 0x75946f6e68
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```