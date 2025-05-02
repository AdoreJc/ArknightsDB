# LegionUICardSelectState

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `BattleLegionSelectCardParam selectData`

- `LegionGameMode m_manager`

- `LegionUIPlugin m_plugin`

- `UIBattleLegionCardSelectPanel m_panel`


## Properties

- `Int32 inHandCardCount`

- `Int32 maxCardCount`


## Methods

- `Int32 get_inHandCardCount()`

- `Int32 get_maxCardCount()`

- `Void SelectDone(List`1, List`1)`

- `Void CancelSelect(List`1)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`

- `Void <>xLuaBaseProxy_OnPanelHiden()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class LegionUICardSelectState : CommonUIStateNode
{
	public BattleLegionSelectCardParam selectData; // 0x50
	private LegionGameMode m_manager; // 0x80
	private LegionUIPlugin m_plugin; // 0x88
	private UIBattleLegionCardSelectPanel m_panel; // 0x90
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_inHandCardCount; // 0x20
	private static DelegateBridge __Hotfix0_get_maxCardCount; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x50
	private static DelegateBridge __Hotfix0_OnPanelHiden; // 0x58
	private static DelegateBridge __Hotfix0_SelectDone; // 0x60
	private static DelegateBridge __Hotfix0_CancelSelect; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public Int32 inHandCardCount { get; }
	public Int32 maxCardCount { get; }

	// RVA: 0x1dbeaec VA: 0x75943d6aec
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1dbeb80 VA: 0x75943d6b80
	public override Boolean get_enablePause() { }
	// RVA: 0x1dbebe4 VA: 0x75943d6be4
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1dbec48 VA: 0x75943d6c48
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1db55a8 VA: 0x75943cd5a8
	public Int32 get_inHandCardCount() { }
	// RVA: 0x1db5628 VA: 0x75943cd628
	public Int32 get_maxCardCount() { }
	// RVA: 0x1dbecac VA: 0x75943d6cac
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1dbeeac VA: 0x75943d6eac
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1dbf1a4 VA: 0x75943d71a4
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1dbf294 VA: 0x75943d7294
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dbf30c VA: 0x75943d730c
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1dbf3a0 VA: 0x75943d73a0
	public override Void OnPanelHiden() { }
	// RVA: 0x1db5ba4 VA: 0x75943cdba4
	public Void SelectDone(List`1 selectRangeIds, List`1 selectIds) { }
	// RVA: 0x1db60dc VA: 0x75943ce0dc
	public Void CancelSelect(List`1 selectRangeIds) { }
	// RVA: 0x1dbf414 VA: 0x75943d7414
	public Void .ctor() { }
	// RVA: 0x1dbf484 VA: 0x75943d7484
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1dbf48c VA: 0x75943d748c
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1dbf494 VA: 0x75943d7494
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1dbf49c VA: 0x75943d749c
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1dbf4a4 VA: 0x75943d74a4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1dbf4ac VA: 0x75943d74ac
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x1dbf4b4 VA: 0x75943d74b4
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
	// RVA: 0x1dbf4bc VA: 0x75943d74bc
	private Void <>xLuaBaseProxy_OnPanelHiden() { }
}
```