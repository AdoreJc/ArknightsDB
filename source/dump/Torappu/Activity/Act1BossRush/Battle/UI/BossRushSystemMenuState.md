# BossRushSystemMenuState

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Fields

- `BossRushSystemMenuPanel _battleMenu`

- `Boolean m_isFromFailState`


## Properties

- `UICharacterInfoPanel characterInfo`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `Void OnCancel()`

- `Void OnConfirmFinish()`

- `Void _SwitchToFailedState(Boolean)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushSystemMenuState : UIStateNode
{
	private BossRushSystemMenuPanel _battleMenu; // 0x20
	private Boolean m_isFromFailState; // 0x28
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x10
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x18
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x20
	private static DelegateBridge __Hotfix0_OnCancel; // 0x28
	private static DelegateBridge __Hotfix0_OnConfirmFinish; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnEnter; // 0x40
	private static DelegateBridge __Hotfix0_OnExit; // 0x48
	private static DelegateBridge __Hotfix0_OnTick; // 0x50
	private static DelegateBridge __Hotfix0__SwitchToFailedState; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x3197764 VA: 0x75957af764
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x31977f0 VA: 0x75957af7f0
	public override UIStateEnum get_uiState() { }
	// RVA: 0x3197884 VA: 0x75957af884
	public override Boolean get_enablePause() { }
	// RVA: 0x31978e8 VA: 0x75957af8e8
	public override Boolean get_enableShowRange() { }
	// RVA: 0x319794c VA: 0x75957af94c
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x31979b0 VA: 0x75957af9b0
	public Void OnCancel() { }
	// RVA: 0x3197a58 VA: 0x75957afa58
	public Void OnConfirmFinish() { }
	// RVA: 0x3197b80 VA: 0x75957afb80
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x3197d30 VA: 0x75957afd30
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3197f54 VA: 0x75957aff54
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x31980e8 VA: 0x75957b00e8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3197adc VA: 0x75957afadc
	private Void _SwitchToFailedState(Boolean isGiveUp) { }
	// RVA: 0x3198160 VA: 0x75957b0160
	public Void .ctor() { }
	// RVA: 0x31981d8 VA: 0x75957b01d8
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x31981e0 VA: 0x75957b01e0
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x31981e8 VA: 0x75957b01e8
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x31981f0 VA: 0x75957b01f0
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x31981f8 VA: 0x75957b01f8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3198200 VA: 0x75957b0200
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```