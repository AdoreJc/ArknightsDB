# AutoChessGameMode

**Namespace:** ` `


## Fields

- `DummyManager <dummyManager>k__BackingField`

- `EffectManager <effectManager>k__BackingField`

- `ShopStateRuneManager <shopStateRuneManager>k__BackingField`

- `BinderManager <binderManager>k__BackingField`

- `AutoChessSchedulerPreprocessor m_preprocessor`

- `AutoChessStateMachine m_states`

- `AutoChessGameModeWaveHandler m_waveHandler`

- `AutoChessBattleRequestHelper m_requestHelper`

- `AutoChessEventHandler m_eventHandler`

- `AutoChessMiscConfig m_config`

- `PredefinedData m_startLevelPredefined`

- `AdvancedRuneHolder m_runeHolder`

- `LevelData m_levelData`

- `SeqNumChecker m_serverMsgStartChecker`

- `SeqNumChecker m_serverMsgFinishChecker`

- `ResourceCollectHandler m_resourceCollectHandler`

- `String m_battleFinishResultCache`

- `Int32 m_retryCnt`

- `String m_actId`


## Properties

- `GameStatus status`

- `LevelData levelData`

- `GameState gameState`

- `AutoChessBattleRequestHelper requestHelper`

- `DummyManager dummyManager`

- `EffectManager effectManager`

- `ShopStateRuneManager shopStateRuneManager`

- `BinderManager binderManager`

- `String actId`

- `Boolean isInBattleState`

- `AutoChessMiscConfig config`


## Methods

- `GameStatus get_status()`

- `LevelData get_levelData()`

- `GameState get_gameState()`

- `AutoChessBattleRequestHelper get_requestHelper()`

- `DummyManager get_dummyManager()`

- `Void set_dummyManager(DummyManager)`

- `EffectManager get_effectManager()`

- `Void set_effectManager(EffectManager)`

- `ShopStateRuneManager get_shopStateRuneManager()`

- `Void set_shopStateRuneManager(ShopStateRuneManager)`

- `BinderManager get_binderManager()`

- `Void set_binderManager(BinderManager)`

- `String get_actId()`

- `Boolean get_isInBattleState()`

- `AutoChessMiscConfig get_config()`

- `Void _PreprocessExtraTriggerRune(RuneManager)`

- `Void _PreprocessTriggerEquipOwnerRune(RuneManager, Dictionary`2)`

- `Void _PreprocessTriggerAllEquipRune(RuneManager, List`1, out)`

- `Void _OnGameStart(Object)`

- `Void _OnPaused(Object)`

- `Void _ApplyInstDataToSharedData(AutoChessUnitQuery, BattleCharacterData)`

- `Void _UpdateLifePoint()`

- `Void SetGameReadyToFinish()`

- `String GetCurrentBattleLevelId()`

- `Void _DoPostInit()`

- `Void _OnSpeedLevelChanged(Object)`

- `Int32 GetInstId(GridPosition)`

- `AutoChessBuySlotType _GetShopSlotType(Tile)`

- `Int32 GetCurrentTokenCnt(Tile)`

- `Void PlayerOp_FreezeOrUnfreeze()`

- `Void PlayerOp_RefreshStore()`

- `Void PlayerOp_UpdateStore()`

- `Void _PlayerOp_SelectTalent(Object)`

- `Void _DoRetryFail()`

- `Void _DoRoundBattleFinish(String, ref, Boolean)`

- `Void _RouteToProperState()`

- `Void _PlayerOp_Prepare(Object)`

- `Void PlayerOp_UseSpell(Int32, BattleDragOperationHandler, List`1)`

- `Void PlayerOp_Buy()`

- `Void PlayerOp_Sale()`

- `Void PlayerOp_Withdraw()`

- `Void PlayerOp_EquipItem(GridPosition, BattleDragOperationHandler, GridPosition)`

- `Void PlayerOp_ReplaceEquipItem(GridPosition, BattleDragOperationHandler, GridPosition, Int32)`

- `Void PlayerOp_UpdateBattleFieldOperation(BattleDragOperationHandler)`

- `Void HighlightCharacter(Character)`

- `Void AttachRequestLock(String, Func`3, String)`

- `Void DetachRequestLock(String)`

- `Boolean IsRequestLocked(AutoChessServiceMsg, ValueBundle)`

- `Void SetHudLock(Boolean, String)`

- `Void SetDragLock(Boolean, String)`

- `Void OnMessage(AutoChessServiceMsg, ValueBundle)`

- `Void OnPushMessage(AutoChessServiceMsg, ValueBundle)`

- `Boolean OnFail(AutoChessServiceMsg, ValueBundle)`

- `Void _OnPlayerDataChanges(UnifiedServiceSysEvent)`

- `Void _OnLifePointChanged(Object)`

- `Void _RaiseTutorialSignal(String, Boolean)`

- `Void _OnDataUpdated(Object)`

- `Void SwitchState(GameState)`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Boolean <>xLuaBaseProxy_get_allowPoolManagerUnload()`

- `Boolean <>xLuaBaseProxy_get_isLargeMap()`

- `Boolean <>xLuaBaseProxy_get_isLowMemoryGameMode()`

- `BattleOutlineConfig <>xLuaBaseProxy_get_outlineConfig()`

- `Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition()`

- `Boolean <>xLuaBaseProxy_get_useLevelBgm()`

- `Boolean <>xLuaBaseProxy_get_doDefaultSchedule()`

- `Boolean <>xLuaBaseProxy_get_isSupportSlowMotion()`

- `Boolean <>xLuaBaseProxy_HookSeed(out)`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Void <>xLuaBaseProxy_PreprocessRuneData(RuneManager)`

- `DefaultWaveHandler <>xLuaBaseProxy_get_waveHandler()`

- `Void <>xLuaBaseProxy_FinishGame(Action`2, GameResult, Boolean)`

- `Single <>xLuaBaseProxy_GetCompleteProgress()`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition, Tile, Direction, Boolean, Boolean, BattleCharacterData, PlayerSide)`

- `Boolean <>xLuaBaseProxy_IsHasCharacterTile(Tile)`

- `Boolean <>xLuaBaseProxy_IsSkillClickable()`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref)`

- `Void <>xLuaBaseProxy_StartGame(Action)`

- `Boolean <>xLuaBaseProxy_GameNotFinishCondition()`

- `Void <>xLuaBaseProxy_PreprocessLevelData(LevelData)`

- `Void <>xLuaBaseProxy_OnEnemyFinished(Enemy, FinishReason)`

- `Void <>xLuaBaseProxy_OnCharacterFinished(Character, FinishReason)`

- `Boolean <>xLuaBaseProxy_EnableGlobalBuffExtraData(GlobalBuff, GlobalBuffData)`

- `Void <>xLuaBaseProxy_OnCharacterRespawnFailed(Character, Card, PlayerSide)`

- `Void <>xLuaBaseProxy_DestroyEntity(Entity, FinishReason)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_OnPlayerLifeToZero(PlayerSide)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessGameMode : DefaultGameMode, IMsgListener
{
	public static readonly BattleOutlineConfig OUTLINE_CONFIG; // 0x0
	private const Int32 ROUND_BATTLE_FINISH_RETRY_CNT; // 0x0
	private DummyManager <dummyManager>k__BackingField; // 0x20
	private EffectManager <effectManager>k__BackingField; // 0x28
	private ShopStateRuneManager <shopStateRuneManager>k__BackingField; // 0x30
	private BinderManager <binderManager>k__BackingField; // 0x38
	private EventPool`1 m_eventPool; // 0x40
	private AutoChessSchedulerPreprocessor m_preprocessor; // 0x48
	private AutoChessStateMachine m_states; // 0x50
	private AutoChessGameModeWaveHandler m_waveHandler; // 0x58
	private AutoChessBattleRequestHelper m_requestHelper; // 0x60
	private AutoChessEventHandler m_eventHandler; // 0x68
	private AutoChessMiscConfig m_config; // 0x70
	private PredefinedData m_startLevelPredefined; // 0x78
	private AdvancedRuneHolder m_runeHolder; // 0x80
	private LevelData m_levelData; // 0x88
	private SeqNumChecker m_serverMsgStartChecker; // 0x90
	private SeqNumChecker m_serverMsgFinishChecker; // 0x98
	private ResourceCollectHandler m_resourceCollectHandler; // 0xa0
	private String m_battleFinishResultCache; // 0xa8
	private Int32 m_retryCnt; // 0xb0
	private String m_actId; // 0xb8
	private static List`1 s_startBattleInsts; // 0x18
	private Dictionary`2 m_requestLocks; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_get_instance; // 0x28
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x30
	private static DelegateBridge __Hotfix0_get_status; // 0x38
	private static DelegateBridge __Hotfix0_get_levelData; // 0x40
	private static DelegateBridge __Hotfix0_get_gameState; // 0x48
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x50
	private static DelegateBridge __Hotfix0_get_requestHelper; // 0x58
	private static DelegateBridge __Hotfix0_get_dummyManager; // 0x60
	private static DelegateBridge __Hotfix0_set_dummyManager; // 0x68
	private static DelegateBridge __Hotfix0_get_effectManager; // 0x70
	private static DelegateBridge __Hotfix0_set_effectManager; // 0x78
	private static DelegateBridge __Hotfix0_get_shopStateRuneManager; // 0x80
	private static DelegateBridge __Hotfix0_set_shopStateRuneManager; // 0x88
	private static DelegateBridge __Hotfix0_get_binderManager; // 0x90
	private static DelegateBridge __Hotfix0_set_binderManager; // 0x98
	private static DelegateBridge __Hotfix0_get_actId; // 0xa0
	private static DelegateBridge __Hotfix0_get_isInBattleState; // 0xa8
	private static DelegateBridge __Hotfix0_Init; // 0xb0
	private static DelegateBridge __Hotfix0_get_allowPoolManagerUnload; // 0xb8
	private static DelegateBridge __Hotfix0_get_isLargeMap; // 0xc0
	private static DelegateBridge __Hotfix0_get_isLowMemoryGameMode; // 0xc8
	private static DelegateBridge __Hotfix0_get_outlineConfig; // 0xd0
	private static DelegateBridge __Hotfix0_get_hasExtraBuildCondition; // 0xd8
	private static DelegateBridge __Hotfix0_get_useLevelBgm; // 0xe0
	private static DelegateBridge __Hotfix0_get_doDefaultSchedule; // 0xe8
	private static DelegateBridge __Hotfix0_get_isSupportSlowMotion; // 0xf0
	private static DelegateBridge __Hotfix0_HookSeed; // 0xf8
	private static DelegateBridge __Hotfix0_get_config; // 0x100
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x108
	private static DelegateBridge __Hotfix0_PreprocessRuneData; // 0x110
	private static DelegateBridge __Hotfix0__PreprocessExtraTriggerRune; // 0x118
	private static DelegateBridge __Hotfix0__PreprocessTriggerEquipOwnerRune; // 0x120
	private static DelegateBridge __Hotfix0__PreprocessTriggerAllEquipRune; // 0x128
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x130
	private static DelegateBridge __Hotfix0_get_waveHandler; // 0x138
	private static DelegateBridge __Hotfix0_FinishGame; // 0x140
	private static DelegateBridge __Hotfix0_GetCompleteProgress; // 0x148
	private static DelegateBridge __Hotfix0__GetRoundBattleFinishResult; // 0x150
	private static DelegateBridge __Hotfix0_Tick; // 0x158
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x160
	private static DelegateBridge __Hotfix0_IsHasCharacterTile; // 0x168
	private static DelegateBridge __Hotfix0_IsSkillClickable; // 0x170
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x178
	private static DelegateBridge __Hotfix0__OnPaused; // 0x180
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x188
	private static DelegateBridge __Hotfix0_StartGame; // 0x190
	private static DelegateBridge __Hotfix0_GameNotFinishCondition; // 0x198
	private static DelegateBridge __Hotfix0_PreprocessLevelData; // 0x1a0
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x1a8
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x1b0
	private static DelegateBridge __Hotfix0_EnableGlobalBuffExtraData; // 0x1b8
	private static DelegateBridge __Hotfix0_OnCharacterRespawnFailed; // 0x1c0
	private static DelegateBridge __Hotfix0_DestroyEntity; // 0x1c8
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x1d0
	private static DelegateBridge __Hotfix0_OnPlayerLifeToZero; // 0x1d8
	private static DelegateBridge __Hotfix0__ApplyInstDataToSharedData; // 0x1e0
	private static DelegateBridge __Hotfix0__UpdateLifePoint; // 0x1e8
	private static DelegateBridge __Hotfix0_SetGameReadyToFinish; // 0x1f0
	private static DelegateBridge __Hotfix0_GetCurrentBattleLevelId; // 0x1f8
	private static DelegateBridge __Hotfix0__DoPostInit; // 0x200
	private static DelegateBridge __Hotfix0__OnSpeedLevelChanged; // 0x208
	private static DelegateBridge __Hotfix0_GetInstId; // 0x210
	private static DelegateBridge __Hotfix0__GetShopSlotType; // 0x218
	private static DelegateBridge __Hotfix0_GetCurrentTokenCnt; // 0x220
	private static DelegateBridge __Hotfix0_PlayerOp_FreezeOrUnfreeze; // 0x228
	private static DelegateBridge __Hotfix0_PlayerOp_RefreshStore; // 0x230
	private static DelegateBridge __Hotfix0_PlayerOp_UpdateStore; // 0x238
	private static DelegateBridge __Hotfix0__PlayerOp_SelectTalent; // 0x240
	private static DelegateBridge __Hotfix0__DoRetryFail; // 0x248
	private static DelegateBridge __Hotfix0__DoRoundBattleFinish; // 0x250
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x258
	private static DelegateBridge __Hotfix0__PlayerOp_Prepare; // 0x260
	private static DelegateBridge __Hotfix0_PlayerOp_UseSpell; // 0x268
	private static DelegateBridge __Hotfix0_PlayerOp_Buy; // 0x270
	private static DelegateBridge __Hotfix0_PlayerOp_Sale; // 0x278
	private static DelegateBridge __Hotfix0_PlayerOp_Withdraw; // 0x280
	private static DelegateBridge __Hotfix0_PlayerOp_EquipItem; // 0x288
	private static DelegateBridge __Hotfix0_PlayerOp_ReplaceEquipItem; // 0x290
	private static DelegateBridge __Hotfix0_PlayerOp_UpdateBattleFieldOperation; // 0x298
	private static DelegateBridge __Hotfix0_HighlightCharacter; // 0x2a0
	private static DelegateBridge __Hotfix0_AttachRequestLock; // 0x2a8
	private static DelegateBridge __Hotfix0_DetachRequestLock; // 0x2b0
	private static DelegateBridge __Hotfix0_IsRequestLocked; // 0x2b8
	private static DelegateBridge __Hotfix0_SetHudLock; // 0x2c0
	private static DelegateBridge __Hotfix0_SetDragLock; // 0x2c8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x2d0
	private static DelegateBridge __Hotfix0_OnPushMessage; // 0x2d8
	private static DelegateBridge __Hotfix0_OnFail; // 0x2e0
	private static DelegateBridge __Hotfix0__OnPlayerDataChanges; // 0x2e8
	private static DelegateBridge __Hotfix0__OnLifePointChanged; // 0x2f0
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x2f8
	private static DelegateBridge __Hotfix0__OnDataUpdated; // 0x300
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x308
	private static DelegateBridge __Hotfix0_SwitchState; // 0x310

	public static AutoChessGameMode instance { get; }
	public static EventPool`1 eventPool { get; }
	public GameStatus status { get; }
	public LevelData levelData { get; }
	public GameState gameState { get; }
	public override GameModeType gameModeType { get; }
	public AutoChessBattleRequestHelper requestHelper { get; }
	public DummyManager dummyManager { get; set; }
	public EffectManager effectManager { get; set; }
	public ShopStateRuneManager shopStateRuneManager { get; set; }
	public BinderManager binderManager { get; set; }
	public String actId { get; }
	public Boolean isInBattleState { get; }
	public override Boolean allowPoolManagerUnload { get; }
	public override Boolean isLargeMap { get; }
	public override Boolean isLowMemoryGameMode { get; }
	public override BattleOutlineConfig outlineConfig { get; }
	public override Boolean hasExtraBuildCondition { get; }
	public override Boolean useLevelBgm { get; }
	public override Boolean doDefaultSchedule { get; }
	public override Boolean isSupportSlowMotion { get; }
	public AutoChessMiscConfig config { get; }
	public override DefaultWaveHandler waveHandler { get; }

	// RVA: 0x1c8b550 VA: 0x75942a3550
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1c91214 VA: 0x75942a9214
	public static AutoChessGameMode get_instance() { }
	// RVA: 0x1c91304 VA: 0x75942a9304
	public static EventPool`1 get_eventPool() { }
	// RVA: 0x1c91390 VA: 0x75942a9390
	public GameStatus get_status() { }
	// RVA: 0x1c91650 VA: 0x75942a9650
	public LevelData get_levelData() { }
	// RVA: 0x1c916c8 VA: 0x75942a96c8
	public GameState get_gameState() { }
	// RVA: 0x1c9174c VA: 0x75942a974c
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1c917c4 VA: 0x75942a97c4
	public AutoChessBattleRequestHelper get_requestHelper() { }
	// RVA: 0x1c9183c VA: 0x75942a983c
	public DummyManager get_dummyManager() { }
	// RVA: 0x1c918b4 VA: 0x75942a98b4
	private Void set_dummyManager(DummyManager value) { }
	// RVA: 0x1c91948 VA: 0x75942a9948
	public EffectManager get_effectManager() { }
	// RVA: 0x1c919c0 VA: 0x75942a99c0
	private Void set_effectManager(EffectManager value) { }
	// RVA: 0x1c91a54 VA: 0x75942a9a54
	public ShopStateRuneManager get_shopStateRuneManager() { }
	// RVA: 0x1c91acc VA: 0x75942a9acc
	private Void set_shopStateRuneManager(ShopStateRuneManager value) { }
	// RVA: 0x1c91b60 VA: 0x75942a9b60
	public BinderManager get_binderManager() { }
	// RVA: 0x1c91bd8 VA: 0x75942a9bd8
	private Void set_binderManager(BinderManager value) { }
	// RVA: 0x1c91c6c VA: 0x75942a9c6c
	public String get_actId() { }
	// RVA: 0x1c91ce4 VA: 0x75942a9ce4
	public Boolean get_isInBattleState() { }
	// RVA: 0x1c91d80 VA: 0x75942a9d80
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1c923d0 VA: 0x75942aa3d0
	public override Boolean get_allowPoolManagerUnload() { }
	// RVA: 0x1c92448 VA: 0x75942aa448
	public override Boolean get_isLargeMap() { }
	// RVA: 0x1c924c0 VA: 0x75942aa4c0
	public override Boolean get_isLowMemoryGameMode() { }
	// RVA: 0x1c92538 VA: 0x75942aa538
	public override BattleOutlineConfig get_outlineConfig() { }
	// RVA: 0x1c925f4 VA: 0x75942aa5f4
	public override Boolean get_hasExtraBuildCondition() { }
	// RVA: 0x1c9266c VA: 0x75942aa66c
	public override Boolean get_useLevelBgm() { }
	// RVA: 0x1c926e0 VA: 0x75942aa6e0
	public override Boolean get_doDefaultSchedule() { }
	// RVA: 0x1c92754 VA: 0x75942aa754
	public override Boolean get_isSupportSlowMotion() { }
	// RVA: 0x1c927c8 VA: 0x75942aa7c8
	public override Boolean HookSeed(out Int32 seed) { }
	// RVA: 0x1c928bc VA: 0x75942aa8bc
	public AutoChessMiscConfig get_config() { }
	// RVA: 0x1c92a08 VA: 0x75942aaa08
	public override Void OnPostInit() { }
	// RVA: 0x1c92f0c VA: 0x75942aaf0c
	public override Void PreprocessRuneData(RuneManager manager) { }
	// RVA: 0x1c92fc0 VA: 0x75942aafc0
	private Void _PreprocessExtraTriggerRune(RuneManager manager) { }
	// RVA: 0x1c93370 VA: 0x75942ab370
	private Void _PreprocessTriggerEquipOwnerRune(RuneManager manager, Dictionary`2 ownerEquipRune) { }
	// RVA: 0x1c93b38 VA: 0x75942abb38
	private Void _PreprocessTriggerAllEquipRune(RuneManager manager, List`1 equipRune, out Int32 triggerExtraTimes) { }
	// RVA: 0x1c94050 VA: 0x75942ac050
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x1c94100 VA: 0x75942ac100
	public override DefaultWaveHandler get_waveHandler() { }
	// RVA: 0x1c94178 VA: 0x75942ac178
	public override Void FinishGame(Action`2 gameFinishCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1c94564 VA: 0x75942ac564
	public override Single GetCompleteProgress() { }
	// RVA: 0x1c942f0 VA: 0x75942ac2f0
	private static String _GetRoundBattleFinishResult(GameResult result) { }
	// RVA: 0x1c94668 VA: 0x75942ac668
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1c94834 VA: 0x75942ac834
	public override Boolean CheckBuildable(BuildCondition buildCondition, Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1c94ba4 VA: 0x75942acba4
	public override Boolean IsHasCharacterTile(Tile tile) { }
	// RVA: 0x1c94d64 VA: 0x75942acd64
	public override Boolean IsSkillClickable() { }
	// RVA: 0x1c94de8 VA: 0x75942acde8
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1c94e60 VA: 0x75942ace60
	private Void _OnPaused(Object isPaused) { }
	// RVA: 0x1c94fe4 VA: 0x75942acfe4
	public override Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1c950b4 VA: 0x75942ad0b4
	public override Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1c951f0 VA: 0x75942ad1f0
	public override Boolean GameNotFinishCondition() { }
	// RVA: 0x1c95264 VA: 0x75942ad264
	public override Void PreprocessLevelData(LevelData levelData) { }
	// RVA: 0x1c95448 VA: 0x75942ad448
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1c95524 VA: 0x75942ad524
	public override Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1c95600 VA: 0x75942ad600
	public override Boolean EnableGlobalBuffExtraData(GlobalBuff buff, GlobalBuffData data) { }
	// RVA: 0x1c95694 VA: 0x75942ad694
	public override Void OnCharacterRespawnFailed(Character character, Card card, PlayerSide playerSide) { }
	// RVA: 0x1c9578c VA: 0x75942ad78c
	public override Void DestroyEntity(Entity entity, FinishReason reason) { }
	// RVA: 0x1c9586c VA: 0x75942ad86c
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1c95938 VA: 0x75942ad938
	public override Void OnPlayerLifeToZero(PlayerSide side) { }
	// RVA: 0x1c959c0 VA: 0x75942ad9c0
	private Void _ApplyInstDataToSharedData(AutoChessUnitQuery query, BattleCharacterData charData) { }
	// RVA: 0x1c95b44 VA: 0x75942adb44
	private Void _UpdateLifePoint() { }
	// RVA: 0x1c95cc4 VA: 0x75942adcc4
	public Void SetGameReadyToFinish() { }
	// RVA: 0x1c95d68 VA: 0x75942add68
	public String GetCurrentBattleLevelId() { }
	// RVA: 0x1c92a8c VA: 0x75942aaa8c
	private Void _DoPostInit() { }
	// RVA: 0x1c96128 VA: 0x75942ae128
	private Void _OnSpeedLevelChanged(Object arg) { }
	// RVA: 0x1c9631c VA: 0x75942ae31c
	public Int32 GetInstId(GridPosition pos) { }
	// RVA: 0x1c963d0 VA: 0x75942ae3d0
	private AutoChessBuySlotType _GetShopSlotType(Tile tile) { }
	// RVA: 0x1c964b4 VA: 0x75942ae4b4
	public Int32 GetCurrentTokenCnt(Tile tokenRootTile) { }
	// RVA: 0x1c96790 VA: 0x75942ae790
	public Void PlayerOp_FreezeOrUnfreeze() { }
	// RVA: 0x1c96cd4 VA: 0x75942aecd4
	public Void PlayerOp_RefreshStore() { }
	// RVA: 0x1c96f80 VA: 0x75942aef80
	public Void PlayerOp_UpdateStore() { }
	// RVA: 0x1c9712c VA: 0x75942af12c
	public Void _PlayerOp_SelectTalent(Object arg) { }
	// RVA: 0x1c97368 VA: 0x75942af368
	private Void _DoRetryFail() { }
	// RVA: 0x1c94494 VA: 0x75942ac494
	private Void _DoRoundBattleFinish(String result, ref Int32 retryCnt, Boolean isRetry) { }
	// RVA: 0x1c973ec VA: 0x75942af3ec
	private Void _RouteToProperState() { }
	// RVA: 0x1c97548 VA: 0x75942af548
	private Void _PlayerOp_Prepare(Object arg) { }
	// RVA: 0x1c9788c VA: 0x75942af88c
	public Void PlayerOp_UseSpell(Int32 instId, BattleDragOperationHandler handler, List`1 charChessInstIds) { }
	// RVA: 0x1c97ce0 VA: 0x75942afce0
	public Void PlayerOp_Buy() { }
	// RVA: 0x1c980cc VA: 0x75942b00cc
	public Void PlayerOp_Sale() { }
	// RVA: 0x1c98318 VA: 0x75942b0318
	public Void PlayerOp_Withdraw() { }
	// RVA: 0x1c98518 VA: 0x75942b0518
	public Void PlayerOp_EquipItem(GridPosition equipPos, BattleDragOperationHandler handler, GridPosition charPos) { }
	// RVA: 0x1c98754 VA: 0x75942b0754
	public Void PlayerOp_ReplaceEquipItem(GridPosition equipPos, BattleDragOperationHandler handler, GridPosition charPos, Int32 unloadEquipInstId) { }
	// RVA: 0x1c989b8 VA: 0x75942b09b8
	public Void PlayerOp_UpdateBattleFieldOperation(BattleDragOperationHandler handler) { }
	// RVA: 0x1c98a8c VA: 0x75942b0a8c
	public Void HighlightCharacter(Character character) { }
	// RVA: 0x1c98bb0 VA: 0x75942b0bb0
	public Void AttachRequestLock(String key, Func`3 lockFunc, String hint) { }
	// RVA: 0x1c98cd0 VA: 0x75942b0cd0
	public Void DetachRequestLock(String key) { }
	// RVA: 0x1c969f4 VA: 0x75942ae9f4
	public Boolean IsRequestLocked(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x1c98dc4 VA: 0x75942b0dc4
	public Void SetHudLock(Boolean isLocked, String reason) { }
	// RVA: 0x1c98e90 VA: 0x75942b0e90
	public Void SetDragLock(Boolean isLocked, String reason) { }
	// RVA: 0x1c98f5c VA: 0x75942b0f5c
	public Void OnMessage(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x1c99068 VA: 0x75942b1068
	public Void OnPushMessage(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x1c99138 VA: 0x75942b1138
	public Boolean OnFail(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x1c992d4 VA: 0x75942b12d4
	private Void _OnPlayerDataChanges(UnifiedServiceSysEvent eventType) { }
	// RVA: 0x1c99394 VA: 0x75942b1394
	private Void _OnLifePointChanged(Object obj) { }
	// RVA: 0x1c96e80 VA: 0x75942aee80
	private Void _RaiseTutorialSignal(String signal, Boolean checkRunning) { }
	// RVA: 0x1c99420 VA: 0x75942b1420
	private Void _OnDataUpdated(Object obj) { }
	// RVA: 0x1c997e8 VA: 0x75942b17e8
	public override Void OnDestroy() { }
	// RVA: 0x1c998c8 VA: 0x75942b18c8
	public Void SwitchState(GameState state) { }
	// RVA: 0x1c99978 VA: 0x75942b1978
	private static Void .cctor() { }
	// RVA: 0x1c99a90 VA: 0x75942b1a90
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1c99a98 VA: 0x75942b1a98
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1c99aa0 VA: 0x75942b1aa0
	private Boolean <>xLuaBaseProxy_get_allowPoolManagerUnload() { }
	// RVA: 0x1c99aa8 VA: 0x75942b1aa8
	private Boolean <>xLuaBaseProxy_get_isLargeMap() { }
	// RVA: 0x1c99ab0 VA: 0x75942b1ab0
	private Boolean <>xLuaBaseProxy_get_isLowMemoryGameMode() { }
	// RVA: 0x1c99ab8 VA: 0x75942b1ab8
	private BattleOutlineConfig <>xLuaBaseProxy_get_outlineConfig() { }
	// RVA: 0x1c99aec VA: 0x75942b1aec
	private Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition() { }
	// RVA: 0x1c99af4 VA: 0x75942b1af4
	private Boolean <>xLuaBaseProxy_get_useLevelBgm() { }
	// RVA: 0x1c99afc VA: 0x75942b1afc
	private Boolean <>xLuaBaseProxy_get_doDefaultSchedule() { }
	// RVA: 0x1c99b04 VA: 0x75942b1b04
	private Boolean <>xLuaBaseProxy_get_isSupportSlowMotion() { }
	// RVA: 0x1c99b0c VA: 0x75942b1b0c
	private Boolean <>xLuaBaseProxy_HookSeed(out Int32 P0) { }
	// RVA: 0x1c99b14 VA: 0x75942b1b14
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x1c99b1c VA: 0x75942b1b1c
	private Void <>xLuaBaseProxy_PreprocessRuneData(RuneManager P0) { }
	// RVA: 0x1c99b24 VA: 0x75942b1b24
	private DefaultWaveHandler <>xLuaBaseProxy_get_waveHandler() { }
	// RVA: 0x1c99b2c VA: 0x75942b1b2c
	private Void <>xLuaBaseProxy_FinishGame(Action`2 P0, GameResult P1, Boolean P2) { }
	// RVA: 0x1c99b38 VA: 0x75942b1b38
	private Single <>xLuaBaseProxy_GetCompleteProgress() { }
	// RVA: 0x1c99b40 VA: 0x75942b1b40
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1c99b48 VA: 0x75942b1b48
	private Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition P0, Tile P1, Direction P2, Boolean P3, Boolean P4, BattleCharacterData P5, PlayerSide P6) { }
	// RVA: 0x1c99bc8 VA: 0x75942b1bc8
	private Boolean <>xLuaBaseProxy_IsHasCharacterTile(Tile P0) { }
	// RVA: 0x1c99bd0 VA: 0x75942b1bd0
	private Boolean <>xLuaBaseProxy_IsSkillClickable() { }
	// RVA: 0x1c99bd8 VA: 0x75942b1bd8
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1c99be0 VA: 0x75942b1be0
	private Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref Modifier P0) { }
	// RVA: 0x1c99be8 VA: 0x75942b1be8
	private Void <>xLuaBaseProxy_StartGame(Action P0) { }
	// RVA: 0x1c99bf0 VA: 0x75942b1bf0
	private Boolean <>xLuaBaseProxy_GameNotFinishCondition() { }
	// RVA: 0x1c99bf8 VA: 0x75942b1bf8
	private Void <>xLuaBaseProxy_PreprocessLevelData(LevelData P0) { }
	// RVA: 0x1c99c00 VA: 0x75942b1c00
	private Void <>xLuaBaseProxy_OnEnemyFinished(Enemy P0, FinishReason P1) { }
	// RVA: 0x1c99c08 VA: 0x75942b1c08
	private Void <>xLuaBaseProxy_OnCharacterFinished(Character P0, FinishReason P1) { }
	// RVA: 0x1c99c10 VA: 0x75942b1c10
	private Boolean <>xLuaBaseProxy_EnableGlobalBuffExtraData(GlobalBuff P0, GlobalBuffData P1) { }
	// RVA: 0x1c99c18 VA: 0x75942b1c18
	private Void <>xLuaBaseProxy_OnCharacterRespawnFailed(Character P0, Card P1, PlayerSide P2) { }
	// RVA: 0x1c99c20 VA: 0x75942b1c20
	private Void <>xLuaBaseProxy_DestroyEntity(Entity P0, FinishReason P1) { }
	// RVA: 0x1c99c28 VA: 0x75942b1c28
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1c99c30 VA: 0x75942b1c30
	private Void <>xLuaBaseProxy_OnPlayerLifeToZero(PlayerSide P0) { }
	// RVA: 0x1c99c38 VA: 0x75942b1c38
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```