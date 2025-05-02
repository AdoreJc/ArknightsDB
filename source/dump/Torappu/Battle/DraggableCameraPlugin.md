# DraggableCameraPlugin

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _enableSlowMotion`

- `Single _dragScale`

- `Single _focusDistance`

- `Single _focusTime`

- `Single _focusRange`

- `Ease _easeType`

- `Single _fallBackSmoothTime`

- `Vector2 _resizeWH`

- `Single _resolutionWidth`

- `DragMode _dragMode`

- `Vector2 _audioVolumeSyncCameraPosRange`

- `Boolean _enableSmooth`

- `Single _smoothFollowFactor`

- `AnimationCurve _smoothStepCurve`

- `Single _smoothStepScale`

- `Single _cameHeightFactor`

- `AnimationCurve _releaseCurve`

- `Single _releaseTime`

- `Tween m_tween`

- `Boolean m_inited`

- `Boolean m_dragEnabled`

- `Int32 m_dragPausedMask`

- `PointerEventData m_pointer`

- `Single m_resolutionScale`

- `Vector3 m_followCurrentVelocity`

- `DragStatus m_status`

- `ConvexHull m_mapHull`


## Properties

- `DragStatus status`

- `ConvexHull mapHull`

- `Boolean dragEnabled`


## Methods

- `DragStatus get_status()`

- `ConvexHull get_mapHull()`

- `Boolean get_dragEnabled()`

- `Void PauseDrag(DragPauseReason, Boolean)`

- `Void UpdateHull()`

- `Void Update()`

- `Void _UpdateDragCamera()`

- `Void ResetCameraWithinHull()`

- `Void _ReleaseDrag()`

- `Void _MoveCamera(Vector2)`

- `Vector2 _CalcScreenDragOffset(Vector2, Single)`

- `Vector2 GetPosInHull(Vector2)`

- `Void _ResetControllerTween()`

- `Boolean _IsDragStateValid(out)`

- `Boolean _IsCornerVertex(Int32, Int32)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3)`

- `Vector2 <>xLuaBaseProxy_get_audioVolumeSyncCameraPosRange()`

- `Boolean <>xLuaBaseProxy_IsValidPut(Int32)`

- `Void <>xLuaBaseProxy_PutDown(Transform)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3)`

- `Void <>xLuaBaseProxy_DoAdaptCameraPosition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DraggableCameraPlugin : Plugin
{
	private const String BANNED_PUTDOWN_UI_TAG; // 0x0
	protected const Int32 RELEASE_FRAME; // 0x0
	private Boolean _enableSlowMotion; // 0x20
	private Single _dragScale; // 0x24
	private Single _focusDistance; // 0x28
	private Single _focusTime; // 0x2c
	private Single _focusRange; // 0x30
	private Ease _easeType; // 0x34
	private Single _fallBackSmoothTime; // 0x38
	private Vector2 _resizeWH; // 0x3c
	private Single _resolutionWidth; // 0x44
	private DragMode _dragMode; // 0x48
	private Vector2 _audioVolumeSyncCameraPosRange; // 0x4c
	private Boolean _enableSmooth; // 0x54
	private Single _smoothFollowFactor; // 0x58
	private AnimationCurve _smoothStepCurve; // 0x60
	private Single _smoothStepScale; // 0x68
	private Single _cameHeightFactor; // 0x6c
	private AnimationCurve _releaseCurve; // 0x70
	private Single _releaseTime; // 0x78
	private Tween m_tween; // 0x80
	private Boolean m_inited; // 0x88
	private Boolean m_dragEnabled; // 0x89
	private Int32 m_dragPausedMask; // 0x8c
	private PointerEventData m_pointer; // 0x90
	private List`1 m_rayCastCache; // 0x98
	private Single m_resolutionScale; // 0xa0
	private Vector3 m_followCurrentVelocity; // 0xa4
	private DragStatus m_status; // 0xb0
	private ConvexHull m_mapHull; // 0xb8
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_get_mapHull; // 0x8
	private static DelegateBridge __Hotfix0_get_dragEnabled; // 0x10
	private static DelegateBridge __Hotfix0_CalculateCameraOffset; // 0x18
	private static DelegateBridge __Hotfix0_get_audioVolumeSyncCameraPosRange; // 0x20
	private static DelegateBridge __Hotfix0_PauseDrag; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_UpdateHull; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x48
	private static DelegateBridge __Hotfix0__UpdateCamera; // 0x50
	private static DelegateBridge __Hotfix0__UpdateDragCamera; // 0x58
	private static DelegateBridge __Hotfix0_ResetCameraWithinHull; // 0x60
	private static DelegateBridge __Hotfix0__ReleaseDrag; // 0x68
	private static DelegateBridge __Hotfix0__MoveCamera; // 0x70
	private static DelegateBridge __Hotfix0__CalcScreenDragOffset; // 0x78
	private static DelegateBridge __Hotfix0_IsValidPut; // 0x80
	private static DelegateBridge __Hotfix0_GetPosInHull; // 0x88
	private static DelegateBridge __Hotfix0_PutDown; // 0x90
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x98
	private static DelegateBridge __Hotfix0__ResetControllerTween; // 0xa0
	private static DelegateBridge __Hotfix0_CalculateCameraFocusPos; // 0xa8
	private static DelegateBridge __Hotfix0__IsDragStateValid; // 0xb0
	private static DelegateBridge __Hotfix0_IsDragValidState; // 0xb8
	private static DelegateBridge __Hotfix0__GetMapCorners; // 0xc0
	private static DelegateBridge __Hotfix0__IsCornerVertex; // 0xc8
	private static DelegateBridge __Hotfix0_DoAdaptCameraPosition; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	protected DragStatus status { get; }
	protected ConvexHull mapHull { get; }
	public Boolean dragEnabled { get; }
	public override Vector2 audioVolumeSyncCameraPosRange { get; }

	// RVA: 0x3fa125c VA: 0x75965b925c
	protected DragStatus get_status() { }
	// RVA: 0x3fa1324 VA: 0x75965b9324
	protected ConvexHull get_mapHull() { }
	// RVA: 0x3fa138c VA: 0x75965b938c
	public Boolean get_dragEnabled() { }
	// RVA: 0x3fa140c VA: 0x75965b940c
	public override Vector3 CalculateCameraOffset(Vector3 originPos) { }
	// RVA: 0x3fa14cc VA: 0x75965b94cc
	public override Vector2 get_audioVolumeSyncCameraPosRange() { }
	// RVA: 0x3fa1530 VA: 0x75965b9530
	public Void PauseDrag(DragPauseReason reason, Boolean pause) { }
	// RVA: 0x3fa15c8 VA: 0x75965b95c8
	protected virtual Void _InitIfNot() { }
	// RVA: 0x3fa1ab0 VA: 0x75965b9ab0
	public Void UpdateHull() { }
	// RVA: 0x3fa1b58 VA: 0x75965b9b58
	private Void Update() { }
	// RVA: 0x3fa1c1c VA: 0x75965b9c1c
	protected virtual Void _OnBeginDrag(Object arg) { }
	// RVA: 0x3fa1db4 VA: 0x75965b9db4
	protected virtual Void _UpdateCamera() { }
	// RVA: 0x3fa1e1c VA: 0x75965b9e1c
	private Void _UpdateDragCamera() { }
	// RVA: 0x3fa2188 VA: 0x75965ba188
	protected Void ResetCameraWithinHull() { }
	// RVA: 0x3fa180c VA: 0x75965b980c
	private Void _ReleaseDrag() { }
	// RVA: 0x3fa23ac VA: 0x75965ba3ac
	private Void _MoveCamera(Vector2 screenPosCurFrame) { }
	// RVA: 0x3fa2840 VA: 0x75965ba840
	private Vector2 _CalcScreenDragOffset(Vector2 screenPosCurFrame, Single deltaTime) { }
	// RVA: 0x3fa2acc VA: 0x75965baacc
	public override Boolean IsValidPut(Int32 touchId) { }
	// RVA: 0x3fa2d4c VA: 0x75965bad4c
	public Vector2 GetPosInHull(Vector2 targetPos) { }
	// RVA: 0x3fa2e20 VA: 0x75965bae20
	public override Void PutDown(Transform ts) { }
	// RVA: 0x3fa332c VA: 0x75965bb32c
	protected virtual Void OnDestroy() { }
	// RVA: 0x3fa3284 VA: 0x75965bb284
	protected Void _ResetControllerTween() { }
	// RVA: 0x3fa3394 VA: 0x75965bb394
	public override Vector3 CalculateCameraFocusPos(Vector3 targetPos) { }
	// RVA: 0x3fa22b0 VA: 0x75965ba2b0
	private Boolean _IsDragStateValid(out Vector2 screenPos) { }
	// RVA: 0x3fa3568 VA: 0x75965bb568
	protected virtual Boolean IsDragValidState() { }
	// RVA: 0x3fa18cc VA: 0x75965b98cc
	private List`1 _GetMapCorners() { }
	// RVA: 0x3fa3600 VA: 0x75965bb600
	private Boolean _IsCornerVertex(Int32 row, Int32 col) { }
	// RVA: 0x3fa374c VA: 0x75965bb74c
	public override Void DoAdaptCameraPosition() { }
	// RVA: 0x3fa37d0 VA: 0x75965bb7d0
	public Void .ctor() { }
	// RVA: 0x3fa39c0 VA: 0x75965bb9c0
	private Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3 P0) { }
	// RVA: 0x3fa39c4 VA: 0x75965bb9c4
	private Vector2 <>xLuaBaseProxy_get_audioVolumeSyncCameraPosRange() { }
	// RVA: 0x3fa39c8 VA: 0x75965bb9c8
	private Boolean <>xLuaBaseProxy_IsValidPut(Int32 P0) { }
	// RVA: 0x3fa39cc VA: 0x75965bb9cc
	private Void <>xLuaBaseProxy_PutDown(Transform P0) { }
	// RVA: 0x3fa39d0 VA: 0x75965bb9d0
	private Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3 P0) { }
	// RVA: 0x3fa39d4 VA: 0x75965bb9d4
	private Void <>xLuaBaseProxy_DoAdaptCameraPosition() { }
}
```