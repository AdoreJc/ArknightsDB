# UICooperateStageWaveStartState

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateStageWaveStartPanel m_panel`

- `Vector3 m_originLocalPosition`


## Methods

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
public class UICooperateStageWaveStartState : CommonUIStateNode, IFixedUpdateState
{
	private UICooperateStageWaveStartPanel m_panel; // 0x50
	private Vector3 m_originLocalPosition; // 0x58
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x40
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x20e0290 VA: 0x75946f8290
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20e0324 VA: 0x75946f8324
	public override Boolean get_enablePause() { }
	// RVA: 0x20e0388 VA: 0x75946f8388
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20e03ec VA: 0x75946f83ec
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20e0450 VA: 0x75946f8450
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x20e04b8 VA: 0x75946f84b8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x20e06e0 VA: 0x75946f86e0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20e0780 VA: 0x75946f8780
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20e07f8 VA: 0x75946f87f8
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20e08fc VA: 0x75946f88fc
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20e0980 VA: 0x75946f8980
	public Void .ctor() { }
	// RVA: 0x20e09f0 VA: 0x75946f89f0
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20e09f8 VA: 0x75946f89f8
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20e0a00 VA: 0x75946f8a00
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20e0a08 VA: 0x75946f8a08
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20e0a10 VA: 0x75946f8a10
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20e0a18 VA: 0x75946f8a18
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20e0a20 VA: 0x75946f8a20
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```