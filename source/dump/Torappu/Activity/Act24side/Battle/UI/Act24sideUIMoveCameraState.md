# Act24sideUIMoveCameraState

**Namespace:** `Torappu.Activity.Act24side.Battle.UI`


## Methods

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side.Battle.UI
public class Act24sideUIMoveCameraState : UIStateNode
{
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x32e5218 VA: 0x75958fd218
	public override UIStateEnum get_uiState() { }
	// RVA: 0x32e52ac VA: 0x75958fd2ac
	public override Boolean get_enablePause() { }
	// RVA: 0x32e5310 VA: 0x75958fd310
	public override Boolean get_enableShowRange() { }
	// RVA: 0x32e5374 VA: 0x75958fd374
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x32e53d8 VA: 0x75958fd3d8
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x32e5440 VA: 0x75958fd440
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x32e54b8 VA: 0x75958fd4b8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x32e55a0 VA: 0x75958fd5a0
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x32e565c VA: 0x75958fd65c
	public Void .ctor() { }
	// RVA: 0x32e56cc VA: 0x75958fd6cc
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x32e56d4 VA: 0x75958fd6d4
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x32e56dc VA: 0x75958fd6dc
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x32e56e4 VA: 0x75958fd6e4
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x32e56ec VA: 0x75958fd6ec
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x32e56f4 VA: 0x75958fd6f4
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```