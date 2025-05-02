# UIEnemyDuelBattleStartState

**Namespace:** `Torappu.Battle.UI.EnemyDuel`


## Fields

- `UIEnemyDuelBattleStartPanel m_panel`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void _OnBattleStart(Object)`

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
// Namespace : Torappu.Battle.UI.EnemyDuel
public class UIEnemyDuelBattleStartState : CommonUIStateNode, IFixedUpdateState
{
	private UIEnemyDuelBattleStartPanel m_panel; // 0x50
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

	// RVA: 0x2090914 VA: 0x75946a8914
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20909a8 VA: 0x75946a89a8
	public override Boolean get_enablePause() { }
	// RVA: 0x2090a0c VA: 0x75946a8a0c
	public override Boolean get_enableShowRange() { }
	// RVA: 0x2090a70 VA: 0x75946a8a70
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2090ad4 VA: 0x75946a8ad4
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x2090b4c VA: 0x75946a8b4c
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x2090db8 VA: 0x75946a8db8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2090ee8 VA: 0x75946a8ee8
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x2090fe4 VA: 0x75946a8fe4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x209105c VA: 0x75946a905c
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20910e8 VA: 0x75946a90e8
	private Void _OnBattleStart(Object arg) { }
	// RVA: 0x20911ac VA: 0x75946a91ac
	public Void .ctor() { }
	// RVA: 0x209121c VA: 0x75946a921c
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x2091224 VA: 0x75946a9224
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x209122c VA: 0x75946a922c
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x2091234 VA: 0x75946a9234
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x209123c VA: 0x75946a923c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2091244 VA: 0x75946a9244
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x209124c VA: 0x75946a924c
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```