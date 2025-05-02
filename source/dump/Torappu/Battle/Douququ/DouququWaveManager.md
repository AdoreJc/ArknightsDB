# DouququWaveManager

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `LevelData m_levelData`

- `DouququGameMode m_gameMode`


## Properties

- `Int32 totalWaveCnt`


## Methods

- `Int32 get_totalWaveCnt()`

- `Void Init(DouququGameMode, LevelData)`

- `Void _ProcessRoundData()`

- `Void _ProcessEnemyData()`

- `WaveData _GenerateRound(Int32)`

- `Int32 _GetActionCnt()`

- `Void _TideRoute()`

- `Void _GenerateTeam(Single, String, List`1, Boolean, WaveData)`

- `Void _GenerateTeamWave(String, List`1, Boolean, WaveData)`

- `Void _GenerateActionForEnemy(String, Int32[], Single, Boolean, WaveData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class DouququWaveManager : IHotfixable
{
	private LevelData m_levelData; // 0x10
	private readonly List`1 m_allEnemyExtraData; // 0x18
	private readonly List`1 m_roundDataList; // 0x20
	private readonly List`1 m_teamList; // 0x28
	private readonly Dictionary`2 m_startPos; // 0x30
	private DouququGameMode m_gameMode; // 0x38
	private const String TILE_START; // 0x0
	private const String TILE_END; // 0x0
	private const Single DOUQUQU_ENEMY_WAVE_INTERVAL; // 0x0
	private const Single MAX_ENEMY_COST; // 0x0
	private const Single MAX_WAIT_TIME; // 0x0
	private static DelegateBridge __Hotfix0_get_teamList; // 0x0
	private static DelegateBridge __Hotfix0_get_totalWaveCnt; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0__ProcessRoundData; // 0x18
	private static DelegateBridge __Hotfix0__ProcessEnemyData; // 0x20
	private static DelegateBridge __Hotfix0__AddToRoundList; // 0x28
	private static DelegateBridge __Hotfix0__GenerateRound; // 0x30
	private static DelegateBridge __Hotfix0__SelectEnemyForEachTeam; // 0x38
	private static DelegateBridge __Hotfix0__AvailableEnemy; // 0x40
	private static DelegateBridge __Hotfix0__GetActionCnt; // 0x48
	private static DelegateBridge __Hotfix0__NeedRoute; // 0x50
	private static DelegateBridge __Hotfix0__TideRoute; // 0x58
	private static DelegateBridge __Hotfix0__GenerateDefaultWave; // 0x60
	private static DelegateBridge __Hotfix0__GenerateTeam; // 0x68
	private static DelegateBridge __Hotfix0__GenerateTeamWave; // 0x70
	private static DelegateBridge __Hotfix0__FindSpawnPositions; // 0x78
	private static DelegateBridge __Hotfix0__GenerateActionForEnemy; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public List`1 teamList { get; }
	public Int32 totalWaveCnt { get; }

	// RVA: 0x1dccd68 VA: 0x75943e4d68
	public List`1 get_teamList() { }
	// RVA: 0x1dccdd0 VA: 0x75943e4dd0
	public Int32 get_totalWaveCnt() { }
	// RVA: 0x1dcce4c VA: 0x75943e4e4c
	public Void Init(DouququGameMode gameMode, LevelData levelData) { }
	// RVA: 0x1dcd304 VA: 0x75943e5304
	private Void _ProcessRoundData() { }
	// RVA: 0x1dcd540 VA: 0x75943e5540
	private Void _ProcessEnemyData() { }
	// RVA: 0x1dcdd58 VA: 0x75943e5d58
	private static Void _AddToRoundList(ref List`1 list, String key, Int32 cnt) { }
	// RVA: 0x1dcd7a4 VA: 0x75943e57a4
	private WaveData _GenerateRound(Int32 round) { }
	// RVA: 0x1dcdff4 VA: 0x75943e5ff4
	private static Void _SelectEnemyForEachTeam(List`1 selected, List`1 enemyForTheRound, Int32 typeCnt) { }
	// RVA: 0x1dce808 VA: 0x75943e6808
	private static Boolean _AvailableEnemy(String enemyId) { }
	// RVA: 0x1dce8d0 VA: 0x75943e68d0
	private Int32 _GetActionCnt() { }
	// RVA: 0x1dce9bc VA: 0x75943e69bc
	private static Boolean _NeedRoute(ActionData action) { }
	// RVA: 0x1dcdad0 VA: 0x75943e5ad0
	private Void _TideRoute() { }
	// RVA: 0x1dce1e4 VA: 0x75943e61e4
	private static WaveData _GenerateDefaultWave() { }
	// RVA: 0x1dce3c0 VA: 0x75943e63c0
	private Void _GenerateTeam(Single score, String tileKey, List`1 enemyList, Boolean unharmful, WaveData outWave) { }
	// RVA: 0x1dcea4c VA: 0x75943e6a4c
	private Void _GenerateTeamWave(String tileKey, List`1 enemyList, Boolean unharmful, WaveData outWave) { }
	// RVA: 0x1dcf098 VA: 0x75943e7098
	private List`1 _FindSpawnPositions(String tileKey) { }
	// RVA: 0x1dcf31c VA: 0x75943e731c
	private Void _GenerateActionForEnemy(String enemyId, Int32[] position, Single spawnDelay, Boolean unharmful, WaveData outWave) { }
	// RVA: 0x1dcf7a0 VA: 0x75943e77a0
	public Void .ctor() { }
}
```