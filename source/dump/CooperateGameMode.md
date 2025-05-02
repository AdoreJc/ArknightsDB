# CooperateGameMode

**Namespace:** ` `


## Fields

- `Boolean blockWaveFinished`

- `Int32 restingTime`

- `Boolean skipRestStage`

- `CooperateSubMode m_curSubModeManager`

- `UInt32 m_lastUpdatedDummyMoveFrame`

- `Character m_cachedDummy`

- `GridPosition m_cachedDummyGrid`

- `Direction m_cachedDummyDirection`

- `Effect m_cachedDummyEffect`

- `InternalState m_state`

- `InternalSpeedType m_speed`

- `InternalSpeedType m_cachedSpeed`

- `SubGameModeType m_subGameModeType`

- `CooperatePreProcessor m_processor`

- `Boolean m_isResting`

- `Int32 m_playerSkipRestingMask`

- `CooperateUIPlugin m_cooperateUIPlugin`

- `DefaultWaveHandler m_waveHandler`

- `Boolean m_playerInCostRequest`

- `Boolean m_playerInPauseRequest`

- `Boolean m_speedUp`

- `Boolean m_mateSpeedUp`

- `Boolean m_isGiveUp`

- `CooperateGuideOutPut m_guideOutPut`

- `OnLineType m_onLineType`

- `OnLineType m_mateOnLineType`

- `Boolean m_isSpeedChange`

- `Int32 m_giveCost`

- `Int32 m_receiveCost`

- `CooperateCommonGlobalBuff m_commonGBuff`


## Properties

- `Boolean isPrepared`

- `Boolean isRunning`

- `Boolean isUnstable`

- `Boolean isPlaying`

- `Boolean m_isQuit`

- `Boolean m_mateIsQuit`

- `SubGameModeType subGameModeType`

- `Boolean isResting`

- `Boolean isSpeedUp`

- `InternalState state`

- `Boolean isFail`

- `CooperateGuideOutPut guideOutPut`

- `CooperateNormalModeManager normalMgr`

- `CooperateDefenceModeManager defenceMgr`

- `CooperateFootballModeManager footballMgr`

- `Boolean playerInPauseRequest`

- `Boolean isInPause`

- `Boolean playerInCostRequest`

- `Boolean isGiveUp`

- `CooperatePreProcessor coopProcessor`


## Methods

- `Void OnFootballManualTick(FP)`

- `Void InitFootball(Vector2, FootballEnemy)`

- `Void LandFootball(Vector2, Boolean)`

- `Void OnAllyHoldFootball(FP, Tile, PlayerSide)`

- `Int32 GetGoal(SideTypeIndex)`

- `Void OnScoreAGoal(SideTypeIndex, Int32)`

- `Void OnScoreFinished()`

- `Boolean get_isPrepared()`

- `Boolean get_isRunning()`

- `Boolean get_isUnstable()`

- `Boolean get_isPlaying()`

- `Void SetReady()`

- `Void SetPrepared()`

- `Void SetPlaying()`

- `Void SetUnstable()`

- `Boolean NextFrame(Boolean)`

- `Void _NextFrameInPause()`

- `Void ApplyOprt(PlayerOprtData)`

- `Void _OnRevMapMarkResponse(Object)`

- `Void _ApplyOprt_Character(PlayerOprtData)`

- `Void _ApplyOprt_DummyDragMate(GameMarkData)`

- `Void _FinishDummyWhenDisable()`

- `Void _ApplyOprt_Cost(PlayerOprtData)`

- `Void _ApplyCostOprt_Receive(PlayerSide, Int32)`

- `Void _ApplyCostOprt_Accept(PlayerSide, Int32)`

- `Void _ApplyCostOprt_Refuse(PlayerSide, Int32)`

- `Void _ApplyOprt_Pause(PlayerOprtData)`

- `Void _ApplyPauseOprt_Receive(PlayerSide)`

- `Void _ApplyPauseOprt_Accept(PlayerSide)`

- `Void _ApplyPauseOprt_Refuse(PlayerSide)`

- `Void _ApplyPauseOprt_Resume(PlayerSide)`

- `Void _ApplyOprt_Online(PlayerOprtData)`

- `Void _ApplyOprt_SpeedUp(PlayerOprtData)`

- `Void _SetPlaySpeed(PlayerSide)`

- `Void _ApplyOprt_SkipResting(PlayerSide)`

- `Void SendSpeedUpRequest()`

- `Void SendPauseResponseRequest(Int32)`

- `Void SendCooperatePauseRequest()`

- `Void SendCooperateRequest(PlayerOperator, Int32)`

- `Void _SendDragDummyOprt(Signiture, GridPosition, Direction)`

- `Void _SendOprtCharacter(CharacterAction, Signiture, GridPosition, Direction)`

- `Void DoCostRequestLocal()`

- `Void _HardSetPlayerSpeed(PlayerSide, Boolean)`

- `Void _RefreshSpeed(InternalSpeedType)`

- `Void _SetPauseAndSpeedStateWhenPlayerDie(PlayerSide)`

- `Boolean get_m_isQuit()`

- `Boolean get_m_mateIsQuit()`

- `SubGameModeType get_subGameModeType()`

- `Boolean get_isResting()`

- `Boolean get_isSpeedUp()`

- `InternalState get_state()`

- `Boolean get_isFail()`

- `CooperateGuideOutPut get_guideOutPut()`

- `CooperateNormalModeManager get_normalMgr()`

- `CooperateDefenceModeManager get_defenceMgr()`

- `CooperateFootballModeManager get_footballMgr()`

- `Boolean get_playerInPauseRequest()`

- `Void set_playerInPauseRequest(Boolean)`

- `Boolean get_isInPause()`

- `Boolean get_playerInCostRequest()`

- `Void set_playerInCostRequest(Boolean)`

- `Void set_isGiveUp(Boolean)`

- `Boolean get_isGiveUp()`

- `CooperatePreProcessor get_coopProcessor()`

- `CooperateGuideOutPut FetchMultiGuideOutPut()`

- `Int32 GetHpForGameCheck()`

- `IEnumerator OnBeforeWaveStart()`

- `Void MakePlayerCharacterRevive(PlayerSide)`

- `Boolean OnBeforeEnemyReachExit(Enemy)`

- `Boolean ReplaceActionKey(String)`

- `Void RecordDefenceBossStatus(FP, FP)`

- `FP GetDefenceBossDamageTaking()`

- `Boolean IsFootballMode()`

- `Boolean IsDefenceMode()`

- `Boolean IsNormalMode()`

- `Void _RegisterEventListener()`

- `CooperateSubMode _CreateSubModeManager()`

- `Void _OnCharacterUseSkill(Object)`

- `Void _MakePlayerCharacterDying(PlayerSide)`

- `Void _CollectModifier(Object)`

- `Void IgnorePauseRequest()`

- `Void ResumePause()`

- `FP GetPlayerReviveTimePeriod()`

- `FP GetPlayerReviveTimeRemainingTime()`

- `CooperateIdentityInfo GetIdentityInfo()`

- `Int32 _GetPlayerDeployCharCnt(ProfessionCategory)`

- `Void _LogPlayerDataOnFinishGame()`

- `Int32 GetCurLevel(PlayerSide)`

- `Void UpgradePlayerBuffLevel(Int32)`

- `Boolean CheckLastWave()`

- `Boolean RegistStageBuff(ObjectPtr`1)`

- `Void DoPlayerResting()`

- `Void OnRestingFinished()`

- `Single FindMaxDistance()`

- `Void AddSharedEnemyKey(String)`

- `Boolean CheckContainsEnemy(String)`

- `Void ResetTargetEnemies(String)`

- `Boolean CheckPlayerDead(PlayerSide)`

- `Boolean <>xLuaBaseProxy_get_allowManualTick()`

- `Boolean <>xLuaBaseProxy_get_isOnline()`

- `Boolean <>xLuaBaseProxy_get_isLargeMap()`

- `Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition()`

- `Boolean <>xLuaBaseProxy_get_isSupportSlowMotion()`

- `BattleOutlineConfig <>xLuaBaseProxy_get_outlineConfig()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Boolean <>xLuaBaseProxy_get_HookGetNextWave()`

- `Boolean <>xLuaBaseProxy_Hook_OnDummyDragging()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_StartGame(Action)`

- `Boolean <>xLuaBaseProxy_HookPlayerOp_Withdraw(Character)`

- `Boolean <>xLuaBaseProxy_HookPlayerOp_Spawn(UInt32, Direction, Tile)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_OnDummyTouchedToTile(Character, Tile, Vector3)`

- `Void <>xLuaBaseProxy_OnDummySetBodyAndFaceDirection(Character, Direction)`

- `Boolean <>xLuaBaseProxy_HookPlayerOp_TrigSkill(Character)`

- `SpeedLevel <>xLuaBaseProxy_HookSpeedLevel(SpeedLevel)`

- `Void <>xLuaBaseProxy_OnCardSpawned(Card)`

- `Void <>xLuaBaseProxy_OnCardListChanged(Card)`

- `Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition, Tile, Direction, Boolean, Boolean, BattleCharacterData, PlayerSide)`

- `Void <>xLuaBaseProxy_PreprocessPlayerData(List`1)`

- `Void <>xLuaBaseProxy_PreprocessRuneInput(IRuneDataHolder)`

- `Void <>xLuaBaseProxy_OnPlayerLifeToZero(PlayerSide)`

- `Void <>xLuaBaseProxy_FinishGame(Action`2, GameResult, Boolean)`

- `Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean, out)`

- `String <>xLuaBaseProxy_GetModeTileEffect(Tile)`

- `Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData)`

- `Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref)`

- `Void <>xLuaBaseProxy_OnEnemyReachExit(Enemy, Tile)`

- `Boolean <>xLuaBaseProxy_TryShowTileInfoToast(Tile, out)`

- `Boolean <>xLuaBaseProxy_TryGetNextWaveIndexInGameMode(out)`

- `Boolean <>xLuaBaseProxy_CheckRenderInvisible(Entity, BattleRenderInvisibleMask)`

- `Boolean <>xLuaBaseProxy_IsMultiplayerLocal()`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `DefaultWaveHandler <>xLuaBaseProxy_get_waveHandler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CooperateGameMode : DefaultGameMode, IMultiplayerGameMode, IGameMode, IHotfixable
{
	private const String FORTRESS_FIXER_KEY; // 0x0
	private static readonly BattleOutlineConfig MULTIV2_CONFIG; // 0x0
	public Boolean blockWaveFinished; // 0x20
	public Int32 restingTime; // 0x24
	public Boolean skipRestStage; // 0x28
	public readonly List`1 sideSharedEnemyKeys; // 0x30
	private CooperateSubMode m_curSubModeManager; // 0x38
	private readonly CooperateNormalModeManager m_normalManager; // 0x40
	private readonly CooperateFootballModeManager m_footballManager; // 0x48
	private readonly CooperateDefenceModeManager m_defenceManager; // 0x50
	private readonly FrameData m_frameData; // 0x58
	private UInt32 m_lastUpdatedDummyMoveFrame; // 0x60
	private Character m_cachedDummy; // 0x68
	private GridPosition m_cachedDummyGrid; // 0x70
	private Direction m_cachedDummyDirection; // 0x78
	private Effect m_cachedDummyEffect; // 0x80
	private InternalState m_state; // 0x88
	private InternalSpeedType m_speed; // 0x8c
	private InternalSpeedType m_cachedSpeed; // 0x90
	private SubGameModeType m_subGameModeType; // 0x94
	private CooperatePreProcessor m_processor; // 0x98
	private Boolean m_isResting; // 0xa0
	private Int32 m_playerSkipRestingMask; // 0xa4
	private CooperateUIPlugin m_cooperateUIPlugin; // 0xa8
	private DefaultWaveHandler m_waveHandler; // 0xb0
	private Boolean m_playerInCostRequest; // 0xb8
	private Boolean m_playerInPauseRequest; // 0xb9
	private Boolean m_speedUp; // 0xba
	private Boolean m_mateSpeedUp; // 0xbb
	private Boolean m_isGiveUp; // 0xbc
	private CooperateGuideOutPut m_guideOutPut; // 0xc0
	private OnLineType m_onLineType; // 0xc8
	private OnLineType m_mateOnLineType; // 0xcc
	private Boolean m_isSpeedChange; // 0xd0
	private readonly ListDict`2 m_playerDamageMelee; // 0xd8
	private readonly ListDict`2 m_playerDamageRange; // 0xe0
	private readonly ListDict`2 m_playerTakeDamage; // 0xe8
	private readonly ListDict`2 m_playerHeal; // 0xf0
	private readonly ListDict`2 m_playerDieTime; // 0xf8
	private readonly ListDict`2 m_playerSkill; // 0x100
	private readonly ListDict`2 m_lifePointReduce; // 0x108
	private readonly Dictionary`2 m_characterDeploy; // 0x110
	private Int32 m_giveCost; // 0x118
	private Int32 m_receiveCost; // 0x11c
	private CooperateCommonGlobalBuff m_commonGBuff; // 0x120
	private readonly ListDict`2 m_playerDead; // 0x128
	private readonly List`1 m_globalBuffs; // 0x130
	private static DelegateBridge __Hotfix0_OnFootballManualTick; // 0x18
	private static DelegateBridge __Hotfix0_InitFootball; // 0x20
	private static DelegateBridge __Hotfix0_LandFootball; // 0x28
	private static DelegateBridge __Hotfix0_OnAllyHoldFootball; // 0x30
	private static DelegateBridge __Hotfix0_GetGoal; // 0x38
	private static DelegateBridge __Hotfix0_OnScoreAGoal; // 0x40
	private static DelegateBridge __Hotfix0_OnScoreFinished; // 0x48
	private static DelegateBridge __Hotfix0_get_isPrepared; // 0x50
	private static DelegateBridge __Hotfix0_get_isRunning; // 0x58
	private static DelegateBridge __Hotfix0_get_isUnstable; // 0x60
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x68
	private static DelegateBridge __Hotfix0_SetReady; // 0x70
	private static DelegateBridge __Hotfix0_SetPrepared; // 0x78
	private static DelegateBridge __Hotfix0_SetPlaying; // 0x80
	private static DelegateBridge __Hotfix0_SetUnstable; // 0x88
	private static DelegateBridge __Hotfix0_NextFrame; // 0x90
	private static DelegateBridge __Hotfix0__NextFrameInPause; // 0x98
	private static DelegateBridge __Hotfix0_ApplyOprt; // 0xa0
	private static DelegateBridge __Hotfix0__OnRevMapMarkResponse; // 0xa8
	private static DelegateBridge __Hotfix0__ApplyOprt_Character; // 0xb0
	private static DelegateBridge __Hotfix0__ApplyOprt_DummyDragMate; // 0xb8
	private static DelegateBridge __Hotfix0__FinishDummyWhenDisable; // 0xc0
	private static DelegateBridge __Hotfix0__ApplyOprt_Cost; // 0xc8
	private static DelegateBridge __Hotfix0__ApplyCostOprt_Receive; // 0xd0
	private static DelegateBridge __Hotfix0__ApplyCostOprt_Accept; // 0xd8
	private static DelegateBridge __Hotfix0__ApplyCostOprt_Refuse; // 0xe0
	private static DelegateBridge __Hotfix0__ApplyOprt_Pause; // 0xe8
	private static DelegateBridge __Hotfix0__ApplyPauseOprt_Receive; // 0xf0
	private static DelegateBridge __Hotfix0__ApplyPauseOprt_Accept; // 0xf8
	private static DelegateBridge __Hotfix0__ApplyPauseOprt_Refuse; // 0x100
	private static DelegateBridge __Hotfix0__ApplyPauseOprt_Resume; // 0x108
	private static DelegateBridge __Hotfix0__ApplyOprt_Online; // 0x110
	private static DelegateBridge __Hotfix0__ApplyOprt_SpeedUp; // 0x118
	private static DelegateBridge __Hotfix0__SetPlaySpeed; // 0x120
	private static DelegateBridge __Hotfix0__ApplyOprt_SkipResting; // 0x128
	private static DelegateBridge __Hotfix0_SendSpeedUpRequest; // 0x130
	private static DelegateBridge __Hotfix0_SendPauseResponseRequest; // 0x138
	private static DelegateBridge __Hotfix0_SendCooperatePauseRequest; // 0x140
	private static DelegateBridge __Hotfix0_SendCooperateRequest; // 0x148
	private static DelegateBridge __Hotfix0__SendDragDummyOprt; // 0x150
	private static DelegateBridge __Hotfix0__SendOprtCharacter; // 0x158
	private static DelegateBridge __Hotfix0_DoCostRequestLocal; // 0x160
	private static DelegateBridge __Hotfix0__HardSetPlayerSpeed; // 0x168
	private static DelegateBridge __Hotfix0__RefreshSpeed; // 0x170
	private static DelegateBridge __Hotfix0__SetPauseAndSpeedStateWhenPlayerDie; // 0x178
	private static DelegateBridge __Hotfix0_get_m_isQuit; // 0x180
	private static DelegateBridge __Hotfix0_get_m_mateIsQuit; // 0x188
	private static DelegateBridge __Hotfix0_get_subGameModeType; // 0x190
	private static DelegateBridge __Hotfix0_get_isResting; // 0x198
	private static DelegateBridge __Hotfix0_get_isSpeedUp; // 0x1a0
	private static DelegateBridge __Hotfix0_get_state; // 0x1a8
	private static DelegateBridge __Hotfix0_get_isFail; // 0x1b0
	private static DelegateBridge __Hotfix0_get_guideOutPut; // 0x1b8
	private static DelegateBridge __Hotfix0_get_normalMgr; // 0x1c0
	private static DelegateBridge __Hotfix0_get_defenceMgr; // 0x1c8
	private static DelegateBridge __Hotfix0_get_footballMgr; // 0x1d0
	private static DelegateBridge __Hotfix0_get_playerInPauseRequest; // 0x1d8
	private static DelegateBridge __Hotfix0_set_playerInPauseRequest; // 0x1e0
	private static DelegateBridge __Hotfix0_get_isInPause; // 0x1e8
	private static DelegateBridge __Hotfix0_get_playerInCostRequest; // 0x1f0
	private static DelegateBridge __Hotfix0_set_playerInCostRequest; // 0x1f8
	private static DelegateBridge __Hotfix0_set_isGiveUp; // 0x200
	private static DelegateBridge __Hotfix0_get_isGiveUp; // 0x208
	private static DelegateBridge __Hotfix0_get_coopProcessor; // 0x210
	private static DelegateBridge __Hotfix0_FetchMultiGuideOutPut; // 0x218
	private static DelegateBridge __Hotfix0_GetHpForGameCheck; // 0x220
	private static DelegateBridge __Hotfix0_OnBeforeWaveStart; // 0x228
	private static DelegateBridge __Hotfix0_MakePlayerCharacterRevive; // 0x230
	private static DelegateBridge __Hotfix0_OnBeforeEnemyReachExit; // 0x238
	private static DelegateBridge __Hotfix0_ReplaceActionKey; // 0x240
	private static DelegateBridge __Hotfix0_RecordDefenceBossStatus; // 0x248
	private static DelegateBridge __Hotfix0_GetDefenceBossDamageTaking; // 0x250
	private static DelegateBridge __Hotfix0_IsFootballMode; // 0x258
	private static DelegateBridge __Hotfix0_IsDefenceMode; // 0x260
	private static DelegateBridge __Hotfix0_IsNormalMode; // 0x268
	private static DelegateBridge _c__Hotfix0_ctor; // 0x270
	private static DelegateBridge __Hotfix0_get_allowManualTick; // 0x278
	private static DelegateBridge __Hotfix0_get_isOnline; // 0x280
	private static DelegateBridge __Hotfix0_get_isLargeMap; // 0x288
	private static DelegateBridge __Hotfix0_get_hasExtraBuildCondition; // 0x290
	private static DelegateBridge __Hotfix0_get_isSupportSlowMotion; // 0x298
	private static DelegateBridge __Hotfix0_get_outlineConfig; // 0x2a0
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x2a8
	private static DelegateBridge __Hotfix0_get_HookGetNextWave; // 0x2b0
	private static DelegateBridge __Hotfix0_Hook_OnDummyDragging; // 0x2b8
	private static DelegateBridge __Hotfix0_Init; // 0x2c0
	private static DelegateBridge __Hotfix0__RegisterEventListener; // 0x2c8
	private static DelegateBridge __Hotfix0__CreateSubModeManager; // 0x2d0
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x2d8
	private static DelegateBridge __Hotfix0_StartGame; // 0x2e0
	private static DelegateBridge __Hotfix0_HookPlayerOp_Withdraw; // 0x2e8
	private static DelegateBridge __Hotfix0_HookPlayerOp_Spawn; // 0x2f0
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x2f8
	private static DelegateBridge __Hotfix0_OnDummyTouchedToTile; // 0x300
	private static DelegateBridge __Hotfix0_OnDummySetBodyAndFaceDirection; // 0x308
	private static DelegateBridge __Hotfix0_HookPlayerOp_TrigSkill; // 0x310
	private static DelegateBridge __Hotfix0_HookSpeedLevel; // 0x318
	private static DelegateBridge __Hotfix0_OnCardSpawned; // 0x320
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x328
	private static DelegateBridge __Hotfix0_CheckCardReadyToSpawn; // 0x330
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x338
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x340
	private static DelegateBridge __Hotfix0_PreprocessPlayerData; // 0x348
	private static DelegateBridge __Hotfix0_PreprocessRuneInput; // 0x350
	private static DelegateBridge __Hotfix0_OnPlayerLifeToZero; // 0x358
	private static DelegateBridge __Hotfix0_FinishGame; // 0x360
	private static DelegateBridge __Hotfix0_TryHookCheckWaveNotFinish; // 0x368
	private static DelegateBridge __Hotfix0_GetModeTileEffect; // 0x370
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0x378
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x380
	private static DelegateBridge __Hotfix0_OnEnemyReachExit; // 0x388
	private static DelegateBridge __Hotfix0_TryShowTileInfoToast; // 0x390
	private static DelegateBridge __Hotfix0_GatherGlobalBuffs; // 0x398
	private static DelegateBridge __Hotfix0_TryGetNextWaveIndexInGameMode; // 0x3a0
	private static DelegateBridge __Hotfix0_CheckRenderInvisible; // 0x3a8
	private static DelegateBridge __Hotfix0__OnCharacterUseSkill; // 0x3b0
	private static DelegateBridge __Hotfix0__MakePlayerCharacterDying; // 0x3b8
	private static DelegateBridge __Hotfix0__CollectModifier; // 0x3c0
	private static DelegateBridge __Hotfix0_IsMultiplayerLocal; // 0x3c8
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x3d0
	private static DelegateBridge __Hotfix0_Tick; // 0x3d8
	private static DelegateBridge __Hotfix0_IgnorePauseRequest; // 0x3e0
	private static DelegateBridge __Hotfix0_ResumePause; // 0x3e8
	private static DelegateBridge __Hotfix0_GatherPreloadAssets; // 0x3f0
	private static DelegateBridge __Hotfix0_GetPlayerReviveTimePeriod; // 0x3f8
	private static DelegateBridge __Hotfix0_GetPlayerReviveTimeRemainingTime; // 0x400
	private static DelegateBridge __Hotfix0_GetIdentityInfo; // 0x408
	private static DelegateBridge __Hotfix0__GetPlayerDeployCharCnt; // 0x410
	private static DelegateBridge __Hotfix0__LogPlayerDataOnFinishGame; // 0x418
	private static DelegateBridge __Hotfix0_get_waveHandler; // 0x420
	private static DelegateBridge __Hotfix0_GetCurLevel; // 0x428
	private static DelegateBridge __Hotfix0_UpgradePlayerBuffLevel; // 0x430
	private static DelegateBridge __Hotfix0_CheckLastWave; // 0x438
	private static DelegateBridge __Hotfix0_RegistStageBuff; // 0x440
	private static DelegateBridge __Hotfix0_DoPlayerResting; // 0x448
	private static DelegateBridge __Hotfix0_OnRestingFinished; // 0x450
	private static DelegateBridge __Hotfix0_FindMaxDistance; // 0x458
	private static DelegateBridge __Hotfix0_AddSharedEnemyKey; // 0x460
	private static DelegateBridge __Hotfix0_CheckContainsEnemy; // 0x468
	private static DelegateBridge __Hotfix0_ResetTargetEnemies; // 0x470
	private static DelegateBridge __Hotfix0_CheckPlayerDead; // 0x478

	public Boolean isPrepared { get; }
	public Boolean isRunning { get; }
	public Boolean isUnstable { get; }
	public Boolean isPlaying { get; }
	private Boolean m_isQuit { get; }
	private Boolean m_mateIsQuit { get; }
	public SubGameModeType subGameModeType { get; }
	public Boolean isResting { get; }
	public Boolean isSpeedUp { get; }
	public InternalState state { get; }
	public Boolean isFail { get; }
	public CooperateGuideOutPut guideOutPut { get; }
	public CooperateNormalModeManager normalMgr { get; }
	public CooperateDefenceModeManager defenceMgr { get; }
	public CooperateFootballModeManager footballMgr { get; }
	public Boolean playerInPauseRequest { get; set; }
	public Boolean isInPause { get; }
	public Boolean playerInCostRequest { get; set; }
	public Boolean isGiveUp { get; set; }
	public CooperatePreProcessor coopProcessor { get; }
	public override Boolean allowManualTick { get; }
	public override Boolean isOnline { get; }
	public override Boolean isLargeMap { get; }
	public override Boolean hasExtraBuildCondition { get; }
	public override Boolean isSupportSlowMotion { get; }
	public override BattleOutlineConfig outlineConfig { get; }
	public override GameModeType gameModeType { get; }
	public override Boolean HookGetNextWave { get; }
	public override DefaultWaveHandler waveHandler { get; }

	// RVA: 0x1cb9760 VA: 0x75942d1760
	public Void OnFootballManualTick(FP deltaTime) { }
	// RVA: 0x1cb99a0 VA: 0x75942d19a0
	public Void InitFootball(Vector2 position, FootballEnemy enemy) { }
	// RVA: 0x1cb9b24 VA: 0x75942d1b24
	public Void LandFootball(Vector2 position, Boolean force) { }
	// RVA: 0x1cb9eac VA: 0x75942d1eac
	public Void OnAllyHoldFootball(FP holdingFootballRemainTime, Tile tile, PlayerSide playerSide) { }
	// RVA: 0x1cba1f0 VA: 0x75942d21f0
	public Int32 GetGoal(SideTypeIndex side) { }
	// RVA: 0x1cba324 VA: 0x75942d2324
	public Void OnScoreAGoal(SideTypeIndex sideTypeIndex, Int32 value) { }
	// RVA: 0x1cba4e8 VA: 0x75942d24e8
	public Void OnScoreFinished() { }
	// RVA: 0x1cba87c VA: 0x75942d287c
	public Boolean get_isPrepared() { }
	// RVA: 0x1cba8fc VA: 0x75942d28fc
	public Boolean get_isRunning() { }
	// RVA: 0x1cba990 VA: 0x75942d2990
	public Boolean get_isUnstable() { }
	// RVA: 0x1cbaa10 VA: 0x75942d2a10
	public Boolean get_isPlaying() { }
	// RVA: 0x1cbaa90 VA: 0x75942d2a90
	public Void SetReady() { }
	// RVA: 0x1cbab0c VA: 0x75942d2b0c
	public Void SetPrepared() { }
	// RVA: 0x1cbab88 VA: 0x75942d2b88
	public Void SetPlaying() { }
	// RVA: 0x1cbac04 VA: 0x75942d2c04
	public Void SetUnstable() { }
	// RVA: 0x1cbac80 VA: 0x75942d2c80
	public Boolean NextFrame(Boolean additional) { }
	// RVA: 0x1cbae64 VA: 0x75942d2e64
	private Void _NextFrameInPause() { }
	// RVA: 0x1cbaee0 VA: 0x75942d2ee0
	public Void ApplyOprt(PlayerOprtData oprt) { }
	// RVA: 0x1cbb76c VA: 0x75942d376c
	private Void _OnRevMapMarkResponse(Object arg) { }
	// RVA: 0x1cbb024 VA: 0x75942d3024
	private Void _ApplyOprt_Character(PlayerOprtData oprt) { }
	// RVA: 0x1cbb894 VA: 0x75942d3894
	private Void _ApplyOprt_DummyDragMate(GameMarkData oprt) { }
	// RVA: 0x1cbbe54 VA: 0x75942d3e54
	private Void _FinishDummyWhenDisable() { }
	// RVA: 0x1cbb1a4 VA: 0x75942d31a4
	private Void _ApplyOprt_Cost(PlayerOprtData oprt) { }
	// RVA: 0x1cbbfe8 VA: 0x75942d3fe8
	private Void _ApplyCostOprt_Receive(PlayerSide side, Int32 status) { }
	// RVA: 0x1cbc118 VA: 0x75942d4118
	private Void _ApplyCostOprt_Accept(PlayerSide side, Int32 status) { }
	// RVA: 0x1cbc35c VA: 0x75942d435c
	private Void _ApplyCostOprt_Refuse(PlayerSide side, Int32 status) { }
	// RVA: 0x1cbb2a4 VA: 0x75942d32a4
	private Void _ApplyOprt_Pause(PlayerOprtData oprt) { }
	// RVA: 0x1cbc5c8 VA: 0x75942d45c8
	private Void _ApplyPauseOprt_Receive(PlayerSide side) { }
	// RVA: 0x1cbc778 VA: 0x75942d4778
	private Void _ApplyPauseOprt_Accept(PlayerSide side) { }
	// RVA: 0x1cbc864 VA: 0x75942d4864
	private Void _ApplyPauseOprt_Refuse(PlayerSide side) { }
	// RVA: 0x1cbc944 VA: 0x75942d4944
	private Void _ApplyPauseOprt_Resume(PlayerSide side) { }
	// RVA: 0x1cbb540 VA: 0x75942d3540
	private Void _ApplyOprt_Online(PlayerOprtData oprt) { }
	// RVA: 0x1cbb4a8 VA: 0x75942d34a8
	private Void _ApplyOprt_SpeedUp(PlayerOprtData oprt) { }
	// RVA: 0x1cbcb38 VA: 0x75942d4b38
	private Void _SetPlaySpeed(PlayerSide side) { }
	// RVA: 0x1cbb3bc VA: 0x75942d33bc
	private Void _ApplyOprt_SkipResting(PlayerSide side) { }
	// RVA: 0x1cbd070 VA: 0x75942d5070
	public Void SendSpeedUpRequest() { }
	// RVA: 0x1cbd200 VA: 0x75942d5200
	public Void SendPauseResponseRequest(Int32 param) { }
	// RVA: 0x1cbd2bc VA: 0x75942d52bc
	public Void SendCooperatePauseRequest() { }
	// RVA: 0x1cbd108 VA: 0x75942d5108
	public Void SendCooperateRequest(PlayerOperator opt, Int32 status) { }
	// RVA: 0x1cbd36c VA: 0x75942d536c
	private Void _SendDragDummyOprt(Signiture sig, GridPosition grid, Direction dir) { }
	// RVA: 0x1cbd464 VA: 0x75942d5464
	private Void _SendOprtCharacter(CharacterAction oprt, Signiture sig, GridPosition grid, Direction dir) { }
	// RVA: 0x1cbd5ac VA: 0x75942d55ac
	public Void DoCostRequestLocal() { }
	// RVA: 0x1cbcdb8 VA: 0x75942d4db8
	private Void _HardSetPlayerSpeed(PlayerSide side, Boolean speedOn) { }
	// RVA: 0x1cbcc8c VA: 0x75942d4c8c
	private Void _RefreshSpeed(InternalSpeedType speedType) { }
	// RVA: 0x1cbd7f0 VA: 0x75942d57f0
	private Void _SetPauseAndSpeedStateWhenPlayerDie(PlayerSide side) { }
	// RVA: 0x1cbc4c0 VA: 0x75942d44c0
	private Boolean get_m_isQuit() { }
	// RVA: 0x1cbc544 VA: 0x75942d4544
	private Boolean get_m_mateIsQuit() { }
	// RVA: 0x1cbd8ac VA: 0x75942d58ac
	public SubGameModeType get_subGameModeType() { }
	// RVA: 0x1cbd778 VA: 0x75942d5778
	public Boolean get_isResting() { }
	// RVA: 0x1cbd924 VA: 0x75942d5924
	public Boolean get_isSpeedUp() { }
	// RVA: 0x1cbd9a4 VA: 0x75942d59a4
	public InternalState get_state() { }
	// RVA: 0x1cbda1c VA: 0x75942d5a1c
	public Boolean get_isFail() { }
	// RVA: 0x1cbdaa0 VA: 0x75942d5aa0
	public CooperateGuideOutPut get_guideOutPut() { }
	// RVA: 0x1cbdb18 VA: 0x75942d5b18
	public CooperateNormalModeManager get_normalMgr() { }
	// RVA: 0x1cbdb90 VA: 0x75942d5b90
	public CooperateDefenceModeManager get_defenceMgr() { }
	// RVA: 0x1cbdc08 VA: 0x75942d5c08
	public CooperateFootballModeManager get_footballMgr() { }
	// RVA: 0x1cbc9fc VA: 0x75942d49fc
	public Boolean get_playerInPauseRequest() { }
	// RVA: 0x1cbca74 VA: 0x75942d4a74
	public Void set_playerInPauseRequest(Boolean value) { }
	// RVA: 0x1cbad98 VA: 0x75942d2d98
	public Boolean get_isInPause() { }
	// RVA: 0x1cbc448 VA: 0x75942d4448
	public Boolean get_playerInCostRequest() { }
	// RVA: 0x1cbdc80 VA: 0x75942d5c80
	public Void set_playerInCostRequest(Boolean value) { }
	// RVA: 0x1cbdd10 VA: 0x75942d5d10
	public Void set_isGiveUp(Boolean value) { }
	// RVA: 0x1cbdda0 VA: 0x75942d5da0
	public Boolean get_isGiveUp() { }
	// RVA: 0x1cbde18 VA: 0x75942d5e18
	public CooperatePreProcessor get_coopProcessor() { }
	// RVA: 0x1cbded8 VA: 0x75942d5ed8
	public CooperateGuideOutPut FetchMultiGuideOutPut() { }
	// RVA: 0x1cbe208 VA: 0x75942d6208
	public Int32 GetHpForGameCheck() { }
	// RVA: 0x1cbe290 VA: 0x75942d6290
	public IEnumerator OnBeforeWaveStart() { }
	// RVA: 0x1cbe374 VA: 0x75942d6374
	public Void MakePlayerCharacterRevive(PlayerSide side) { }
	// RVA: 0x1cbe924 VA: 0x75942d6924
	public Boolean OnBeforeEnemyReachExit(Enemy enemy) { }
	// RVA: 0x1cbeaec VA: 0x75942d6aec
	public Boolean ReplaceActionKey(String key) { }
	// RVA: 0x1cbec04 VA: 0x75942d6c04
	public Void RecordDefenceBossStatus(FP hp, FP maxHp) { }
	// RVA: 0x1cbed2c VA: 0x75942d6d2c
	public FP GetDefenceBossDamageTaking() { }
	// RVA: 0x1cbea60 VA: 0x75942d6a60
	public Boolean IsFootballMode() { }
	// RVA: 0x1cbedfc VA: 0x75942d6dfc
	public Boolean IsDefenceMode() { }
	// RVA: 0x1cbee88 VA: 0x75942d6e88
	public Boolean IsNormalMode() { }
	// RVA: 0x1cbef14 VA: 0x75942d6f14
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cbfa88 VA: 0x75942d7a88
	public override Boolean get_allowManualTick() { }
	// RVA: 0x1cbfb00 VA: 0x75942d7b00
	public override Boolean get_isOnline() { }
	// RVA: 0x1cbfb78 VA: 0x75942d7b78
	public override Boolean get_isLargeMap() { }
	// RVA: 0x1cbfbf0 VA: 0x75942d7bf0
	public override Boolean get_hasExtraBuildCondition() { }
	// RVA: 0x1cbfc74 VA: 0x75942d7c74
	public override Boolean get_isSupportSlowMotion() { }
	// RVA: 0x1cbfce8 VA: 0x75942d7ce8
	public override BattleOutlineConfig get_outlineConfig() { }
	// RVA: 0x1cbfda4 VA: 0x75942d7da4
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cbfe1c VA: 0x75942d7e1c
	public override Boolean get_HookGetNextWave() { }
	// RVA: 0x1cbfea4 VA: 0x75942d7ea4
	public override Boolean Hook_OnDummyDragging() { }
	// RVA: 0x1cbff34 VA: 0x75942d7f34
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cc0224 VA: 0x75942d8224
	private Void _RegisterEventListener() { }
	// RVA: 0x1cc0168 VA: 0x75942d8168
	private CooperateSubMode _CreateSubModeManager() { }
	// RVA: 0x1cc046c VA: 0x75942d846c
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cc052c VA: 0x75942d852c
	public override Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1cc05d4 VA: 0x75942d85d4
	public override Boolean HookPlayerOp_Withdraw(Character character) { }
	// RVA: 0x1cc0738 VA: 0x75942d8738
	public override Boolean HookPlayerOp_Spawn(UInt32 uniqueId, Direction direction, Tile tile) { }
	// RVA: 0x1cc08d8 VA: 0x75942d88d8
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cc0b88 VA: 0x75942d8b88
	public override Void OnDummyTouchedToTile(Character character, Tile tile, Vector3 dummyPos) { }
	// RVA: 0x1cc0e94 VA: 0x75942d8e94
	public override Void OnDummySetBodyAndFaceDirection(Character character, Direction direction) { }
	// RVA: 0x1cc1000 VA: 0x75942d9000
	public override Boolean HookPlayerOp_TrigSkill(Character character) { }
	// RVA: 0x1cc1158 VA: 0x75942d9158
	public override SpeedLevel HookSpeedLevel(SpeedLevel originSpeedLevel) { }
	// RVA: 0x1cc12c4 VA: 0x75942d92c4
	public override Void OnCardSpawned(Card card) { }
	// RVA: 0x1cc1478 VA: 0x75942d9478
	public override Void OnCardListChanged(Card card) { }
	// RVA: 0x1cc15f4 VA: 0x75942d95f4
	public override Boolean CheckCardReadyToSpawn(Card card) { }
	// RVA: 0x1cc1788 VA: 0x75942d9788
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cc1860 VA: 0x75942d9860
	public override Boolean CheckBuildable(BuildCondition buildCondition, Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1cc1a1c VA: 0x75942d9a1c
	public override Void PreprocessPlayerData(List`1 dataList) { }
	// RVA: 0x1cc1fc0 VA: 0x75942d9fc0
	public override Void PreprocessRuneInput(IRuneDataHolder runeInput) { }
	// RVA: 0x1cc22c0 VA: 0x75942da2c0
	public override Void OnPlayerLifeToZero(PlayerSide side) { }
	// RVA: 0x1cc2af4 VA: 0x75942daaf4
	public override Void FinishGame(Action`2 gameOverCallback, GameResult result, Boolean silent) { }
	// RVA: 0x1cc3078 VA: 0x75942db078
	public override Boolean TryHookCheckWaveNotFinish(Boolean schedulerResult, out Boolean result) { }
	// RVA: 0x1cc3448 VA: 0x75942db448
	public override String GetModeTileEffect(Tile tile) { }
	// RVA: 0x1cc35b4 VA: 0x75942db5b4
	public override Void OnWaveWillFinish(WaveData waveData) { }
	// RVA: 0x1cc3654 VA: 0x75942db654
	public override Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cc3908 VA: 0x75942db908
	public override Void OnEnemyReachExit(Enemy enemy, Tile cacheTile) { }
	// RVA: 0x1cc3ecc VA: 0x75942dbecc
	public override Boolean TryShowTileInfoToast(Tile tile, out Int32 id) { }
	// RVA: 0x1cc41dc VA: 0x75942dc1dc
	public override List`1 GatherGlobalBuffs() { }
	// RVA: 0x1cc4470 VA: 0x75942dc470
	public override Boolean TryGetNextWaveIndexInGameMode(out Int32 index) { }
	// RVA: 0x1cc4510 VA: 0x75942dc510
	public override Boolean CheckRenderInvisible(Entity entity, BattleRenderInvisibleMask mask) { }
	// RVA: 0x1cc46b0 VA: 0x75942dc6b0
	private Void _OnCharacterUseSkill(Object param) { }
	// RVA: 0x1cc255c VA: 0x75942da55c
	private Void _MakePlayerCharacterDying(PlayerSide side) { }
	// RVA: 0x1cc4870 VA: 0x75942dc870
	private Void _CollectModifier(Object obj) { }
	// RVA: 0x1cc4fa8 VA: 0x75942dcfa8
	public override Boolean IsMultiplayerLocal() { }
	// RVA: 0x1cc503c VA: 0x75942dd03c
	public override Void OnPostInit() { }
	// RVA: 0x1cc50c0 VA: 0x75942dd0c0
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cc5184 VA: 0x75942dd184
	public Void IgnorePauseRequest() { }
	// RVA: 0x1cc5238 VA: 0x75942dd238
	public Void ResumePause() { }
	// RVA: 0x1cc52c4 VA: 0x75942dd2c4
	public static Dictionary`2 GatherPreloadAssets() { }
	// RVA: 0x1cc55ec VA: 0x75942dd5ec
	public FP GetPlayerReviveTimePeriod() { }
	// RVA: 0x1cc56e4 VA: 0x75942dd6e4
	public FP GetPlayerReviveTimeRemainingTime() { }
	// RVA: 0x1cc57dc VA: 0x75942dd7dc
	public CooperateIdentityInfo GetIdentityInfo() { }
	// RVA: 0x1cc5994 VA: 0x75942dd994
	private Int32 _GetPlayerDeployCharCnt(ProfessionCategory profession) { }
	// RVA: 0x1cc2d70 VA: 0x75942dad70
	private Void _LogPlayerDataOnFinishGame() { }
	// RVA: 0x1cc5ba0 VA: 0x75942ddba0
	public override DefaultWaveHandler get_waveHandler() { }
	// RVA: 0x1cc5c60 VA: 0x75942ddc60
	public Int32 GetCurLevel(PlayerSide side) { }
	// RVA: 0x1cc5cec VA: 0x75942ddcec
	public Void UpgradePlayerBuffLevel(Int32 count) { }
	// RVA: 0x1cc5d74 VA: 0x75942ddd74
	public Boolean CheckLastWave() { }
	// RVA: 0x1cc5ec0 VA: 0x75942ddec0
	public Boolean RegistStageBuff(ObjectPtr`1 buff) { }
	// RVA: 0x1cc60a0 VA: 0x75942de0a0
	public Void DoPlayerResting() { }
	// RVA: 0x1cbcf68 VA: 0x75942d4f68
	public Void OnRestingFinished() { }
	// RVA: 0x1cc66e0 VA: 0x75942de6e0
	public Single FindMaxDistance() { }
	// RVA: 0x1cc67fc VA: 0x75942de7fc
	public Void AddSharedEnemyKey(String enemyKey) { }
	// RVA: 0x1cc6944 VA: 0x75942de944
	public Boolean CheckContainsEnemy(String enemyId) { }
	// RVA: 0x1cc6a7c VA: 0x75942dea7c
	public Void ResetTargetEnemies(String enemyId) { }
	// RVA: 0x1cc6c68 VA: 0x75942dec68
	public Boolean CheckPlayerDead(PlayerSide side) { }
	// RVA: 0x1cc6d18 VA: 0x75942ded18
	private static Void .cctor() { }
	// RVA: 0x1cc6dd4 VA: 0x75942dedd4
	private Boolean <>xLuaBaseProxy_get_allowManualTick() { }
	// RVA: 0x1cc6ddc VA: 0x75942deddc
	private Boolean <>xLuaBaseProxy_get_isOnline() { }
	// RVA: 0x1cc6de4 VA: 0x75942dede4
	private Boolean <>xLuaBaseProxy_get_isLargeMap() { }
	// RVA: 0x1cc6dec VA: 0x75942dedec
	private Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition() { }
	// RVA: 0x1cc6df4 VA: 0x75942dedf4
	private Boolean <>xLuaBaseProxy_get_isSupportSlowMotion() { }
	// RVA: 0x1cc6dfc VA: 0x75942dedfc
	private BattleOutlineConfig <>xLuaBaseProxy_get_outlineConfig() { }
	// RVA: 0x1cc6e30 VA: 0x75942dee30
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cc6e38 VA: 0x75942dee38
	private Boolean <>xLuaBaseProxy_get_HookGetNextWave() { }
	// RVA: 0x1cc6e40 VA: 0x75942dee40
	private Boolean <>xLuaBaseProxy_Hook_OnDummyDragging() { }
	// RVA: 0x1cc6e48 VA: 0x75942dee48
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cc6e50 VA: 0x75942dee50
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cc6e58 VA: 0x75942dee58
	private Void <>xLuaBaseProxy_StartGame(Action P0) { }
	// RVA: 0x1cc6e60 VA: 0x75942dee60
	private Boolean <>xLuaBaseProxy_HookPlayerOp_Withdraw(Character P0) { }
	// RVA: 0x1cc6e68 VA: 0x75942dee68
	private Boolean <>xLuaBaseProxy_HookPlayerOp_Spawn(UInt32 P0, Direction P1, Tile P2) { }
	// RVA: 0x1cc6e70 VA: 0x75942dee70
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1cc6e78 VA: 0x75942dee78
	private Void <>xLuaBaseProxy_OnDummyTouchedToTile(Character P0, Tile P1, Vector3 P2) { }
	// RVA: 0x1cc6e80 VA: 0x75942dee80
	private Void <>xLuaBaseProxy_OnDummySetBodyAndFaceDirection(Character P0, Direction P1) { }
	// RVA: 0x1cc6e88 VA: 0x75942dee88
	private Boolean <>xLuaBaseProxy_HookPlayerOp_TrigSkill(Character P0) { }
	// RVA: 0x1cc6e90 VA: 0x75942dee90
	private SpeedLevel <>xLuaBaseProxy_HookSpeedLevel(SpeedLevel P0) { }
	// RVA: 0x1cc6e98 VA: 0x75942dee98
	private Void <>xLuaBaseProxy_OnCardSpawned(Card P0) { }
	// RVA: 0x1cc6ea0 VA: 0x75942deea0
	private Void <>xLuaBaseProxy_OnCardListChanged(Card P0) { }
	// RVA: 0x1cc6ea8 VA: 0x75942deea8
	private Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card P0) { }
	// RVA: 0x1cc6eb0 VA: 0x75942deeb0
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cc6eb8 VA: 0x75942deeb8
	private Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition P0, Tile P1, Direction P2, Boolean P3, Boolean P4, BattleCharacterData P5, PlayerSide P6) { }
	// RVA: 0x1cc6f38 VA: 0x75942def38
	private Void <>xLuaBaseProxy_PreprocessPlayerData(List`1 P0) { }
	// RVA: 0x1cc6f40 VA: 0x75942def40
	private Void <>xLuaBaseProxy_PreprocessRuneInput(IRuneDataHolder P0) { }
	// RVA: 0x1cc6f48 VA: 0x75942def48
	private Void <>xLuaBaseProxy_OnPlayerLifeToZero(PlayerSide P0) { }
	// RVA: 0x1cc6f50 VA: 0x75942def50
	private Void <>xLuaBaseProxy_FinishGame(Action`2 P0, GameResult P1, Boolean P2) { }
	// RVA: 0x1cc6f5c VA: 0x75942def5c
	private Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean P0, out Boolean P1) { }
	// RVA: 0x1cc6f68 VA: 0x75942def68
	private String <>xLuaBaseProxy_GetModeTileEffect(Tile P0) { }
	// RVA: 0x1cc6f70 VA: 0x75942def70
	private Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData P0) { }
	// RVA: 0x1cc6f78 VA: 0x75942def78
	private Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref Modifier P0) { }
	// RVA: 0x1cc6f80 VA: 0x75942def80
	private Void <>xLuaBaseProxy_OnEnemyReachExit(Enemy P0, Tile P1) { }
	// RVA: 0x1cc6f88 VA: 0x75942def88
	private Boolean <>xLuaBaseProxy_TryShowTileInfoToast(Tile P0, out Int32 P1) { }
	// RVA: 0x1cc6f90 VA: 0x75942def90
	private List`1 <>xLuaBaseProxy_GatherGlobalBuffs() { }
	// RVA: 0x1cc6f98 VA: 0x75942def98
	private Boolean <>xLuaBaseProxy_TryGetNextWaveIndexInGameMode(out Int32 P0) { }
	// RVA: 0x1cc6fa0 VA: 0x75942defa0
	private Boolean <>xLuaBaseProxy_CheckRenderInvisible(Entity P0, BattleRenderInvisibleMask P1) { }
	// RVA: 0x1cc6fa8 VA: 0x75942defa8
	private Boolean <>xLuaBaseProxy_IsMultiplayerLocal() { }
	// RVA: 0x1cc6fb0 VA: 0x75942defb0
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x1cc6fb8 VA: 0x75942defb8
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cc6fc0 VA: 0x75942defc0
	private DefaultWaveHandler <>xLuaBaseProxy_get_waveHandler() { }
}
```