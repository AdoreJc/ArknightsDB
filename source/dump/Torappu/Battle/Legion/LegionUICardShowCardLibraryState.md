# LegionUICardShowCardLibraryState

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `BattleLegionCardLibraryParam m_libraryData`

- `LegionUIPlugin m_plugin`

- `UIBattleLegionShowCardLibraryPanel m_panel`


## Methods

- `Void CloseUsedAndPendingPanel()`

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
// Namespace : Torappu.Battle.Legion
public class LegionUICardShowCardLibraryState : CommonUIStateNode
{
	private BattleLegionCardLibraryParam m_libraryData; // 0x50
	private LegionUIPlugin m_plugin; // 0x60
	private UIBattleLegionShowCardLibraryPanel m_panel; // 0x68
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge __Hotfix0_CloseUsedAndPendingPanel; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x1dbf4c4 VA: 0x75943d74c4
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1dbf558 VA: 0x75943d7558
	public override Boolean get_enablePause() { }
	// RVA: 0x1dbf5bc VA: 0x75943d75bc
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1dbf620 VA: 0x75943d7620
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1dbf684 VA: 0x75943d7684
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1dbf7bc VA: 0x75943d77bc
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1dbfa00 VA: 0x75943d7a00
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1dbfaec VA: 0x75943d7aec
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dbfb64 VA: 0x75943d7b64
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1dbfc30 VA: 0x75943d7c30
	public Void CloseUsedAndPendingPanel() { }
	// RVA: 0x1dbfdac VA: 0x75943d7dac
	public Void .ctor() { }
	// RVA: 0x1dbfe1c VA: 0x75943d7e1c
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1dbfe24 VA: 0x75943d7e24
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1dbfe2c VA: 0x75943d7e2c
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1dbfe34 VA: 0x75943d7e34
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1dbfe3c VA: 0x75943d7e3c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1dbfe44 VA: 0x75943d7e44
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x1dbfe4c VA: 0x75943d7e4c
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```