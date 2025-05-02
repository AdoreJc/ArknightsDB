# BossRushCameraPlugin

**Namespace:** `Torappu.Activity.Act1BossRush.Battle`


## Properties

- `Vector3 cameraOffset`


## Methods

- `Vector3 get_cameraOffset()`

- `IEnumerator WaitMoveCameraFinished(Tweener)`

- `Void <>xLuaBaseProxy_DoAdaptCameraPosition()`

- `Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3, Boolean)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3)`

- `Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle
public class BossRushCameraPlugin : Plugin
{
	private const Single MOVE_TIME; // 0x0
	private static DelegateBridge __Hotfix0_get_cameraOffset; // 0x0
	private static DelegateBridge __Hotfix0_DoAdaptCameraPosition; // 0x8
	private static DelegateBridge __Hotfix0_DoMoveCameraDirectly; // 0x10
	private static DelegateBridge __Hotfix0_CalculateCameraFocusPos; // 0x18
	private static DelegateBridge __Hotfix0_CalculateCameraOffset; // 0x20
	private static DelegateBridge __Hotfix0_WaitMoveCameraFinished; // 0x28
	private static DelegateBridge __Hotfix0_TrySetCameraPosition; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Vector3 cameraOffset { get; }

	// RVA: 0x3195984 VA: 0x75957ad984
	private Vector3 get_cameraOffset() { }
	// RVA: 0x3195a14 VA: 0x75957ada14
	public override Void DoAdaptCameraPosition() { }
	// RVA: 0x3195bdc VA: 0x75957adbdc
	public override Void DoMoveCameraDirectly(Vector3 targetPos, Boolean tween) { }
	// RVA: 0x3195f54 VA: 0x75957adf54
	public override Vector3 CalculateCameraFocusPos(Vector3 targetPos) { }
	// RVA: 0x3195ff0 VA: 0x75957adff0
	public override Vector3 CalculateCameraOffset(Vector3 originPos) { }
	// RVA: 0x3195e84 VA: 0x75957ade84
	public IEnumerator WaitMoveCameraFinished(Tweener cameraTweener) { }
	// RVA: 0x31960b4 VA: 0x75957ae0b4
	public override Boolean TrySetCameraPosition(CameraPosition cameraPos, Boolean tween) { }
	// RVA: 0x319640c VA: 0x75957ae40c
	public Void .ctor() { }
	// RVA: 0x319647c VA: 0x75957ae47c
	private Void <>xLuaBaseProxy_DoAdaptCameraPosition() { }
	// RVA: 0x3196484 VA: 0x75957ae484
	private Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3 P0, Boolean P1) { }
	// RVA: 0x3196490 VA: 0x75957ae490
	private Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3 P0) { }
	// RVA: 0x3196498 VA: 0x75957ae498
	private Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3 P0) { }
	// RVA: 0x31964a0 VA: 0x75957ae4a0
	private Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition P0, Boolean P1) { }
}
```