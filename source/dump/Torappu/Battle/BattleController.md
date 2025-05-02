# BattleController

**Namespace:** `Torappu.Battle`


## Fields

- `PlayerSide <playerSide>k__BackingField`

- `Map _map`

- `Scheduler _scheduler`

- `BattleFactory _factory`

- `GridRangeDrawer _gridRangeDrawer`

- `Transform _dragPlane`

- `ObjectManager m_objectManger`

- `Context m_context`

- `Single m_originCostIncreaseTime`

- `Boolean m_costAddLocked`

- `BattleLogger m_logger`

- `ReplayController m_replayController`

- `BattleAttackRangeController m_attackRangeController`

- `PredefinedData m_predefines`

- `RuneManager m_runeManager`

- `SpineShaderManager m_spineShaderManager`

- `PlayerOperationQueue m_playerOpQueue`

- `Boolean m_additionalFrame`

- `Action m_pendingGameReadyCallbacks`

- `CoroutineSimulator m_coroutineSimulator`

- `HashCodeBuilder m_hashCodeBuilder`

- `StringBuilder m_snapshotBuilder`

- `StringBuilder m_playerOperationBuilder`

- `BattleTweenMgr m_battleTweenMgr`

- `LevelData m_levelData`

- `MapData m_mapData`

- `IGameMode m_gameMode`

- `ObscuredInt m_randomSeed`

- `ClientAntiCheatChecker m_antiCheatChecker`

- `OperaController m_operaController`

- `Action m_tick`

- `DialogController m_dialogController`

- `BattleSpineOutlineManager m_spineOutlineManager`

- `Int32 m_slowMotionReason`

- `Int32 m_costLockReason`

- `Action m_onGameDoFinish`

- `Boolean m_haveGameLoaded`

- `BattlePluginExternalHost m_externalPluginHost`

- `State m_state`

- `GameResult m_result`

- `SpeedLevel m_speedLevel`

- `Boolean m_speedLevelSlowFlag`

- `Boolean m_alwaysWinWhenFinish`

- `BattleGlobalBlackboard m_globalBlackboard`

- `ObscuredInt m_maxLeftPoint`

- `ObscuredInt m_lifePoint`

- `ObscuredInt m_tempLifePoint`

- `Single m_originTimeScale`

- `Single m_realPlayTime`

- `FP m_timeDeltaNoEnemy`

- `Boolean m_isAutoReplayOn`

- `UnitManager <unitManager>k__BackingField`

- `Boolean <disableDragCard>k__BackingField`

- `Boolean <disableDragCardForced>k__BackingField`

- `Boolean <disableToggleCard>k__BackingField`

- `Boolean m_isSelectCardMode`

- `String <levelId>k__BackingField`

- `SingletonHost m_singletonHost`


## Properties

- `Boolean isOnline`

- `Boolean isMultiActivePlayers`

- `PlayerSide playerSide`

- `PlayerSide playerSideNext`

- `MapLayer playerLayer`

- `Boolean isAtOwnLayer`

- `MapLayer currentLayer`

- `Boolean isLegionMode`

- `Boolean isSandBox`

- `Boolean isFunLivePlayMode`

- `Boolean isStrifeMode`

- `Boolean isRacingMode`

- `Boolean isDouququMode`

- `Boolean isEnemyDuel`

- `Boolean isCooperateMode`

- `Boolean isPvpOrSeperateMode`

- `Boolean isGameCityMode`

- `Int32 randomSeed`

- `BattleTweenMgr battleTweenMgr`

- `BattleAttackRangeController attackRangeController`

- `Map map`

- `MapData mapData`

- `LevelData levelData`

- `Scheduler scheduler`

- `GridRangeDrawer gridRangeDrawer`

- `UnitManager unitManager`

- `Context context`

- `BattleFactory factory`

- `BattleLogger logger`

- `Transform dragPlane`

- `RuneManager runeManager`

- `ReplayController replayController`

- `IGameMode gameMode`

- `SandboxGameMode sandboxGameMode`

- `CooperateGameMode cooperateGameMode`

- `ClientAntiCheatChecker antiCheatChecker`

- `OperaController operaController`

- `SpineShaderManager spineShaderManager`

- `BattleSpineOutlineManager spineOutlineManager`

- `DialogController dialogController`

- `ObjectManager objectManager`

- `Boolean isPlaying`

- `Boolean isFinished`

- `Boolean isPausedOrNotPlaying`

- `Boolean isAutoReplayOn`

- `Boolean isDisableSlowMotion`

- `BattleGlobalBlackboard globalBlackboard`

- `Boolean disableDragCard`

- `Boolean disableDragCardForced`

- `Boolean disableToggleCard`

- `Boolean isCostLocked`

- `Boolean isSelectCardMode`

- `Boolean isAdditionalFrame`

- `Boolean haveGameLoaded`

- `State state`

- `Single realPlayTime`

- `FP timeDeltaNoEnemy`

- `String levelId`

- `Boolean isActive`

- `Boolean isPaused`

- `SpeedLevel speedLevel`

- `Boolean inSlowMotion`

- `Int32 maxLifePoint`

- `Boolean alwaysWinWhenFinish`

- `GameResult gameResult`

- `PlayerBattleRank battleRank`

- `Single costTimerPeriodTime`

- `Int32 remainingEnemiesCnt`

- `Single completeProgress`

- `Single timeScale`


## Methods

- `Boolean get_isOnline()`

- `Boolean get_isMultiActivePlayers()`

- `PlayerSide get_playerSide()`

- `Void set_playerSide(PlayerSide)`

- `PlayerSide get_playerSideNext()`

- `MapLayer get_playerLayer()`

- `Boolean get_isAtOwnLayer()`

- `MapLayer get_currentLayer()`

- `Boolean get_isLegionMode()`

- `Boolean get_isSandBox()`

- `Boolean get_isFunLivePlayMode()`

- `Boolean get_isStrifeMode()`

- `Boolean get_isRacingMode()`

- `Boolean get_isDouququMode()`

- `Boolean get_isEnemyDuel()`

- `Boolean get_isCooperateMode()`

- `Boolean get_isPvpOrSeperateMode()`

- `Boolean get_isGameCityMode()`

- `Int32 get_randomSeed()`

- `BattleTweenMgr get_battleTweenMgr()`

- `BattleAttackRangeController get_attackRangeController()`

- `Map get_map()`

- `MapData get_mapData()`

- `LevelData get_levelData()`

- `Deck GetDeck(PlayerSide)`

- `Deck GetDeck(Entity)`

- `Void ForeachActiveDecks(Action`1)`

- `Void ForeachCard(PlayerSide, Action`1)`

- `Scheduler get_scheduler()`

- `GridRangeDrawer get_gridRangeDrawer()`

- `Void set_gridRangeDrawer(GridRangeDrawer)`

- `UnitManager get_unitManager()`

- `Void set_unitManager(UnitManager)`

- `Context get_context()`

- `BattleFactory get_factory()`

- `BattleLogger get_logger()`

- `Transform get_dragPlane()`

- `RuneManager get_runeManager()`

- `ReplayController get_replayController()`

- `IGameMode get_gameMode()`

- `SandboxGameMode get_sandboxGameMode()`

- `CooperateGameMode get_cooperateGameMode()`

- `ClientAntiCheatChecker get_antiCheatChecker()`

- `OperaController get_operaController()`

- `SpineShaderManager get_spineShaderManager()`

- `BattleSpineOutlineManager get_spineOutlineManager()`

- `DialogController get_dialogController()`

- `ObjectManager get_objectManager()`

- `Boolean get_isPlaying()`

- `Boolean get_isFinished()`

- `Boolean get_isPausedOrNotPlaying()`

- `Boolean get_isAutoReplayOn()`

- `Void set_isAutoReplayOn(Boolean)`

- `Boolean get_isDisableSlowMotion()`

- `BattleGlobalBlackboard get_globalBlackboard()`

- `Boolean get_disableDragCard()`

- `Void set_disableDragCard(Boolean)`

- `Boolean get_disableDragCardForced()`

- `Void set_disableDragCardForced(Boolean)`

- `Boolean get_disableToggleCard()`

- `Void set_disableToggleCard(Boolean)`

- `Boolean get_isCostLocked()`

- `Boolean get_isSelectCardMode()`

- `Void set_isSelectCardMode(Boolean)`

- `Boolean get_isAdditionalFrame()`

- `Int32 GetNumCharacterLimit(PlayerSide)`

- `Int32 _SetNumCharacterLimit(Int32, PlayerSide)`

- `Boolean get_haveGameLoaded()`

- `Int32 GetRemainingAvailableCharacterCnt(PlayerSide)`

- `State get_state()`

- `Void set_state(State)`

- `Single get_realPlayTime()`

- `FP get_timeDeltaNoEnemy()`

- `String get_levelId()`

- `Void set_levelId(String)`

- `Boolean get_isActive()`

- `Void set_isActive(Boolean)`

- `Boolean get_isPaused()`

- `SpeedLevel get_speedLevel()`

- `Void set_speedLevel(SpeedLevel)`

- `Boolean get_inSlowMotion()`

- `Int32 get_maxLifePoint()`

- `Boolean get_alwaysWinWhenFinish()`

- `Int32 GetLifePoint(PlayerSide)`

- `Void SetLifePoint(Int32, PlayerSide, Boolean)`

- `Int32 GetTempLifePoint(PlayerSide)`

- `Void SetTempLifePoint(Int32, PlayerSide)`

- `Int32 LifePointToShow(PlayerSide)`

- `Int32 GetLifePointLossByEnemy(PlayerSide)`

- `Int32 GetLifePointLossByOthers(PlayerSide)`

- `Void MarkAlwaysWinWhenFinish(Boolean)`

- `GameResult get_gameResult()`

- `PlayerBattleRank get_battleRank()`

- `Int32 GetCost(PlayerSide)`

- `Int32 SetCost(Int32, PlayerSide)`

- `Int32 SetMaxCost(Int32, PlayerSide)`

- `Void LockCostIncreasement(Boolean, CostLockReason)`

- `PrecisePeriodicTimer GetCostTimer(PlayerSide)`

- `FP GetCostTimerProgress(Boolean)`

- `FP GetCostTimerProgress(PlayerSide)`

- `Single get_costTimerPeriodTime()`

- `Int32 get_remainingEnemiesCnt()`

- `Single get_completeProgress()`

- `Single get_timeScale()`

- `Void set_timeScale(Single)`

- `Void SetPaused(Boolean, BattlePauseKey)`

- `Void SetTimeScale_DialogControllerOnly(Single)`

- `Void LoadGame(List`1, LevelData, MapData, Difficulty)`

- `Void LoadAutoReplayGame(List`1, LevelData, MapData, Journal, Difficulty)`

- `Void StartGame()`

- `Void ResetAll()`

- `Void FinishGame(GameResult, Boolean, Action)`

- `Void _DoFinishGame(GameResult, Boolean)`

- `Void GiveUpGame()`

- `Void LoadCamera(Boolean)`

- `Void _PreLoadGameInternal(LevelData, MapData)`

- `Boolean ModifyCost(Int32, Entity, PlayerSide, Boolean, Boolean)`

- `Boolean ModifyCostIncreaseTime(Single, PlayerSide)`

- `Boolean AddCostTimerModifier(Single, Entity, Int32, Boolean, PlayerSide)`

- `Boolean RemoveCostTimerModifier(Entity, PlayerSide)`

- `Void _RefreshCostTimerModifier(PlayerSide)`

- `Boolean SetCostIncreaseTime(Single, PlayerSide)`

- `Boolean ModifyMaxCost(Int32, Entity, PlayerSide, Boolean, Boolean)`

- `Boolean ModifyLegionGold(Int32)`

- `Boolean ModifyCharacterLimit(Int32, Entity, PlayerSide)`

- `Boolean ModifyLifePoint(Int32, Entity, PlayerSide, Boolean)`

- `Boolean AddTempLifePoint(Int32, Entity, PlayerSide)`

- `Void EnsureMinCost(Int32)`

- `Void PlayAudioSignal(String, Unit, Boolean)`

- `Void EnableBuildableHighlight(Func`2)`

- `Void EnableBuildableHighlight(BattleCharacterData, BuildCondition, Boolean)`

- `Void DisableBuildableHighlight()`

- `Void _ChangeTileHighlightType(Tile, Boolean)`

- `Void _ChangeOverlapTargetColor(Character, Boolean)`

- `Vector3 GetPredefinedLocationPosition(PredefinedLocation)`

- `Vector3 ScreenPointToWorldPositionAtMapHeight(Vector3, Single)`

- `GlobalEnvSystem GetEnvSystemByKey(String)`

- `T GetEnvSystemManager()`

- `T GetEnvSystemManagerByKey(String)`

- `Boolean ActivateInternalHiddenCard(String)`

- `Void RefreshDeck(ref)`

- `Void ResetSeed()`

- `Void ResetSeed(Int32)`

- `Void CriticalAlertAndForceExit(String, String)`

- `Void PaddingPreload(ObjectConfig)`

- `Void ClearPadding()`

- `Void TrigOrQueueFixedEntityEvent(Entity, UInt32, UInt32, Action`1)`

- `Void TrigOrQueueFixedPtrEvent(IPtrObject, UInt32, UInt32, Action`1)`

- `Void TryAddDeckGlobalBuff(Unit, ref)`

- `Void ManualFrameTick(FrameData, Boolean)`

- `Void LoadPredefinedData(PredefinedData)`

- `Void RegisterBObject(BObject)`

- `Void UnregisterBObject(BObject)`

- `Void RegisterUnit(Unit)`

- `Void OnRallyPointLikeReborn(Unit)`

- `Void OnEnemyRebornAfterFakeDeath(Unit)`

- `Void UnregisterUnit(Unit)`

- `Void RegisterModule(IBattleModule)`

- `Void UnregisterModule(IBattleModule)`

- `Void RegisterMustInvokeGameReadyCallback(Action)`

- `Boolean PlayerOp_Withdraw(Character)`

- `Boolean PlayerOp_Spawn(UInt32, Direction, Tile)`

- `Boolean PlayerOp_TrigSkill(Character)`

- `Boolean SpawnPredefinedInstanceByAlias(String)`

- `Boolean SpawnPredefinedInstanceByAlias(String, PredefinedData)`

- `Boolean WithdrawPredefinedInstByAlias(String)`

- `Character SpawnPredefinedInstanceWithTile(String, Tile, Direction)`

- `Boolean IsPredefinedAndNeedToTakeSnapshot(String)`

- `PredefinedInst GetPredefineCharacter(String)`

- `Boolean IsPredefinedAssistCharacter(String)`

- `Boolean SpawnTokenBySkillFreely(String, Character, Direction, Tile, out, PlayerSide, Boolean, Boolean, Boolean)`

- `Boolean _SpawnInternal(Signiture, Direction, Tile, Boolean, Boolean)`

- `Boolean _SpawnInternal(UInt32, Direction, Tile, Boolean, Boolean, PlayerSide)`

- `Boolean _WithdrawInternal(Signiture, GridPosition)`

- `Boolean _WithdrawInternal(Character, PlayerSide)`

- `Boolean _OpTrigSkillInternal(Signiture, GridPosition, Boolean)`

- `Boolean _OpTrigSkillInternal(Character, Boolean, PlayerSide)`

- `Character _FindCharacterBySignitureAndPos(Signiture, GridPosition)`

- `Character _FindCharacterByIdAndPos(String, GridPosition)`

- `PreviewCursor CreatePreviewCursor(Int32, Boolean, SchedulerSnapshot, Action, String)`

- `Enemy CreateEnemy(EnemyData, EnemyHandBookData, SchedulerSnapshot, Int32, Options, Boolean)`

- `Enemy CreateEnemy(EnemyData, EnemyHandBookData, SchedulerSnapshot, Route, Options)`

- `Character CreateCharacter(Card, Direction, Tile, Boolean, SpawnDetailsTracker, Boolean)`

- `Character CreateToken(Card, Direction, Tile, Boolean, SpawnDetailsTracker, Boolean)`

- `Character CreateNpc(String, Direction, GridPosition, Boolean, Int32)`

- `Character CreateRuntimeInst(Direction, GridPosition, Boolean, AdvancedCharacterInst, Boolean, Blackboard)`

- `Character CreateRuntimeInstance(AdvancedCharacterInst, Direction, Tile, Boolean, SideType, PlayerSide, Boolean, Boolean)`

- `Character CreateRuntimeInstance(BattleCharacterData, Direction, Tile, Boolean, SideType, PlayerSide, Boolean, Boolean)`

- `Projectile CreateProjectile(String, Entity, ILocatable, ILocatable, Ability, out)`

- `Projectile CreateProjectileUseSourceAsProjectileSource(String, Entity, ILocatable, ILocatable, Ability, out)`

- `Projectile CreateProjectileFromProjectile(String, Projectile, ILocatable, Type, String, EffectReplacePair[])`

- `Character CreateCharacterDummy(BattleCharacterData, AdditionalBuildCondition, Boolean)`

- `Character CreateTokenDummy(BattleCharacterData, AdditionalBuildCondition, Boolean)`

- `BasicSkill CreateSkill(SkillData)`

- `Effect CreateEffect(String, ILocatable, Entity, Single)`

- `Effect CreateEffectHoldBySource(String, ILocatable, Entity, Single)`

- `Effect CreateEffect(String, Transform, Entity, Boolean, Single)`

- `Effect CreateEffectAtWorldPos(String, Vector3, Entity, Single, PlayerSide)`

- `Effect CreateEffectAtWorldPos(String, Vector3, Vector3, Entity, Single)`

- `Effect CreateEffectAtMapPos(String, Vector3, Entity, Single)`

- `Effect CreateEffectAtMapPos(String, Vector3, Entity, Vector3, Single)`

- `Effect CreateEffectAtMapPosAndHold(String, Vector3, Entity, Single)`

- `Void FinishOperaHoldEffectIfExist()`

- `Effect CreateMapEffect(MapEffectData, ILocatable, Transform)`

- `Effect CreateEffect(String, Entity, Entity, Single)`

- `Effect CreateEffect(String, Entity, Entity, Vector3, Single)`

- `CameraEffect CreateCameraEffect(String)`

- `Void CreateEffects(IList`1, ILocatable, Entity, Single)`

- `Void CreateEffects(IList`1, Entity, Entity)`

- `Void CreateEffects(IList`1, Entity, Entity, Vector3, Single)`

- `Void CreateEffectsAtMapPos(IList`1, Vector3, Entity, Single)`

- `Void CreateMapEffects(IList`1, ILocatable, Transform)`

- `Effect CreateEffectOn(String, Transform)`

- `Void ThrowEffect(ObjectPtr`1)`

- `Void _PlayBattleFinishAudio(GameResult)`

- `UInt32 TakeSnapshotAsHashCode()`

- `Void _LogSnapshot(UInt32)`

- `Void RecycleBuffNextFrame(ObjectPtr`1)`

- `Void _UpdateDelayToRecycleBuffContainer()`

- `Void SetSlowMotion(SlowMotionReason)`

- `Void RevertSlowMotion(SlowMotionReason)`

- `Void LogPlayerOperation(PlayerOprtData)`

- `Journal AchieveBattleJournal()`

- `Void CancelAutoReplayIfOn()`

- `Boolean IsAutoBattleUnsync()`

- `Void OnPhysicObjectInit(IPhysicObject)`

- `Void OnPhysicObjectRecycle(IPhysicObject)`

- `Void OnUnitPostInit(Unit)`

- `Void OnUnitBorn(Unit)`

- `Void OnUnitFinished(Unit, FinishReason)`

- `Void OnCharacterLocate(Character)`

- `Void OnCharacterFinished(Character, FinishReason)`

- `Void RecycleCard(Character)`

- `Void OnCharacterAtkOrCbt(Character)`

- `Void OnDummyTouchedToTile(Character, Tile)`

- `Void OnDummyTouchedToTile(Character, Tile, Vector3)`

- `Boolean Hook_OnDummyDragging()`

- `Void OnEnemyFinished(Enemy, FinishReason)`

- `Void OnEnemyReachedExit(Enemy, Tile)`

- `Void OnEnemyRecycled(Enemy)`

- `Void OnBossEnter(Enemy)`

- `Void OnGiantBossInit(Enemy)`

- `Void OnPredefinedLocationReached(Object)`

- `Void _OnPauseToggled(Boolean)`

- `Void _OnSpeedLevelChanged(SpeedLevel)`

- `Void OnWaveWillStart(WaveData)`

- `Void OnWaveWillFinish(WaveData)`

- `Void OnSpecialUITrigger(Object)`

- `PlayerBattleRank _ParseBattleRank()`

- `Character _CreatePredefinedCharacter(PredefinedCharacter, Boolean, out)`

- `Void _WithdrawPredefinedCharacter(PredefinedCharacter)`

- `Void _PreprocessPredefinedCharacter(BattleCharacterData, Boolean, out)`

- `Void _LoadPredefinedData(PredefinedData)`

- `Void _InitRunes(IRuneDataHolder, IList`1, Difficulty)`

- `Void _CreateAndInitGlobalBuffs(IList`1)`

- `GlobalBuff CreateAndInitGlobalBuff(GlobalBuffData)`

- `GlobalBuff GetFirstGlobalBuffByKey(String)`

- `Void _CreateAndInitGlobalEnvSystem(IList`1)`

- `Void ResetGlobalBuff()`

- `Void _ResetGlobalBuffStatics()`

- `Void _OnGlobalEnvSystemPostInit()`

- `CardBuff CreateCardBuffWithBlackboard(Buff, Blackboard, Card, LifeType, Boolean, String)`

- `CardBuff CreateCardBuffByCardWithBlackboard(Card, Blackboard, Card, LifeType, Boolean, String)`

- `Void AddDeckBuff(Card, DeckBuff)`

- `Void _SwitchState(State, State)`

- `Void _RegisterModules()`

- `Void _UpdateGameInfo(FP)`

- `Void _UpdateCost(FP, PlayerSide)`

- `Void _UpdatePlayerOrReplayInput()`

- `Void _LoadGameInternal(List`1, LevelData, MapData, Difficulty, Int32)`

- `Void LoadGameWithRune(List`1, LevelData, MapData, Difficulty, IRuneDataHolder, out, out)`

- `Void _GenerateDeckDict(ref, LevelData)`

- `Void _MergeDeckModifiers(ref)`

- `Void _PostProcessCharacters()`

- `Void _InitCameraAndMapEffects(MapData, Map, IList`1)`

- `String _GetFinalCameraEffect(String)`

- `Boolean _DoApplyGlobalModifier(ref, Entity)`

- `Boolean _ApplyGlobalModifier(ref, Entity)`

- `Void _OnApplyingGlobalModifier(ref)`

- `Boolean _InitPostprocessSettings(PostprocessMask)`

- `Void _LoadPools()`

- `Void Update()`

- `Void FixedUpdate()`

- `Void OnTick()`

- `TSingleton GetOrCreateSingleton(Func`1)`

- `Void <StartGame>b__303_0()`

- `Void <_InitRunes>b__455_0(RuneData)`

- `Void <_InitRunes>b__455_1(RuneData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleController : SingletonMonoBehaviour`1, ILuaCallCSharp, IHotfixable, ISingletonMonoHost
{
	public const Int32 INITIAL_OBJECT_CAPACITY; // 0x0
	public const Int32 INITIAL_BUFF_PRELOAD_CNT; // 0x0
	private static GameModeMeta s_cachedModeMeta; // 0x0
	private static Boolean <isDeterministic>k__BackingField; // 0x10
	private PlayerSide <playerSide>k__BackingField; // 0x18
	private static UInt32 s_fixedFrameCnt; // 0x14
	private static FP s_fixedPlayTime; // 0x18
	private static FP s_fixedPlayTimeIgnored; // 0x20
	private static Single s_fixedPlayTimeFloat; // 0x28
	private const AlgorithmType RANDOM_ALGORITHM; // 0x0
	private static Random s_randomImp; // 0x30
	private static Random s_randomTrivial; // 0x38
	private static UInt32 s_battleUidCounter; // 0x40
	private static ListPool`1 s_entityListPool; // 0x48
	private ListDict`2 m_delayToRecycleBuffContainer; // 0x20
	private Map _map; // 0x28
	private Scheduler _scheduler; // 0x30
	private BattleFactory _factory; // 0x38
	private GridRangeDrawer _gridRangeDrawer; // 0x40
	private Transform _dragPlane; // 0x48
	private Transform[] _predefinedLocations; // 0x50
	private List`1 m_modules; // 0x58
	private EventPool`1 m_eventPool; // 0x60
	private List`1 m_globalBuffs; // 0x68
	private ListDict`2 m_globalEnvSystems; // 0x70
	private ObjectManager m_objectManger; // 0x78
	private Context m_context; // 0x80
	private ObjectPool`1 m_buffPool; // 0x88
	private readonly List`1 m_sortedActivePlayers; // 0x90
	private readonly ListDict`2 m_deckDict; // 0x98
	private Single m_originCostIncreaseTime; // 0xa0
	private readonly ListDict`2 m_costDict; // 0xa8
	private readonly ListDict`2 m_costTimerDict; // 0xb0
	private readonly ListDict`2 m_lifePointDict; // 0xb8
	private readonly ListDict`2 m_characterLimitDict; // 0xc0
	private readonly List`1 m_physicObjects; // 0xc8
	private readonly ListDict`2 m_costTimerModifiers; // 0xd0
	private Boolean m_costAddLocked; // 0xd8
	private readonly ListDict`2 m_tempLifePointDict; // 0xe0
	private BattleLogger m_logger; // 0xe8
	private ReplayController m_replayController; // 0xf0
	private BattleAttackRangeController m_attackRangeController; // 0xf8
	private PredefinedData m_predefines; // 0x100
	private RuneManager m_runeManager; // 0x108
	private SpineShaderManager m_spineShaderManager; // 0x110
	private PlayerOperationQueue m_playerOpQueue; // 0x118
	private Boolean m_additionalFrame; // 0x120
	private FixedEventHandler`1 m_fixedEventHandler; // 0x128
	private Action m_pendingGameReadyCallbacks; // 0x130
	private CoroutineSimulator m_coroutineSimulator; // 0x138
	private HashCodeBuilder m_hashCodeBuilder; // 0x140
	private StringBuilder m_snapshotBuilder; // 0x148
	private StringBuilder m_playerOperationBuilder; // 0x150
	private BattleTweenMgr m_battleTweenMgr; // 0x158
	private LevelData m_levelData; // 0x160
	private MapData m_mapData; // 0x168
	private List`1 m_playerDataList; // 0x170
	private IGameMode m_gameMode; // 0x178
	private ObscuredInt m_randomSeed; // 0x180
	private ClientAntiCheatChecker m_antiCheatChecker; // 0x198
	private OperaController m_operaController; // 0x1a0
	private ObjectPtr`1 m_operaHoldEffect; // 0x1a8
	private Action m_tick; // 0x1b8
	private DialogController m_dialogController; // 0x1c0
	private BattleSpineOutlineManager m_spineOutlineManager; // 0x1c8
	private Int32 m_slowMotionReason; // 0x1d0
	private Int32 m_costLockReason; // 0x1d4
	private Action m_onGameDoFinish; // 0x1d8
	private Boolean m_haveGameLoaded; // 0x1e0
	private BattlePluginExternalHost m_externalPluginHost; // 0x1e8
	private State m_state; // 0x1f0
	private GameResult m_result; // 0x1f4
	private SpeedLevel m_speedLevel; // 0x1f8
	private Boolean m_speedLevelSlowFlag; // 0x1fc
	private Boolean m_alwaysWinWhenFinish; // 0x1fd
	private BattleGlobalBlackboard m_globalBlackboard; // 0x200
	private ObscuredInt m_maxLeftPoint; // 0x208
	private ObscuredInt m_lifePoint; // 0x21c
	private ObscuredInt m_tempLifePoint; // 0x230
	private EnableStateWithKey`1 m_pauseState; // 0x248
	private Single m_originTimeScale; // 0x250
	private Single m_realPlayTime; // 0x254
	private FP m_timeDeltaNoEnemy; // 0x258
	private Queue`1 m_paddingPools; // 0x260
	private Func`2 m_unloadCb; // 0x268
	private Boolean m_isAutoReplayOn; // 0x270
	private UnitManager <unitManager>k__BackingField; // 0x278
	private Boolean <disableDragCard>k__BackingField; // 0x280
	private Boolean <disableDragCardForced>k__BackingField; // 0x281
	private Boolean <disableToggleCard>k__BackingField; // 0x282
	private Boolean m_isSelectCardMode; // 0x283
	private String <levelId>k__BackingField; // 0x288
	private readonly ListDict`2 m_lifePointLossByEnemy; // 0x290
	private readonly ListDict`2 m_lifePointLossByOthers; // 0x298
	private SingletonHost m_singletonHost; // 0x2a0
	private static DelegateBridge __Hotfix0_get_isDeterministic; // 0x50
	private static DelegateBridge __Hotfix0_set_isDeterministic; // 0x58
	private static DelegateBridge __Hotfix0_get_isOnline; // 0x60
	private static DelegateBridge __Hotfix0_get_isMultiActivePlayers; // 0x68
	private static DelegateBridge __Hotfix0_get_playerSide; // 0x70
	private static DelegateBridge __Hotfix0_set_playerSide; // 0x78
	private static DelegateBridge __Hotfix0_get_playerSideNext; // 0x80
	private static DelegateBridge __Hotfix0_get_sortedActivePlayers; // 0x88
	private static DelegateBridge __Hotfix0_get_playerLayer; // 0x90
	private static DelegateBridge __Hotfix0_get_isAtOwnLayer; // 0x98
	private static DelegateBridge __Hotfix0_get_currentLayer; // 0xa0
	private static DelegateBridge __Hotfix0_get_isLegionMode; // 0xa8
	private static DelegateBridge __Hotfix0_get_isSandBox; // 0xb0
	private static DelegateBridge __Hotfix0_get_isFunLivePlayMode; // 0xb8
	private static DelegateBridge __Hotfix0_get_isStrifeMode; // 0xc0
	private static DelegateBridge __Hotfix0_get_isRacingMode; // 0xc8
	private static DelegateBridge __Hotfix0_get_isDouququMode; // 0xd0
	private static DelegateBridge __Hotfix0_get_isEnemyDuel; // 0xd8
	private static DelegateBridge __Hotfix0_get_isCooperateMode; // 0xe0
	private static DelegateBridge __Hotfix0_get_isPvpOrSeperateMode; // 0xe8
	private static DelegateBridge __Hotfix0_get_isGameCityMode; // 0xf0
	private static DelegateBridge __Hotfix0_get_fixedFrameCnt; // 0xf8
	private static DelegateBridge __Hotfix0_get_fixedPlayTime; // 0x100
	private static DelegateBridge __Hotfix0_get_userFixedPlayTime; // 0x108
	private static DelegateBridge __Hotfix0_get_randomImp; // 0x110
	private static DelegateBridge __Hotfix0_get_randomTrivial; // 0x118
	private static DelegateBridge __Hotfix0_GenNextUniqueId; // 0x120
	private static DelegateBridge __Hotfix0_AllocateEntityList_DISPOSE; // 0x128
	private static DelegateBridge __Hotfix0_get_randomSeed; // 0x130
	private static DelegateBridge __Hotfix0_get_battleTweenMgr; // 0x138
	private static DelegateBridge __Hotfix0_get_attackRangeController; // 0x140
	private static DelegateBridge __Hotfix0_get_map; // 0x148
	private static DelegateBridge __Hotfix0_get_mapData; // 0x150
	private static DelegateBridge __Hotfix0_get_levelData; // 0x158
	private static DelegateBridge __Hotfix0_get_playerDataList; // 0x160
	private static DelegateBridge __Hotfix0_GetDeck; // 0x168
	private static DelegateBridge __Hotfix1_GetDeck; // 0x170
	private static DelegateBridge __Hotfix0_ForeachActiveDecks; // 0x178
	private static DelegateBridge __Hotfix0_ForeachCard; // 0x180
	private static DelegateBridge __Hotfix0_get_scheduler; // 0x188
	private static DelegateBridge __Hotfix0_get_gridRangeDrawer; // 0x190
	private static DelegateBridge __Hotfix0_set_gridRangeDrawer; // 0x198
	private static DelegateBridge __Hotfix0_get_unitManager; // 0x1a0
	private static DelegateBridge __Hotfix0_set_unitManager; // 0x1a8
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x1b0
	private static DelegateBridge __Hotfix0_get_context; // 0x1b8
	private static DelegateBridge __Hotfix0_get_factory; // 0x1c0
	private static DelegateBridge __Hotfix0_get_logger; // 0x1c8
	private static DelegateBridge __Hotfix0_get_dragPlane; // 0x1d0
	private static DelegateBridge __Hotfix0_get_runeManager; // 0x1d8
	private static DelegateBridge __Hotfix0_get_buffPool; // 0x1e0
	private static DelegateBridge __Hotfix0_get_replayController; // 0x1e8
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x1f0
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x1f8
	private static DelegateBridge __Hotfix0_get_cooperateGameMode; // 0x200
	private static DelegateBridge __Hotfix0_get_antiCheatChecker; // 0x208
	private static DelegateBridge __Hotfix0_get_operaController; // 0x210
	private static DelegateBridge __Hotfix0_get_spineShaderManager; // 0x218
	private static DelegateBridge __Hotfix0_get_spineOutlineManager; // 0x220
	private static DelegateBridge __Hotfix0_get_dialogController; // 0x228
	private static DelegateBridge __Hotfix0_get_objectManager; // 0x230
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x238
	private static DelegateBridge __Hotfix0_get_isFinished; // 0x240
	private static DelegateBridge __Hotfix0_get_isPausedOrNotPlaying; // 0x248
	private static DelegateBridge __Hotfix0_get_isAutoReplayOn; // 0x250
	private static DelegateBridge __Hotfix0_set_isAutoReplayOn; // 0x258
	private static DelegateBridge __Hotfix0_get_isDisableSlowMotion; // 0x260
	private static DelegateBridge __Hotfix0_get_globalBlackboard; // 0x268
	private static DelegateBridge __Hotfix0_get_disableDragCard; // 0x270
	private static DelegateBridge __Hotfix0_set_disableDragCard; // 0x278
	private static DelegateBridge __Hotfix0_get_disableDragCardForced; // 0x280
	private static DelegateBridge __Hotfix0_set_disableDragCardForced; // 0x288
	private static DelegateBridge __Hotfix0_get_disableToggleCard; // 0x290
	private static DelegateBridge __Hotfix0_set_disableToggleCard; // 0x298
	private static DelegateBridge __Hotfix0_get_isCostLocked; // 0x2a0
	private static DelegateBridge __Hotfix0_get_isSelectCardMode; // 0x2a8
	private static DelegateBridge __Hotfix0_set_isSelectCardMode; // 0x2b0
	private static DelegateBridge __Hotfix0_get_isAdditionalFrame; // 0x2b8
	private static DelegateBridge __Hotfix0_GetNumCharacterLimit; // 0x2c0
	private static DelegateBridge __Hotfix0__SetNumCharacterLimit; // 0x2c8
	private static DelegateBridge __Hotfix0_get_haveGameLoaded; // 0x2d0
	private static DelegateBridge __Hotfix0_GetRemainingAvailableCharacterCnt; // 0x2d8
	private static DelegateBridge __Hotfix0_get_state; // 0x2e0
	private static DelegateBridge __Hotfix0_set_state; // 0x2e8
	private static DelegateBridge __Hotfix0_get_realPlayTime; // 0x2f0
	private static DelegateBridge __Hotfix0_get_timeDeltaNoEnemy; // 0x2f8
	private static DelegateBridge __Hotfix0_get_levelId; // 0x300
	private static DelegateBridge __Hotfix0_set_levelId; // 0x308
	private static DelegateBridge __Hotfix0_get_isActive; // 0x310
	private static DelegateBridge __Hotfix0_set_isActive; // 0x318
	private static DelegateBridge __Hotfix0_get_isPaused; // 0x320
	private static DelegateBridge __Hotfix0_get_speedLevel; // 0x328
	private static DelegateBridge __Hotfix0_set_speedLevel; // 0x330
	private static DelegateBridge __Hotfix0_get_inSlowMotion; // 0x338
	private static DelegateBridge __Hotfix0_get_maxLifePoint; // 0x340
	private static DelegateBridge __Hotfix0_get_alwaysWinWhenFinish; // 0x348
	private static DelegateBridge __Hotfix0_GetLifePoint; // 0x350
	private static DelegateBridge __Hotfix0_SetLifePoint; // 0x358
	private static DelegateBridge __Hotfix0_GetTempLifePoint; // 0x360
	private static DelegateBridge __Hotfix0_SetTempLifePoint; // 0x368
	private static DelegateBridge __Hotfix0_LifePointToShow; // 0x370
	private static DelegateBridge __Hotfix0_GetLifePointLossByEnemy; // 0x378
	private static DelegateBridge __Hotfix0_GetLifePointLossByOthers; // 0x380
	private static DelegateBridge __Hotfix0_MarkAlwaysWinWhenFinish; // 0x388
	private static DelegateBridge __Hotfix0_get_gameResult; // 0x390
	private static DelegateBridge __Hotfix0_get_battleRank; // 0x398
	private static DelegateBridge __Hotfix0_GetCost; // 0x3a0
	private static DelegateBridge __Hotfix0_SetCost; // 0x3a8
	private static DelegateBridge __Hotfix0_SetMaxCost; // 0x3b0
	private static DelegateBridge __Hotfix0_LockCostIncreasement; // 0x3b8
	private static DelegateBridge __Hotfix0_GetCostTimer; // 0x3c0
	private static DelegateBridge __Hotfix0_GetCostTimerProgress; // 0x3c8
	private static DelegateBridge __Hotfix1_GetCostTimerProgress; // 0x3d0
	private static DelegateBridge __Hotfix0_get_costTimerPeriodTime; // 0x3d8
	private static DelegateBridge __Hotfix0_get_remainingEnemiesCnt; // 0x3e0
	private static DelegateBridge __Hotfix0_get_completeProgress; // 0x3e8
	private static DelegateBridge __Hotfix0_get_timeScale; // 0x3f0
	private static DelegateBridge __Hotfix0_set_timeScale; // 0x3f8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x400
	private static DelegateBridge __Hotfix0_SetPaused; // 0x408
	private static DelegateBridge __Hotfix0_SetTimeScale_DialogControllerOnly; // 0x410
	private static DelegateBridge __Hotfix0_LoadGame; // 0x418
	private static DelegateBridge __Hotfix0_LoadAutoReplayGame; // 0x420
	private static DelegateBridge __Hotfix0_StartGame; // 0x428
	private static DelegateBridge __Hotfix0_ResetAll; // 0x430
	private static DelegateBridge __Hotfix0_FinishGame; // 0x438
	private static DelegateBridge __Hotfix0__DoFinishGame; // 0x440
	private static DelegateBridge __Hotfix0_GiveUpGame; // 0x448
	private static DelegateBridge __Hotfix0_LoadCamera; // 0x450
	private static DelegateBridge __Hotfix0__PreLoadGameInternal; // 0x458
	private static DelegateBridge __Hotfix0_ModifyCost; // 0x460
	private static DelegateBridge __Hotfix0_ModifyCostIncreaseTime; // 0x468
	private static DelegateBridge __Hotfix0_AddCostTimerModifier; // 0x470
	private static DelegateBridge __Hotfix0_RemoveCostTimerModifier; // 0x478
	private static DelegateBridge __Hotfix0__RefreshCostTimerModifier; // 0x480
	private static DelegateBridge __Hotfix0_SetCostIncreaseTime; // 0x488
	private static DelegateBridge __Hotfix0_ModifyMaxCost; // 0x490
	private static DelegateBridge __Hotfix0_ModifyLegionGold; // 0x498
	private static DelegateBridge __Hotfix0_ModifyCharacterLimit; // 0x4a0
	private static DelegateBridge __Hotfix0_ModifyLifePoint; // 0x4a8
	private static DelegateBridge __Hotfix0_AddTempLifePoint; // 0x4b0
	private static DelegateBridge __Hotfix0_EnsureMinCost; // 0x4b8
	private static DelegateBridge __Hotfix0_PlayAudioSignal; // 0x4c0
	private static DelegateBridge __Hotfix0_EnableBuildableHighlight; // 0x4c8
	private static DelegateBridge __Hotfix1_EnableBuildableHighlight; // 0x4d0
	private static DelegateBridge __Hotfix0_DisableBuildableHighlight; // 0x4d8
	private static DelegateBridge __Hotfix0__ChangeTileHighlightType; // 0x4e0
	private static DelegateBridge __Hotfix0__ChangeOverlapTargetColor; // 0x4e8
	private static DelegateBridge __Hotfix0_GetPredefinedLocationPosition; // 0x4f0
	private static DelegateBridge __Hotfix0_ScreenPointToWorldPositionAtMapHeight; // 0x4f8
	private static DelegateBridge __Hotfix0_GetEnvSystemByKey; // 0x500
	private static DelegateBridge __Hotfix0_GetEnvSystemManager; // 0x508
	private static DelegateBridge __Hotfix0_GetEnvSystemManagerByKey; // 0x510
	private static DelegateBridge __Hotfix0_ActivateInternalHiddenCard; // 0x518
	private static DelegateBridge __Hotfix0_RefreshDeck; // 0x520
	private static DelegateBridge __Hotfix0_ResetSeed; // 0x528
	private static DelegateBridge __Hotfix1_ResetSeed; // 0x530
	private static DelegateBridge __Hotfix0_CriticalAlertAndForceExit; // 0x538
	private static DelegateBridge __Hotfix0_PaddingPreload; // 0x540
	private static DelegateBridge __Hotfix0_ClearPadding; // 0x548
	private static DelegateBridge __Hotfix0_TrigOrQueueFixedEntityEvent; // 0x550
	private static DelegateBridge __Hotfix0_TrigOrQueueFixedPtrEvent; // 0x558
	private static DelegateBridge __Hotfix0_TryAddDeckGlobalBuff; // 0x560
	private static DelegateBridge __Hotfix0_ManualFrameTick; // 0x568
	private static DelegateBridge __Hotfix0_LoadPredefinedData; // 0x570
	private static DelegateBridge __Hotfix0_BattleInitializerOnly_EarlyInit; // 0x578
	private static DelegateBridge __Hotfix0_RegisterBObject; // 0x580
	private static DelegateBridge __Hotfix0_UnregisterBObject; // 0x588
	private static DelegateBridge __Hotfix0_RegisterUnit; // 0x590
	private static DelegateBridge __Hotfix0_OnRallyPointLikeReborn; // 0x598
	private static DelegateBridge __Hotfix0_OnEnemyRebornAfterFakeDeath; // 0x5a0
	private static DelegateBridge __Hotfix0_UnregisterUnit; // 0x5a8
	private static DelegateBridge __Hotfix0_RegisterModule; // 0x5b0
	private static DelegateBridge __Hotfix0_UnregisterModule; // 0x5b8
	private static DelegateBridge __Hotfix0_RegisterMustInvokeGameReadyCallback; // 0x5c0
	private static DelegateBridge __Hotfix0_PlayerOp_Withdraw; // 0x5c8
	private static DelegateBridge __Hotfix0_PlayerOp_Spawn; // 0x5d0
	private static DelegateBridge __Hotfix0_PlayerOp_TrigSkill; // 0x5d8
	private static DelegateBridge __Hotfix0_SpawnPredefinedInstanceByAlias; // 0x5e0
	private static DelegateBridge __Hotfix1_SpawnPredefinedInstanceByAlias; // 0x5e8
	private static DelegateBridge __Hotfix0_WithdrawPredefinedInstByAlias; // 0x5f0
	private static DelegateBridge __Hotfix0_SpawnPredefinedInstanceWithTile; // 0x5f8
	private static DelegateBridge __Hotfix0_IsPredefinedAndNeedToTakeSnapshot; // 0x600
	private static DelegateBridge __Hotfix0_GetPredefineCharacter; // 0x608
	private static DelegateBridge __Hotfix0_IsPredefinedAssistCharacter; // 0x610
	private static DelegateBridge __Hotfix0_SpawnTokenBySkillFreely; // 0x618
	private static DelegateBridge __Hotfix0__SpawnInternal; // 0x620
	private static DelegateBridge __Hotfix1__SpawnInternal; // 0x628
	private static DelegateBridge __Hotfix0__WithdrawInternal; // 0x630
	private static DelegateBridge __Hotfix1__WithdrawInternal; // 0x638
	private static DelegateBridge __Hotfix0__OpTrigSkillInternal; // 0x640
	private static DelegateBridge __Hotfix1__OpTrigSkillInternal; // 0x648
	private static DelegateBridge __Hotfix0__FindCharacterBySignitureAndPos; // 0x650
	private static DelegateBridge __Hotfix0__FindCharacterByIdAndPos; // 0x658
	private static DelegateBridge __Hotfix0_CreatePreviewCursor; // 0x660
	private static DelegateBridge __Hotfix0_CreateEnemy; // 0x668
	private static DelegateBridge __Hotfix1_CreateEnemy; // 0x670
	private static DelegateBridge __Hotfix0_CreateCharacter; // 0x678
	private static DelegateBridge __Hotfix0_CreateToken; // 0x680
	private static DelegateBridge __Hotfix0_CreateNpc; // 0x688
	private static DelegateBridge __Hotfix0_CreateRuntimeInst; // 0x690
	private static DelegateBridge __Hotfix0_CreateRuntimeInstance; // 0x698
	private static DelegateBridge __Hotfix1_CreateRuntimeInstance; // 0x6a0
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x6a8
	private static DelegateBridge __Hotfix0_CreateProjectileUseSourceAsProjectileSource; // 0x6b0
	private static DelegateBridge __Hotfix0_CreateProjectileFromProjectile; // 0x6b8
	private static DelegateBridge __Hotfix0_CreateCharacterDummy; // 0x6c0
	private static DelegateBridge __Hotfix0_CreateTokenDummy; // 0x6c8
	private static DelegateBridge __Hotfix0_CreateSkill; // 0x6d0
	private static DelegateBridge __Hotfix0_CreateEffect; // 0x6d8
	private static DelegateBridge __Hotfix0_CreateEffectHoldBySource; // 0x6e0
	private static DelegateBridge __Hotfix1_CreateEffect; // 0x6e8
	private static DelegateBridge __Hotfix0_CreateEffectAtWorldPos; // 0x6f0
	private static DelegateBridge __Hotfix1_CreateEffectAtWorldPos; // 0x6f8
	private static DelegateBridge __Hotfix0_CreateEffectAtMapPos; // 0x700
	private static DelegateBridge __Hotfix1_CreateEffectAtMapPos; // 0x708
	private static DelegateBridge __Hotfix0_CreateEffectAtMapPosAndHold; // 0x710
	private static DelegateBridge __Hotfix0_FinishOperaHoldEffectIfExist; // 0x718
	private static DelegateBridge __Hotfix0_CreateMapEffect; // 0x720
	private static DelegateBridge __Hotfix2_CreateEffect; // 0x728
	private static DelegateBridge __Hotfix3_CreateEffect; // 0x730
	private static DelegateBridge __Hotfix0_CreateCameraEffect; // 0x738
	private static DelegateBridge __Hotfix0_CreateEffects; // 0x740
	private static DelegateBridge __Hotfix1_CreateEffects; // 0x748
	private static DelegateBridge __Hotfix2_CreateEffects; // 0x750
	private static DelegateBridge __Hotfix0_CreateEffectsAtMapPos; // 0x758
	private static DelegateBridge __Hotfix0_CreateMapEffects; // 0x760
	private static DelegateBridge __Hotfix0_CreateEffectOn; // 0x768
	private static DelegateBridge __Hotfix0_ThrowEffect; // 0x770
	private static DelegateBridge __Hotfix0_PlayAudioAtPos; // 0x778
	private static DelegateBridge __Hotfix0__PlayBattleCharFX; // 0x780
	private static DelegateBridge __Hotfix0__PlayBattleFinishAudio; // 0x788
	private static DelegateBridge __Hotfix0_StartBattleCoroutine; // 0x790
	private static DelegateBridge __Hotfix0_StopBattleCoroutine; // 0x798
	private static DelegateBridge __Hotfix0_StopAllBattleCoroutines; // 0x7a0
	private static DelegateBridge __Hotfix0_StartBattleTween; // 0x7a8
	private static DelegateBridge __Hotfix1_StartBattleTween; // 0x7b0
	private static DelegateBridge __Hotfix0_TakeSnapshotAsHashCode; // 0x7b8
	private static DelegateBridge __Hotfix0__LogSnapshot; // 0x7c0
	private static DelegateBridge __Hotfix0_RecycleBuffNextFrame; // 0x7c8
	private static DelegateBridge __Hotfix0__UpdateDelayToRecycleBuffContainer; // 0x7d0
	private static DelegateBridge __Hotfix0_SetSlowMotion; // 0x7d8
	private static DelegateBridge __Hotfix0_RevertSlowMotion; // 0x7e0
	private static DelegateBridge __Hotfix0_LogPlayerOperation; // 0x7e8
	private static DelegateBridge __Hotfix0_AchieveBattleJournal; // 0x7f0
	private static DelegateBridge __Hotfix0_CancelAutoReplayIfOn; // 0x7f8
	private static DelegateBridge __Hotfix0_IsAutoBattleUnsync; // 0x800
	private static DelegateBridge __Hotfix0_OnPhysicObjectInit; // 0x808
	private static DelegateBridge __Hotfix0_OnPhysicObjectRecycle; // 0x810
	private static DelegateBridge __Hotfix0_OnUnitPostInit; // 0x818
	private static DelegateBridge __Hotfix0_OnUnitBorn; // 0x820
	private static DelegateBridge __Hotfix0_OnUnitFinished; // 0x828
	private static DelegateBridge __Hotfix0_OnCharacterLocate; // 0x830
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x838
	private static DelegateBridge __Hotfix0_RecycleCard; // 0x840
	private static DelegateBridge __Hotfix0_OnCharacterAtkOrCbt; // 0x848
	private static DelegateBridge __Hotfix0_OnDummyTouchedToTile; // 0x850
	private static DelegateBridge __Hotfix1_OnDummyTouchedToTile; // 0x858
	private static DelegateBridge __Hotfix0_Hook_OnDummyDragging; // 0x860
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x868
	private static DelegateBridge __Hotfix0_OnEnemyReachedExit; // 0x870
	private static DelegateBridge __Hotfix0_OnEnemyRecycled; // 0x878
	private static DelegateBridge __Hotfix0_OnBossEnter; // 0x880
	private static DelegateBridge __Hotfix0_OnGiantBossInit; // 0x888
	private static DelegateBridge __Hotfix0_OnPredefinedLocationReached; // 0x890
	private static DelegateBridge __Hotfix0__OnPauseToggled; // 0x898
	private static DelegateBridge __Hotfix0__OnSpeedLevelChanged; // 0x8a0
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x8a8
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0x8b0
	private static DelegateBridge __Hotfix0_OnSpecialUITrigger; // 0x8b8
	private static DelegateBridge __Hotfix0__ParseBattleRank; // 0x8c0
	private static DelegateBridge __Hotfix0__CreatePredefinedCharacter; // 0x8c8
	private static DelegateBridge __Hotfix0__WithdrawPredefinedCharacter; // 0x8d0
	private static DelegateBridge __Hotfix0__PreprocessPredefinedCharacter; // 0x8d8
	private static DelegateBridge __Hotfix0__LoadPredefinedData; // 0x8e0
	private static DelegateBridge __Hotfix0__InitRunes; // 0x8e8
	private static DelegateBridge __Hotfix0__CreateAndInitGlobalBuffs; // 0x8f0
	private static DelegateBridge __Hotfix0_CreateAndInitGlobalBuff; // 0x8f8
	private static DelegateBridge __Hotfix0_GetFirstGlobalBuffByKey; // 0x900
	private static DelegateBridge __Hotfix0__CreateAndInitGlobalEnvSystem; // 0x908
	private static DelegateBridge __Hotfix0_ResetGlobalBuff; // 0x910
	private static DelegateBridge __Hotfix0__ResetGlobalBuffStatics; // 0x918
	private static DelegateBridge __Hotfix0__OnGlobalEnvSystemPostInit; // 0x920
	private static DelegateBridge __Hotfix0_CreateCardBuffWithBlackboard; // 0x928
	private static DelegateBridge __Hotfix0_CreateCardBuffByCardWithBlackboard; // 0x930
	private static DelegateBridge __Hotfix0_AddDeckBuff; // 0x938
	private static DelegateBridge __Hotfix0__SwitchState; // 0x940
	private static DelegateBridge __Hotfix0__RegisterModules; // 0x948
	private static DelegateBridge __Hotfix0__UpdateGameInfo; // 0x950
	private static DelegateBridge __Hotfix0__UpdateCost; // 0x958
	private static DelegateBridge __Hotfix0__UpdatePlayerOrReplayInput; // 0x960
	private static DelegateBridge __Hotfix0__LoadGameInternal; // 0x968
	private static DelegateBridge __Hotfix0_LoadGameWithRune; // 0x970
	private static DelegateBridge __Hotfix0__GenerateDeckDict; // 0x978
	private static DelegateBridge __Hotfix0__MergeDeckModifiers; // 0x980
	private static DelegateBridge __Hotfix0__PostProcessCharacters; // 0x988
	private static DelegateBridge __Hotfix0__InitCameraAndMapEffects; // 0x990
	private static DelegateBridge __Hotfix0__GetFinalCameraEffect; // 0x998
	private static DelegateBridge __Hotfix0__DoApplyGlobalModifier; // 0x9a0
	private static DelegateBridge __Hotfix0__ApplyGlobalModifier; // 0x9a8
	private static DelegateBridge __Hotfix0__OnApplyingGlobalModifier; // 0x9b0
	private static DelegateBridge __Hotfix0__InitPostprocessSettings; // 0x9b8
	private static DelegateBridge __Hotfix0__LoadPools; // 0x9c0
	private static DelegateBridge __Hotfix0_Awake; // 0x9c8
	private static DelegateBridge __Hotfix0_Update; // 0x9d0
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x9d8
	private static DelegateBridge __Hotfix0_OnTick; // 0x9e0
	private static DelegateBridge __Hotfix0_OnInit; // 0x9e8
	private static DelegateBridge __Hotfix0_LiteDisposeBattle; // 0x9f0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x9f8
	private static DelegateBridge __Hotfix0_GetOrCreateSingleton; // 0xa00

	public static Boolean isDeterministic { get; set; }
	public Boolean isOnline { get; }
	public Boolean isMultiActivePlayers { get; }
	public PlayerSide playerSide { get; set; }
	public PlayerSide playerSideNext { get; }
	public List`1 sortedActivePlayers { get; }
	public MapLayer playerLayer { get; }
	public Boolean isAtOwnLayer { get; }
	private MapLayer currentLayer { get; }
	public Boolean isLegionMode { get; }
	public Boolean isSandBox { get; }
	public Boolean isFunLivePlayMode { get; }
	public Boolean isStrifeMode { get; }
	public Boolean isRacingMode { get; }
	public Boolean isDouququMode { get; }
	public Boolean isEnemyDuel { get; }
	public Boolean isCooperateMode { get; }
	public Boolean isPvpOrSeperateMode { get; }
	public Boolean isGameCityMode { get; }
	public static UInt32 fixedFrameCnt { get; }
	public static FP fixedPlayTime { get; }
	public static FP userFixedPlayTime { get; }
	public static Random randomImp { get; }
	public static Random randomTrivial { get; }
	public Int32 randomSeed { get; }
	private BattleTweenMgr battleTweenMgr { get; }
	public BattleAttackRangeController attackRangeController { get; }
	public Map map { get; }
	public MapData mapData { get; }
	public LevelData levelData { get; }
	public List`1 playerDataList { get; }
	public Scheduler scheduler { get; }
	public GridRangeDrawer gridRangeDrawer { get; set; }
	public UnitManager unitManager { get; set; }
	public EventPool`1 eventPool { get; }
	public Context context { get; }
	public BattleFactory factory { get; }
	public BattleLogger logger { get; }
	public Transform dragPlane { get; }
	public RuneManager runeManager { get; }
	public ObjectPool`1 buffPool { get; }
	public ReplayController replayController { get; }
	public IGameMode gameMode { get; }
	public SandboxGameMode sandboxGameMode { get; }
	public CooperateGameMode cooperateGameMode { get; }
	public ClientAntiCheatChecker antiCheatChecker { get; }
	public OperaController operaController { get; }
	public SpineShaderManager spineShaderManager { get; }
	public BattleSpineOutlineManager spineOutlineManager { get; }
	public DialogController dialogController { get; }
	public ObjectManager objectManager { get; }
	public Boolean isPlaying { get; }
	public Boolean isFinished { get; }
	public Boolean isPausedOrNotPlaying { get; }
	public Boolean isAutoReplayOn { get; set; }
	public Boolean isDisableSlowMotion { get; }
	public BattleGlobalBlackboard globalBlackboard { get; }
	public Boolean disableDragCard { get; set; }
	public Boolean disableDragCardForced { get; set; }
	public Boolean disableToggleCard { get; set; }
	public Boolean isCostLocked { get; }
	public Boolean isSelectCardMode { get; set; }
	public Boolean isAdditionalFrame { get; }
	public Boolean haveGameLoaded { get; }
	public State state { get; set; }
	public Single realPlayTime { get; }
	public FP timeDeltaNoEnemy { get; }
	public String levelId { get; set; }
	public Boolean isActive { get; set; }
	public Boolean isPaused { get; }
	public SpeedLevel speedLevel { get; set; }
	public Boolean inSlowMotion { get; }
	public Int32 maxLifePoint { get; }
	public Boolean alwaysWinWhenFinish { get; }
	public GameResult gameResult { get; }
	public PlayerBattleRank battleRank { get; }
	public Single costTimerPeriodTime { get; }
	public Int32 remainingEnemiesCnt { get; }
	public Single completeProgress { get; }
	private Single timeScale { get; set; }

	// RVA: 0x3f37234 VA: 0x759654f234
	public static Boolean get_isDeterministic() { }
	// RVA: 0x3f372bc VA: 0x759654f2bc
	private static Void set_isDeterministic(Boolean value) { }
	// RVA: 0x3f37350 VA: 0x759654f350
	public Boolean get_isOnline() { }
	// RVA: 0x3f374d4 VA: 0x759654f4d4
	public Boolean get_isMultiActivePlayers() { }
	// RVA: 0x3f37570 VA: 0x759654f570
	public PlayerSide get_playerSide() { }
	// RVA: 0x3f375e8 VA: 0x759654f5e8
	private Void set_playerSide(PlayerSide value) { }
	// RVA: 0x3f37674 VA: 0x759654f674
	public PlayerSide get_playerSideNext() { }
	// RVA: 0x3f377a4 VA: 0x759654f7a4
	public List`1 get_sortedActivePlayers() { }
	// RVA: 0x3f3781c VA: 0x759654f81c
	public MapLayer get_playerLayer() { }
	// RVA: 0x3f378cc VA: 0x759654f8cc
	public Boolean get_isAtOwnLayer() { }
	// RVA: 0x3f37980 VA: 0x759654f980
	private MapLayer get_currentLayer() { }
	// RVA: 0x3f37a58 VA: 0x759654fa58
	public Boolean get_isLegionMode() { }
	// RVA: 0x3f37b5c VA: 0x759654fb5c
	public Boolean get_isSandBox() { }
	// RVA: 0x3f37c60 VA: 0x759654fc60
	public Boolean get_isFunLivePlayMode() { }
	// RVA: 0x3f37d64 VA: 0x759654fd64
	public Boolean get_isStrifeMode() { }
	// RVA: 0x3f37e68 VA: 0x759654fe68
	public Boolean get_isRacingMode() { }
	// RVA: 0x3f37f6c VA: 0x759654ff6c
	public Boolean get_isDouququMode() { }
	// RVA: 0x3f38070 VA: 0x7596550070
	public Boolean get_isEnemyDuel() { }
	// RVA: 0x3f38174 VA: 0x7596550174
	public Boolean get_isCooperateMode() { }
	// RVA: 0x3f38278 VA: 0x7596550278
	public Boolean get_isPvpOrSeperateMode() { }
	// RVA: 0x3f382ec VA: 0x75965502ec
	public Boolean get_isGameCityMode() { }
	// RVA: 0x3f383f0 VA: 0x75965503f0
	public static UInt32 get_fixedFrameCnt() { }
	// RVA: 0x3f38478 VA: 0x7596550478
	public static FP get_fixedPlayTime() { }
	// RVA: 0x3f385b0 VA: 0x75965505b0
	public static FP get_userFixedPlayTime() { }
	// RVA: 0x3f38674 VA: 0x7596550674
	public static Random get_randomImp() { }
	// RVA: 0x3f386fc VA: 0x75965506fc
	public static Random get_randomTrivial() { }
	// RVA: 0x3f38784 VA: 0x7596550784
	public static UInt32 GenNextUniqueId() { }
	// RVA: 0x3f38814 VA: 0x7596550814
	public static ReusableList`1 AllocateEntityList_DISPOSE() { }
	// RVA: 0x3f3890c VA: 0x759655090c
	public Int32 get_randomSeed() { }
	// RVA: 0x3f389b0 VA: 0x75965509b0
	private BattleTweenMgr get_battleTweenMgr() { }
	// RVA: 0x3f38a78 VA: 0x7596550a78
	public BattleAttackRangeController get_attackRangeController() { }
	// RVA: 0x3f38b38 VA: 0x7596550b38
	public Map get_map() { }
	// RVA: 0x3f38bb0 VA: 0x7596550bb0
	public MapData get_mapData() { }
	// RVA: 0x3f38c28 VA: 0x7596550c28
	public LevelData get_levelData() { }
	// RVA: 0x3f38ca0 VA: 0x7596550ca0
	public List`1 get_playerDataList() { }
	// RVA: 0x3f38d18 VA: 0x7596550d18
	public Deck GetDeck(PlayerSide side) { }
	// RVA: 0x3f38dec VA: 0x7596550dec
	public Deck GetDeck(Entity entity) { }
	// RVA: 0x3f38ec8 VA: 0x7596550ec8
	public Void ForeachActiveDecks(Action`1 action) { }
	// RVA: 0x3f3906c VA: 0x759655106c
	public Void ForeachCard(PlayerSide selectSide, Action`1 action) { }
	// RVA: 0x3f391f4 VA: 0x75965511f4
	public Scheduler get_scheduler() { }
	// RVA: 0x3f3926c VA: 0x759655126c
	public GridRangeDrawer get_gridRangeDrawer() { }
	// RVA: 0x3f392e4 VA: 0x75965512e4
	public Void set_gridRangeDrawer(GridRangeDrawer value) { }
	// RVA: 0x3f39378 VA: 0x7596551378
	public UnitManager get_unitManager() { }
	// RVA: 0x3f393f0 VA: 0x75965513f0
	private Void set_unitManager(UnitManager value) { }
	// RVA: 0x3f39484 VA: 0x7596551484
	public EventPool`1 get_eventPool() { }
	// RVA: 0x3f394f8 VA: 0x75965514f8
	public Context get_context() { }
	// RVA: 0x3f39570 VA: 0x7596551570
	public BattleFactory get_factory() { }
	// RVA: 0x3f395e8 VA: 0x75965515e8
	public BattleLogger get_logger() { }
	// RVA: 0x3f39660 VA: 0x7596551660
	public Transform get_dragPlane() { }
	// RVA: 0x3f396d8 VA: 0x75965516d8
	public RuneManager get_runeManager() { }
	// RVA: 0x3f39750 VA: 0x7596551750
	public ObjectPool`1 get_buffPool() { }
	// RVA: 0x3f397c8 VA: 0x75965517c8
	public ReplayController get_replayController() { }
	// RVA: 0x3f3745c VA: 0x759654f45c
	public IGameMode get_gameMode() { }
	// RVA: 0x3f39840 VA: 0x7596551840
	public SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x3f39904 VA: 0x7596551904
	public CooperateGameMode get_cooperateGameMode() { }
	// RVA: 0x3f399c8 VA: 0x75965519c8
	public ClientAntiCheatChecker get_antiCheatChecker() { }
	// RVA: 0x3f39a40 VA: 0x7596551a40
	public OperaController get_operaController() { }
	// RVA: 0x3f39ab8 VA: 0x7596551ab8
	public SpineShaderManager get_spineShaderManager() { }
	// RVA: 0x3f39b30 VA: 0x7596551b30
	public BattleSpineOutlineManager get_spineOutlineManager() { }
	// RVA: 0x3f39ba8 VA: 0x7596551ba8
	public DialogController get_dialogController() { }
	// RVA: 0x3f39c20 VA: 0x7596551c20
	public ObjectManager get_objectManager() { }
	// RVA: 0x3f39c98 VA: 0x7596551c98
	public Boolean get_isPlaying() { }
	// RVA: 0x3f39d94 VA: 0x7596551d94
	public Boolean get_isFinished() { }
	// RVA: 0x3f39e18 VA: 0x7596551e18
	public Boolean get_isPausedOrNotPlaying() { }
	// RVA: 0x3f39f44 VA: 0x7596551f44
	public Boolean get_isAutoReplayOn() { }
	// RVA: 0x3f39fbc VA: 0x7596551fbc
	private Void set_isAutoReplayOn(Boolean value) { }
	// RVA: 0x3f3a04c VA: 0x759655204c
	public Boolean get_isDisableSlowMotion() { }
	// RVA: 0x3f3a17c VA: 0x759655217c
	public BattleGlobalBlackboard get_globalBlackboard() { }
	// RVA: 0x3f3a1f4 VA: 0x75965521f4
	public Boolean get_disableDragCard() { }
	// RVA: 0x3f3a26c VA: 0x759655226c
	public Void set_disableDragCard(Boolean value) { }
	// RVA: 0x3f3a2fc VA: 0x75965522fc
	public Boolean get_disableDragCardForced() { }
	// RVA: 0x3f3a374 VA: 0x7596552374
	public Void set_disableDragCardForced(Boolean value) { }
	// RVA: 0x3f3a404 VA: 0x7596552404
	public Boolean get_disableToggleCard() { }
	// RVA: 0x3f3a47c VA: 0x759655247c
	public Void set_disableToggleCard(Boolean value) { }
	// RVA: 0x3f3a50c VA: 0x759655250c
	public Boolean get_isCostLocked() { }
	// RVA: 0x3f3a58c VA: 0x759655258c
	public Boolean get_isSelectCardMode() { }
	// RVA: 0x3f3a604 VA: 0x7596552604
	public Void set_isSelectCardMode(Boolean value) { }
	// RVA: 0x3f3a6e8 VA: 0x75965526e8
	public Boolean get_isAdditionalFrame() { }
	// RVA: 0x3f3a760 VA: 0x7596552760
	public Int32 GetNumCharacterLimit(PlayerSide side) { }
	// RVA: 0x3f3a8a0 VA: 0x75965528a0
	private Int32 _SetNumCharacterLimit(Int32 value, PlayerSide side) { }
	// RVA: 0x3f3aa54 VA: 0x7596552a54
	public Boolean get_haveGameLoaded() { }
	// RVA: 0x3f3aacc VA: 0x7596552acc
	public Int32 GetRemainingAvailableCharacterCnt(PlayerSide playerSide) { }
	// RVA: 0x3f39d1c VA: 0x7596551d1c
	public State get_state() { }
	// RVA: 0x3f3ac04 VA: 0x7596552c04
	private Void set_state(State value) { }
	// RVA: 0x3f3adb4 VA: 0x7596552db4
	public Single get_realPlayTime() { }
	// RVA: 0x3f3ae2c VA: 0x7596552e2c
	public FP get_timeDeltaNoEnemy() { }
	// RVA: 0x3f3aea4 VA: 0x7596552ea4
	public String get_levelId() { }
	// RVA: 0x3f3af1c VA: 0x7596552f1c
	private Void set_levelId(String value) { }
	// RVA: 0x3f3afb0 VA: 0x7596552fb0
	public Boolean get_isActive() { }
	// RVA: 0x3f3b03c VA: 0x759655303c
	public Void set_isActive(Boolean value) { }
	// RVA: 0x3f39eac VA: 0x7596551eac
	public Boolean get_isPaused() { }
	// RVA: 0x3f3b0e0 VA: 0x75965530e0
	public SpeedLevel get_speedLevel() { }
	// RVA: 0x3f3b168 VA: 0x7596553168
	public Void set_speedLevel(SpeedLevel value) { }
	// RVA: 0x3f3b51c VA: 0x759655351c
	public Boolean get_inSlowMotion() { }
	// RVA: 0x3f3b5a0 VA: 0x75965535a0
	public Int32 get_maxLifePoint() { }
	// RVA: 0x3f3b674 VA: 0x7596553674
	public Boolean get_alwaysWinWhenFinish() { }
	// RVA: 0x3f3b764 VA: 0x7596553764
	public Int32 GetLifePoint(PlayerSide side) { }
	// RVA: 0x3f3b8a4 VA: 0x75965538a4
	public Void SetLifePoint(Int32 value, PlayerSide side, Boolean force) { }
	// RVA: 0x3f3bb2c VA: 0x7596553b2c
	public Int32 GetTempLifePoint(PlayerSide side) { }
	// RVA: 0x3f3bc6c VA: 0x7596553c6c
	public Void SetTempLifePoint(Int32 value, PlayerSide side) { }
	// RVA: 0x3f3bdac VA: 0x7596553dac
	public Int32 LifePointToShow(PlayerSide side) { }
	// RVA: 0x3f3beac VA: 0x7596553eac
	public Int32 GetLifePointLossByEnemy(PlayerSide side) { }
	// RVA: 0x3f3bfd4 VA: 0x7596553fd4
	public Int32 GetLifePointLossByOthers(PlayerSide side) { }
	// RVA: 0x3f3c0fc VA: 0x75965540fc
	public Void MarkAlwaysWinWhenFinish(Boolean enable) { }
	// RVA: 0x3f3c18c VA: 0x759655418c
	public GameResult get_gameResult() { }
	// RVA: 0x3f3c204 VA: 0x7596554204
	public PlayerBattleRank get_battleRank() { }
	// RVA: 0x3f3c368 VA: 0x7596554368
	public Int32 GetCost(PlayerSide side) { }
	// RVA: 0x3f3c4a8 VA: 0x75965544a8
	public Int32 SetCost(Int32 value, PlayerSide side) { }
	// RVA: 0x3f3c798 VA: 0x7596554798
	public Int32 SetMaxCost(Int32 value, PlayerSide side) { }
	// RVA: 0x3f3c980 VA: 0x7596554980
	public Void LockCostIncreasement(Boolean isLock, CostLockReason reason) { }
	// RVA: 0x3f3ca28 VA: 0x7596554a28
	public PrecisePeriodicTimer GetCostTimer(PlayerSide side) { }
	// RVA: 0x3f3cafc VA: 0x7596554afc
	public FP GetCostTimerProgress(Boolean next) { }
	// RVA: 0x3f3cba0 VA: 0x7596554ba0
	public FP GetCostTimerProgress(PlayerSide side) { }
	// RVA: 0x3f3cd2c VA: 0x7596554d2c
	public Single get_costTimerPeriodTime() { }
	// RVA: 0x3f3ce1c VA: 0x7596554e1c
	public Int32 get_remainingEnemiesCnt() { }
	// RVA: 0x3f3cea4 VA: 0x7596554ea4
	public Single get_completeProgress() { }
	// RVA: 0x3f3cfac VA: 0x7596554fac
	private Single get_timeScale() { }
	// RVA: 0x3f3b384 VA: 0x7596553384
	private Void set_timeScale(Single value) { }
	// RVA: 0x3f3d040 VA: 0x7596555040
	public Void .ctor() { }
	// RVA: 0x3f3db9c VA: 0x7596555b9c
	public Void SetPaused(Boolean value, BattlePauseKey pauseKey) { }
	// RVA: 0x3f3ddb0 VA: 0x7596555db0
	public Void SetTimeScale_DialogControllerOnly(Single value) { }
	// RVA: 0x3f3de5c VA: 0x7596555e5c
	public Void LoadGame(List`1 playerDataList, LevelData levelData, MapData mapData, Difficulty difficulty) { }
	// RVA: 0x3f3f0a8 VA: 0x75965570a8
	public Void LoadAutoReplayGame(List`1 playerDataList, LevelData levelData, MapData mapData, Journal journal, Difficulty difficulty) { }
	// RVA: 0x3f3f258 VA: 0x7596557258
	public Void StartGame() { }
	// RVA: 0x3f3e060 VA: 0x7596556060
	public Void ResetAll() { }
	// RVA: 0x3f3f390 VA: 0x7596557390
	public Void FinishGame(GameResult result, Boolean silent, Action gameDoFinishCallback) { }
	// RVA: 0x3f3f54c VA: 0x759655754c
	private Void _DoFinishGame(GameResult result, Boolean silent) { }
	// RVA: 0x3f3fe38 VA: 0x7596557e38
	public Void GiveUpGame() { }
	// RVA: 0x3f3ff28 VA: 0x7596557f28
	public Void LoadCamera(Boolean needPostprocess) { }
	// RVA: 0x3f3df40 VA: 0x7596555f40
	private Void _PreLoadGameInternal(LevelData data, MapData mapData) { }
	// RVA: 0x3f40310 VA: 0x7596558310
	public Boolean ModifyCost(Int32 value, Entity source, PlayerSide side, Boolean forceToDisplayNumber, Boolean forceToDisplayNegativeNumber) { }
	// RVA: 0x3f405c8 VA: 0x75965585c8
	public Boolean ModifyCostIncreaseTime(Single mulValue, PlayerSide side) { }
	// RVA: 0x3f407d0 VA: 0x75965587d0
	public Boolean AddCostTimerModifier(Single mulValue, Entity source, Int32 priority, Boolean costAddLocked, PlayerSide side) { }
	// RVA: 0x3f40ba4 VA: 0x7596558ba4
	public Boolean RemoveCostTimerModifier(Entity source, PlayerSide side) { }
	// RVA: 0x3f40a14 VA: 0x7596558a14
	private Void _RefreshCostTimerModifier(PlayerSide side) { }
	// RVA: 0x3f40dc8 VA: 0x7596558dc8
	public Boolean SetCostIncreaseTime(Single value, PlayerSide side) { }
	// RVA: 0x3f40fa4 VA: 0x7596558fa4
	public Boolean ModifyMaxCost(Int32 value, Entity source, PlayerSide side, Boolean ensureCurCostNotExceedMax, Boolean playAudio) { }
	// RVA: 0x3f41214 VA: 0x7596559214
	public Boolean ModifyLegionGold(Int32 value) { }
	// RVA: 0x3f41388 VA: 0x7596559388
	public Boolean ModifyCharacterLimit(Int32 value, Entity source, PlayerSide side) { }
	// RVA: 0x3f41500 VA: 0x7596559500
	public Boolean ModifyLifePoint(Int32 value, Entity source, PlayerSide side, Boolean isReachExit) { }
	// RVA: 0x3f41730 VA: 0x7596559730
	public Boolean AddTempLifePoint(Int32 value, Entity source, PlayerSide side) { }
	// RVA: 0x3f41870 VA: 0x7596559870
	public Void EnsureMinCost(Int32 cost) { }
	// RVA: 0x3f41928 VA: 0x7596559928
	public Void PlayAudioSignal(String ev, Unit unit, Boolean ignorePredefined) { }
	// RVA: 0x3f41ac8 VA: 0x7596559ac8
	public Void EnableBuildableHighlight(Func`2 checker) { }
	// RVA: 0x3f41d34 VA: 0x7596559d34
	public Void EnableBuildableHighlight(BattleCharacterData sourceData, BuildCondition condition, Boolean overflowOccupiedCnt) { }
	// RVA: 0x3f41ee4 VA: 0x7596559ee4
	public Void DisableBuildableHighlight() { }
	// RVA: 0x3f41c00 VA: 0x7596559c00
	private Void _ChangeTileHighlightType(Tile tile, Boolean isBuildable) { }
	// RVA: 0x3f42024 VA: 0x759655a024
	private Void _ChangeOverlapTargetColor(Character target, Boolean enable) { }
	// RVA: 0x3f421e4 VA: 0x759655a1e4
	public Vector3 GetPredefinedLocationPosition(PredefinedLocation predefinedLocation) { }
	// RVA: 0x3f4232c VA: 0x759655a32c
	public Vector3 ScreenPointToWorldPositionAtMapHeight(Vector3 screenPoint, Single heightOffset) { }
	// RVA: 0x3f42588 VA: 0x759655a588
	public GlobalEnvSystem GetEnvSystemByKey(String key) { }
	// RVA: 0x VA: 0x0
	public T GetEnvSystemManager() { }
	// RVA: 0x VA: 0x0
	public T GetEnvSystemManagerByKey(String key) { }
	// RVA: 0x3f42678 VA: 0x759655a678
	public Boolean ActivateInternalHiddenCard(String alias) { }
	// RVA: 0x3f427b0 VA: 0x759655a7b0
	public Void RefreshDeck(ref List`1 data) { }
	// RVA: 0x3f42f60 VA: 0x759655af60
	public Void ResetSeed() { }
	// RVA: 0x3f431a0 VA: 0x759655b1a0
	public Void ResetSeed(Int32 newSeed) { }
	// RVA: 0x3f43344 VA: 0x759655b344
	public Void CriticalAlertAndForceExit(String content, String sceneName) { }
	// RVA: 0x3f434d4 VA: 0x759655b4d4
	public Void PaddingPreload(ObjectConfig config) { }
	// RVA: 0x3f435b8 VA: 0x759655b5b8
	public Void ClearPadding() { }
	// RVA: 0x3f43650 VA: 0x759655b650
	public Void TrigOrQueueFixedEntityEvent(Entity target, UInt32 secondaryCompareUid, UInt32 thirdCompareWeight, Action`1 callback) { }
	// RVA: 0x3f43810 VA: 0x759655b810
	public Void TrigOrQueueFixedPtrEvent(IPtrObject target, UInt32 secondaryCompareUid, UInt32 thirdCompareWeight, Action`1 callback) { }
	// RVA: 0x3f43930 VA: 0x759655b930
	public Void TryAddDeckGlobalBuff(Unit unit, ref List`1 deckBuff) { }
	// RVA: 0x3f43a28 VA: 0x759655ba28
	public Void ManualFrameTick(FrameData frameData, Boolean additionalFrame) { }
	// RVA: 0x3f442c0 VA: 0x759655c2c0
	public Void LoadPredefinedData(PredefinedData predefinedData) { }
	// RVA: 0x3f445fc VA: 0x759655c5fc
	public static Void BattleInitializerOnly_EarlyInit(GameModeMeta meta) { }
	// RVA: 0x3f446c4 VA: 0x759655c6c4
	public Void RegisterBObject(BObject obj) { }
	// RVA: 0x3f4477c VA: 0x759655c77c
	public Void UnregisterBObject(BObject obj) { }
	// RVA: 0x3f44834 VA: 0x759655c834
	public Void RegisterUnit(Unit unit) { }
	// RVA: 0x3f449d0 VA: 0x759655c9d0
	public Void OnRallyPointLikeReborn(Unit unit) { }
	// RVA: 0x3f44af4 VA: 0x759655caf4
	public Void OnEnemyRebornAfterFakeDeath(Unit unit) { }
	// RVA: 0x3f44c18 VA: 0x759655cc18
	public Void UnregisterUnit(Unit unit) { }
	// RVA: 0x3f44cd4 VA: 0x759655ccd4
	public Void RegisterModule(IBattleModule module) { }
	// RVA: 0x3f44df4 VA: 0x759655cdf4
	public Void UnregisterModule(IBattleModule module) { }
	// RVA: 0x3f44ea4 VA: 0x759655cea4
	public Void RegisterMustInvokeGameReadyCallback(Action callback) { }
	// RVA: 0x3f44fc0 VA: 0x759655cfc0
	public Boolean PlayerOp_Withdraw(Character character) { }
	// RVA: 0x3f4515c VA: 0x759655d15c
	public Boolean PlayerOp_Spawn(UInt32 uniqueId, Direction direction, Tile tile) { }
	// RVA: 0x3f452d4 VA: 0x759655d2d4
	public Boolean PlayerOp_TrigSkill(Character character) { }
	// RVA: 0x3f45518 VA: 0x759655d518
	public Boolean SpawnPredefinedInstanceByAlias(String alias) { }
	// RVA: 0x3f45ac0 VA: 0x759655dac0
	public Boolean SpawnPredefinedInstanceByAlias(String alias, PredefinedData predefines) { }
	// RVA: 0x3f45ccc VA: 0x759655dccc
	public Boolean WithdrawPredefinedInstByAlias(String alias) { }
	// RVA: 0x3f45f74 VA: 0x759655df74
	public Character SpawnPredefinedInstanceWithTile(String alias, Tile tile, Direction direction) { }
	// RVA: 0x3f461ac VA: 0x759655e1ac
	public Boolean IsPredefinedAndNeedToTakeSnapshot(String characterId) { }
	// RVA: 0x3f462d8 VA: 0x759655e2d8
	public PredefinedInst GetPredefineCharacter(String charId) { }
	// RVA: 0x3f463c8 VA: 0x759655e3c8
	public Boolean IsPredefinedAssistCharacter(String charId) { }
	// RVA: 0x3f46584 VA: 0x759655e584
	public Boolean SpawnTokenBySkillFreely(String key, Character host, Direction direction, Tile tile, out Character token, PlayerSide side, Boolean refreshCooldown, Boolean ignoreAdvancedBuildableMask, Boolean forceSpawn) { }
	// RVA: 0x3f466d0 VA: 0x759655e6d0
	private Boolean _SpawnInternal(Signiture signiture, Direction direction, Tile tile, Boolean strict, Boolean spawnManually) { }
	// RVA: 0x3f4680c VA: 0x759655e80c
	private Boolean _SpawnInternal(UInt32 uniqueId, Direction direction, Tile tile, Boolean strict, Boolean spawnManually, PlayerSide opSide) { }
	// RVA: 0x3f46948 VA: 0x759655e948
	private Boolean _WithdrawInternal(Signiture signiture, GridPosition gridPos) { }
	// RVA: 0x3f46bac VA: 0x759655ebac
	private Boolean _WithdrawInternal(Character character, PlayerSide opSide) { }
	// RVA: 0x3f46cdc VA: 0x759655ecdc
	private Boolean _OpTrigSkillInternal(Signiture signiture, GridPosition gridPos, Boolean requireNotHidden) { }
	// RVA: 0x3f46e50 VA: 0x759655ee50
	private Boolean _OpTrigSkillInternal(Character character, Boolean requireNotHidden, PlayerSide side) { }
	// RVA: 0x3f46a98 VA: 0x759655ea98
	private Character _FindCharacterBySignitureAndPos(Signiture signiture, GridPosition gridPos) { }
	// RVA: 0x3f46fb4 VA: 0x759655efb4
	public Character _FindCharacterByIdAndPos(String id, GridPosition gridPos) { }
	// RVA: 0x3f470c8 VA: 0x759655f0c8
	public PreviewCursor CreatePreviewCursor(Int32 routeIndex, Boolean isExtraRoute, SchedulerSnapshot snapshot, Action finishCb, String overrideEffect) { }
	// RVA: 0x3f473c4 VA: 0x759655f3c4
	public Enemy CreateEnemy(EnemyData enemyData, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Int32 routeIndex, Options options, Boolean isExtraRoute) { }
	// RVA: 0x3f475d4 VA: 0x759655f5d4
	public Enemy CreateEnemy(EnemyData enemyData, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route, Options options) { }
	// RVA: 0x3f477d8 VA: 0x759655f7d8
	public Character CreateCharacter(Card characterCard, Direction direction, Tile tile, Boolean spawnManually, SpawnDetailsTracker spawnDetailsTracker, Boolean force) { }
	// RVA: 0x3f47c0c VA: 0x759655fc0c
	public Character CreateToken(Card tokenCard, Direction direction, Tile tile, Boolean spawnManually, SpawnDetailsTracker spawnDetailsTracker, Boolean force) { }
	// RVA: 0x3f47db8 VA: 0x759655fdb8
	public Character CreateNpc(String npcId, Direction direction, GridPosition gridPosition, Boolean isToken, Int32 skillIndex) { }
	// RVA: 0x3f480d4 VA: 0x75965600d4
	public Character CreateRuntimeInst(Direction direction, GridPosition gridPosition, Boolean isToken, AdvancedCharacterInst inst, Boolean isDialogTarget, Blackboard skillBlackboard) { }
	// RVA: 0x3f48384 VA: 0x7596560384
	public Character CreateRuntimeInstance(AdvancedCharacterInst inst, Direction direction, Tile tile, Boolean isToken, SideType sideType, PlayerSide pSide, Boolean checkBuildValid, Boolean force) { }
	// RVA: 0x3f484c4 VA: 0x75965604c4
	public Character CreateRuntimeInstance(BattleCharacterData data, Direction direction, Tile tile, Boolean isToken, SideType sideType, PlayerSide pSide, Boolean checkBuildValid, Boolean force) { }
	// RVA: 0x3f48738 VA: 0x7596560738
	public Projectile CreateProjectile(String key, Entity source, ILocatable start, ILocatable target, Ability ability, out Projectile graphicProjectile) { }
	// RVA: 0x3f48aa4 VA: 0x7596560aa4
	public Projectile CreateProjectileUseSourceAsProjectileSource(String key, Entity source, ILocatable start, ILocatable target, Ability ability, out Projectile graphicProjectile) { }
	// RVA: 0x3f48e10 VA: 0x7596560e10
	public Projectile CreateProjectileFromProjectile(String key, Projectile sourceProjectile, ILocatable target, Type type, String originalKey, EffectReplacePair[] effectReplacePairs) { }
	// RVA: 0x3f48f54 VA: 0x7596560f54
	public Character CreateCharacterDummy(BattleCharacterData characterData, AdditionalBuildCondition additionalBuildCondition, Boolean useOutline) { }
	// RVA: 0x3f49074 VA: 0x7596561074
	public Character CreateTokenDummy(BattleCharacterData tokenData, AdditionalBuildCondition additionalBuildCondition, Boolean useOutline) { }
	// RVA: 0x3f49194 VA: 0x7596561194
	public BasicSkill CreateSkill(SkillData skillData) { }
	// RVA: 0x3f49258 VA: 0x7596561258
	public Effect CreateEffect(String key, ILocatable locatable, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f493dc VA: 0x75965613dc
	public Effect CreateEffectHoldBySource(String key, ILocatable locatable, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f49560 VA: 0x7596561560
	public Effect CreateEffect(String key, Transform transform, Entity source, Boolean setAsParent, Single playbackSpeed) { }
	// RVA: 0x3f497c0 VA: 0x75965617c0
	public Effect CreateEffectAtWorldPos(String key, Vector3 position, Entity source, Single playbackSpeed, PlayerSide side) { }
	// RVA: 0x3f499e0 VA: 0x75965619e0
	public Effect CreateEffectAtWorldPos(String key, Vector3 position, Vector3 direction, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f49c14 VA: 0x7596561c14
	public Effect CreateEffectAtMapPos(String key, Vector3 mapPos, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f49e1c VA: 0x7596561e1c
	public Effect CreateEffectAtMapPos(String key, Vector3 mapPos, Entity source, Vector3 direction, Single playbackSpeed) { }
	// RVA: 0x3f4a050 VA: 0x7596562050
	public Effect CreateEffectAtMapPosAndHold(String key, Vector3 mapPos, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f4a184 VA: 0x7596562184
	public Void FinishOperaHoldEffectIfExist() { }
	// RVA: 0x3f4a25c VA: 0x759656225c
	public Effect CreateMapEffect(MapEffectData data, ILocatable locator, Transform parent) { }
	// RVA: 0x3f4a500 VA: 0x7596562500
	public Effect CreateEffect(String key, Entity target, Entity source, Single playSpeed) { }
	// RVA: 0x3f4a63c VA: 0x759656263c
	public Effect CreateEffect(String key, Entity target, Entity source, Vector3 direction, Single playbackSpeed) { }
	// RVA: 0x3f4a95c VA: 0x759656295c
	public CameraEffect CreateCameraEffect(String key) { }
	// RVA: 0x3f4aa9c VA: 0x7596562a9c
	public Void CreateEffects(IList`1 keys, ILocatable position, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f4ac60 VA: 0x7596562c60
	public Void CreateEffects(IList`1 keys, Entity entity, Entity source) { }
	// RVA: 0x3f4ae20 VA: 0x7596562e20
	public Void CreateEffects(IList`1 keys, Entity target, Entity source, Vector3 direction, Single playbackSpeed) { }
	// RVA: 0x3f4b014 VA: 0x7596563014
	public Void CreateEffectsAtMapPos(IList`1 keys, Vector3 mapPos, Entity source, Single playbackSpeed) { }
	// RVA: 0x3f4b1fc VA: 0x75965631fc
	public Void CreateMapEffects(IList`1 effects, ILocatable locator, Transform parent) { }
	// RVA: 0x3f4b3d0 VA: 0x75965633d0
	public Effect CreateEffectOn(String key, Transform parent) { }
	// RVA: 0x3f4b508 VA: 0x7596563508
	public Void ThrowEffect(ObjectPtr`1 effect) { }
	// RVA: 0x3f4b628 VA: 0x7596563628
	public static Void PlayAudioAtPos(String signal, String key, Vector3 worldPosition, Entity bindTo) { }
	// RVA: 0x3f4b8b4 VA: 0x75965638b4
	private static Void _PlayBattleCharFX(String signal, String key, Vector3 worldPosition, VoiceQuery query) { }
	// RVA: 0x3f3fbd4 VA: 0x7596557bd4
	private Void _PlayBattleFinishAudio(GameResult result) { }
	// RVA: 0x3f4ba80 VA: 0x7596563a80
	public static CoroutineId StartBattleCoroutine(MonoBehaviour mono, IEnumerator routine) { }
	// RVA: 0x3f4bc4c VA: 0x7596563c4c
	public static Void StopBattleCoroutine(MonoBehaviour mono, CoroutineId coroutineId) { }
	// RVA: 0x3f4bdcc VA: 0x7596563dcc
	public static Void StopAllBattleCoroutines(MonoBehaviour mono, Boolean checkInstance) { }
	// RVA: 0x3f4bf54 VA: 0x7596563f54
	public static Tween StartBattleTween(FP startValue, Action`1 func, FP endValue, FP duration) { }
	// RVA: 0x3f4c094 VA: 0x7596564094
	public static Tween StartBattleTween(Vector2 startPos, Action`1 func, Vector2 endPos, FP duration) { }
	// RVA: 0x3f4c1fc VA: 0x75965641fc
	public UInt32 TakeSnapshotAsHashCode() { }
	// RVA: 0x3f4c6e0 VA: 0x75965646e0
	private Void _LogSnapshot(UInt32 hash) { }
	// RVA: 0x3f4ce50 VA: 0x7596564e50
	public Void RecycleBuffNextFrame(ObjectPtr`1 buff) { }
	// RVA: 0x3f4d098 VA: 0x7596565098
	private Void _UpdateDelayToRecycleBuffContainer() { }
	// RVA: 0x3f4d340 VA: 0x7596565340
	public Void SetSlowMotion(SlowMotionReason reason) { }
	// RVA: 0x3f4d400 VA: 0x7596565400
	public Void RevertSlowMotion(SlowMotionReason reason) { }
	// RVA: 0x3f4d4c4 VA: 0x75965654c4
	public Void LogPlayerOperation(PlayerOprtData oprt) { }
	// RVA: 0x3f4d830 VA: 0x7596565830
	public Journal AchieveBattleJournal() { }
	// RVA: 0x3f4d8ec VA: 0x75965658ec
	public Void CancelAutoReplayIfOn() { }
	// RVA: 0x3f4da0c VA: 0x7596565a0c
	public Boolean IsAutoBattleUnsync() { }
	// RVA: 0x3f4daac VA: 0x7596565aac
	public Void OnPhysicObjectInit(IPhysicObject obj) { }
	// RVA: 0x3f4dbb8 VA: 0x7596565bb8
	public Void OnPhysicObjectRecycle(IPhysicObject obj) { }
	// RVA: 0x3f4dc68 VA: 0x7596565c68
	public Void OnUnitPostInit(Unit unit) { }
	// RVA: 0x3f4dd20 VA: 0x7596565d20
	public Void OnUnitBorn(Unit unit) { }
	// RVA: 0x3f4de00 VA: 0x7596565e00
	public Void OnUnitFinished(Unit unit, FinishReason reason) { }
	// RVA: 0x3f4df4c VA: 0x7596565f4c
	public Void OnCharacterLocate(Character character) { }
	// RVA: 0x3f4e02c VA: 0x759656602c
	public Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x3f4e244 VA: 0x7596566244
	public Void RecycleCard(Character character) { }
	// RVA: 0x3f4e3b4 VA: 0x75965663b4
	public Void OnCharacterAtkOrCbt(Character character) { }
	// RVA: 0x3f4e46c VA: 0x759656646c
	public Void OnDummyTouchedToTile(Character character, Tile tile) { }
	// RVA: 0x3f4e540 VA: 0x7596566540
	public Void OnDummyTouchedToTile(Character character, Tile tile, Vector3 dummyPos) { }
	// RVA: 0x3f4e850 VA: 0x7596566850
	public Boolean Hook_OnDummyDragging() { }
	// RVA: 0x3f4e944 VA: 0x7596566944
	public Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x3f4eab8 VA: 0x7596566ab8
	public Void OnEnemyReachedExit(Enemy enemy, Tile tile) { }
	// RVA: 0x3f4ecc8 VA: 0x7596566cc8
	public Void OnEnemyRecycled(Enemy enemy) { }
	// RVA: 0x3f4ed80 VA: 0x7596566d80
	public Void OnBossEnter(Enemy enemy) { }
	// RVA: 0x3f4eeec VA: 0x7596566eec
	public Void OnGiantBossInit(Enemy enemy) { }
	// RVA: 0x3f4efa4 VA: 0x7596566fa4
	public Void OnPredefinedLocationReached(Object info) { }
	// RVA: 0x3f3dcc4 VA: 0x7596555cc4
	private Void _OnPauseToggled(Boolean isPaused) { }
	// RVA: 0x3f3b434 VA: 0x7596553434
	private Void _OnSpeedLevelChanged(SpeedLevel level) { }
	// RVA: 0x3f4f150 VA: 0x7596567150
	public Void OnWaveWillStart(WaveData wave) { }
	// RVA: 0x3f4f2bc VA: 0x75965672bc
	public Void OnWaveWillFinish(WaveData wave) { }
	// RVA: 0x3f4f428 VA: 0x7596567428
	public Void OnSpecialUITrigger(Object param) { }
	// RVA: 0x3f3c27c VA: 0x759655427c
	private PlayerBattleRank _ParseBattleRank() { }
	// RVA: 0x3f45728 VA: 0x759655d728
	private Character _CreatePredefinedCharacter(PredefinedCharacter slot, Boolean isToken, out Boolean isExcluded) { }
	// RVA: 0x3f45e38 VA: 0x759655de38
	private Void _WithdrawPredefinedCharacter(PredefinedCharacter slot) { }
	// RVA: 0x3f4f4e0 VA: 0x75965674e0
	private Void _PreprocessPredefinedCharacter(BattleCharacterData data, Boolean isToken, out Boolean isExcluded) { }
	// RVA: 0x3f44350 VA: 0x759655c350
	private Void _LoadPredefinedData(PredefinedData predefines) { }
	// RVA: 0x3f4f7a8 VA: 0x75965677a8
	private Void _InitRunes(IRuneDataHolder runeInput, IList`1 legacyRunes, Difficulty difficulty) { }
	// RVA: 0x3f4fae4 VA: 0x7596567ae4
	private Void _CreateAndInitGlobalBuffs(IList`1 data) { }
	// RVA: 0x3f4fe00 VA: 0x7596567e00
	public GlobalBuff CreateAndInitGlobalBuff(GlobalBuffData globalBuffData) { }
	// RVA: 0x3f4ffdc VA: 0x7596567fdc
	public GlobalBuff GetFirstGlobalBuffByKey(String key) { }
	// RVA: 0x3f50158 VA: 0x7596568158
	private Void _CreateAndInitGlobalEnvSystem(IList`1 globalEnvSystemData) { }
	// RVA: 0x3f505c0 VA: 0x75965685c0
	public Void ResetGlobalBuff() { }
	// RVA: 0x3f50754 VA: 0x7596568754
	private Void _ResetGlobalBuffStatics() { }
	// RVA: 0x3f5081c VA: 0x759656881c
	private Void _OnGlobalEnvSystemPostInit() { }
	// RVA: 0x3f509dc VA: 0x75965689dc
	public CardBuff CreateCardBuffWithBlackboard(Buff sourceBuff, Blackboard blackboard, Card card, LifeType lifeType, Boolean isRatio, String key) { }
	// RVA: 0x3f50c34 VA: 0x7596568c34
	public CardBuff CreateCardBuffByCardWithBlackboard(Card sourceCard, Blackboard blackboard, Card card, LifeType lifeType, Boolean isRatio, String key) { }
	// RVA: 0x3f50e8c VA: 0x7596568e8c
	public Void AddDeckBuff(Card card, DeckBuff deckBuff) { }
	// RVA: 0x3f3acb0 VA: 0x7596552cb0
	private Void _SwitchState(State newState, State oldState) { }
	// RVA: 0x3f50f4c VA: 0x7596568f4c
	private Void _RegisterModules() { }
	// RVA: 0x3f50ff0 VA: 0x7596568ff0
	private Void _UpdateGameInfo(FP deltaTime) { }
	// RVA: 0x3f510f4 VA: 0x75965690f4
	private Void _UpdateCost(FP fixedDeltaTime, PlayerSide side) { }
	// RVA: 0x3f512c8 VA: 0x75965692c8
	private Void _UpdatePlayerOrReplayInput() { }
	// RVA: 0x3f3e514 VA: 0x7596556514
	private Void _LoadGameInternal(List`1 playerDataList, LevelData levelData, MapData mapData, Difficulty difficulty, Int32 randomSeed) { }
	// RVA: 0x3f5138c VA: 0x759656938c
	public Void LoadGameWithRune(List`1 playerDataList, LevelData levelData, MapData mapData, Difficulty difficulty, IRuneDataHolder runeInput, out Options levelOptions, out RuneLevelExtraOutput runeExtraData) { }
	// RVA: 0x3f42844 VA: 0x759655a844
	private Void _GenerateDeckDict(ref List`1 playerDataList, LevelData levelData) { }
	// RVA: 0x3f52950 VA: 0x759656a950
	private Void _MergeDeckModifiers(ref List`1 playerDataList) { }
	// RVA: 0x3f3fa38 VA: 0x7596557a38
	private Void _PostProcessCharacters() { }
	// RVA: 0x3f52620 VA: 0x759656a620
	private Void _InitCameraAndMapEffects(MapData mapData, Map map, IList`1 extraDisableLocations) { }
	// RVA: 0x3f52e50 VA: 0x759656ae50
	private String _GetFinalCameraEffect(String originCameraEffect) { }
	// RVA: 0x3f52f68 VA: 0x759656af68
	private Boolean _DoApplyGlobalModifier(ref Modifier modifier, Entity source) { }
	// RVA: 0x3f40520 VA: 0x7596558520
	private Boolean _ApplyGlobalModifier(ref Modifier modifier, Entity source) { }
	// RVA: 0x3f539bc VA: 0x759656b9bc
	private Void _OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x3f400c8 VA: 0x75965580c8
	private Boolean _InitPostprocessSettings(PostprocessMask mask) { }
	// RVA: 0x3f53ac0 VA: 0x759656bac0
	private Void _LoadPools() { }
	// RVA: 0x3f53c6c VA: 0x759656bc6c
	protected override Void Awake() { }
	// RVA: 0x3f53d04 VA: 0x759656bd04
	private Void Update() { }
	// RVA: 0x3f53dac VA: 0x759656bdac
	private Void FixedUpdate() { }
	// RVA: 0x3f43b64 VA: 0x759655bb64
	protected Void OnTick() { }
	// RVA: 0x3f53f54 VA: 0x759656bf54
	protected override Void OnInit() { }
	// RVA: 0x3f540f4 VA: 0x759656c0f4
	public static IEnumerator LiteDisposeBattle(Coroutine showMaskCoro, InvokeWhenUnlock enableNextScene) { }
	// RVA: 0x3f541d4 VA: 0x759656c1d4
	protected override Void OnDestroy() { }
	// RVA: 0x VA: 0x0
	public TSingleton GetOrCreateSingleton(Func`1 creator) { }
	// RVA: 0x3f54650 VA: 0x759656c650
	private static Void .cctor() { }
	// RVA: 0x3f54800 VA: 0x759656c800
	private Void <StartGame>b__303_0() { }
	// RVA: 0x3f549f8 VA: 0x759656c9f8
	private Void <_InitRunes>b__455_0(RuneData runeData) { }
	// RVA: 0x3f54a14 VA: 0x759656ca14
	private Void <_InitRunes>b__455_1(RuneData runeData) { }
}
```