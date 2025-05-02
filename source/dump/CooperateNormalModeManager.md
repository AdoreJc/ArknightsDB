# CooperateNormalModeManager

**Namespace:** ` `


## Fields

- `CooperateGameMode m_mode`

- `Int32 m_curWave`

- `Int32 m_curStage`

- `Int32 m_curScore`

- `CoopStageType m_curStageType`

- `Int32 m_dieTime`

- `Int32 m_hpReduceMeStage`

- `Int32 m_hpReduceMateStage`

- `Int32 m_hpReduceSharedStage`

- `Boolean m_isMeFailStage`


## Properties

- `Boolean isLastWave`

- `Int32 curStage`

- `Int32 curScore`

- `Boolean isMeFailStage`

- `Int32 dieTime`


## Methods

- `Boolean get_isLastWave()`

- `Int32 get_curStage()`

- `Int32 get_curScore()`

- `Boolean get_isMeFailStage()`

- `Int32 get_dieTime()`

- `Void OnApplyingGlobalModifier(ref)`

- `Void OnEnemyReachExit(Enemy, Tile)`

- `Void OnPlayerLifeToZero(PlayerSide)`

- `Void OnRestingFinished()`

- `Boolean OnRegistStageBuff(ObjectPtr`1)`

- `Void OnFinishGame()`

- `Single FindMaxDistance()`

- `Boolean CheckContainsEnemy(String)`

- `Void ResetTargetEnemies(String)`

- `Void ModifyStateType(CoopStageType)`

- `Void UpdateScoreManually(Int32)`

- `Void _ResetStage()`

- `Void _OnMakePlayerCharacterRevive(PlayerSide)`

- `Void OnDoPlayerResting()`

- `Void <OnDoPlayerResting>b__43_0(Deck)`

- `Boolean <>xLuaBaseProxy_HookGetNextWave()`

- `Void <>xLuaBaseProxy_Init(CooperateGameMode, LevelData)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData)`

- `Int32 <>xLuaBaseProxy_OnGetHpForGameCheck()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CooperateNormalModeManager : CooperateSubMode
{
	private CooperateGameMode m_mode; // 0x10
	private Int32 m_curWave; // 0x18
	private Int32 m_curStage; // 0x1c
	private Int32 m_curScore; // 0x20
	private CoopStageType m_curStageType; // 0x24
	private ObjectPtr`1 m_stageBuff; // 0x28
	private List`1 m_targetEnemies; // 0x38
	private Int32 m_dieTime; // 0x40
	private Int32 m_hpReduceMeStage; // 0x44
	private Int32 m_hpReduceMateStage; // 0x48
	private Int32 m_hpReduceSharedStage; // 0x4c
	private Boolean m_isMeFailStage; // 0x50
	private readonly Blackboard m_restingBlackboard; // 0x58
	private static DelegateBridge __Hotfix0_get_isLastWave; // 0x0
	private static DelegateBridge __Hotfix0_get_curStage; // 0x8
	private static DelegateBridge __Hotfix0_get_curScore; // 0x10
	private static DelegateBridge __Hotfix0_get_hpReduce; // 0x18
	private static DelegateBridge __Hotfix0_get_isMeFailStage; // 0x20
	private static DelegateBridge __Hotfix0_get_dieTime; // 0x28
	private static DelegateBridge __Hotfix0_HookGetNextWave; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x40
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0x48
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x50
	private static DelegateBridge __Hotfix0_OnEnemyReachExit; // 0x58
	private static DelegateBridge __Hotfix0_OnPlayerLifeToZero; // 0x60
	private static DelegateBridge __Hotfix0_OnRestingFinished; // 0x68
	private static DelegateBridge __Hotfix0_OnRegistStageBuff; // 0x70
	private static DelegateBridge __Hotfix0_OnFinishGame; // 0x78
	private static DelegateBridge __Hotfix0_OnGetHpForGameCheck; // 0x80
	private static DelegateBridge __Hotfix0_FindMaxDistance; // 0x88
	private static DelegateBridge __Hotfix0_CheckContainsEnemy; // 0x90
	private static DelegateBridge __Hotfix0_ResetTargetEnemies; // 0x98
	private static DelegateBridge __Hotfix0_ModifyStateType; // 0xa0
	private static DelegateBridge __Hotfix0_UpdateScoreManually; // 0xa8
	private static DelegateBridge __Hotfix0__ResetStage; // 0xb0
	private static DelegateBridge __Hotfix0__OnMakePlayerCharacterRevive; // 0xb8
	private static DelegateBridge __Hotfix0_OnDoPlayerResting; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Boolean isLastWave { get; }
	public Int32 curStage { get; }
	public Int32 curScore { get; }
	public List`1 hpReduce { get; }
	public Boolean isMeFailStage { get; }
	public Int32 dieTime { get; }

	// RVA: 0x1cc5e30 VA: 0x75942dde30
	public Boolean get_isLastWave() { }
	// RVA: 0x1cc84d8 VA: 0x75942e04d8
	public Int32 get_curStage() { }
	// RVA: 0x1cc8540 VA: 0x75942e0540
	public Int32 get_curScore() { }
	// RVA: 0x1cc85a8 VA: 0x75942e05a8
	public List`1 get_hpReduce() { }
	// RVA: 0x1cc8770 VA: 0x75942e0770
	public Boolean get_isMeFailStage() { }
	// RVA: 0x1cc87d8 VA: 0x75942e07d8
	public Int32 get_dieTime() { }
	// RVA: 0x1cc8840 VA: 0x75942e0840
	public override Boolean HookGetNextWave() { }
	// RVA: 0x1cc88a4 VA: 0x75942e08a4
	public override Void Init(CooperateGameMode gameMode, LevelData levelData) { }
	// RVA: 0x1cc8940 VA: 0x75942e0940
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cc8ce8 VA: 0x75942e0ce8
	public override Void OnWaveWillFinish(WaveData waveData) { }
	// RVA: 0x1cc378c VA: 0x75942db78c
	public Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cc3c30 VA: 0x75942dbc30
	public Void OnEnemyReachExit(Enemy enemy, Tile cacheTile) { }
	// RVA: 0x1cc2488 VA: 0x75942da488
	public Void OnPlayerLifeToZero(PlayerSide side) { }
	// RVA: 0x1cc65b4 VA: 0x75942de5b4
	public Void OnRestingFinished() { }
	// RVA: 0x1cc5f64 VA: 0x75942ddf64
	public Boolean OnRegistStageBuff(ObjectPtr`1 buff) { }
	// RVA: 0x1cc2cb0 VA: 0x75942dacb0
	public Void OnFinishGame() { }
	// RVA: 0x1cc8f58 VA: 0x75942e0f58
	public override Int32 OnGetHpForGameCheck() { }
	// RVA: 0x1cc6760 VA: 0x75942de760
	public Single FindMaxDistance() { }
	// RVA: 0x1cc69dc VA: 0x75942de9dc
	public Boolean CheckContainsEnemy(String enemyId) { }
	// RVA: 0x1cc6b14 VA: 0x75942deb14
	public Void ResetTargetEnemies(String enemyId) { }
	// RVA: 0x1cc9010 VA: 0x75942e1010
	public Void ModifyStateType(CoopStageType type) { }
	// RVA: 0x1cc908c VA: 0x75942e108c
	public Void UpdateScoreManually(Int32 score) { }
	// RVA: 0x1cc8eb0 VA: 0x75942e0eb0
	private Void _ResetStage() { }
	// RVA: 0x1cc8be8 VA: 0x75942e0be8
	private Void _OnMakePlayerCharacterRevive(PlayerSide side) { }
	// RVA: 0x1cc6308 VA: 0x75942de308
	public Void OnDoPlayerResting() { }
	// RVA: 0x1cbf594 VA: 0x75942d7594
	public Void .ctor() { }
	// RVA: 0x1cc9168 VA: 0x75942e1168
	private Void <OnDoPlayerResting>b__43_0(Deck deck) { }
	// RVA: 0x1cc9254 VA: 0x75942e1254
	private Boolean <>xLuaBaseProxy_HookGetNextWave() { }
	// RVA: 0x1cc9258 VA: 0x75942e1258
	private Void <>xLuaBaseProxy_Init(CooperateGameMode P0, LevelData P1) { }
	// RVA: 0x1cc925c VA: 0x75942e125c
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cc9260 VA: 0x75942e1260
	private Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData P0) { }
	// RVA: 0x1cc9264 VA: 0x75942e1264
	private Int32 <>xLuaBaseProxy_OnGetHpForGameCheck() { }
}
```