# UIBattleSystemMenuState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIBattleSystemMenuPanel _battleMenu`

- `Boolean m_isFromFailState`


## Properties

- `UICharacterInfoPanel characterInfo`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `Void OnCancel()`

- `Void OnRestart()`

- `Void OnRestartForBattle()`

- `Void OnForceSucceed()`

- `Void OnGiveUp()`

- `Void OnConfirmFinish()`

- `Void _SwitchToFailedState(Boolean)`

- `Void <OnConfirmFinish>b__17_0()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleSystemMenuState : UIStateNode
{
	private UIBattleSystemMenuPanel _battleMenu; // 0x20
	private Boolean m_isFromFailState; // 0x28
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x10
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x18
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x20
	private static DelegateBridge __Hotfix0_OnCancel; // 0x28
	private static DelegateBridge __Hotfix0_OnRestart; // 0x30
	private static DelegateBridge __Hotfix0_OnRestartForBattle; // 0x38
	private static DelegateBridge __Hotfix0_OnForceSucceed; // 0x40
	private static DelegateBridge __Hotfix0_OnGiveUp; // 0x48
	private static DelegateBridge __Hotfix0_OnConfirmFinish; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x58
	private static DelegateBridge __Hotfix0_OnEnter; // 0x60
	private static DelegateBridge __Hotfix0_OnExit; // 0x68
	private static DelegateBridge __Hotfix0_OnTick; // 0x70
	private static DelegateBridge __Hotfix0__SwitchToFailedState; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x2057a30 VA: 0x759466fa30
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x2057abc VA: 0x759466fabc
	public override UIStateEnum get_uiState() { }
	// RVA: 0x2057b24 VA: 0x759466fb24
	public override Boolean get_enablePause() { }
	// RVA: 0x2057b88 VA: 0x759466fb88
	public override Boolean get_enableShowRange() { }
	// RVA: 0x2057bec VA: 0x759466fbec
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2057c50 VA: 0x759466fc50
	public Void OnCancel() { }
	// RVA: 0x2057d54 VA: 0x759466fd54
	public Void OnRestart() { }
	// RVA: 0x2057db8 VA: 0x759466fdb8
	public Void OnRestartForBattle() { }
	// RVA: 0x2057e98 VA: 0x759466fe98
	public Void OnForceSucceed() { }
	// RVA: 0x2057efc VA: 0x759466fefc
	public Void OnGiveUp() { }
	// RVA: 0x20580a0 VA: 0x75946700a0
	public Void OnConfirmFinish() { }
	// RVA: 0x20581f8 VA: 0x75946701f8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x2058334 VA: 0x7594670334
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20584b8 VA: 0x75946704b8
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20585d8 VA: 0x75946705d8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x2057f80 VA: 0x759466ff80
	private Void _SwitchToFailedState(Boolean isGiveUp) { }
	// RVA: 0x2058650 VA: 0x7594670650
	public Void .ctor() { }
	// RVA: 0x20586c8 VA: 0x75946706c8
	private Void <OnConfirmFinish>b__17_0() { }
	// RVA: 0x20586d0 VA: 0x75946706d0
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20586d8 VA: 0x75946706d8
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20586e0 VA: 0x75946706e0
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20586e8 VA: 0x75946706e8
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20586f0 VA: 0x75946706f0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20586f8 VA: 0x75946706f8
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```