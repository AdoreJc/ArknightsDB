# Act24sideCameraPlugin

**Namespace:** `Torappu.Activity.Act24side.Battle`


## Properties

- `Vector3 cameraOffset`


## Methods

- `Vector3 get_cameraOffset()`

- `Void _OnUpdateCameraMove()`

- `Void _OnFinishCameraMove()`

- `Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3)`

- `Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3, Boolean)`

- `Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side.Battle
public class Act24sideCameraPlugin : Plugin
{
	private const Single MOVE_TIME; // 0x0
	private static DelegateBridge __Hotfix0_get_cameraOffset; // 0x0
	private static DelegateBridge __Hotfix0_CalculateCameraFocusPos; // 0x8
	private static DelegateBridge __Hotfix0_CalculateCameraOffset; // 0x10
	private static DelegateBridge __Hotfix0_DoMoveCameraDirectly; // 0x18
	private static DelegateBridge __Hotfix0_TrySetCameraPosition; // 0x20
	private static DelegateBridge __Hotfix0__OnUpdateCameraMove; // 0x28
	private static DelegateBridge __Hotfix0__OnFinishCameraMove; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Vector3 cameraOffset { get; }

	// RVA: 0x32e45a0 VA: 0x75958fc5a0
	private Vector3 get_cameraOffset() { }
	// RVA: 0x32e4630 VA: 0x75958fc630
	public override Vector3 CalculateCameraFocusPos(Vector3 targetPos) { }
	// RVA: 0x32e46cc VA: 0x75958fc6cc
	public override Vector3 CalculateCameraOffset(Vector3 originPos) { }
	// RVA: 0x32e4768 VA: 0x75958fc768
	public override Void DoMoveCameraDirectly(Vector3 offset, Boolean tween) { }
	// RVA: 0x32e4a90 VA: 0x75958fca90
	public override Boolean TrySetCameraPosition(CameraPosition cameraPos, Boolean tween) { }
	// RVA: 0x32e4de8 VA: 0x75958fcde8
	private Void _OnUpdateCameraMove() { }
	// RVA: 0x32e4e64 VA: 0x75958fce64
	private Void _OnFinishCameraMove() { }
	// RVA: 0x32e4f2c VA: 0x75958fcf2c
	public Void .ctor() { }
	// RVA: 0x32e4f9c VA: 0x75958fcf9c
	private Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3 P0) { }
	// RVA: 0x32e4fa4 VA: 0x75958fcfa4
	private Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3 P0) { }
	// RVA: 0x32e4fac VA: 0x75958fcfac
	private Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3 P0, Boolean P1) { }
	// RVA: 0x32e4fb8 VA: 0x75958fcfb8
	private Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition P0, Boolean P1) { }
}
```