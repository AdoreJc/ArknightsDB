# Act1VAutoChessBattleHUDPage

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessHUDController _controller`

- `Act1VAutoChessHUDVirtualCamCanvasBinder _canvasBinder`

- `RectTransform _dlgContainer`

- `CanvasGroup _rootCanvasGroup`

- `Act1VAutoChessHUDBlurBackPanel _blurPanel`

- `Params m_params`

- `UICompDialogMgr m_dlgMgr`

- `DataBundle m_savedInst`

- `UIPageVirtualCamera m_virtualCamera`

- `UIPageVirtualCamera m_blurCameraPerspectiveLower`

- `UIPageVirtualCamera m_blurCameraOthographicLower`

- `FadeSwitchTween m_fadeTween`


## Properties

- `String actId`

- `UICompDialogMgr dlgMgr`


## Methods

- `String get_actId()`

- `UICompDialogMgr get_dlgMgr()`

- `Void _SetVirtualCamera(UIPageVirtualCamCanvasBinder, UIPageVirtualCamera)`

- `Void _ConstructCompDlgMgr(UIPageVirtualCamBlurCompBinder, List`1)`

- `Void _ConstructBackBlurPanel(BlurHandler, List`1)`

- `Void InitVirtualCamera(UIPageCameraProvider)`

- `Void DisposeVirtualCamera()`

- `Void LoadAllVirtualCamTypes(ICollection`1)`

- `Boolean <EffectsOnShow>b__30_0()`

- `Boolean <EffectsOnHide>b__31_0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessBattleHUDPage : StateEnginePage, IVirtualCameraPage
{
	private Act1VAutoChessHUDController _controller; // 0xe8
	private Act1VAutoChessHUDVirtualCamCanvasBinder _canvasBinder; // 0xf0
	private RectTransform _dlgContainer; // 0xf8
	private CanvasGroup _rootCanvasGroup; // 0x100
	private Act1VAutoChessHUDBlurBackPanel _blurPanel; // 0x108
	private Params m_params; // 0x110
	private UICompDialogMgr m_dlgMgr; // 0x118
	private DataBundle m_savedInst; // 0x120
	private UIPageVirtualCamera m_virtualCamera; // 0x128
	private UIPageVirtualCamera m_blurCameraPerspectiveLower; // 0x130
	private UIPageVirtualCamera m_blurCameraOthographicLower; // 0x138
	private SetWhenBind`2 m_cameraSetter; // 0x140
	private FadeSwitchTween m_fadeTween; // 0x148
	private SetWhenBind`2 m_dlgCameraCollecter; // 0x150
	private SetWhenBind`2 m_blurPanelCameraCollecter; // 0x158
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x8
	private static DelegateBridge __Hotfix0__SetVirtualCamera; // 0x10
	private static DelegateBridge __Hotfix0__ConstructCompDlgMgr; // 0x18
	private static DelegateBridge __Hotfix0__ConstructBackBlurPanel; // 0x20
	private static DelegateBridge __Hotfix0__EnsureCameraSetter; // 0x28
	private static DelegateBridge __Hotfix0__EnsureDlgCameraCollector; // 0x30
	private static DelegateBridge __Hotfix0__EnsureBlurPanelCameraCollector; // 0x38
	private static DelegateBridge __Hotfix0_InitVirtualCamera; // 0x40
	private static DelegateBridge __Hotfix0_DisposeVirtualCamera; // 0x48
	private static DelegateBridge __Hotfix0_LoadAllVirtualCamTypes; // 0x50
	private static DelegateBridge __Hotfix0_OnCreate; // 0x58
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x60
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String actId { get; }
	public UICompDialogMgr dlgMgr { get; }

	// RVA: 0x3364274 VA: 0x759597c274
	public String get_actId() { }
	// RVA: 0x3364348 VA: 0x759597c348
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x33643b0 VA: 0x759597c3b0
	private Void _SetVirtualCamera(UIPageVirtualCamCanvasBinder binder, UIPageVirtualCamera virtualCamera) { }
	// RVA: 0x3364444 VA: 0x759597c444
	private Void _ConstructCompDlgMgr(UIPageVirtualCamBlurCompBinder binder, List`1 virtualCameras) { }
	// RVA: 0x3364578 VA: 0x759597c578
	private Void _ConstructBackBlurPanel(BlurHandler blurHander, List`1 virtualCameras) { }
	// RVA: 0x3364694 VA: 0x759597c694
	private SetWhenBind`2 _EnsureCameraSetter() { }
	// RVA: 0x33647a8 VA: 0x759597c7a8
	private SetWhenBind`2 _EnsureDlgCameraCollector() { }
	// RVA: 0x33648bc VA: 0x759597c8bc
	private SetWhenBind`2 _EnsureBlurPanelCameraCollector() { }
	// RVA: 0x33649d0 VA: 0x759597c9d0
	public Void InitVirtualCamera(UIPageCameraProvider provider) { }
	// RVA: 0x3364e1c VA: 0x759597ce1c
	public Void DisposeVirtualCamera() { }
	// RVA: 0x3364eb0 VA: 0x759597ceb0
	public Void LoadAllVirtualCamTypes(ICollection`1 cameraTypes) { }
	// RVA: 0x33650c8 VA: 0x759597d0c8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x33652f4 VA: 0x759597d2f4
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x33653dc VA: 0x759597d3dc
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x33654c4 VA: 0x759597d4c4
	public Void .ctor() { }
	// RVA: 0x3365534 VA: 0x759597d534
	private Boolean <EffectsOnShow>b__30_0() { }
	// RVA: 0x3365550 VA: 0x759597d550
	private Boolean <EffectsOnHide>b__31_0() { }
	// RVA: 0x336556c VA: 0x759597d56c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3365574 VA: 0x759597d574
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x3365580 VA: 0x759597d580
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```