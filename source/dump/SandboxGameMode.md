# SandboxGameMode

**Namespace:** ` `


## Fields

- `SandboxInput m_input`

- `SandboxOutput m_output`

- `SandboxBattleManager m_battleManager`

- `String m_topicId`

- `SandboxV2Data m_configData`

- `LevelData m_levelData`

- `Boolean m_gameHasFinished`

- `FP m_maxPlayTime`

- `Boolean m_isInBuildType`

- `Boolean m_isTimingNode`

- `Boolean m_isRushEnemyMode`

- `Boolean m_isRacerCatchMode`


## Properties

- `BattleRenderInvisibleMask renderInvisibleMask`

- `BattleRenderInvisibleMask renderCameraVisibleMask`

- `Boolean isInMonthlyBattle`

- `Boolean isRushEnemyMode`

- `Boolean isRacerCatchMode`

- `Boolean isTimingMode`

- `Boolean isInfiniteTimeLevel`

- `Boolean isInMarketType`

- `SandboxV2Data configData`

- `SandboxBattleManager battleManager`

- `String topicId`

- `SandboxInput input`

- `SandboxOutput output`

- `LevelData levelData`

- `SandboxV2NodeType currentNodeType`

- `SandboxV2SeasonType currentSeasonType`

- `String currentWeatherId`

- `Boolean isInBuildType`


## Methods

- `BattleRenderInvisibleMask get_renderInvisibleMask()`

- `BattleRenderInvisibleMask get_renderCameraVisibleMask()`

- `Boolean get_isInMonthlyBattle()`

- `Boolean get_isRushEnemyMode()`

- `Boolean get_isRacerCatchMode()`

- `Boolean get_isTimingMode()`

- `Boolean get_isInfiniteTimeLevel()`

- `Boolean get_isInMarketType()`

- `SandboxV2Data get_configData()`

- `SandboxBattleManager get_battleManager()`

- `String get_topicId()`

- `SandboxInput get_input()`

- `SandboxOutput get_output()`

- `LevelData get_levelData()`

- `SandboxV2NodeType get_currentNodeType()`

- `SandboxV2SeasonType get_currentSeasonType()`

- `String get_currentWeatherId()`

- `Boolean get_isInBuildType()`

- `SandboxOutput FetchGameOverOutput()`

- `Boolean HaveRemainAp()`

- `Boolean HaveEscapeTrap()`

- `Int32 GetFarmRemainingTime()`

- `Int32 GetFarmMaxTime()`

- `Single GetFarmProgress()`

- `Void _CheckGameFinish()`

- `Int32 <SortDeck>b__73_0(Card, Card)`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Boolean <>xLuaBaseProxy_get_isLargeMap()`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `String <>xLuaBaseProxy_HookTileEffect(String)`

- `String <>xLuaBaseProxy_HookTileAppendInfoKey(String)`

- `Boolean <>xLuaBaseProxy_CheckTileValid(Int32, Int32)`

- `Void <>xLuaBaseProxy_OnGameOver(ref)`

- `Void <>xLuaBaseProxy_PreprocessPlayerDeckList(ListDict`2)`

- `Void <>xLuaBaseProxy_PreprocessCharacterCard(BattleCharacterData, Character)`

- `Void <>xLuaBaseProxy_PreprocessEnemy(EnemyData)`

- `Void <>xLuaBaseProxy_PreprocessRuneData(RuneManager)`

- `Void <>xLuaBaseProxy_SortDeck(Card[])`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card)`

- `Void <>xLuaBaseProxy_OnCharacterFinished(Character, FinishReason)`

- `Void <>xLuaBaseProxy_OnEnemyFinished(Enemy, FinishReason)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_OnCardListChanged(Card)`

- `Void <>xLuaBaseProxy_StartGame(Action)`

- `IEnumerator <>xLuaBaseProxy_FinalSchedule()`

- `Void <>xLuaBaseProxy_PreprocessLevelWithScheduler(LevelData)`

- `Boolean <>xLuaBaseProxy_GameNotFinishCondition()`

- `Object <>xLuaBaseProxy_GetActMeta()`

- `Void <>xLuaBaseProxy_FinishGame(Action`2, GameResult, Boolean)`

- `PlayerBattleRank <>xLuaBaseProxy_GetBattleCompleteRank()`

- `Void <>xLuaBaseProxy_PostprocessMap(Map)`

- `Boolean <>xLuaBaseProxy_CheckRenderInvisible(Entity, BattleRenderInvisibleMask)`

- `Void <>xLuaBaseProxy_OnPostInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxGameMode : DefaultGameMode
{
	private SandboxInput m_input; // 0x20
	private SandboxOutput m_output; // 0x28
	private SandboxBattleManager m_battleManager; // 0x30
	private String m_topicId; // 0x38
	private SandboxV2Data m_configData; // 0x40
	private LevelData m_levelData; // 0x48
	private Boolean m_gameHasFinished; // 0x50
	private FP m_maxPlayTime; // 0x58
	private Boolean m_isInBuildType; // 0x60
	private Boolean m_isTimingNode; // 0x61
	private Boolean m_isRushEnemyMode; // 0x62
	private Boolean m_isRacerCatchMode; // 0x63
	private Dictionary`2 m_materialKeywordData; // 0x68
	private static DelegateBridge __Hotfix0_get_renderInvisibleMask; // 0x0
	private static DelegateBridge __Hotfix0_get_renderCameraVisibleMask; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_isInMonthlyBattle; // 0x18
	private static DelegateBridge __Hotfix0_get_isRushEnemyMode; // 0x20
	private static DelegateBridge __Hotfix0_get_isRacerCatchMode; // 0x28
	private static DelegateBridge __Hotfix0_get_isTimingMode; // 0x30
	private static DelegateBridge __Hotfix0_get_isInfiniteTimeLevel; // 0x38
	private static DelegateBridge __Hotfix0_get_isInMarketType; // 0x40
	private static DelegateBridge __Hotfix0_get_configData; // 0x48
	private static DelegateBridge __Hotfix0_get_materialKeywordData; // 0x50
	private static DelegateBridge __Hotfix0_get_battleManager; // 0x58
	private static DelegateBridge __Hotfix0_get_topicId; // 0x60
	private static DelegateBridge __Hotfix0_get_input; // 0x68
	private static DelegateBridge __Hotfix0_get_output; // 0x70
	private static DelegateBridge __Hotfix0_get_levelData; // 0x78
	private static DelegateBridge __Hotfix0_get_currentNodeType; // 0x80
	private static DelegateBridge __Hotfix0_get_currentSeasonType; // 0x88
	private static DelegateBridge __Hotfix0_get_currentWeatherId; // 0x90
	private static DelegateBridge __Hotfix0_get_isInBuildType; // 0x98
	private static DelegateBridge __Hotfix0_FetchGameOverOutput; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0xa8
	private static DelegateBridge __Hotfix0_HaveRemainAp; // 0xb0
	private static DelegateBridge __Hotfix0_HaveEscapeTrap; // 0xb8
	private static DelegateBridge __Hotfix0_GetFarmRemainingTime; // 0xc0
	private static DelegateBridge __Hotfix0_GetFarmMaxTime; // 0xc8
	private static DelegateBridge __Hotfix0_GetFarmProgress; // 0xd0
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0xd8
	private static DelegateBridge __Hotfix0_get_isLargeMap; // 0xe0
	private static DelegateBridge __Hotfix0_Tick; // 0xe8
	private static DelegateBridge __Hotfix0__CheckGameFinish; // 0xf0
	private static DelegateBridge __Hotfix0_HookTileEffect; // 0xf8
	private static DelegateBridge __Hotfix0_HookTileAppendInfoKey; // 0x100
	private static DelegateBridge __Hotfix0_CheckTileValid; // 0x108
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x110
	private static DelegateBridge __Hotfix0_PreprocessPlayerDeckList; // 0x118
	private static DelegateBridge __Hotfix0_PreprocessCharacterCard; // 0x120
	private static DelegateBridge __Hotfix0_PreprocessEnemy; // 0x128
	private static DelegateBridge __Hotfix0_PreprocessRuneData; // 0x130
	private static DelegateBridge __Hotfix0_SortDeck; // 0x138
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x140
	private static DelegateBridge __Hotfix0_GatherGlobalBuffs; // 0x148
	private static DelegateBridge __Hotfix0_CheckCardReadyToSpawn; // 0x150
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x158
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x160
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x168
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x170
	private static DelegateBridge __Hotfix0_StartGame; // 0x178
	private static DelegateBridge __Hotfix0_FinalSchedule; // 0x180
	private static DelegateBridge __Hotfix0_PreprocessLevelWithScheduler; // 0x188
	private static DelegateBridge __Hotfix0_GameNotFinishCondition; // 0x190
	private static DelegateBridge __Hotfix0_GetActMeta; // 0x198
	private static DelegateBridge __Hotfix0_FinishGame; // 0x1a0
	private static DelegateBridge __Hotfix0_GetBattleCompleteRank; // 0x1a8
	private static DelegateBridge __Hotfix0_PostprocessMap; // 0x1b0
	private static DelegateBridge __Hotfix0_CheckRenderInvisible; // 0x1b8
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x1c0

	private BattleRenderInvisibleMask renderInvisibleMask { get; }
	private BattleRenderInvisibleMask renderCameraVisibleMask { get; }
	public Boolean isInMonthlyBattle { get; }
	public Boolean isRushEnemyMode { get; }
	public Boolean isRacerCatchMode { get; }
	public Boolean isTimingMode { get; }
	public Boolean isInfiniteTimeLevel { get; }
	public Boolean isInMarketType { get; }
	public SandboxV2Data configData { get; }
	public Dictionary`2 materialKeywordData { get; }
	public SandboxBattleManager battleManager { get; }
	public String topicId { get; }
	public SandboxInput input { get; }
	public SandboxOutput output { get; }
	public LevelData levelData { get; }
	public SandboxV2NodeType currentNodeType { get; }
	public SandboxV2SeasonType currentSeasonType { get; }
	public String currentWeatherId { get; }
	public Boolean isInBuildType { get; }
	public override GameModeType gameModeType { get; }
	public override Boolean isLargeMap { get; }

	// RVA: 0x1cf741c VA: 0x759430f41c
	private BattleRenderInvisibleMask get_renderInvisibleMask() { }
	// RVA: 0x1cf7480 VA: 0x759430f480
	private BattleRenderInvisibleMask get_renderCameraVisibleMask() { }
	// RVA: 0x1cf74e8 VA: 0x759430f4e8
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cf7688 VA: 0x759430f688
	public Boolean get_isInMonthlyBattle() { }
	// RVA: 0x1cf778c VA: 0x759430f78c
	public Boolean get_isRushEnemyMode() { }
	// RVA: 0x1cf77f4 VA: 0x759430f7f4
	public Boolean get_isRacerCatchMode() { }
	// RVA: 0x1cf785c VA: 0x759430f85c
	public Boolean get_isTimingMode() { }
	// RVA: 0x1cf78d8 VA: 0x759430f8d8
	public Boolean get_isInfiniteTimeLevel() { }
	// RVA: 0x1cf79c4 VA: 0x759430f9c4
	public Boolean get_isInMarketType() { }
	// RVA: 0x1cf7ab4 VA: 0x759430fab4
	public SandboxV2Data get_configData() { }
	// RVA: 0x1cf7b1c VA: 0x759430fb1c
	public Dictionary`2 get_materialKeywordData() { }
	// RVA: 0x1cf7bc8 VA: 0x759430fbc8
	public SandboxBattleManager get_battleManager() { }
	// RVA: 0x1cf7c30 VA: 0x759430fc30
	public String get_topicId() { }
	// RVA: 0x1cf7724 VA: 0x759430f724
	public SandboxInput get_input() { }
	// RVA: 0x1cf7c98 VA: 0x759430fc98
	public SandboxOutput get_output() { }
	// RVA: 0x1cf7d00 VA: 0x759430fd00
	public LevelData get_levelData() { }
	// RVA: 0x1cf7a38 VA: 0x759430fa38
	public SandboxV2NodeType get_currentNodeType() { }
	// RVA: 0x1cf7d68 VA: 0x759430fd68
	public SandboxV2SeasonType get_currentSeasonType() { }
	// RVA: 0x1cf7de4 VA: 0x759430fde4
	public String get_currentWeatherId() { }
	// RVA: 0x1cf795c VA: 0x759430f95c
	public Boolean get_isInBuildType() { }
	// RVA: 0x1cf7e60 VA: 0x759430fe60
	public SandboxOutput FetchGameOverOutput() { }
	// RVA: 0x1cf7edc VA: 0x759430fedc
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cf8318 VA: 0x7594310318
	public Boolean HaveRemainAp() { }
	// RVA: 0x1cf8394 VA: 0x7594310394
	public Boolean HaveEscapeTrap() { }
	// RVA: 0x1cf8408 VA: 0x7594310408
	public Int32 GetFarmRemainingTime() { }
	// RVA: 0x1cf853c VA: 0x759431053c
	public Int32 GetFarmMaxTime() { }
	// RVA: 0x1cf85d0 VA: 0x75943105d0
	public Single GetFarmProgress() { }
	// RVA: 0x1cf86b8 VA: 0x75943106b8
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cf8720 VA: 0x7594310720
	public override Boolean get_isLargeMap() { }
	// RVA: 0x1cf8788 VA: 0x7594310788
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cf881c VA: 0x759431081c
	private Void _CheckGameFinish() { }
	// RVA: 0x1cf89b4 VA: 0x75943109b4
	public override String HookTileEffect(String originEffectKey) { }
	// RVA: 0x1cf8ae4 VA: 0x7594310ae4
	public override String HookTileAppendInfoKey(String originTileKey) { }
	// RVA: 0x1cf8c08 VA: 0x7594310c08
	public override Boolean CheckTileValid(Int32 row, Int32 col) { }
	// RVA: 0x1cf8ca0 VA: 0x7594310ca0
	public override Void OnGameOver(ref GameResult result) { }
	// RVA: 0x1cf8d2c VA: 0x7594310d2c
	public override Void PreprocessPlayerDeckList(ListDict`2 deckList) { }
	// RVA: 0x1cf8db8 VA: 0x7594310db8
	public override Void PreprocessCharacterCard(BattleCharacterData data, Character character) { }
	// RVA: 0x1cf8e64 VA: 0x7594310e64
	public override Void PreprocessEnemy(EnemyData data) { }
	// RVA: 0x1cf8ef0 VA: 0x7594310ef0
	public override Void PreprocessRuneData(RuneManager manager) { }
	// RVA: 0x1cf8f7c VA: 0x7594310f7c
	public override Void SortDeck(Card[] cards) { }
	// RVA: 0x1cf9060 VA: 0x7594311060
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cf90d4 VA: 0x75943110d4
	public override List`1 GatherGlobalBuffs() { }
	// RVA: 0x1cf9148 VA: 0x7594311148
	public override Boolean CheckCardReadyToSpawn(Card card) { }
	// RVA: 0x1cf91fc VA: 0x75943111fc
	public override Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cf9294 VA: 0x7594311294
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1cf932c VA: 0x759431132c
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cf9460 VA: 0x7594311460
	public override Void OnCardListChanged(Card card) { }
	// RVA: 0x1cf94f8 VA: 0x75943114f8
	public override Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1cf9594 VA: 0x7594311594
	public override IEnumerator FinalSchedule() { }
	// RVA: 0x1cf9668 VA: 0x7594311668
	public override Void PreprocessLevelWithScheduler(LevelData levelData) { }
	// RVA: 0x1cf96f4 VA: 0x75943116f4
	public override Boolean GameNotFinishCondition() { }
	// RVA: 0x1cf97c0 VA: 0x75943117c0
	public override Object GetActMeta() { }
	// RVA: 0x1cf9828 VA: 0x7594311828
	public override Void FinishGame(Action`2 gameFinishCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1cf99e0 VA: 0x75943119e0
	public override PlayerBattleRank GetBattleCompleteRank() { }
	// RVA: 0x1cf9a78 VA: 0x7594311a78
	public override Void PostprocessMap(Map map) { }
	// RVA: 0x1cf9b04 VA: 0x7594311b04
	public override Boolean CheckRenderInvisible(Entity entity, BattleRenderInvisibleMask mask) { }
	// RVA: 0x1cf9cc0 VA: 0x7594311cc0
	public override Void OnPostInit() { }
	// RVA: 0x1cf9d88 VA: 0x7594311d88
	private Int32 <SortDeck>b__73_0(Card lhs, Card rhs) { }
	// RVA: 0x1cfa0cc VA: 0x75943120cc
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cfa0d4 VA: 0x75943120d4
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cfa0dc VA: 0x75943120dc
	private Boolean <>xLuaBaseProxy_get_isLargeMap() { }
	// RVA: 0x1cfa0e4 VA: 0x75943120e4
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cfa0ec VA: 0x75943120ec
	private String <>xLuaBaseProxy_HookTileEffect(String P0) { }
	// RVA: 0x1cfa0f4 VA: 0x75943120f4
	private String <>xLuaBaseProxy_HookTileAppendInfoKey(String P0) { }
	// RVA: 0x1cfa0fc VA: 0x75943120fc
	private Boolean <>xLuaBaseProxy_CheckTileValid(Int32 P0, Int32 P1) { }
	// RVA: 0x1cfa104 VA: 0x7594312104
	private Void <>xLuaBaseProxy_OnGameOver(ref GameResult P0) { }
	// RVA: 0x1cfa10c VA: 0x759431210c
	private Void <>xLuaBaseProxy_PreprocessPlayerDeckList(ListDict`2 P0) { }
	// RVA: 0x1cfa114 VA: 0x7594312114
	private Void <>xLuaBaseProxy_PreprocessCharacterCard(BattleCharacterData P0, Character P1) { }
	// RVA: 0x1cfa11c VA: 0x759431211c
	private Void <>xLuaBaseProxy_PreprocessEnemy(EnemyData P0) { }
	// RVA: 0x1cfa124 VA: 0x7594312124
	private Void <>xLuaBaseProxy_PreprocessRuneData(RuneManager P0) { }
	// RVA: 0x1cfa12c VA: 0x759431212c
	private Void <>xLuaBaseProxy_SortDeck(Card[] P0) { }
	// RVA: 0x1cfa134 VA: 0x7594312134
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cfa13c VA: 0x759431213c
	private List`1 <>xLuaBaseProxy_GatherGlobalBuffs() { }
	// RVA: 0x1cfa144 VA: 0x7594312144
	private Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card P0) { }
	// RVA: 0x1cfa14c VA: 0x759431214c
	private Void <>xLuaBaseProxy_OnCharacterFinished(Character P0, FinishReason P1) { }
	// RVA: 0x1cfa154 VA: 0x7594312154
	private Void <>xLuaBaseProxy_OnEnemyFinished(Enemy P0, FinishReason P1) { }
	// RVA: 0x1cfa15c VA: 0x759431215c
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1cfa164 VA: 0x7594312164
	private Void <>xLuaBaseProxy_OnCardListChanged(Card P0) { }
	// RVA: 0x1cfa16c VA: 0x759431216c
	private Void <>xLuaBaseProxy_StartGame(Action P0) { }
	// RVA: 0x1cfa174 VA: 0x7594312174
	private IEnumerator <>xLuaBaseProxy_FinalSchedule() { }
	// RVA: 0x1cfa17c VA: 0x759431217c
	private Void <>xLuaBaseProxy_PreprocessLevelWithScheduler(LevelData P0) { }
	// RVA: 0x1cfa184 VA: 0x7594312184
	private Boolean <>xLuaBaseProxy_GameNotFinishCondition() { }
	// RVA: 0x1cfa18c VA: 0x759431218c
	private Object <>xLuaBaseProxy_GetActMeta() { }
	// RVA: 0x1cfa194 VA: 0x7594312194
	private Void <>xLuaBaseProxy_FinishGame(Action`2 P0, GameResult P1, Boolean P2) { }
	// RVA: 0x1cfa1a0 VA: 0x75943121a0
	private PlayerBattleRank <>xLuaBaseProxy_GetBattleCompleteRank() { }
	// RVA: 0x1cfa1a8 VA: 0x75943121a8
	private Void <>xLuaBaseProxy_PostprocessMap(Map P0) { }
	// RVA: 0x1cfa1b0 VA: 0x75943121b0
	private Boolean <>xLuaBaseProxy_CheckRenderInvisible(Entity P0, BattleRenderInvisibleMask P1) { }
	// RVA: 0x1cfa1b8 VA: 0x75943121b8
	private Void <>xLuaBaseProxy_OnPostInit() { }
}
```