# GameCitySystemMenuState

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `UIBattleSystemMenuPanel _battleMenu`


## Properties

- `UICharacterInfoPanel characterInfo`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `Void OnCancel()`

- `Void OnRestartForBattle()`

- `Void OnConfirmFinish()`

- `Void _SwitchToBattleFinish()`

- `Void <OnConfirmFinish>b__13_0()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCitySystemMenuState : UIStateNode
{
	private UIBattleSystemMenuPanel _battleMenu; // 0x20
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x10
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x18
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x20
	private static DelegateBridge __Hotfix0_OnCancel; // 0x28
	private static DelegateBridge __Hotfix0_OnRestartForBattle; // 0x30
	private static DelegateBridge __Hotfix0_OnConfirmFinish; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnExit; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0__SwitchToBattleFinish; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x33e8668 VA: 0x7595a00668
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x33e86f4 VA: 0x7595a006f4
	public override UIStateEnum get_uiState() { }
	// RVA: 0x33e8788 VA: 0x7595a00788
	public override Boolean get_enablePause() { }
	// RVA: 0x33e87ec VA: 0x7595a007ec
	public override Boolean get_enableShowRange() { }
	// RVA: 0x33e8850 VA: 0x7595a00850
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x33e88b4 VA: 0x7595a008b4
	public Void OnCancel() { }
	// RVA: 0x33e89a4 VA: 0x7595a009a4
	public Void OnRestartForBattle() { }
	// RVA: 0x33e8a84 VA: 0x7595a00a84
	public Void OnConfirmFinish() { }
	// RVA: 0x33e8bcc VA: 0x7595a00bcc
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x33e8d08 VA: 0x7595a00d08
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x33e8e3c VA: 0x7595a00e3c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x33e8f54 VA: 0x7595a00f54
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x33e8fcc VA: 0x7595a00fcc
	private Void _SwitchToBattleFinish() { }
	// RVA: 0x33e9120 VA: 0x7595a01120
	public Void .ctor() { }
	// RVA: 0x33e9190 VA: 0x7595a01190
	private Void <OnConfirmFinish>b__13_0() { }
	// RVA: 0x33e9194 VA: 0x7595a01194
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x33e919c VA: 0x7595a0119c
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x33e91a4 VA: 0x7595a011a4
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x33e91ac VA: 0x7595a011ac
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x33e91b4 VA: 0x7595a011b4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x33e91bc VA: 0x7595a011bc
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```