# FifthAnnivExploreMapController

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `StateEngine _stateEngine`

- `FifthAnnivExploreMapCameraController _cameraController`

- `FifthAnnivExploreMapView _mapView`

- `RectTransform _rectTransformBottomLeft`

- `RectTransform _rectTransformBottomRight`

- `RectTransform _rectTransformTopLeft`

- `RectTransform _rectTransformTopRight`

- `FifthAnnivExploreTopMenuView _topMenuView`

- `FifthAnnivExploreTargetInfoView _targetInfoView`

- `FifthAnnivExploreSideInfoView _sideInfoView`

- `Single _lineCornerCountFactor`

- `Single _lineMaxAmplitudeFactor`

- `Boolean m_isInited`

- `FifthAnnivExploreProperty m_exploreProperty`

- `FifthAnnivExploreMapViewConfig m_mapViewConfig`

- `RouteCornerPos m_cornerPos`

- `OnStateChangeListener m_stateChangeListener`

- `FifthAnnivExploreTargetInfoProperty m_targetInfoProperty`

- `Int32 m_quitDialogInstId`

- `FifthAnnivExploreMapCameraRTHolder m_cameraRTHolder`


## Properties

- `FifthAnnivExploreProperty exploreProperty`

- `FifthAnnivExploreMapViewConfig mapViewConfig`

- `StateEngine stateEngine`

- `FifthAnnivExploreMapCameraRTHolder cameraRTHolder`


## Methods

- `FifthAnnivExploreProperty get_exploreProperty()`

- `FifthAnnivExploreMapViewConfig get_mapViewConfig()`

- `StateEngine get_stateEngine()`

- `FifthAnnivExploreMapCameraRTHolder get_cameraRTHolder()`

- `Void ReloadMap(Boolean, Boolean)`

- `Void OpenQuitDialog()`

- `Void OpenMissionDialog()`

- `Void FinishGame()`

- `Void _OnStateEnter(Type, Additions)`

- `Void _OnStateResume(Type, Boolean, Additions)`

- `Void _OnBeforeTransition(Type, Type, Additions)`

- `Void _OnStatePause(Type, Additions)`

- `Void _OnHeritageBtnClick()`

- `Void _OnProgressBtnClick()`

- `Void _CloseTargetInfo()`

- `Void _InitController()`

- `Boolean _CheckUIStable()`

- `Void _OnMsgForwardToNextNodeSuc()`

- `Void _OnMsgForwardToNextNodeFail()`

- `Void _OnMsgBackToMap()`

- `Void _OnMsgUpdateTopMenu()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _OnMsgBackFromMissionDialog()`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapController : PageSingleComponent, IValueMsgReceiver, ICompDialogCallBack
{
	public const Int32 MSG_FORWARD_TO_NEXT_NODE; // 0x0
	public const Int32 MSG_BACK_TO_MAP; // 0x0
	public const Int32 MSG_UPDATE_TOP_MENU; // 0x0
	public const Int32 MSG_BACK_FROM_MISSION_DIALOG; // 0x0
	public const Int32 MSG_OPEN_TARGET_VIEW; // 0x0
	private StateEngine _stateEngine; // 0x20
	private FifthAnnivExploreMapCameraController _cameraController; // 0x28
	private FifthAnnivExploreMapView _mapView; // 0x30
	private RectTransform _rectTransformBottomLeft; // 0x38
	private RectTransform _rectTransformBottomRight; // 0x40
	private RectTransform _rectTransformTopLeft; // 0x48
	private RectTransform _rectTransformTopRight; // 0x50
	private FifthAnnivExploreTopMenuView _topMenuView; // 0x58
	private FifthAnnivExploreTargetInfoView _targetInfoView; // 0x60
	private FifthAnnivExploreSideInfoView _sideInfoView; // 0x68
	private Single _lineCornerCountFactor; // 0x70
	private Single _lineMaxAmplitudeFactor; // 0x74
	private Boolean m_isInited; // 0x78
	private FifthAnnivExploreProperty m_exploreProperty; // 0x80
	private FifthAnnivExploreMapViewConfig m_mapViewConfig; // 0x88
	private RouteCornerPos m_cornerPos; // 0x90
	private OnStateChangeListener m_stateChangeListener; // 0xb0
	private EventPool`1 m_eventPool; // 0xb8
	private FifthAnnivExploreTargetInfoProperty m_targetInfoProperty; // 0xc0
	private Int32 m_quitDialogInstId; // 0xc8
	private FifthAnnivExploreMapCameraRTHolder m_cameraRTHolder; // 0xd0
	private static DelegateBridge __Hotfix0_get_exploreProperty; // 0x0
	private static DelegateBridge __Hotfix0_get_mapViewConfig; // 0x8
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x10
	private static DelegateBridge __Hotfix0_get_stateEngine; // 0x18
	private static DelegateBridge __Hotfix0_get_cameraRTHolder; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x28
	private static DelegateBridge __Hotfix0_ReloadMap; // 0x30
	private static DelegateBridge __Hotfix0_OpenQuitDialog; // 0x38
	private static DelegateBridge __Hotfix0_OpenMissionDialog; // 0x40
	private static DelegateBridge __Hotfix0_FinishGame; // 0x48
	private static DelegateBridge __Hotfix0__OnStateEnter; // 0x50
	private static DelegateBridge __Hotfix0__OnStateResume; // 0x58
	private static DelegateBridge __Hotfix0__OnBeforeTransition; // 0x60
	private static DelegateBridge __Hotfix0__OnStatePause; // 0x68
	private static DelegateBridge __Hotfix0__OnHeritageBtnClick; // 0x70
	private static DelegateBridge __Hotfix0__OnProgressBtnClick; // 0x78
	private static DelegateBridge __Hotfix0__CloseTargetInfo; // 0x80
	private static DelegateBridge __Hotfix0__InitController; // 0x88
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0x90
	private static DelegateBridge __Hotfix0__OnMsgForwardToNextNodeSuc; // 0x98
	private static DelegateBridge __Hotfix0__OnMsgForwardToNextNodeFail; // 0xa0
	private static DelegateBridge __Hotfix0__OnMsgBackToMap; // 0xa8
	private static DelegateBridge __Hotfix0__OnMsgUpdateTopMenu; // 0xb0
	private static DelegateBridge __Hotfix0_OnMessage; // 0xb8
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0xc0
	private static DelegateBridge __Hotfix0__OnMsgBackFromMissionDialog; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public FifthAnnivExploreProperty exploreProperty { get; }
	public FifthAnnivExploreMapViewConfig mapViewConfig { get; }
	public EventPool`1 eventPool { get; }
	public StateEngine stateEngine { get; }
	public FifthAnnivExploreMapCameraRTHolder cameraRTHolder { get; }

	// RVA: 0x2917e60 VA: 0x7594f2fe60
	public FifthAnnivExploreProperty get_exploreProperty() { }
	// RVA: 0x291e3c0 VA: 0x7594f363c0
	public FifthAnnivExploreMapViewConfig get_mapViewConfig() { }
	// RVA: 0x291e428 VA: 0x7594f36428
	public EventPool`1 get_eventPool() { }
	// RVA: 0x291e490 VA: 0x7594f36490
	public StateEngine get_stateEngine() { }
	// RVA: 0x291de80 VA: 0x7594f35e80
	public FifthAnnivExploreMapCameraRTHolder get_cameraRTHolder() { }
	// RVA: 0x291e4f8 VA: 0x7594f364f8
	protected override Void OnCreate() { }
	// RVA: 0x29179e8 VA: 0x7594f2f9e8
	public Void ReloadMap(Boolean isInit, Boolean isNewGame) { }
	// RVA: 0x291eae4 VA: 0x7594f36ae4
	public Void OpenQuitDialog() { }
	// RVA: 0x291ec70 VA: 0x7594f36c70
	public Void OpenMissionDialog() { }
	// RVA: 0x291ee04 VA: 0x7594f36e04
	public Void FinishGame() { }
	// RVA: 0x291ee6c VA: 0x7594f36e6c
	private Void _OnStateEnter(Type stateType, Additions additions) { }
	// RVA: 0x291ef80 VA: 0x7594f36f80
	private Void _OnStateResume(Type stateType, Boolean isBack, Additions additions) { }
	// RVA: 0x291f0a4 VA: 0x7594f370a4
	private Void _OnBeforeTransition(Type stateType, Type toType, Additions additions) { }
	// RVA: 0x291f1c0 VA: 0x7594f371c0
	private Void _OnStatePause(Type stateType, Additions additions) { }
	// RVA: 0x291f2d4 VA: 0x7594f372d4
	private Void _OnHeritageBtnClick() { }
	// RVA: 0x291f4b8 VA: 0x7594f374b8
	private Void _OnProgressBtnClick() { }
	// RVA: 0x291f5c4 VA: 0x7594f375c4
	private Void _CloseTargetInfo() { }
	// RVA: 0x291e56c VA: 0x7594f3656c
	private Void _InitController() { }
	// RVA: 0x291f680 VA: 0x7594f37680
	private Boolean _CheckUIStable() { }
	// RVA: 0x291f788 VA: 0x7594f37788
	private Void _OnMsgForwardToNextNodeSuc() { }
	// RVA: 0x291f898 VA: 0x7594f37898
	private Void _OnMsgForwardToNextNodeFail() { }
	// RVA: 0x291f938 VA: 0x7594f37938
	private Void _OnMsgBackToMap() { }
	// RVA: 0x291fa18 VA: 0x7594f37a18
	private Void _OnMsgUpdateTopMenu() { }
	// RVA: 0x291fb10 VA: 0x7594f37b10
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x291fca8 VA: 0x7594f37ca8
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x291fd54 VA: 0x7594f37d54
	private Void _OnMsgBackFromMissionDialog() { }
	// RVA: 0x291fe2c VA: 0x7594f37e2c
	public Void .ctor() { }
	// RVA: 0x291ffe8 VA: 0x7594f37fe8
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```