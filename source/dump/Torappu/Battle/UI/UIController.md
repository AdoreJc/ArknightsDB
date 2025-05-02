# UIController

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Camera _uiCamera`

- `Canvas _rootCanvas`

- `Canvas _perspectiveCanvas`

- `UITopBar _topBar`

- `UICharacterInfoPanel _characterInfo`

- `UIFakeBlur _fakeBlur`

- `UICardList _cardList`

- `UIToastController _toastController`

- `UIHintController _hintController`

- `UIAutoBattlePanel _autoBattlePanel`

- `UIBattleSystemMenuPanel _systemMenuPanel`

- `UICostPanel _costPanel`

- `RectTransform _hudPanel`

- `RectTransform _tempPanel`

- `RectTransform _tempPanelPerspective`

- `UIUnitHUD _characterHud`

- `UIUnitHUD _enemyHud`

- `UIUnitHUD _enemyBossHud`

- `UIUnitHUD _trapHud`

- `UINumericText _damageText`

- `UINumericText _healText`

- `UINumericText _blockText`

- `UIMessageText _messageText`

- `UIMessageText _messageTextSlow`

- `UIEnemyGiantBossInfoPanel _enemyBossInfo`

- `UIAnimationPerform _battleAccomplishedPerform`

- `UIDirectionSelector _directionSelector`

- `UICharacterMenuState _characterMenuState`

- `UIRemainingAvailableCharacter _remainingCharacter`

- `RectTransform _groupRoot`

- `RectTransform _groupStatic`

- `RectTransform _groupTop`

- `RectTransform _groupTopBar`

- `RectTransform _groupDialogue`

- `RectTransform _groupEnemy`

- `UIEnemyGiantBossInfoPanel m_enemyBossInfo`

- `Boolean m_isPerspectiveCanvasOn`

- `Camera m_uiPerspectiveCamera`

- `UIStateMachine m_stateMachine`

- `BattleFunctionDisableMask m_functionDisableMask`

- `UICanvasScalerHelper m_canvasScalerHelper`

- `Single m_cameraHudScale`

- `TileInfoController _tileInfoController`

- `VoicePlayer m_voicePlayer`

- `UIAutoBattlePanel m_autoBattlePanel`

- `Boolean <isGuideMode>k__BackingField`

- `BattleController <controller>k__BackingField`

- `IAVGTutorialPanelPlugin <avgTutorialPlugin>k__BackingField`

- `Plugin <plugin>k__BackingField`


## Properties

- `UIStateMachine stateMachine`

- `UIStateEnum currentState`

- `UITopBar topbar`

- `UICharacterMenuState characterMenuState`

- `UIFakeBlur fakeBlur`

- `UIDirectionSelector directionSelector`

- `UIAnimationPerform battleAccomplishedPerform`

- `Transform hudPanel`

- `UIToastController toastController`

- `UICharacterInfoPanel characterInfo`

- `Canvas perspectiveCanvas`

- `UICardList cardList`

- `UICanvasScalerHelper scalerHelper`

- `UIAutoBattlePanel autoBattlePanel`

- `RectTransform groupRoot`

- `RectTransform groupStatic`

- `RectTransform groupTop`

- `RectTransform groupTopBar`

- `RectTransform groupDialogue`

- `RectTransform tempPanelPerspective`

- `Camera camera`

- `Boolean isPaused`

- `Boolean isPausedButNotInGuideMode`

- `Boolean enableUIShowCardState`

- `Boolean isGuideMode`

- `Boolean isPerspectiveCanvasOn`

- `BattleController controller`

- `IAVGTutorialPanelPlugin avgTutorialPlugin`

- `Plugin plugin`

- `Boolean needReleaseIllust`

- `UIEnemyGiantBossInfoPanel enemyBossInfo`

- `Boolean showCharacterStatusInDummy`


## Methods

- `UIStateMachine get_stateMachine()`

- `UIStateEnum get_currentState()`

- `UITopBar get_topbar()`

- `UICharacterMenuState get_characterMenuState()`

- `UIFakeBlur get_fakeBlur()`

- `UIDirectionSelector get_directionSelector()`

- `UIAnimationPerform get_battleAccomplishedPerform()`

- `Transform get_hudPanel()`

- `UIToastController get_toastController()`

- `UICharacterInfoPanel get_characterInfo()`

- `Canvas get_perspectiveCanvas()`

- `UICardList get_cardList()`

- `UICanvasScalerHelper get_scalerHelper()`

- `UIAutoBattlePanel get_autoBattlePanel()`

- `RectTransform get_groupRoot()`

- `RectTransform get_groupStatic()`

- `RectTransform get_groupTop()`

- `RectTransform get_groupTopBar()`

- `RectTransform get_groupDialogue()`

- `RectTransform get_tempPanelPerspective()`

- `Camera get_camera()`

- `Boolean get_isPaused()`

- `Boolean get_isPausedButNotInGuideMode()`

- `Boolean get_enableUIShowCardState()`

- `Boolean get_isGuideMode()`

- `Void set_isGuideMode(Boolean)`

- `Boolean get_isPerspectiveCanvasOn()`

- `Void set_isPerspectiveCanvasOn(Boolean)`

- `BattleController get_controller()`

- `Void set_controller(BattleController)`

- `IAVGTutorialPanelPlugin get_avgTutorialPlugin()`

- `Void set_avgTutorialPlugin(IAVGTutorialPanelPlugin)`

- `Plugin get_plugin()`

- `Void set_plugin(Plugin)`

- `Boolean get_needReleaseIllust()`

- `UIEnemyGiantBossInfoPanel get_enemyBossInfo()`

- `Boolean get_showCharacterStatusInDummy()`

- `Void OnCardMenuShow(Card)`

- `Boolean CanPluginPressBackButton()`

- `Void OnCharacterMenuShow(Character)`

- `Void OnCharacterMenuHide()`

- `Void OnFixedUpdate(FP)`

- `Boolean SetPaused(Boolean, Boolean, Boolean)`

- `Void RaiseTutorialSignal(String)`

- `Void RaiseTutorialSignalIfRuning(String)`

- `Void RegisterTutorialExtraBattleTarget(String, GameObject)`

- `Boolean TryMatchingTutorialWaitSignalStringParam(String, String, String)`

- `Void OnCardBeginDrag(UICard)`

- `Void OnCardEndDrag(UICard)`

- `Void OnCardToggled(UICard, Boolean)`

- `Void HideCharacterInfo(Boolean)`

- `Void UpdateCardListToggleGroup(Boolean)`

- `Void OnBottomMaskClicked(Object)`

- `Void OnBottomMaskDrag(Object)`

- `Void OnBottomMaskBeginDrag(Object)`

- `Void OnBottomMaskEndDrag(Object)`

- `Void OnBottomMaskDown()`

- `Void OnBottomMaskUp()`

- `Void PrepareThenRestartGame()`

- `Void RestartGame()`

- `Vector2 GameToUIWorldPos(Vector3)`

- `Vector2 GameToUIPixel(Vector3)`

- `Void EnableFunction(BattleFunctionDisableMask)`

- `Void DisableFunction(BattleFunctionDisableMask)`

- `Boolean HasFunction(BattleFunctionDisableMask)`

- `Void OnApplicationPause(Boolean)`

- `Void _TriggerPauseWhenApplicationPaused()`

- `Void _UpdateDisableMask(BattleFunctionDisableMask)`

- `Void _UpdateGameInfo()`

- `Void _UpdateHudScaleIfNot()`

- `RectTransform _LoadRuntimeUIPluginIfNot(String)`

- `Void AddRuntimeUIPlugin(RtUIPluginPosition, String)`

- `Void RemoveRuntimeUIPlugin(String)`

- `Void _InitStateMachine()`

- `Void _TryCreatePlugin()`

- `GameObject _CreatePluginByLevelData(LevelData)`

- `Void SetUIStateParam(UIStateEnum, Object)`

- `T GetUIStateParam(UIStateEnum)`

- `Vector2 UIPixelToWorldVector(Vector2)`

- `Void ShowModifierText(ref, Transform)`

- `Void ShowNumericText(ref, Transform, UINumericText, Boolean, Int32)`

- `Void ShowMessageText(String, Transform)`

- `Void ShowMessageText(String, Transform, Color)`

- `Void ShowSlowMessageText(String, Transform, Color)`

- `Boolean ShowGameModeNumericTest(Int32, Transform, Color)`

- `Void SwitchToBattleFinishService(BattleFinishServiceStateParam)`

- `Void SwitchToBattleFailedState(BattleFailedStateParam)`

- `Void SwitchToBattleAccomplishedState()`

- `Void SwitchToDialogState(BattleDialogParam)`

- `Void OnSystemMenuCancel()`

- `Void ShowDynamicHUDGroup(Boolean)`

- `Void ShowHint(String, BannerStyle)`

- `Boolean AttachHudPlugin(Unit, Transform)`

- `Void PrepareHideForDialog()`

- `Void RestoreHideForDialog()`

- `Void OnGameReset(BattleController)`

- `Void OnGameInit(Options)`

- `Void OnGameReady()`

- `Void OnGameStart()`

- `Void OnGameOver(GameResult)`

- `Void OnSwitchToBattleFinish()`

- `Void OnUIStateChanged(IUIStateNode)`

- `Vector3 GetPredefinedLocationByUI(PredefinedLocation)`

- `Void _OnUnitBorn(Unit)`

- `UIUnitHUD _GetDefaultHud(Unit)`

- `Void _OnUnitSwitchSide(Unit)`

- `Void _OnGiantBossEnter(Unit)`

- `Void _OnUnitFinish(Unit)`

- `Void _OnStateChanged(Int32, Int32)`

- `Void _OnDisplayEnemyInfo(Object)`

- `Void _OnBlockAnyRoutes(Object)`

- `Void _OnDisplayLegionBlastCard(Object)`

- `Void _OnDisplayDeckBuffEffect(Object)`

- `Void _OnAutoReplayModeChanged(Object)`

- `Void _OnAutoReplayFinished(Object)`

- `Void Update()`

- `Void <OnGameReset>b__201_0(Object)`

- `Void <OnGameReset>b__201_1(Object)`

- `Void <OnGameReset>b__201_2(Object)`

- `Void <OnGameReset>b__201_3(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIController : SingletonMonoBehaviour`1, IBattleModule, ISingletonNotAutoCreate, IHotfixable
{
	public const Single ALERT_INFO_POPUP_TIME; // 0x0
	private const Single ENEMY_INFO_TOAST_TIME; // 0x0
	private const Single LEGION_BLAST_CARD_TOAST_TIME; // 0x0
	private const Single LEGION_TRAP_EFFECT_TOAST_TIME; // 0x0
	private const String MISS_TEXT; // 0x0
	private const String BLOCKED_TEXT; // 0x0
	private static readonly Vector3 PREDEFINED_LOCATION_COST_OFFSET; // 0x0
	private static readonly Vector3 PREDEFINED_LOCATION_LEGION_CARD_PENDING_OFFSET; // 0xc
	private static readonly Vector3 PREDEFINED_LOCATION_FUNLIVE_PHOTO_PENDING_OFFSET; // 0x18
	private Camera _uiCamera; // 0x18
	private Canvas _rootCanvas; // 0x20
	private Canvas _perspectiveCanvas; // 0x28
	private UITopBar _topBar; // 0x30
	private UICharacterInfoPanel _characterInfo; // 0x38
	private UIFakeBlur _fakeBlur; // 0x40
	private UICardList _cardList; // 0x48
	private UIToastController _toastController; // 0x50
	private UIHintController _hintController; // 0x58
	private UIAutoBattlePanel _autoBattlePanel; // 0x60
	private UIBattleSystemMenuPanel _systemMenuPanel; // 0x68
	private UICostPanel _costPanel; // 0x70
	private RectTransform _hudPanel; // 0x78
	private RectTransform _tempPanel; // 0x80
	private RectTransform _tempPanelPerspective; // 0x88
	private UIUnitHUD _characterHud; // 0x90
	private UIUnitHUD _enemyHud; // 0x98
	private UIUnitHUD _enemyBossHud; // 0xa0
	private UIUnitHUD _trapHud; // 0xa8
	private UINumericText _damageText; // 0xb0
	private UINumericText _healText; // 0xb8
	private UINumericText _blockText; // 0xc0
	private UIMessageText _messageText; // 0xc8
	private UIMessageText _messageTextSlow; // 0xd0
	private UIEnemyGiantBossInfoPanel _enemyBossInfo; // 0xd8
	private UIAnimationPerform _battleAccomplishedPerform; // 0xe0
	private UIDirectionSelector _directionSelector; // 0xe8
	private ObjectConfig[] _additionalPreloads; // 0xf0
	private UIStateNode[] _states; // 0xf8
	private UICharacterMenuState _characterMenuState; // 0x100
	private UIRemainingAvailableCharacter _remainingCharacter; // 0x108
	private List`1 _hideWhenDialog; // 0x110
	private RectTransform _groupRoot; // 0x118
	private RectTransform _groupStatic; // 0x120
	private RectTransform _groupTop; // 0x128
	private RectTransform _groupTopBar; // 0x130
	private RectTransform _groupDialogue; // 0x138
	private RectTransform _groupEnemy; // 0x140
	private UIEnemyGiantBossInfoPanel m_enemyBossInfo; // 0x148
	private Boolean m_isPerspectiveCanvasOn; // 0x150
	private Camera m_uiPerspectiveCamera; // 0x158
	private UIStateMachine m_stateMachine; // 0x160
	private ListDict`2 m_stateParams; // 0x168
	private EventPool`1 m_eventPool; // 0x170
	private Dictionary`2 m_hudMap; // 0x178
	private BattleFunctionDisableMask m_functionDisableMask; // 0x180
	private UICanvasScalerHelper m_canvasScalerHelper; // 0x188
	private Single m_cameraHudScale; // 0x190
	private TileInfoController _tileInfoController; // 0x198
	private VoicePlayer m_voicePlayer; // 0x1a0
	private ListDict`2 m_hideCache; // 0x1a8
	private Dictionary`2 m_loadedUIPlugins; // 0x1b0
	private Dictionary`2 m_runTimeUIPluginRefCount; // 0x1b8
	private UIAutoBattlePanel m_autoBattlePanel; // 0x1c0
	private Boolean <isGuideMode>k__BackingField; // 0x1c8
	private BattleController <controller>k__BackingField; // 0x1d0
	private IAVGTutorialPanelPlugin <avgTutorialPlugin>k__BackingField; // 0x1d8
	private Plugin <plugin>k__BackingField; // 0x1e0
	private static DelegateBridge __Hotfix0_get_stateMachine; // 0x28
	private static DelegateBridge __Hotfix0_get_currentState; // 0x30
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x38
	private static DelegateBridge __Hotfix0_get_topbar; // 0x40
	private static DelegateBridge __Hotfix0_get_characterMenuState; // 0x48
	private static DelegateBridge __Hotfix0_get_fakeBlur; // 0x50
	private static DelegateBridge __Hotfix0_get_directionSelector; // 0x58
	private static DelegateBridge __Hotfix0_get_battleAccomplishedPerform; // 0x60
	private static DelegateBridge __Hotfix0_get_hudPanel; // 0x68
	private static DelegateBridge __Hotfix0_get_toastController; // 0x70
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x78
	private static DelegateBridge __Hotfix0_get_perspectiveCanvas; // 0x80
	private static DelegateBridge __Hotfix0_get_cardList; // 0x88
	private static DelegateBridge __Hotfix0_get_scalerHelper; // 0x90
	private static DelegateBridge __Hotfix0_get_autoBattlePanel; // 0x98
	private static DelegateBridge __Hotfix0_get_groupRoot; // 0xa0
	private static DelegateBridge __Hotfix0_get_groupStatic; // 0xa8
	private static DelegateBridge __Hotfix0_get_groupTop; // 0xb0
	private static DelegateBridge __Hotfix0_get_groupTopBar; // 0xb8
	private static DelegateBridge __Hotfix0_get_hideWhenDialog; // 0xc0
	private static DelegateBridge __Hotfix0_get_groupDialogue; // 0xc8
	private static DelegateBridge __Hotfix0_get_tempPanelPerspective; // 0xd0
	private static DelegateBridge __Hotfix0_get_camera; // 0xd8
	private static DelegateBridge __Hotfix0_get_isPaused; // 0xe0
	private static DelegateBridge __Hotfix0_get_isPausedButNotInGuideMode; // 0xe8
	private static DelegateBridge __Hotfix0_get_enableUIShowCardState; // 0xf0
	private static DelegateBridge __Hotfix0_get_isGuideMode; // 0xf8
	private static DelegateBridge __Hotfix0_set_isGuideMode; // 0x100
	private static DelegateBridge __Hotfix0_get_isPerspectiveCanvasOn; // 0x108
	private static DelegateBridge __Hotfix0_set_isPerspectiveCanvasOn; // 0x110
	private static DelegateBridge __Hotfix0_get_controller; // 0x118
	private static DelegateBridge __Hotfix0_set_controller; // 0x120
	private static DelegateBridge __Hotfix0_get_avgTutorialPlugin; // 0x128
	private static DelegateBridge __Hotfix0_set_avgTutorialPlugin; // 0x130
	private static DelegateBridge __Hotfix0_get_plugin; // 0x138
	private static DelegateBridge __Hotfix0_set_plugin; // 0x140
	private static DelegateBridge __Hotfix0_get_needReleaseIllust; // 0x148
	private static DelegateBridge __Hotfix0_get_enemyBossInfo; // 0x150
	private static DelegateBridge __Hotfix0_get_showCharacterStatusInDummy; // 0x158
	private static DelegateBridge __Hotfix0_OnCardMenuShow; // 0x160
	private static DelegateBridge __Hotfix0_CanPluginPressBackButton; // 0x168
	private static DelegateBridge __Hotfix0_OnCharacterMenuShow; // 0x170
	private static DelegateBridge __Hotfix0_OnCharacterMenuHide; // 0x178
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x180
	private static DelegateBridge __Hotfix0_SetPaused; // 0x188
	private static DelegateBridge __Hotfix0_RaiseTutorialSignal; // 0x190
	private static DelegateBridge __Hotfix0_RaiseTutorialSignalIfRuning; // 0x198
	private static DelegateBridge __Hotfix0_RegisterTutorialExtraBattleTarget; // 0x1a0
	private static DelegateBridge __Hotfix0_TryMatchingTutorialWaitSignalStringParam; // 0x1a8
	private static DelegateBridge __Hotfix0_OnCardBeginDrag; // 0x1b0
	private static DelegateBridge __Hotfix0_OnCardEndDrag; // 0x1b8
	private static DelegateBridge __Hotfix0_OnCardToggled; // 0x1c0
	private static DelegateBridge __Hotfix0_HideCharacterInfo; // 0x1c8
	private static DelegateBridge __Hotfix0_UpdateCardListToggleGroup; // 0x1d0
	private static DelegateBridge __Hotfix0_OnBottomMaskClicked; // 0x1d8
	private static DelegateBridge __Hotfix0_OnBottomMaskDrag; // 0x1e0
	private static DelegateBridge __Hotfix0_OnBottomMaskBeginDrag; // 0x1e8
	private static DelegateBridge __Hotfix0_OnBottomMaskEndDrag; // 0x1f0
	private static DelegateBridge __Hotfix0_OnBottomMaskDown; // 0x1f8
	private static DelegateBridge __Hotfix0_OnBottomMaskUp; // 0x200
	private static DelegateBridge __Hotfix0_PrepareThenRestartGame; // 0x208
	private static DelegateBridge __Hotfix0_RestartGame; // 0x210
	private static DelegateBridge __Hotfix0_GameToUIWorldPos; // 0x218
	private static DelegateBridge __Hotfix0_GameToUIPixel; // 0x220
	private static DelegateBridge __Hotfix0_EnableFunction; // 0x228
	private static DelegateBridge __Hotfix0_DisableFunction; // 0x230
	private static DelegateBridge __Hotfix0_HasFunction; // 0x238
	private static DelegateBridge __Hotfix0_OnApplicationPause; // 0x240
	private static DelegateBridge __Hotfix0__TriggerPauseWhenApplicationPaused; // 0x248
	private static DelegateBridge __Hotfix0__UpdateDisableMask; // 0x250
	private static DelegateBridge __Hotfix0__UpdateGameInfo; // 0x258
	private static DelegateBridge __Hotfix0__UpdateHudScaleIfNot; // 0x260
	private static DelegateBridge __Hotfix0__LoadRuntimeUIPluginIfNot; // 0x268
	private static DelegateBridge __Hotfix0_AddRuntimeUIPlugin; // 0x270
	private static DelegateBridge __Hotfix0_RemoveRuntimeUIPlugin; // 0x278
	private static DelegateBridge __Hotfix0__InitStateMachine; // 0x280
	private static DelegateBridge __Hotfix0__TryCreatePlugin; // 0x288
	private static DelegateBridge __Hotfix0__CreatePluginByLevelData; // 0x290
	private static DelegateBridge __Hotfix0_SetUIStateParam; // 0x298
	private static DelegateBridge __Hotfix0_GetUIStateParam; // 0x2a0
	private static DelegateBridge __Hotfix0_UIPixelToWorldVector; // 0x2a8
	private static DelegateBridge __Hotfix0_ShowModifierText; // 0x2b0
	private static DelegateBridge __Hotfix0_ShowNumericText; // 0x2b8
	private static DelegateBridge __Hotfix0_ShowMessageText; // 0x2c0
	private static DelegateBridge __Hotfix1_ShowMessageText; // 0x2c8
	private static DelegateBridge __Hotfix0_ShowSlowMessageText; // 0x2d0
	private static DelegateBridge __Hotfix0_ShowGameModeNumericTest; // 0x2d8
	private static DelegateBridge __Hotfix0_SwitchToBattleFinishService; // 0x2e0
	private static DelegateBridge __Hotfix0_SwitchToBattleFailedState; // 0x2e8
	private static DelegateBridge __Hotfix0_SwitchToBattleAccomplishedState; // 0x2f0
	private static DelegateBridge __Hotfix0_SwitchToDialogState; // 0x2f8
	private static DelegateBridge __Hotfix0_OnSystemMenuCancel; // 0x300
	private static DelegateBridge __Hotfix0_ShowDynamicHUDGroup; // 0x308
	private static DelegateBridge __Hotfix0_ShowHint; // 0x310
	private static DelegateBridge __Hotfix0_AttachHudPlugin; // 0x318
	private static DelegateBridge __Hotfix0_PrepareHideForDialog; // 0x320
	private static DelegateBridge __Hotfix0_RestoreHideForDialog; // 0x328
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x330
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x338
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x340
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x348
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x350
	private static DelegateBridge __Hotfix0_OnSwitchToBattleFinish; // 0x358
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x360
	private static DelegateBridge __Hotfix0_GetPredefinedLocationByUI; // 0x368
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x370
	private static DelegateBridge __Hotfix0__GetDefaultHud; // 0x378
	private static DelegateBridge __Hotfix0__OnUnitSwitchSide; // 0x380
	private static DelegateBridge __Hotfix0__OnGiantBossEnter; // 0x388
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x390
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x398
	private static DelegateBridge __Hotfix0__OnDisplayEnemyInfo; // 0x3a0
	private static DelegateBridge __Hotfix0__OnBlockAnyRoutes; // 0x3a8
	private static DelegateBridge __Hotfix0__OnDisplayLegionBlastCard; // 0x3b0
	private static DelegateBridge __Hotfix0__OnDisplayDeckBuffEffect; // 0x3b8
	private static DelegateBridge __Hotfix0__OnAutoReplayModeChanged; // 0x3c0
	private static DelegateBridge __Hotfix0__OnAutoReplayFinished; // 0x3c8
	private static DelegateBridge __Hotfix0_Awake; // 0x3d0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x3d8
	private static DelegateBridge __Hotfix0_Update; // 0x3e0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x3e8

	public UIStateMachine stateMachine { get; }
	public UIStateEnum currentState { get; }
	public EventPool`1 eventPool { get; }
	public UITopBar topbar { get; }
	public UICharacterMenuState characterMenuState { get; }
	public UIFakeBlur fakeBlur { get; }
	public UIDirectionSelector directionSelector { get; }
	public UIAnimationPerform battleAccomplishedPerform { get; }
	public Transform hudPanel { get; }
	public UIToastController toastController { get; }
	public UICharacterInfoPanel characterInfo { get; }
	public Canvas perspectiveCanvas { get; }
	public UICardList cardList { get; }
	public UICanvasScalerHelper scalerHelper { get; }
	private UIAutoBattlePanel autoBattlePanel { get; }
	public RectTransform groupRoot { get; }
	public RectTransform groupStatic { get; }
	public RectTransform groupTop { get; }
	public RectTransform groupTopBar { get; }
	public List`1 hideWhenDialog { get; }
	public RectTransform groupDialogue { get; }
	public RectTransform tempPanelPerspective { get; }
	public Camera camera { get; }
	public Boolean isPaused { get; }
	public Boolean isPausedButNotInGuideMode { get; }
	public Boolean enableUIShowCardState { get; }
	public Boolean isGuideMode { get; set; }
	public Boolean isPerspectiveCanvasOn { get; set; }
	private BattleController controller { get; set; }
	public IAVGTutorialPanelPlugin avgTutorialPlugin { get; set; }
	public Plugin plugin { get; set; }
	public Boolean needReleaseIllust { get; }
	private UIEnemyGiantBossInfoPanel enemyBossInfo { get; }
	public Boolean showCharacterStatusInDummy { get; }

	// RVA: 0x205e078 VA: 0x7594676078
	public UIStateMachine get_stateMachine() { }
	// RVA: 0x205e0f0 VA: 0x75946760f0
	public UIStateEnum get_currentState() { }
	// RVA: 0x205e178 VA: 0x7594676178
	public EventPool`1 get_eventPool() { }
	// RVA: 0x205e1f0 VA: 0x75946761f0
	public UITopBar get_topbar() { }
	// RVA: 0x205e268 VA: 0x7594676268
	public UICharacterMenuState get_characterMenuState() { }
	// RVA: 0x205e2e0 VA: 0x75946762e0
	public UIFakeBlur get_fakeBlur() { }
	// RVA: 0x205e358 VA: 0x7594676358
	public UIDirectionSelector get_directionSelector() { }
	// RVA: 0x205e3d0 VA: 0x75946763d0
	public UIAnimationPerform get_battleAccomplishedPerform() { }
	// RVA: 0x205e448 VA: 0x7594676448
	public Transform get_hudPanel() { }
	// RVA: 0x205e4c0 VA: 0x75946764c0
	public UIToastController get_toastController() { }
	// RVA: 0x205e538 VA: 0x7594676538
	public UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x205e5b0 VA: 0x75946765b0
	public Canvas get_perspectiveCanvas() { }
	// RVA: 0x205e628 VA: 0x7594676628
	public UICardList get_cardList() { }
	// RVA: 0x205e6a0 VA: 0x75946766a0
	public UICanvasScalerHelper get_scalerHelper() { }
	// RVA: 0x205e760 VA: 0x7594676760
	private UIAutoBattlePanel get_autoBattlePanel() { }
	// RVA: 0x205ea1c VA: 0x7594676a1c
	public RectTransform get_groupRoot() { }
	// RVA: 0x205e9a4 VA: 0x75946769a4
	public RectTransform get_groupStatic() { }
	// RVA: 0x205ea94 VA: 0x7594676a94
	public RectTransform get_groupTop() { }
	// RVA: 0x205eb0c VA: 0x7594676b0c
	public RectTransform get_groupTopBar() { }
	// RVA: 0x205eb84 VA: 0x7594676b84
	public List`1 get_hideWhenDialog() { }
	// RVA: 0x205ebfc VA: 0x7594676bfc
	public RectTransform get_groupDialogue() { }
	// RVA: 0x205ec74 VA: 0x7594676c74
	public RectTransform get_tempPanelPerspective() { }
	// RVA: 0x205ecec VA: 0x7594676cec
	public Camera get_camera() { }
	// RVA: 0x205ed64 VA: 0x7594676d64
	public Boolean get_isPaused() { }
	// RVA: 0x205eee0 VA: 0x7594676ee0
	public Boolean get_isPausedButNotInGuideMode() { }
	// RVA: 0x205eff0 VA: 0x7594676ff0
	public Boolean get_enableUIShowCardState() { }
	// RVA: 0x205ef78 VA: 0x7594676f78
	public Boolean get_isGuideMode() { }
	// RVA: 0x205f104 VA: 0x7594677104
	public Void set_isGuideMode(Boolean value) { }
	// RVA: 0x205f194 VA: 0x7594677194
	public Boolean get_isPerspectiveCanvasOn() { }
	// RVA: 0x205f20c VA: 0x759467720c
	public Void set_isPerspectiveCanvasOn(Boolean value) { }
	// RVA: 0x205f3a4 VA: 0x75946773a4
	private BattleController get_controller() { }
	// RVA: 0x205f41c VA: 0x759467741c
	private Void set_controller(BattleController value) { }
	// RVA: 0x205f4b0 VA: 0x75946774b0
	public IAVGTutorialPanelPlugin get_avgTutorialPlugin() { }
	// RVA: 0x205f528 VA: 0x7594677528
	private Void set_avgTutorialPlugin(IAVGTutorialPanelPlugin value) { }
	// RVA: 0x205ee68 VA: 0x7594676e68
	public Plugin get_plugin() { }
	// RVA: 0x205f5bc VA: 0x75946775bc
	private Void set_plugin(Plugin value) { }
	// RVA: 0x205f650 VA: 0x7594677650
	public Boolean get_needReleaseIllust() { }
	// RVA: 0x205f734 VA: 0x7594677734
	private UIEnemyGiantBossInfoPanel get_enemyBossInfo() { }
	// RVA: 0x205f854 VA: 0x7594677854
	public Boolean get_showCharacterStatusInDummy() { }
	// RVA: 0x205f938 VA: 0x7594677938
	public Void OnCardMenuShow(Card card) { }
	// RVA: 0x205fa38 VA: 0x7594677a38
	public Boolean CanPluginPressBackButton() { }
	// RVA: 0x205fb20 VA: 0x7594677b20
	public Void OnCharacterMenuShow(Character character) { }
	// RVA: 0x205fc20 VA: 0x7594677c20
	public Void OnCharacterMenuHide() { }
	// RVA: 0x205fd04 VA: 0x7594677d04
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x205fe98 VA: 0x7594677e98
	public Boolean SetPaused(Boolean value, Boolean quiet, Boolean force) { }
	// RVA: 0x205ff94 VA: 0x7594677f94
	public Void RaiseTutorialSignal(String signal) { }
	// RVA: 0x206007c VA: 0x759467807c
	public Void RaiseTutorialSignalIfRuning(String signal) { }
	// RVA: 0x2060170 VA: 0x7594678170
	public Void RegisterTutorialExtraBattleTarget(String signal, GameObject target) { }
	// RVA: 0x20602e0 VA: 0x75946782e0
	public Boolean TryMatchingTutorialWaitSignalStringParam(String waitSignal, String paramKey, String targetValue) { }
	// RVA: 0x20603dc VA: 0x75946783dc
	public Void OnCardBeginDrag(UICard card) { }
	// RVA: 0x2060494 VA: 0x7594678494
	public Void OnCardEndDrag(UICard card) { }
	// RVA: 0x206054c VA: 0x759467854c
	public Void OnCardToggled(UICard card, Boolean isOn) { }
	// RVA: 0x2060770 VA: 0x7594678770
	public Void HideCharacterInfo(Boolean unselectActiveCard) { }
	// RVA: 0x206087c VA: 0x759467887c
	public Void UpdateCardListToggleGroup(Boolean isEnabled) { }
	// RVA: 0x2060918 VA: 0x7594678918
	public Void OnBottomMaskClicked(Object arg) { }
	// RVA: 0x2060a98 VA: 0x7594678a98
	public Void OnBottomMaskDrag(Object arg) { }
	// RVA: 0x2060b50 VA: 0x7594678b50
	public Void OnBottomMaskBeginDrag(Object arg) { }
	// RVA: 0x2060c08 VA: 0x7594678c08
	public Void OnBottomMaskEndDrag(Object arg) { }
	// RVA: 0x2060cc0 VA: 0x7594678cc0
	public Void OnBottomMaskDown() { }
	// RVA: 0x2060d74 VA: 0x7594678d74
	public Void OnBottomMaskUp() { }
	// RVA: 0x2060e28 VA: 0x7594678e28
	public Void PrepareThenRestartGame() { }
	// RVA: 0x2060ef8 VA: 0x7594678ef8
	public Void RestartGame() { }
	// RVA: 0x205dec0 VA: 0x7594675ec0
	public Vector2 GameToUIWorldPos(Vector3 position) { }
	// RVA: 0x2061004 VA: 0x7594679004
	public Vector2 GameToUIPixel(Vector3 position) { }
	// RVA: 0x2061108 VA: 0x7594679108
	public Void EnableFunction(BattleFunctionDisableMask mask) { }
	// RVA: 0x2061348 VA: 0x7594679348
	public Void DisableFunction(BattleFunctionDisableMask mask) { }
	// RVA: 0x20613dc VA: 0x75946793dc
	public Boolean HasFunction(BattleFunctionDisableMask mask) { }
	// RVA: 0x2061470 VA: 0x7594679470
	public Void OnApplicationPause(Boolean paused) { }
	// RVA: 0x2061544 VA: 0x7594679544
	private Void _TriggerPauseWhenApplicationPaused() { }
	// RVA: 0x206119c VA: 0x759467919c
	private Void _UpdateDisableMask(BattleFunctionDisableMask mask) { }
	// RVA: 0x2061690 VA: 0x7594679690
	private Void _UpdateGameInfo() { }
	// RVA: 0x206189c VA: 0x759467989c
	private Void _UpdateHudScaleIfNot() { }
	// RVA: 0x20619f0 VA: 0x75946799f0
	private RectTransform _LoadRuntimeUIPluginIfNot(String name) { }
	// RVA: 0x2061b74 VA: 0x7594679b74
	public Void AddRuntimeUIPlugin(RtUIPluginPosition position, String name) { }
	// RVA: 0x2061d50 VA: 0x7594679d50
	public Void RemoveRuntimeUIPlugin(String name) { }
	// RVA: 0x2061ef8 VA: 0x7594679ef8
	private Void _InitStateMachine() { }
	// RVA: 0x2062194 VA: 0x759467a194
	private Void _TryCreatePlugin() { }
	// RVA: 0x2062440 VA: 0x759467a440
	private GameObject _CreatePluginByLevelData(LevelData levelData) { }
	// RVA: 0x2062648 VA: 0x759467a648
	public Void SetUIStateParam(UIStateEnum targetState, Object param) { }
	// RVA: 0x VA: 0x0
	public T GetUIStateParam(UIStateEnum targetState) { }
	// RVA: 0x2062704 VA: 0x759467a704
	public Vector2 UIPixelToWorldVector(Vector2 vector) { }
	// RVA: 0x20627b8 VA: 0x759467a7b8
	public Void ShowModifierText(ref Modifier modifier, Transform spawnPoint) { }
	// RVA: 0x2062e28 VA: 0x759467ae28
	public Void ShowNumericText(ref Modifier modifier, Transform spawnPoint, UINumericText _text, Boolean useFixedValue, Int32 value) { }
	// RVA: 0x2062b10 VA: 0x759467ab10
	public Void ShowMessageText(String message, Transform spawnPoint) { }
	// RVA: 0x2062c78 VA: 0x759467ac78
	public Void ShowMessageText(String message, Transform spawnPoint, Color color) { }
	// RVA: 0x2062ff0 VA: 0x759467aff0
	public Void ShowSlowMessageText(String message, Transform spawnPoint, Color color) { }
	// RVA: 0x20631a0 VA: 0x759467b1a0
	public Boolean ShowGameModeNumericTest(Int32 value, Transform spawnPoint, Color color) { }
	// RVA: 0x20632f4 VA: 0x759467b2f4
	public Void SwitchToBattleFinishService(BattleFinishServiceStateParam param) { }
	// RVA: 0x20633e0 VA: 0x759467b3e0
	public Void SwitchToBattleFailedState(BattleFailedStateParam param) { }
	// RVA: 0x2063538 VA: 0x759467b538
	public Void SwitchToBattleAccomplishedState() { }
	// RVA: 0x2063648 VA: 0x759467b648
	public Void SwitchToDialogState(BattleDialogParam param) { }
	// RVA: 0x2063734 VA: 0x759467b734
	public Void OnSystemMenuCancel() { }
	// RVA: 0x2063818 VA: 0x759467b818
	public Void ShowDynamicHUDGroup(Boolean isActive) { }
	// RVA: 0x20639e4 VA: 0x759467b9e4
	public Void ShowHint(String text, BannerStyle style) { }
	// RVA: 0x2063a8c VA: 0x759467ba8c
	public Boolean AttachHudPlugin(Unit unit, Transform plugin) { }
	// RVA: 0x2063b7c VA: 0x759467bb7c
	public Void PrepareHideForDialog() { }
	// RVA: 0x2063e54 VA: 0x759467be54
	public Void RestoreHideForDialog() { }
	// RVA: 0x2064034 VA: 0x759467c034
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x2064634 VA: 0x759467c634
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x2064988 VA: 0x759467c988
	public Void OnGameReady() { }
	// RVA: 0x2064b58 VA: 0x759467cb58
	public Void OnGameStart() { }
	// RVA: 0x2064cb8 VA: 0x759467ccb8
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x2064e54 VA: 0x759467ce54
	public Void OnSwitchToBattleFinish() { }
	// RVA: 0x2064efc VA: 0x759467cefc
	public Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x2065024 VA: 0x759467d024
	public Vector3 GetPredefinedLocationByUI(PredefinedLocation location) { }
	// RVA: 0x2065294 VA: 0x759467d294
	private Void _OnUnitBorn(Unit unit) { }
	// RVA: 0x20655c0 VA: 0x759467d5c0
	private UIUnitHUD _GetDefaultHud(Unit unit) { }
	// RVA: 0x20657ac VA: 0x759467d7ac
	private Void _OnUnitSwitchSide(Unit unit) { }
	// RVA: 0x2065878 VA: 0x759467d878
	private Void _OnGiantBossEnter(Unit unit) { }
	// RVA: 0x20659ac VA: 0x759467d9ac
	private Void _OnUnitFinish(Unit unit) { }
	// RVA: 0x2065c38 VA: 0x759467dc38
	private Void _OnStateChanged(Int32 newState, Int32 oldState) { }
	// RVA: 0x2065d34 VA: 0x759467dd34
	private Void _OnDisplayEnemyInfo(Object arg) { }
	// RVA: 0x2065ecc VA: 0x759467decc
	private Void _OnBlockAnyRoutes(Object arg) { }
	// RVA: 0x2066020 VA: 0x759467e020
	private Void _OnDisplayLegionBlastCard(Object arg) { }
	// RVA: 0x206618c VA: 0x759467e18c
	private Void _OnDisplayDeckBuffEffect(Object arg) { }
	// RVA: 0x206485c VA: 0x759467c85c
	private Void _OnAutoReplayModeChanged(Object arg) { }
	// RVA: 0x20662fc VA: 0x759467e2fc
	private Void _OnAutoReplayFinished(Object arg) { }
	// RVA: 0x2066410 VA: 0x759467e410
	protected override Void Awake() { }
	// RVA: 0x206650c VA: 0x759467e50c
	protected override Void OnDestroy() { }
	// RVA: 0x20666bc VA: 0x759467e6bc
	private Void Update() { }
	// RVA: 0x20667a0 VA: 0x759467e7a0
	public Void .ctor() { }
	// RVA: 0x2066b04 VA: 0x759467eb04
	private static Void .cctor() { }
	// RVA: 0x2066b84 VA: 0x759467eb84
	private Void <OnGameReset>b__201_0(Object arg) { }
	// RVA: 0x2066c04 VA: 0x759467ec04
	private Void <OnGameReset>b__201_1(Object arg) { }
	// RVA: 0x2066c84 VA: 0x759467ec84
	private Void <OnGameReset>b__201_2(Object arg) { }
	// RVA: 0x2066d04 VA: 0x759467ed04
	private Void <OnGameReset>b__201_3(Object arg) { }
}
```