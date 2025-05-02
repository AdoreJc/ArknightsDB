# EnemyDuelGameMode

**Namespace:** ` `


## Fields

- `InternalState m_state`

- `FP m_roundTime`

- `Int32 m_roundIndex`

- `Int32 m_waveSafeTime`

- `EnemyDuelInput m_inputData`

- `ActivityEnemyDuelData m_actData`

- `ActivityEnemyDuelModeData m_modeData`

- `String m_subModeID`

- `Boolean m_isMultiPlayer`

- `String m_actId`

- `String m_sceneId`

- `Boolean m_isGiveUp`

- `Boolean m_canWaveFinish`

- `CoroutineId m_coroutine`

- `EnemyDuelServiceGameState m_roundState`

- `Boolean m_isInPause`


## Properties

- `Boolean isMultiplayer`

- `String actId`

- `Boolean isInPause`

- `Boolean isPrepared`

- `Boolean isRunning`

- `Boolean isReady`


## Methods

- `Boolean get_isMultiplayer()`

- `String get_actId()`

- `Void OnGameQuit()`

- `Boolean _CheckGameRealStart()`

- `Void _UpdateRound()`

- `Void _UnregisterEnemy(UInt32)`

- `Void _CheckRoundFinish()`

- `Void _FinishRound(EnemyDuelRoundResult)`

- `IEnumerator _CleanMapForNextRound(EnemyDuelRoundResult)`

- `Void _OnReceiveRoundBet()`

- `Void _OnReceiveRoundSettle()`

- `Void _FinishAllUnitsOnRoundEnd()`

- `Void _PreprocessOnWaveWillStart()`

- `Void _DoClearOnWaveWillStart()`

- `Void _TriggerNpcFastForward()`

- `Void _UnloadPool()`

- `Boolean get_isInPause()`

- `Void SetPaused(Boolean)`

- `Void SetPrepared()`

- `Void SetReady()`

- `Void SetPlaying()`

- `Void SetUnstable()`

- `Boolean NextFrame(Boolean)`

- `Void ApplyAction(EnemyDuelServiceAction)`

- `Void _ApplyOprt_Character(EnemyDuelServiceAction)`

- `Void OnRoundChanged(EnemyDuelBattleStatus)`

- `Void OnStateChanged(EnemyDuelBattleStatus)`

- `Void _ResetRandomSeed(EnemyDuelBattleStatus)`

- `Boolean get_isPrepared()`

- `Boolean get_isRunning()`

- `Boolean get_isReady()`

- `Void SendBetRequest(String, EnemyDuelChoiceSide, Boolean, Boolean)`

- `Void SendEmojiRequest(String, String)`

- `Void SendQuitRequest()`

- `Void _SendRoundSettleRequest(EnemyDuelRoundResult)`

- `Void _OnReceiveGameFinish()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_PreprocessLevelData(LevelData)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Boolean <>xLuaBaseProxy_get_allowManualTick()`

- `Boolean <>xLuaBaseProxy_get_HookGetNextWave()`

- `Boolean <>xLuaBaseProxy_get_allowPoolManagerUnload()`

- `Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean, out)`

- `Boolean <>xLuaBaseProxy_TryGetNextWaveIndexInGameMode(out)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_OnEnemyFinished(Enemy, FinishReason)`

- `Void <>xLuaBaseProxy_FinishGame(Action`2, GameResult, Boolean)`

- `Object <>xLuaBaseProxy_GetActMeta()`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyDuelGameMode : DefaultGameMode, IEnemyDuelGameMode, IGameMode, IHotfixable
{
	private InternalState m_state; // 0x20
	private FP m_roundTime; // 0x28
	private Int32 m_roundIndex; // 0x30
	private Int32 m_waveSafeTime; // 0x34
	private EnemyDuelInput m_inputData; // 0x38
	private ActivityEnemyDuelData m_actData; // 0x40
	private ActivityEnemyDuelModeData m_modeData; // 0x48
	private String m_subModeID; // 0x50
	private Boolean m_isMultiPlayer; // 0x58
	private readonly List`1 m_teamRight; // 0x60
	private readonly List`1 m_teamLeft; // 0x68
	private String m_actId; // 0x70
	private String m_sceneId; // 0x78
	private Boolean m_isGiveUp; // 0x80
	private Boolean m_canWaveFinish; // 0x81
	private readonly EnemyDuelWaveManager m_waveManager; // 0x88
	private readonly EnemyDuelPlayerManager m_playerManager; // 0x90
	private readonly FrameData m_frameData; // 0x98
	private CoroutineId m_coroutine; // 0xa0
	private const Int32 MULTI_PLAYER_MODE_INIT_INDEX; // 0x0
	private const Single WIN_WAIT_TIME; // 0x0
	private EnemyDuelServiceGameState m_roundState; // 0xb0
	private Boolean m_isInPause; // 0xb4
	private static DelegateBridge __Hotfix0_get_isMultiplayer; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_get_instance; // 0x10
	private static DelegateBridge __Hotfix0_get_actId; // 0x18
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_PreprocessLevelData; // 0x30
	private static DelegateBridge __Hotfix0_Tick; // 0x38
	private static DelegateBridge __Hotfix0_get_allowManualTick; // 0x40
	private static DelegateBridge __Hotfix0_get_HookGetNextWave; // 0x48
	private static DelegateBridge __Hotfix0_get_allowPoolManagerUnload; // 0x50
	private static DelegateBridge __Hotfix0_TryHookCheckWaveNotFinish; // 0x58
	private static DelegateBridge __Hotfix0_TryGetNextWaveIndexInGameMode; // 0x60
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x68
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x70
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x78
	private static DelegateBridge __Hotfix0_FinishGame; // 0x80
	private static DelegateBridge __Hotfix0_GetActMeta; // 0x88
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x90
	private static DelegateBridge __Hotfix0_OnGameQuit; // 0x98
	private static DelegateBridge __Hotfix0__CheckGameRealStart; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateRound; // 0xa8
	private static DelegateBridge __Hotfix0__GetHostEnemyByUid; // 0xb0
	private static DelegateBridge __Hotfix0__UnregisterEnemy; // 0xb8
	private static DelegateBridge __Hotfix0__CheckRoundFinish; // 0xc0
	private static DelegateBridge __Hotfix0__FinishRound; // 0xc8
	private static DelegateBridge __Hotfix0__CleanMapForNextRound; // 0xd0
	private static DelegateBridge __Hotfix0__OnReceiveRoundBet; // 0xd8
	private static DelegateBridge __Hotfix0__OnReceiveRoundSettle; // 0xe0
	private static DelegateBridge __Hotfix0__FinishAllUnitsOnRoundEnd; // 0xe8
	private static DelegateBridge __Hotfix0__PreprocessOnWaveWillStart; // 0xf0
	private static DelegateBridge __Hotfix0__DoClearOnWaveWillStart; // 0xf8
	private static DelegateBridge __Hotfix0__TriggerNpcFastForward; // 0x100
	private static DelegateBridge __Hotfix0__UnloadPool; // 0x108
	private static DelegateBridge __Hotfix0_get_isInPause; // 0x110
	private static DelegateBridge __Hotfix0_SetPaused; // 0x118
	private static DelegateBridge __Hotfix0_SetPrepared; // 0x120
	private static DelegateBridge __Hotfix0_SetReady; // 0x128
	private static DelegateBridge __Hotfix0_SetPlaying; // 0x130
	private static DelegateBridge __Hotfix0_SetUnstable; // 0x138
	private static DelegateBridge __Hotfix0_NextFrame; // 0x140
	private static DelegateBridge __Hotfix0_ApplyAction; // 0x148
	private static DelegateBridge __Hotfix0__ApplyOprt_Character; // 0x150
	private static DelegateBridge __Hotfix0_OnRoundChanged; // 0x158
	private static DelegateBridge __Hotfix0_OnStateChanged; // 0x160
	private static DelegateBridge __Hotfix0__ResetRandomSeed; // 0x168
	private static DelegateBridge __Hotfix0_get_isPrepared; // 0x170
	private static DelegateBridge __Hotfix0_get_isRunning; // 0x178
	private static DelegateBridge __Hotfix0_get_isReady; // 0x180
	private static DelegateBridge __Hotfix0_SendBetRequest; // 0x188
	private static DelegateBridge __Hotfix0_SendEmojiRequest; // 0x190
	private static DelegateBridge __Hotfix0_SendQuitRequest; // 0x198
	private static DelegateBridge __Hotfix0__SendRoundSettleRequest; // 0x1a0
	private static DelegateBridge __Hotfix0__OnReceiveGameFinish; // 0x1a8

	public Boolean isMultiplayer { get; }
	public static EnemyDuelGameMode instance { get; }
	public String actId { get; }
	public override GameModeType gameModeType { get; }
	public override Boolean allowManualTick { get; }
	public override Boolean HookGetNextWave { get; }
	public override Boolean allowPoolManagerUnload { get; }
	public Boolean isInPause { get; }
	public Boolean isPrepared { get; }
	public Boolean isRunning { get; }
	public Boolean isReady { get; }

	// RVA: 0x1cccf5c VA: 0x75942e4f5c
	public Boolean get_isMultiplayer() { }
	// RVA: 0x1cccfc4 VA: 0x75942e4fc4
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1ccd1d4 VA: 0x75942e51d4
	public static EnemyDuelGameMode get_instance() { }
	// RVA: 0x1ccd2b4 VA: 0x75942e52b4
	public String get_actId() { }
	// RVA: 0x1ccd31c VA: 0x75942e531c
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1ccd384 VA: 0x75942e5384
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1ccd6b8 VA: 0x75942e56b8
	public override Void PreprocessLevelData(LevelData levelData) { }
	// RVA: 0x1ccd7b8 VA: 0x75942e57b8
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1ccda00 VA: 0x75942e5a00
	public override Boolean get_allowManualTick() { }
	// RVA: 0x1ccda68 VA: 0x75942e5a68
	public override Boolean get_HookGetNextWave() { }
	// RVA: 0x1ccdad0 VA: 0x75942e5ad0
	public override Boolean get_allowPoolManagerUnload() { }
	// RVA: 0x1ccdb38 VA: 0x75942e5b38
	public override Boolean TryHookCheckWaveNotFinish(Boolean schedulerResult, out Boolean result) { }
	// RVA: 0x1ccdc6c VA: 0x75942e5c6c
	public override Boolean TryGetNextWaveIndexInGameMode(out Int32 index) { }
	// RVA: 0x1ccdd3c VA: 0x75942e5d3c
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1ccdf1c VA: 0x75942e5f1c
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cce0d0 VA: 0x75942e60d0
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1cce714 VA: 0x75942e6714
	public override Void FinishGame(Action`2 gameOverCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1cce7e8 VA: 0x75942e67e8
	public override Object GetActMeta() { }
	// RVA: 0x1cce8d0 VA: 0x75942e68d0
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cce968 VA: 0x75942e6968
	public Void OnGameQuit() { }
	// RVA: 0x1ccdbe8 VA: 0x75942e5be8
	private Boolean _CheckGameRealStart() { }
	// RVA: 0x1ccd87c VA: 0x75942e587c
	private Void _UpdateRound() { }
	// RVA: 0x1cce2a8 VA: 0x75942e62a8
	private static Unit _GetHostEnemyByUid(UInt32 hostUid) { }
	// RVA: 0x1cce614 VA: 0x75942e6614
	private Void _UnregisterEnemy(UInt32 uid) { }
	// RVA: 0x1cceb48 VA: 0x75942e6b48
	private Void _CheckRoundFinish() { }
	// RVA: 0x1ccec1c VA: 0x75942e6c1c
	private Void _FinishRound(EnemyDuelRoundResult result) { }
	// RVA: 0x1ccee00 VA: 0x75942e6e00
	private IEnumerator _CleanMapForNextRound(EnemyDuelRoundResult result) { }
	// RVA: 0x1cceec4 VA: 0x75942e6ec4
	private Void _OnReceiveRoundBet() { }
	// RVA: 0x1ccef58 VA: 0x75942e6f58
	private Void _OnReceiveRoundSettle() { }
	// RVA: 0x1ccf104 VA: 0x75942e7104
	private Void _FinishAllUnitsOnRoundEnd() { }
	// RVA: 0x1ccde60 VA: 0x75942e5e60
	private Void _PreprocessOnWaveWillStart() { }
	// RVA: 0x1ccf510 VA: 0x75942e7510
	private Void _DoClearOnWaveWillStart() { }
	// RVA: 0x1ccea18 VA: 0x75942e6a18
	private Void _TriggerNpcFastForward() { }
	// RVA: 0x1ccfc30 VA: 0x75942e7c30
	private Void _UnloadPool() { }
	// RVA: 0x1ccfcfc VA: 0x75942e7cfc
	public Boolean get_isInPause() { }
	// RVA: 0x1ccfd64 VA: 0x75942e7d64
	public Void SetPaused(Boolean isPaused) { }
	// RVA: 0x1cceadc VA: 0x75942e6adc
	public Void SetPrepared() { }
	// RVA: 0x1ccfe30 VA: 0x75942e7e30
	public Void SetReady() { }
	// RVA: 0x1ccfe9c VA: 0x75942e7e9c
	public Void SetPlaying() { }
	// RVA: 0x1ccff08 VA: 0x75942e7f08
	public Void SetUnstable() { }
	// RVA: 0x1ccff9c VA: 0x75942e7f9c
	public Boolean NextFrame(Boolean additional) { }
	// RVA: 0x1cd009c VA: 0x75942e809c
	public Void ApplyAction(EnemyDuelServiceAction action) { }
	// RVA: 0x1cd013c VA: 0x75942e813c
	private Void _ApplyOprt_Character(EnemyDuelServiceAction oprt) { }
	// RVA: 0x1cd01bc VA: 0x75942e81bc
	public Void OnRoundChanged(EnemyDuelBattleStatus status) { }
	// RVA: 0x1cd0460 VA: 0x75942e8460
	public Void OnStateChanged(EnemyDuelBattleStatus status) { }
	// RVA: 0x1cd0300 VA: 0x75942e8300
	private Void _ResetRandomSeed(EnemyDuelBattleStatus status) { }
	// RVA: 0x1cd067c VA: 0x75942e867c
	public Boolean get_isPrepared() { }
	// RVA: 0x1cd06ec VA: 0x75942e86ec
	public Boolean get_isRunning() { }
	// RVA: 0x1cd075c VA: 0x75942e875c
	public Boolean get_isReady() { }
	// RVA: 0x1cd07cc VA: 0x75942e87cc
	public Void SendBetRequest(String playerId, EnemyDuelChoiceSide side, Boolean isPlayer, Boolean isAllIn) { }
	// RVA: 0x1cd08c4 VA: 0x75942e88c4
	public Void SendEmojiRequest(String emojiGroup, String emojiId) { }
	// RVA: 0x1cd099c VA: 0x75942e899c
	public Void SendQuitRequest() { }
	// RVA: 0x1cd0a38 VA: 0x75942e8a38
	private Void _SendRoundSettleRequest(EnemyDuelRoundResult result) { }
	// RVA: 0x1cd05d0 VA: 0x75942e85d0
	private Void _OnReceiveGameFinish() { }
	// RVA: 0x1cd0b1c VA: 0x75942e8b1c
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cd0b24 VA: 0x75942e8b24
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cd0b2c VA: 0x75942e8b2c
	private Void <>xLuaBaseProxy_PreprocessLevelData(LevelData P0) { }
	// RVA: 0x1cd0b34 VA: 0x75942e8b34
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cd0b3c VA: 0x75942e8b3c
	private Boolean <>xLuaBaseProxy_get_allowManualTick() { }
	// RVA: 0x1cd0b44 VA: 0x75942e8b44
	private Boolean <>xLuaBaseProxy_get_HookGetNextWave() { }
	// RVA: 0x1cd0b4c VA: 0x75942e8b4c
	private Boolean <>xLuaBaseProxy_get_allowPoolManagerUnload() { }
	// RVA: 0x1cd0b54 VA: 0x75942e8b54
	private Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean P0, out Boolean P1) { }
	// RVA: 0x1cd0b60 VA: 0x75942e8b60
	private Boolean <>xLuaBaseProxy_TryGetNextWaveIndexInGameMode(out Int32 P0) { }
	// RVA: 0x1cd0b68 VA: 0x75942e8b68
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cd0b70 VA: 0x75942e8b70
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1cd0b78 VA: 0x75942e8b78
	private Void <>xLuaBaseProxy_OnEnemyFinished(Enemy P0, FinishReason P1) { }
	// RVA: 0x1cd0b80 VA: 0x75942e8b80
	private Void <>xLuaBaseProxy_FinishGame(Action`2 P0, GameResult P1, Boolean P2) { }
	// RVA: 0x1cd0b8c VA: 0x75942e8b8c
	private Object <>xLuaBaseProxy_GetActMeta() { }
	// RVA: 0x1cd0b94 VA: 0x75942e8b94
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
}
```