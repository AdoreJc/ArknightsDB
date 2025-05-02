# DouququUIAnnounceState

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `DouququUIPlugin m_plugin`

- `UIBattleDouququAnnouncePanel m_panel`

- `Boolean m_hasStartBattle`

- `DouququGameMode m_manager`


## Methods

- `Void OnAnnounceEnd()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enableBackpress()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class DouququUIAnnounceState : CommonUIStateNode
{
	private DouququUIPlugin m_plugin; // 0x50
	private UIBattleDouququAnnouncePanel m_panel; // 0x58
	private Boolean m_hasStartBattle; // 0x60
	private DouququGameMode m_manager; // 0x68
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enableBackpress; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0_OnAnnounceEnd; // 0x48
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableBackpress { get; }

	// RVA: 0x1dd3b04 VA: 0x75943ebb04
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1dd3b98 VA: 0x75943ebb98
	public override Boolean get_enablePause() { }
	// RVA: 0x1dd3bfc VA: 0x75943ebbfc
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1dd3c60 VA: 0x75943ebc60
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1dd3cc4 VA: 0x75943ebcc4
	public override Boolean get_enableBackpress() { }
	// RVA: 0x1dd3d28 VA: 0x75943ebd28
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1dd4004 VA: 0x75943ec004
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1dd41a4 VA: 0x75943ec1a4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dd421c VA: 0x75943ec21c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1dd0164 VA: 0x75943e8164
	public Void OnAnnounceEnd() { }
	// RVA: 0x1dd42f0 VA: 0x75943ec2f0
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1dd4370 VA: 0x75943ec370
	public Void .ctor() { }
	// RVA: 0x1dd43e0 VA: 0x75943ec3e0
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1dd43e8 VA: 0x75943ec3e8
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1dd43f0 VA: 0x75943ec3f0
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1dd43f8 VA: 0x75943ec3f8
	private Boolean <>xLuaBaseProxy_get_enableBackpress() { }
	// RVA: 0x1dd4400 VA: 0x75943ec400
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1dd4408 VA: 0x75943ec408
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1dd4410 VA: 0x75943ec410
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x1dd4418 VA: 0x75943ec418
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```