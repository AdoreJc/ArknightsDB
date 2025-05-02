# LegionUIBattleStartState

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `Transform _parent`

- `UIBattleStartPanel _startPanel`

- `LegionGameMode m_manager`

- `UIBattleStartPanel m_panel`


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
// Namespace : Torappu.Battle.Legion
public class LegionUIBattleStartState : UIStateNode
{
	private Transform _parent; // 0x20
	private UIBattleStartPanel _startPanel; // 0x28
	private LegionGameMode m_manager; // 0x30
	private UIBattleStartPanel m_panel; // 0x38
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

	// RVA: 0x1dbd084 VA: 0x75943d5084
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1dbd118 VA: 0x75943d5118
	public override Boolean get_enablePause() { }
	// RVA: 0x1dbd17c VA: 0x75943d517c
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1dbd1e0 VA: 0x75943d51e0
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1dbd244 VA: 0x75943d5244
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1dbd3d8 VA: 0x75943d53d8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1dbd664 VA: 0x75943d5664
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dbd6dc VA: 0x75943d56dc
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1dbd7a0 VA: 0x75943d57a0
	public Void .ctor() { }
	// RVA: 0x1dbd810 VA: 0x75943d5810
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1dbd818 VA: 0x75943d5818
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1dbd820 VA: 0x75943d5820
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1dbd828 VA: 0x75943d5828
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1dbd830 VA: 0x75943d5830
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1dbd838 VA: 0x75943d5838
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```