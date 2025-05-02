# HomeDisplayController

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _panelLeft`

- `CanvasGroup _panelRight`

- `CanvasGroup _panelFront`

- `CanvasGroup _charWordCanvas`

- `CanvasGroup _backgroundBtnCanvas`

- `UIStyleProvider _themeProvider`

- `Image _imageBackgroundLeft`

- `Image _imageBackgroundRight`

- `Transform _transHomePlayerContainer`

- `Transform _transEffectBgContainer`

- `Transform _transEffectFrontContainer`

- `Transform _transEffectCameraContainer`

- `CameraGyroController _frontController`

- `CameraGyroController _leftController`

- `CameraGyroController _rightController`

- `Single _tweenDuration`

- `UIAnimationLocation _animShow`

- `Boolean m_gyroInitialized`

- `HomeTheme m_theme`

- `JObject m_defaultHomeThemeJData`

- `String m_cachedHomeBgId`

- `HomeBackgroundAssetsWrapper m_cahcedHomeBgAssets`

- `ShowSwitchTween m_showSwitchTween`

- `Boolean <isUIShowing>k__BackingField`

- `FadeSwitchTween m_leftPanelTween`

- `FadeSwitchTween m_rightPanelTween`

- `FadeSwitchTween m_frontPanelTween`

- `FadeSwitchTween m_charWordTween`

- `FadeSwitchTween m_backgroundBtnTween`

- `Boolean m_hasPreviewTweenInited`


## Properties

- `JObject defaultHomeThemeJData`

- `Boolean isUIShowing`


## Methods

- `JObject get_defaultHomeThemeJData()`

- `Void _TryLoadDefaultHomeThemeJData()`

- `Boolean get_isUIShowing()`

- `Void set_isUIShowing(Boolean)`

- `Void LoadHomeBackground(String)`

- `Void SetIllustAvail(Boolean)`

- `Void _LoadHomeBackground(String)`

- `T _LoadAsset(String)`

- `Void _UnloadHomeBackgroundAssets()`

- `Void _UnloadAsset(T)`

- `Int32 _GetAssetGroup()`

- `Void _DisposeSelf()`

- `Void LoadHomeTheme(String)`

- `Void _UnloadHomeThemeAssets()`

- `Void RequestStartPreviewMode(Int32, Boolean, PreviewElemFlag)`

- `Void RequestExitPreviewMode(Int32, Boolean, PreviewElemFlag)`

- `Void _RequestStartPreviewModeInternal(PreviewElemFlag, Int32, PreviewElemFlag, Boolean)`

- `Void _RequestExitPreviewModeInternal(PreviewElemFlag, Int32, PreviewElemFlag, Boolean)`

- `FadeSwitchTween _GetTweenByFlag(PreviewElemFlag)`

- `Void _InitPreviewTweenIfNot()`

- `FadeSwitchTween _GenerateSwitchTween(CanvasGroup)`

- `Void _InitHomeShowAnim()`

- `IEnumerator PlayHomeShowAnim()`

- `Void HideForegroundCameras(Boolean)`

- `Void DisableLeftRightUpdate()`

- `Void EnableLeftRightUpdate()`

- `Void TweenCamerasToOriginalPositions(Action)`

- `Void RecontrolCameras()`

- `Void _DisableAll()`

- `Void _EnableAll()`

- `Boolean _CheckCondition()`

- `IEnumerator _EnableComponentsDelayed()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeDisplayController : PageSingleComponent
{
	private const String DEFAULT_THEME_ID; // 0x0
	private CanvasGroup _panelLeft; // 0x20
	private CanvasGroup _panelRight; // 0x28
	private CanvasGroup _panelFront; // 0x30
	private CanvasGroup _charWordCanvas; // 0x38
	private CanvasGroup _backgroundBtnCanvas; // 0x40
	private UIStyleProvider _themeProvider; // 0x48
	private Image _imageBackgroundLeft; // 0x50
	private Image _imageBackgroundRight; // 0x58
	private Transform _transHomePlayerContainer; // 0x60
	private Transform _transEffectBgContainer; // 0x68
	private Transform _transEffectFrontContainer; // 0x70
	private Transform _transEffectCameraContainer; // 0x78
	private CameraGyroController _frontController; // 0x80
	private CameraGyroController _leftController; // 0x88
	private CameraGyroController _rightController; // 0x90
	private Single _tweenDuration; // 0x98
	private UIAnimationLocation _animShow; // 0xa0
	private List`1 _foregroundCameras; // 0xb0
	private Boolean m_gyroInitialized; // 0xb8
	private HomeTheme m_theme; // 0xc0
	private JObject m_defaultHomeThemeJData; // 0xc8
	private String m_cachedHomeBgId; // 0xd0
	private HomeBackgroundAssetsWrapper m_cahcedHomeBgAssets; // 0xd8
	private ShowSwitchTween m_showSwitchTween; // 0xe0
	private Boolean <isUIShowing>k__BackingField; // 0xe8
	private const Single UI_FADE_TIME; // 0x0
	private const Single SHOW_DURATION; // 0x0
	private Dictionary`2 m_requesetedPreviewModeDict; // 0xf0
	private FadeSwitchTween m_leftPanelTween; // 0xf8
	private FadeSwitchTween m_rightPanelTween; // 0x100
	private FadeSwitchTween m_frontPanelTween; // 0x108
	private FadeSwitchTween m_charWordTween; // 0x110
	private FadeSwitchTween m_backgroundBtnTween; // 0x118
	private Boolean m_hasPreviewTweenInited; // 0x120
	private static DelegateBridge __Hotfix0_get_defaultHomeThemeJData; // 0x0
	private static DelegateBridge __Hotfix0__TryLoadDefaultHomeThemeJData; // 0x8
	private static DelegateBridge __Hotfix0_get_isUIShowing; // 0x10
	private static DelegateBridge __Hotfix0_set_isUIShowing; // 0x18
	private static DelegateBridge __Hotfix0_LoadHomeBackground; // 0x20
	private static DelegateBridge __Hotfix0_SetIllustAvail; // 0x28
	private static DelegateBridge __Hotfix0__LoadHomeBackground; // 0x30
	private static DelegateBridge __Hotfix0__LoadAsset; // 0x38
	private static DelegateBridge __Hotfix0__UnloadHomeBackgroundAssets; // 0x40
	private static DelegateBridge __Hotfix0__UnloadAsset; // 0x48
	private static DelegateBridge __Hotfix0__GetAssetGroup; // 0x50
	private static DelegateBridge __Hotfix0__DisposeSelf; // 0x58
	private static DelegateBridge __Hotfix0_LoadHomeTheme; // 0x60
	private static DelegateBridge __Hotfix0__UnloadHomeThemeAssets; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge __Hotfix0_RequestStartPreviewMode; // 0x78
	private static DelegateBridge __Hotfix0_RequestExitPreviewMode; // 0x80
	private static DelegateBridge __Hotfix0__RequestStartPreviewModeInternal; // 0x88
	private static DelegateBridge __Hotfix0__RequestExitPreviewModeInternal; // 0x90
	private static DelegateBridge __Hotfix0__GetTweenByFlag; // 0x98
	private static DelegateBridge __Hotfix0__InitPreviewTweenIfNot; // 0xa0
	private static DelegateBridge __Hotfix0__GenerateSwitchTween; // 0xa8
	private static DelegateBridge __Hotfix0__InitHomeShowAnim; // 0xb0
	private static DelegateBridge __Hotfix0_PlayHomeShowAnim; // 0xb8
	private static DelegateBridge __Hotfix0_HideForegroundCameras; // 0xc0
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0xc8
	private static DelegateBridge __Hotfix0_DisableLeftRightUpdate; // 0xd0
	private static DelegateBridge __Hotfix0_EnableLeftRightUpdate; // 0xd8
	private static DelegateBridge __Hotfix0_TweenCamerasToOriginalPositions; // 0xe0
	private static DelegateBridge __Hotfix0_RecontrolCameras; // 0xe8
	private static DelegateBridge __Hotfix0__DisableAll; // 0xf0
	private static DelegateBridge __Hotfix0__EnableAll; // 0xf8
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x100
	private static DelegateBridge __Hotfix0__EnableComponentsDelayed; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	public JObject defaultHomeThemeJData { get; }
	public Boolean isUIShowing { get; set; }

	// RVA: 0x28071f4 VA: 0x7594e1f1f4
	public JObject get_defaultHomeThemeJData() { }
	// RVA: 0x280725c VA: 0x7594e1f25c
	private Void _TryLoadDefaultHomeThemeJData() { }
	// RVA: 0x28073a8 VA: 0x7594e1f3a8
	public Boolean get_isUIShowing() { }
	// RVA: 0x2807410 VA: 0x7594e1f410
	private Void set_isUIShowing(Boolean value) { }
	// RVA: 0x280572c VA: 0x7594e1d72c
	public Void LoadHomeBackground(String bgId) { }
	// RVA: 0x2807810 VA: 0x7594e1f810
	public Void SetIllustAvail(Boolean flag) { }
	// RVA: 0x2807490 VA: 0x7594e1f490
	private Void _LoadHomeBackground(String bgId) { }
	// RVA: 0x VA: 0x0
	private T _LoadAsset(String resPath) { }
	// RVA: 0x2807918 VA: 0x7594e1f918
	private Void _UnloadHomeBackgroundAssets() { }
	// RVA: 0x VA: 0x0
	private Void _UnloadAsset(T asset) { }
	// RVA: 0x2807b24 VA: 0x7594e1fb24
	private Int32 _GetAssetGroup() { }
	// RVA: 0x2807b90 VA: 0x7594e1fb90
	private Void _DisposeSelf() { }
	// RVA: 0x2807cd4 VA: 0x7594e1fcd4
	public Void LoadHomeTheme(String themeId) { }
	// RVA: 0x2807c00 VA: 0x7594e1fc00
	private Void _UnloadHomeThemeAssets() { }
	// RVA: 0x2807ec4 VA: 0x7594e1fec4
	protected override Void OnDestroy() { }
	// RVA: 0x2800a08 VA: 0x7594e18a08
	public Void RequestStartPreviewMode(Int32 requestId, Boolean fastMode, PreviewElemFlag flag) { }
	// RVA: 0x2800c38 VA: 0x7594e18c38
	public Void RequestExitPreviewMode(Int32 requestId, Boolean fastMode, PreviewElemFlag flag) { }
	// RVA: 0x2807f38 VA: 0x7594e1ff38
	private Void _RequestStartPreviewModeInternal(PreviewElemFlag checkFlag, Int32 requestId, PreviewElemFlag flag, Boolean fastMode) { }
	// RVA: 0x280813c VA: 0x7594e2013c
	private Void _RequestExitPreviewModeInternal(PreviewElemFlag checkFlag, Int32 requestId, PreviewElemFlag flag, Boolean fastMode) { }
	// RVA: 0x280835c VA: 0x7594e2035c
	private FadeSwitchTween _GetTweenByFlag(PreviewElemFlag flag) { }
	// RVA: 0x2808430 VA: 0x7594e20430
	private Void _InitPreviewTweenIfNot() { }
	// RVA: 0x2808538 VA: 0x7594e20538
	private FadeSwitchTween _GenerateSwitchTween(CanvasGroup cg) { }
	// RVA: 0x280873c VA: 0x7594e2073c
	private Void _InitHomeShowAnim() { }
	// RVA: 0x280889c VA: 0x7594e2089c
	public IEnumerator PlayHomeShowAnim() { }
	// RVA: 0x2808970 VA: 0x7594e20970
	public Void HideForegroundCameras(Boolean hide) { }
	// RVA: 0x2808b18 VA: 0x7594e20b18
	protected override Void OnPageRouted() { }
	// RVA: 0x2808e04 VA: 0x7594e20e04
	public Void DisableLeftRightUpdate() { }
	// RVA: 0x2808f24 VA: 0x7594e20f24
	public Void EnableLeftRightUpdate() { }
	// RVA: 0x2809044 VA: 0x7594e21044
	public Void TweenCamerasToOriginalPositions(Action tweenFinishCb) { }
	// RVA: 0x2809278 VA: 0x7594e21278
	public Void RecontrolCameras() { }
	// RVA: 0x2808be4 VA: 0x7594e20be4
	private Void _DisableAll() { }
	// RVA: 0x280933c VA: 0x7594e2133c
	private Void _EnableAll() { }
	// RVA: 0x2809210 VA: 0x7594e21210
	private Boolean _CheckCondition() { }
	// RVA: 0x2808d58 VA: 0x7594e20d58
	private IEnumerator _EnableComponentsDelayed() { }
	// RVA: 0x2809508 VA: 0x7594e21508
	public Void .ctor() { }
	// RVA: 0x2809610 VA: 0x7594e21610
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x2809618 VA: 0x7594e21618
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```