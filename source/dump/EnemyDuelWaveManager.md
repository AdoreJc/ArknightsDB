# EnemyDuelWaveManager

**Namespace:** ` `


## Fields

- `LevelData m_levelData`

- `Int32 m_maxRoundCnt`

- `Int32 m_hasGenerateRound`


## Methods

- `Void Init(LevelData, ActivityEnemyDuelData, ActivityEnemyDuelModeData)`

- `Int32 GenerateNextWaves(Int32)`

- `Int32 GetRemainingRoundCnt(Int32)`

- `ActivityEnemyDuelRoundData GetCurRoundData(Int32)`

- `Void _ProcessRoundData(ActivityEnemyDuelData, ActivityEnemyDuelModeData)`

- `Void _ProcessPoolData(ActivityEnemyDuelData, String)`

- `Single _GetWeightByPoolTypeString(EnemyDuelRoundPoolType, ActivityEnemyDuelPoolData)`

- `Void _ProcessEnemyData()`

- `WaveData _GenerateRound(Int32)`

- `Void _SelectEnemyForEachTeam(List`1, Dictionary`2, Int32, String)`

- `Boolean _AvailableEnemy(String)`

- `Int32 _GetActionCnt()`

- `Boolean _NeedRoute(ActionData)`

- `Void _TideRoute()`

- `WaveData _GenerateDefaultWave()`

- `Void _GenerateTeam(Single, String, List`1, Boolean, WaveData)`

- `Void _GenerateTeamWave(String, List`1, Boolean, WaveData)`

- `Void _GenerateActionForEnemy(String, Int32[], Single, Boolean, WaveData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyDuelWaveManager : IHotfixable
{
	private LevelData m_levelData; // 0x10
	private readonly Dictionary`2 m_allEnemyExtraData; // 0x18
	private readonly List`1 m_roundDataList; // 0x20
	private readonly Dictionary`2 m_poolDataDict; // 0x28
	private readonly Dictionary`2 m_startPos; // 0x30
	private Int32 m_maxRoundCnt; // 0x38
	private Int32 m_hasGenerateRound; // 0x3c
	private const Single ROUND_END_WAIT_TIME; // 0x0
	private const Single ENEMY_WAVE_INTERVAL; // 0x0
	private const Single MAX_ENEMY_COST; // 0x0
	private const Single MAX_WAIT_TIME; // 0x0
	private const Single MIN_LAST_ENEMY_PROB; // 0x0
	private const String TILE_START; // 0x0
	private const String TILE_END; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_GenerateNextWaves; // 0x8
	private static DelegateBridge __Hotfix0_GetRemainingRoundCnt; // 0x10
	private static DelegateBridge __Hotfix0_GetCurRoundData; // 0x18
	private static DelegateBridge __Hotfix0_GetRoundData; // 0x20
	private static DelegateBridge __Hotfix0__ProcessRoundData; // 0x28
	private static DelegateBridge __Hotfix0__ProcessPoolData; // 0x30
	private static DelegateBridge __Hotfix0__GetWeightByPoolTypeString; // 0x38
	private static DelegateBridge __Hotfix0__ProcessEnemyData; // 0x40
	private static DelegateBridge __Hotfix0__GenerateRound; // 0x48
	private static DelegateBridge __Hotfix0__SelectEnemyForEachTeam; // 0x50
	private static DelegateBridge __Hotfix0__AvailableEnemy; // 0x58
	private static DelegateBridge __Hotfix0__GetActionCnt; // 0x60
	private static DelegateBridge __Hotfix0__NeedRoute; // 0x68
	private static DelegateBridge __Hotfix0__TideRoute; // 0x70
	private static DelegateBridge __Hotfix0__GenerateDefaultWave; // 0x78
	private static DelegateBridge __Hotfix0__GenerateTeam; // 0x80
	private static DelegateBridge __Hotfix0__GenerateTeamWave; // 0x88
	private static DelegateBridge __Hotfix0__FindSpawnPositions; // 0x90
	private static DelegateBridge __Hotfix0__GenerateActionForEnemy; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x1cd4760 VA: 0x75942ec760
	public Void Init(LevelData levelData, ActivityEnemyDuelData actData, ActivityEnemyDuelModeData modeData) { }
	// RVA: 0x1cd5528 VA: 0x75942ed528
	public Int32 GenerateNextWaves(Int32 roundIndex) { }
	// RVA: 0x1cd57ec VA: 0x75942ed7ec
	public Int32 GetRemainingRoundCnt(Int32 roundIndex) { }
	// RVA: 0x1cd586c VA: 0x75942ed86c
	public ActivityEnemyDuelRoundData GetCurRoundData(Int32 roundIndex) { }
	// RVA: 0x1cd592c VA: 0x75942ed92c
	public List`1 GetRoundData() { }
	// RVA: 0x1cd49f4 VA: 0x75942ec9f4
	private Void _ProcessRoundData(ActivityEnemyDuelData actData, ActivityEnemyDuelModeData modeData) { }
	// RVA: 0x1cd5994 VA: 0x75942ed994
	private Void _ProcessPoolData(ActivityEnemyDuelData actData, String poolKey) { }
	// RVA: 0x1cd5dac VA: 0x75942eddac
	private Single _GetWeightByPoolTypeString(EnemyDuelRoundPoolType poolType, ActivityEnemyDuelPoolData poolData) { }
	// RVA: 0x1cd4d80 VA: 0x75942ecd80
	private Void _ProcessEnemyData() { }
	// RVA: 0x1cd4f80 VA: 0x75942ecf80
	private WaveData _GenerateRound(Int32 round) { }
	// RVA: 0x1cd5e68 VA: 0x75942ede68
	private Void _SelectEnemyForEachTeam(List`1 selected, Dictionary`2 enemyForTheRound, Int32 typeCnt, String enemyPoolKey) { }
	// RVA: 0x1cd6734 VA: 0x75942ee734
	private Boolean _AvailableEnemy(String enemyId) { }
	// RVA: 0x1cd6804 VA: 0x75942ee804
	private Int32 _GetActionCnt() { }
	// RVA: 0x1cd68f0 VA: 0x75942ee8f0
	private Boolean _NeedRoute(ActionData action) { }
	// RVA: 0x1cd529c VA: 0x75942ed29c
	private Void _TideRoute() { }
	// RVA: 0x1cd6144 VA: 0x75942ee144
	private WaveData _GenerateDefaultWave() { }
	// RVA: 0x1cd62c8 VA: 0x75942ee2c8
	private Void _GenerateTeam(Single score, String tileKey, List`1 enemyList, Boolean unharmful, WaveData outWave) { }
	// RVA: 0x1cd6994 VA: 0x75942ee994
	private Void _GenerateTeamWave(String tileKey, List`1 enemyList, Boolean unharmful, WaveData outWave) { }
	// RVA: 0x1cd6fe0 VA: 0x75942eefe0
	private List`1 _FindSpawnPositions(String tileKey) { }
	// RVA: 0x1cd7264 VA: 0x75942ef264
	private Void _GenerateActionForEnemy(String enemyId, Int32[] position, Single spawnDelay, Boolean unharmful, WaveData outWave) { }
	// RVA: 0x1cd76e8 VA: 0x75942ef6e8
	public Void .ctor() { }
}
```