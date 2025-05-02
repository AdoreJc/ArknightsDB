# DouququUIRoundEndState

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `DouququUIPlugin m_plugin`

- `UIBattleDouququRoundEndPanel m_panel`

- `DouququGameMode m_manager`


## Methods

- `Void OnRoundResultShowEnd()`

- `Void OnRoundEndOver(Boolean)`

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
public class DouququUIRoundEndState : CommonUIStateNode
{
	private DouququUIPlugin m_plugin; // 0x50
	private UIBattleDouququRoundEndPanel m_panel; // 0x58
	private DouququGameMode m_manager; // 0x60
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enableBackpress; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0_OnRoundResultShowEnd; // 0x48
	private static DelegateBridge __Hotfix0_OnRoundEndOver; // 0x50
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableBackpress { get; }

	// RVA: 0x1dd5420 VA: 0x75943ed420
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1dd54b4 VA: 0x75943ed4b4
	public override Boolean get_enablePause() { }
	// RVA: 0x1dd5518 VA: 0x75943ed518
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1dd557c VA: 0x75943ed57c
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1dd55e0 VA: 0x75943ed5e0
	public override Boolean get_enableBackpress() { }
	// RVA: 0x1dd5644 VA: 0x75943ed644
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1dd5920 VA: 0x75943ed920
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1dd5a9c VA: 0x75943eda9c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dd5b14 VA: 0x75943edb14
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1dd5be8 VA: 0x75943edbe8
	public Void OnRoundResultShowEnd() { }
	// RVA: 0x1dd5c7c VA: 0x75943edc7c
	public Void OnRoundEndOver(Boolean isFinish) { }
	// RVA: 0x1dd5e3c VA: 0x75943ede3c
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1dd5ebc VA: 0x75943edebc
	public Void .ctor() { }
	// RVA: 0x1dd5f2c VA: 0x75943edf2c
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1dd5f34 VA: 0x75943edf34
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1dd5f3c VA: 0x75943edf3c
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1dd5f44 VA: 0x75943edf44
	private Boolean <>xLuaBaseProxy_get_enableBackpress() { }
	// RVA: 0x1dd5f4c VA: 0x75943edf4c
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1dd5f54 VA: 0x75943edf54
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1dd5f5c VA: 0x75943edf5c
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x1dd5f64 VA: 0x75943edf64
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```