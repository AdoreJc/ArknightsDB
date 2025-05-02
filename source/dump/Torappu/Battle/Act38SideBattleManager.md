# Act38SideBattleManager

**Namespace:** `Torappu.Battle`


## Fields

- `Single _timeToRespawnFirework`

- `FireworkType _defaultFireworkType`

- `Int32 _defaultFireworkLevel`

- `Int32 _defaultFireworkRangeIndex`

- `Single _minClearDistance`

- `Single _minFireOffset`

- `String _fireEnemyId`

- `String _fireworkTrapId`

- `String _bossId`

- `String _fireworkCamEff`

- `String _tileEffectKey`

- `String _color`

- `Single _colorTweenDuration`

- `Tile m_fireworkTile`

- `Trap m_fireworkTrap`

- `FireworkType m_fireworkType`

- `String m_fireworkId`

- `Int32 m_fireworkLevel`

- `Int32 m_fireworkRangeIndex`

- `Boolean m_isAvgLevel`

- `Boolean m_isFunLevel`

- `Boolean m_isTrLevel`

- `Boolean m_hasStartAvgEmitted`

- `Boolean m_hasWinAvgEmitted`

- `Boolean m_hasLostAvgEmitted`

- `Boolean m_isTrapInitiated`

- `CameraEffect m_fireworkCamEff`

- `Enemy m_boss`

- `Enemy m_fire`

- `Effect m_lineEffect`

- `LineRenderer m_lineRenderer`

- `Material m_material`

- `Int32 m_tintColor`

- `Tween m_tween`

- `BattleCharacterData m_fireworkTrapData`

- `Route m_carnivalRoute`

- `CoroutineId m_coroutineId`

- `RangeData m_fireworkRangeData`

- `Boolean m_isBossLevel`

- `Int32 m_allyKillCnt`

- `Int32 m_bossKillCnt`

- `Boolean m_isBossWin`

- `Boolean m_nextFireworkBuff`

- `Boolean m_nextFireworkDeBuff`

- `Boolean m_isDuringCarnival`

- `Boolean m_bossBorn`


## Properties

- `Enemy boss`

- `FireworkType fireworkType`

- `Int32 fireworkLevel`

- `String defaultRangeId`

- `RangeData fireworkRangeData`

- `Int32 allyKillCnt`

- `Int32 bossKillCnt`

- `Boolean isDuringCarnivalBet`

- `Boolean isDuringCarnival`

- `Boolean isBossFinished`

- `Boolean isBossWin`

- `Route carnivalRoute`


## Methods

- `Enemy get_boss()`

- `FireworkType get_fireworkType()`

- `Int32 get_fireworkLevel()`

- `String get_defaultRangeId()`

- `RangeData get_fireworkRangeData()`

- `Int32 get_allyKillCnt()`

- `Int32 get_bossKillCnt()`

- `Boolean get_isDuringCarnivalBet()`

- `Boolean get_isDuringCarnival()`

- `Boolean get_isBossFinished()`

- `Boolean get_isBossWin()`

- `Route get_carnivalRoute()`

- `Void LogKilled(Boolean)`

- `Void CheckFunLevelLost()`

- `Void _OnGameStart(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _OnEnemyBorn(Enemy)`

- `Void _OnCarnivalStart()`

- `Void _OnCarnivalFinish()`

- `Void _OnBossWin()`

- `Void _OnAllyWin()`

- `Void _OnGameOver(Object)`

- `Void _InitFirework()`

- `Void _ResetCount()`

- `Void _InitFireworkSpine()`

- `Void _ResetFirework()`

- `RangeData _ConvertToRangeData()`

- `Void _LogCarnivalStart()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnTrigger(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act38SideBattleManager : EnvManager
{
	private Single _timeToRespawnFirework; // 0x28
	private FireworkType _defaultFireworkType; // 0x2c
	private Int32 _defaultFireworkLevel; // 0x30
	private Int32 _defaultFireworkRangeIndex; // 0x34
	private List`1 _defaultRangeIdList; // 0x38
	private List`1 _defaultFireworkRangeData; // 0x40
	private Single _minClearDistance; // 0x48
	private Single _minFireOffset; // 0x4c
	private String _fireEnemyId; // 0x50
	private String _fireworkTrapId; // 0x58
	private String _bossId; // 0x60
	private List`1 _winFireworkBuffs; // 0x68
	private List`1 _winBossBuffs; // 0x70
	private List`1 _lostFireworkBuffs; // 0x78
	private String _fireworkCamEff; // 0x80
	private String _tileEffectKey; // 0x88
	private String _color; // 0x90
	private Single _colorTweenDuration; // 0x98
	private Tile m_fireworkTile; // 0xa0
	private Trap m_fireworkTrap; // 0xa8
	private FireworkType m_fireworkType; // 0xb0
	private String m_fireworkId; // 0xb8
	private Int32 m_fireworkLevel; // 0xc0
	private Int32 m_fireworkRangeIndex; // 0xc4
	private Boolean m_isAvgLevel; // 0xc8
	private Boolean m_isFunLevel; // 0xc9
	private Boolean m_isTrLevel; // 0xca
	private Boolean m_hasStartAvgEmitted; // 0xcb
	private Boolean m_hasWinAvgEmitted; // 0xcc
	private Boolean m_hasLostAvgEmitted; // 0xcd
	private Boolean m_isTrapInitiated; // 0xce
	private CameraEffect m_fireworkCamEff; // 0xd0
	private Enemy m_boss; // 0xd8
	private Enemy m_fire; // 0xe0
	private readonly ListDict`2 m_tiles; // 0xe8
	private Effect m_lineEffect; // 0xf0
	private LineRenderer[] m_lineRenderers; // 0xf8
	private LineRenderer m_lineRenderer; // 0x100
	private Material m_material; // 0x108
	private readonly List`1 m_originLinePositions; // 0x110
	private List`1 m_linePositions; // 0x118
	private Int32 m_tintColor; // 0x120
	private Tween m_tween; // 0x128
	private BattleCharacterData m_fireworkTrapData; // 0x130
	private Route m_carnivalRoute; // 0x138
	private CoroutineId m_coroutineId; // 0x140
	private RangeData m_fireworkRangeData; // 0x150
	private Int32[,] m_fireworkRangeDataArray; // 0x158
	private Boolean m_isBossLevel; // 0x160
	private Int32 m_allyKillCnt; // 0x164
	private Int32 m_bossKillCnt; // 0x168
	private Boolean m_isBossWin; // 0x16c
	private Boolean m_nextFireworkBuff; // 0x16d
	private Boolean m_nextFireworkDeBuff; // 0x16e
	private Boolean m_isDuringCarnival; // 0x16f
	private Boolean m_bossBorn; // 0x170
	private const String EVENT_ON_CARNIVAL_START; // 0x0
	private const String EVENT_ON_CARNIVAL_FINISH; // 0x0
	private const String LINE_INDEX; // 0x0
	private const String LOG_CARNIVAL; // 0x0
	private const String MATERIAL_KEY; // 0x0
	private static DelegateBridge __Hotfix0_get_boss; // 0x0
	private static DelegateBridge __Hotfix0_get_fireworkType; // 0x8
	private static DelegateBridge __Hotfix0_get_fireworkLevel; // 0x10
	private static DelegateBridge __Hotfix0_get_defaultRangeId; // 0x18
	private static DelegateBridge __Hotfix0_get_fireworkRangeData; // 0x20
	private static DelegateBridge __Hotfix0_get_allyKillCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_bossKillCnt; // 0x30
	private static DelegateBridge __Hotfix0_get_isDuringCarnivalBet; // 0x38
	private static DelegateBridge __Hotfix0_get_isDuringCarnival; // 0x40
	private static DelegateBridge __Hotfix0_get_isBossFinished; // 0x48
	private static DelegateBridge __Hotfix0_get_isBossWin; // 0x50
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x58
	private static DelegateBridge __Hotfix0_get_carnivalRoute; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x68
	private static DelegateBridge __Hotfix0_OnTick; // 0x70
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x78
	private static DelegateBridge __Hotfix0_LogKilled; // 0x80
	private static DelegateBridge __Hotfix0_CheckFunLevelLost; // 0x88
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x90
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x98
	private static DelegateBridge __Hotfix0__OnEnemyBorn; // 0xa0
	private static DelegateBridge __Hotfix0__OnCarnivalStart; // 0xa8
	private static DelegateBridge __Hotfix0__OnCarnivalFinish; // 0xb0
	private static DelegateBridge __Hotfix0__OnBossWin; // 0xb8
	private static DelegateBridge __Hotfix0__OnAllyWin; // 0xc0
	private static DelegateBridge __Hotfix0__OnGameOver; // 0xc8
	private static DelegateBridge __Hotfix0__InitFirework; // 0xd0
	private static DelegateBridge __Hotfix0__ResetCount; // 0xd8
	private static DelegateBridge __Hotfix0__InitFireworkSpine; // 0xe0
	private static DelegateBridge __Hotfix0__ResetFirework; // 0xe8
	private static DelegateBridge __Hotfix0__ConvertToGridPositions; // 0xf0
	private static DelegateBridge __Hotfix0__ConvertToIntArray; // 0xf8
	private static DelegateBridge __Hotfix0__ConvertToRangeData; // 0x100
	private static DelegateBridge __Hotfix0__LogCarnivalStart; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	private Enemy boss { get; }
	public FireworkType fireworkType { get; }
	public Int32 fireworkLevel { get; }
	public String defaultRangeId { get; }
	public RangeData fireworkRangeData { get; }
	public Int32 allyKillCnt { get; }
	public Int32 bossKillCnt { get; }
	public Boolean isDuringCarnivalBet { get; }
	public Boolean isDuringCarnival { get; }
	public Boolean isBossFinished { get; }
	public Boolean isBossWin { get; }
	public override IEnumerable`1 eventGroups { get; }
	public Route carnivalRoute { get; }

	// RVA: 0x403c96c VA: 0x759665496c
	private Enemy get_boss() { }
	// RVA: 0x403ca38 VA: 0x7596654a38
	public FireworkType get_fireworkType() { }
	// RVA: 0x403caa0 VA: 0x7596654aa0
	public Int32 get_fireworkLevel() { }
	// RVA: 0x403cb08 VA: 0x7596654b08
	public String get_defaultRangeId() { }
	// RVA: 0x403cbdc VA: 0x7596654bdc
	public RangeData get_fireworkRangeData() { }
	// RVA: 0x403cc44 VA: 0x7596654c44
	public Int32 get_allyKillCnt() { }
	// RVA: 0x403ccac VA: 0x7596654cac
	public Int32 get_bossKillCnt() { }
	// RVA: 0x403cd14 VA: 0x7596654d14
	public Boolean get_isDuringCarnivalBet() { }
	// RVA: 0x403cdd0 VA: 0x7596654dd0
	public Boolean get_isDuringCarnival() { }
	// RVA: 0x403ce38 VA: 0x7596654e38
	public Boolean get_isBossFinished() { }
	// RVA: 0x403cf64 VA: 0x7596654f64
	public Boolean get_isBossWin() { }
	// RVA: 0x403d02c VA: 0x759665502c
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x403d2cc VA: 0x75966552cc
	public Route get_carnivalRoute() { }
	// RVA: 0x403d334 VA: 0x7596655334
	public override Void Init(GlobalEnvSystem envSystem) { }
	// RVA: 0x403d7e4 VA: 0x75966557e4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x403dce0 VA: 0x7596655ce0
	public override Void OnTrigger(Object param) { }
	// RVA: 0x403e6b0 VA: 0x75966566b0
	public Void LogKilled(Boolean isKilledByBoss) { }
	// RVA: 0x403e76c VA: 0x759665676c
	public Void CheckFunLevelLost() { }
	// RVA: 0x403e818 VA: 0x7596656818
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x403f4e4 VA: 0x75966574e4
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x403f5f8 VA: 0x75966575f8
	private Void _OnEnemyBorn(Enemy enemy) { }
	// RVA: 0x403de60 VA: 0x7596655e60
	private Void _OnCarnivalStart() { }
	// RVA: 0x403e480 VA: 0x7596656480
	private Void _OnCarnivalFinish() { }
	// RVA: 0x403f7ec VA: 0x75966577ec
	private Void _OnBossWin() { }
	// RVA: 0x403f9b8 VA: 0x75966579b8
	private Void _OnAllyWin() { }
	// RVA: 0x403fd64 VA: 0x7596657d64
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x403ef4c VA: 0x7596656f4c
	private Void _InitFirework() { }
	// RVA: 0x4040528 VA: 0x7596658528
	private Void _ResetCount() { }
	// RVA: 0x404059c VA: 0x759665859c
	private Void _InitFireworkSpine() { }
	// RVA: 0x40400d4 VA: 0x75966580d4
	private Void _ResetFirework() { }
	// RVA: 0x4040730 VA: 0x7596658730
	private static List`1 _ConvertToGridPositions(Int32[,] array) { }
	// RVA: 0x4040950 VA: 0x7596658950
	private Int32[,] _ConvertToIntArray() { }
	// RVA: 0x403d718 VA: 0x7596655718
	private RangeData _ConvertToRangeData() { }
	// RVA: 0x403f6e8 VA: 0x75966576e8
	private Void _LogCarnivalStart() { }
	// RVA: 0x4040adc VA: 0x7596658adc
	public Void .ctor() { }
	// RVA: 0x4040d84 VA: 0x7596658d84
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x4040d8c VA: 0x7596658d8c
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4040d94 VA: 0x7596658d94
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x4040d9c VA: 0x7596658d9c
	private Void <>xLuaBaseProxy_OnTrigger(Object P0) { }
}
```