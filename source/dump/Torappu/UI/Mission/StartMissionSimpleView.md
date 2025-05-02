# StartMissionSimpleView

**Namespace:** `Torappu.UI.Mission`


## Fields

- `GameObject _normalPartGo`

- `GameObject _emptyPartGo`

- `GameObject _allCompleteInfoGo`

- `GameObject _unlockInfoGo`

- `GameObject _fullOpenUnavailGo`

- `GameObject _fullOpenAvailGo`

- `GameObject _fullOpenRemainGo`

- `Text _textFullOpenRemainTime`

- `GameObject _fullOpenActiveTimeGo`

- `GameObject _fullOpenPauseTimeGo`

- `Color _colorFullOpenActiveTime`

- `Color _colorFullOpenPauseTime`

- `Text _textUnlockTitle`

- `Text _textUnlockDesc`

- `Transform _taskContainer`

- `StartMissionTaskStart _tagObj`

- `Text _missionText`

- `MissionRewardPreviewItem _rewardItem`

- `Transform _maskContainer`

- `GameObject _missionGroupButton`

- `GameObject _unfinishedBgPanel`

- `GameObject _unfinishedPanel`

- `GameObject _finishedBgPanel`

- `GameObject _finishedPanel`

- `TextGroupWithPadding _phaseRewardCountLabelGroup`

- `GridLayoutGroup _gridLayout`

- `RectTransform _rectContainer`

- `Boolean m_isFirstRender`

- `MissionGroup m_missionGroup`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Awake()`

- `Void OnMissionGroupButtonPressed()`

- `Void _RenderBtnResFullOpen()`

- `Void _RenderEmptyView(Boolean, Boolean)`

- `Void _RenderNormalView()`

- `Void _InitView()`

- `Void _RefreshView()`

- `Void _RenderGroupInfo()`

- `Void _AdjustGridCellSize(CanvasScaler)`

- `Void EventOnPreviewOpen()`

- `Void EventOnResDialogOpen()`

- `Boolean <>xLuaBaseProxy_IsToBeShown(MissionModel)`

- `Void <>xLuaBaseProxy_RefreshView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class StartMissionSimpleView : MissionSinglePage
{
	private GameObject _normalPartGo; // 0x30
	private GameObject _emptyPartGo; // 0x38
	private GameObject _allCompleteInfoGo; // 0x40
	private GameObject _unlockInfoGo; // 0x48
	private GameObject _fullOpenUnavailGo; // 0x50
	private GameObject _fullOpenAvailGo; // 0x58
	private GameObject _fullOpenRemainGo; // 0x60
	private Text _textFullOpenRemainTime; // 0x68
	private GameObject _fullOpenActiveTimeGo; // 0x70
	private GameObject _fullOpenPauseTimeGo; // 0x78
	private Color _colorFullOpenActiveTime; // 0x80
	private Color _colorFullOpenPauseTime; // 0x90
	private Text _textUnlockTitle; // 0xa0
	private Text _textUnlockDesc; // 0xa8
	private Transform _taskContainer; // 0xb0
	private StartMissionTaskStart _tagObj; // 0xb8
	private Text _missionText; // 0xc0
	private MissionRewardPreviewItem _rewardItem; // 0xc8
	private Transform _maskContainer; // 0xd0
	private GameObject _missionGroupButton; // 0xd8
	private GameObject _unfinishedBgPanel; // 0xe0
	private GameObject _unfinishedPanel; // 0xe8
	private GameObject _finishedBgPanel; // 0xf0
	private GameObject _finishedPanel; // 0xf8
	private TextGroupWithPadding _phaseRewardCountLabelGroup; // 0x100
	private Text[] _phaseRewardNameLabels; // 0x108
	private GridLayoutGroup _gridLayout; // 0x110
	private RectTransform _rectContainer; // 0x118
	private static readonly Vector2 cellSizeDefault; // 0x0
	private static readonly Vector2 cellSizeExpand; // 0x8
	private Boolean m_isFirstRender; // 0x120
	private MissionGroup m_missionGroup; // 0x128
	private Dictionary`2 m_missionTasks; // 0x130
	private UIPageFinder m_pageFinder; // 0x138
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0_OnMissionGroupButtonPressed; // 0x18
	private static DelegateBridge __Hotfix0_IsToBeShown; // 0x20
	private static DelegateBridge __Hotfix0_RefreshView; // 0x28
	private static DelegateBridge __Hotfix0__RenderBtnResFullOpen; // 0x30
	private static DelegateBridge __Hotfix0__RenderEmptyView; // 0x38
	private static DelegateBridge __Hotfix0__RenderNormalView; // 0x40
	private static DelegateBridge __Hotfix0__InitView; // 0x48
	private static DelegateBridge __Hotfix0__RefreshView; // 0x50
	private static DelegateBridge __Hotfix0__RenderGroupInfo; // 0x58
	private static DelegateBridge __Hotfix0__AdjustGridCellSize; // 0x60
	private static DelegateBridge __Hotfix0_EventOnPreviewOpen; // 0x68
	private static DelegateBridge __Hotfix0_EventOnResDialogOpen; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2744564 VA: 0x7594d5c564
	private Void Awake() { }
	// RVA: 0x2744848 VA: 0x7594d5c848
	public Void OnMissionGroupButtonPressed() { }
	// RVA: 0x27448d8 VA: 0x7594d5c8d8
	public override Boolean IsToBeShown(MissionModel stateBean) { }
	// RVA: 0x27449c0 VA: 0x7594d5c9c0
	protected override Void RefreshView() { }
	// RVA: 0x2744cf0 VA: 0x7594d5ccf0
	private Void _RenderBtnResFullOpen() { }
	// RVA: 0x2744b04 VA: 0x7594d5cb04
	private Void _RenderEmptyView(Boolean isMissionLock, Boolean isFullOpenAndAllComplete) { }
	// RVA: 0x2744c5c VA: 0x7594d5cc5c
	private Void _RenderNormalView() { }
	// RVA: 0x2744f38 VA: 0x7594d5cf38
	private Void _InitView() { }
	// RVA: 0x27451b4 VA: 0x7594d5d1b4
	private Void _RefreshView() { }
	// RVA: 0x2745ae8 VA: 0x7594d5dae8
	private Void _RenderGroupInfo() { }
	// RVA: 0x27455d4 VA: 0x7594d5d5d4
	private Void _AdjustGridCellSize(CanvasScaler nullableScaler) { }
	// RVA: 0x2745ff8 VA: 0x7594d5dff8
	public Void EventOnPreviewOpen() { }
	// RVA: 0x27460ac VA: 0x7594d5e0ac
	public Void EventOnResDialogOpen() { }
	// RVA: 0x2746160 VA: 0x7594d5e160
	public Void .ctor() { }
	// RVA: 0x2746238 VA: 0x7594d5e238
	private static Void .cctor() { }
	// RVA: 0x274629c VA: 0x7594d5e29c
	private Boolean <>xLuaBaseProxy_IsToBeShown(MissionModel P0) { }
	// RVA: 0x27462a0 VA: 0x7594d5e2a0
	private Void <>xLuaBaseProxy_RefreshView() { }
}
```