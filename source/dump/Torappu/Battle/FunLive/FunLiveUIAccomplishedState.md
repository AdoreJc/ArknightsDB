# FunLiveUIAccomplishedState

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `Animation _showAnimation`

- `BattleFailedStateParam m_stateParam`


## Methods

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIAccomplishedState : UIStateNode
{
	private Animation _showAnimation; // 0x20
	private BattleFailedStateParam m_stateParam; // 0x28
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x1c5d1a8 VA: 0x75942751a8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1c5d23c VA: 0x759427523c
	public override Boolean get_enablePause() { }
	// RVA: 0x1c5d2a0 VA: 0x75942752a0
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1c5d304 VA: 0x7594275304
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1c5d368 VA: 0x7594275368
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1c5d418 VA: 0x7594275418
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c5d558 VA: 0x7594275558
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c5d638 VA: 0x7594275638
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c5d6b8 VA: 0x75942756b8
	public Void .ctor() { }
	// RVA: 0x1c5d728 VA: 0x7594275728
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1c5d730 VA: 0x7594275730
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1c5d738 VA: 0x7594275738
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1c5d740 VA: 0x7594275740
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1c5d748 VA: 0x7594275748
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1c5d750 VA: 0x7594275750
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```