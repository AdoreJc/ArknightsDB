# UICooperateBattleStartState

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateBattleStartPanel m_panel`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void _OnBattleStart(Object)`

- `Void <OnEnter>b__11_0()`

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
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleStartState : CommonUIStateNode, IFixedUpdateState
{
	private UICooperateBattleStartPanel m_panel; // 0x50
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x48
	private static DelegateBridge __Hotfix0__OnBattleStart; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x20db8b8 VA: 0x75946f38b8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20db94c VA: 0x75946f394c
	public override Boolean get_enablePause() { }
	// RVA: 0x20db9b0 VA: 0x75946f39b0
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20dba14 VA: 0x75946f3a14
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20dba78 VA: 0x75946f3a78
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20dbb50 VA: 0x75946f3b50
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x20dbdc0 VA: 0x75946f3dc0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20dbf1c VA: 0x75946f3f1c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20dc018 VA: 0x75946f4018
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20dc090 VA: 0x75946f4090
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20dc17c VA: 0x75946f417c
	private Void _OnBattleStart(Object arg) { }
	// RVA: 0x20dc2dc VA: 0x75946f42dc
	public Void .ctor() { }
	// RVA: 0x20dc34c VA: 0x75946f434c
	private Void <OnEnter>b__11_0() { }
	// RVA: 0x20dc368 VA: 0x75946f4368
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20dc370 VA: 0x75946f4370
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20dc378 VA: 0x75946f4378
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20dc380 VA: 0x75946f4380
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20dc388 VA: 0x75946f4388
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20dc390 VA: 0x75946f4390
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x20dc398 VA: 0x75946f4398
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```