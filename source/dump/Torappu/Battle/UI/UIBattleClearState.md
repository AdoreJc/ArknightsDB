# UIBattleClearState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `RectTransform _battleClearPanel`


## Methods

- `Void OnRestart()`

- `Void _ClearImpl()`

- `Void _ContinueBattle(DefaultContinueBattleResponse)`

- `Void _JumpToBattleFinish(BattleClearStateParam)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleClearState : UIStateNode
{
	private RectTransform _battleClearPanel; // 0x20
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnRestart; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge __Hotfix0__ClearImpl; // 0x48
	private static DelegateBridge __Hotfix0__ContinueBattle; // 0x50
	private static DelegateBridge __Hotfix0__JumpToBattleFinish; // 0x58
	private static DelegateBridge __Hotfix0__UseLiteBattleFinish; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x20545a8 VA: 0x759466c5a8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x2054610 VA: 0x759466c610
	public override Boolean get_enablePause() { }
	// RVA: 0x2054674 VA: 0x759466c674
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20546d8 VA: 0x759466c6d8
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x205473c VA: 0x759466c73c
	public Void OnRestart() { }
	// RVA: 0x20547c8 VA: 0x759466c7c8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x205487c VA: 0x759466c87c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2054a94 VA: 0x759466ca94
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x2054b0c VA: 0x759466cb0c
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x2054908 VA: 0x759466c908
	private Void _ClearImpl() { }
	// RVA: 0x2054b84 VA: 0x759466cb84
	private Void _ContinueBattle(DefaultContinueBattleResponse continueResponse) { }
	// RVA: 0x2054c38 VA: 0x759466cc38
	private Void _JumpToBattleFinish(BattleClearStateParam clearParam) { }
	// RVA: 0x205500c VA: 0x759466d00c
	private static Boolean _UseLiteBattleFinish() { }
	// RVA: 0x20551fc VA: 0x759466d1fc
	public Void .ctor() { }
	// RVA: 0x205526c VA: 0x759466d26c
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x2055274 VA: 0x759466d274
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x205527c VA: 0x759466d27c
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x2055284 VA: 0x759466d284
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x205528c VA: 0x759466d28c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2055294 VA: 0x759466d294
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```