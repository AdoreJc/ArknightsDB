# GameCityGameMode

**Namespace:** ` `


## Fields

- `FP m_score`

- `Int32 m_curWave`

- `Int32 m_maxWave`

- `Int32 m_curArcgachaStartCnt`

- `String m_actId`

- `String m_levelId`

- `Rank m_curRank`

- `GameCityInput m_input`

- `SubModeType m_subMode`

- `Int32 m_rainbowScore`

- `FP m_waveDuration`

- `FP m_restDuration`

- `Boolean m_skipCurWave`

- `PeriodicTimer m_restingTimer`

- `PeriodicTimer m_waveTimer`

- `GamecityBattleUIPlugin m_plugin`


## Properties

- `SubModeType SubModeType`

- `Int32 maxWave`

- `Int32 curWave`

- `Boolean isResting`

- `Boolean skipCurWave`

- `FP waveRestTime`

- `FP waveRestTimeProgress`

- `FP restingTime`

- `Rank curRank`

- `String actId`

- `Int32 rainbowScore`


## Methods

- `SubModeType get_SubModeType()`

- `Int32 get_maxWave()`

- `Int32 get_curWave()`

- `Boolean get_isResting()`

- `Boolean get_skipCurWave()`

- `Void set_skipCurWave(Boolean)`

- `FP get_waveRestTime()`

- `FP get_waveRestTimeProgress()`

- `FP get_restingTime()`

- `Rank get_curRank()`

- `String get_actId()`

- `Int32 get_rainbowScore()`

- `Void set_rainbowScore(Int32)`

- `Void SetWaveAndRestTime(FP, FP)`

- `Single GetScoreMaxValue(Rank)`

- `Void AddArcgachaObjects(List`1)`

- `Void AddArcgachaObjectsStart(List`1)`

- `String RandomGetArcgachaObject()`

- `Void MarkBranch(String, BranchData)`

- `Void AddScore(FP, Entity)`

- `Void GetTileScoreAdd(FP)`

- `Void FinishCurWaveBecauseTimeUp()`

- `Void SetRestingTimerOnWaveFinish()`

- `Void SetWaveTimerOnWaveStart(FP)`

- `Void UpdateRestingTimer(FP)`

- `Void UpdateWaveTimer(FP)`

- `Void _ParseMinerGlobalBuffs()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Boolean <>xLuaBaseProxy_CheckUnitValidHudPlugin(Unit)`

- `Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref)`

- `String <>xLuaBaseProxy_HookTileEffect(String)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_FinishGame(Action`2, GameResult, Boolean)`

- `PlayerBattleRank <>xLuaBaseProxy_GetBattleCompleteRank()`

- `Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card)`

- `Boolean <>xLuaBaseProxy_HookBattleFinishAudio(GameResult)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Void <>xLuaBaseProxy_DestroyEntity(Entity, FinishReason)`

- `DefaultWaveHandler <>xLuaBaseProxy_get_waveHandler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameCityGameMode : DefaultGameMode
{
	public const String BATTLE_UI_PLUGIN_PATH; // 0x0
	public const String STAGE_LEVEL_FORMAT; // 0x0
	private FP m_score; // 0x20
	private Int32 m_curWave; // 0x28
	private Int32 m_maxWave; // 0x2c
	private Int32 m_curArcgachaStartCnt; // 0x30
	private String m_actId; // 0x38
	private String m_levelId; // 0x40
	private Rank m_curRank; // 0x48
	private GameCityInput m_input; // 0x50
	private SubModeType m_subMode; // 0x58
	private Int32 m_rainbowScore; // 0x5c
	private FP m_waveDuration; // 0x60
	private FP m_restDuration; // 0x68
	private Boolean m_skipCurWave; // 0x70
	private List`1 m_arcgachaObjectStart; // 0x78
	private List`1 m_arcgachaObject; // 0x80
	private List`1 m_extraLevelRunes; // 0x88
	private List`1 m_branchMarked; // 0x90
	private List`1 m_branchRoutes; // 0x98
	private List`1 m_enemyHudScoreIds; // 0xa0
	private List`1 m_trapNotBuildableInRestIds; // 0xa8
	private Dictionary`2 m_rankData; // 0xb0
	private PeriodicTimer m_restingTimer; // 0xb8
	private PeriodicTimer m_waveTimer; // 0xc0
	private Dictionary`2 m_antiCheatScore; // 0xc8
	private GamecityBattleUIPlugin m_plugin; // 0xd0
	private readonly List`1 m_globalBuffs; // 0xd8
	private readonly List`1 m_globalEnvSystem; // 0xe0
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_GatherEnvSystems; // 0x20
	private static DelegateBridge __Hotfix0_GatherGlobalBuffs; // 0x28
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x30
	private static DelegateBridge __Hotfix0_CheckUnitValidHudPlugin; // 0x38
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x40
	private static DelegateBridge __Hotfix0_HookTileEffect; // 0x48
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x50
	private static DelegateBridge __Hotfix0_FinishGame; // 0x58
	private static DelegateBridge __Hotfix0_GetBattleCompleteRank; // 0x60
	private static DelegateBridge __Hotfix0_CheckCardReadyToSpawn; // 0x68
	private static DelegateBridge __Hotfix0_HookBattleFinishAudio; // 0x70
	private static DelegateBridge __Hotfix0_Tick; // 0x78
	private static DelegateBridge __Hotfix0_DestroyEntity; // 0x80
	private static DelegateBridge __Hotfix0_get_SubModeType; // 0x88
	private static DelegateBridge __Hotfix0_get_maxWave; // 0x90
	private static DelegateBridge __Hotfix0_get_curWave; // 0x98
	private static DelegateBridge __Hotfix0_get_isResting; // 0xa0
	private static DelegateBridge __Hotfix0_get_skipCurWave; // 0xa8
	private static DelegateBridge __Hotfix0_set_skipCurWave; // 0xb0
	private static DelegateBridge __Hotfix0_get_waveRestTime; // 0xb8
	private static DelegateBridge __Hotfix0_get_waveRestTimeProgress; // 0xc0
	private static DelegateBridge __Hotfix0_get_restingTime; // 0xc8
	private static DelegateBridge __Hotfix0_get_curRank; // 0xd0
	private static DelegateBridge __Hotfix0_get_actId; // 0xd8
	private static DelegateBridge __Hotfix0_get_rainbowScore; // 0xe0
	private static DelegateBridge __Hotfix0_set_rainbowScore; // 0xe8
	private static DelegateBridge __Hotfix0_SetWaveAndRestTime; // 0xf0
	private static DelegateBridge __Hotfix0_GetScoreMaxValue; // 0xf8
	private static DelegateBridge __Hotfix0_AddArcgachaObjects; // 0x100
	private static DelegateBridge __Hotfix0_AddArcgachaObjectsStart; // 0x108
	private static DelegateBridge __Hotfix0_RandomGetArcgachaObject; // 0x110
	private static DelegateBridge __Hotfix0_MarkBranch; // 0x118
	private static DelegateBridge __Hotfix0_AddScore; // 0x120
	private static DelegateBridge __Hotfix0_GetTileScoreAdd; // 0x128
	private static DelegateBridge __Hotfix0_FinishCurWaveBecauseTimeUp; // 0x130
	private static DelegateBridge __Hotfix0_SetRestingTimerOnWaveFinish; // 0x138
	private static DelegateBridge __Hotfix0_SetWaveTimerOnWaveStart; // 0x140
	private static DelegateBridge __Hotfix0_UpdateRestingTimer; // 0x148
	private static DelegateBridge __Hotfix0_UpdateWaveTimer; // 0x150
	private static DelegateBridge __Hotfix0__ParseMinerGlobalBuffs; // 0x158
	private static DelegateBridge __Hotfix0_get_waveHandler; // 0x160

	public override GameModeType gameModeType { get; }
	public SubModeType SubModeType { get; }
	public Int32 maxWave { get; }
	public Int32 curWave { get; }
	public Boolean isResting { get; }
	public Boolean skipCurWave { get; set; }
	public FP waveRestTime { get; }
	public FP waveRestTimeProgress { get; }
	public FP restingTime { get; }
	public Rank curRank { get; }
	public String actId { get; }
	public Int32 rainbowScore { get; set; }
	public override DefaultWaveHandler waveHandler { get; }

	// RVA: 0x1cda64c VA: 0x75942f264c
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cda6b4 VA: 0x75942f26b4
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cdab00 VA: 0x75942f2b00
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cdab98 VA: 0x75942f2b98
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cdb2e8 VA: 0x75942f32e8
	public override List`1 GatherEnvSystems() { }
	// RVA: 0x1cdb4a0 VA: 0x75942f34a0
	public override List`1 GatherGlobalBuffs() { }
	// RVA: 0x1cdb8a0 VA: 0x75942f38a0
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cdbb00 VA: 0x75942f3b00
	public override Boolean CheckUnitValidHudPlugin(Unit unit) { }
	// RVA: 0x1cdbc4c VA: 0x75942f3c4c
	public override Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cdbd28 VA: 0x75942f3d28
	public override String HookTileEffect(String originEffectKey) { }
	// RVA: 0x1cdbdec VA: 0x75942f3dec
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cdc068 VA: 0x75942f4068
	public override Void FinishGame(Action`2 gameFinishCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1cdc3ec VA: 0x75942f43ec
	public override PlayerBattleRank GetBattleCompleteRank() { }
	// RVA: 0x1cdc454 VA: 0x75942f4454
	public override Boolean CheckCardReadyToSpawn(Card card) { }
	// RVA: 0x1cdc68c VA: 0x75942f468c
	public override Boolean HookBattleFinishAudio(GameResult result) { }
	// RVA: 0x1cdc768 VA: 0x75942f4768
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cdc9c8 VA: 0x75942f49c8
	public override Void DestroyEntity(Entity entity, FinishReason reason) { }
	// RVA: 0x1cdcc68 VA: 0x75942f4c68
	public SubModeType get_SubModeType() { }
	// RVA: 0x1cdccd0 VA: 0x75942f4cd0
	public Int32 get_maxWave() { }
	// RVA: 0x1cdcd38 VA: 0x75942f4d38
	public Int32 get_curWave() { }
	// RVA: 0x1cdc538 VA: 0x75942f4538
	public Boolean get_isResting() { }
	// RVA: 0x1cdcb1c VA: 0x75942f4b1c
	public Boolean get_skipCurWave() { }
	// RVA: 0x1cdbf1c VA: 0x75942f3f1c
	public Void set_skipCurWave(Boolean value) { }
	// RVA: 0x1cdcda0 VA: 0x75942f4da0
	public FP get_waveRestTime() { }
	// RVA: 0x1cdce60 VA: 0x75942f4e60
	public FP get_waveRestTimeProgress() { }
	// RVA: 0x1cdcf20 VA: 0x75942f4f20
	public FP get_restingTime() { }
	// RVA: 0x1cdcfe0 VA: 0x75942f4fe0
	public Rank get_curRank() { }
	// RVA: 0x1cdd048 VA: 0x75942f5048
	public String get_actId() { }
	// RVA: 0x1cdd0b0 VA: 0x75942f50b0
	public Int32 get_rainbowScore() { }
	// RVA: 0x1cdd118 VA: 0x75942f5118
	public Void set_rainbowScore(Int32 value) { }
	// RVA: 0x1cdd194 VA: 0x75942f5194
	public Void SetWaveAndRestTime(FP wave, FP rest) { }
	// RVA: 0x1cdd218 VA: 0x75942f5218
	public Single GetScoreMaxValue(Rank rank) { }
	// RVA: 0x1cdd2b8 VA: 0x75942f52b8
	public Void AddArcgachaObjects(List`1 data) { }
	// RVA: 0x1cdd390 VA: 0x75942f5390
	public Void AddArcgachaObjectsStart(List`1 data) { }
	// RVA: 0x1cdd468 VA: 0x75942f5468
	public String RandomGetArcgachaObject() { }
	// RVA: 0x1cdd61c VA: 0x75942f561c
	public Void MarkBranch(String dataKey, BranchData data) { }
	// RVA: 0x1cdd808 VA: 0x75942f5808
	public Void AddScore(FP value, Entity target) { }
	// RVA: 0x1cddcdc VA: 0x75942f5cdc
	public Void GetTileScoreAdd(FP value) { }
	// RVA: 0x1cddeb4 VA: 0x75942f5eb4
	public Void FinishCurWaveBecauseTimeUp() { }
	// RVA: 0x1cde1f4 VA: 0x75942f61f4
	public Void SetRestingTimerOnWaveFinish() { }
	// RVA: 0x1cdbfd8 VA: 0x75942f3fd8
	public Void SetWaveTimerOnWaveStart(FP restTime) { }
	// RVA: 0x1cdc830 VA: 0x75942f4830
	public Void UpdateRestingTimer(FP deltaTime) { }
	// RVA: 0x1cdc8f8 VA: 0x75942f48f8
	public Void UpdateWaveTimer(FP deltaTime) { }
	// RVA: 0x1cdb554 VA: 0x75942f3554
	private Void _ParseMinerGlobalBuffs() { }
	// RVA: 0x1cde29c VA: 0x75942f629c
	public override DefaultWaveHandler get_waveHandler() { }
	// RVA: 0x1cde334 VA: 0x75942f6334
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cde338 VA: 0x75942f6338
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cde33c VA: 0x75942f633c
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cde340 VA: 0x75942f6340
	private List`1 <>xLuaBaseProxy_GatherEnvSystems() { }
	// RVA: 0x1cde3a8 VA: 0x75942f63a8
	private List`1 <>xLuaBaseProxy_GatherGlobalBuffs() { }
	// RVA: 0x1cde410 VA: 0x75942f6410
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1cde414 VA: 0x75942f6414
	private Boolean <>xLuaBaseProxy_CheckUnitValidHudPlugin(Unit P0) { }
	// RVA: 0x1cde494 VA: 0x75942f6494
	private Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref Modifier P0) { }
	// RVA: 0x1cde510 VA: 0x75942f6510
	private String <>xLuaBaseProxy_HookTileEffect(String P0) { }
	// RVA: 0x1cde590 VA: 0x75942f6590
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cde60c VA: 0x75942f660c
	private Void <>xLuaBaseProxy_FinishGame(Action`2 P0, GameResult P1, Boolean P2) { }
	// RVA: 0x1cde614 VA: 0x75942f6614
	private PlayerBattleRank <>xLuaBaseProxy_GetBattleCompleteRank() { }
	// RVA: 0x1cde788 VA: 0x75942f6788
	private Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card P0) { }
	// RVA: 0x1cde78c VA: 0x75942f678c
	private Boolean <>xLuaBaseProxy_HookBattleFinishAudio(GameResult P0) { }
	// RVA: 0x1cde808 VA: 0x75942f6808
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cde80c VA: 0x75942f680c
	private Void <>xLuaBaseProxy_DestroyEntity(Entity P0, FinishReason P1) { }
	// RVA: 0x1cde810 VA: 0x75942f6810
	private DefaultWaveHandler <>xLuaBaseProxy_get_waveHandler() { }
}
```