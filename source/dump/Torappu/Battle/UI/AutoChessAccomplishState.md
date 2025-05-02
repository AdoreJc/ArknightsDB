# AutoChessAccomplishState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Vector3 _preformOffset`


## Properties

- `AutoChessCameraPlugin cameraPlugin`

- `UIAnimationPerform accomplishedPerform`


## Methods

- `AutoChessCameraPlugin get_cameraPlugin()`

- `UIAnimationPerform get_accomplishedPerform()`

- `Void _PlayPerform()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessAccomplishState : UIStateNode
{
	private Vector3 _preformOffset; // 0x20
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x0
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x8
	private static DelegateBridge __Hotfix0_get_uiState; // 0x10
	private static DelegateBridge __Hotfix0_get_accomplishedPerform; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0__PlayPerform; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Boolean enablePerspectiveCanvas { get; }
	private AutoChessCameraPlugin cameraPlugin { get; }
	public override UIStateEnum uiState { get; }
	private UIAnimationPerform accomplishedPerform { get; }

	// RVA: 0x201fee0 VA: 0x7594637ee0
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x201ff48 VA: 0x7594637f48
	private AutoChessCameraPlugin get_cameraPlugin() { }
	// RVA: 0x2020024 VA: 0x7594638024
	public override UIStateEnum get_uiState() { }
	// RVA: 0x202008c VA: 0x759463808c
	private UIAnimationPerform get_accomplishedPerform() { }
	// RVA: 0x2020118 VA: 0x7594638118
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20205d0 VA: 0x75946385d0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x202038c VA: 0x759463838c
	private Void _PlayPerform() { }
	// RVA: 0x2020648 VA: 0x7594638648
	public Void .ctor() { }
	// RVA: 0x20206b8 VA: 0x75946386b8
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20206c0 VA: 0x75946386c0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```