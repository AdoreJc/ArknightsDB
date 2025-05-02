# FreeFollowCameraPlugin

**Namespace:** `Torappu.Battle`


## Fields

- `Single _followFactor`

- `Single _zoomResetDuration`

- `Single _zoomInScaleFactor`

- `Single _shakeDuration`

- `Single _shakeStrengthFactor`

- `Int32 _shakeVibrato`

- `Single _shakeRandomness`

- `Boolean _disableSideBy`

- `Boolean m_isFollowing`

- `Boolean m_isZoomIn`

- `Single m_followFactor`

- `Single m_cameraOriginScale`


## Properties

- `Boolean isFollowing`

- `Boolean isZoomIn`


## Methods

- `Boolean get_isFollowing()`

- `Void set_isFollowing(Boolean)`

- `Boolean get_isZoomIn()`

- `Void SetTarget(Entity)`

- `Void ZoomIn(Single, Single)`

- `Void ResetZoom(Single)`

- `Void ShakeCamera(Vector2)`

- `Void FixedUpdate()`

- `Void _UpdateFollowCamera()`

- `Vector3 _GetLerpFollowCameraPosition(Vector3, Vector3)`

- `Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition, Boolean)`

- `Void <>xLuaBaseProxy__InitIfNot()`

- `Void <>xLuaBaseProxy__UpdateCamera()`

- `Void <>xLuaBaseProxy__OnBeginDrag(Object)`

- `Boolean <>xLuaBaseProxy_IsDragValidState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FreeFollowCameraPlugin : DraggableCameraPlugin
{
	private Single _followFactor; // 0xc0
	private Single _zoomResetDuration; // 0xc4
	private Single _zoomInScaleFactor; // 0xc8
	private Single _shakeDuration; // 0xcc
	private Single _shakeStrengthFactor; // 0xd0
	private Int32 _shakeVibrato; // 0xd4
	private Single _shakeRandomness; // 0xd8
	private Boolean _disableSideBy; // 0xdc
	private ObjectPtr`1 m_target; // 0xe0
	private Boolean m_isFollowing; // 0xf0
	private Boolean m_isZoomIn; // 0xf1
	private Single m_followFactor; // 0xf4
	private Single m_cameraOriginScale; // 0xf8
	private static DelegateBridge __Hotfix0_get_isFollowing; // 0x0
	private static DelegateBridge __Hotfix0_set_isFollowing; // 0x8
	private static DelegateBridge __Hotfix0_get_isZoomIn; // 0x10
	private static DelegateBridge __Hotfix0_SetTarget; // 0x18
	private static DelegateBridge __Hotfix0_ZoomIn; // 0x20
	private static DelegateBridge __Hotfix0_ResetZoom; // 0x28
	private static DelegateBridge __Hotfix0_ShakeCamera; // 0x30
	private static DelegateBridge __Hotfix0_TrySetCameraPosition; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__UpdateCamera; // 0x48
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x50
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x58
	private static DelegateBridge __Hotfix0_IsDragValidState; // 0x60
	private static DelegateBridge __Hotfix0__UpdateFollowCamera; // 0x68
	private static DelegateBridge __Hotfix0__GetLerpFollowCameraPosition; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Boolean isFollowing { get; set; }
	public Boolean isZoomIn { get; }

	// RVA: 0x3fa3da0 VA: 0x75965bbda0
	public Boolean get_isFollowing() { }
	// RVA: 0x3fa3e08 VA: 0x75965bbe08
	public Void set_isFollowing(Boolean value) { }
	// RVA: 0x3fa3f68 VA: 0x75965bbf68
	public Boolean get_isZoomIn() { }
	// RVA: 0x3fa3fd0 VA: 0x75965bbfd0
	public Void SetTarget(Entity target) { }
	// RVA: 0x3fa4088 VA: 0x75965bc088
	public Void ZoomIn(Single duration, Single zoomInFactor) { }
	// RVA: 0x3fa3ec0 VA: 0x75965bbec0
	public Void ResetZoom(Single duration) { }
	// RVA: 0x3fa4154 VA: 0x75965bc154
	public Void ShakeCamera(Vector2 dir) { }
	// RVA: 0x3fa41fc VA: 0x75965bc1fc
	public override Boolean TrySetCameraPosition(CameraPosition cameraPos, Boolean tween) { }
	// RVA: 0x3fa42ac VA: 0x75965bc2ac
	protected override Void _InitIfNot() { }
	// RVA: 0x3fa4340 VA: 0x75965bc340
	protected override Void _UpdateCamera() { }
	// RVA: 0x3fa4650 VA: 0x75965bc650
	private Void FixedUpdate() { }
	// RVA: 0x3fa46cc VA: 0x75965bc6cc
	protected override Void _OnBeginDrag(Object arg) { }
	// RVA: 0x3fa4764 VA: 0x75965bc764
	protected override Boolean IsDragValidState() { }
	// RVA: 0x3fa4464 VA: 0x75965bc464
	private Void _UpdateFollowCamera() { }
	// RVA: 0x3fa4848 VA: 0x75965bc848
	private Vector3 _GetLerpFollowCameraPosition(Vector3 curCameraPos, Vector3 targetPos) { }
	// RVA: 0x3fa492c VA: 0x75965bc92c
	public Void .ctor() { }
	// RVA: 0x3fa49b4 VA: 0x75965bc9b4
	private Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition P0, Boolean P1) { }
	// RVA: 0x3fa49bc VA: 0x75965bc9bc
	private Void <>xLuaBaseProxy__InitIfNot() { }
	// RVA: 0x3fa49c0 VA: 0x75965bc9c0
	private Void <>xLuaBaseProxy__UpdateCamera() { }
	// RVA: 0x3fa49c4 VA: 0x75965bc9c4
	private Void <>xLuaBaseProxy__OnBeginDrag(Object P0) { }
	// RVA: 0x3fa49c8 VA: 0x75965bc9c8
	private Boolean <>xLuaBaseProxy_IsDragValidState() { }
}
```