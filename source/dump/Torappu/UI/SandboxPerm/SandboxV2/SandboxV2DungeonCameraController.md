# SandboxV2DungeonCameraController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `MobileTouchCamera _touchCamera`

- `TorappuTouchInputController _touchInputController`

- `Single _standardGlobalZoomMin`

- `Single _standardGlobalContentHeight`

- `Single _standardGlobalTiltMin`

- `Single _standardGlobalTiltMax`

- `SandboxV2DungeonCameraSlider _slider`

- `SandboxV2DungeonLodController _lodController`

- `SandboxV2DungeonCameraClick _cameraClick`

- `Single _cameraMargin`

- `BlurScreenTexGenerator _blurGenerator`

- `UIBlendRTHost _blurHost`

- `Boolean m_inited`

- `Int32 m_lock`

- `State m_state`

- `Tween m_cameraTween`

- `Single m_cachedSafeAreaWidth`

- `Single m_cachedSafeAreaHeight`

- `Single m_cachedScreenWidth`

- `Single m_cachedScreenHeight`

- `SafeRect m_cachedSafeRect`

- `Vector2 m_boundaryCenter`

- `Vector2 m_boundarySize`

- `Vector2 m_boundaryMax`

- `Vector2 m_boundaryMin`

- `Single m_cameraGlobalZoomMin`

- `Single m_cameraGlobalZoomMax`

- `Single m_cameraMaxNormalizedZoom`

- `SeqNumChecker m_dungeonConstructChecker`

- `SeqNumChecker m_nodeFocusChecker`

- `UIPageFinder m_pageFinder`

- `Boolean <cullingEnabled>k__BackingField`

- `Action <onSelectionCanceled>k__BackingField`


## Properties

- `Boolean cullingEnabled`

- `Single tanHalfFov`

- `Action onSelectionCanceled`

- `Boolean interactable`


## Methods

- `Boolean get_cullingEnabled()`

- `Void set_cullingEnabled(Boolean)`

- `Single get_tanHalfFov()`

- `Action get_onSelectionCanceled()`

- `Void set_onSelectionCanceled(Action)`

- `Boolean get_interactable()`

- `Void _InitIfNot()`

- `Void Awake()`

- `Void OnDestroy()`

- `Void Update()`

- `Void LateUpdate()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Single _GetNormalizedZoom(Single)`

- `Single _GetZoom(Single)`

- `Void _ResetCameraBoundary()`

- `Void _OnZoomUpdate(Single, Single)`

- `Void _UpdateSliderZoom(Single)`

- `Void _UpdateCameraZoom(Single)`

- `Void _OnCameraClicked(Vector2)`

- `Void _SetLock(LockSource, Boolean)`

- `Void SetLock(LockSource, Boolean)`

- `Void _SetState(State)`

- `Void _UpdateMapConfig(SandboxV2MapConfig)`

- `Boolean _CheckCulling(Vector3)`

- `Boolean _CheckCulling(ISandboxV2DungeonCullElement)`

- `Void _UpdateCulling()`

- `Void Watch(ISandboxV2DungeonCullElement)`

- `Void Unwatch(ISandboxV2DungeonCullElement)`

- `Vector2 _GetIntersection2d(Ray)`

- `Vector2 _GetTargetFocusPos(Vector2, Vector2[])`

- `Vector2 _GetCurrFocusPos(Vector2)`

- `Void _CameraFocusOnPos(Vector2, Vector2, Single)`

- `Tween _GetFocusOnPosTween(Vector2, Vector2, Single, Ease)`

- `Tween _GetFocusOnPosAndZoomTween(Vector2, Vector2, Single, Single, Ease)`

- `Tween _GetZoomInWithCustomCenterTween(Vector3, Single, Single, Ease)`

- `Void _CameraZoom(Vector2, Single, Single, Ease)`

- `Void _FocusOnPos(Vector2, Vector2, Single, Ease)`

- `Void _FocusOnPosImmediately(Vector2, Vector2)`

- `Void _CancelSelectedNode()`

- `Vector3 <_GetFocusOnPosTween>b__81_0()`

- `Void <_GetFocusOnPosTween>b__81_1(Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCameraController : DataBinder`1, ISafeAreaListener
{
	private const Single STANDARD_ASPECT_RATIO; // 0x0
	private const Single UI_CANVAS_SCALE; // 0x0
	public const Single DEFAULT_FOCUS_DURATION; // 0x0
	public const Ease DEFAULT_FOCUS_EASE_TYPE; // 0x0
	private MobileTouchCamera _touchCamera; // 0x20
	private TorappuTouchInputController _touchInputController; // 0x28
	private Single _standardGlobalZoomMin; // 0x30
	private Single _standardGlobalContentHeight; // 0x34
	private Single _standardGlobalTiltMin; // 0x38
	private Single _standardGlobalTiltMax; // 0x3c
	private SandboxV2DungeonCameraSlider _slider; // 0x40
	private SandboxV2DungeonLodController _lodController; // 0x48
	private SandboxV2DungeonCameraClick _cameraClick; // 0x50
	private Single _cameraMargin; // 0x58
	private Single[] _lodThresholds; // 0x60
	private Vector2[] _focusScreenAnchors; // 0x68
	private BlurScreenTexGenerator _blurGenerator; // 0x70
	private UIBlendRTHost _blurHost; // 0x78
	private Boolean m_inited; // 0x80
	private Int32 m_lock; // 0x84
	private State m_state; // 0x88
	private Tween m_cameraTween; // 0x90
	private Single m_cachedSafeAreaWidth; // 0x98
	private Single m_cachedSafeAreaHeight; // 0x9c
	private Single m_cachedScreenWidth; // 0xa0
	private Single m_cachedScreenHeight; // 0xa4
	private SafeRect m_cachedSafeRect; // 0xa8
	private Vector2 m_boundaryCenter; // 0xb8
	private Vector2 m_boundarySize; // 0xc0
	private Vector2 m_boundaryMax; // 0xc8
	private Vector2 m_boundaryMin; // 0xd0
	private Single m_cameraGlobalZoomMin; // 0xd8
	private Single m_cameraGlobalZoomMax; // 0xdc
	private Single m_cameraMaxNormalizedZoom; // 0xe0
	private SeqNumChecker m_dungeonConstructChecker; // 0xe8
	private SeqNumChecker m_nodeFocusChecker; // 0xf8
	private UIPageFinder m_pageFinder; // 0x108
	private HashSet`1 m_cullElements; // 0x118
	private Boolean <cullingEnabled>k__BackingField; // 0x120
	private Action <onSelectionCanceled>k__BackingField; // 0x128
	private static DelegateBridge __Hotfix0_get_cullingEnabled; // 0x0
	private static DelegateBridge __Hotfix0_set_cullingEnabled; // 0x8
	private static DelegateBridge __Hotfix0_get_tanHalfFov; // 0x10
	private static DelegateBridge __Hotfix0_get_onSelectionCanceled; // 0x18
	private static DelegateBridge __Hotfix0_set_onSelectionCanceled; // 0x20
	private static DelegateBridge __Hotfix0_get_interactable; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_Awake; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x50
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x58
	private static DelegateBridge __Hotfix0__GetNormalizedZoom; // 0x60
	private static DelegateBridge __Hotfix0__GetZoom; // 0x68
	private static DelegateBridge __Hotfix0__ResetCameraBoundary; // 0x70
	private static DelegateBridge __Hotfix0__OnZoomUpdate; // 0x78
	private static DelegateBridge __Hotfix0__UpdateSliderZoom; // 0x80
	private static DelegateBridge __Hotfix0__UpdateCameraZoom; // 0x88
	private static DelegateBridge __Hotfix0__OnCameraClicked; // 0x90
	private static DelegateBridge __Hotfix0__SetLock; // 0x98
	private static DelegateBridge __Hotfix0_SetLock; // 0xa0
	private static DelegateBridge __Hotfix0__SetState; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateMapConfig; // 0xb0
	private static DelegateBridge __Hotfix0__CheckCulling; // 0xb8
	private static DelegateBridge __Hotfix1__CheckCulling; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateCulling; // 0xc8
	private static DelegateBridge __Hotfix0_Watch; // 0xd0
	private static DelegateBridge __Hotfix0_Unwatch; // 0xd8
	private static DelegateBridge __Hotfix0__GetIntersection2d; // 0xe0
	private static DelegateBridge __Hotfix0__CalculateFocusOffset; // 0xe8
	private static DelegateBridge __Hotfix1__CalculateFocusOffset; // 0xf0
	private static DelegateBridge __Hotfix0__GetTargetFocusPos; // 0xf8
	private static DelegateBridge __Hotfix0__GetCurrFocusPos; // 0x100
	private static DelegateBridge __Hotfix0__CameraFocusOnPos; // 0x108
	private static DelegateBridge __Hotfix0__GetFocusOnPosTween; // 0x110
	private static DelegateBridge __Hotfix0__GetFocusOnPosAndZoomTween; // 0x118
	private static DelegateBridge __Hotfix0__GetZoomInWithCustomCenterTween; // 0x120
	private static DelegateBridge __Hotfix0__CameraZoom; // 0x128
	private static DelegateBridge __Hotfix0__FocusOnPos; // 0x130
	private static DelegateBridge __Hotfix0__FocusOnPosImmediately; // 0x138
	private static DelegateBridge __Hotfix0__CancelSelectedNode; // 0x140
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x148
	private static DelegateBridge __Hotfix0_GetCenterOffset; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	public Boolean cullingEnabled { get; set; }
	private Single tanHalfFov { get; }
	public Action onSelectionCanceled { get; set; }
	public Boolean interactable { get; }

	// RVA: 0x2515080 VA: 0x7594b2d080
	public Boolean get_cullingEnabled() { }
	// RVA: 0x25150e8 VA: 0x7594b2d0e8
	public Void set_cullingEnabled(Boolean value) { }
	// RVA: 0x2515168 VA: 0x7594b2d168
	private Single get_tanHalfFov() { }
	// RVA: 0x2515208 VA: 0x7594b2d208
	public Action get_onSelectionCanceled() { }
	// RVA: 0x2515270 VA: 0x7594b2d270
	public Void set_onSelectionCanceled(Action value) { }
	// RVA: 0x25152f4 VA: 0x7594b2d2f4
	public Boolean get_interactable() { }
	// RVA: 0x2515374 VA: 0x7594b2d374
	private Void _InitIfNot() { }
	// RVA: 0x2515764 VA: 0x7594b2d764
	private Void Awake() { }
	// RVA: 0x25158bc VA: 0x7594b2d8bc
	private Void OnDestroy() { }
	// RVA: 0x2515a14 VA: 0x7594b2da14
	private Void Update() { }
	// RVA: 0x2515ed4 VA: 0x7594b2ded4
	private Void LateUpdate() { }
	// RVA: 0x2516180 VA: 0x7594b2e180
	public Void OnSafeRectUpdated(SafeRect rect) { }
	// RVA: 0x2515da0 VA: 0x7594b2dda0
	private Single _GetNormalizedZoom(Single zoom) { }
	// RVA: 0x25165c4 VA: 0x7594b2e5c4
	private Single _GetZoom(Single normalizedZoom) { }
	// RVA: 0x2516284 VA: 0x7594b2e284
	private Void _ResetCameraBoundary() { }
	// RVA: 0x25167dc VA: 0x7594b2e7dc
	private Void _OnZoomUpdate(Single prevZoom, Single currZoom) { }
	// RVA: 0x2515e40 VA: 0x7594b2de40
	private Void _UpdateSliderZoom(Single normalizedZoomValue) { }
	// RVA: 0x2515cf8 VA: 0x7594b2dcf8
	private Void _UpdateCameraZoom(Single normalizedZoomValue) { }
	// RVA: 0x2516964 VA: 0x7594b2e964
	private Void _OnCameraClicked(Vector2 screenPosition) { }
	// RVA: 0x2516e54 VA: 0x7594b2ee54
	private Void _SetLock(LockSource lockSource, Boolean isLock) { }
	// RVA: 0x2516f14 VA: 0x7594b2ef14
	public Void SetLock(LockSource lockSource, Boolean isLock) { }
	// RVA: 0x2515b44 VA: 0x7594b2db44
	private Void _SetState(State state) { }
	// RVA: 0x251700c VA: 0x7594b2f00c
	private Void _UpdateMapConfig(SandboxV2MapConfig config) { }
	// RVA: 0x2517128 VA: 0x7594b2f128
	private Boolean _CheckCulling(Vector3 pos) { }
	// RVA: 0x251722c VA: 0x7594b2f22c
	private Boolean _CheckCulling(ISandboxV2DungeonCullElement element) { }
	// RVA: 0x2515f3c VA: 0x7594b2df3c
	private Void _UpdateCulling() { }
	// RVA: 0x2517378 VA: 0x7594b2f378
	public Void Watch(ISandboxV2DungeonCullElement element) { }
	// RVA: 0x25174f8 VA: 0x7594b2f4f8
	public Void Unwatch(ISandboxV2DungeonCullElement element) { }
	// RVA: 0x25175d4 VA: 0x7594b2f5d4
	private Vector2 _GetIntersection2d(Ray ray) { }
	// RVA: 0x2517694 VA: 0x7594b2f694
	private Vector2[] _CalculateFocusOffset(Vector2 screenAnchor) { }
	// RVA: 0x25179a4 VA: 0x7594b2f9a4
	private Vector2[] _CalculateFocusOffset(Vector2 screenAnchor, Single normalizedZoom) { }
	// RVA: 0x2517c64 VA: 0x7594b2fc64
	private Vector2 _GetTargetFocusPos(Vector2 targetPos, Vector2[] focusOffset) { }
	// RVA: 0x2517d8c VA: 0x7594b2fd8c
	private Vector2 _GetCurrFocusPos(Vector2 screenAnchor) { }
	// RVA: 0x2517e7c VA: 0x7594b2fe7c
	private Void _CameraFocusOnPos(Vector2 pos, Vector2 screenAnchor, Single zoom) { }
	// RVA: 0x2517fd0 VA: 0x7594b2ffd0
	private Tween _GetFocusOnPosTween(Vector2 targetPos, Vector2 screenAnchor, Single duration, Ease easeType) { }
	// RVA: 0x2518244 VA: 0x7594b30244
	private Tween _GetFocusOnPosAndZoomTween(Vector2 targetPos, Vector2 screenAnchor, Single targetNormalizedZoom, Single duration, Ease easeType) { }
	// RVA: 0x2516bb8 VA: 0x7594b2ebb8
	private Tween _GetZoomInWithCustomCenterTween(Vector3 zoomCenterScreenPos, Single targetNormalizedZoom, Single duration, Ease easeType) { }
	// RVA: 0x25184ec VA: 0x7594b304ec
	private Void _CameraZoom(Vector2 targetCanvasPos, Single targetNormalizedZoom, Single duration, Ease easeType) { }
	// RVA: 0x2518618 VA: 0x7594b30618
	private Void _FocusOnPos(Vector2 targetCanvasPos, Vector2 screenAnchor, Single duration, Ease easeType) { }
	// RVA: 0x2518820 VA: 0x7594b30820
	private Void _FocusOnPosImmediately(Vector2 targetCanvasPos, Vector2 screenAnchor) { }
	// RVA: 0x2516b1c VA: 0x7594b2eb1c
	private Void _CancelSelectedNode() { }
	// RVA: 0x2518988 VA: 0x7594b30988
	public override Void OnValueChanged(SandboxV2DungeonProperty property) { }
	// RVA: 0x2516670 VA: 0x7594b2e670
	public static Vector2 GetCenterOffset(Single camZoom, Single camTilt, Single camFov, Single aspectRatio, Single screenWidth, Single screenHeight, Vector2 screenPos) { }
	// RVA: 0x2518be8 VA: 0x7594b30be8
	public Void .ctor() { }
	// RVA: 0x2518d60 VA: 0x7594b30d60
	private Vector3 <_GetFocusOnPosTween>b__81_0() { }
	// RVA: 0x2518d88 VA: 0x7594b30d88
	private Void <_GetFocusOnPosTween>b__81_1(Vector3 val) { }
}
```