# BossRushMoveCameraState

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Methods

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushMoveCameraState : UIStateNode
{
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x3197174 VA: 0x75957af174
	public override UIStateEnum get_uiState() { }
	// RVA: 0x3197208 VA: 0x75957af208
	public override Boolean get_enablePause() { }
	// RVA: 0x319726c VA: 0x75957af26c
	public override Boolean get_enableShowRange() { }
	// RVA: 0x31972d0 VA: 0x75957af2d0
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x3197334 VA: 0x75957af334
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x319739c VA: 0x75957af39c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3197414 VA: 0x75957af414
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3197554 VA: 0x75957af554
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x3197604 VA: 0x75957af604
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x31976bc VA: 0x75957af6bc
	public Void .ctor() { }
	// RVA: 0x319772c VA: 0x75957af72c
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x3197734 VA: 0x75957af734
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x319773c VA: 0x75957af73c
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x3197744 VA: 0x75957af744
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x319774c VA: 0x75957af74c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3197754 VA: 0x75957af754
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
	// RVA: 0x319775c VA: 0x75957af75c
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```