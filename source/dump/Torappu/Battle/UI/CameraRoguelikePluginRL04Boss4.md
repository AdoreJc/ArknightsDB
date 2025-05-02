# CameraRoguelikePluginRL04Boss4

**Namespace:** `Torappu.Battle.UI`


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
// Namespace : Torappu.Battle.UI
public class CameraRoguelikePluginRL04Boss4 : Plugin
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

	// RVA: 0x2071498 VA: 0x7594689498
	private Vector3 get_cameraOffset() { }
	// RVA: 0x2071528 VA: 0x7594689528
	public override Vector3 CalculateCameraFocusPos(Vector3 targetPos) { }
	// RVA: 0x20715c4 VA: 0x75946895c4
	public override Vector3 CalculateCameraOffset(Vector3 originPos) { }
	// RVA: 0x2071660 VA: 0x7594689660
	public override Void DoMoveCameraDirectly(Vector3 offset, Boolean tween) { }
	// RVA: 0x2071968 VA: 0x7594689968
	public override Boolean TrySetCameraPosition(CameraPosition cameraPos, Boolean tween) { }
	// RVA: 0x2071cc0 VA: 0x7594689cc0
	private Void _OnUpdateCameraMove() { }
	// RVA: 0x2071d3c VA: 0x7594689d3c
	private Void _OnFinishCameraMove() { }
	// RVA: 0x2071e00 VA: 0x7594689e00
	public Void .ctor() { }
	// RVA: 0x2071e70 VA: 0x7594689e70
	private Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3 P0) { }
	// RVA: 0x2071e78 VA: 0x7594689e78
	private Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3 P0) { }
	// RVA: 0x2071e80 VA: 0x7594689e80
	private Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3 P0, Boolean P1) { }
	// RVA: 0x2071e8c VA: 0x7594689e8c
	private Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition P0, Boolean P1) { }
}
```