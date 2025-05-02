# CooperateFootballModeManager

**Namespace:** ` `


## Fields

- `CooperateGameMode m_mode`

- `SideTypeIndex m_cachedScoreSideTypeIndex`

- `FP m_footballMaxPlayTime`

- `FP m_footballRemainTime`

- `FP m_holdingFootballRemainTime`

- `PlayerSide m_holdFootballPlayerSide`

- `PeriodicTimer m_landingFootballTimer`

- `Card m_landBallCard`

- `Vector2 m_targetLandPosition`

- `Vector2 m_defaultLandPosition`

- `Boolean m_isHoldingFootball`

- `Boolean m_isLandingFootball`

- `Boolean m_hasScored`

- `Int32 m_curWave`

- `Effect m_cachedLandBallEffect`


## Properties

- `Boolean hasScored`

- `FP footballMaxPlayTime`

- `FP footballRemainTime`

- `SideTypeIndex cachedScoreSideTypeIndex`


## Methods

- `Boolean get_hasScored()`

- `FP get_footballMaxPlayTime()`

- `FP get_footballRemainTime()`

- `SideTypeIndex get_cachedScoreSideTypeIndex()`

- `Void InitFootball(Vector2, FootballEnemy)`

- `Void OnFootballManualTick(FP)`

- `Void LandFootball(Vector2, Boolean)`

- `Void OnAllyHoldFootball(FP, Tile, PlayerSide)`

- `Void OnScoreAGoal(SideTypeIndex, Int32)`

- `Void OnScoreFinished()`

- `Int32 GetGoal(SideTypeIndex)`

- `IEnumerator OnBeforeWaveStart()`

- `Void _DoLandFootball()`

- `Void _InitLandFootballPosition(GridPosition)`

- `Void _ProcessDeckOnScoreFinished(Deck)`

- `Boolean <>xLuaBaseProxy_HookGetNextWave()`

- `Void <>xLuaBaseProxy_Init(CooperateGameMode, LevelData)`

- `Boolean <>xLuaBaseProxy_TryGetNextWaveIndexInGameMode(out)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData)`

- `Int32 <>xLuaBaseProxy_OnGetHpForGameCheck()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CooperateFootballModeManager : CooperateSubMode
{
	private const Int32 LAND_FOOTBALL_PREDELAY; // 0x0
	private const Int32 FOOTBALL_RESPAWN_COST_MULTI_CNT; // 0x0
	private const Int32 FOOTBALL_RESPAWN_COST_MULTIPLIER; // 0x0
	private const Int32 FOOTBALL_RESPAWN_COST_MAX_MULTIPLIER; // 0x0
	private CooperateGameMode m_mode; // 0x10
	private SideTypeIndex m_cachedScoreSideTypeIndex; // 0x18
	private ObjectPtr`1 m_football; // 0x20
	private FP m_footballMaxPlayTime; // 0x30
	private FP m_footballRemainTime; // 0x38
	private FP m_holdingFootballRemainTime; // 0x40
	private PlayerSide m_holdFootballPlayerSide; // 0x48
	private PeriodicTimer m_landingFootballTimer; // 0x50
	private Card m_landBallCard; // 0x58
	private Vector2 m_targetLandPosition; // 0x60
	private Vector2 m_defaultLandPosition; // 0x68
	private Boolean m_isHoldingFootball; // 0x70
	private Boolean m_isLandingFootball; // 0x71
	private Boolean m_hasScored; // 0x72
	private Int32 m_curWave; // 0x74
	private Effect m_cachedLandBallEffect; // 0x78
	private readonly GridPosition m_landBallOffset; // 0x80
	private readonly Blackboard m_enemyScoreBlackboard; // 0x88
	public readonly Int32[] scoreStatus; // 0x90
	private static DelegateBridge __Hotfix0_get_hasScored; // 0x0
	private static DelegateBridge __Hotfix0_get_footballMaxPlayTime; // 0x8
	private static DelegateBridge __Hotfix0_get_footballRemainTime; // 0x10
	private static DelegateBridge __Hotfix0_get_cachedScoreSideTypeIndex; // 0x18
	private static DelegateBridge __Hotfix0_HookGetNextWave; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_InitFootball; // 0x30
	private static DelegateBridge __Hotfix0_TryGetNextWaveIndexInGameMode; // 0x38
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x40
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0x48
	private static DelegateBridge __Hotfix0_OnGetHpForGameCheck; // 0x50
	private static DelegateBridge __Hotfix0_OnFootballManualTick; // 0x58
	private static DelegateBridge __Hotfix0_LandFootball; // 0x60
	private static DelegateBridge __Hotfix0_OnAllyHoldFootball; // 0x68
	private static DelegateBridge __Hotfix0_OnScoreAGoal; // 0x70
	private static DelegateBridge __Hotfix0_OnScoreFinished; // 0x78
	private static DelegateBridge __Hotfix0_GetGoal; // 0x80
	private static DelegateBridge __Hotfix0_OnBeforeWaveStart; // 0x88
	private static DelegateBridge __Hotfix0__DoLandFootball; // 0x90
	private static DelegateBridge __Hotfix0__InitLandFootballPosition; // 0x98
	private static DelegateBridge __Hotfix0__ProcessDeckOnScoreFinished; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Boolean hasScored { get; }
	public FP footballMaxPlayTime { get; }
	public FP footballRemainTime { get; }
	public SideTypeIndex cachedScoreSideTypeIndex { get; }

	// RVA: 0x1cc6fc8 VA: 0x75942defc8
	public Boolean get_hasScored() { }
	// RVA: 0x1cc7030 VA: 0x75942df030
	public FP get_footballMaxPlayTime() { }
	// RVA: 0x1cc7098 VA: 0x75942df098
	public FP get_footballRemainTime() { }
	// RVA: 0x1cc7100 VA: 0x75942df100
	public SideTypeIndex get_cachedScoreSideTypeIndex() { }
	// RVA: 0x1cc7168 VA: 0x75942df168
	public override Boolean HookGetNextWave() { }
	// RVA: 0x1cc71e4 VA: 0x75942df1e4
	public override Void Init(CooperateGameMode gameMode, LevelData levelData) { }
	// RVA: 0x1cb9a5c VA: 0x75942d1a5c
	public Void InitFootball(Vector2 position, FootballEnemy enemy) { }
	// RVA: 0x1cc7324 VA: 0x75942df324
	public override Boolean TryGetNextWaveIndexInGameMode(out Int32 index) { }
	// RVA: 0x1cc75cc VA: 0x75942df5cc
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cc7738 VA: 0x75942df738
	public override Void OnWaveWillFinish(WaveData waveData) { }
	// RVA: 0x1cc77b8 VA: 0x75942df7b8
	public override Int32 OnGetHpForGameCheck() { }
	// RVA: 0x1cb97f8 VA: 0x75942d17f8
	public Void OnFootballManualTick(FP deltaTime) { }
	// RVA: 0x1cb9be0 VA: 0x75942d1be0
	public Void LandFootball(Vector2 position, Boolean force) { }
	// RVA: 0x1cb9f68 VA: 0x75942d1f68
	public Void OnAllyHoldFootball(FP holdingFootballRemainTime, Tile tile, PlayerSide playerSide) { }
	// RVA: 0x1cba3c8 VA: 0x75942d23c8
	public Void OnScoreAGoal(SideTypeIndex sideTypeIndex, Int32 value) { }
	// RVA: 0x1cba568 VA: 0x75942d2568
	public Void OnScoreFinished() { }
	// RVA: 0x1cba288 VA: 0x75942d2288
	public Int32 GetGoal(SideTypeIndex side) { }
	// RVA: 0x1cc7b38 VA: 0x75942dfb38
	public IEnumerator OnBeforeWaveStart() { }
	// RVA: 0x1cc7844 VA: 0x75942df844
	private Void _DoLandFootball() { }
	// RVA: 0x1cc79cc VA: 0x75942df9cc
	private Void _InitLandFootballPosition(GridPosition holdFootballGridPos) { }
	// RVA: 0x1cc7c0c VA: 0x75942dfc0c
	private Void _ProcessDeckOnScoreFinished(Deck deck) { }
	// RVA: 0x1cbf780 VA: 0x75942d7780
	public Void .ctor() { }
	// RVA: 0x1cc7dc0 VA: 0x75942dfdc0
	private Boolean <>xLuaBaseProxy_HookGetNextWave() { }
	// RVA: 0x1cc7e28 VA: 0x75942dfe28
	private Void <>xLuaBaseProxy_Init(CooperateGameMode P0, LevelData P1) { }
	// RVA: 0x1cc7eac VA: 0x75942dfeac
	private Boolean <>xLuaBaseProxy_TryGetNextWaveIndexInGameMode(out Int32 P0) { }
	// RVA: 0x1cc7f2c VA: 0x75942dff2c
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cc7fa8 VA: 0x75942dffa8
	private Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData P0) { }
	// RVA: 0x1cc8024 VA: 0x75942e0024
	private Int32 <>xLuaBaseProxy_OnGetHpForGameCheck() { }
}
```