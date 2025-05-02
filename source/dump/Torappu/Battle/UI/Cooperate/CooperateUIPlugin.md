# CooperateUIPlugin

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateCostHandlePanel _costHandlePanel`

- `UICooperateBattleMenuSystemPanel _systemPanel`

- `UICooperateBattleTopBar _topBarStatus`

- `UICooperateHintPanel _hintPanel`

- `UICooperateRestingPanel _restingPanel`

- `UICooperateBattleUnstablePanel _unstablePanel`

- `UICooperatePinMarkCard _pinMarkCard`

- `UICooperateBattleEmoticonController _emoticonCtrl`

- `CooperateGameMode m_gameMode`

- `UICooperateBattleTopBar m_topBarStatus`

- `UICooperateBattleMenuSystemPanel m_menuSystemPanel`

- `UICooperateHintPanel m_hintPanel`

- `UICooperateRestingPanel m_restingPanel`

- `UICooperateCostHandlePanel m_costHandlePanel`

- `UICooperateBattleUnstablePanel m_unstablePanel`

- `UICooperatePinMarkCard m_pinMarkCard`

- `Boolean m_isMultiPlayerLocal`


## Properties

- `UICooperatePinMarkCard pinMarkCard`


## Methods

- `Boolean RegistTask(ObjectPtr`1, CoopStageType)`

- `Boolean UpdateProgressBuff(ObjectPtr`1)`

- `Void SetStageTimer(FP)`

- `Void StopTimerAnim()`

- `Void StageEndAnim()`

- `Void GetProgress(Int32)`

- `UICooperatePinMarkCard get_pinMarkCard()`

- `Void ShowHint(HintType)`

- `Void HideHint(HintType)`

- `Void AddResultNormalTarget(TargetInfo)`

- `Void SendMapMarkRequest(GameMarkData)`

- `Void SetSpeedColor(Boolean, Boolean)`

- `Void ShowSystemPanel()`

- `Void OnCancelGiveUp()`

- `Void OnRealResume()`

- `Void ClosePauseConfirmPanel()`

- `CooperateIdentityInfo GetIdentityInfo()`

- `Void SwitchOutFromUICooperateBattleStartState()`

- `Void ShowEmoticonExpandPanel()`

- `Void _PreloadAssets()`

- `Void _InitLayout()`

- `Void _RegisterMultiplayerListener()`

- `Void _UnRegisterMultiplayerListener()`

- `Void _SetPauseButtonActive(Object)`

- `Void _OnAcceptPause(Object)`

- `Void _OnRefusePause(Object)`

- `Void _OnResumePause(Object)`

- `Void _OnSpeedStateChanged(Object)`

- `Void _OnSkipResting(Object)`

- `Void _OnRestingStart(Object)`

- `Void _OnBeforeNextStage(Object)`

- `Void _OnDefenceOrFootvallWaveFinished(Object)`

- `Void _OnReceivePinMark(Object)`

- `Void _OnBeforeFirstWave(Object)`

- `Void _OnGetNormolProgress(Object)`

- `Void _OnFootballManualTick(FP)`

- `Void _HandlePlayerStatusChangedResponse(Object)`

- `Void _HandleMapMarkResponse(Object)`

- `Void _HandleMultiplayerBattleStart(Object)`

- `Void CheatHandle(Object)`

- `Void _HandleMultiplayerBattleStatusChanged(Object)`

- `Void _OnRealPaused()`

- `Void _NextFrameInPause(Object)`

- `Void _OnReceiveCostRequest(Object)`

- `Void _OnPlayerDead(Object)`

- `Void _OnAllPlayerRevive(Object)`

- `Void _OnMateOnlineStateChanged(Object)`

- `Void _OnPauseRequest(Object)`

- `Void _SetPunishInfo(Boolean)`

- `Void _OpenPauseConfirmPanel()`

- `Void _ResetPauseWaitTimer(PlayerSide)`

- `Void _MarkPauseWaitInvalid(Boolean, PlayerSide)`

- `Void OnDestroy()`

- `Boolean <>xLuaBaseProxy_get_isPaused()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnFixedUpdate(FP)`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookGameStartStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Boolean <>xLuaBaseProxy_HookOnBattleFinishServiceStateEnter()`

- `Void <>xLuaBaseProxy_UpdateDisableMask(BattleFunctionDisableMask)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class CooperateUIPlugin : Plugin
{
	private static Vector2 CARD_LIST_OFFSET_MIN; // 0x0
	public static readonly UIStateEnum UI_STATE_BATTLE_START; // 0x8
	public static readonly UIStateEnum UI_STATE_PIN_MARK; // 0xc
	public static readonly UIStateEnum UI_STATE_BATTLE_FAILED; // 0x10
	public static readonly UIStateEnum UI_STATE_SCORE_A_GOAL; // 0x14
	public static readonly UIStateEnum UI_STAGE_WAVE_START; // 0x18
	public static readonly UIStateEnum UI_STAGE_SHOW_IDENTITY_BUFF; // 0x1c
	private static readonly Color UNSTABLE_BLUR_COLOR; // 0x20
	private List`1 _states; // 0x28
	private UICooperateCostHandlePanel _costHandlePanel; // 0x30
	private UICooperateBattleMenuSystemPanel _systemPanel; // 0x38
	private UICooperateBattleTopBar _topBarStatus; // 0x40
	private UICooperateHintPanel _hintPanel; // 0x48
	private UICooperateRestingPanel _restingPanel; // 0x50
	private UICooperateBattleUnstablePanel _unstablePanel; // 0x58
	private UICooperatePinMarkCard _pinMarkCard; // 0x60
	private UICooperateBattleEmoticonController _emoticonCtrl; // 0x68
	private CooperateGameMode m_gameMode; // 0x70
	private UICooperateBattleTopBar m_topBarStatus; // 0x78
	private UICooperateBattleMenuSystemPanel m_menuSystemPanel; // 0x80
	private UICooperateHintPanel m_hintPanel; // 0x88
	private UICooperateRestingPanel m_restingPanel; // 0x90
	private UICooperateCostHandlePanel m_costHandlePanel; // 0x98
	private UICooperateBattleUnstablePanel m_unstablePanel; // 0xa0
	private UICooperatePinMarkCard m_pinMarkCard; // 0xa8
	private Boolean m_isMultiPlayerLocal; // 0xb0
	private static DelegateBridge __Hotfix0_get_isPaused; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x40
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x48
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x50
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x58
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x60
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x68
	private static DelegateBridge __Hotfix0_HookGameReadyStateSwitch; // 0x70
	private static DelegateBridge __Hotfix0_HookGameStartStateSwitch; // 0x78
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0x80
	private static DelegateBridge __Hotfix0_HookOnBattleFinishServiceStateEnter; // 0x88
	private static DelegateBridge __Hotfix0_UpdateDisableMask; // 0x90
	private static DelegateBridge __Hotfix0_RegistTask; // 0x98
	private static DelegateBridge __Hotfix0_UpdateProgressBuff; // 0xa0
	private static DelegateBridge __Hotfix0_SetStageTimer; // 0xa8
	private static DelegateBridge __Hotfix0_StopTimerAnim; // 0xb0
	private static DelegateBridge __Hotfix0_StageEndAnim; // 0xb8
	private static DelegateBridge __Hotfix0_GetProgress; // 0xc0
	private static DelegateBridge __Hotfix0_get_pinMarkCard; // 0xc8
	private static DelegateBridge __Hotfix0_ShowHint; // 0xd0
	private static DelegateBridge __Hotfix0_HideHint; // 0xd8
	private static DelegateBridge __Hotfix0_AddResultNormalTarget; // 0xe0
	private static DelegateBridge __Hotfix0_SendMapMarkRequest; // 0xe8
	private static DelegateBridge __Hotfix0_SetSpeedColor; // 0xf0
	private static DelegateBridge __Hotfix0_ShowSystemPanel; // 0xf8
	private static DelegateBridge __Hotfix0_OnCancelGiveUp; // 0x100
	private static DelegateBridge __Hotfix0_OnRealResume; // 0x108
	private static DelegateBridge __Hotfix0_ClosePauseConfirmPanel; // 0x110
	private static DelegateBridge __Hotfix0_GetIdentityInfo; // 0x118
	private static DelegateBridge __Hotfix0_SwitchOutFromUICooperateBattleStartState; // 0x120
	private static DelegateBridge __Hotfix0_ShowEmoticonExpandPanel; // 0x128
	private static DelegateBridge __Hotfix0__PreloadAssets; // 0x130
	private static DelegateBridge __Hotfix0__InitLayout; // 0x138
	private static DelegateBridge __Hotfix0__RegisterMultiplayerListener; // 0x140
	private static DelegateBridge __Hotfix0__UnRegisterMultiplayerListener; // 0x148
	private static DelegateBridge __Hotfix0__SetPauseButtonActive; // 0x150
	private static DelegateBridge __Hotfix0__OnAcceptPause; // 0x158
	private static DelegateBridge __Hotfix0__OnRefusePause; // 0x160
	private static DelegateBridge __Hotfix0__OnResumePause; // 0x168
	private static DelegateBridge __Hotfix0__OnSpeedStateChanged; // 0x170
	private static DelegateBridge __Hotfix0__OnSkipResting; // 0x178
	private static DelegateBridge __Hotfix0__OnRestingStart; // 0x180
	private static DelegateBridge __Hotfix0__OnBeforeNextStage; // 0x188
	private static DelegateBridge __Hotfix0__OnDefenceOrFootvallWaveFinished; // 0x190
	private static DelegateBridge __Hotfix0__OnReceivePinMark; // 0x198
	private static DelegateBridge __Hotfix0__OnBeforeFirstWave; // 0x1a0
	private static DelegateBridge __Hotfix0__OnGetNormolProgress; // 0x1a8
	private static DelegateBridge __Hotfix0__OnFootballManualTick; // 0x1b0
	private static DelegateBridge __Hotfix0__HandlePlayerStatusChangedResponse; // 0x1b8
	private static DelegateBridge __Hotfix0__HandleMapMarkResponse; // 0x1c0
	private static DelegateBridge __Hotfix0__HandleMultiplayerBattleStart; // 0x1c8
	private static DelegateBridge __Hotfix0_CheatHandle; // 0x1d0
	private static DelegateBridge __Hotfix0__HandleMultiplayerBattleStatusChanged; // 0x1d8
	private static DelegateBridge __Hotfix0__OnRealPaused; // 0x1e0
	private static DelegateBridge __Hotfix0__NextFrameInPause; // 0x1e8
	private static DelegateBridge __Hotfix0__OnReceiveCostRequest; // 0x1f0
	private static DelegateBridge __Hotfix0__OnPlayerDead; // 0x1f8
	private static DelegateBridge __Hotfix0__OnAllPlayerRevive; // 0x200
	private static DelegateBridge __Hotfix0__OnMateOnlineStateChanged; // 0x208
	private static DelegateBridge __Hotfix0__OnPauseRequest; // 0x210
	private static DelegateBridge __Hotfix0__SetPunishInfo; // 0x218
	private static DelegateBridge __Hotfix0__OpenPauseConfirmPanel; // 0x220
	private static DelegateBridge __Hotfix0__ResetPauseWaitTimer; // 0x228
	private static DelegateBridge __Hotfix0__MarkPauseWaitInvalid; // 0x230
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x238
	private static DelegateBridge _c__Hotfix0_ctor; // 0x240

	public override Boolean isPaused { get; }
	public UICooperatePinMarkCard pinMarkCard { get; }

	// RVA: 0x20eba3c VA: 0x7594703a3c
	public override Boolean get_isPaused() { }
	// RVA: 0x20ebaf8 VA: 0x7594703af8
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x20ec38c VA: 0x759470438c
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x20ec4e4 VA: 0x75947044e4
	public override Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20ec884 VA: 0x7594704884
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x20ec930 VA: 0x7594704930
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x20ed2c0 VA: 0x75947052c0
	public override Void OnGameReady() { }
	// RVA: 0x20ed560 VA: 0x7594705560
	public override Void UpdateGameInfo() { }
	// RVA: 0x20ed690 VA: 0x7594705690
	public override Boolean HookGameReadyStateSwitch() { }
	// RVA: 0x20ed76c VA: 0x759470576c
	public override Boolean HookGameStartStateSwitch() { }
	// RVA: 0x20ed7e4 VA: 0x75947057e4
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x20ed930 VA: 0x7594705930
	public override Boolean HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x20ed9e8 VA: 0x75947059e8
	public override Void UpdateDisableMask(BattleFunctionDisableMask mask) { }
	// RVA: 0x20eda9c VA: 0x7594705a9c
	public Boolean RegistTask(ObjectPtr`1 buff, CoopStageType type) { }
	// RVA: 0x20edb5c VA: 0x7594705b5c
	public Boolean UpdateProgressBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20edc04 VA: 0x7594705c04
	public Void SetStageTimer(FP time) { }
	// RVA: 0x20edca0 VA: 0x7594705ca0
	public Void StopTimerAnim() { }
	// RVA: 0x20edd24 VA: 0x7594705d24
	public Void StageEndAnim() { }
	// RVA: 0x20edda8 VA: 0x7594705da8
	public Void GetProgress(Int32 curScore) { }
	// RVA: 0x20ede44 VA: 0x7594705e44
	public UICooperatePinMarkCard get_pinMarkCard() { }
	// RVA: 0x20edebc VA: 0x7594705ebc
	public Void ShowHint(HintType type) { }
	// RVA: 0x20edf58 VA: 0x7594705f58
	public Void HideHint(HintType type) { }
	// RVA: 0x20edff4 VA: 0x7594705ff4
	public Void AddResultNormalTarget(TargetInfo target) { }
	// RVA: 0x20ee0c4 VA: 0x75947060c4
	public Void SendMapMarkRequest(GameMarkData param) { }
	// RVA: 0x20ee198 VA: 0x7594706198
	public Void SetSpeedColor(Boolean speedUp, Boolean mateSpeedUp) { }
	// RVA: 0x20ee240 VA: 0x7594706240
	public Void ShowSystemPanel() { }
	// RVA: 0x20ee2c4 VA: 0x75947062c4
	public Void OnCancelGiveUp() { }
	// RVA: 0x20ee3ac VA: 0x75947063ac
	public Void OnRealResume() { }
	// RVA: 0x20ee498 VA: 0x7594706498
	public Void ClosePauseConfirmPanel() { }
	// RVA: 0x20ee51c VA: 0x759470651c
	public CooperateIdentityInfo GetIdentityInfo() { }
	// RVA: 0x20ee618 VA: 0x7594706618
	public Void SwitchOutFromUICooperateBattleStartState() { }
	// RVA: 0x20ee70c VA: 0x759470670c
	public Void ShowEmoticonExpandPanel() { }
	// RVA: 0x20ebbb0 VA: 0x7594703bb0
	private Void _PreloadAssets() { }
	// RVA: 0x20ec29c VA: 0x759470429c
	private Void _InitLayout() { }
	// RVA: 0x20ecba8 VA: 0x7594704ba8
	private Void _RegisterMultiplayerListener() { }
	// RVA: 0x20ee7a4 VA: 0x75947067a4
	private Void _UnRegisterMultiplayerListener() { }
	// RVA: 0x20eeebc VA: 0x7594706ebc
	private Void _SetPauseButtonActive(Object arg) { }
	// RVA: 0x20eefa0 VA: 0x7594706fa0
	private Void _OnAcceptPause(Object arg) { }
	// RVA: 0x20ef254 VA: 0x7594707254
	private Void _OnRefusePause(Object arg) { }
	// RVA: 0x20ef368 VA: 0x7594707368
	private Void _OnResumePause(Object arg) { }
	// RVA: 0x20ef400 VA: 0x7594707400
	private Void _OnSpeedStateChanged(Object arg) { }
	// RVA: 0x20ef4d8 VA: 0x75947074d8
	private Void _OnSkipResting(Object arg) { }
	// RVA: 0x20ef5b4 VA: 0x75947075b4
	private Void _OnRestingStart(Object arg) { }
	// RVA: 0x20ef64c VA: 0x759470764c
	private Void _OnBeforeNextStage(Object arg) { }
	// RVA: 0x20ef79c VA: 0x759470779c
	private Void _OnDefenceOrFootvallWaveFinished(Object arg) { }
	// RVA: 0x20ef8b0 VA: 0x75947078b0
	private Void _OnReceivePinMark(Object arg) { }
	// RVA: 0x20ef948 VA: 0x7594707948
	private Void _OnBeforeFirstWave(Object arg) { }
	// RVA: 0x20efa40 VA: 0x7594707a40
	private Void _OnGetNormolProgress(Object arg) { }
	// RVA: 0x20ec5fc VA: 0x75947045fc
	private Void _OnFootballManualTick(FP deltaTime) { }
	// RVA: 0x20efb10 VA: 0x7594707b10
	private Void _HandlePlayerStatusChangedResponse(Object arg) { }
	// RVA: 0x20efcec VA: 0x7594707cec
	private Void _HandleMapMarkResponse(Object arg) { }
	// RVA: 0x20efd80 VA: 0x7594707d80
	private Void _HandleMultiplayerBattleStart(Object arg) { }
	// RVA: 0x20efe10 VA: 0x7594707e10
	public Void CheatHandle(Object arg) { }
	// RVA: 0x20efea0 VA: 0x7594707ea0
	private Void _HandleMultiplayerBattleStatusChanged(Object arg) { }
	// RVA: 0x20ef168 VA: 0x7594707168
	private Void _OnRealPaused() { }
	// RVA: 0x20f0010 VA: 0x7594708010
	private Void _NextFrameInPause(Object arg) { }
	// RVA: 0x20f00ec VA: 0x75947080ec
	private Void _OnReceiveCostRequest(Object arg) { }
	// RVA: 0x20f0188 VA: 0x7594708188
	private Void _OnPlayerDead(Object arg) { }
	// RVA: 0x20f02a8 VA: 0x75947082a8
	private Void _OnAllPlayerRevive(Object arg) { }
	// RVA: 0x20f03a8 VA: 0x75947083a8
	private Void _OnMateOnlineStateChanged(Object arg) { }
	// RVA: 0x20f0548 VA: 0x7594708548
	private Void _OnPauseRequest(Object arg) { }
	// RVA: 0x20ed4c4 VA: 0x75947054c4
	private Void _SetPunishInfo(Boolean punish) { }
	// RVA: 0x20f073c VA: 0x759470873c
	private Void _OpenPauseConfirmPanel() { }
	// RVA: 0x20f06a0 VA: 0x75947086a0
	private Void _ResetPauseWaitTimer(PlayerSide side) { }
	// RVA: 0x20ef0c0 VA: 0x75947070c0
	private Void _MarkPauseWaitInvalid(Boolean reject, PlayerSide side) { }
	// RVA: 0x20f07c0 VA: 0x75947087c0
	public Void OnDestroy() { }
	// RVA: 0x20f0838 VA: 0x7594708838
	public Void .ctor() { }
	// RVA: 0x20f08b8 VA: 0x75947088b8
	private static Void .cctor() { }
	// RVA: 0x20f0934 VA: 0x7594708934
	private Boolean <>xLuaBaseProxy_get_isPaused() { }
	// RVA: 0x20f093c VA: 0x759470893c
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x20f0944 VA: 0x7594708944
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x20f094c VA: 0x759470894c
	private Void <>xLuaBaseProxy_OnFixedUpdate(FP P0) { }
	// RVA: 0x20f0954 VA: 0x7594708954
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
	// RVA: 0x20f095c VA: 0x759470895c
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x20f0964 VA: 0x7594708964
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x20f096c VA: 0x759470896c
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x20f0974 VA: 0x7594708974
	private Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch() { }
	// RVA: 0x20f097c VA: 0x759470897c
	private Boolean <>xLuaBaseProxy_HookGameStartStateSwitch() { }
	// RVA: 0x20f0984 VA: 0x7594708984
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x20f0990 VA: 0x7594708990
	private Boolean <>xLuaBaseProxy_HookOnBattleFinishServiceStateEnter() { }
	// RVA: 0x20f0998 VA: 0x7594708998
	private Void <>xLuaBaseProxy_UpdateDisableMask(BattleFunctionDisableMask P0) { }
}
```