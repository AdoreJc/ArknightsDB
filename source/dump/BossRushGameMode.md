# BossRushGameMode

**Namespace:** ` `


## Fields

- `Int32 currBossWaveCnt`

- `Int32 prevBossWavesEnemiesCnt`

- `Int32 m_battleAreaBegin`

- `Int32 m_battleAreaEnd`

- `Int32 m_dangerAreaEnd`

- `Int32 m_currentWaveIndex`

- `Int32 m_activatedControllerCount`

- `BossRushSchedulerPreprocessor m_schedulerPreprocessor`

- `Int32 m_willSummonedEnemiesCount`

- `Boolean m_hasFinishedDangerArea`


## Properties

- `Int32 maxBossWaveCnt`

- `Int32 currBossWaveKillCnt`

- `Int32 currBossWaveTotalCnt`

- `Int32 battleAreaBegin`

- `Int32 battleAreaEnd`

- `Boolean hasFinishedDangerArea`


## Methods

- `Int32 get_maxBossWaveCnt()`

- `Int32 get_currBossWaveKillCnt()`

- `Int32 get_currBossWaveTotalCnt()`

- `Int32 get_battleAreaBegin()`

- `Int32 get_battleAreaEnd()`

- `Boolean get_hasFinishedDangerArea()`

- `Void set_hasFinishedDangerArea(Boolean)`

- `Void _OnInitNextBossWave()`

- `Void InitBossRushController(Entity)`

- `Void InitBossRushRecodr(Entity)`

- `Void ModifyBattleAreaData(Blackboard)`

- `Vector3 GetDangerAreaEffectPosition(Vector3)`

- `Vector3 GetBattleAreaBeginEffectPosition(Vector3)`

- `Vector3 GetBattleAreaEndEffectPosition(Vector3)`

- `Void OnBossWaveWillStart(Object)`

- `Boolean _CheckCanMoveToBonusWave()`

- `Boolean NextWaveIsBonusWave()`

- `Void TrackRecycleEnemyAtWave(Enemy, Int32)`

- `Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition()`

- `Boolean <>xLuaBaseProxy_get_isLargeMap()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData)`

- `Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition, Tile, Direction, Boolean, Boolean, BattleCharacterData, PlayerSide)`

- `Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean, out)`

- `Void <>xLuaBaseProxy_OnSpawnSummonedEnemy()`

- `Void <>xLuaBaseProxy_OnSpawnSummonedEnemyFinished()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BossRushGameMode : DefaultGameMode
{
	public readonly List`1 enemyCntStats; // 0x20
	public List`1 bossWaveCount; // 0x28
	public const String BOSSRUSH_BOSSWAVE_TAG; // 0x0
	public const String BOSSRUSH_BONUSWAVE_TAG; // 0x0
	public const String BOSSRUSH_UI_PLUGIN_PATH; // 0x0
	public const String BOSSRUSH_CAMERA_PLUGIN_PATH; // 0x0
	private const String BOSS_WAVE_FINISHED_LOG; // 0x0
	private const String WITHDRAW_ABILITY_KEY; // 0x0
	private const String DANGER_AREA_ABILITY_KEY; // 0x0
	private const String MOVE_CAMERA_ABILITY_KEY; // 0x0
	private const String DISABLE_RECODR_ABILITY_KEY; // 0x0
	public Int32 currBossWaveCnt; // 0x30
	public Int32 prevBossWavesEnemiesCnt; // 0x34
	private Int32 m_battleAreaBegin; // 0x38
	private Int32 m_battleAreaEnd; // 0x3c
	private Int32 m_dangerAreaEnd; // 0x40
	private Dictionary`2 m_cachedRecycleEnemies; // 0x48
	private Int32 m_currentWaveIndex; // 0x50
	private Int32 m_activatedControllerCount; // 0x54
	private BossRushSchedulerPreprocessor m_schedulerPreprocessor; // 0x58
	private ObjectPtr`1 m_bossRushCtroller; // 0x60
	private ObjectPtr`1 m_bossRushRecodr; // 0x70
	private Int32 m_willSummonedEnemiesCount; // 0x80
	private Boolean m_hasFinishedDangerArea; // 0x84
	private static DelegateBridge __Hotfix0_get_maxBossWaveCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_currBossWaveKillCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_currBossWaveTotalCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_waveDatas; // 0x18
	private static DelegateBridge __Hotfix0_get_battleAreaBegin; // 0x20
	private static DelegateBridge __Hotfix0_get_battleAreaEnd; // 0x28
	private static DelegateBridge __Hotfix0_get_hasExtraBuildCondition; // 0x30
	private static DelegateBridge __Hotfix0_get_isLargeMap; // 0x38
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0_get_hasFinishedDangerArea; // 0x50
	private static DelegateBridge __Hotfix0_set_hasFinishedDangerArea; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x60
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x68
	private static DelegateBridge __Hotfix0__OnInitNextBossWave; // 0x70
	private static DelegateBridge __Hotfix0_InitBossRushController; // 0x78
	private static DelegateBridge __Hotfix0_InitBossRushRecodr; // 0x80
	private static DelegateBridge __Hotfix0_ModifyBattleAreaData; // 0x88
	private static DelegateBridge __Hotfix0_GetDangerAreaEffectPosition; // 0x90
	private static DelegateBridge __Hotfix0_GetBattleAreaBeginEffectPosition; // 0x98
	private static DelegateBridge __Hotfix0_GetBattleAreaEndEffectPosition; // 0xa0
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0xa8
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0xb0
	private static DelegateBridge __Hotfix0_OnBossWaveWillStart; // 0xb8
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0xc0
	private static DelegateBridge __Hotfix0_TryHookCheckWaveNotFinish; // 0xc8
	private static DelegateBridge __Hotfix0__CheckCanMoveToBonusWave; // 0xd0
	private static DelegateBridge __Hotfix0_OnSpawnSummonedEnemy; // 0xd8
	private static DelegateBridge __Hotfix0_OnSpawnSummonedEnemyFinished; // 0xe0
	private static DelegateBridge __Hotfix0_NextWaveIsBonusWave; // 0xe8
	private static DelegateBridge __Hotfix0_TrackRecycleEnemyAtWave; // 0xf0

	public Int32 maxBossWaveCnt { get; }
	public Int32 currBossWaveKillCnt { get; }
	public Int32 currBossWaveTotalCnt { get; }
	public List`1 waveDatas { get; }
	public Int32 battleAreaBegin { get; }
	public Int32 battleAreaEnd { get; }
	public override Boolean hasExtraBuildCondition { get; }
	public override Boolean isLargeMap { get; }
	public override GameModeType gameModeType { get; }
	public Boolean hasFinishedDangerArea { get; set; }

	// RVA: 0x1cb6514 VA: 0x75942ce514
	public Int32 get_maxBossWaveCnt() { }
	// RVA: 0x1cb6594 VA: 0x75942ce594
	public Int32 get_currBossWaveKillCnt() { }
	// RVA: 0x1cb6638 VA: 0x75942ce638
	public Int32 get_currBossWaveTotalCnt() { }
	// RVA: 0x1cb66c8 VA: 0x75942ce6c8
	public List`1 get_waveDatas() { }
	// RVA: 0x1cb673c VA: 0x75942ce73c
	public Int32 get_battleAreaBegin() { }
	// RVA: 0x1cb67a4 VA: 0x75942ce7a4
	public Int32 get_battleAreaEnd() { }
	// RVA: 0x1cb680c VA: 0x75942ce80c
	public override Boolean get_hasExtraBuildCondition() { }
	// RVA: 0x1cb6874 VA: 0x75942ce874
	public override Boolean get_isLargeMap() { }
	// RVA: 0x1cb68dc VA: 0x75942ce8dc
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cb6944 VA: 0x75942ce944
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cb6ad4 VA: 0x75942cead4
	public Boolean get_hasFinishedDangerArea() { }
	// RVA: 0x1cb6b3c VA: 0x75942ceb3c
	public Void set_hasFinishedDangerArea(Boolean value) { }
	// RVA: 0x1cb6bbc VA: 0x75942cebbc
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cb6e00 VA: 0x75942cee00
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cb6d38 VA: 0x75942ced38
	private Void _OnInitNextBossWave() { }
	// RVA: 0x1cb6e68 VA: 0x75942cee68
	public Void InitBossRushController(Entity entity) { }
	// RVA: 0x1cb7030 VA: 0x75942cf030
	public Void InitBossRushRecodr(Entity entity) { }
	// RVA: 0x1cb70d8 VA: 0x75942cf0d8
	public Void ModifyBattleAreaData(Blackboard blackboard) { }
	// RVA: 0x1cb71e8 VA: 0x75942cf1e8
	public Vector3 GetDangerAreaEffectPosition(Vector3 trapLocalPosition) { }
	// RVA: 0x1cb72d4 VA: 0x75942cf2d4
	public Vector3 GetBattleAreaBeginEffectPosition(Vector3 trapLocalPosition) { }
	// RVA: 0x1cb73bc VA: 0x75942cf3bc
	public Vector3 GetBattleAreaEndEffectPosition(Vector3 trapLocalPosition) { }
	// RVA: 0x1cb74a8 VA: 0x75942cf4a8
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cb7b3c VA: 0x75942cfb3c
	public override Void OnWaveWillFinish(WaveData waveData) { }
	// RVA: 0x1cb7d94 VA: 0x75942cfd94
	public Void OnBossWaveWillStart(Object args) { }
	// RVA: 0x1cb7e98 VA: 0x75942cfe98
	public override Boolean CheckBuildable(BuildCondition buildCondition, Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1cb80a4 VA: 0x75942d00a4
	public override Boolean TryHookCheckWaveNotFinish(Boolean schedulerResult, out Boolean result) { }
	// RVA: 0x1cb8268 VA: 0x75942d0268
	private Boolean _CheckCanMoveToBonusWave() { }
	// RVA: 0x1cb83bc VA: 0x75942d03bc
	public override Void OnSpawnSummonedEnemy() { }
	// RVA: 0x1cb842c VA: 0x75942d042c
	public override Void OnSpawnSummonedEnemyFinished() { }
	// RVA: 0x1cb814c VA: 0x75942d014c
	public Boolean NextWaveIsBonusWave() { }
	// RVA: 0x1cb849c VA: 0x75942d049c
	public Void TrackRecycleEnemyAtWave(Enemy enemy, Int32 waveDelta) { }
	// RVA: 0x1cb868c VA: 0x75942d068c
	private Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition() { }
	// RVA: 0x1cb8694 VA: 0x75942d0694
	private Boolean <>xLuaBaseProxy_get_isLargeMap() { }
	// RVA: 0x1cb869c VA: 0x75942d069c
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cb86a4 VA: 0x75942d06a4
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cb86ac VA: 0x75942d06ac
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cb86b4 VA: 0x75942d06b4
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cb86bc VA: 0x75942d06bc
	private Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData P0) { }
	// RVA: 0x1cb86c4 VA: 0x75942d06c4
	private Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition P0, Tile P1, Direction P2, Boolean P3, Boolean P4, BattleCharacterData P5, PlayerSide P6) { }
	// RVA: 0x1cb8744 VA: 0x75942d0744
	private Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean P0, out Boolean P1) { }
	// RVA: 0x1cb8750 VA: 0x75942d0750
	private Void <>xLuaBaseProxy_OnSpawnSummonedEnemy() { }
	// RVA: 0x1cb8758 VA: 0x75942d0758
	private Void <>xLuaBaseProxy_OnSpawnSummonedEnemyFinished() { }
}
```