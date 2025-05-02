# Act20SideUIBattleAccomplishedState

**Namespace:** `Torappu.Activity.Act20side.Battle.UI`


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
// Namespace : Torappu.Activity.Act20side.Battle.UI
public class Act20SideUIBattleAccomplishedState : UIStateNode
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

	// RVA: 0x3304d10 VA: 0x759591cd10
	public override UIStateEnum get_uiState() { }
	// RVA: 0x3304da4 VA: 0x759591cda4
	public override Boolean get_enablePause() { }
	// RVA: 0x3304e08 VA: 0x759591ce08
	public override Boolean get_enableShowRange() { }
	// RVA: 0x3304e6c VA: 0x759591ce6c
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x3304ed0 VA: 0x759591ced0
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x3304f80 VA: 0x759591cf80
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x33050c0 VA: 0x759591d0c0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x33051a0 VA: 0x759591d1a0
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x3305220 VA: 0x759591d220
	public Void .ctor() { }
	// RVA: 0x3305290 VA: 0x759591d290
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x3305298 VA: 0x759591d298
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x33052a0 VA: 0x759591d2a0
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x33052a8 VA: 0x759591d2a8
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x33052b0 VA: 0x759591d2b0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x33052b8 VA: 0x759591d2b8
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```