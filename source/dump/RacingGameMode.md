# RacingGameMode

**Namespace:** ` `


## Fields

- `RacingInput m_input`

- `RacingBattleManager m_racingManager`

- `Int32 m_circleCnt`

- `Int32 m_circleCheckpointCnt`

- `FP m_realRacingStartTime`

- `Boolean m_isRacingFinished`

- `RacingOutput m_output`


## Properties

- `RacingInput input`

- `Int32 circleCheckpointCnt`

- `Int32 circleCnt`

- `FP realRacingStartTime`

- `RacingEnemy myRacingEnemy`

- `Int32 myRanking`


## Methods

- `RacingInput get_input()`

- `Int32 get_circleCheckpointCnt()`

- `Int32 get_circleCnt()`

- `FP get_realRacingStartTime()`

- `Void set_realRacingStartTime(FP)`

- `RacingEnemy get_myRacingEnemy()`

- `Int32 get_myRanking()`

- `Void UseCurrentItem()`

- `SandboxV2RacingItemInfo GetCurrentItemInfo()`

- `Void SetRacingInfo(Int32, Int32)`

- `Void UpdateRacingFinish(RacingEnemy)`

- `RacingOutput FetchRacingBattleOutput()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_StartGame(Action)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Boolean <>xLuaBaseProxy_GameNotFinishCondition()`

- `Void <>xLuaBaseProxy_FinishGame(Action`2, GameResult, Boolean)`

- `Void <>xLuaBaseProxy_Tick(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingGameMode : DefaultGameMode
{
	private RacingInput m_input; // 0x20
	private RacingBattleManager m_racingManager; // 0x28
	private List`1 m_internalFinishRecords; // 0x30
	private Int32 m_circleCnt; // 0x38
	private Int32 m_circleCheckpointCnt; // 0x3c
	private FP m_realRacingStartTime; // 0x40
	private Boolean m_isRacingFinished; // 0x48
	private RacingOutput m_output; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_input; // 0x8
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x10
	private static DelegateBridge __Hotfix0_get_circleCheckpointCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_circleCnt; // 0x20
	private static DelegateBridge __Hotfix0_get_realRacingStartTime; // 0x28
	private static DelegateBridge __Hotfix0_set_realRacingStartTime; // 0x30
	private static DelegateBridge __Hotfix0_get_myRacingEnemy; // 0x38
	private static DelegateBridge __Hotfix0_get_myRanking; // 0x40
	private static DelegateBridge __Hotfix0_get_racingEnemies; // 0x48
	private static DelegateBridge __Hotfix0_GatherPreloadAssets; // 0x50
	private static DelegateBridge __Hotfix0_UseCurrentItem; // 0x58
	private static DelegateBridge __Hotfix0_GetCurrentItemInfo; // 0x60
	private static DelegateBridge __Hotfix0_SetRacingInfo; // 0x68
	private static DelegateBridge __Hotfix0_UpdateRacingFinish; // 0x70
	private static DelegateBridge __Hotfix0_FetchRacingBattleOutput; // 0x78
	private static DelegateBridge __Hotfix0_StartGame; // 0x80
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x88
	private static DelegateBridge __Hotfix0_GameNotFinishCondition; // 0x90
	private static DelegateBridge __Hotfix0_FinishGame; // 0x98
	private static DelegateBridge __Hotfix0_Tick; // 0xa0
	private static DelegateBridge __Hotfix0__AchieveRacingRecords; // 0xa8
	private static DelegateBridge __Hotfix0__TryGatherDynamicAbilities; // 0xb0

	public RacingInput input { get; }
	public override GameModeType gameModeType { get; }
	public Int32 circleCheckpointCnt { get; }
	public Int32 circleCnt { get; }
	public FP realRacingStartTime { get; set; }
	public RacingEnemy myRacingEnemy { get; }
	public Int32 myRanking { get; }
	public List`1 racingEnemies { get; }

	// RVA: 0x1ceeaec VA: 0x7594306aec
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1ceece8 VA: 0x7594306ce8
	public RacingInput get_input() { }
	// RVA: 0x1ceed50 VA: 0x7594306d50
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1ceedb8 VA: 0x7594306db8
	public Int32 get_circleCheckpointCnt() { }
	// RVA: 0x1ceee20 VA: 0x7594306e20
	public Int32 get_circleCnt() { }
	// RVA: 0x1ceee88 VA: 0x7594306e88
	public FP get_realRacingStartTime() { }
	// RVA: 0x1ceeef0 VA: 0x7594306ef0
	public Void set_realRacingStartTime(FP value) { }
	// RVA: 0x1ceef6c VA: 0x7594306f6c
	public RacingEnemy get_myRacingEnemy() { }
	// RVA: 0x1ceefe0 VA: 0x7594306fe0
	public Int32 get_myRanking() { }
	// RVA: 0x1cef054 VA: 0x7594307054
	public List`1 get_racingEnemies() { }
	// RVA: 0x1cef0c8 VA: 0x75943070c8
	public static Dictionary`2 GatherPreloadAssets() { }
	// RVA: 0x1cef954 VA: 0x7594307954
	public Void UseCurrentItem() { }
	// RVA: 0x1cef9c8 VA: 0x75943079c8
	public SandboxV2RacingItemInfo GetCurrentItemInfo() { }
	// RVA: 0x1cefa3c VA: 0x7594307a3c
	public Void SetRacingInfo(Int32 circleCheckpointCnt, Int32 circleCnt) { }
	// RVA: 0x1cefac0 VA: 0x7594307ac0
	public Void UpdateRacingFinish(RacingEnemy enemy) { }
	// RVA: 0x1cefda4 VA: 0x7594307da4
	public RacingOutput FetchRacingBattleOutput() { }
	// RVA: 0x1cefe0c VA: 0x7594307e0c
	public override Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1cefe9c VA: 0x7594307e9c
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1ceff3c VA: 0x7594307f3c
	public override Boolean GameNotFinishCondition() { }
	// RVA: 0x1cf0030 VA: 0x7594308030
	public override Void FinishGame(Action`2 gameOverCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1cf0604 VA: 0x7594308604
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cf0154 VA: 0x7594308154
	private Dictionary`2 _AchieveRacingRecords() { }
	// RVA: 0x1cef2cc VA: 0x75943072cc
	private static Void _TryGatherDynamicAbilities(RacingInput input, List`1 dynamicAbilities) { }
	// RVA: 0x1cf06cc VA: 0x75943086cc
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cf06d4 VA: 0x75943086d4
	private Void <>xLuaBaseProxy_StartGame(Action P0) { }
	// RVA: 0x1cf06dc VA: 0x75943086dc
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cf06e4 VA: 0x75943086e4
	private Boolean <>xLuaBaseProxy_GameNotFinishCondition() { }
	// RVA: 0x1cf06ec VA: 0x75943086ec
	private Void <>xLuaBaseProxy_FinishGame(Action`2 P0, GameResult P1, Boolean P2) { }
	// RVA: 0x1cf06f8 VA: 0x75943086f8
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
}
```