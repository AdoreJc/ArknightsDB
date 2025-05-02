# UICooperateBattleTopBar

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateBattlePauseConfirmPanel _pauseConfirmPanel`

- `Button _multiPlayerPauseButton`

- `Graphic _pauseImg`

- `Graphic _resumeImg`

- `BasicStatus _basicStatus`

- `BasicStatus _footballStatus`

- `ExtraStatus _extraStatus`

- `Button _multiSystemButton`

- `Button _multiSpeedUpButton`

- `Slider _pauseResumeSlider`

- `Slider _pauseRequestSlider`

- `UICooperateBattleSpeedPanel _speedPanel`

- `UICooperateScoreStatusPanel _cooperateScoreStatusPanel`

- `UICooperateTaskView _taskView`

- `Text _footballTimer`

- `UICooperateTaskFortressPanel _fortressTaskPanel`

- `UICooperateTaskFortressLastWavePanel _fortressTaskLastWavePanel`

- `Text _reviveTimerSelf`

- `Text _reviveTimerOpposite`

- `UIAnimationLocation _reviveTimerEnterSelf`

- `UIAnimationLocation _reviveTimerEnterOppo`

- `UIAnimationLocation _lifePointEnterSelf`

- `UIAnimationLocation _lifePointEnterOppo`

- `CooperateUIPlugin m_plugin`

- `CooperateGameMode m_gameMode`

- `PeriodicTimer m_pauseWaitingTimer`

- `PeriodicTimer m_pauseResumeTimer`

- `PeriodicTimer m_pauseCooldownTimer`

- `Int32 m_mateIgnorePauseTime`

- `Boolean m_pausebuttonIsOnLocal`

- `PlayerSide m_pauseRequestSide`

- `Boolean m_isPauseButtonInteractive`

- `UICooperateTaskPanel m_curPanel`

- `Boolean m_isPlayerDead`

- `PlayerSide m_deadPlayerSide`


## Methods

- `Void OnCreate()`

- `Void OnGameInit(CooperateUIPlugin, CooperateGameMode)`

- `Void OnGameReady()`

- `Void SetStageTimer(FP)`

- `Void StopTimerAnim()`

- `Void StageEndAnim()`

- `Boolean RegistTask(ObjectPtr`1, CoopStageType)`

- `Void AddResultNormalTarget(TargetInfo)`

- `Boolean UpdateProgressBuff(ObjectPtr`1)`

- `Void GetProgress(Int32)`

- `Void OnUIStateChanged(IUIStateNode)`

- `Void OnFixedUpdate(FP)`

- `Void UpdateGameInfo()`

- `Void UpdateDisableMask(BattleFunctionDisableMask)`

- `Void OpenPauseConfirmPanel()`

- `Void ClosePauseConfirmPanel()`

- `Void SetPauseButtonActive(Boolean)`

- `Void SetSpeedColor(Boolean, Boolean)`

- `Void InitLayout()`

- `Void NextFrameInPause()`

- `Void OnRealPaused()`

- `Void OnRealResume()`

- `Void MarkPauseWaitInvalid(Boolean, PlayerSide)`

- `Void ResetPauseWaitTimer(PlayerSide)`

- `Void ResetResumeTimer()`

- `Void OnPlayerDie(PlayerSide)`

- `Void OnPlayerRevive(PlayerSide)`

- `Void OnMultiPlayerPauseButtonClicked()`

- `Void OnSystemMenuClicked()`

- `Void OnPauseResponseClicked(Int32)`

- `Void OnSpeedUpClicked()`

- `String _TimeToShow(FP)`

- `Void _OnMultiPauseButtonClicked()`

- `Void _ResetPauseCoolDown()`

- `Void _ChangeButtonIcon(Boolean)`

- `Void _OnScoreAGoal(Object)`

- `Boolean _PauseWaitingTimerUpdate(FP)`

- `Void _OnPlayerDying(Object)`

- `Void _OnPlayerRevive(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleTopBar : MonoBehaviour, IHotfixable
{
	private const String TIME_FORMAT; // 0x0
	private UICooperateBattlePauseConfirmPanel _pauseConfirmPanel; // 0x18
	private Button _multiPlayerPauseButton; // 0x20
	private Graphic _pauseImg; // 0x28
	private Graphic _resumeImg; // 0x30
	private BasicStatus _basicStatus; // 0x38
	private BasicStatus _footballStatus; // 0x40
	private ExtraStatus _extraStatus; // 0x48
	private Button _multiSystemButton; // 0x50
	private Button _multiSpeedUpButton; // 0x58
	private Slider _pauseResumeSlider; // 0x60
	private Slider _pauseRequestSlider; // 0x68
	private UICooperateBattleSpeedPanel _speedPanel; // 0x70
	private UICooperateScoreStatusPanel _cooperateScoreStatusPanel; // 0x78
	private UICooperateTaskView _taskView; // 0x80
	private Text _footballTimer; // 0x88
	private List`1 _taskPanels; // 0x90
	private UICooperateTaskFortressPanel _fortressTaskPanel; // 0x98
	private UICooperateTaskFortressLastWavePanel _fortressTaskLastWavePanel; // 0xa0
	private Text _reviveTimerSelf; // 0xa8
	private Text _reviveTimerOpposite; // 0xb0
	private UIAnimationLocation _reviveTimerEnterSelf; // 0xb8
	private UIAnimationLocation _reviveTimerEnterOppo; // 0xc8
	private UIAnimationLocation _lifePointEnterSelf; // 0xd8
	private UIAnimationLocation _lifePointEnterOppo; // 0xe8
	private CooperateUIPlugin m_plugin; // 0xf8
	private CooperateGameMode m_gameMode; // 0x100
	private PeriodicTimer m_pauseWaitingTimer; // 0x108
	private PeriodicTimer m_pauseResumeTimer; // 0x110
	private PeriodicTimer m_pauseCooldownTimer; // 0x118
	private Int32 m_mateIgnorePauseTime; // 0x120
	private Boolean m_pausebuttonIsOnLocal; // 0x124
	private PlayerSide m_pauseRequestSide; // 0x128
	private Boolean m_isPauseButtonInteractive; // 0x12c
	private UICooperateTaskPanel m_curPanel; // 0x130
	private Boolean m_isPlayerDead; // 0x138
	private PlayerSide m_deadPlayerSide; // 0x13c
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x8
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x10
	private static DelegateBridge __Hotfix0_SetStageTimer; // 0x18
	private static DelegateBridge __Hotfix0_StopTimerAnim; // 0x20
	private static DelegateBridge __Hotfix0_StageEndAnim; // 0x28
	private static DelegateBridge __Hotfix0_RegistTask; // 0x30
	private static DelegateBridge __Hotfix0_AddResultNormalTarget; // 0x38
	private static DelegateBridge __Hotfix0_UpdateProgressBuff; // 0x40
	private static DelegateBridge __Hotfix0_GetProgress; // 0x48
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x50
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x58
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x60
	private static DelegateBridge __Hotfix0_UpdateDisableMask; // 0x68
	private static DelegateBridge __Hotfix0_OpenPauseConfirmPanel; // 0x70
	private static DelegateBridge __Hotfix0_ClosePauseConfirmPanel; // 0x78
	private static DelegateBridge __Hotfix0_SetPauseButtonActive; // 0x80
	private static DelegateBridge __Hotfix0_SetSpeedColor; // 0x88
	private static DelegateBridge __Hotfix0_InitLayout; // 0x90
	private static DelegateBridge __Hotfix0_NextFrameInPause; // 0x98
	private static DelegateBridge __Hotfix0_OnRealPaused; // 0xa0
	private static DelegateBridge __Hotfix0_OnRealResume; // 0xa8
	private static DelegateBridge __Hotfix0_MarkPauseWaitInvalid; // 0xb0
	private static DelegateBridge __Hotfix0_ResetPauseWaitTimer; // 0xb8
	private static DelegateBridge __Hotfix0_ResetResumeTimer; // 0xc0
	private static DelegateBridge __Hotfix0_OnPlayerDie; // 0xc8
	private static DelegateBridge __Hotfix0_OnPlayerRevive; // 0xd0
	private static DelegateBridge __Hotfix0_OnMultiPlayerPauseButtonClicked; // 0xd8
	private static DelegateBridge __Hotfix0_OnSystemMenuClicked; // 0xe0
	private static DelegateBridge __Hotfix0_OnPauseResponseClicked; // 0xe8
	private static DelegateBridge __Hotfix0_OnSpeedUpClicked; // 0xf0
	private static DelegateBridge __Hotfix0__TimeToShow; // 0xf8
	private static DelegateBridge __Hotfix0__OnMultiPauseButtonClicked; // 0x100
	private static DelegateBridge __Hotfix0__ResetPauseCoolDown; // 0x108
	private static DelegateBridge __Hotfix0__ChangeButtonIcon; // 0x110
	private static DelegateBridge __Hotfix0__OnScoreAGoal; // 0x118
	private static DelegateBridge __Hotfix0__PauseWaitingTimerUpdate; // 0x120
	private static DelegateBridge __Hotfix0__OnPlayerDying; // 0x128
	private static DelegateBridge __Hotfix0__OnPlayerRevive; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138


	// RVA: 0x20e494c VA: 0x75946fc94c
	public Void OnCreate() { }
	// RVA: 0x20e49c0 VA: 0x75946fc9c0
	public Void OnGameInit(CooperateUIPlugin plugin, CooperateGameMode gameMode) { }
	// RVA: 0x20e4bbc VA: 0x75946fcbbc
	public Void OnGameReady() { }
	// RVA: 0x20e4f50 VA: 0x75946fcf50
	public Void SetStageTimer(FP time) { }
	// RVA: 0x20e5190 VA: 0x75946fd190
	public Void StopTimerAnim() { }
	// RVA: 0x20e5250 VA: 0x75946fd250
	public Void StageEndAnim() { }
	// RVA: 0x20e5310 VA: 0x75946fd310
	public Boolean RegistTask(ObjectPtr`1 buff, CoopStageType type) { }
	// RVA: 0x20e55e4 VA: 0x75946fd5e4
	public Void AddResultNormalTarget(TargetInfo target) { }
	// RVA: 0x20e56a4 VA: 0x75946fd6a4
	public Boolean UpdateProgressBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20e5784 VA: 0x75946fd784
	public Void GetProgress(Int32 curScore) { }
	// RVA: 0x20e58a0 VA: 0x75946fd8a0
	public Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x20e5b94 VA: 0x75946fdb94
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20e5ff0 VA: 0x75946fdff0
	public Void UpdateGameInfo() { }
	// RVA: 0x20e62e4 VA: 0x75946fe2e4
	public Void UpdateDisableMask(BattleFunctionDisableMask mask) { }
	// RVA: 0x20e6394 VA: 0x75946fe394
	public Void OpenPauseConfirmPanel() { }
	// RVA: 0x20e64dc VA: 0x75946fe4dc
	public Void ClosePauseConfirmPanel() { }
	// RVA: 0x20e5f4c VA: 0x75946fdf4c
	public Void SetPauseButtonActive(Boolean isActive) { }
	// RVA: 0x20e655c VA: 0x75946fe55c
	public Void SetSpeedColor(Boolean speedUp, Boolean mateSpeedUp) { }
	// RVA: 0x20e65f4 VA: 0x75946fe5f4
	public Void InitLayout() { }
	// RVA: 0x20e6788 VA: 0x75946fe788
	public Void NextFrameInPause() { }
	// RVA: 0x20e6908 VA: 0x75946fe908
	public Void OnRealPaused() { }
	// RVA: 0x20e6b08 VA: 0x75946feb08
	public Void OnRealResume() { }
	// RVA: 0x20e6b78 VA: 0x75946feb78
	public Void MarkPauseWaitInvalid(Boolean reject, PlayerSide side) { }
	// RVA: 0x20e6ce8 VA: 0x75946fece8
	public Void ResetPauseWaitTimer(PlayerSide side) { }
	// RVA: 0x20e6e20 VA: 0x75946fee20
	public Void ResetResumeTimer() { }
	// RVA: 0x20e6f98 VA: 0x75946fef98
	public Void OnPlayerDie(PlayerSide side) { }
	// RVA: 0x20e7074 VA: 0x75946ff074
	public Void OnPlayerRevive(PlayerSide side) { }
	// RVA: 0x20e7154 VA: 0x75946ff154
	public Void OnMultiPlayerPauseButtonClicked() { }
	// RVA: 0x20e7350 VA: 0x75946ff350
	public Void OnSystemMenuClicked() { }
	// RVA: 0x20e7438 VA: 0x75946ff438
	public Void OnPauseResponseClicked(Int32 param) { }
	// RVA: 0x20e74c4 VA: 0x75946ff4c4
	public Void OnSpeedUpClicked() { }
	// RVA: 0x20e5034 VA: 0x75946fd034
	private String _TimeToShow(FP time) { }
	// RVA: 0x20e71bc VA: 0x75946ff1bc
	private Void _OnMultiPauseButtonClicked() { }
	// RVA: 0x20e75e4 VA: 0x75946ff5e4
	private Void _ResetPauseCoolDown() { }
	// RVA: 0x20e69e0 VA: 0x75946fe9e0
	private Void _ChangeButtonIcon(Boolean isPause) { }
	// RVA: 0x20e7710 VA: 0x75946ff710
	private Void _OnScoreAGoal(Object arg) { }
	// RVA: 0x20e5d58 VA: 0x75946fdd58
	private Boolean _PauseWaitingTimerUpdate(FP deltaTime) { }
	// RVA: 0x20e7854 VA: 0x75946ff854
	private Void _OnPlayerDying(Object arg) { }
	// RVA: 0x20e7c40 VA: 0x75946ffc40
	private Void _OnPlayerRevive(Object arg) { }
	// RVA: 0x20e7ea8 VA: 0x75946ffea8
	public Void .ctor() { }
}
```