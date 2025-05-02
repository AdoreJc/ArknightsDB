# MobileTouchCamera

**Namespace:** `BitBenderGames`


## Fields

- `CameraPlaneAxes cameraAxes`

- `PerspectiveZoomMode perspectiveZoomMode`

- `Single camZoomMin`

- `Single camZoomMax`

- `Single camOverzoomMargin`

- `Single camOverdragMargin`

- `Vector2 boundaryMin`

- `Vector2 boundaryMax`

- `Single camFollowFactor`

- `AutoScrollDampMode autoScrollDampMode`

- `Single autoScrollDamp`

- `AnimationCurve autoScrollDampCurve`

- `Single groundLevelOffset`

- `Boolean enableRotation`

- `Boolean enableTilt`

- `Single tiltAngleMin`

- `Single tiltAngleMax`

- `Boolean enableZoomTilt`

- `Single zoomTiltAngleMin`

- `Single zoomTiltAngleMax`

- `UnityEventWithRaycastHit OnPickItem`

- `UnityEventWithRaycastHit2D OnPickItem2D`

- `UnityEventWithRaycastHit OnPickItemDoubleClick`

- `UnityEventWithRaycastHit2D OnPickItem2DDoubleClick`

- `AbstractTouchInputController touchInputController`

- `Vector3 dragStartCamPos`

- `Vector3 cameraScrollVelocity`

- `Single pinchStartCamZoomSize`

- `Vector3 pinchStartIntersectionCenter`

- `Vector3 pinchCenterCurrent`

- `Single pinchDistanceCurrent`

- `Single pinchAngleCurrent`

- `Single pinchDistanceStart`

- `Vector3 pinchCenterCurrentLerp`

- `Single pinchDistanceCurrentLerp`

- `Single pinchAngleCurrentLerp`

- `Boolean isRotationLock`

- `Boolean isRotationActivated`

- `Single pinchAngleLastFrame`

- `Single pinchTiltCurrent`

- `Single pinchTiltAccumulated`

- `Boolean isTiltModeEvaluated`

- `Single pinchTiltLastFrame`

- `Boolean isPinchTiltMode`

- `Single timeRealDragStop`

- `Boolean <IsPinching>k__BackingField`

- `Boolean <IsDragging>k__BackingField`

- `Boolean expertModeEnabled`

- `Single zoomBackSpringFactor`

- `Single dragBackSpringFactor`

- `Single autoScrollVelocityMax`

- `Single dampFactorTimeMultiplier`

- `Boolean isPinchModeExclusive`

- `Single customZoomSensitivity`

- `TerrainCollider terrainCollider`

- `Transform cameraTransform`

- `Single rotationDetectionDeltaThreshold`

- `Single rotationMinPinchDistance`

- `Single rotationLockThreshold`

- `Single pinchModeDetectionMoveTreshold`

- `Single pinchTiltModeThreshold`

- `Single pinchTiltSpeed`

- `Boolean isStarted`

- `Camera <Cam>k__BackingField`

- `Boolean isDraggingSceneObject`

- `Plane refPlaneXY`

- `Plane refPlaneXZ`

- `Vector3 targetPositionClamped`

- `Boolean <IsSmoothingEnabled>k__BackingField`

- `Single <ScreenRatio>k__BackingField`

- `Vector2 <CamPosMin>k__BackingField`

- `Vector2 <CamPosMax>k__BackingField`

- `Boolean <AllowDragOrPinch>k__BackingField`

- `ZoomUpdateDelegate OnZoomUpdate`

- `Boolean enableOvertiltSpring`

- `Single camOvertiltMargin`

- `Single tiltBackSpringFactor`

- `Single minOvertiltSpringPositionThreshold`


## Properties

- `CameraPlaneAxes CameraAxes`

- `Boolean IsAutoScrolling`

- `Boolean IsPinching`

- `Boolean IsDragging`

- `Boolean IsDraggingOrPinching`

- `Camera Cam`

- `Boolean IsTranslationZoom`

- `Single CamZoom`

- `Single CamZoomMin`

- `Single CamZoomMax`

- `Single CamOverzoomMargin`

- `Single CamOverdragMargin`

- `Single CamFollowFactor`

- `Single AutoScrollDamp`

- `AnimationCurve AutoScrollDampCurve`

- `Single GroundLevelOffset`

- `Vector2 BoundaryMin`

- `Vector2 BoundaryMax`

- `PerspectiveZoomMode PerspectiveZoomMode`

- `Boolean EnableRotation`

- `Boolean EnableTilt`

- `Single TiltAngleMin`

- `Single TiltAngleMax`

- `Boolean EnableZoomTilt`

- `Single ZoomTiltAngleMin`

- `Single ZoomTiltAngleMax`

- `Plane RefPlane`

- `Boolean IsSmoothingEnabled`

- `Single ScreenRatio`

- `Vector2 CamPosMin`

- `Vector2 CamPosMax`

- `TerrainCollider TerrainCollider`

- `Boolean AllowDragOrPinch`


## Methods

- `CameraPlaneAxes get_CameraAxes()`

- `Void set_CameraAxes(CameraPlaneAxes)`

- `Boolean get_IsAutoScrolling()`

- `Boolean get_IsPinching()`

- `Void set_IsPinching(Boolean)`

- `Boolean get_IsDragging()`

- `Void set_IsDragging(Boolean)`

- `Boolean get_IsDraggingOrPinching()`

- `Camera get_Cam()`

- `Void set_Cam(Camera)`

- `Boolean get_IsTranslationZoom()`

- `Single get_CamZoom()`

- `Void set_CamZoom(Single)`

- `Single get_CamZoomMin()`

- `Void set_CamZoomMin(Single)`

- `Single get_CamZoomMax()`

- `Void set_CamZoomMax(Single)`

- `Single get_CamOverzoomMargin()`

- `Void set_CamOverzoomMargin(Single)`

- `Single get_CamOverdragMargin()`

- `Void set_CamOverdragMargin(Single)`

- `Single get_CamFollowFactor()`

- `Void set_CamFollowFactor(Single)`

- `Single get_AutoScrollDamp()`

- `Void set_AutoScrollDamp(Single)`

- `AnimationCurve get_AutoScrollDampCurve()`

- `Void set_AutoScrollDampCurve(AnimationCurve)`

- `Single get_GroundLevelOffset()`

- `Void set_GroundLevelOffset(Single)`

- `Vector2 get_BoundaryMin()`

- `Void set_BoundaryMin(Vector2)`

- `Vector2 get_BoundaryMax()`

- `Void set_BoundaryMax(Vector2)`

- `PerspectiveZoomMode get_PerspectiveZoomMode()`

- `Void set_PerspectiveZoomMode(PerspectiveZoomMode)`

- `Boolean get_EnableRotation()`

- `Void set_EnableRotation(Boolean)`

- `Boolean get_EnableTilt()`

- `Void set_EnableTilt(Boolean)`

- `Single get_TiltAngleMin()`

- `Void set_TiltAngleMin(Single)`

- `Single get_TiltAngleMax()`

- `Void set_TiltAngleMax(Single)`

- `Boolean get_EnableZoomTilt()`

- `Void set_EnableZoomTilt(Boolean)`

- `Single get_ZoomTiltAngleMin()`

- `Void set_ZoomTiltAngleMin(Single)`

- `Single get_ZoomTiltAngleMax()`

- `Void set_ZoomTiltAngleMax(Single)`

- `Plane get_RefPlane()`

- `Void set_DragCameraMoveVector(List`1)`

- `Boolean get_IsSmoothingEnabled()`

- `Void set_IsSmoothingEnabled(Boolean)`

- `Single get_ScreenRatio()`

- `Void set_ScreenRatio(Single)`

- `Vector2 get_CamPosMin()`

- `Void set_CamPosMin(Vector2)`

- `Vector2 get_CamPosMax()`

- `Void set_CamPosMax(Vector2)`

- `TerrainCollider get_TerrainCollider()`

- `Void set_TerrainCollider(TerrainCollider)`

- `Boolean get_AllowDragOrPinch()`

- `Void set_AllowDragOrPinch(Boolean)`

- `Void add_OnZoomUpdate(ZoomUpdateDelegate)`

- `Void remove_OnZoomUpdate(ZoomUpdateDelegate)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void ResetCameraBoundaries()`

- `Void ResetZoomTilt()`

- `Vector3 GetFinger0PosWorld()`

- `Boolean RaycastGround(Ray, out)`

- `Vector3 GetIntersectionPoint(Ray)`

- `Vector3 GetIntersectionPointUnsafe(Ray)`

- `Boolean GetIsBoundaryPosition(Vector3)`

- `Vector3 GetClampToBoundaries(Vector3, Boolean)`

- `Void OnDragSceneObject()`

- `String CheckCameraAxesErrors()`

- `Vector3 UnprojectVector2(Vector2, Single)`

- `Vector2 ProjectVector3(Vector3)`

- `IEnumerator InitCamBoundariesDelayed()`

- `Void Reset()`

- `Void UpdatePinch(Single)`

- `Void UpdateTiltForAutoTilt(Single)`

- `Void DoPositionUpdateForTilt(Boolean)`

- `Single ComputeOvertiltSpringBackFactor(Single)`

- `Void UpdateCameraTilt(Single)`

- `Void ClampCameraTilt(Vector3, Vector3)`

- `Single GetCurrentTiltAngleDeg(Vector3)`

- `Vector3 GetRotationAxis()`

- `Single GetRotationDeg()`

- `Vector3 GetTiltRotationAxis()`

- `Void UpdatePosition(Single)`

- `Vector3 ComputeOverdragSpringBackVector(Vector3, Single, ref)`

- `Void SetTargetPosition(Vector3)`

- `Vector2 RotateVector2(Vector2, Single)`

- `Void ComputeCamBoundaries()`

- `Void RotateBoundingBox(Vector2, Vector2, Single, out, out)`

- `Vector2 GetIntersection2d(Ray)`

- `Vector2 GetVector2Min(Vector2, Vector2, Vector2, Vector2)`

- `Vector2 GetVector2Max(Vector2, Vector2, Vector2, Vector2)`

- `Void LateUpdate()`

- `Single DoEditorCameraZoom(Single)`

- `Void FixedUpdate()`

- `Single EvaluateAutoScrollDampCurve(Single)`

- `Void InputControllerOnFingerDown(Vector3)`

- `Void InputControllerOnFingerUp()`

- `Vector3 GetDragVector(Vector3, Vector3)`

- `Vector3 GetVelocityFromMoveHistory()`

- `Void InputControllerOnDragStart(Vector3, Boolean)`

- `Void InputControllerOnDragUpdate(Vector3, Vector3, Vector3)`

- `Void InputControllerOnDragStop(Vector3, Vector3)`

- `Void InputControllerOnPinchStart(Vector3, Single)`

- `Void InputControllerOnPinchUpdate(PinchUpdateData)`

- `Void ResetPinchRotation(Single)`

- `Void InputControllerOnPinchStop()`

- `Void InputControllerOnInputClick(Vector3, Boolean, Boolean)`

- `Single GetScreenRatio()`

- `IEnumerator ZoomToTargetValueCoroutine(Single)`

- `Ray GetCamCenterRay()`

- `Void OnDrawGizmosSelected()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class MobileTouchCamera : MonoBehaviourWrapped
{
	private CameraPlaneAxes cameraAxes; // 0x28
	private PerspectiveZoomMode perspectiveZoomMode; // 0x2c
	private Single camZoomMin; // 0x30
	private Single camZoomMax; // 0x34
	private Single camOverzoomMargin; // 0x38
	private Single camOverdragMargin; // 0x3c
	private Vector2 boundaryMin; // 0x40
	private Vector2 boundaryMax; // 0x48
	private Single camFollowFactor; // 0x50
	private AutoScrollDampMode autoScrollDampMode; // 0x54
	private Single autoScrollDamp; // 0x58
	private AnimationCurve autoScrollDampCurve; // 0x60
	private Single groundLevelOffset; // 0x68
	private Boolean enableRotation; // 0x6c
	private Boolean enableTilt; // 0x6d
	private Single tiltAngleMin; // 0x70
	private Single tiltAngleMax; // 0x74
	private Boolean enableZoomTilt; // 0x78
	private Single zoomTiltAngleMin; // 0x7c
	private Single zoomTiltAngleMax; // 0x80
	private UnityEventWithRaycastHit OnPickItem; // 0x88
	private UnityEventWithRaycastHit2D OnPickItem2D; // 0x90
	private UnityEventWithRaycastHit OnPickItemDoubleClick; // 0x98
	private UnityEventWithRaycastHit2D OnPickItem2DDoubleClick; // 0xa0
	private AbstractTouchInputController touchInputController; // 0xa8
	private Vector3 dragStartCamPos; // 0xb0
	private Vector3 cameraScrollVelocity; // 0xbc
	private Single pinchStartCamZoomSize; // 0xc8
	private Vector3 pinchStartIntersectionCenter; // 0xcc
	private Vector3 pinchCenterCurrent; // 0xd8
	private Single pinchDistanceCurrent; // 0xe4
	private Single pinchAngleCurrent; // 0xe8
	private Single pinchDistanceStart; // 0xec
	private Vector3 pinchCenterCurrentLerp; // 0xf0
	private Single pinchDistanceCurrentLerp; // 0xfc
	private Single pinchAngleCurrentLerp; // 0x100
	private Boolean isRotationLock; // 0x104
	private Boolean isRotationActivated; // 0x105
	private Single pinchAngleLastFrame; // 0x108
	private Single pinchTiltCurrent; // 0x10c
	private Single pinchTiltAccumulated; // 0x110
	private Boolean isTiltModeEvaluated; // 0x114
	private Single pinchTiltLastFrame; // 0x118
	private Boolean isPinchTiltMode; // 0x11c
	private Single timeRealDragStop; // 0x120
	private Boolean <IsPinching>k__BackingField; // 0x124
	private Boolean <IsDragging>k__BackingField; // 0x125
	private Boolean expertModeEnabled; // 0x126
	private Single zoomBackSpringFactor; // 0x128
	private Single dragBackSpringFactor; // 0x12c
	private Single autoScrollVelocityMax; // 0x130
	private Single dampFactorTimeMultiplier; // 0x134
	private Boolean isPinchModeExclusive; // 0x138
	private Single customZoomSensitivity; // 0x13c
	private TerrainCollider terrainCollider; // 0x140
	private Transform cameraTransform; // 0x148
	private Single rotationDetectionDeltaThreshold; // 0x150
	private Single rotationMinPinchDistance; // 0x154
	private Single rotationLockThreshold; // 0x158
	private Single pinchModeDetectionMoveTreshold; // 0x15c
	private Single pinchTiltModeThreshold; // 0x160
	private Single pinchTiltSpeed; // 0x164
	private Boolean isStarted; // 0x168
	private Camera <Cam>k__BackingField; // 0x170
	private Boolean isDraggingSceneObject; // 0x178
	private Plane refPlaneXY; // 0x17c
	private Plane refPlaneXZ; // 0x18c
	private List`1 <DragCameraMoveVector>k__BackingField; // 0x1a0
	private const Int32 momentumSamplesCount; // 0x0
	private const Single pinchDistanceForTiltBreakout; // 0x0
	private const Single pinchAccumBreakout; // 0x0
	private Vector3 targetPositionClamped; // 0x1a8
	private Boolean <IsSmoothingEnabled>k__BackingField; // 0x1b4
	private Single <ScreenRatio>k__BackingField; // 0x1b8
	private Vector2 <CamPosMin>k__BackingField; // 0x1bc
	private Vector2 <CamPosMax>k__BackingField; // 0x1c4
	private Boolean <AllowDragOrPinch>k__BackingField; // 0x1cc
	private ZoomUpdateDelegate OnZoomUpdate; // 0x1d0
	private Boolean enableOvertiltSpring; // 0x1d8
	private Single camOvertiltMargin; // 0x1dc
	private Single tiltBackSpringFactor; // 0x1e0
	private Single minOvertiltSpringPositionThreshold; // 0x1e4

	public CameraPlaneAxes CameraAxes { get; set; }
	public Boolean IsAutoScrolling { get; }
	public Boolean IsPinching { get; set; }
	public Boolean IsDragging { get; set; }
	public Boolean IsDraggingOrPinching { get; }
	public Camera Cam { get; set; }
	private Boolean IsTranslationZoom { get; }
	public Single CamZoom { get; set; }
	public Single CamZoomMin { get; set; }
	public Single CamZoomMax { get; set; }
	public Single CamOverzoomMargin { get; set; }
	public Single CamOverdragMargin { get; set; }
	public Single CamFollowFactor { get; set; }
	public Single AutoScrollDamp { get; set; }
	public AnimationCurve AutoScrollDampCurve { get; set; }
	public Single GroundLevelOffset { get; set; }
	public Vector2 BoundaryMin { get; set; }
	public Vector2 BoundaryMax { get; set; }
	public PerspectiveZoomMode PerspectiveZoomMode { get; set; }
	public Boolean EnableRotation { get; set; }
	public Boolean EnableTilt { get; set; }
	public Single TiltAngleMin { get; set; }
	public Single TiltAngleMax { get; set; }
	public Boolean EnableZoomTilt { get; set; }
	public Single ZoomTiltAngleMin { get; set; }
	public Single ZoomTiltAngleMax { get; set; }
	public Plane RefPlane { get; }
	private List`1 DragCameraMoveVector { get; set; }
	public Boolean IsSmoothingEnabled { get; set; }
	private Single ScreenRatio { get; set; }
	public Vector2 CamPosMin { get; set; }
	public Vector2 CamPosMax { get; set; }
	public TerrainCollider TerrainCollider { get; set; }
	public Boolean AllowDragOrPinch { get; set; }

	// RVA: 0x2c25854 VA: 0x759523d854
	public CameraPlaneAxes get_CameraAxes() { }
	// RVA: 0x2c2585c VA: 0x759523d85c
	public Void set_CameraAxes(CameraPlaneAxes value) { }
	// RVA: 0x2c25864 VA: 0x759523d864
	public Boolean get_IsAutoScrolling() { }
	// RVA: 0x2c25894 VA: 0x759523d894
	public Boolean get_IsPinching() { }
	// RVA: 0x2c2589c VA: 0x759523d89c
	private Void set_IsPinching(Boolean value) { }
	// RVA: 0x2c258a8 VA: 0x759523d8a8
	public Boolean get_IsDragging() { }
	// RVA: 0x2c258b0 VA: 0x759523d8b0
	private Void set_IsDragging(Boolean value) { }
	// RVA: 0x2c258bc VA: 0x759523d8bc
	public Boolean get_IsDraggingOrPinching() { }
	// RVA: 0x2c258ec VA: 0x759523d8ec
	public Camera get_Cam() { }
	// RVA: 0x2c258f4 VA: 0x759523d8f4
	private Void set_Cam(Camera value) { }
	// RVA: 0x2c25904 VA: 0x759523d904
	private Boolean get_IsTranslationZoom() { }
	// RVA: 0x2c25940 VA: 0x759523d940
	public Single get_CamZoom() { }
	// RVA: 0x2c20af4 VA: 0x7595238af4
	public Void set_CamZoom(Single value) { }
	// RVA: 0x2c26044 VA: 0x759523e044
	public Single get_CamZoomMin() { }
	// RVA: 0x2c2604c VA: 0x759523e04c
	public Void set_CamZoomMin(Single value) { }
	// RVA: 0x2c26054 VA: 0x759523e054
	public Single get_CamZoomMax() { }
	// RVA: 0x2c2605c VA: 0x759523e05c
	public Void set_CamZoomMax(Single value) { }
	// RVA: 0x2c26064 VA: 0x759523e064
	public Single get_CamOverzoomMargin() { }
	// RVA: 0x2c2606c VA: 0x759523e06c
	public Void set_CamOverzoomMargin(Single value) { }
	// RVA: 0x2c26074 VA: 0x759523e074
	public Single get_CamOverdragMargin() { }
	// RVA: 0x2c2607c VA: 0x759523e07c
	public Void set_CamOverdragMargin(Single value) { }
	// RVA: 0x2c26084 VA: 0x759523e084
	public Single get_CamFollowFactor() { }
	// RVA: 0x2c2608c VA: 0x759523e08c
	public Void set_CamFollowFactor(Single value) { }
	// RVA: 0x2c26094 VA: 0x759523e094
	public Single get_AutoScrollDamp() { }
	// RVA: 0x2c2609c VA: 0x759523e09c
	public Void set_AutoScrollDamp(Single value) { }
	// RVA: 0x2c260a4 VA: 0x759523e0a4
	public AnimationCurve get_AutoScrollDampCurve() { }
	// RVA: 0x2c260ac VA: 0x759523e0ac
	public Void set_AutoScrollDampCurve(AnimationCurve value) { }
	// RVA: 0x2c260b4 VA: 0x759523e0b4
	public Single get_GroundLevelOffset() { }
	// RVA: 0x2c260bc VA: 0x759523e0bc
	public Void set_GroundLevelOffset(Single value) { }
	// RVA: 0x2c260c4 VA: 0x759523e0c4
	public Vector2 get_BoundaryMin() { }
	// RVA: 0x2c260cc VA: 0x759523e0cc
	public Void set_BoundaryMin(Vector2 value) { }
	// RVA: 0x2c260d4 VA: 0x759523e0d4
	public Vector2 get_BoundaryMax() { }
	// RVA: 0x2c260dc VA: 0x759523e0dc
	public Void set_BoundaryMax(Vector2 value) { }
	// RVA: 0x2c260e4 VA: 0x759523e0e4
	public PerspectiveZoomMode get_PerspectiveZoomMode() { }
	// RVA: 0x2c260ec VA: 0x759523e0ec
	public Void set_PerspectiveZoomMode(PerspectiveZoomMode value) { }
	// RVA: 0x2c260f4 VA: 0x759523e0f4
	public Boolean get_EnableRotation() { }
	// RVA: 0x2c260fc VA: 0x759523e0fc
	public Void set_EnableRotation(Boolean value) { }
	// RVA: 0x2c26108 VA: 0x759523e108
	public Boolean get_EnableTilt() { }
	// RVA: 0x2c26110 VA: 0x759523e110
	public Void set_EnableTilt(Boolean value) { }
	// RVA: 0x2c2611c VA: 0x759523e11c
	public Single get_TiltAngleMin() { }
	// RVA: 0x2c26124 VA: 0x759523e124
	public Void set_TiltAngleMin(Single value) { }
	// RVA: 0x2c2612c VA: 0x759523e12c
	public Single get_TiltAngleMax() { }
	// RVA: 0x2c26134 VA: 0x759523e134
	public Void set_TiltAngleMax(Single value) { }
	// RVA: 0x2c2613c VA: 0x759523e13c
	public Boolean get_EnableZoomTilt() { }
	// RVA: 0x2c26144 VA: 0x759523e144
	public Void set_EnableZoomTilt(Boolean value) { }
	// RVA: 0x2c26150 VA: 0x759523e150
	public Single get_ZoomTiltAngleMin() { }
	// RVA: 0x2c26158 VA: 0x759523e158
	public Void set_ZoomTiltAngleMin(Single value) { }
	// RVA: 0x2c26160 VA: 0x759523e160
	public Single get_ZoomTiltAngleMax() { }
	// RVA: 0x2c26168 VA: 0x759523e168
	public Void set_ZoomTiltAngleMax(Single value) { }
	// RVA: 0x2c24860 VA: 0x759523c860
	public Plane get_RefPlane() { }
	// RVA: 0x2c26170 VA: 0x759523e170
	private List`1 get_DragCameraMoveVector() { }
	// RVA: 0x2c26178 VA: 0x759523e178
	private Void set_DragCameraMoveVector(List`1 value) { }
	// RVA: 0x2c26188 VA: 0x759523e188
	public Boolean get_IsSmoothingEnabled() { }
	// RVA: 0x2c26190 VA: 0x759523e190
	public Void set_IsSmoothingEnabled(Boolean value) { }
	// RVA: 0x2c2619c VA: 0x759523e19c
	private Single get_ScreenRatio() { }
	// RVA: 0x2c261a4 VA: 0x759523e1a4
	private Void set_ScreenRatio(Single value) { }
	// RVA: 0x2c261ac VA: 0x759523e1ac
	public Vector2 get_CamPosMin() { }
	// RVA: 0x2c261b8 VA: 0x759523e1b8
	public Void set_CamPosMin(Vector2 value) { }
	// RVA: 0x2c261c4 VA: 0x759523e1c4
	public Vector2 get_CamPosMax() { }
	// RVA: 0x2c261d0 VA: 0x759523e1d0
	public Void set_CamPosMax(Vector2 value) { }
	// RVA: 0x2c261dc VA: 0x759523e1dc
	public TerrainCollider get_TerrainCollider() { }
	// RVA: 0x2c261e4 VA: 0x759523e1e4
	public Void set_TerrainCollider(TerrainCollider value) { }
	// RVA: 0x2c261f4 VA: 0x759523e1f4
	public Boolean get_AllowDragOrPinch() { }
	// RVA: 0x2c261fc VA: 0x759523e1fc
	public Void set_AllowDragOrPinch(Boolean value) { }
	// RVA: 0x2c26208 VA: 0x759523e208
	public Void add_OnZoomUpdate(ZoomUpdateDelegate value) { }
	// RVA: 0x2c262a8 VA: 0x759523e2a8
	public Void remove_OnZoomUpdate(ZoomUpdateDelegate value) { }
	// RVA: 0x2c26348 VA: 0x759523e348
	public Void Awake() { }
	// RVA: 0x2c269f0 VA: 0x759523e9f0
	public Void Start() { }
	// RVA: 0x2c27034 VA: 0x759523f034
	public Void OnDestroy() { }
	// RVA: 0x2c20e1c VA: 0x7595238e1c
	public Void ResetCameraBoundaries() { }
	// RVA: 0x2c26828 VA: 0x759523e828
	public Void ResetZoomTilt() { }
	// RVA: 0x2c245ec VA: 0x759523c5ec
	public Vector3 GetFinger0PosWorld() { }
	// RVA: 0x2c23eac VA: 0x759523beac
	public Boolean RaycastGround(Ray ray, out Vector3 hitPoint) { }
	// RVA: 0x2c25af4 VA: 0x759523daf4
	public Vector3 GetIntersectionPoint(Ray ray) { }
	// RVA: 0x2c27664 VA: 0x759523f664
	public Vector3 GetIntersectionPointUnsafe(Ray ray) { }
	// RVA: 0x2c2786c VA: 0x759523f86c
	public Boolean GetIsBoundaryPosition(Vector3 testPosition) { }
	// RVA: 0x2c278c8 VA: 0x759523f8c8
	public Vector3 GetClampToBoundaries(Vector3 newPosition, Boolean includeSpringBackMargin) { }
	// RVA: 0x2c24854 VA: 0x759523c854
	public Void OnDragSceneObject() { }
	// RVA: 0x2c26840 VA: 0x759523e840
	public String CheckCameraAxesErrors() { }
	// RVA: 0x2c2797c VA: 0x759523f97c
	public Vector3 UnprojectVector2(Vector2 v2, Single offset) { }
	// RVA: 0x2c27994 VA: 0x759523f994
	public Vector2 ProjectVector3(Vector3 v3) { }
	// RVA: 0x2c26fc0 VA: 0x759523efc0
	private IEnumerator InitCamBoundariesDelayed() { }
	// RVA: 0x2c279cc VA: 0x759523f9cc
	private Void Reset() { }
	// RVA: 0x2c27c10 VA: 0x759523fc10
	private Void UpdatePinch(Single deltaTime) { }
	// RVA: 0x2c27600 VA: 0x759523f600
	private Void UpdateTiltForAutoTilt(Single newCameraSize) { }
	// RVA: 0x2c28040 VA: 0x7595240040
	private Void DoPositionUpdateForTilt(Boolean isSpringBack) { }
	// RVA: 0x2c28194 VA: 0x7595240194
	private Single ComputeOvertiltSpringBackFactor(Single margin) { }
	// RVA: 0x2c27ea4 VA: 0x759523fea4
	private Void UpdateCameraTilt(Single angle) { }
	// RVA: 0x2c283b0 VA: 0x75952403b0
	private Void ClampCameraTilt(Vector3 rotationPoint, Vector3 rotationAxis) { }
	// RVA: 0x2c281f0 VA: 0x75952401f0
	private Single GetCurrentTiltAngleDeg(Vector3 rotationAxis) { }
	// RVA: 0x2c27fd4 VA: 0x759523ffd4
	private Vector3 GetRotationAxis() { }
	// RVA: 0x2c2846c VA: 0x759524046c
	private Single GetRotationDeg() { }
	// RVA: 0x2c27bf4 VA: 0x759523fbf4
	private Vector3 GetTiltRotationAxis() { }
	// RVA: 0x2c284bc VA: 0x75952404bc
	private Void UpdatePosition(Single deltaTime) { }
	// RVA: 0x2c28870 VA: 0x7595240870
	private Vector3 ComputeOverdragSpringBackVector(Vector3 camPos, Single margin, ref Vector3 currentCamScrollVelocity) { }
	// RVA: 0x2c28974 VA: 0x7595240974
	private Void SetTargetPosition(Vector3 newPositionClamped) { }
	// RVA: 0x2c28984 VA: 0x7595240984
	private Vector2 RotateVector2(Vector2 v, Single degrees) { }
	// RVA: 0x2c25c38 VA: 0x759523dc38
	private Void ComputeCamBoundaries() { }
	// RVA: 0x2c28e44 VA: 0x7595240e44
	private Void RotateBoundingBox(Vector2 min, Vector2 max, Single rotationDegrees, out Vector2 resultMin, out Vector2 resultMax) { }
	// RVA: 0x2c28abc VA: 0x7595240abc
	private Vector2 GetIntersection2d(Ray ray) { }
	// RVA: 0x2c28b5c VA: 0x7595240b5c
	private Vector2 GetVector2Min(Vector2 v0, Vector2 v1, Vector2 v2, Vector2 v3) { }
	// RVA: 0x2c28cd0 VA: 0x7595240cd0
	private Vector2 GetVector2Max(Vector2 v0, Vector2 v1, Vector2 v2, Vector2 v3) { }
	// RVA: 0x2c29114 VA: 0x7595241114
	public Void LateUpdate() { }
	// RVA: 0x2c2927c VA: 0x759524127c
	private Single DoEditorCameraZoom(Single amount) { }
	// RVA: 0x2c292e4 VA: 0x75952412e4
	public Void FixedUpdate() { }
	// RVA: 0x2c29578 VA: 0x7595241578
	private Single EvaluateAutoScrollDampCurve(Single t) { }
	// RVA: 0x2c295cc VA: 0x75952415cc
	private Void InputControllerOnFingerDown(Vector3 pos) { }
	// RVA: 0x2c29624 VA: 0x7595241624
	private Void InputControllerOnFingerUp() { }
	// RVA: 0x2c2962c VA: 0x759524162c
	private Vector3 GetDragVector(Vector3 dragPosStart, Vector3 dragPosCurrent) { }
	// RVA: 0x2c296f0 VA: 0x75952416f0
	private Vector3 GetVelocityFromMoveHistory() { }
	// RVA: 0x2c297f8 VA: 0x75952417f8
	private Void InputControllerOnDragStart(Vector3 dragPosStart, Boolean isLongTap) { }
	// RVA: 0x2c298d4 VA: 0x75952418d4
	private Void InputControllerOnDragUpdate(Vector3 dragPosStart, Vector3 dragPosCurrent, Vector3 correctionOffset) { }
	// RVA: 0x2c2993c VA: 0x759524193c
	private Void InputControllerOnDragStop(Vector3 dragStopPos, Vector3 dragFinalMomentum) { }
	// RVA: 0x2c29aa8 VA: 0x7595241aa8
	private Void InputControllerOnPinchStart(Vector3 pinchCenter, Single pinchDistance) { }
	// RVA: 0x2c29bb4 VA: 0x7595241bb4
	private Void InputControllerOnPinchUpdate(PinchUpdateData pinchUpdateData) { }
	// RVA: 0x2c29b9c VA: 0x7595241b9c
	private Void ResetPinchRotation(Single currentPinchRotation) { }
	// RVA: 0x2c29d70 VA: 0x7595241d70
	private Void InputControllerOnPinchStop() { }
	// RVA: 0x2c29dcc VA: 0x7595241dcc
	private Void InputControllerOnInputClick(Vector3 clickPosition, Boolean isDoubleClick, Boolean isLongTap) { }
	// RVA: 0x2c267fc VA: 0x759523e7fc
	private Single GetScreenRatio() { }
	// RVA: 0x2c2a020 VA: 0x7595242020
	private IEnumerator ZoomToTargetValueCoroutine(Single target) { }
	// RVA: 0x2c25a7c VA: 0x759523da7c
	private Ray GetCamCenterRay() { }
	// RVA: 0x2c2a0cc VA: 0x75952420cc
	public Void OnDrawGizmosSelected() { }
	// RVA: 0x2c2a144 VA: 0x7595242144
	public Void .ctor() { }
}
```