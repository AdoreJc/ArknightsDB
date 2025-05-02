# GameCityWaveStartState

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `GameCityWaveStartPanel _perform`

- `Vector3 m_offset`

- `GameCityWaveStartPanel m_panel`


## Methods

- `Void _ResetPerformPositionByCameraPos()`

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
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCityWaveStartState : UIStateNode
{
	private GameCityWaveStartPanel _perform; // 0x20
	private Vector3 m_offset; // 0x28
	private GameCityWaveStartPanel m_panel; // 0x38
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x48
	private static DelegateBridge __Hotfix0__ResetPerformPositionByCameraPos; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x33e91c4 VA: 0x7595a011c4
	public override UIStateEnum get_uiState() { }
	// RVA: 0x33e9258 VA: 0x7595a01258
	public override Boolean get_enablePause() { }
	// RVA: 0x33e92bc VA: 0x7595a012bc
	public override Boolean get_enableShowRange() { }
	// RVA: 0x33e9320 VA: 0x7595a01320
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x33e9384 VA: 0x7595a01384
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x33e93ec VA: 0x7595a013ec
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x33e962c VA: 0x7595a0162c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x33e9e8c VA: 0x7595a01e8c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x33e9f04 VA: 0x7595a01f04
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x33e9fa8 VA: 0x7595a01fa8
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x33e99f8 VA: 0x7595a019f8
	private Void _ResetPerformPositionByCameraPos() { }
	// RVA: 0x33ea028 VA: 0x7595a02028
	public Void .ctor() { }
	// RVA: 0x33ea098 VA: 0x7595a02098
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x33ea0a0 VA: 0x7595a020a0
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x33ea0a8 VA: 0x7595a020a8
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x33ea0b0 VA: 0x7595a020b0
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x33ea0b8 VA: 0x7595a020b8
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x33ea0c0 VA: 0x7595a020c0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x33ea0c8 VA: 0x7595a020c8
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x33ea0d0 VA: 0x7595a020d0
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```