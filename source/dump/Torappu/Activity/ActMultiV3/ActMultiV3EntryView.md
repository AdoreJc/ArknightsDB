# ActMultiV3EntryView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Image _imgLogo`

- `Image _entryAnimLogo`

- `UIAtlasImage _imgEntryAnimBkg`

- `Text _textTitle`

- `Image _imgManualEntry`

- `Text _textMilestoneRank`

- `GameObject _pnlMilestoneProgress`

- `GameObject _pnlMilestoneComplete`

- `Image _imgMilestoneItemIcon`

- `Slider _sliderMilestone`

- `GameObject _pnlRewardProgress`

- `GameObject _pnlRewardComplete`

- `GameObject _pnlRewardActivityEnd`

- `Button _btnDailyReward`

- `Image _imgRewardProgress`

- `GameObject _pnlSquadInvalid`

- `GameObject _pnlSquadNotEnough`

- `GameObject _pnlStageActivityEnd`

- `GameObject _pnlMatchNotTrained`

- `GameObject _pnlMatchSquadInvalid`

- `GameObject _pnlMatchBanned`

- `GameObject _pnlMatchActivityEnd`

- `PnlMask _pnlMask`

- `GameObject _pnlStageEndTime`

- `GameObject _pnlRewardEndTime`

- `Text _textEndTime`

- `Text _textRemainTime`

- `Button _btnSquad`

- `Button _btnStage`

- `Button _btnTeamMatch`

- `Button _btnQuickMatch`

- `CanvasGroup _canvasTeamMatch`

- `CanvasGroup _canvasQuickMatch`

- `InputField _inputTeamId`

- `CanvasGroup _canvasJoinBtn`

- `RectTransform _bottomBarHolder`

- `Text _textBannedRemainTime`

- `GameObject _btnCreateRoomGO`

- `GameObject _btnJoinRoomGO`

- `GameObject _btnTrainingGO`

- `GameObject _trackpointPrefab`

- `RectTransform _manualTrackpointHolder`

- `RectTransform _milestoneTrackpointHolder`

- `RectTransform _squadTrackpointHolder`

- `GameObject _manualHasNewTitleMark`

- `GameObject _stageHasNewTitleMark`

- `GameObject _matchHasNewTitleMark`

- `GameObject _trainingHasNewTitleMark`

- `String m_cachedActId`

- `UIStateFinder m_stateFinder`

- `Boolean m_inited`

- `UISwitchTween m_joinBtnShowTween`

- `ActMultiV3EntryViewModel m_cachedViewModel`

- `ActMultiV3CommonBottomBar m_bottomBar`

- `GameObject m_manualTrackPoint`

- `GameObject m_milestoneTrackPoint`

- `GameObject m_squadTrackPoint`


## Methods

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Void RegisterTeamTutorialGo()`

- `Void UpdateTime(Single)`

- `Void Start()`

- `Void OnDestroy()`

- `Void _RenderTime(ActMultiV3LifeCycleViewModel)`

- `Void _RenderMileStone(ActMultiV3EntryMilestoneViewModel)`

- `Void _RenderDailyMission(ActMultiV3EntryViewModel)`

- `Void _RenderSquadAndStage(ActMultiV3EntryViewModel)`

- `Void _RenderTeamMatch(ActMultiV3EntryViewModel)`

- `Void _RenderRoom(ActMultiV3EntryViewModel)`

- `Void _RenderBannedStatus(ActMultiV3EntryViewModel)`

- `Void OnBtnManualClicked()`

- `Void OnBtnMilestoneClicked()`

- `Void OnBtnRewardClicked()`

- `Void OnBtnSquadClicked()`

- `Void OnBtnStageClicked()`

- `Void OnBtnTeamMatchClicked()`

- `Void OnBtnQuickMatchClicked()`

- `Void OnBtnMedalClicked()`

- `Void OnInputValueChanged()`

- `Void OnBtnCreateTeamClicked()`

- `Void OnBtnJoinTeamClicked()`

- `Void OnBtnTrainingRoomClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryView : DataBinder`1, ITimeWatcher
{
	private const String TITLE_FORMAT; // 0x0
	private Image _imgLogo; // 0x20
	private Image _entryAnimLogo; // 0x28
	private UIAtlasImage _imgEntryAnimBkg; // 0x30
	private Text _textTitle; // 0x38
	private Image _imgManualEntry; // 0x40
	private Text _textMilestoneRank; // 0x48
	private GameObject _pnlMilestoneProgress; // 0x50
	private GameObject _pnlMilestoneComplete; // 0x58
	private Image _imgMilestoneItemIcon; // 0x60
	private Slider _sliderMilestone; // 0x68
	private GameObject _pnlRewardProgress; // 0x70
	private GameObject _pnlRewardComplete; // 0x78
	private GameObject _pnlRewardActivityEnd; // 0x80
	private Button _btnDailyReward; // 0x88
	private Image _imgRewardProgress; // 0x90
	private GameObject _pnlSquadInvalid; // 0x98
	private GameObject _pnlSquadNotEnough; // 0xa0
	private GameObject _pnlStageActivityEnd; // 0xa8
	private GameObject _pnlMatchNotTrained; // 0xb0
	private GameObject _pnlMatchSquadInvalid; // 0xb8
	private GameObject _pnlMatchBanned; // 0xc0
	private GameObject _pnlMatchActivityEnd; // 0xc8
	private PnlMask _pnlMask; // 0xd0
	private GameObject _pnlStageEndTime; // 0xd8
	private GameObject _pnlRewardEndTime; // 0xe0
	private Text _textEndTime; // 0xe8
	private Text _textRemainTime; // 0xf0
	private Button _btnSquad; // 0xf8
	private Button _btnStage; // 0x100
	private Button _btnTeamMatch; // 0x108
	private Button _btnQuickMatch; // 0x110
	private CanvasGroup _canvasTeamMatch; // 0x118
	private CanvasGroup _canvasQuickMatch; // 0x120
	private InputField _inputTeamId; // 0x128
	private CanvasGroup _canvasJoinBtn; // 0x130
	private RectTransform _bottomBarHolder; // 0x138
	private Text _textBannedRemainTime; // 0x140
	private GameObject _btnCreateRoomGO; // 0x148
	private GameObject _btnJoinRoomGO; // 0x150
	private GameObject _btnTrainingGO; // 0x158
	private GameObject _trackpointPrefab; // 0x160
	private RectTransform _manualTrackpointHolder; // 0x168
	private RectTransform _milestoneTrackpointHolder; // 0x170
	private RectTransform _squadTrackpointHolder; // 0x178
	private GameObject _manualHasNewTitleMark; // 0x180
	private GameObject _stageHasNewTitleMark; // 0x188
	private GameObject _matchHasNewTitleMark; // 0x190
	private GameObject _trainingHasNewTitleMark; // 0x198
	private String m_cachedActId; // 0x1a0
	private UIStateFinder m_stateFinder; // 0x1a8
	private Boolean m_inited; // 0x1b8
	private UISwitchTween m_joinBtnShowTween; // 0x1c0
	private ActMultiV3EntryViewModel m_cachedViewModel; // 0x1c8
	private ActMultiV3CommonBottomBar m_bottomBar; // 0x1d0
	private GameObject m_manualTrackPoint; // 0x1d8
	private GameObject m_milestoneTrackPoint; // 0x1e0
	private GameObject m_squadTrackPoint; // 0x1e8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0_RegisterTeamTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__RenderTime; // 0x38
	private static DelegateBridge __Hotfix0__RenderMileStone; // 0x40
	private static DelegateBridge __Hotfix0__RenderDailyMission; // 0x48
	private static DelegateBridge __Hotfix0__RenderSquadAndStage; // 0x50
	private static DelegateBridge __Hotfix0__RenderTeamMatch; // 0x58
	private static DelegateBridge __Hotfix0__RenderRoom; // 0x60
	private static DelegateBridge __Hotfix0__RenderBannedStatus; // 0x68
	private static DelegateBridge __Hotfix0_OnBtnManualClicked; // 0x70
	private static DelegateBridge __Hotfix0_OnBtnMilestoneClicked; // 0x78
	private static DelegateBridge __Hotfix0_OnBtnRewardClicked; // 0x80
	private static DelegateBridge __Hotfix0_OnBtnSquadClicked; // 0x88
	private static DelegateBridge __Hotfix0_OnBtnStageClicked; // 0x90
	private static DelegateBridge __Hotfix0_OnBtnTeamMatchClicked; // 0x98
	private static DelegateBridge __Hotfix0_OnBtnQuickMatchClicked; // 0xa0
	private static DelegateBridge __Hotfix0_OnBtnMedalClicked; // 0xa8
	private static DelegateBridge __Hotfix0_OnInputValueChanged; // 0xb0
	private static DelegateBridge __Hotfix0_OnBtnCreateTeamClicked; // 0xb8
	private static DelegateBridge __Hotfix0_OnBtnJoinTeamClicked; // 0xc0
	private static DelegateBridge __Hotfix0_OnBtnTrainingRoomClicked; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x30eeb78 VA: 0x7595706b78
	private Void _InitIfNot() { }
	// RVA: 0x30eee84 VA: 0x7595706e84
	private Void _RegisterTutorialGo() { }
	// RVA: 0x30ed75c VA: 0x759570575c
	public Void RegisterTeamTutorialGo() { }
	// RVA: 0x30ef174 VA: 0x7595707174
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x30ef44c VA: 0x759570744c
	private Void Start() { }
	// RVA: 0x30ef4bc VA: 0x75957074bc
	private Void OnDestroy() { }
	// RVA: 0x30ef52c VA: 0x759570752c
	public override Void OnValueChanged(ActMultiV3EntryProperty property) { }
	// RVA: 0x30ef88c VA: 0x759570788c
	private Void _RenderTime(ActMultiV3LifeCycleViewModel lifeCycleModel) { }
	// RVA: 0x30efa48 VA: 0x7595707a48
	private Void _RenderMileStone(ActMultiV3EntryMilestoneViewModel milestoneModel) { }
	// RVA: 0x30efbbc VA: 0x7595707bbc
	private Void _RenderDailyMission(ActMultiV3EntryViewModel model) { }
	// RVA: 0x30efd04 VA: 0x7595707d04
	private Void _RenderSquadAndStage(ActMultiV3EntryViewModel model) { }
	// RVA: 0x30efe5c VA: 0x7595707e5c
	private Void _RenderTeamMatch(ActMultiV3EntryViewModel model) { }
	// RVA: 0x30effa8 VA: 0x7595707fa8
	private Void _RenderRoom(ActMultiV3EntryViewModel model) { }
	// RVA: 0x30ef1f4 VA: 0x75957071f4
	private Void _RenderBannedStatus(ActMultiV3EntryViewModel model) { }
	// RVA: 0x30f0188 VA: 0x7595708188
	public Void OnBtnManualClicked() { }
	// RVA: 0x30f023c VA: 0x759570823c
	public Void OnBtnMilestoneClicked() { }
	// RVA: 0x30f02f0 VA: 0x75957082f0
	public Void OnBtnRewardClicked() { }
	// RVA: 0x30f03a4 VA: 0x75957083a4
	public Void OnBtnSquadClicked() { }
	// RVA: 0x30f0458 VA: 0x7595708458
	public Void OnBtnStageClicked() { }
	// RVA: 0x30f050c VA: 0x759570850c
	public Void OnBtnTeamMatchClicked() { }
	// RVA: 0x30f05c0 VA: 0x75957085c0
	public Void OnBtnQuickMatchClicked() { }
	// RVA: 0x30f0674 VA: 0x7595708674
	public Void OnBtnMedalClicked() { }
	// RVA: 0x30f0728 VA: 0x7595708728
	public Void OnInputValueChanged() { }
	// RVA: 0x30f083c VA: 0x759570883c
	public Void OnBtnCreateTeamClicked() { }
	// RVA: 0x30f08f0 VA: 0x75957088f0
	public Void OnBtnJoinTeamClicked() { }
	// RVA: 0x30f09a4 VA: 0x75957089a4
	public Void OnBtnTrainingRoomClicked() { }
	// RVA: 0x30f0a58 VA: 0x7595708a58
	public Void .ctor() { }
}
```