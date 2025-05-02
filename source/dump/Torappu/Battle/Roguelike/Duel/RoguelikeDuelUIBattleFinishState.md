# RoguelikeDuelUIBattleFinishState

**Namespace:** `Torappu.Battle.Roguelike.Duel`


## Fields

- `UIAnimationLocation _showLoseAnimation`

- `UIAnimationLocation _showDrawAnimation`

- `UIAnimationLocation _showWinAnimation`

- `BattleFailedStateParam m_stateParam`


## Methods

- `Void _OnAnimationFinish()`

- `Void <OnEnter>b__13_0()`

- `Void <OnEnter>b__13_1()`

- `Void <OnEnter>b__13_2()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Duel
public class RoguelikeDuelUIBattleFinishState : UIStateNode
{
	private UIAnimationLocation _showLoseAnimation; // 0x20
	private UIAnimationLocation _showDrawAnimation; // 0x30
	private UIAnimationLocation _showWinAnimation; // 0x40
	private BattleFailedStateParam m_stateParam; // 0x50
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x38
	private static DelegateBridge __Hotfix0__OnAnimationFinish; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x1d4de60 VA: 0x7594365e60
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1d4def4 VA: 0x7594365ef4
	public override Boolean get_enablePause() { }
	// RVA: 0x1d4df58 VA: 0x7594365f58
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1d4dfbc VA: 0x7594365fbc
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1d4e020 VA: 0x7594366020
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1d4e0b0 VA: 0x75943660b0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1d4e558 VA: 0x7594366558
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d4e5d0 VA: 0x75943665d0
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1d4e4c8 VA: 0x75943664c8
	private Void _OnAnimationFinish() { }
	// RVA: 0x1d4e650 VA: 0x7594366650
	public Void .ctor() { }
	// RVA: 0x1d4e6c0 VA: 0x75943666c0
	private Void <OnEnter>b__13_0() { }
	// RVA: 0x1d4e6c4 VA: 0x75943666c4
	private Void <OnEnter>b__13_1() { }
	// RVA: 0x1d4e6c8 VA: 0x75943666c8
	private Void <OnEnter>b__13_2() { }
	// RVA: 0x1d4e6cc VA: 0x75943666cc
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1d4e6d4 VA: 0x75943666d4
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1d4e6dc VA: 0x75943666dc
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1d4e6e4 VA: 0x75943666e4
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1d4e6ec VA: 0x75943666ec
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1d4e6f4 VA: 0x75943666f4
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```