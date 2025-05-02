# CameraController

**Namespace:** `Torappu.Battle`


## Fields

- `Camera _camera`

- `Camera _fakeCamera`

- `Camera _uiPerspectiveCamera`

- `Transform _offset`

- `Single _moveTime`

- `Ease _easeType`

- `Vector2 _fromResolution`

- `Vector2 _toResolution`

- `Vector3 _fromLocalPosition`

- `Vector3 _toLocalPosition`

- `MapLayer m_originalLayer`

- `PostProcessLayer m_postProcessLayer`

- `AntialiasingProfile m_aaProfile`

- `Boolean m_cameraMoveDirectlyDisableState`

- `MapLayer <currentLayer>k__BackingField`

- `Vector3 m_originPos`

- `CameraPosition m_cameraPosition`

- `Tween m_moveTween`

- `Tween m_scaleTween`

- `Int32 m_isTweening`

- `Int32 m_isPerspectiveCameraOn`

- `Plugin <plugin>k__BackingField`

- `Vector3 m_cacheCameraPos`

- `Quaternion m_cacheCameraRotation`

- `Single m_cacheFov`


## Properties

- `Boolean hasPPLayer`

- `MapLayer currentLayer`

- `Vector3 originPos`

- `MapLayer nextLayer`

- `Boolean isTweening`

- `Boolean isMoving`

- `Boolean isScaling`

- `CameraPosition cameraPosition`

- `Camera camera`

- `Camera uiPerspectiveCamera`

- `Plugin plugin`

- `Vector3 cameraOffset`

- `Transform offsetTransform`


## Methods

- `Boolean get_hasPPLayer()`

- `MapLayer get_currentLayer()`

- `Void set_currentLayer(MapLayer)`

- `Vector3 get_originPos()`

- `Void set_originPos(Vector3)`

- `MapLayer get_nextLayer()`

- `Boolean get_isTweening()`

- `Boolean get_isMoving()`

- `Boolean get_isScaling()`

- `CameraPosition get_cameraPosition()`

- `Camera get_camera()`

- `Camera get_uiPerspectiveCamera()`

- `Plugin get_plugin()`

- `Void set_plugin(Plugin)`

- `Vector3 get_cameraOffset()`

- `Transform get_offsetTransform()`

- `Void ResetAll(Boolean)`

- `Void SetCameraMoveDirectlyDisableState(Boolean)`

- `Void SetPerspectiveCameraOn(PerpectiveCameraMask, Boolean)`

- `Void _SetPerspectiveCameraImp()`

- `Void SetCameraPosition(CameraPosition, Boolean)`

- `Void MoveCameraDirectly(Vector3, Boolean)`

- `Void SetCameraDefaultView(CameraViewLevel)`

- `Void SetCameraDefaultView(Vector3)`

- `Void InitCameraDefaultView()`

- `Void ResetCameraPosition(Boolean)`

- `Void ShakeCamera(Single, Vector3, Int32, Single)`

- `Void PutDown(Transform)`

- `Void ResetFocus(Boolean)`

- `Void Focus(Transform, Boolean)`

- `Void Focus(Transform, Single, Boolean)`

- `Void Focus(Vector3, Single, Single, Boolean, Ease, Ease)`

- `Void ScaleOn(Single, Single, Ease, Boolean)`

- `Void ResetFocusAndScale(Single, Ease, Ease)`

- `Void _FocusInternal(Vector3, Boolean)`

- `Void _FocusInternal(Vector3, Single, Single, Boolean, Ease, Ease)`

- `Boolean IsValidPut(Int32)`

- `Void FaceToCamera(Transform)`

- `Void FaceToCameraOnlyX(Transform)`

- `Vector2 WorldToViewportDirectionV2(Vector3, Vector2)`

- `Void _DoAdaptCameraPosition()`

- `Void _DoAdaptDefaultCameraPosition()`

- `Vector3 GetCameraPos()`

- `Single GetCameraScale()`

- `Single GetCameraHeight()`

- `Void UpdateCameraControllerPos(Vector3)`

- `Void UpdateCameraControllerScale(Single)`

- `Void ParseCameraBasic(Blackboard)`

- `Void DoSetCameraStartPos(Vector2)`

- `Boolean UpdateLayerCameraOrigins(PlayerSide)`

- `Void UpdateAudioListener()`

- `Void FinishTweenIfNot()`

- `Void _TryCreatePlugin()`

- `Void _TryCreatePluginByActivity()`

- `Void _UpdateTransparencySortMode()`

- `Void ReplaceCamera(Camera)`

- `Void Start()`

- `Void Update()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void _InitPostProcessLayer()`

- `Void InitPostProcessAA()`

- `Void SetSMAA(Quality)`

- `Void _UpdateFrustumPlanesIfNeeded()`

- `Boolean IsVisible(Vector3, Single)`

- `Void <_FocusInternal>b__79_0()`

- `Void <_FocusInternal>b__79_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CameraController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ISafeAreaListener, IHotfixable
{
	private const String PERSPECTIVE_UI_CAMERA_NAME; // 0x0
	private const Ease EASE_TYPE_SCALE; // 0x0
	private Camera _camera; // 0x18
	private Camera _fakeCamera; // 0x20
	private Camera _uiPerspectiveCamera; // 0x28
	private Transform _offset; // 0x30
	private Single _moveTime; // 0x38
	private Ease _easeType; // 0x3c
	private Transform[] _placeholders; // 0x40
	private Vector2 _fromResolution; // 0x48
	private Vector2 _toResolution; // 0x50
	private Vector3 _fromLocalPosition; // 0x58
	private Vector3 _toLocalPosition; // 0x64
	private MapLayer m_originalLayer; // 0x70
	private PostProcessLayer m_postProcessLayer; // 0x78
	private AntialiasingProfile m_aaProfile; // 0x80
	private Boolean m_cameraMoveDirectlyDisableState; // 0x88
	private MapLayer <currentLayer>k__BackingField; // 0x8c
	private readonly List`1 m_layerOrigins; // 0x90
	private Vector3 m_originPos; // 0x98
	private Nullable`1 m_overrideScale; // 0xa4
	private CameraPosition m_cameraPosition; // 0xac
	private Tween m_moveTween; // 0xb0
	private Tween m_scaleTween; // 0xb8
	private Int32 m_isTweening; // 0xc0
	private Int32 m_isPerspectiveCameraOn; // 0xc4
	private Plugin <plugin>k__BackingField; // 0xc8
	private Plane[] m_planes; // 0xd0
	private Vector3 m_cacheCameraPos; // 0xd8
	private Quaternion m_cacheCameraRotation; // 0xe4
	private Single m_cacheFov; // 0xf4
	private static DelegateBridge __Hotfix0_get_hasPPLayer; // 0x0
	private static DelegateBridge __Hotfix0_get_currentLayer; // 0x8
	private static DelegateBridge __Hotfix0_set_currentLayer; // 0x10
	private static DelegateBridge __Hotfix0_get_originPos; // 0x18
	private static DelegateBridge __Hotfix0_set_originPos; // 0x20
	private static DelegateBridge __Hotfix0_get_nextLayer; // 0x28
	private static DelegateBridge __Hotfix0_get_isTweening; // 0x30
	private static DelegateBridge __Hotfix0_get_isMoving; // 0x38
	private static DelegateBridge __Hotfix0_get_isScaling; // 0x40
	private static DelegateBridge __Hotfix0_get_cameraPosition; // 0x48
	private static DelegateBridge __Hotfix0_get_camera; // 0x50
	private static DelegateBridge __Hotfix0_get_uiPerspectiveCamera; // 0x58
	private static DelegateBridge __Hotfix0_get_plugin; // 0x60
	private static DelegateBridge __Hotfix0_set_plugin; // 0x68
	private static DelegateBridge __Hotfix0_get_cameraOffset; // 0x70
	private static DelegateBridge __Hotfix0_get_offsetTransform; // 0x78
	private static DelegateBridge __Hotfix0_ResetAll; // 0x80
	private static DelegateBridge __Hotfix0_SetCameraMoveDirectlyDisableState; // 0x88
	private static DelegateBridge __Hotfix0_SetPerspectiveCameraOn; // 0x90
	private static DelegateBridge __Hotfix0__SetPerspectiveCameraImp; // 0x98
	private static DelegateBridge __Hotfix0_SetCameraPosition; // 0xa0
	private static DelegateBridge __Hotfix0_MoveCameraDirectly; // 0xa8
	private static DelegateBridge __Hotfix0_SetCameraDefaultView; // 0xb0
	private static DelegateBridge __Hotfix1_SetCameraDefaultView; // 0xb8
	private static DelegateBridge __Hotfix0_InitCameraDefaultView; // 0xc0
	private static DelegateBridge __Hotfix0_ResetCameraPosition; // 0xc8
	private static DelegateBridge __Hotfix0_ShakeCamera; // 0xd0
	private static DelegateBridge __Hotfix0_PutDown; // 0xd8
	private static DelegateBridge __Hotfix0_ResetFocus; // 0xe0
	private static DelegateBridge __Hotfix0_Focus; // 0xe8
	private static DelegateBridge __Hotfix1_Focus; // 0xf0
	private static DelegateBridge __Hotfix2_Focus; // 0xf8
	private static DelegateBridge __Hotfix0_ScaleOn; // 0x100
	private static DelegateBridge __Hotfix0_ResetFocusAndScale; // 0x108
	private static DelegateBridge __Hotfix0__FocusInternal; // 0x110
	private static DelegateBridge __Hotfix1__FocusInternal; // 0x118
	private static DelegateBridge __Hotfix0_IsValidPut; // 0x120
	private static DelegateBridge __Hotfix0_FaceToCamera; // 0x128
	private static DelegateBridge __Hotfix0_FaceToCameraOnlyX; // 0x130
	private static DelegateBridge __Hotfix0_WorldToViewportDirectionV2; // 0x138
	private static DelegateBridge __Hotfix0__DoAdaptCameraPosition; // 0x140
	private static DelegateBridge __Hotfix0__DoAdaptDefaultCameraPosition; // 0x148
	private static DelegateBridge __Hotfix0_GetCameraPos; // 0x150
	private static DelegateBridge __Hotfix0_GetCameraScale; // 0x158
	private static DelegateBridge __Hotfix0_GetCameraHeight; // 0x160
	private static DelegateBridge __Hotfix0_UpdateCameraControllerPos; // 0x168
	private static DelegateBridge __Hotfix0_UpdateCameraControllerScale; // 0x170
	private static DelegateBridge __Hotfix0_ParseCameraBasic; // 0x178
	private static DelegateBridge __Hotfix0_DoSetCameraStartPos; // 0x180
	private static DelegateBridge __Hotfix0_UpdateLayerCameraOrigins; // 0x188
	private static DelegateBridge __Hotfix0_UpdateAudioListener; // 0x190
	private static DelegateBridge __Hotfix0_FinishTweenIfNot; // 0x198
	private static DelegateBridge __Hotfix0__TryCreatePlugin; // 0x1a0
	private static DelegateBridge __Hotfix0__TryCreatePluginByActivity; // 0x1a8
	private static DelegateBridge __Hotfix0__UpdateTransparencySortMode; // 0x1b0
	private static DelegateBridge __Hotfix0_ReplaceCamera; // 0x1b8
	private static DelegateBridge __Hotfix0_Awake; // 0x1c0
	private static DelegateBridge __Hotfix0_Start; // 0x1c8
	private static DelegateBridge __Hotfix0_Update; // 0x1d0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x1d8
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x1e0
	private static DelegateBridge __Hotfix0__InitPostProcessLayer; // 0x1e8
	private static DelegateBridge __Hotfix0_InitPostProcessAA; // 0x1f0
	private static DelegateBridge __Hotfix0_SetSMAA; // 0x1f8
	private static DelegateBridge __Hotfix0__UpdateFrustumPlanesIfNeeded; // 0x200
	private static DelegateBridge __Hotfix0_IsVisible; // 0x208
	private static DelegateBridge _c__Hotfix0_ctor; // 0x210

	public Boolean hasPPLayer { get; }
	public MapLayer currentLayer { get; set; }
	public Vector3 originPos { get; set; }
	private MapLayer nextLayer { get; }
	public Boolean isTweening { get; }
	public Boolean isMoving { get; }
	public Boolean isScaling { get; }
	public CameraPosition cameraPosition { get; }
	public Camera camera { get; }
	public Camera uiPerspectiveCamera { get; }
	public Plugin plugin { get; set; }
	public Vector3 cameraOffset { get; }
	public Transform offsetTransform { get; }

	// RVA: 0x3f9bee8 VA: 0x75965b3ee8
	public Boolean get_hasPPLayer() { }
	// RVA: 0x3f9bf80 VA: 0x75965b3f80
	public MapLayer get_currentLayer() { }
	// RVA: 0x3f9bfe8 VA: 0x75965b3fe8
	protected Void set_currentLayer(MapLayer value) { }
	// RVA: 0x3f9c064 VA: 0x75965b4064
	public Vector3 get_originPos() { }
	// RVA: 0x3f9c128 VA: 0x75965b4128
	private Void set_originPos(Vector3 value) { }
	// RVA: 0x3f9c1c4 VA: 0x75965b41c4
	private MapLayer get_nextLayer() { }
	// RVA: 0x3f9c26c VA: 0x75965b426c
	public Boolean get_isTweening() { }
	// RVA: 0x3f9c2dc VA: 0x75965b42dc
	public Boolean get_isMoving() { }
	// RVA: 0x3f9c358 VA: 0x75965b4358
	public Boolean get_isScaling() { }
	// RVA: 0x3f9c3d4 VA: 0x75965b43d4
	public CameraPosition get_cameraPosition() { }
	// RVA: 0x3f9c43c VA: 0x75965b443c
	public Camera get_camera() { }
	// RVA: 0x3f9c4a4 VA: 0x75965b44a4
	public Camera get_uiPerspectiveCamera() { }
	// RVA: 0x3f9c50c VA: 0x75965b450c
	public Plugin get_plugin() { }
	// RVA: 0x3f9c574 VA: 0x75965b4574
	private Void set_plugin(Plugin value) { }
	// RVA: 0x3f9c5f8 VA: 0x75965b45f8
	public Vector3 get_cameraOffset() { }
	// RVA: 0x3f9c6fc VA: 0x75965b46fc
	public Transform get_offsetTransform() { }
	// RVA: 0x3f9c764 VA: 0x75965b4764
	public Void ResetAll(Boolean tween) { }
	// RVA: 0x3f9c908 VA: 0x75965b4908
	public Void SetCameraMoveDirectlyDisableState(Boolean disableState) { }
	// RVA: 0x3f9c988 VA: 0x75965b4988
	public Void SetPerspectiveCameraOn(PerpectiveCameraMask mask, Boolean isOn) { }
	// RVA: 0x3f9ca2c VA: 0x75965b4a2c
	private Void _SetPerspectiveCameraImp() { }
	// RVA: 0x3f9cab4 VA: 0x75965b4ab4
	public Void SetCameraPosition(CameraPosition cameraPos, Boolean tween) { }
	// RVA: 0x3f9cd30 VA: 0x75965b4d30
	public Void MoveCameraDirectly(Vector3 cameraPos, Boolean tween) { }
	// RVA: 0x3f9ce68 VA: 0x75965b4e68
	public Void SetCameraDefaultView(CameraViewLevel cameraView) { }
	// RVA: 0x3f9cf40 VA: 0x75965b4f40
	public Void SetCameraDefaultView(Vector3 pos) { }
	// RVA: 0x3f9d09c VA: 0x75965b509c
	public Void InitCameraDefaultView() { }
	// RVA: 0x3f9c800 VA: 0x75965b4800
	public Void ResetCameraPosition(Boolean tween) { }
	// RVA: 0x3f9d238 VA: 0x75965b5238
	public Void ShakeCamera(Single duration, Vector3 strength, Int32 vibrato, Single randomness) { }
	// RVA: 0x3f9d334 VA: 0x75965b5334
	public Void PutDown(Transform ts) { }
	// RVA: 0x3f9c884 VA: 0x75965b4884
	public Void ResetFocus(Boolean tween) { }
	// RVA: 0x3f9d420 VA: 0x75965b5420
	public Void Focus(Transform focusTo, Boolean tween) { }
	// RVA: 0x3f9d6b0 VA: 0x75965b56b0
	public Void Focus(Transform focusTo, Single ratio, Boolean tween) { }
	// RVA: 0x3f9d88c VA: 0x75965b588c
	public Void Focus(Vector3 pos, Single scale, Single moveTime, Boolean tween, Ease scaleEase, Ease moveEase) { }
	// RVA: 0x3f9df04 VA: 0x75965b5f04
	public Void ScaleOn(Single value, Single time, Ease scaleEase, Boolean tween) { }
	// RVA: 0x3f9dfd4 VA: 0x75965b5fd4
	public Void ResetFocusAndScale(Single time, Ease scaleEase, Ease moveEase) { }
	// RVA: 0x3f9d5b4 VA: 0x75965b55b4
	private Void _FocusInternal(Vector3 pos, Boolean tween) { }
	// RVA: 0x3f9da28 VA: 0x75965b5a28
	private Void _FocusInternal(Vector3 pos, Single scale, Single moveTime, Boolean tween, Ease scaleEase, Ease moveEase) { }
	// RVA: 0x3f9e140 VA: 0x75965b6140
	public Boolean IsValidPut(Int32 touchId) { }
	// RVA: 0x3f9e230 VA: 0x75965b6230
	public Void FaceToCamera(Transform obj) { }
	// RVA: 0x3f9e2d8 VA: 0x75965b62d8
	public Void FaceToCameraOnlyX(Transform obj) { }
	// RVA: 0x3f9e3f4 VA: 0x75965b63f4
	public Vector2 WorldToViewportDirectionV2(Vector3 origin, Vector2 direction) { }
	// RVA: 0x3f9e584 VA: 0x75965b6584
	private Void _DoAdaptCameraPosition() { }
	// RVA: 0x3f9e658 VA: 0x75965b6658
	private Void _DoAdaptDefaultCameraPosition() { }
	// RVA: 0x3f9e7a0 VA: 0x75965b67a0
	public Vector3 GetCameraPos() { }
	// RVA: 0x3f9e81c VA: 0x75965b681c
	public Single GetCameraScale() { }
	// RVA: 0x3f9e898 VA: 0x75965b6898
	public Single GetCameraHeight() { }
	// RVA: 0x3f9e920 VA: 0x75965b6920
	public Void UpdateCameraControllerPos(Vector3 pos) { }
	// RVA: 0x3f9eb68 VA: 0x75965b6b68
	public Void UpdateCameraControllerScale(Single scale) { }
	// RVA: 0x3f9ec40 VA: 0x75965b6c40
	public Void ParseCameraBasic(Blackboard blackboard) { }
	// RVA: 0x3f9ed50 VA: 0x75965b6d50
	public Void DoSetCameraStartPos(Vector2 startPos) { }
	// RVA: 0x3f9ee44 VA: 0x75965b6e44
	public Boolean UpdateLayerCameraOrigins(PlayerSide playerSide) { }
	// RVA: 0x3f9e9e8 VA: 0x75965b69e8
	public Void UpdateAudioListener() { }
	// RVA: 0x3f9e088 VA: 0x75965b6088
	public Void FinishTweenIfNot() { }
	// RVA: 0x3f9f040 VA: 0x75965b7040
	private Void _TryCreatePlugin() { }
	// RVA: 0x3f9f198 VA: 0x75965b7198
	private Void _TryCreatePluginByActivity() { }
	// RVA: 0x3f9f3d0 VA: 0x75965b73d0
	private Void _UpdateTransparencySortMode() { }
	// RVA: 0x3f9f44c VA: 0x75965b744c
	public Void ReplaceCamera(Camera newCamera) { }
	// RVA: 0x3f9f7a4 VA: 0x75965b77a4
	protected override Void Awake() { }
	// RVA: 0x3f9f898 VA: 0x75965b7898
	private Void Start() { }
	// RVA: 0x3f9f938 VA: 0x75965b7938
	public Void Update() { }
	// RVA: 0x3f9fbac VA: 0x75965b7bac
	protected override Void OnDestroy() { }
	// RVA: 0x3f9fc64 VA: 0x75965b7c64
	public Void OnSafeRectUpdated(SafeRect safeRect) { }
	// RVA: 0x3f9f6c4 VA: 0x75965b76c4
	private Void _InitPostProcessLayer() { }
	// RVA: 0x3f9fce8 VA: 0x75965b7ce8
	public Void InitPostProcessAA() { }
	// RVA: 0x3f9fed0 VA: 0x75965b7ed0
	public Void SetSMAA(Quality quality) { }
	// RVA: 0x3f9f9a0 VA: 0x75965b79a0
	private Void _UpdateFrustumPlanesIfNeeded() { }
	// RVA: 0x3f9ff68 VA: 0x75965b7f68
	public Boolean IsVisible(Vector3 center, Single radius) { }
	// RVA: 0x3fa00f8 VA: 0x75965b80f8
	public Void .ctor() { }
	// RVA: 0x3fa02b4 VA: 0x75965b82b4
	private Void <_FocusInternal>b__79_0() { }
	// RVA: 0x3fa02c4 VA: 0x75965b82c4
	private Void <_FocusInternal>b__79_1() { }
}
```