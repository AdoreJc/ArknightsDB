# DouququGameMode

**Namespace:** ` `


## Fields

- `FP m_roundTime`

- `Int32 m_roundIndex`

- `Boolean m_isBetMode`

- `Coroutine m_finalCoroutine`

- `BattleData m_battleData`

- `RoundResult m_roundResult`


## Properties

- `BattleData battleData`

- `Int32 roundIndex`

- `RoundResult roundResult`

- `Boolean isBetMode`

- `String currentRoundId`

- `DouququMoneyManager moneyManager`

- `DouququNpcManager npcManager`

- `DouququWaveManager waveManager`


## Methods

- `BattleData get_battleData()`

- `Int32 get_roundIndex()`

- `RoundResult get_roundResult()`

- `Boolean get_isBetMode()`

- `String get_currentRoundId()`

- `DouququMoneyManager get_moneyManager()`

- `DouququNpcManager get_npcManager()`

- `DouququWaveManager get_waveManager()`

- `String GetAct5FunLevelId()`

- `Act5FunNpcData GetNpcItemData(Boolean, Int32)`

- `Void GetNpcDataByListPosition(Boolean, Int32, out, out)`

- `Boolean TryGetChoiceRewardData(Int32, out)`

- `String GetTeamDetailsBySide(Boolean)`

- `Single CalculateTeamScoreBySide(Boolean, Act5FunNpcData)`

- `Void _ProcessDouququMode(LevelData)`

- `Void _UnregisterEnemy(UInt32)`

- `Void _CheckRoundFinish()`

- `Void _FinishRound(RoundResult)`

- `IEnumerator _CleanMapForNextRound()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Void <>xLuaBaseProxy_OnGameOver(ref)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_OnEnemyFinished(Enemy, FinishReason)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DouququGameMode : DefaultGameMode
{
	private FP m_roundTime; // 0x20
	private Int32 m_roundIndex; // 0x28
	private Boolean m_isBetMode; // 0x2c
	private Coroutine m_finalCoroutine; // 0x30
	private BattleData m_battleData; // 0x38
	private RoundResult m_roundResult; // 0x40
	private readonly List`1 m_teamRight; // 0x48
	private readonly List`1 m_teamLeft; // 0x50
	private readonly DouququWaveManager m_waveManager; // 0x58
	private readonly DouququMoneyManager m_moneyManager; // 0x60
	private readonly DouququNpcManager m_npcManager; // 0x68
	private const String NORMAL_MODE_LEVEL_ID; // 0x0
	private const Int32 NORMAL_MODE_INIT_INDEX; // 0x0
	private const Int32 BET_MODE_INIT_INDEX; // 0x0
	private const Single WIN_WAIT_TIME; // 0x0
	private const String CHOICE_ID_PREFIX; // 0x0
	private const String ENEMY_DETAILS_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_get_battleData; // 0x0
	private static DelegateBridge __Hotfix0_get_roundIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_roundResult; // 0x10
	private static DelegateBridge __Hotfix0_get_isBetMode; // 0x18
	private static DelegateBridge __Hotfix0_get_currentRoundId; // 0x20
	private static DelegateBridge __Hotfix0_get_moneyManager; // 0x28
	private static DelegateBridge __Hotfix0_get_npcManager; // 0x30
	private static DelegateBridge __Hotfix0_get_waveManager; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x50
	private static DelegateBridge __Hotfix0_Tick; // 0x58
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x60
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x68
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x70
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x78
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x80
	private static DelegateBridge __Hotfix0_GetAct5FunLevelId; // 0x88
	private static DelegateBridge __Hotfix0_GetNpcItemData; // 0x90
	private static DelegateBridge __Hotfix0_GetNpcDataByListPosition; // 0x98
	private static DelegateBridge __Hotfix0_TryGetChoiceRewardData; // 0xa0
	private static DelegateBridge __Hotfix0_GetTeamDetailsBySide; // 0xa8
	private static DelegateBridge __Hotfix0_CalculateTeamScoreBySide; // 0xb0
	private static DelegateBridge __Hotfix0__GetHostEnemyByUid; // 0xb8
	private static DelegateBridge __Hotfix0__GetTeamData; // 0xc0
	private static DelegateBridge __Hotfix0__ProcessDouququMode; // 0xc8
	private static DelegateBridge __Hotfix0__UnregisterEnemy; // 0xd0
	private static DelegateBridge __Hotfix0__CheckRoundFinish; // 0xd8
	private static DelegateBridge __Hotfix0__FinishRound; // 0xe0
	private static DelegateBridge __Hotfix0__CleanMapForNextRound; // 0xe8

	public BattleData battleData { get; }
	public Int32 roundIndex { get; }
	public RoundResult roundResult { get; }
	public Boolean isBetMode { get; }
	public String currentRoundId { get; }
	public DouququMoneyManager moneyManager { get; }
	public DouququNpcManager npcManager { get; }
	public DouququWaveManager waveManager { get; }
	public override GameModeType gameModeType { get; }

	// RVA: 0x1cca6f8 VA: 0x75942e26f8
	public BattleData get_battleData() { }
	// RVA: 0x1cca7b0 VA: 0x75942e27b0
	public Int32 get_roundIndex() { }
	// RVA: 0x1cca818 VA: 0x75942e2818
	public RoundResult get_roundResult() { }
	// RVA: 0x1cca880 VA: 0x75942e2880
	public Boolean get_isBetMode() { }
	// RVA: 0x1cca8e8 VA: 0x75942e28e8
	public String get_currentRoundId() { }
	// RVA: 0x1ccaa74 VA: 0x75942e2a74
	public DouququMoneyManager get_moneyManager() { }
	// RVA: 0x1ccaadc VA: 0x75942e2adc
	public DouququNpcManager get_npcManager() { }
	// RVA: 0x1ccab44 VA: 0x75942e2b44
	public DouququWaveManager get_waveManager() { }
	// RVA: 0x1ccabac VA: 0x75942e2bac
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1ccad64 VA: 0x75942e2d64
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1ccadcc VA: 0x75942e2dcc
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1ccafdc VA: 0x75942e2fdc
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1ccb254 VA: 0x75942e3254
	public override Void OnGameOver(ref GameResult result) { }
	// RVA: 0x1ccb2dc VA: 0x75942e32dc
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1ccb3e8 VA: 0x75942e33e8
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1ccb59c VA: 0x75942e359c
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1ccbbe0 VA: 0x75942e3be0
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cca9bc VA: 0x75942e29bc
	public String GetAct5FunLevelId() { }
	// RVA: 0x1ccbc78 VA: 0x75942e3c78
	public Act5FunNpcData GetNpcItemData(Boolean isLeft, Int32 position) { }
	// RVA: 0x1ccbd84 VA: 0x75942e3d84
	public Void GetNpcDataByListPosition(Boolean isLeft, Int32 position, out String originId, out Int32 cnt) { }
	// RVA: 0x1ccbfe0 VA: 0x75942e3fe0
	public Boolean TryGetChoiceRewardData(Int32 selection, out Act5FunChoiceRewardData data) { }
	// RVA: 0x1ccc118 VA: 0x75942e4118
	public String GetTeamDetailsBySide(Boolean isLeft) { }
	// RVA: 0x1ccc3b4 VA: 0x75942e43b4
	public Single CalculateTeamScoreBySide(Boolean isLeft, Act5FunNpcData npcInfoData) { }
	// RVA: 0x1ccb774 VA: 0x75942e3774
	private static Unit _GetHostEnemyByUid(UInt32 hostUid) { }
	// RVA: 0x1ccbf1c VA: 0x75942e3f1c
	private List`1 _GetTeamData(Boolean isLeft) { }
	// RVA: 0x1ccaf30 VA: 0x75942e2f30
	private Void _ProcessDouququMode(LevelData levelData) { }
	// RVA: 0x1ccbae0 VA: 0x75942e3ae0
	private Void _UnregisterEnemy(UInt32 uid) { }
	// RVA: 0x1ccb188 VA: 0x75942e3188
	private Void _CheckRoundFinish() { }
	// RVA: 0x1ccc620 VA: 0x75942e4620
	private Void _FinishRound(RoundResult result) { }
	// RVA: 0x1ccc768 VA: 0x75942e4768
	private IEnumerator _CleanMapForNextRound() { }
	// RVA: 0x1ccc83c VA: 0x75942e483c
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1ccc844 VA: 0x75942e4844
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1ccc84c VA: 0x75942e484c
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1ccc854 VA: 0x75942e4854
	private Void <>xLuaBaseProxy_OnGameOver(ref GameResult P0) { }
	// RVA: 0x1ccc85c VA: 0x75942e485c
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1ccc864 VA: 0x75942e4864
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1ccc86c VA: 0x75942e486c
	private Void <>xLuaBaseProxy_OnEnemyFinished(Enemy P0, FinishReason P1) { }
	// RVA: 0x1ccc874 VA: 0x75942e4874
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
}
```