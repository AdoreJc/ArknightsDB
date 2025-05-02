# UICooperateShowIdentityBuffState

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateStageWaveStartPanel _waveStartPanel`

- `Single _firstWaveStateWaitTime`

- `Vector3 m_originLocalPosition`

- `UICooperateShowIdentityBuffPanel m_panel`

- `UICooperateStageWaveStartPanel m_wavePanel`

- `CooperateUIPlugin m_plugin`

- `PeriodicTimer m_firstWaveStateTimer`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void _CheckFirstWaveState(FP)`

- `Void _InitIdentityPanel()`

- `Void _ProcessPanelRenderData(ActMultiV3Data, CooperateIdentityInfo, IdentityRenderData, IdentityRenderData)`

- `String _ProcessGameModeColor(ActMultiV3Data, CooperateIdentityInfo)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateShowIdentityBuffState : CommonUIStateNode, IFixedUpdateState
{
	private UICooperateStageWaveStartPanel _waveStartPanel; // 0x50
	private Single _firstWaveStateWaitTime; // 0x58
	private Vector3 m_originLocalPosition; // 0x5c
	private UICooperateShowIdentityBuffPanel m_panel; // 0x68
	private UICooperateStageWaveStartPanel m_wavePanel; // 0x70
	private CooperateUIPlugin m_plugin; // 0x78
	private PeriodicTimer m_firstWaveStateTimer; // 0x80
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x50
	private static DelegateBridge __Hotfix0__CheckFirstWaveState; // 0x58
	private static DelegateBridge __Hotfix0__InitIdentityPanel; // 0x60
	private static DelegateBridge __Hotfix0__ProcessPanelRenderData; // 0x68
	private static DelegateBridge __Hotfix0__ProcessGameModeColor; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x20dee8c VA: 0x75946f6e8c
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20def20 VA: 0x75946f6f20
	public override Boolean get_enablePause() { }
	// RVA: 0x20def84 VA: 0x75946f6f84
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20defe8 VA: 0x75946f6fe8
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20df04c VA: 0x75946f704c
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x20df0b4 VA: 0x75946f70b4
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x20df53c VA: 0x75946f753c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20df990 VA: 0x75946f7990
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20dfa14 VA: 0x75946f7a14
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20dfba0 VA: 0x75946f7ba0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20dfc18 VA: 0x75946f7c18
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20dfac0 VA: 0x75946f7ac0
	private Void _CheckFirstWaveState(FP deltaTime) { }
	// RVA: 0x20df7b8 VA: 0x75946f77b8
	private Void _InitIdentityPanel() { }
	// RVA: 0x20dfcdc VA: 0x75946f7cdc
	private Void _ProcessPanelRenderData(ActMultiV3Data actData, CooperateIdentityInfo identityInfo, IdentityRenderData selfRenderData, IdentityRenderData oppositeRenderData) { }
	// RVA: 0x20dff74 VA: 0x75946f7f74
	private String _ProcessGameModeColor(ActMultiV3Data actData, CooperateIdentityInfo identityInfo) { }
	// RVA: 0x20e011c VA: 0x75946f811c
	public Void .ctor() { }
	// RVA: 0x20e01d4 VA: 0x75946f81d4
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20e01dc VA: 0x75946f81dc
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20e01e4 VA: 0x75946f81e4
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20e01ec VA: 0x75946f81ec
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20e01f4 VA: 0x75946f81f4
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20e01fc VA: 0x75946f81fc
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20e0204 VA: 0x75946f8204
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x20e020c VA: 0x75946f820c
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```