# DefaultGameMode

**Namespace:** ` `


## Fields

- `Boolean m_allowManualTick`

- `Character <draggingDummy>k__BackingField`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DefaultGameMode : IGameMode, IHotfixable
{
	private Boolean m_allowManualTick; // 0x10
	private Character <draggingDummy>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_allowManualTick; // 0x0
	private static DelegateBridge __Hotfix0_get_isOnline; // 0x8
	private static DelegateBridge __Hotfix0_get_isLargeMap; // 0x10
	private static DelegateBridge __Hotfix0_get_hasExtraBuildCondition; // 0x18
	private static DelegateBridge __Hotfix0_get_isSupportSlowMotion; // 0x20
	private static DelegateBridge __Hotfix0_get_doDefaultSchedule; // 0x28
	private static DelegateBridge __Hotfix0_get_useLevelBgm; // 0x30
	private static DelegateBridge __Hotfix0_get_isLowMemoryGameMode; // 0x38
	private static DelegateBridge __Hotfix0_get_outlineConfig; // 0x40
	private static DelegateBridge __Hotfix0_HookSeed; // 0x48
	private static DelegateBridge __Hotfix0_get_draggingDummy; // 0x50
	private static DelegateBridge __Hotfix0_set_draggingDummy; // 0x58
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x60
	private static DelegateBridge __Hotfix0_get_waveHandler; // 0x68
	private static DelegateBridge __Hotfix0_get_allowPoolManagerUnload; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x78
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x80
	private static DelegateBridge __Hotfix0_StartGame; // 0x88
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x90
	private static DelegateBridge __Hotfix0_Tick; // 0x98
	private static DelegateBridge __Hotfix0_GetCompleteProgress; // 0xa0
	private static DelegateBridge __Hotfix0_HookPlayerOp_Withdraw; // 0xa8
	private static DelegateBridge __Hotfix0_HookPlayerOp_Spawn; // 0xb0
	private static DelegateBridge __Hotfix0_HookPlayerOp_TrigSkill; // 0xb8
	private static DelegateBridge __Hotfix0_IsHasCharacterTile; // 0xc0
	private static DelegateBridge __Hotfix0_get_HookGetNextWave; // 0xc8
	private static DelegateBridge __Hotfix0_Hook_MapGetTileFromScreenPos; // 0xd0
	private static DelegateBridge __Hotfix0_IsHook_MapGetTileFromScreenPos; // 0xd8
	private static DelegateBridge __Hotfix0_PostprocessLevelOptions; // 0xe0
	private static DelegateBridge __Hotfix0_PreprocessLevelData; // 0xe8
	private static DelegateBridge __Hotfix0_PreprocessRuneInput; // 0xf0
	private static DelegateBridge __Hotfix0_PreprocessRuneData; // 0xf8
	private static DelegateBridge __Hotfix0_PostprocessRuneExtraData; // 0x100
	private static DelegateBridge __Hotfix0_PostprocessMap; // 0x108
	private static DelegateBridge __Hotfix0_PreprocessPlayerData; // 0x110
	private static DelegateBridge __Hotfix0_PreprocessPlayerDeckList; // 0x118
	private static DelegateBridge __Hotfix0_PreprocessCharacterCard; // 0x120
	private static DelegateBridge __Hotfix0_PreProcessDeckCards; // 0x128
	private static DelegateBridge __Hotfix0_SortDeck; // 0x130
	private static DelegateBridge __Hotfix0_PreprocessEnemy; // 0x138
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x140
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0x148
	private static DelegateBridge __Hotfix0_ParseBattleEvents; // 0x150
	private static DelegateBridge __Hotfix0_GameNotFinishCondition; // 0x158
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x160
	private static DelegateBridge __Hotfix0_IsSkillClickable; // 0x168
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x170
	private static DelegateBridge __Hotfix0_PreprocessLevelWithScheduler; // 0x178
	private static DelegateBridge __Hotfix0_GatherGlobalBuffs; // 0x180
	private static DelegateBridge __Hotfix0_NeedPreprocessPredefinedCharacter; // 0x188
	private static DelegateBridge __Hotfix0_HookSpeedLevel; // 0x190
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x198
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x1a0
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x1a8
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x1b0
	private static DelegateBridge __Hotfix0_CheckTileValid; // 0x1b8
	private static DelegateBridge __Hotfix0_HookTileEffect; // 0x1c0
	private static DelegateBridge __Hotfix0_GetModeTileEffect; // 0x1c8
	private static DelegateBridge __Hotfix0_HookTileAppendInfoKey; // 0x1d0
	private static DelegateBridge __Hotfix0_CheckCardReadyToSpawn; // 0x1d8
	private static DelegateBridge __Hotfix0_OnCardRecycle; // 0x1e0
	private static DelegateBridge __Hotfix0_OnCardSpawned; // 0x1e8
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x1f0
	private static DelegateBridge __Hotfix0_HookBattleFinishAudio; // 0x1f8
	private static DelegateBridge __Hotfix0_HookPlayAudioSignal; // 0x200
	private static DelegateBridge __Hotfix0_HookEnemyReachedExitAudio; // 0x208
	private static DelegateBridge __Hotfix0_EnableGlobalBuffExtraData; // 0x210
	private static DelegateBridge __Hotfix0_TryHookCheckWaveNotFinish; // 0x218
	private static DelegateBridge __Hotfix0_OnSpawnSummonedEnemy; // 0x220
	private static DelegateBridge __Hotfix0_OnSpawnSummonedEnemyFinished; // 0x228
	private static DelegateBridge __Hotfix0_CheckRenderInvisible; // 0x230
	private static DelegateBridge __Hotfix0_FinalSchedule; // 0x238
	private static DelegateBridge __Hotfix0_FinishGame; // 0x240
	private static DelegateBridge __Hotfix0_GetActMeta; // 0x248
	private static DelegateBridge __Hotfix0_GetBattleCompleteRank; // 0x250
	private static DelegateBridge __Hotfix0_TryGetNextWaveIndexInGameMode; // 0x258
	private static DelegateBridge __Hotfix0_OnDummyTouchedToTile; // 0x260
	private static DelegateBridge __Hotfix0_Hook_OnDummyDragging; // 0x268
	private static DelegateBridge __Hotfix0_OnDummySetBodyAndFaceDirection; // 0x270
	private static DelegateBridge __Hotfix0_DestroyEntity; // 0x278
	private static DelegateBridge __Hotfix0_OnPlayerLifeToZero; // 0x280
	private static DelegateBridge __Hotfix0_OnEnemyReachExit; // 0x288
	private static DelegateBridge __Hotfix0_TryShowTileInfoToast; // 0x290
	private static DelegateBridge __Hotfix0_OnCharacterRespawnFailed; // 0x298
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x2a0
	private static DelegateBridge __Hotfix0_IsMultiplayerLocal; // 0x2a8
	private static DelegateBridge __Hotfix0_CheckUnitValidHudPlugin; // 0x2b0
	private static DelegateBridge __Hotfix0_GatherEnvSystems; // 0x2b8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x2c0

	public virtual Boolean allowManualTick { get; }
	public virtual Boolean isOnline { get; }
	public virtual Boolean isLargeMap { get; }
	public virtual Boolean hasExtraBuildCondition { get; }
	public virtual Boolean isSupportSlowMotion { get; }
	public virtual Boolean doDefaultSchedule { get; }
	public virtual Boolean useLevelBgm { get; }
	public virtual Boolean isLowMemoryGameMode { get; }
	public virtual BattleOutlineConfig outlineConfig { get; }
	public virtual Character draggingDummy { get; set; }
	public virtual GameModeType gameModeType { get; }
	public virtual DefaultWaveHandler waveHandler { get; }
	public virtual Boolean allowPoolManagerUnload { get; }
	public virtual Boolean HookGetNextWave { get; }

	// RVA: 0x1cde8ac VA: 0x75942f68ac
	public virtual Boolean get_allowManualTick() { }
	// RVA: 0x1cde914 VA: 0x75942f6914
	public virtual Boolean get_isOnline() { }
	// RVA: 0x1cde978 VA: 0x75942f6978
	public virtual Boolean get_isLargeMap() { }
	// RVA: 0x1cde9dc VA: 0x75942f69dc
	public virtual Boolean get_hasExtraBuildCondition() { }
	// RVA: 0x1cdea40 VA: 0x75942f6a40
	public virtual Boolean get_isSupportSlowMotion() { }
	// RVA: 0x1cdeaa8 VA: 0x75942f6aa8
	public virtual Boolean get_doDefaultSchedule() { }
	// RVA: 0x1cdeb10 VA: 0x75942f6b10
	public virtual Boolean get_useLevelBgm() { }
	// RVA: 0x1cdeb78 VA: 0x75942f6b78
	public virtual Boolean get_isLowMemoryGameMode() { }
	// RVA: 0x1cdebdc VA: 0x75942f6bdc
	public virtual BattleOutlineConfig get_outlineConfig() { }
	// RVA: 0x1cdec9c VA: 0x75942f6c9c
	public virtual Boolean HookSeed(out Int32 seed) { }
	// RVA: 0x1cded18 VA: 0x75942f6d18
	public virtual Character get_draggingDummy() { }
	// RVA: 0x1cded80 VA: 0x75942f6d80
	public virtual Void set_draggingDummy(Character value) { }
	// RVA: 0x1cda404 VA: 0x75942f2404
	public virtual GameModeType get_gameModeType() { }
	// RVA: 0x1cde814 VA: 0x75942f6814
	public virtual DefaultWaveHandler get_waveHandler() { }
	// RVA: 0x1cdee04 VA: 0x75942f6e04
	public virtual Boolean get_allowPoolManagerUnload() { }
	// RVA: 0x1cda46c VA: 0x75942f246c
	public virtual Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cdee68 VA: 0x75942f6e68
	public virtual Void OnPostInit() { }
	// RVA: 0x1cdeecc VA: 0x75942f6ecc
	public virtual Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1cdef58 VA: 0x75942f6f58
	public virtual Void OnGameOver(ref GameResult result) { }
	// RVA: 0x1cda50c VA: 0x75942f250c
	public virtual Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cdefd0 VA: 0x75942f6fd0
	public virtual Single GetCompleteProgress() { }
	// RVA: 0x1cdf098 VA: 0x75942f7098
	public virtual Boolean HookPlayerOp_Withdraw(Character character) { }
	// RVA: 0x1cdf110 VA: 0x75942f7110
	public virtual Boolean HookPlayerOp_Spawn(UInt32 uniqueId, Direction direction, Tile tile) { }
	// RVA: 0x1cdf1a4 VA: 0x75942f71a4
	public virtual Boolean HookPlayerOp_TrigSkill(Character character) { }
	// RVA: 0x1cdf21c VA: 0x75942f721c
	public virtual Boolean IsHasCharacterTile(Tile tile) { }
	// RVA: 0x1cdf318 VA: 0x75942f7318
	public virtual Boolean get_HookGetNextWave() { }
	// RVA: 0x1cdf37c VA: 0x75942f737c
	public virtual Tile Hook_MapGetTileFromScreenPos(Vector2 screenPos, out Vector2 mapPos) { }
	// RVA: 0x1cdf44c VA: 0x75942f744c
	public virtual Boolean IsHook_MapGetTileFromScreenPos() { }
	// RVA: 0x1cdf4b0 VA: 0x75942f74b0
	public virtual Options PostprocessLevelOptions(Options options) { }
	// RVA: 0x1cdf52c VA: 0x75942f752c
	public virtual Void PreprocessLevelData(LevelData levelData) { }
	// RVA: 0x1cdf5a4 VA: 0x75942f75a4
	public virtual Void PreprocessRuneInput(IRuneDataHolder runeInput) { }
	// RVA: 0x1cdf61c VA: 0x75942f761c
	public virtual Void PreprocessRuneData(RuneManager manager) { }
	// RVA: 0x1cdf694 VA: 0x75942f7694
	public virtual Void PostprocessRuneExtraData(RuneLevelExtraOutput extraData) { }
	// RVA: 0x1cdf70c VA: 0x75942f770c
	public virtual Void PostprocessMap(Map map) { }
	// RVA: 0x1cdf784 VA: 0x75942f7784
	public virtual Void PreprocessPlayerData(List`1 dataList) { }
	// RVA: 0x1cdf7fc VA: 0x75942f77fc
	public virtual Void PreprocessPlayerDeckList(ListDict`2 deckList) { }
	// RVA: 0x1cdf874 VA: 0x75942f7874
	public virtual Void PreprocessCharacterCard(BattleCharacterData data, Character character) { }
	// RVA: 0x1cdf8f4 VA: 0x75942f78f4
	public virtual Void PreProcessDeckCards(IList`1 cards) { }
	// RVA: 0x1cdf96c VA: 0x75942f796c
	public virtual Void SortDeck(Card[] cards) { }
	// RVA: 0x1cdfab0 VA: 0x75942f7ab0
	public virtual Void PreprocessEnemy(EnemyData data) { }
	// RVA: 0x1cde594 VA: 0x75942f6594
	public virtual Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cdfb28 VA: 0x75942f7b28
	public virtual Void OnWaveWillFinish(WaveData waveData) { }
	// RVA: 0x1cdfba0 VA: 0x75942f7ba0
	public virtual Void ParseBattleEvents(ActionData data) { }
	// RVA: 0x1cdfc18 VA: 0x75942f7c18
	public virtual Boolean GameNotFinishCondition() { }
	// RVA: 0x1cdfc7c VA: 0x75942f7c7c
	public virtual Boolean CheckBuildable(BuildCondition buildCondition, Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1cdfd58 VA: 0x75942f7d58
	public virtual Boolean IsSkillClickable() { }
	// RVA: 0x1cda5b4 VA: 0x75942f25b4
	public virtual SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cdfdc0 VA: 0x75942f7dc0
	public virtual Void PreprocessLevelWithScheduler(LevelData levelData) { }
	// RVA: 0x1cde3ac VA: 0x75942f63ac
	public virtual List`1 GatherGlobalBuffs() { }
	// RVA: 0x1cdfe38 VA: 0x75942f7e38
	public virtual Boolean NeedPreprocessPredefinedCharacter() { }
	// RVA: 0x1cdfe9c VA: 0x75942f7e9c
	public virtual SpeedLevel HookSpeedLevel(SpeedLevel originSpeedLevel) { }
	// RVA: 0x1cde498 VA: 0x75942f6498
	public virtual Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cdba88 VA: 0x75942f3a88
	public virtual Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cdff18 VA: 0x75942f7f18
	public virtual Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cdff98 VA: 0x75942f7f98
	public virtual Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1ce0018 VA: 0x75942f8018
	public virtual Boolean CheckTileValid(Int32 row, Int32 col) { }
	// RVA: 0x1cde514 VA: 0x75942f6514
	public virtual String HookTileEffect(String originEffectKey) { }
	// RVA: 0x1ce009c VA: 0x75942f809c
	public virtual String GetModeTileEffect(Tile tile) { }
	// RVA: 0x1ce0134 VA: 0x75942f8134
	public virtual String HookTileAppendInfoKey(String originTileKey) { }
	// RVA: 0x1cdc5ac VA: 0x75942f45ac
	public virtual Boolean CheckCardReadyToSpawn(Card card) { }
	// RVA: 0x1ce01b0 VA: 0x75942f81b0
	public virtual Void OnCardRecycle(Card card) { }
	// RVA: 0x1ce0228 VA: 0x75942f8228
	public virtual Void OnCardSpawned(Card card) { }
	// RVA: 0x1ce02a0 VA: 0x75942f82a0
	public virtual Void OnCardListChanged(Card card) { }
	// RVA: 0x1cde790 VA: 0x75942f6790
	public virtual Boolean HookBattleFinishAudio(GameResult result) { }
	// RVA: 0x1ce0318 VA: 0x75942f8318
	public virtual Boolean HookPlayAudioSignal(String ev, Unit unit, Boolean ignorePredefined) { }
	// RVA: 0x1ce03ac VA: 0x75942f83ac
	public virtual Boolean HookEnemyReachedExitAudio() { }
	// RVA: 0x1ce0410 VA: 0x75942f8410
	public virtual Boolean EnableGlobalBuffExtraData(GlobalBuff buff, GlobalBuffData data) { }
	// RVA: 0x1ce049c VA: 0x75942f849c
	public virtual Boolean TryHookCheckWaveNotFinish(Boolean schedulerResult, out Boolean result) { }
	// RVA: 0x1ce0524 VA: 0x75942f8524
	public virtual Void OnSpawnSummonedEnemy() { }
	// RVA: 0x1ce0588 VA: 0x75942f8588
	public virtual Void OnSpawnSummonedEnemyFinished() { }
	// RVA: 0x1ce05ec VA: 0x75942f85ec
	public virtual Boolean CheckRenderInvisible(Entity entity, BattleRenderInvisibleMask mask) { }
	// RVA: 0x1ce0670 VA: 0x75942f8670
	public virtual IEnumerator FinalSchedule() { }
	// RVA: 0x1cdc334 VA: 0x75942f4334
	public virtual Void FinishGame(Action`2 gameFinishCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1ce0734 VA: 0x75942f8734
	public virtual Object GetActMeta() { }
	// RVA: 0x1cde618 VA: 0x75942f6618
	public virtual PlayerBattleRank GetBattleCompleteRank() { }
	// RVA: 0x1ce0798 VA: 0x75942f8798
	public virtual Boolean TryGetNextWaveIndexInGameMode(out Int32 index) { }
	// RVA: 0x1ce0818 VA: 0x75942f8818
	public virtual Void OnDummyTouchedToTile(Character character, Tile tile, Vector3 dummyPos) { }
	// RVA: 0x1ce08c8 VA: 0x75942f88c8
	public virtual Boolean Hook_OnDummyDragging() { }
	// RVA: 0x1ce092c VA: 0x75942f892c
	public virtual Void OnDummySetBodyAndFaceDirection(Character character, Direction direction) { }
	// RVA: 0x1cdcb84 VA: 0x75942f4b84
	public virtual Void DestroyEntity(Entity entity, FinishReason reason) { }
	// RVA: 0x1ce09ac VA: 0x75942f89ac
	public virtual Void OnPlayerLifeToZero(PlayerSide side) { }
	// RVA: 0x1ce0a58 VA: 0x75942f8a58
	public virtual Void OnEnemyReachExit(Enemy enemy, Tile cacheTile) { }
	// RVA: 0x1ce0b28 VA: 0x75942f8b28
	public virtual Boolean TryShowTileInfoToast(Tile tile, out Int32 id) { }
	// RVA: 0x1ce0bb0 VA: 0x75942f8bb0
	public virtual Void OnCharacterRespawnFailed(Character character, Card card, PlayerSide playerSide) { }
	// RVA: 0x1ce0c90 VA: 0x75942f8c90
	public virtual Void OnDestroy() { }
	// RVA: 0x1ce0cf4 VA: 0x75942f8cf4
	public virtual Boolean IsMultiplayerLocal() { }
	// RVA: 0x1cde418 VA: 0x75942f6418
	public virtual Boolean CheckUnitValidHudPlugin(Unit unit) { }
	// RVA: 0x1cde344 VA: 0x75942f6344
	public virtual List`1 GatherEnvSystems() { }
	// RVA: 0x1cd85ec VA: 0x75942f05ec
	public Void .ctor(ref GameModeMeta meta) { }
}
```