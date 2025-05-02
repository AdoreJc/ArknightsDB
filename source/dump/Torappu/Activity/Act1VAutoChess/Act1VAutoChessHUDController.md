# Act1VAutoChessHUDController

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `StateEngine _stateEngine`

- `Act1VAutoChessHUDView _hudView`

- `Text _time`

- `Color _timeNormal`

- `Color _timeOut`

- `RectTransform _prepareBackHotspot`

- `RectTransform _battleBackHotspot`

- `Int32 m_replaceDlg`

- `Int32 m_quitDlg`

- `Int32 m_goldLeftDlg`

- `String m_actId`

- `Act1VAutoChessBattleHUDPage m_page`

- `SeqNumChecker m_talentChecker`

- `SeqNumChecker m_battleRoundFinishChecker`

- `SeqNumChecker m_charChecker`

- `SeqNumChecker m_refreshChecker`

- `Act1VAutoChessHUDProperty m_prop`

- `Boolean m_isTimeOut`

- `Int32 m_cachedTime`

- `Coroutine m_tutorialWaitCoroutine`


## Properties

- `HUDState hudState`


## Methods

- `HUDState get_hudState()`

- `Void _LoadData()`

- `Void _OnBackPress()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSelfCampClick()`

- `Void _OnSelfCampClickImpl()`

- `Void _OnEnemyCampClick()`

- `Void _OnEnemyCampClickImpl()`

- `Void _OnTipCampClick()`

- `Void _OnCloseCampClick()`

- `Void _OnCloseCampImpl(Boolean)`

- `Void _OnMenuClick()`

- `Void _OnSpeedClick()`

- `Void _OnPauseClick()`

- `Boolean _CheckGameBattleState()`

- `Void _OnStartBattle()`

- `Void _OnExitGame()`

- `Void _OnSelectTalent(ValueBundle)`

- `Void _OnConfirmTalent()`

- `Void _OnRoundEndAnimComplete()`

- `Void _OnRoundStartAnimComplete()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _HandleReplaceEquip(Output)`

- `Void _OpenQuitDlg()`

- `Void _HandleQuitDlg(Int32)`

- `Boolean _TryOpenGoldLeftDlg()`

- `Void _OnGainGoldCheckBoxConfirm()`

- `Void _HandleGoldLeftDlg(Int32)`

- `Void _InitBattleEvent()`

- `Void _HandleStartPerpare(Object)`

- `Void _HandleStartBatlle(Object)`

- `Void _HandleRoundInterval(Object)`

- `Void _HandleCommonStateChange(HUDState)`

- `Void _HandleEnemyEscape(Object)`

- `Void _SetTimeColorIfNecessary(Boolean)`

- `Void _HandleTimeChange(Object)`

- `Void TriggerPrepareEnemyEffectHint(String, String)`

- `Void _OnPrepareHintImp(String, String)`

- `Void _HandleBattleHint(Object)`

- `Void _HandleGameSpeedChange(Object)`

- `Void _HandleGamePause(Object)`

- `Void _HandleReplaceDialog(Object)`

- `Void _HandleDataChanged(Object)`

- `Boolean _HandleCharDeployChanged(AutoChessDataCenter, Act1VAutoChessHUDViewModel)`

- `Void _TryTriggerAfterChooseBuffTutorial()`

- `IEnumerator _WaitAfterChooseBuffTutorialReady()`

- `Void _RaiseTutorialPrepareEnterSignal()`

- `Void _SetState(HUDState)`

- `Void _OnEnterState(HUDState)`

- `Void _OnEnterRoundBattle()`

- `Void _HandleStartRound()`

- `Void _OnEnterPrepareAnimFinish()`

- `Void _OnEnterPrepareOpenTalent()`

- `Void _OnEnterPrepareTriggerTutorial()`

- `Void _TryTriggerTalentTutorial()`

- `Void _TryTriggerPhase3Tutorial()`

- `Void _OnEnterPrepareOpenEnemy()`

- `Void _CloseAllDialog()`

- `Void _UpdateData(Boolean)`

- `Void _UpdateRoundStartEnd(RoundBattleFinishResponseViewModel)`

- `SpeedLevel _ClampSpeedLevel(SpeedLevel)`

- `Void _LoadCamp()`

- `Void _RefreshCamp()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDController : PageSingleComponent, IValueMsgReceiver, ICompDialogCallBack
{
	private StateEngine _stateEngine; // 0x20
	private Act1VAutoChessHUDView _hudView; // 0x28
	private Text _time; // 0x30
	private Color _timeNormal; // 0x38
	private Color _timeOut; // 0x48
	private RectTransform _prepareBackHotspot; // 0x58
	private RectTransform _battleBackHotspot; // 0x60
	private Int32 m_replaceDlg; // 0x68
	private Int32 m_quitDlg; // 0x6c
	private Int32 m_goldLeftDlg; // 0x70
	private String m_actId; // 0x78
	private Act1VAutoChessBattleHUDPage m_page; // 0x80
	private SeqNumChecker m_talentChecker; // 0x88
	private SeqNumChecker m_battleRoundFinishChecker; // 0x90
	private SeqNumChecker m_charChecker; // 0x98
	private SeqNumChecker m_refreshChecker; // 0xa0
	private Act1VAutoChessHUDProperty m_prop; // 0xa8
	public const Int32 ON_SELF_CAMP_CLICK; // 0x0
	public const Int32 ON_ENEMY_CAMP_CLICK; // 0x0
	public const Int32 ON_CLOSE_CAMP_CLICK; // 0x0
	public const Int32 ON_MENU_CLICK; // 0x0
	public const Int32 ON_SPEED_CLICK; // 0x0
	public const Int32 ON_PAUSE_CLICK; // 0x0
	public const Int32 ON_START_BATTLE_CLICK; // 0x0
	public const Int32 ON_EXIT_GAME_CLICK; // 0x0
	public const Int32 ON_SELECT_TALENT; // 0x0
	public const Int32 ON_CONFIRM_TALENT; // 0x0
	public const Int32 ON_START_TO_PREPARE_ANIM_FINISH; // 0x0
	public const Int32 ON_TIP_CAMP_CLICK; // 0x0
	public const Int32 ON_ROUND_END_ANIM_COMPLETE; // 0x0
	public const Int32 ON_ROUND_START_ANIM_COMPLETE; // 0x0
	private Boolean m_isTimeOut; // 0xb0
	private Int32 m_cachedTime; // 0xb4
	private Coroutine m_tutorialWaitCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0_get_hudState; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0__LoadData; // 0x18
	private static DelegateBridge __Hotfix0__OnBackPress; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnSelfCampClick; // 0x30
	private static DelegateBridge __Hotfix0__OnSelfCampClickImpl; // 0x38
	private static DelegateBridge __Hotfix0__OnEnemyCampClick; // 0x40
	private static DelegateBridge __Hotfix0__OnEnemyCampClickImpl; // 0x48
	private static DelegateBridge __Hotfix0__OnTipCampClick; // 0x50
	private static DelegateBridge __Hotfix0__OnCloseCampClick; // 0x58
	private static DelegateBridge __Hotfix0__OnCloseCampImpl; // 0x60
	private static DelegateBridge __Hotfix0__OnMenuClick; // 0x68
	private static DelegateBridge __Hotfix0__OnSpeedClick; // 0x70
	private static DelegateBridge __Hotfix0__OnPauseClick; // 0x78
	private static DelegateBridge __Hotfix0__CheckGameBattleState; // 0x80
	private static DelegateBridge __Hotfix0__OnStartBattle; // 0x88
	private static DelegateBridge __Hotfix0__OnExitGame; // 0x90
	private static DelegateBridge __Hotfix0__OnSelectTalent; // 0x98
	private static DelegateBridge __Hotfix0__OnConfirmTalent; // 0xa0
	private static DelegateBridge __Hotfix0__OnRoundEndAnimComplete; // 0xa8
	private static DelegateBridge __Hotfix0__OnRoundStartAnimComplete; // 0xb0
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0xb8
	private static DelegateBridge __Hotfix0__HandleReplaceEquip; // 0xc0
	private static DelegateBridge __Hotfix0__OpenQuitDlg; // 0xc8
	private static DelegateBridge __Hotfix0__HandleQuitDlg; // 0xd0
	private static DelegateBridge __Hotfix0__TryOpenGoldLeftDlg; // 0xd8
	private static DelegateBridge __Hotfix0__OnGainGoldCheckBoxConfirm; // 0xe0
	private static DelegateBridge __Hotfix0__HandleGoldLeftDlg; // 0xe8
	private static DelegateBridge __Hotfix0__InitBattleEvent; // 0xf0
	private static DelegateBridge __Hotfix0__HandleStartPerpare; // 0xf8
	private static DelegateBridge __Hotfix0__HandleStartBatlle; // 0x100
	private static DelegateBridge __Hotfix0__HandleRoundInterval; // 0x108
	private static DelegateBridge __Hotfix0__HandleCommonStateChange; // 0x110
	private static DelegateBridge __Hotfix0__HandleEnemyEscape; // 0x118
	private static DelegateBridge __Hotfix0__SetTimeColorIfNecessary; // 0x120
	private static DelegateBridge __Hotfix0__HandleTimeChange; // 0x128
	private static DelegateBridge __Hotfix0_TriggerPrepareEnemyEffectHint; // 0x130
	private static DelegateBridge __Hotfix0__OnPrepareHintImp; // 0x138
	private static DelegateBridge __Hotfix0__HandleBattleHint; // 0x140
	private static DelegateBridge __Hotfix0__HandleGameSpeedChange; // 0x148
	private static DelegateBridge __Hotfix0__HandleGamePause; // 0x150
	private static DelegateBridge __Hotfix0__HandleReplaceDialog; // 0x158
	private static DelegateBridge __Hotfix0__HandleDataChanged; // 0x160
	private static DelegateBridge __Hotfix0__HandleCharDeployChanged; // 0x168
	private static DelegateBridge __Hotfix0__TryTriggerAfterChooseBuffTutorial; // 0x170
	private static DelegateBridge __Hotfix0__WaitAfterChooseBuffTutorialReady; // 0x178
	private static DelegateBridge __Hotfix0__RaiseTutorialPrepareEnterSignal; // 0x180
	private static DelegateBridge __Hotfix0__SetState; // 0x188
	private static DelegateBridge __Hotfix0__OnEnterState; // 0x190
	private static DelegateBridge __Hotfix0__OnEnterRoundBattle; // 0x198
	private static DelegateBridge __Hotfix0__HandleStartRound; // 0x1a0
	private static DelegateBridge __Hotfix0__OnEnterPrepareAnimFinish; // 0x1a8
	private static DelegateBridge __Hotfix0__OnEnterPrepareOpenTalent; // 0x1b0
	private static DelegateBridge __Hotfix0__OnEnterPrepareTriggerTutorial; // 0x1b8
	private static DelegateBridge __Hotfix0__TryTriggerTalentTutorial; // 0x1c0
	private static DelegateBridge __Hotfix0__TryTriggerPhase3Tutorial; // 0x1c8
	private static DelegateBridge __Hotfix0__OnEnterPrepareOpenEnemy; // 0x1d0
	private static DelegateBridge __Hotfix0__CloseAllDialog; // 0x1d8
	private static DelegateBridge __Hotfix0__UpdateData; // 0x1e0
	private static DelegateBridge __Hotfix0__UpdateRoundStartEnd; // 0x1e8
	private static DelegateBridge __Hotfix0__ClampSpeedLevel; // 0x1f0
	private static DelegateBridge __Hotfix0__LoadCamp; // 0x1f8
	private static DelegateBridge __Hotfix0__RefreshCamp; // 0x200
	private static DelegateBridge _c__Hotfix0_ctor; // 0x208

	public HUDState hudState { get; }

	// RVA: 0x33725fc VA: 0x759598a5fc
	public HUDState get_hudState() { }
	// RVA: 0x337268c VA: 0x759598a68c
	protected override Void OnCreate() { }
	// RVA: 0x3372920 VA: 0x759598a920
	protected override Void OnStart() { }
	// RVA: 0x3372d18 VA: 0x759598ad18
	private Void _LoadData() { }
	// RVA: 0x337319c VA: 0x759598b19c
	private Void _OnBackPress() { }
	// RVA: 0x3373490 VA: 0x759598b490
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3373698 VA: 0x759598b698
	private Void _OnSelfCampClick() { }
	// RVA: 0x33742f0 VA: 0x759598c2f0
	private Void _OnSelfCampClickImpl() { }
	// RVA: 0x3373700 VA: 0x759598b700
	private Void _OnEnemyCampClick() { }
	// RVA: 0x33745fc VA: 0x759598c5fc
	private Void _OnEnemyCampClickImpl() { }
	// RVA: 0x3373e18 VA: 0x759598be18
	private Void _OnTipCampClick() { }
	// RVA: 0x3373768 VA: 0x759598b768
	private Void _OnCloseCampClick() { }
	// RVA: 0x337480c VA: 0x759598c80c
	private Void _OnCloseCampImpl(Boolean openCampIfNecessary) { }
	// RVA: 0x33733d8 VA: 0x759598b3d8
	private Void _OnMenuClick() { }
	// RVA: 0x33737d4 VA: 0x759598b7d4
	private Void _OnSpeedClick() { }
	// RVA: 0x33738d4 VA: 0x759598b8d4
	private Void _OnPauseClick() { }
	// RVA: 0x3374a58 VA: 0x759598ca58
	private Boolean _CheckGameBattleState() { }
	// RVA: 0x33739d4 VA: 0x759598b9d4
	private Void _OnStartBattle() { }
	// RVA: 0x33732b8 VA: 0x759598b2b8
	private Void _OnExitGame() { }
	// RVA: 0x3373ba8 VA: 0x759598bba8
	private Void _OnSelectTalent(ValueBundle msg) { }
	// RVA: 0x3373cb8 VA: 0x759598bcb8
	private Void _OnConfirmTalent() { }
	// RVA: 0x33741d0 VA: 0x759598c1d0
	private Void _OnRoundEndAnimComplete() { }
	// RVA: 0x3374284 VA: 0x759598c284
	private Void _OnRoundStartAnimComplete() { }
	// RVA: 0x3375134 VA: 0x759598d134
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x3375260 VA: 0x759598d260
	private Void _HandleReplaceEquip(Output output) { }
	// RVA: 0x3374aec VA: 0x759598caec
	private Void _OpenQuitDlg() { }
	// RVA: 0x3375318 VA: 0x759598d318
	private Void _HandleQuitDlg(Int32 confirm) { }
	// RVA: 0x3374d84 VA: 0x759598cd84
	private Boolean _TryOpenGoldLeftDlg() { }
	// RVA: 0x33754a8 VA: 0x759598d4a8
	private Void _OnGainGoldCheckBoxConfirm() { }
	// RVA: 0x33753d8 VA: 0x759598d3d8
	private Void _HandleGoldLeftDlg(Int32 confirm) { }
	// RVA: 0x33729f8 VA: 0x759598a9f8
	private Void _InitBattleEvent() { }
	// RVA: 0x3375578 VA: 0x759598d578
	private Void _HandleStartPerpare(Object obj) { }
	// RVA: 0x33756a0 VA: 0x759598d6a0
	private Void _HandleStartBatlle(Object obj) { }
	// RVA: 0x3375720 VA: 0x759598d720
	private Void _HandleRoundInterval(Object obj) { }
	// RVA: 0x33755f8 VA: 0x759598d5f8
	private Void _HandleCommonStateChange(HUDState state) { }
	// RVA: 0x337591c VA: 0x759598d91c
	private Void _HandleEnemyEscape(Object obj) { }
	// RVA: 0x3375a78 VA: 0x759598da78
	private Void _SetTimeColorIfNecessary(Boolean isTimeOut) { }
	// RVA: 0x3375b58 VA: 0x759598db58
	private Void _HandleTimeChange(Object obj) { }
	// RVA: 0x3375d30 VA: 0x759598dd30
	public Void TriggerPrepareEnemyEffectHint(String effectId, String forceId) { }
	// RVA: 0x3375ec0 VA: 0x759598dec0
	private Void _OnPrepareHintImp(String hint, String iconId) { }
	// RVA: 0x33760a8 VA: 0x759598e0a8
	private Void _HandleBattleHint(Object obj) { }
	// RVA: 0x33762a4 VA: 0x759598e2a4
	private Void _HandleGameSpeedChange(Object obj) { }
	// RVA: 0x3376468 VA: 0x759598e468
	private Void _HandleGamePause(Object obj) { }
	// RVA: 0x3376584 VA: 0x759598e584
	private Void _HandleReplaceDialog(Object arg) { }
	// RVA: 0x3376870 VA: 0x759598e870
	private Void _HandleDataChanged(Object arg) { }
	// RVA: 0x3376df0 VA: 0x759598edf0
	private Boolean _HandleCharDeployChanged(AutoChessDataCenter dataCenter, Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x3376be4 VA: 0x759598ebe4
	private Void _TryTriggerAfterChooseBuffTutorial() { }
	// RVA: 0x3377358 VA: 0x759598f358
	private IEnumerator _WaitAfterChooseBuffTutorialReady() { }
	// RVA: 0x337742c VA: 0x759598f42c
	private Void _RaiseTutorialPrepareEnterSignal() { }
	// RVA: 0x33757f0 VA: 0x759598d7f0
	private Void _SetState(HUDState state) { }
	// RVA: 0x3377530 VA: 0x759598f530
	private Void _OnEnterState(HUDState state) { }
	// RVA: 0x33777c4 VA: 0x759598f7c4
	private Void _OnEnterRoundBattle() { }
	// RVA: 0x33750bc VA: 0x759598d0bc
	private Void _HandleStartRound() { }
	// RVA: 0x3374008 VA: 0x759598c008
	private Void _OnEnterPrepareAnimFinish() { }
	// RVA: 0x33778b4 VA: 0x759598f8b4
	private Void _OnEnterPrepareOpenTalent() { }
	// RVA: 0x33776c4 VA: 0x759598f6c4
	private Void _OnEnterPrepareTriggerTutorial() { }
	// RVA: 0x3377984 VA: 0x759598f984
	private Void _TryTriggerTalentTutorial() { }
	// RVA: 0x3377aa0 VA: 0x759598faa0
	private Void _TryTriggerPhase3Tutorial() { }
	// RVA: 0x337791c VA: 0x759598f91c
	private Void _OnEnterPrepareOpenEnemy() { }
	// RVA: 0x337782c VA: 0x759598f82c
	private Void _CloseAllDialog() { }
	// RVA: 0x3372fe4 VA: 0x759598afe4
	private Void _UpdateData(Boolean isInit) { }
	// RVA: 0x3376cd0 VA: 0x759598ecd0
	private Void _UpdateRoundStartEnd(RoundBattleFinishResponseViewModel resp) { }
	// RVA: 0x33763c8 VA: 0x759598e3c8
	private SpeedLevel _ClampSpeedLevel(SpeedLevel speedOrigin) { }
	// RVA: 0x3372e30 VA: 0x759598ae30
	private Void _LoadCamp() { }
	// RVA: 0x3376f24 VA: 0x759598ef24
	private Void _RefreshCamp() { }
	// RVA: 0x3378174 VA: 0x7595990174
	public Void .ctor() { }
	// RVA: 0x33782d8 VA: 0x75959902d8
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x33782e0 VA: 0x75959902e0
	private Void <>xLuaBaseProxy_OnStart() { }
}
```