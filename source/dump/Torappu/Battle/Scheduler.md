# Scheduler

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_blockCounter`

- `UInt32 m_spawnedEnemiesCnt`

- `Int32 m_spawnedWavesCnt`

- `ObscuredInt m_finishedEnemiesCnt`

- `ObscuredInt m_killedEnemiesCnt`

- `ObscuredInt m_validFinishedEnemiesCnt`

- `ObscuredInt m_validKilledEnemiesCnt`

- `ObscuredInt m_validMissedEnemiesCnt`

- `FP m_waveStartTime`

- `FP m_fragmentStartTime`

- `Int32 m_cachedEnemiesWaveToAdd`

- `Boolean m_inWavePostDelay`

- `CoroutineId m_mainCoroutine`

- `Boolean m_allowSummonSpawnEnemy`

- `DefaultWaveHandler m_waveHandler`

- `Int32 <totalEnemiesCnt>k__BackingField`

- `BattleController <battleController>k__BackingField`


## Properties

- `Int32 totalEnemiesCnt`

- `Int32 totalWavesCnt`

- `Int32 remainingEnemiesCnt`

- `Int32 finishedEnemiesCnt`

- `UInt32 spawnedEnemiesCnt`

- `Int32 spawnedWavesCnt`

- `Int32 killedEnemiesCnt`

- `Int32 validKilledEnemiesCnt`

- `Int32 validFinishedEnemiesCnt`

- `Int32 validMissedEnemiesCnt`

- `Single completeProgress`

- `Boolean inWavePostDelay`

- `BattleController battleController`

- `Boolean allowSummonSpawnEnemy`


## Methods

- `Int32 get_totalEnemiesCnt()`

- `Void set_totalEnemiesCnt(Int32)`

- `Int32 get_totalWavesCnt()`

- `Int32 get_remainingEnemiesCnt()`

- `Int32 get_finishedEnemiesCnt()`

- `UInt32 get_spawnedEnemiesCnt()`

- `Int32 get_spawnedWavesCnt()`

- `Int32 get_killedEnemiesCnt()`

- `Int32 get_validKilledEnemiesCnt()`

- `Int32 get_validFinishedEnemiesCnt()`

- `Int32 get_validMissedEnemiesCnt()`

- `Single get_completeProgress()`

- `Boolean get_inWavePostDelay()`

- `BattleController get_battleController()`

- `Void set_battleController(BattleController)`

- `Boolean get_allowSummonSpawnEnemy()`

- `Void set_allowSummonSpawnEnemy(Boolean)`

- `Void Init(LevelData, IList`1, IList`1)`

- `Void UpdateWaves(WaveData[])`

- `Boolean _NotCountInTotal(ActionData)`

- `Void OnGameInit(Options)`

- `Void OnGameReady()`

- `Void OnGameStart()`

- `Void RegisterPlugin(IWavePlugin)`

- `Void OnGameReset(BattleController)`

- `Void OnGameOver(GameResult)`

- `Boolean CheckBranchIsReadyToMoveNext(String)`

- `Boolean CheckBranchIsNotEmpty(String)`

- `Boolean TryMoveNextBranch(String, Boolean)`

- `Boolean TryPickRandomBranch(String, Boolean)`

- `Boolean TryPickRandomBranchNotRepeat(String, Boolean)`

- `Boolean TryGetEnemyRouteFromBranch(String, Int32, out, out)`

- `Boolean TryGetEnemyRouteFromBranch(String, Int32, out, out)`

- `Boolean TryGetBranch(String, out)`

- `SchedulerSnapshot TakeSnapshot()`

- `Void FinishCurrentWave(Boolean)`

- `Void FinishCurrentWaveDeeply()`

- `Void ReleaseEnemyFromCurrentWave(Enemy)`

- `Void TrackEnemyAtNextWave(Enemy, Int32)`

- `Void TrackAllManagedEnemiesAtNextWave(Int32)`

- `Void DoSchedule()`

- `IEnumerator _DoSchedule()`

- `Void DoFinishGame(Action)`

- `IEnumerator DealWithAfterBattleWaveFromPluginIfValid(Action)`

- `IEnumerator _DealAfterBattleWaveFromPlugin()`

- `IEnumerator _DealWave(WaveData, WaveData)`

- `IEnumerator _DealFragment(FragmentData)`

- `IEnumerator TryDealDynamicPhase(PhaseData, Func`1, Boolean)`

- `IEnumerator _DoSpawn(ActionData, Action`1)`

- `IEnumerator SpawnSummonedEnemyTrackedInGameMode(String, Enemy, Boolean, Boolean, Vector2, FP, FP, Boolean, Boolean, Boolean, Boolean, Blackboard, BuffData, MotionMask)`

- `IEnumerator SpawnSummonedEnemyTrackedInGameMode(SpawnSummonedEnemyTrackedInGameModeParams)`

- `Enemy SpawnSummonedEnemyWithRuntimeRoute(String, Entity, GridPosition, GridPosition, MotionMode, Boolean, Boolean, Single, Single, Boolean, Boolean, Boolean, Blackboard, BuffData, Boolean)`

- `Enemy SpawnSummonedEnemyWithBranchRoute(String, Int32, Boolean, Boolean, Boolean, Boolean, Boolean, Boolean, String)`

- `Enemy SpawnEnemyWithRoute(String, Entity, Route, Boolean, Boolean, Boolean)`

- `Void SpawnSummonedEnemyWithRuntimeRoute(String, Entity, GridPosition, GridPosition, MotionMode, Boolean, Boolean, CheckpointData[], Boolean, Blackboard, BuffData)`

- `Void SpawnSummonedEnemyWithFixedDirection(String, Enemy, MotionMode, Boolean, Boolean, Single, Single, Single, Int32)`

- `Enemy SpawnEnemyNpc(String, GridPosition, GridPosition, MotionMode, Boolean, Boolean, String, Boolean)`

- `Enemy _DoSpawnEnemyInternal(String, Int32, Options, Boolean)`

- `Enemy _DoSpawnEnemyInternal(String, Route, Options)`

- `Void _AlertSpawnError(String)`

- `Route GenerateRuntimeRoute(RouteData)`

- `Route GenerateRuntimeTraceRoute(GridPosition, MotionMode)`

- `IEnumerator _DoPreviewCursor(ActionData, Action`1)`

- `IEnumerator _DoStory(ActionData, Action`1)`

- `IEnumerator _DoDialog(ActionData, Action`1)`

- `IEnumerator _DoTutorial(ActionData, Action`1)`

- `IEnumerator _DoPlayBGM(ActionData, Action`1)`

- `IEnumerator _DoParseBattleEvents(ActionData, Action`1)`

- `IEnumerator _DoDisplayEnemyInfo(ActionData, Action`1)`

- `IEnumerator _DoActivatePredefined(ActionData, Action`1)`

- `IEnumerator _DoWithdrawPredefined(ActionData, Action`1)`

- `IEnumerator _DoShowAllHiddenCards(ActionData, Action`1)`

- `IEnumerator _DoPlayOpera(ActionData, Action`1)`

- `IEnumerator _DoTriggerPredefined(ActionData, Action`1)`

- `EnemyItem _CreateEnemyItem(EnemyData)`

- `Void _OnActionExecuted(ActionData)`

- `Boolean _CheckWaveNotFinish()`

- `Boolean _CheckFinalNotFinish()`

- `Void _OnUnitDestroyed(Object)`

- `Void MarkEnemyKilled(Enemy)`

- `Void _OnEnemyRecycled(Object)`

- `Boolean TryActivePredefined(String)`

- `Boolean CheckActionEnabled(ActionData)`

- `Void _RegisterActionExecutors()`

- `Boolean <_DealFragment>b__105_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Scheduler : MonoBehaviour, IBattleModule, IHotfixable
{
	private const Int32 PREVIEW_CURSOR_COUNT; // 0x0
	private const Single PREVIEW_CURSOR_PRE_DELAY; // 0x0
	private const Single PREVIEW_CURSOR_INTERVAL; // 0x0
	private static Dictionary`2 s_dictGameFinishBlocker; // 0x0
	private Int32 m_blockCounter; // 0x18
	private UInt32 m_spawnedEnemiesCnt; // 0x1c
	private Int32 m_spawnedWavesCnt; // 0x20
	private ObscuredInt m_finishedEnemiesCnt; // 0x24
	private ObscuredInt m_killedEnemiesCnt; // 0x38
	private ObscuredInt m_validFinishedEnemiesCnt; // 0x4c
	private ObscuredInt m_validKilledEnemiesCnt; // 0x60
	private ObscuredInt m_validMissedEnemiesCnt; // 0x74
	private FP m_waveStartTime; // 0x88
	private FP m_fragmentStartTime; // 0x90
	private WaveData[] m_waves; // 0x98
	private Dictionary`2 m_enemyMap; // 0xa0
	private Func`3[] m_actionExecutors; // 0xa8
	private List`1 m_actionQueue; // 0xb0
	private List`1 m_managedWaveEnemies; // 0xb8
	private List`1 m_managedFinalEnemies; // 0xc0
	private ListDict`2 m_brancheMap; // 0xc8
	private ListSet`1 m_enabledHiddenGroups; // 0xd0
	private ListSet`1 m_cachedEnemies; // 0xd8
	private Int32 m_cachedEnemiesWaveToAdd; // 0xe0
	private Boolean m_inWavePostDelay; // 0xe4
	private CoroutineId m_mainCoroutine; // 0xe8
	private Boolean m_allowSummonSpawnEnemy; // 0xf8
	private DefaultWaveHandler m_waveHandler; // 0x100
	private List`1 m_wavePlugin; // 0x108
	private Int32 <totalEnemiesCnt>k__BackingField; // 0x110
	private BattleController <battleController>k__BackingField; // 0x118
	private static DelegateBridge __Hotfix0_get_totalEnemiesCnt; // 0x8
	private static DelegateBridge __Hotfix0_set_totalEnemiesCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_totalWavesCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_waves; // 0x20
	private static DelegateBridge __Hotfix0_get_remainingEnemiesCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_finishedEnemiesCnt; // 0x30
	private static DelegateBridge __Hotfix0_get_spawnedEnemiesCnt; // 0x38
	private static DelegateBridge __Hotfix0_get_spawnedWavesCnt; // 0x40
	private static DelegateBridge __Hotfix0_get_managedWaveEnemies; // 0x48
	private static DelegateBridge __Hotfix0_get_killedEnemiesCnt; // 0x50
	private static DelegateBridge __Hotfix0_get_validKilledEnemiesCnt; // 0x58
	private static DelegateBridge __Hotfix0_get_validFinishedEnemiesCnt; // 0x60
	private static DelegateBridge __Hotfix0_get_validMissedEnemiesCnt; // 0x68
	private static DelegateBridge __Hotfix0_get_completeProgress; // 0x70
	private static DelegateBridge __Hotfix0_get_inWavePostDelay; // 0x78
	private static DelegateBridge __Hotfix0_get_managedFinalEnemies; // 0x80
	private static DelegateBridge __Hotfix0_get_battleController; // 0x88
	private static DelegateBridge __Hotfix0_set_battleController; // 0x90
	private static DelegateBridge __Hotfix0_get_allowSummonSpawnEnemy; // 0x98
	private static DelegateBridge __Hotfix0_set_allowSummonSpawnEnemy; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateWaves; // 0xb0
	private static DelegateBridge __Hotfix0__NotCountInTotal; // 0xb8
	private static DelegateBridge __Hotfix0_OnGameInit; // 0xc0
	private static DelegateBridge __Hotfix0_OnGameReady; // 0xc8
	private static DelegateBridge __Hotfix0_OnGameStart; // 0xd0
	private static DelegateBridge __Hotfix0_RegisterPlugin; // 0xd8
	private static DelegateBridge __Hotfix0_OnGameReset; // 0xe0
	private static DelegateBridge __Hotfix0_OnGameOver; // 0xe8
	private static DelegateBridge __Hotfix0_CheckBranchIsReadyToMoveNext; // 0xf0
	private static DelegateBridge __Hotfix0_CheckBranchIsNotEmpty; // 0xf8
	private static DelegateBridge __Hotfix0_AddBlockGameKey; // 0x100
	private static DelegateBridge __Hotfix0_RemoveBlockGameKey; // 0x108
	private static DelegateBridge __Hotfix0_TryMoveNextBranch; // 0x110
	private static DelegateBridge __Hotfix0_TryPickRandomBranch; // 0x118
	private static DelegateBridge __Hotfix0_TryPickRandomBranchNotRepeat; // 0x120
	private static DelegateBridge __Hotfix0_TryGetEnemyRouteFromBranch; // 0x128
	private static DelegateBridge __Hotfix1_TryGetEnemyRouteFromBranch; // 0x130
	private static DelegateBridge __Hotfix0_TryGetBranch; // 0x138
	private static DelegateBridge __Hotfix0_TakeSnapshot; // 0x140
	private static DelegateBridge __Hotfix0_FinishCurrentWave; // 0x148
	private static DelegateBridge __Hotfix0_FinishCurrentWaveDeeply; // 0x150
	private static DelegateBridge __Hotfix0_ReleaseEnemyFromCurrentWave; // 0x158
	private static DelegateBridge __Hotfix0_TrackEnemyAtNextWave; // 0x160
	private static DelegateBridge __Hotfix0_TrackAllManagedEnemiesAtNextWave; // 0x168
	private static DelegateBridge __Hotfix0_DoSchedule; // 0x170
	private static DelegateBridge __Hotfix0__DoSchedule; // 0x178
	private static DelegateBridge __Hotfix0_DoFinishGame; // 0x180
	private static DelegateBridge __Hotfix0_DealWithAfterBattleWaveFromPluginIfValid; // 0x188
	private static DelegateBridge __Hotfix0__DealAfterBattleWaveFromPlugin; // 0x190
	private static DelegateBridge __Hotfix0__DealWave; // 0x198
	private static DelegateBridge __Hotfix0__DealFragment; // 0x1a0
	private static DelegateBridge __Hotfix0__DealBranchPhase; // 0x1a8
	private static DelegateBridge __Hotfix0__DealAction; // 0x1b0
	private static DelegateBridge __Hotfix0_TryDealDynamicPhase; // 0x1b8
	private static DelegateBridge __Hotfix0__DoSpawn; // 0x1c0
	private static DelegateBridge __Hotfix0_SpawnSummonedEnemyTrackedInGameMode; // 0x1c8
	private static DelegateBridge __Hotfix1_SpawnSummonedEnemyTrackedInGameMode; // 0x1d0
	private static DelegateBridge __Hotfix0_SpawnSummonedEnemyWithRuntimeRoute; // 0x1d8
	private static DelegateBridge __Hotfix0_SpawnSummonedEnemyWithBranchRoute; // 0x1e0
	private static DelegateBridge __Hotfix0_SpawnEnemyWithRoute; // 0x1e8
	private static DelegateBridge __Hotfix1_SpawnSummonedEnemyWithRuntimeRoute; // 0x1f0
	private static DelegateBridge __Hotfix0_SpawnSummonedEnemyWithFixedDirection; // 0x1f8
	private static DelegateBridge __Hotfix0_SpawnEnemyNpc; // 0x200
	private static DelegateBridge __Hotfix0__DoSpawnEnemyInternal; // 0x208
	private static DelegateBridge __Hotfix1__DoSpawnEnemyInternal; // 0x210
	private static DelegateBridge __Hotfix0__AlertSpawnError; // 0x218
	private static DelegateBridge __Hotfix0_GenerateRuntimeRoute; // 0x220
	private static DelegateBridge __Hotfix0_GenerateRuntimeTraceRoute; // 0x228
	private static DelegateBridge __Hotfix0__DoPreviewCursor; // 0x230
	private static DelegateBridge __Hotfix0__DoStory; // 0x238
	private static DelegateBridge __Hotfix0__DoDialog; // 0x240
	private static DelegateBridge __Hotfix0__DoTutorial; // 0x248
	private static DelegateBridge __Hotfix0__DoPlayBGM; // 0x250
	private static DelegateBridge __Hotfix0__DoParseBattleEvents; // 0x258
	private static DelegateBridge __Hotfix0__DoDisplayEnemyInfo; // 0x260
	private static DelegateBridge __Hotfix0__DoActivatePredefined; // 0x268
	private static DelegateBridge __Hotfix0__DoWithdrawPredefined; // 0x270
	private static DelegateBridge __Hotfix0__DoShowAllHiddenCards; // 0x278
	private static DelegateBridge __Hotfix0__DoPlayOpera; // 0x280
	private static DelegateBridge __Hotfix0__DoTriggerPredefined; // 0x288
	private static DelegateBridge __Hotfix0__CreateEnemyItem; // 0x290
	private static DelegateBridge __Hotfix0__OnActionExecuted; // 0x298
	private static DelegateBridge __Hotfix0__CheckWaveNotFinish; // 0x2a0
	private static DelegateBridge __Hotfix0__CheckFinalNotFinish; // 0x2a8
	private static DelegateBridge __Hotfix0__OnUnitDestroyed; // 0x2b0
	private static DelegateBridge __Hotfix0_MarkEnemyKilled; // 0x2b8
	private static DelegateBridge __Hotfix0__OnEnemyRecycled; // 0x2c0
	private static DelegateBridge __Hotfix0_TryActivePredefined; // 0x2c8
	private static DelegateBridge __Hotfix0_CheckActionEnabled; // 0x2d0
	private static DelegateBridge __Hotfix0__RegisterActionExecutors; // 0x2d8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x2e0

	public Int32 totalEnemiesCnt { get; set; }
	public Int32 totalWavesCnt { get; }
	public WaveData[] waves { get; }
	public Int32 remainingEnemiesCnt { get; }
	public Int32 finishedEnemiesCnt { get; }
	public UInt32 spawnedEnemiesCnt { get; }
	public Int32 spawnedWavesCnt { get; }
	public List`1 managedWaveEnemies { get; }
	public Int32 killedEnemiesCnt { get; }
	public Int32 validKilledEnemiesCnt { get; }
	public Int32 validFinishedEnemiesCnt { get; }
	public Int32 validMissedEnemiesCnt { get; }
	public Single completeProgress { get; }
	public Boolean inWavePostDelay { get; }
	public List`1 managedFinalEnemies { get; }
	private BattleController battleController { get; set; }
	public Boolean allowSummonSpawnEnemy { get; set; }

	// RVA: 0x40cf818 VA: 0x75966e7818
	public Int32 get_totalEnemiesCnt() { }
	// RVA: 0x40cf890 VA: 0x75966e7890
	private Void set_totalEnemiesCnt(Int32 value) { }
	// RVA: 0x40cf91c VA: 0x75966e791c
	public Int32 get_totalWavesCnt() { }
	// RVA: 0x40cf9a0 VA: 0x75966e79a0
	public WaveData[] get_waves() { }
	// RVA: 0x40cfa18 VA: 0x75966e7a18
	public Int32 get_remainingEnemiesCnt() { }
	// RVA: 0x40cfafc VA: 0x75966e7afc
	public Int32 get_finishedEnemiesCnt() { }
	// RVA: 0x40cfbcc VA: 0x75966e7bcc
	public UInt32 get_spawnedEnemiesCnt() { }
	// RVA: 0x40cfc44 VA: 0x75966e7c44
	public Int32 get_spawnedWavesCnt() { }
	// RVA: 0x40cfcbc VA: 0x75966e7cbc
	public List`1 get_managedWaveEnemies() { }
	// RVA: 0x40cfd34 VA: 0x75966e7d34
	public Int32 get_killedEnemiesCnt() { }
	// RVA: 0x40cfe04 VA: 0x75966e7e04
	public Int32 get_validKilledEnemiesCnt() { }
	// RVA: 0x40cfed4 VA: 0x75966e7ed4
	public Int32 get_validFinishedEnemiesCnt() { }
	// RVA: 0x40cffa4 VA: 0x75966e7fa4
	public Int32 get_validMissedEnemiesCnt() { }
	// RVA: 0x40d0074 VA: 0x75966e8074
	public Single get_completeProgress() { }
	// RVA: 0x40d0170 VA: 0x75966e8170
	public Boolean get_inWavePostDelay() { }
	// RVA: 0x40d01e8 VA: 0x75966e81e8
	public List`1 get_managedFinalEnemies() { }
	// RVA: 0x40d0260 VA: 0x75966e8260
	private BattleController get_battleController() { }
	// RVA: 0x40d02d8 VA: 0x75966e82d8
	private Void set_battleController(BattleController value) { }
	// RVA: 0x40d036c VA: 0x75966e836c
	public Boolean get_allowSummonSpawnEnemy() { }
	// RVA: 0x40d03e4 VA: 0x75966e83e4
	public Void set_allowSummonSpawnEnemy(Boolean value) { }
	// RVA: 0x40d0474 VA: 0x75966e8474
	public Void Init(LevelData levelData, IList`1 enabledHiddenGroups, IList`1 disabledHiddenGroups) { }
	// RVA: 0x40d1dc0 VA: 0x75966e9dc0
	public Void UpdateWaves(WaveData[] newWaves) { }
	// RVA: 0x40d1660 VA: 0x75966e9660
	private Boolean _NotCountInTotal(ActionData actionData) { }
	// RVA: 0x40d1e88 VA: 0x75966e9e88
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x40d1f10 VA: 0x75966e9f10
	public Void OnGameReady() { }
	// RVA: 0x40d1f84 VA: 0x75966e9f84
	public Void OnGameStart() { }
	// RVA: 0x40d2178 VA: 0x75966ea178
	public Void RegisterPlugin(IWavePlugin wavePlugin) { }
	// RVA: 0x40d2284 VA: 0x75966ea284
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x40d245c VA: 0x75966ea45c
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x40d2514 VA: 0x75966ea514
	public Boolean CheckBranchIsReadyToMoveNext(String branchId) { }
	// RVA: 0x40d2648 VA: 0x75966ea648
	public Boolean CheckBranchIsNotEmpty(String branchId) { }
	// RVA: 0x40d2744 VA: 0x75966ea744
	public static Void AddBlockGameKey(String key) { }
	// RVA: 0x40d28bc VA: 0x75966ea8bc
	public static Void RemoveBlockGameKey(String key) { }
	// RVA: 0x40d2a58 VA: 0x75966eaa58
	public Boolean TryMoveNextBranch(String branchId, Boolean isLoop) { }
	// RVA: 0x40d2e90 VA: 0x75966eae90
	public Boolean TryPickRandomBranch(String branchId, Boolean blockGameFinish) { }
	// RVA: 0x40d318c VA: 0x75966eb18c
	public Boolean TryPickRandomBranchNotRepeat(String branchId, Boolean blockGameFinish) { }
	// RVA: 0x40d3544 VA: 0x75966eb544
	public Boolean TryGetEnemyRouteFromBranch(String branchId, Int32 actionIndex, out Route route, out String enemyKey) { }
	// RVA: 0x40d3680 VA: 0x75966eb680
	public Boolean TryGetEnemyRouteFromBranch(String branchId, Int32 actionIndex, out Int32 routeIndex, out String enemyKey) { }
	// RVA: 0x40d3844 VA: 0x75966eb844
	public Boolean TryGetBranch(String branchId, out BranchData branchData) { }
	// RVA: 0x40d3944 VA: 0x75966eb944
	public SchedulerSnapshot TakeSnapshot() { }
	// RVA: 0x40d39e4 VA: 0x75966eb9e4
	public Void FinishCurrentWave(Boolean alsoFinishFinalEnemies) { }
	// RVA: 0x40d3ae4 VA: 0x75966ebae4
	public Void FinishCurrentWaveDeeply() { }
	// RVA: 0x40d3bd4 VA: 0x75966ebbd4
	public Void ReleaseEnemyFromCurrentWave(Enemy enemy) { }
	// RVA: 0x40d3c84 VA: 0x75966ebc84
	public Void TrackEnemyAtNextWave(Enemy enemy, Int32 waveDelta) { }
	// RVA: 0x40d3d4c VA: 0x75966ebd4c
	public Void TrackAllManagedEnemiesAtNextWave(Int32 waveDelta) { }
	// RVA: 0x40d20b0 VA: 0x75966ea0b0
	public Void DoSchedule() { }
	// RVA: 0x40d3e0c VA: 0x75966ebe0c
	private IEnumerator _DoSchedule() { }
	// RVA: 0x40d3ef0 VA: 0x75966ebef0
	public Void DoFinishGame(Action callback) { }
	// RVA: 0x40d4004 VA: 0x75966ec004
	public IEnumerator DealWithAfterBattleWaveFromPluginIfValid(Action callback) { }
	// RVA: 0x40d410c VA: 0x75966ec10c
	private IEnumerator _DealAfterBattleWaveFromPlugin() { }
	// RVA: 0x40d41f0 VA: 0x75966ec1f0
	private IEnumerator _DealWave(WaveData wave, WaveData nextWave) { }
	// RVA: 0x40d4310 VA: 0x75966ec310
	private IEnumerator _DealFragment(FragmentData fragment) { }
	// RVA: 0x40d2d14 VA: 0x75966ead14
	private static IEnumerator _DealBranchPhase(PhaseData phase, DefaultWaveHandler handler, Dictionary`2 enemyMap, Func`3[] actionExecutors, Func`2 actionValidator, String branchId, Boolean blockGameFinish, Func`1 actionBlockTimer) { }
	// RVA: 0x40d4440 VA: 0x75966ec440
	private static Void _DealAction(ActionData action, Single fragmentPreDelay, Dictionary`2 enemyMap, List`1 actionQueue, ref Int32 blockCounter, Boolean fromBranch) { }
	// RVA: 0x40d4818 VA: 0x75966ec818
	public IEnumerator TryDealDynamicPhase(PhaseData phaseData, Func`1 actionBlockTimer, Boolean includeInTotalEnemy) { }
	// RVA: 0x40d4954 VA: 0x75966ec954
	private IEnumerator _DoSpawn(ActionData data, Action`1 cb) { }
	// RVA: 0x40d4a74 VA: 0x75966eca74
	public IEnumerator SpawnSummonedEnemyTrackedInGameMode(String enemyKey, Enemy host, Boolean managedByScheduler, Boolean dontBlockWave, Vector2 summonPos, FP randomOffset, FP delayTime, Boolean ignoreOffset, Boolean unharmful, Boolean stopSummonIfHostDead, Boolean addBuffToEnemy, Blackboard blackboard, BuffData buffData, MotionMask _checkMotionMode) { }
	// RVA: 0x40d4c94 VA: 0x75966ecc94
	public IEnumerator SpawnSummonedEnemyTrackedInGameMode(SpawnSummonedEnemyTrackedInGameModeParams param) { }
	// RVA: 0x40d4dc8 VA: 0x75966ecdc8
	public Enemy SpawnSummonedEnemyWithRuntimeRoute(String enemyKey, Entity host, GridPosition sourcePos, GridPosition targetPos, MotionMode motionMode, Boolean unharmful, Boolean alwaysCountAsKilled, Single waitTime, Single offset, Boolean managedByScheduler, Boolean avoidHighland, Boolean addBuffToEnemy, Blackboard blackboard, BuffData buffData, Boolean withOutHost) { }
	// RVA: 0x40d5560 VA: 0x75966ed560
	public Enemy SpawnSummonedEnemyWithBranchRoute(String branchId, Int32 actionIndex, Boolean dontBlockWave, Boolean unharmful, Boolean alwaysCountAsKilled, Boolean isSummon, Boolean managedByScheduler, Boolean disableBornTweenColor, String overrideEnemyKey) { }
	// RVA: 0x40d5954 VA: 0x75966ed954
	public Enemy SpawnEnemyWithRoute(String enemyKey, Entity host, Route route, Boolean unharmful, Boolean alwaysCountAsKilled, Boolean managedByScheduler) { }
	// RVA: 0x40d5b88 VA: 0x75966edb88
	public Void SpawnSummonedEnemyWithRuntimeRoute(String enemyKey, Entity host, GridPosition startGridPos, GridPosition endGridPos, MotionMode motionMode, Boolean unharmful, Boolean alwaysCountAsKilled, CheckpointData[] checkPointDataArray, Boolean addBuffToEnemy, Blackboard blackboard, BuffData buffData) { }
	// RVA: 0x40d5e70 VA: 0x75966ede70
	public Void SpawnSummonedEnemyWithFixedDirection(String enemyKey, Enemy host, MotionMode motionMode, Boolean unharmful, Boolean alwaysCountAsKilled, Single offset, Single startAngle, Single endAngle, Int32 summonCnt) { }
	// RVA: 0x40d6374 VA: 0x75966ee374
	public Enemy SpawnEnemyNpc(String enemyKey, GridPosition targetPos, GridPosition endPos, MotionMode motionMode, Boolean unharmful, Boolean alwaysCountAsKilled, String alias, Boolean randomOffset) { }
	// RVA: 0x40d6b90 VA: 0x75966eeb90
	private Enemy _DoSpawnEnemyInternal(String enemyKey, Int32 routeIndex, Options options, Boolean isExtraRoute) { }
	// RVA: 0x40d5394 VA: 0x75966ed394
	private Enemy _DoSpawnEnemyInternal(String enemyKey, Route route, Options options) { }
	// RVA: 0x40d6d68 VA: 0x75966eed68
	private Void _AlertSpawnError(String enemyKey) { }
	// RVA: 0x40d6ec8 VA: 0x75966eeec8
	public Route GenerateRuntimeRoute(RouteData data) { }
	// RVA: 0x40d6f7c VA: 0x75966eef7c
	public Route GenerateRuntimeTraceRoute(GridPosition tracePosition, MotionMode motionMode) { }
	// RVA: 0x40d703c VA: 0x75966ef03c
	private IEnumerator _DoPreviewCursor(ActionData data, Action`1 cb) { }
	// RVA: 0x40d715c VA: 0x75966ef15c
	private IEnumerator _DoStory(ActionData data, Action`1 cb) { }
	// RVA: 0x40d726c VA: 0x75966ef26c
	private IEnumerator _DoDialog(ActionData data, Action`1 cb) { }
	// RVA: 0x40d736c VA: 0x75966ef36c
	private IEnumerator _DoTutorial(ActionData data, Action`1 cb) { }
	// RVA: 0x40d747c VA: 0x75966ef47c
	private IEnumerator _DoPlayBGM(ActionData data, Action`1 cb) { }
	// RVA: 0x40d758c VA: 0x75966ef58c
	private IEnumerator _DoParseBattleEvents(ActionData data, Action`1 cb) { }
	// RVA: 0x40d76ac VA: 0x75966ef6ac
	private IEnumerator _DoDisplayEnemyInfo(ActionData data, Action`1 cb) { }
	// RVA: 0x40d77cc VA: 0x75966ef7cc
	private IEnumerator _DoActivatePredefined(ActionData data, Action`1 cb) { }
	// RVA: 0x40d78ec VA: 0x75966ef8ec
	private IEnumerator _DoWithdrawPredefined(ActionData data, Action`1 cb) { }
	// RVA: 0x40d79fc VA: 0x75966ef9fc
	private IEnumerator _DoShowAllHiddenCards(ActionData data, Action`1 cb) { }
	// RVA: 0x40d7b0c VA: 0x75966efb0c
	private IEnumerator _DoPlayOpera(ActionData data, Action`1 cb) { }
	// RVA: 0x40d7c1c VA: 0x75966efc1c
	private IEnumerator _DoTriggerPredefined(ActionData data, Action`1 cb) { }
	// RVA: 0x40d1130 VA: 0x75966e9130
	private EnemyItem _CreateEnemyItem(EnemyData enemyData) { }
	// RVA: 0x40d7d2c VA: 0x75966efd2c
	private Void _OnActionExecuted(ActionData data) { }
	// RVA: 0x40d7dd0 VA: 0x75966efdd0
	private Boolean _CheckWaveNotFinish() { }
	// RVA: 0x40d7f24 VA: 0x75966eff24
	private Boolean _CheckFinalNotFinish() { }
	// RVA: 0x40d8094 VA: 0x75966f0094
	private Void _OnUnitDestroyed(Object arg) { }
	// RVA: 0x40d87dc VA: 0x75966f07dc
	public Void MarkEnemyKilled(Enemy enemy) { }
	// RVA: 0x40d89d4 VA: 0x75966f09d4
	private Void _OnEnemyRecycled(Object arg) { }
	// RVA: 0x40d8b18 VA: 0x75966f0b18
	public Boolean TryActivePredefined(String alias) { }
	// RVA: 0x40d1594 VA: 0x75966e9594
	public Boolean CheckActionEnabled(ActionData actionData) { }
	// RVA: 0x40d17a4 VA: 0x75966e97a4
	private Void _RegisterActionExecutors() { }
	// RVA: 0x40d8ca0 VA: 0x75966f0ca0
	public Void .ctor() { }
	// RVA: 0x40d90ac VA: 0x75966f10ac
	private static Void .cctor() { }
	// RVA: 0x40d9144 VA: 0x75966f1144
	private Boolean <_DealFragment>b__105_1() { }
}
```