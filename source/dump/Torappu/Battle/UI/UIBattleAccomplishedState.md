# UIBattleAccomplishedState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIAnimationPerform _perform`

- `Boolean m_skipPerform`

- `Vector3 m_offset`

- `UIAnimationPerform m_perform`


## Methods

- `Void _ResetPerformPositionByCameraPos()`

- `Void _SwitchToBattleFinishService()`

- `Void <OnEnter>b__17_0(Boolean)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Boolean <>xLuaBaseProxy_get_enableBackpress()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleAccomplishedState : UIStateNode
{
	private UIAnimationPerform _perform; // 0x20
	private Boolean m_skipPerform; // 0x28
	private Vector3 m_offset; // 0x2c
	private UIAnimationPerform m_perform; // 0x38
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_get_enableBackpress; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x48
	private static DelegateBridge __Hotfix0__ResetPerformPositionByCameraPos; // 0x50
	private static DelegateBridge __Hotfix0__SwitchToBattleFinishService; // 0x58
	private static DelegateBridge __Hotfix0_OnExit; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }
	public override Boolean enableBackpress { get; }

	// RVA: 0x2053970 VA: 0x759466b970
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20539d8 VA: 0x759466b9d8
	public override Boolean get_enablePause() { }
	// RVA: 0x2053a3c VA: 0x759466ba3c
	public override Boolean get_enableShowRange() { }
	// RVA: 0x2053aa0 VA: 0x759466baa0
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2053b04 VA: 0x759466bb04
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x2053b6c VA: 0x759466bb6c
	public override Boolean get_enableBackpress() { }
	// RVA: 0x2053bd0 VA: 0x759466bbd0
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x2053ea8 VA: 0x759466bea8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2054368 VA: 0x759466c368
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20543e0 VA: 0x759466c3e0
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x2054134 VA: 0x759466c134
	private Void _ResetPerformPositionByCameraPos() { }
	// RVA: 0x20542d8 VA: 0x759466c2d8
	private Void _SwitchToBattleFinishService() { }
	// RVA: 0x2054460 VA: 0x759466c460
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20544ec VA: 0x759466c4ec
	public Void .ctor() { }
	// RVA: 0x205455c VA: 0x759466c55c
	private Void <OnEnter>b__17_0(Boolean _) { }
	// RVA: 0x2054560 VA: 0x759466c560
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x2054568 VA: 0x759466c568
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x2054570 VA: 0x759466c570
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x2054578 VA: 0x759466c578
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x2054580 VA: 0x759466c580
	private Boolean <>xLuaBaseProxy_get_enableBackpress() { }
	// RVA: 0x2054588 VA: 0x759466c588
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x2054590 VA: 0x759466c590
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2054598 VA: 0x759466c598
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
	// RVA: 0x20545a0 VA: 0x759466c5a0
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```