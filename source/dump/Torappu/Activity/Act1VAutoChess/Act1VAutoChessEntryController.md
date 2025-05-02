# Act1VAutoChessEntryController

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `StateEngine _stateEngine`

- `CanvasGroup _canvasGroupBack`

- `Camera _cameraFishEye`

- `Camera _cameraFront`

- `CanvasGroup _canvasGroupFront`

- `CanvasGroup _canvasGroupFrontEntry`

- `CanvasGroup _canvasGroupEmpty`

- `RectTransform _dialogContainer`

- `Act1VAutoChessEntryAnimView _animView`

- `Act1VAutoChessEntryView _entryView`

- `String m_actId`

- `UICompDialogMgr m_dialogMgr`

- `Act1VAutoChessEntryProperty m_property`

- `Boolean m_blockingShowTypeChangeDuringService`

- `Coroutine m_popChessPoolAlertCoroutine`

- `FadeSwitchTween m_emptySwitchTween`


## Properties

- `String actId`

- `Boolean isPlaying`

- `ShowType showType`

- `ActState actState`

- `UICompDialogMgr dialogMgr`

- `TemplateActivityMilestoneGroupViewModel tmplMilestoneViewModel`


## Methods

- `String get_actId()`

- `Boolean get_isPlaying()`

- `ShowType get_showType()`

- `ActState get_actState()`

- `UICompDialogMgr get_dialogMgr()`

- `TemplateActivityMilestoneGroupViewModel get_tmplMilestoneViewModel()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnMainViewMessage(ShowType, Int32, ValueBundle)`

- `Void _OnStartGameViewMessage(ShowType, Int32, ValueBundle)`

- `Void _OnTeamInfoViewMessage(ShowType, Int32, ValueBundle)`

- `Void _OnModeChoiceViewMessage(ShowType, Int32, ValueBundle)`

- `Void _OnTopMenuViewMessage(ShowType, Int32, ValueBundle)`

- `IEnumerator ProcessServiceOnShow(Boolean, Boolean)`

- `IEnumerator EffectsOnHide(Boolean)`

- `Void SetShow(Boolean, Boolean, Boolean)`

- `Void SetShowType(ShowType, Boolean)`

- `Void RefreshData()`

- `TemplateMissionInputParam CreateTemplateMissionInputParam()`

- `Void _InitController()`

- `Void _OnTopMenuViewReturnBtnClick()`

- `Void _OnTopMenuViewLeaveBtnClick()`

- `Boolean _IsBasicToShowCheckFail(ShowType, ShowType)`

- `Boolean _IsToSubViewCheckFail(ShowType, ShowType)`

- `Boolean _IsToExitCheckFail(ShowType, ShowType)`

- `Boolean _CheckIsTransiting()`

- `Void _SendSyncChessPoolService(Boolean)`

- `Void _OnSyncChessPoolProceedOnPageShow(Act1VAutoChessSyncChessPoolResponse)`

- `Void _OnSyncChessPoolProceed(Act1VAutoChessSyncChessPoolResponse)`

- `IEnumerator _WaitToPopChessPoolAlertCoroutine(String, Boolean)`

- `Void _OnMainViewTeamInfoBtnClick()`

- `Void _OnMainViewStartGameBtnClick()`

- `Void _OnMainViewQuitGameBtnClick()`

- `Void _OnMainViewChessShopBtnClick()`

- `Void _OnMainViewModeChoiceBtnClick()`

- `Void _OpenDailyDialog()`

- `Void _OpenRewardRuleDialog()`

- `Void _OnMissionBtnClick()`

- `Void _OnMilestoneBtnClick()`

- `Void _OnMedalBtnClick()`

- `Void _OnStartGameSelectBand(ValueBundle)`

- `Void _OnStartGameSwitchShow()`

- `Void _OnChooseBandConfirm()`

- `Void _OnStartGameReleaseBlocking()`

- `Void _ModeChoiceViewFocusOnMode(String, Boolean)`

- `Void _ModeChoiceViewConfirmMode(String)`

- `Void _OnTeamInfoViewSwitchTeam(ValueBundle)`

- `Void _OnTeamInfoViewClickTeamCard(ValueBundle)`

- `Void _OnTeamInfoViewClickEnemyHandBookInfo()`

- `Void OnJumpToEnemyHandBook(IStateBean)`

- `Boolean _TryToTriggerPageShowAvg()`

- `Boolean _TriggerAct1VAutoChessEntrySysAvg()`

- `Void _OnSysAvgFinish(Story)`

- `Boolean _TryTriggerAct1VAutoChessShopAvg()`

- `IEnumerator _WaitToTriggerStartGameAvg()`

- `Void _SendStartGameService()`

- `Void _OnStartGameServiceProceed(Act1VAutoChessStartGameResponse)`

- `Void _SendChooseBandService()`

- `Void _EnterBattle()`

- `Boolean _GenerateBattleParam(ActivityAutoChessVerify1Data, AutoChessGame, out)`

- `Act1VAutoChessModeData _FetchModeData(ActivityAutoChessVerify1Data, String)`

- `Void _SettleGameFromBattle()`

- `Void _OnSettleGameFromBattleServiceProceed(Act1VAutoChessSettleGameResponse)`

- `Void _SendSettleGameService(Boolean)`

- `Void _OnSettleGameServiceProceedShowSettle(Act1VAutoChessSettleGameResponse)`

- `Void _OnSettleGameServiceProceedToSyncChessPool(Act1VAutoChessSettleGameResponse)`

- `Boolean _OnEnterPageServiceBlocked(ResponseError)`

- `IEnumerator _WaitToClosePage()`

- `Boolean <EffectsOnHide>b__60_0()`

- `Void <_SendChooseBandService>b__103_0(Act1VAutoChessChooseBandResponse)`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryController : PageSingleComponent, IValueMsgReceiver
{
	private StateEngine _stateEngine; // 0x20
	private CanvasGroup _canvasGroupBack; // 0x28
	private Camera _cameraFishEye; // 0x30
	private Camera _cameraFront; // 0x38
	private CanvasGroup _canvasGroupFront; // 0x40
	private CanvasGroup _canvasGroupFrontEntry; // 0x48
	private CanvasGroup _canvasGroupEmpty; // 0x50
	private RectTransform _dialogContainer; // 0x58
	private Act1VAutoChessEntryAnimView _animView; // 0x60
	private Act1VAutoChessEntryView _entryView; // 0x68
	private String m_actId; // 0x70
	private UICompDialogMgr m_dialogMgr; // 0x78
	private Act1VAutoChessEntryProperty m_property; // 0x80
	private Dictionary`2 _forceToEnemyListCacheDict; // 0x88
	private Boolean m_blockingShowTypeChangeDuringService; // 0x90
	private Coroutine m_popChessPoolAlertCoroutine; // 0x98
	private const Int32 CHESS_CHAR_CHANGE_INTO_THREHOLD; // 0x0
	private FadeSwitchTween m_emptySwitchTween; // 0xa0
	public const Int32 MSG_MAIN_VIEW_ON_START_GAME_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_CHESS_POOL_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_MODE_CHOICE_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_TEAM_INFO_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_QUIT_GAME_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_DAILY_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_REWARD_RULE_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_MISSION_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_MILESTONE_BTN_CLICK; // 0x0
	public const Int32 MSG_MAIN_VIEW_ON_MEDAL_BTN_CLICK; // 0x0
	public const Int32 MSG_START_GAME_ON_SELECT_BAND; // 0x0
	public const Int32 MSG_START_GAME_ON_SWITCH_SHOW; // 0x0
	public const Int32 MSG_START_GAME_ON_START_CONFIRM; // 0x0
	public const Int32 MSG_START_GAME_RELEASE_BLOCKING; // 0x0
	public const Int32 MSG_TEAM_INFO_VIEW_ON_SWITCH_TEAM_CLICK; // 0x0
	public const Int32 MSG_TEAM_INFO_VIEW_ON_CLICK_TEAM_CARD; // 0x0
	public const Int32 MSG_TEAM_INFO_VIEW_ON_CLICK_ENEMY_HANDBOOK_INFO; // 0x0
	public const Int32 MSG_MODE_CHOICE_ON_FOCUS; // 0x0
	public const Int32 MSG_MODE_CHOICE_ON_CONFIRM; // 0x0
	public const Int32 MSG_RETURN_BTN_CLICK; // 0x0
	public const Int32 MSG_LEAVE_BTN_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_get_actState; // 0x18
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x20
	private static DelegateBridge __Hotfix0_get_tmplMilestoneViewModel; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge __Hotfix0__OnMainViewMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnStartGameViewMessage; // 0x40
	private static DelegateBridge __Hotfix0__OnTeamInfoViewMessage; // 0x48
	private static DelegateBridge __Hotfix0__OnModeChoiceViewMessage; // 0x50
	private static DelegateBridge __Hotfix0__OnTopMenuViewMessage; // 0x58
	private static DelegateBridge __Hotfix0_OnCreate; // 0x60
	private static DelegateBridge __Hotfix0_ProcessServiceOnShow; // 0x68
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x70
	private static DelegateBridge __Hotfix0_SetShow; // 0x78
	private static DelegateBridge __Hotfix0_SetShowType; // 0x80
	private static DelegateBridge __Hotfix0_RefreshData; // 0x88
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x90
	private static DelegateBridge __Hotfix0__InitController; // 0x98
	private static DelegateBridge __Hotfix0__OnTopMenuViewReturnBtnClick; // 0xa0
	private static DelegateBridge __Hotfix0__OnTopMenuViewLeaveBtnClick; // 0xa8
	private static DelegateBridge __Hotfix0__IsBasicToShowCheckFail; // 0xb0
	private static DelegateBridge __Hotfix0__IsToSubViewCheckFail; // 0xb8
	private static DelegateBridge __Hotfix0__IsToExitCheckFail; // 0xc0
	private static DelegateBridge __Hotfix0__CheckIsTransiting; // 0xc8
	private static DelegateBridge __Hotfix0__SendSyncChessPoolService; // 0xd0
	private static DelegateBridge __Hotfix0__OnSyncChessPoolProceedOnPageShow; // 0xd8
	private static DelegateBridge __Hotfix0__OnSyncChessPoolProceed; // 0xe0
	private static DelegateBridge __Hotfix0__WaitToPopChessPoolAlertCoroutine; // 0xe8
	private static DelegateBridge __Hotfix0__OnMainViewTeamInfoBtnClick; // 0xf0
	private static DelegateBridge __Hotfix0__OnMainViewStartGameBtnClick; // 0xf8
	private static DelegateBridge __Hotfix0__OnMainViewQuitGameBtnClick; // 0x100
	private static DelegateBridge __Hotfix0__OnMainViewChessShopBtnClick; // 0x108
	private static DelegateBridge __Hotfix0__OnMainViewModeChoiceBtnClick; // 0x110
	private static DelegateBridge __Hotfix0__OpenDailyDialog; // 0x118
	private static DelegateBridge __Hotfix0__OpenRewardRuleDialog; // 0x120
	private static DelegateBridge __Hotfix0__OnMissionBtnClick; // 0x128
	private static DelegateBridge __Hotfix0__OnMilestoneBtnClick; // 0x130
	private static DelegateBridge __Hotfix0__OnMedalBtnClick; // 0x138
	private static DelegateBridge __Hotfix0__OnStartGameSelectBand; // 0x140
	private static DelegateBridge __Hotfix0__OnStartGameSwitchShow; // 0x148
	private static DelegateBridge __Hotfix0__OnChooseBandConfirm; // 0x150
	private static DelegateBridge __Hotfix0__OnStartGameReleaseBlocking; // 0x158
	private static DelegateBridge __Hotfix0__ModeChoiceViewFocusOnMode; // 0x160
	private static DelegateBridge __Hotfix0__ModeChoiceViewConfirmMode; // 0x168
	private static DelegateBridge __Hotfix0__OnTeamInfoViewSwitchTeam; // 0x170
	private static DelegateBridge __Hotfix0__OnTeamInfoViewClickTeamCard; // 0x178
	private static DelegateBridge __Hotfix0__OnTeamInfoViewClickEnemyHandBookInfo; // 0x180
	private static DelegateBridge __Hotfix0_OnJumpToEnemyHandBook; // 0x188
	private static DelegateBridge __Hotfix0__TryToTriggerPageShowAvg; // 0x190
	private static DelegateBridge __Hotfix0__TriggerAct1VAutoChessEntrySysAvg; // 0x198
	private static DelegateBridge __Hotfix0__OnSysAvgFinish; // 0x1a0
	private static DelegateBridge __Hotfix0__TryTriggerAct1VAutoChessShopAvg; // 0x1a8
	private static DelegateBridge __Hotfix0__WaitToTriggerStartGameAvg; // 0x1b0
	private static DelegateBridge __Hotfix0__SendStartGameService; // 0x1b8
	private static DelegateBridge __Hotfix0__OnStartGameServiceProceed; // 0x1c0
	private static DelegateBridge __Hotfix0__SendChooseBandService; // 0x1c8
	private static DelegateBridge __Hotfix0__EnterBattle; // 0x1d0
	private static DelegateBridge __Hotfix0__GenerateBattleParam; // 0x1d8
	private static DelegateBridge __Hotfix0__FetchModeData; // 0x1e0
	private static DelegateBridge __Hotfix0__SettleGameFromBattle; // 0x1e8
	private static DelegateBridge __Hotfix0__OnSettleGameFromBattleServiceProceed; // 0x1f0
	private static DelegateBridge __Hotfix0__SendSettleGameService; // 0x1f8
	private static DelegateBridge __Hotfix0__OnSettleGameServiceProceedShowSettle; // 0x200
	private static DelegateBridge __Hotfix0__OnSettleGameServiceProceedToSyncChessPool; // 0x208
	private static DelegateBridge __Hotfix0__OnEnterPageServiceBlocked; // 0x210
	private static DelegateBridge __Hotfix0__WaitToClosePage; // 0x218
	private static DelegateBridge _c__Hotfix0_ctor; // 0x220

	public String actId { get; }
	public Boolean isPlaying { get; }
	public ShowType showType { get; }
	public ActState actState { get; }
	public UICompDialogMgr dialogMgr { get; }
	public TemplateActivityMilestoneGroupViewModel tmplMilestoneViewModel { get; }

	// RVA: 0x3333954 VA: 0x759594b954
	public String get_actId() { }
	// RVA: 0x33339bc VA: 0x759594b9bc
	public Boolean get_isPlaying() { }
	// RVA: 0x3333b00 VA: 0x759594bb00
	public ShowType get_showType() { }
	// RVA: 0x3333b94 VA: 0x759594bb94
	public ActState get_actState() { }
	// RVA: 0x3333c58 VA: 0x759594bc58
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x3333cc0 VA: 0x759594bcc0
	public TemplateActivityMilestoneGroupViewModel get_tmplMilestoneViewModel() { }
	// RVA: 0x3333d78 VA: 0x759594bd78
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3333ea4 VA: 0x759594bea4
	private Void _OnMainViewMessage(ShowType curShowType, Int32 key, ValueBundle msg) { }
	// RVA: 0x3334080 VA: 0x759594c080
	private Void _OnStartGameViewMessage(ShowType curShowType, Int32 key, ValueBundle msg) { }
	// RVA: 0x33341ac VA: 0x759594c1ac
	private Void _OnTeamInfoViewMessage(ShowType curShowType, Int32 key, ValueBundle msg) { }
	// RVA: 0x33342ac VA: 0x759594c2ac
	private Void _OnModeChoiceViewMessage(ShowType curShowType, Int32 key, ValueBundle msg) { }
	// RVA: 0x33343a0 VA: 0x759594c3a0
	private Void _OnTopMenuViewMessage(ShowType curShowType, Int32 key, ValueBundle msg) { }
	// RVA: 0x3335f64 VA: 0x759594df64
	protected override Void OnCreate() { }
	// RVA: 0x33364b0 VA: 0x759594e4b0
	public IEnumerator ProcessServiceOnShow(Boolean isFromBattle, Boolean isFromStack) { }
	// RVA: 0x33365b0 VA: 0x759594e5b0
	public IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x333638c VA: 0x759594e38c
	public Void SetShow(Boolean isShow, Boolean setFrontAllUI, Boolean setEmptyStateMask) { }
	// RVA: 0x33366a0 VA: 0x759594e6a0
	public Void SetShowType(ShowType toShowType, Boolean fastMode) { }
	// RVA: 0x3336e3c VA: 0x759594ee3c
	public Void RefreshData() { }
	// RVA: 0x3336f04 VA: 0x759594ef04
	public TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x3335fec VA: 0x759594dfec
	private Void _InitController() { }
	// RVA: 0x3335d78 VA: 0x759594dd78
	private Void _OnTopMenuViewReturnBtnClick() { }
	// RVA: 0x3335ebc VA: 0x759594debc
	private Void _OnTopMenuViewLeaveBtnClick() { }
	// RVA: 0x33368f0 VA: 0x759594e8f0
	private Boolean _IsBasicToShowCheckFail(ShowType curType, ShowType toType) { }
	// RVA: 0x3336994 VA: 0x759594e994
	private Boolean _IsToSubViewCheckFail(ShowType curType, ShowType toType) { }
	// RVA: 0x3336a2c VA: 0x759594ea2c
	private Boolean _IsToExitCheckFail(ShowType curType, ShowType toType) { }
	// RVA: 0x3337288 VA: 0x759594f288
	private Boolean _CheckIsTransiting() { }
	// RVA: 0x3336ac0 VA: 0x759594eac0
	private Void _SendSyncChessPoolService(Boolean onPageShow) { }
	// RVA: 0x3337380 VA: 0x759594f380
	private Void _OnSyncChessPoolProceedOnPageShow(Act1VAutoChessSyncChessPoolResponse response) { }
	// RVA: 0x3337428 VA: 0x759594f428
	private Void _OnSyncChessPoolProceed(Act1VAutoChessSyncChessPoolResponse response) { }
	// RVA: 0x3337b3c VA: 0x759594fb3c
	private IEnumerator _WaitToPopChessPoolAlertCoroutine(String charNameStr, Boolean moreThenThree) { }
	// RVA: 0x33349b8 VA: 0x759594c9b8
	private Void _OnMainViewTeamInfoBtnClick() { }
	// RVA: 0x3334488 VA: 0x759594c488
	private Void _OnMainViewStartGameBtnClick() { }
	// RVA: 0x3334cdc VA: 0x759594ccdc
	private Void _OnMainViewQuitGameBtnClick() { }
	// RVA: 0x333478c VA: 0x759594c78c
	private Void _OnMainViewChessShopBtnClick() { }
	// RVA: 0x3334894 VA: 0x759594c894
	private Void _OnMainViewModeChoiceBtnClick() { }
	// RVA: 0x3334a28 VA: 0x759594ca28
	private Void _OpenDailyDialog() { }
	// RVA: 0x3334b98 VA: 0x759594cb98
	private Void _OpenRewardRuleDialog() { }
	// RVA: 0x3334f6c VA: 0x759594cf6c
	private Void _OnMissionBtnClick() { }
	// RVA: 0x33350a0 VA: 0x759594d0a0
	private Void _OnMilestoneBtnClick() { }
	// RVA: 0x33351d4 VA: 0x759594d1d4
	private Void _OnMedalBtnClick() { }
	// RVA: 0x33353b8 VA: 0x759594d3b8
	private Void _OnStartGameSelectBand(ValueBundle msg) { }
	// RVA: 0x33354f8 VA: 0x759594d4f8
	private Void _OnStartGameSwitchShow() { }
	// RVA: 0x33355e4 VA: 0x759594d5e4
	private Void _OnChooseBandConfirm() { }
	// RVA: 0x3335688 VA: 0x759594d688
	private Void _OnStartGameReleaseBlocking() { }
	// RVA: 0x3335b78 VA: 0x759594db78
	private Void _ModeChoiceViewFocusOnMode(String modeId, Boolean isFromItemClick) { }
	// RVA: 0x3335ca8 VA: 0x759594dca8
	private Void _ModeChoiceViewConfirmMode(String modeId) { }
	// RVA: 0x3335928 VA: 0x759594d928
	private Void _OnTeamInfoViewSwitchTeam(ValueBundle msg) { }
	// RVA: 0x3335774 VA: 0x759594d774
	private Void _OnTeamInfoViewClickTeamCard(ValueBundle msg) { }
	// RVA: 0x3335a9c VA: 0x759594da9c
	private Void _OnTeamInfoViewClickEnemyHandBookInfo() { }
	// RVA: 0x3338494 VA: 0x7595950494
	public Void OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x3337a08 VA: 0x759594fa08
	private Boolean _TryToTriggerPageShowAvg() { }
	// RVA: 0x33389c0 VA: 0x75959509c0
	private Boolean _TriggerAct1VAutoChessEntrySysAvg() { }
	// RVA: 0x3338b10 VA: 0x7595950b10
	private Void _OnSysAvgFinish(Story story) { }
	// RVA: 0x3338a90 VA: 0x7595950a90
	private Boolean _TryTriggerAct1VAutoChessShopAvg() { }
	// RVA: 0x3336d90 VA: 0x759594ed90
	private IEnumerator _WaitToTriggerStartGameAvg() { }
	// RVA: 0x3337c44 VA: 0x759594fc44
	private Void _SendStartGameService() { }
	// RVA: 0x3338bd8 VA: 0x7595950bd8
	private Void _OnStartGameServiceProceed(Act1VAutoChessStartGameResponse response) { }
	// RVA: 0x3338234 VA: 0x7595950234
	private Void _SendChooseBandService() { }
	// RVA: 0x33380d0 VA: 0x75959500d0
	private Void _EnterBattle() { }
	// RVA: 0x3338d2c VA: 0x7595950d2c
	private Boolean _GenerateBattleParam(ActivityAutoChessVerify1Data actData, AutoChessGame game, out Param param) { }
	// RVA: 0x333917c VA: 0x759595117c
	private Act1VAutoChessModeData _FetchModeData(ActivityAutoChessVerify1Data gameData, String modeId) { }
	// RVA: 0x333931c VA: 0x759595131c
	private Void _SettleGameFromBattle() { }
	// RVA: 0x3339564 VA: 0x7595951564
	private Void _OnSettleGameFromBattleServiceProceed(Act1VAutoChessSettleGameResponse response) { }
	// RVA: 0x3337eb0 VA: 0x759594feb0
	private Void _SendSettleGameService(Boolean showSettle) { }
	// RVA: 0x33396e4 VA: 0x75959516e4
	private Void _OnSettleGameServiceProceedShowSettle(Act1VAutoChessSettleGameResponse response) { }
	// RVA: 0x3339854 VA: 0x7595951854
	private Void _OnSettleGameServiceProceedToSyncChessPool(Act1VAutoChessSettleGameResponse response) { }
	// RVA: 0x33398d4 VA: 0x75959518d4
	private Boolean _OnEnterPageServiceBlocked(ResponseError error) { }
	// RVA: 0x3339994 VA: 0x7595951994
	private IEnumerator _WaitToClosePage() { }
	// RVA: 0x3339a68 VA: 0x7595951a68
	public Void .ctor() { }
	// RVA: 0x3339b2c VA: 0x7595951b2c
	private Boolean <EffectsOnHide>b__60_0() { }
	// RVA: 0x3339b30 VA: 0x7595951b30
	private Void <_SendChooseBandService>b__103_0(Act1VAutoChessChooseBandResponse response) { }
	// RVA: 0x3339b34 VA: 0x7595951b34
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```