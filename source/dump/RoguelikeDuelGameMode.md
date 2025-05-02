# RoguelikeDuelGameMode

**Namespace:** ` `


## Fields

- `Int32 m_battleAreaBegin`

- `Int32 m_battleAreaEnd`

- `FP m_maxPlayTime`

- `FP m_chooseTime`

- `GameStage m_gameStage`

- `DuelMode m_duelMode`

- `DuelBattleResult m_duelBattleResult`

- `Int32 m_chosenGroupId`

- `String m_withdrawCardName`

- `Int32 m_refreshLimitTimes`

- `Int32 m_currentRefreshTimes`

- `Boolean m_receiveUIBtnStartConfirm`

- `Boolean m_chosenSync`

- `RoguelikeDuelSchedulerPreprocessor m_schedulerPreprocessor`


## Properties

- `DuelBattleResult duelBattleResult`

- `Int32 deployedCharacterCount`

- `Int32 chosenEnemyCount`

- `Int32 duelModeToInt`

- `GameStage gameStage`


## Methods

- `DuelBattleResult get_duelBattleResult()`

- `Int32 get_deployedCharacterCount()`

- `Int32 get_chosenEnemyCount()`

- `Int32 get_duelModeToInt()`

- `GameStage get_gameStage()`

- `Void OnDuelBattleStart()`

- `Void WithDrawAllCharacters()`

- `Void KillAllEnemies()`

- `Void SetDuelMode(DuelMode)`

- `Void AddChosenTrapCol(Int32)`

- `Void SetChosenGroupId(Int32)`

- `Void SetChosenSync(Boolean)`

- `Boolean CheckConvertBattleStage()`

- `Void ModifyPlaceAreaData(Blackboard)`

- `Void AddChosenEnemy(Enemy)`

- `Void AddChosenCharacter(String)`

- `Void ReceiveUIBtnStartConfirm()`

- `Void _OnTileClicked(Object)`

- `Void _ShowEnemyToast(Enemy, String)`

- `Void _HideCardExceptChosenCharacters()`

- `Void _SummonChosenEnemies()`

- `Void _StartSummonEnemy(String, String)`

- `Void _SetCardCostZero(Card)`

- `Void _SetRespawnTimeAndMultCntZero(Card)`

- `Void _RemoveCardBuff()`

- `Void _CheckGameFinish()`

- `Void _AddDuelGameInfoLog(Int32, String)`

- `Int32 GetMaxTime()`

- `Int32 GetRemainingTime()`

- `Void SetChooseTime()`

- `Boolean CheckCanRefresh()`

- `Void RefreshEnemy()`

- `Boolean CheckInRefreshStatus()`

- `Boolean ExtraStartCheck()`

- `Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean, out)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Void <>xLuaBaseProxy_OnEnemyFinished(Enemy, FinishReason)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_PreProcessDeckCards(IList`1)`

- `Void <>xLuaBaseProxy_OnCardListChanged(Card)`

- `Void <>xLuaBaseProxy_OnCharacterFinished(Character, FinishReason)`

- `Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition, Tile, Direction, Boolean, Boolean, BattleCharacterData, PlayerSide)`

- `PlayerBattleRank <>xLuaBaseProxy_GetBattleCompleteRank()`

- `Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeDuelGameMode : RoguelikeGameMode
{
	public const String DUEL_UI_PLUGIN_PATH; // 0x0
	public const String DUEL_CAMERA_PLUGIN_PATH; // 0x0
	private const String LOG_LOSS; // 0x0
	private const String LOG_DRAW; // 0x0
	private const String LOG_WIN; // 0x0
	private const String SINGLE_ROUTE; // 0x0
	private const String DOUBLE_ROUTE_1; // 0x0
	private const String DOUBLE_ROUTE_2; // 0x0
	private const String GROUP_ID; // 0x0
	private const String REFRESH_LIMIT_TIME; // 0x0
	private const String COST_ZERO_CARD_BUFF_KEY; // 0x0
	private const String RESPAWN_ZERO_CARD_BUFF_KEY; // 0x0
	private const Int32 COST_DELTA; // 0x0
	private const Single RESPAWN_TIME_DELTA; // 0x0
	private const Int32 GROUP_NUM; // 0x0
	private Int32 m_battleAreaBegin; // 0x50
	private Int32 m_battleAreaEnd; // 0x54
	private FP m_maxPlayTime; // 0x58
	private FP m_chooseTime; // 0x60
	private GameStage m_gameStage; // 0x68
	private DuelMode m_duelMode; // 0x6c
	private DuelBattleResult m_duelBattleResult; // 0x70
	private List`1 m_chosenTrapCols; // 0x78
	private Int32 m_chosenGroupId; // 0x80
	private String m_withdrawCardName; // 0x88
	private Int32 m_refreshLimitTimes; // 0x90
	private Int32 m_currentRefreshTimes; // 0x94
	private Boolean m_receiveUIBtnStartConfirm; // 0x98
	private Boolean m_chosenSync; // 0x99
	private RoguelikeDuelSchedulerPreprocessor m_schedulerPreprocessor; // 0xa0
	private List`1 m_chosenEnemyList; // 0xa8
	private List`1 m_chosenCharacterList; // 0xb0
	private static DelegateBridge __Hotfix0_get_duelBattleResult; // 0x0
	private static DelegateBridge __Hotfix0_get_deployedCharacterCount; // 0x8
	private static DelegateBridge __Hotfix0_get_chosenEnemyCount; // 0x10
	private static DelegateBridge __Hotfix0_get_duelModeToInt; // 0x18
	private static DelegateBridge __Hotfix0_get_gameStage; // 0x20
	private static DelegateBridge __Hotfix0_get_hasExtraBuildCondition; // 0x28
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0_TryHookCheckWaveNotFinish; // 0x40
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x48
	private static DelegateBridge __Hotfix0_Tick; // 0x50
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x58
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x60
	private static DelegateBridge __Hotfix0_PreProcessDeckCards; // 0x68
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x70
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x78
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x80
	private static DelegateBridge __Hotfix0_GetBattleCompleteRank; // 0x88
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98
	private static DelegateBridge __Hotfix0_OnDuelBattleStart; // 0xa0
	private static DelegateBridge __Hotfix0_WithDrawAllCharacters; // 0xa8
	private static DelegateBridge __Hotfix0_KillAllEnemies; // 0xb0
	private static DelegateBridge __Hotfix0_SetDuelMode; // 0xb8
	private static DelegateBridge __Hotfix0_AddChosenTrapCol; // 0xc0
	private static DelegateBridge __Hotfix0_SetChosenGroupId; // 0xc8
	private static DelegateBridge __Hotfix0_SetChosenSync; // 0xd0
	private static DelegateBridge __Hotfix0_CheckConvertBattleStage; // 0xd8
	private static DelegateBridge __Hotfix0_ModifyPlaceAreaData; // 0xe0
	private static DelegateBridge __Hotfix0_AddChosenEnemy; // 0xe8
	private static DelegateBridge __Hotfix0_AddChosenCharacter; // 0xf0
	private static DelegateBridge __Hotfix0_ReceiveUIBtnStartConfirm; // 0xf8
	private static DelegateBridge __Hotfix0__OnTileClicked; // 0x100
	private static DelegateBridge __Hotfix0__ShowEnemyToast; // 0x108
	private static DelegateBridge __Hotfix0__HideCardExceptChosenCharacters; // 0x110
	private static DelegateBridge __Hotfix0__SummonChosenEnemies; // 0x118
	private static DelegateBridge __Hotfix0__StartSummonEnemy; // 0x120
	private static DelegateBridge __Hotfix0__SetCardCostZero; // 0x128
	private static DelegateBridge __Hotfix0__SetRespawnTimeAndMultCntZero; // 0x130
	private static DelegateBridge __Hotfix0__RemoveCardBuff; // 0x138
	private static DelegateBridge __Hotfix0__CheckGameFinish; // 0x140
	private static DelegateBridge __Hotfix0__AddDuelGameInfoLog; // 0x148
	private static DelegateBridge __Hotfix0_GetMaxTime; // 0x150
	private static DelegateBridge __Hotfix0_GetRemainingTime; // 0x158
	private static DelegateBridge __Hotfix0_SetChooseTime; // 0x160
	private static DelegateBridge __Hotfix0_CheckCanRefresh; // 0x168
	private static DelegateBridge __Hotfix0_RefreshEnemy; // 0x170
	private static DelegateBridge __Hotfix0_CheckInRefreshStatus; // 0x178
	private static DelegateBridge __Hotfix0_ExtraStartCheck; // 0x180

	public DuelBattleResult duelBattleResult { get; }
	public Int32 deployedCharacterCount { get; }
	public Int32 chosenEnemyCount { get; }
	public Int32 duelModeToInt { get; }
	public GameStage gameStage { get; }
	public override Boolean hasExtraBuildCondition { get; }
	public override GameModeType gameModeType { get; }

	// RVA: 0x1cf0700 VA: 0x7594308700
	public DuelBattleResult get_duelBattleResult() { }
	// RVA: 0x1cf0768 VA: 0x7594308768
	public Int32 get_deployedCharacterCount() { }
	// RVA: 0x1cf07e8 VA: 0x75943087e8
	public Int32 get_chosenEnemyCount() { }
	// RVA: 0x1cf0868 VA: 0x7594308868
	public Int32 get_duelModeToInt() { }
	// RVA: 0x1cf08dc VA: 0x75943088dc
	public GameStage get_gameStage() { }
	// RVA: 0x1cf0944 VA: 0x7594308944
	public override Boolean get_hasExtraBuildCondition() { }
	// RVA: 0x1cf09ac VA: 0x75943089ac
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cf0a14 VA: 0x7594308a14
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cf0e40 VA: 0x7594308e40
	public override Boolean TryHookCheckWaveNotFinish(Boolean schedulerResult, out Boolean result) { }
	// RVA: 0x1cf0edc VA: 0x7594308edc
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cf0f44 VA: 0x7594308f44
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cf11a4 VA: 0x75943091a4
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1cf1428 VA: 0x7594309428
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cf16b8 VA: 0x75943096b8
	public override Void PreProcessDeckCards(IList`1 cards) { }
	// RVA: 0x1cf2160 VA: 0x759430a160
	public override Void OnCardListChanged(Card card) { }
	// RVA: 0x1cf22c8 VA: 0x759430a2c8
	public override Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cf24c8 VA: 0x759430a4c8
	public override Boolean CheckBuildable(BuildCondition buildCondition, Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1cf2744 VA: 0x759430a744
	public override PlayerBattleRank GetBattleCompleteRank() { }
	// RVA: 0x1cf27f8 VA: 0x759430a7f8
	public override Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cf2920 VA: 0x759430a920
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cf2ccc VA: 0x759430accc
	public Void OnDuelBattleStart() { }
	// RVA: 0x1cf3534 VA: 0x759430b534
	public Void WithDrawAllCharacters() { }
	// RVA: 0x1cf2e28 VA: 0x759430ae28
	public Void KillAllEnemies() { }
	// RVA: 0x1cf3754 VA: 0x759430b754
	public Void SetDuelMode(DuelMode duelMode) { }
	// RVA: 0x1cf1598 VA: 0x7594309598
	public Void AddChosenTrapCol(Int32 col) { }
	// RVA: 0x1cf37d0 VA: 0x759430b7d0
	public Void SetChosenGroupId(Int32 groupid) { }
	// RVA: 0x1cf384c VA: 0x759430b84c
	public Void SetChosenSync(Boolean flag) { }
	// RVA: 0x1cf38cc VA: 0x759430b8cc
	public Boolean CheckConvertBattleStage() { }
	// RVA: 0x1cf3948 VA: 0x759430b948
	public Void ModifyPlaceAreaData(Blackboard blackboard) { }
	// RVA: 0x1cf3a28 VA: 0x759430ba28
	public Void AddChosenEnemy(Enemy enemy) { }
	// RVA: 0x1cf3b60 VA: 0x759430bb60
	public Void AddChosenCharacter(String charId) { }
	// RVA: 0x1cf3c98 VA: 0x759430bc98
	public Void ReceiveUIBtnStartConfirm() { }
	// RVA: 0x1cf4034 VA: 0x759430c034
	private Void _OnTileClicked(Object args) { }
	// RVA: 0x1cf43f4 VA: 0x759430c3f4
	private Void _ShowEnemyToast(Enemy enemy, String desc) { }
	// RVA: 0x1cf3d18 VA: 0x759430bd18
	private Void _HideCardExceptChosenCharacters() { }
	// RVA: 0x1cf3324 VA: 0x759430b324
	private Void _SummonChosenEnemies() { }
	// RVA: 0x1cf45b0 VA: 0x759430c5b0
	private Void _StartSummonEnemy(String branchId, String enemyId) { }
	// RVA: 0x1cf1e20 VA: 0x7594309e20
	private Void _SetCardCostZero(Card card) { }
	// RVA: 0x1cf1fb8 VA: 0x7594309fb8
	private Void _SetRespawnTimeAndMultCntZero(Card card) { }
	// RVA: 0x1cf3f00 VA: 0x759430bf00
	private Void _RemoveCardBuff() { }
	// RVA: 0x1cf0fd8 VA: 0x7594308fd8
	private Void _CheckGameFinish() { }
	// RVA: 0x1cf12ec VA: 0x75943092ec
	private Void _AddDuelGameInfoLog(Int32 chosenGroup, String gameResult) { }
	// RVA: 0x1cf47d4 VA: 0x759430c7d4
	public Int32 GetMaxTime() { }
	// RVA: 0x1cf4694 VA: 0x759430c694
	public Int32 GetRemainingTime() { }
	// RVA: 0x1cf4868 VA: 0x759430c868
	public Void SetChooseTime() { }
	// RVA: 0x1cf48fc VA: 0x759430c8fc
	public Boolean CheckCanRefresh() { }
	// RVA: 0x1cf4980 VA: 0x759430c980
	public Void RefreshEnemy() { }
	// RVA: 0x1cf49fc VA: 0x759430c9fc
	public Boolean CheckInRefreshStatus() { }
	// RVA: 0x1cf4adc VA: 0x759430cadc
	public Boolean ExtraStartCheck() { }
	// RVA: 0x1cf4bb0 VA: 0x759430cbb0
	private Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition() { }
	// RVA: 0x1cf4bb8 VA: 0x759430cbb8
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cf4c34 VA: 0x759430cc34
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cf4c38 VA: 0x759430cc38
	private Boolean <>xLuaBaseProxy_TryHookCheckWaveNotFinish(Boolean P0, out Boolean P1) { }
	// RVA: 0x1cf4c44 VA: 0x759430cc44
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cf4cd0 VA: 0x759430ccd0
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cf4cd8 VA: 0x759430ccd8
	private Void <>xLuaBaseProxy_OnEnemyFinished(Enemy P0, FinishReason P1) { }
	// RVA: 0x1cf4ce0 VA: 0x759430cce0
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1cf4ce8 VA: 0x759430cce8
	private Void <>xLuaBaseProxy_PreProcessDeckCards(IList`1 P0) { }
	// RVA: 0x1cf4cec VA: 0x759430ccec
	private Void <>xLuaBaseProxy_OnCardListChanged(Card P0) { }
	// RVA: 0x1cf4cf4 VA: 0x759430ccf4
	private Void <>xLuaBaseProxy_OnCharacterFinished(Character P0, FinishReason P1) { }
	// RVA: 0x1cf4cfc VA: 0x759430ccfc
	private Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition P0, Tile P1, Direction P2, Boolean P3, Boolean P4, BattleCharacterData P5, PlayerSide P6) { }
	// RVA: 0x1cf4d7c VA: 0x759430cd7c
	private PlayerBattleRank <>xLuaBaseProxy_GetBattleCompleteRank() { }
	// RVA: 0x1cf4d84 VA: 0x759430cd84
	private Void <>xLuaBaseProxy_OnApplyingGlobalModifier(ref Modifier P0) { }
}
```