# UIBattleFailedState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIBattleFailedPanel _failedPanel`

- `BattleFailedStateParam m_stateParam`


## Methods

- `Void OnFailPanelClose()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleFailedState : UIStateNode
{
	private UIBattleFailedPanel _failedPanel; // 0x20
	private BattleFailedStateParam m_stateParam; // 0x28
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge __Hotfix0_OnFailPanelClose; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x205529c VA: 0x759466d29c
	public override UIStateEnum get_uiState() { }
	// RVA: 0x2055304 VA: 0x759466d304
	public override Boolean get_enablePause() { }
	// RVA: 0x2055368 VA: 0x759466d368
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20553cc VA: 0x759466d3cc
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2055430 VA: 0x759466d430
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x205562c VA: 0x759466d62c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20558b0 VA: 0x759466d8b0
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20559ec VA: 0x759466d9ec
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x2055a64 VA: 0x759466da64
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x2055ae4 VA: 0x759466dae4
	public Void OnFailPanelClose() { }
	// RVA: 0x2055b74 VA: 0x759466db74
	public Void .ctor() { }
	// RVA: 0x2055be4 VA: 0x759466dbe4
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x2055bec VA: 0x759466dbec
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x2055bf4 VA: 0x759466dbf4
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x2055bfc VA: 0x759466dbfc
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x2055c04 VA: 0x759466dc04
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2055c0c VA: 0x759466dc0c
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x2055c14 VA: 0x759466dc14
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```