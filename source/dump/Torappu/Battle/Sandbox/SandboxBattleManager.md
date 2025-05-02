# SandboxBattleManager

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxInput m_input`

- `SandboxOutput m_output`

- `SandboxGameMode m_gameMode`

- `SandboxLevelDataProcessor m_levelDataProcessor`

- `SandboxBattleDataController m_battleStatusController`

- `SandboxLevelConfig m_levelConfig`

- `SandboxCameraPlugin m_cameraPlugin`

- `HiddenAreaTileListener m_hiddenTileListener`

- `SandboxLevelProgressHelper m_progressHelper`

- `Int32 m_activePage`

- `Int32 m_maxVisibleCnt`

- `Int32 m_maxVisibleCntLimit`

- `UIBattleSandboxItemNotification m_notification`

- `SandboxUIPlugin m_uiPlugin`

- `Boolean hasSpwanedNpc`

- `Int32 m_remainingRacerItemSpace`

- `Boolean m_teamTacticalEffectEnabled`


## Properties

- `SandboxUIPlugin uiPlugin`

- `UIBattleSandboxItemNotification notification`

- `Int32 maxVisibleCnt`

- `Int32 maxVisibleCntLimit`

- `Int32 activePage`

- `String exploredMap`

- `SandboxV2Data configData`

- `SandboxLevelConfig levelConfig`

- `SandboxCameraPlugin cameraPlugin`


## Methods

- `SandboxUIPlugin get_uiPlugin()`

- `UIBattleSandboxItemNotification get_notification()`

- `Void set_notification(UIBattleSandboxItemNotification)`

- `Int32 get_maxVisibleCnt()`

- `Void set_maxVisibleCnt(Int32)`

- `Int32 get_maxVisibleCntLimit()`

- `Void set_maxVisibleCntLimit(Int32)`

- `Int32 get_activePage()`

- `Void set_activePage(Int32)`

- `String get_exploredMap()`

- `Void set_exploredMap(String)`

- `SandboxV2Data get_configData()`

- `SandboxLevelConfig get_levelConfig()`

- `SandboxCameraPlugin get_cameraPlugin()`

- `Void Init(LevelData, BattlePlayerData)`

- `Void OnGameOver(GameResult)`

- `Void OnFetchGameOverOutput()`

- `Void _ParseConfigBlackboard(LevelData)`

- `Void _InitInputStatus()`

- `Void _ParseCameraPlugin(Blackboard)`

- `Void _ParseNpc(Blackboard)`

- `Void _ParseHiddenArea(Blackboard)`

- `Void PostprocessMap(Map)`

- `Void _DoHideTile()`

- `Boolean CheckTileValid(Int32, Int32)`

- `Boolean ShowHiddenAreas(String, Trap)`

- `Boolean _ShowHiddenArea(String, Trap)`

- `Void PreprocessCharacterCard(BattleCharacterData, Character)`

- `Void PreprocessEnemy(EnemyData)`

- `Void OnEnemyBorn(Enemy)`

- `Void PreprocessRuneInput(RuneManager)`

- `Void OnStartGame()`

- `IEnumerator FinalSchedule()`

- `Void TrySummonInsects()`

- `Void PostPreprocessLevel(LevelData)`

- `Void RebuildPageList()`

- `Void RefreshCardListByActivePage()`

- `Void PreprocessPlayerDeckList(ListDict`2)`

- `Boolean CheckCardDeployCountNotOverflow(Card)`

- `Void SwitchPage(Int32)`

- `Void OnCharacterFinished(Character, FinishReason)`

- `Void OnEnemyFinished(Enemy, FinishReason)`

- `Void OnUnitRegistered(Unit)`

- `SchedulerPreprocessor GetSchedulerPreprocessor()`

- `Boolean IsConstructItem(Character)`

- `Boolean IsFactoryTrap(Character)`

- `Boolean IsFactoryTrap(Card)`

- `Boolean IsPlacedItem(Entity)`

- `Int32 GetResCountByID(String, Boolean)`

- `Int32 GetGoldCount(Boolean)`

- `Int32 GetAllRepairCost()`

- `Int32 GetDimensionCoinItemIdCount(Boolean)`

- `Void SandboxEntityDropItem(Entity, ResDropSourceType)`

- `Void SandboxEntityDropItem(Entity, String, Int32)`

- `Void SandboxCollectItem(String, Int32)`

- `Boolean SandboxCollectRacer(Enemy)`

- `Void SandboxBindCollectItemListener(Action`2)`

- `Boolean IsPackedResFull(Entity)`

- `Int32 GetPackedResMaxCount(Entity)`

- `Int32 GetPackedResMaxCount(Card)`

- `Boolean CollectPackedRes(Entity)`

- `Boolean TransferAllPackedRes(Entity, Entity)`

- `Int32 GetTotalPackedResCount(Entity)`

- `Void SandboxAvgCollectItem(String, Int32)`

- `Void SandboxAvgCollectItemList(List`1)`

- `Boolean CheckItemCount(String, Int32, Boolean)`

- `Boolean FetchBossRecordedStatus(String, String, out)`

- `Boolean FetchUniEnemyRecordedStatus(String, out)`

- `Boolean FetchUnitRecordedStatus(SandboxEntityStatusKey, out)`

- `Boolean FetchPlacedItemRecordedStatus(SandboxPlacedItemStatusKey, out)`

- `Void RecordUnitState(SandboxEntityStatusKey, SandboxEntityStatusValue)`

- `Void RecordPlacedItemState(SandboxPlacedItemStatusKey, SandboxPlacedItemStatusValue)`

- `Void RecordUniEnemyState(String, SandboxV2UniEnemyStatus)`

- `Boolean FetchUniEnemyExtraInfo(String, out)`

- `Void RecordBossState(String, String, SandboxRushBossStatus)`

- `Void RecordUsingConstructItem(Character)`

- `Void MarkRushEnemyDead(RushEnemy)`

- `Void MarkRushEnemyReachExit(Enemy)`

- `Boolean ProcessSpecialEnemy(Enemy)`

- `Boolean CheckSpecialUniEnemy(String)`

- `Void ConstructSaveLevelRes()`

- `Void SandboxMarkDeathDetail(String, Int32, EnemyDeathDetailType)`

- `Void SandboxMarkUniDeathDetail(String, UniEnemyDeathDetailType)`

- `Void SandboxLogEnemyEvent(String, String, Int32)`

- `Void SandboxMarkRemoveDeathDetail(String, Int32, EnemyDeathDetailType)`

- `Single GetCompleteProgress()`

- `Boolean IsLevelUnlockConditionComplete()`

- `Boolean CheckConditionKey(String, Int32, Boolean)`

- `Void ModifyCondition(String, Int32)`

- `Boolean CheckFavour(String, Int32, Boolean)`

- `Void AddFavour(String, Int32)`

- `Void AddOutput(String, BattleDialogType)`

- `Boolean MakeReactGacha(String, Boolean, Int32, ref)`

- `Void AddOutputChoice(String, String, BattleDialogType)`

- `String GetFirstSignal(BattleDialogType)`

- `NpcBattleInput GetNpcInputData(String, BattleDialogType)`

- `Void SetNpcFinish(String, BattleDialogType)`

- `Void OverrideRiftId(String)`

- `Void SpawnReactNpcIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxBattleManager : IHotfixable
{
	private SandboxInput m_input; // 0x10
	private SandboxOutput m_output; // 0x18
	private SandboxGameMode m_gameMode; // 0x20
	private SandboxLevelDataProcessor m_levelDataProcessor; // 0x28
	private SandboxBattleDataController m_battleStatusController; // 0x30
	private SandboxLevelConfig m_levelConfig; // 0x38
	private readonly List`1 m_globalBuffs; // 0x40
	private SandboxCameraPlugin m_cameraPlugin; // 0x48
	private Dictionary`2 m_hiddenAreaGraphicKeys; // 0x50
	private Dictionary`2 m_hiddenAreas; // 0x58
	private HiddenAreaTileListener m_hiddenTileListener; // 0x60
	private SandboxLevelProgressHelper m_progressHelper; // 0x68
	private List`1 m_sandboxFactoryTrapUidList; // 0x70
	private HashSet`1 m_sandboxFactoryTrapIds; // 0x78
	private Dictionary`2 m_itemMaxDeployCnt; // 0x80
	private Dictionary`2 m_itemCurrentDeployCnt; // 0x88
	private readonly List`1 m_cardPageList; // 0x90
	private Int32 m_activePage; // 0x98
	private readonly List`1 m_originHiddenList; // 0xa0
	private Int32 m_maxVisibleCnt; // 0xa8
	private Int32 m_maxVisibleCntLimit; // 0xac
	private UIBattleSandboxItemNotification m_notification; // 0xb0
	private SandboxUIPlugin m_uiPlugin; // 0xb8
	private Boolean hasSpwanedNpc; // 0xc0
	private Int32 m_remainingRacerItemSpace; // 0xc4
	private Boolean m_teamTacticalEffectEnabled; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_uiPlugin; // 0x8
	private static DelegateBridge __Hotfix0_get_notification; // 0x10
	private static DelegateBridge __Hotfix0_set_notification; // 0x18
	private static DelegateBridge __Hotfix0_get_maxVisibleCnt; // 0x20
	private static DelegateBridge __Hotfix0_set_maxVisibleCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_maxVisibleCntLimit; // 0x30
	private static DelegateBridge __Hotfix0_set_maxVisibleCntLimit; // 0x38
	private static DelegateBridge __Hotfix0_get_originHiddenList; // 0x40
	private static DelegateBridge __Hotfix0_get_cardPageList; // 0x48
	private static DelegateBridge __Hotfix0_get_activePage; // 0x50
	private static DelegateBridge __Hotfix0_set_activePage; // 0x58
	private static DelegateBridge __Hotfix0_get_charactersWithFoodBuff; // 0x60
	private static DelegateBridge __Hotfix0_get_exploredMap; // 0x68
	private static DelegateBridge __Hotfix0_set_exploredMap; // 0x70
	private static DelegateBridge __Hotfix0_get_configData; // 0x78
	private static DelegateBridge __Hotfix0_get_levelConfig; // 0x80
	private static DelegateBridge __Hotfix0_get_entityStatus; // 0x88
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x98
	private static DelegateBridge __Hotfix0_OnGameOver; // 0xa0
	private static DelegateBridge __Hotfix0_OnFetchGameOverOutput; // 0xa8
	private static DelegateBridge __Hotfix0__ParseConfigBlackboard; // 0xb0
	private static DelegateBridge __Hotfix0__InitInputStatus; // 0xb8
	private static DelegateBridge __Hotfix0__ParseCameraPlugin; // 0xc0
	private static DelegateBridge __Hotfix0__ParseNpc; // 0xc8
	private static DelegateBridge __Hotfix0__ParseHiddenArea; // 0xd0
	private static DelegateBridge __Hotfix0_PostprocessMap; // 0xd8
	private static DelegateBridge __Hotfix0__DoHideTile; // 0xe0
	private static DelegateBridge __Hotfix0_CheckTileValid; // 0xe8
	private static DelegateBridge __Hotfix0_ShowHiddenAreas; // 0xf0
	private static DelegateBridge __Hotfix0__ShowHiddenArea; // 0xf8
	private static DelegateBridge __Hotfix0_PreprocessCharacterCard; // 0x100
	private static DelegateBridge __Hotfix0_PreprocessEnemy; // 0x108
	private static DelegateBridge __Hotfix0_OnEnemyBorn; // 0x110
	private static DelegateBridge __Hotfix0_PreprocessRuneInput; // 0x118
	private static DelegateBridge __Hotfix0_OnStartGame; // 0x120
	private static DelegateBridge __Hotfix0_FinalSchedule; // 0x128
	private static DelegateBridge __Hotfix0_TrySummonInsects; // 0x130
	private static DelegateBridge __Hotfix0_PostPreprocessLevel; // 0x138
	private static DelegateBridge __Hotfix0_RebuildPageList; // 0x140
	private static DelegateBridge __Hotfix0_RefreshCardListByActivePage; // 0x148
	private static DelegateBridge __Hotfix0__CheckIfTeamTacticalCard; // 0x150
	private static DelegateBridge __Hotfix0__RemoveTeamTacticalCard; // 0x158
	private static DelegateBridge __Hotfix0_PreprocessPlayerDeckList; // 0x160
	private static DelegateBridge __Hotfix0_CheckCardDeployCountNotOverflow; // 0x168
	private static DelegateBridge __Hotfix0_SwitchPage; // 0x170
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x178
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x180
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x188
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x190
	private static DelegateBridge __Hotfix0_PreprocessGlobalBuff; // 0x198
	private static DelegateBridge __Hotfix0_IsConstructItem; // 0x1a0
	private static DelegateBridge __Hotfix0_IsFactoryTrap; // 0x1a8
	private static DelegateBridge __Hotfix1_IsFactoryTrap; // 0x1b0
	private static DelegateBridge __Hotfix0_IsPlacedItem; // 0x1b8
	private static DelegateBridge __Hotfix0_GetResCountByID; // 0x1c0
	private static DelegateBridge __Hotfix0_GetGoldCount; // 0x1c8
	private static DelegateBridge __Hotfix0_GetAllRepairCost; // 0x1d0
	private static DelegateBridge __Hotfix0_GetDimensionCoinItemIdCount; // 0x1d8
	private static DelegateBridge __Hotfix0_SandboxEntityPackedItems; // 0x1e0
	private static DelegateBridge __Hotfix0_SandboxEntityDropItem; // 0x1e8
	private static DelegateBridge __Hotfix1_SandboxEntityDropItem; // 0x1f0
	private static DelegateBridge __Hotfix0_SandboxCollectItem; // 0x1f8
	private static DelegateBridge __Hotfix0_SandboxCollectRacer; // 0x200
	private static DelegateBridge __Hotfix0_SandboxBindCollectItemListener; // 0x208
	private static DelegateBridge __Hotfix0_IsPackedResFull; // 0x210
	private static DelegateBridge __Hotfix0_GetPackedResMaxCount; // 0x218
	private static DelegateBridge __Hotfix1_GetPackedResMaxCount; // 0x220
	private static DelegateBridge __Hotfix0_CollectPackedRes; // 0x228
	private static DelegateBridge __Hotfix0_TransferAllPackedRes; // 0x230
	private static DelegateBridge __Hotfix0_GetTotalPackedResCount; // 0x238
	private static DelegateBridge __Hotfix0_SandboxAvgCollectItem; // 0x240
	private static DelegateBridge __Hotfix0_SandboxAvgCollectItemList; // 0x248
	private static DelegateBridge __Hotfix0_CheckItemCount; // 0x250
	private static DelegateBridge __Hotfix0_FetchBossRecordedStatus; // 0x258
	private static DelegateBridge __Hotfix0_FetchUniEnemyRecordedStatus; // 0x260
	private static DelegateBridge __Hotfix0_FetchUnitRecordedStatus; // 0x268
	private static DelegateBridge __Hotfix0_FetchPlacedItemRecordedStatus; // 0x270
	private static DelegateBridge __Hotfix0_RecordUnitState; // 0x278
	private static DelegateBridge __Hotfix0_RecordPlacedItemState; // 0x280
	private static DelegateBridge __Hotfix0_RecordUniEnemyState; // 0x288
	private static DelegateBridge __Hotfix0_FetchUniEnemyExtraInfo; // 0x290
	private static DelegateBridge __Hotfix0_RecordBossState; // 0x298
	private static DelegateBridge __Hotfix0_RecordUsingConstructItem; // 0x2a0
	private static DelegateBridge __Hotfix0_MarkRushEnemyDead; // 0x2a8
	private static DelegateBridge __Hotfix0_MarkRushEnemyReachExit; // 0x2b0
	private static DelegateBridge __Hotfix0_ProcessSpecialEnemy; // 0x2b8
	private static DelegateBridge __Hotfix0_CheckSpecialUniEnemy; // 0x2c0
	private static DelegateBridge __Hotfix0_ConstructSaveLevelRes; // 0x2c8
	private static DelegateBridge __Hotfix0_SandboxMarkDeathDetail; // 0x2d0
	private static DelegateBridge __Hotfix0_SandboxMarkUniDeathDetail; // 0x2d8
	private static DelegateBridge __Hotfix0_SandboxLogEnemyEvent; // 0x2e0
	private static DelegateBridge __Hotfix0_SandboxMarkRemoveDeathDetail; // 0x2e8
	private static DelegateBridge __Hotfix0_GetCompleteProgress; // 0x2f0
	private static DelegateBridge __Hotfix0_IsLevelUnlockConditionComplete; // 0x2f8
	private static DelegateBridge __Hotfix0__GetAvailableCardList; // 0x300
	private static DelegateBridge __Hotfix0_CheckConditionKey; // 0x308
	private static DelegateBridge __Hotfix0_ModifyCondition; // 0x310
	private static DelegateBridge __Hotfix0_CheckFavour; // 0x318
	private static DelegateBridge __Hotfix0_AddFavour; // 0x320
	private static DelegateBridge __Hotfix0_AddOutput; // 0x328
	private static DelegateBridge __Hotfix0_MakeReactGacha; // 0x330
	private static DelegateBridge __Hotfix0_AddOutputChoice; // 0x338
	private static DelegateBridge __Hotfix0_GetFirstSignal; // 0x340
	private static DelegateBridge __Hotfix0_GetNpcInputData; // 0x348
	private static DelegateBridge __Hotfix0_SetNpcFinish; // 0x350
	private static DelegateBridge __Hotfix0_OverrideRiftId; // 0x358
	private static DelegateBridge __Hotfix0_SpawnReactNpcIfNot; // 0x360

	private SandboxUIPlugin uiPlugin { get; }
	public UIBattleSandboxItemNotification notification { get; set; }
	private Int32 maxVisibleCnt { get; set; }
	public Int32 maxVisibleCntLimit { get; set; }
	public List`1 originHiddenList { get; }
	public List`1 cardPageList { get; }
	public Int32 activePage { get; set; }
	public List`1 charactersWithFoodBuff { get; }
	public String exploredMap { get; set; }
	public SandboxV2Data configData { get; }
	public SandboxLevelConfig levelConfig { get; }
	public Dictionary`2 entityStatus { get; }
	public SandboxCameraPlugin cameraPlugin { get; }

	// RVA: 0x1de6f88 VA: 0x75943fef88
	public Void .ctor(SandboxGameMode gameMode) { }
	// RVA: 0x1de7428 VA: 0x75943ff428
	private SandboxUIPlugin get_uiPlugin() { }
	// RVA: 0x1de6048 VA: 0x75943fe048
	public UIBattleSandboxItemNotification get_notification() { }
	// RVA: 0x1de7588 VA: 0x75943ff588
	public Void set_notification(UIBattleSandboxItemNotification value) { }
	// RVA: 0x1de760c VA: 0x75943ff60c
	private Int32 get_maxVisibleCnt() { }
	// RVA: 0x1de7674 VA: 0x75943ff674
	private Void set_maxVisibleCnt(Int32 value) { }
	// RVA: 0x1de76f0 VA: 0x75943ff6f0
	public Int32 get_maxVisibleCntLimit() { }
	// RVA: 0x1de7784 VA: 0x75943ff784
	public Void set_maxVisibleCntLimit(Int32 value) { }
	// RVA: 0x1de7800 VA: 0x75943ff800
	public List`1 get_originHiddenList() { }
	// RVA: 0x1de7868 VA: 0x75943ff868
	public List`1 get_cardPageList() { }
	// RVA: 0x1de78d0 VA: 0x75943ff8d0
	public Int32 get_activePage() { }
	// RVA: 0x1de7938 VA: 0x75943ff938
	public Void set_activePage(Int32 value) { }
	// RVA: 0x1de79b4 VA: 0x75943ff9b4
	public List`1 get_charactersWithFoodBuff() { }
	// RVA: 0x1de7a28 VA: 0x75943ffa28
	public String get_exploredMap() { }
	// RVA: 0x1de7a9c VA: 0x75943ffa9c
	public Void set_exploredMap(String value) { }
	// RVA: 0x1dda7f8 VA: 0x75943f27f8
	public SandboxV2Data get_configData() { }
	// RVA: 0x1de7b28 VA: 0x75943ffb28
	public SandboxLevelConfig get_levelConfig() { }
	// RVA: 0x1de7b98 VA: 0x75943ffb98
	public Dictionary`2 get_entityStatus() { }
	// RVA: 0x1de7c08 VA: 0x75943ffc08
	public SandboxCameraPlugin get_cameraPlugin() { }
	// RVA: 0x1de7d68 VA: 0x75943ffd68
	public Void Init(LevelData levelData, BattlePlayerData playerData) { }
	// RVA: 0x1de8e90 VA: 0x7594400e90
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x1de8f18 VA: 0x7594400f18
	public Void OnFetchGameOverOutput() { }
	// RVA: 0x1de853c VA: 0x759440053c
	private Void _ParseConfigBlackboard(LevelData levelData) { }
	// RVA: 0x1de81b0 VA: 0x75944001b0
	private Void _InitInputStatus() { }
	// RVA: 0x1de8710 VA: 0x7594400710
	private Void _ParseCameraPlugin(Blackboard blackboard) { }
	// RVA: 0x1de87e8 VA: 0x75944007e8
	private Void _ParseNpc(Blackboard blackboard) { }
	// RVA: 0x1de8a78 VA: 0x7594400a78
	private Void _ParseHiddenArea(Blackboard blackboard) { }
	// RVA: 0x1de8f88 VA: 0x7594400f88
	public Void PostprocessMap(Map map) { }
	// RVA: 0x1de9004 VA: 0x7594401004
	private Void _DoHideTile() { }
	// RVA: 0x1de933c VA: 0x759440133c
	public Boolean CheckTileValid(Int32 row, Int32 col) { }
	// RVA: 0x1de9524 VA: 0x7594401524
	public Boolean ShowHiddenAreas(String rectStrs, Trap trap) { }
	// RVA: 0x1de9658 VA: 0x7594401658
	private Boolean _ShowHiddenArea(String rectStr, Trap trap) { }
	// RVA: 0x1de9c34 VA: 0x7594401c34
	public Void PreprocessCharacterCard(BattleCharacterData data, Character character) { }
	// RVA: 0x1de9dc4 VA: 0x7594401dc4
	public Void PreprocessEnemy(EnemyData data) { }
	// RVA: 0x1de9f7c VA: 0x7594401f7c
	public Void OnEnemyBorn(Enemy enemy) { }
	// RVA: 0x1dea05c VA: 0x759440205c
	public Void PreprocessRuneInput(RuneManager manager) { }
	// RVA: 0x1deaa54 VA: 0x7594402a54
	public Void OnStartGame() { }
	// RVA: 0x1deab50 VA: 0x7594402b50
	public IEnumerator FinalSchedule() { }
	// RVA: 0x1deabfc VA: 0x7594402bfc
	public Void TrySummonInsects() { }
	// RVA: 0x1deac70 VA: 0x7594402c70
	public Void PostPreprocessLevel(LevelData levelData) { }
	// RVA: 0x1deacfc VA: 0x7594402cfc
	public Void RebuildPageList() { }
	// RVA: 0x1deb52c VA: 0x759440352c
	public Void RefreshCardListByActivePage() { }
	// RVA: 0x1deb96c VA: 0x759440396c
	private static Boolean _CheckIfTeamTacticalCard(Card card) { }
	// RVA: 0x1deba94 VA: 0x7594403a94
	private static Void _RemoveTeamTacticalCard(List`1 cards) { }
	// RVA: 0x1debb7c VA: 0x7594403b7c
	public Void PreprocessPlayerDeckList(ListDict`2 deckList) { }
	// RVA: 0x1debdd0 VA: 0x7594403dd0
	public Boolean CheckCardDeployCountNotOverflow(Card card) { }
	// RVA: 0x1debf3c VA: 0x7594403f3c
	public Void SwitchPage(Int32 curPage) { }
	// RVA: 0x1dec010 VA: 0x7594404010
	public Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1dec148 VA: 0x7594404148
	public Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1dec250 VA: 0x7594404250
	public Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1dec444 VA: 0x7594404444
	public SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1dec4b8 VA: 0x75944044b8
	public List`1 PreprocessGlobalBuff() { }
	// RVA: 0x1dec974 VA: 0x7594404974
	public Boolean IsConstructItem(Character character) { }
	// RVA: 0x1deca58 VA: 0x7594404a58
	public Boolean IsFactoryTrap(Character character) { }
	// RVA: 0x1decb0c VA: 0x7594404b0c
	public Boolean IsFactoryTrap(Card card) { }
	// RVA: 0x1decbc0 VA: 0x7594404bc0
	public Boolean IsPlacedItem(Entity entity) { }
	// RVA: 0x1dd9778 VA: 0x75943f1778
	public Int32 GetResCountByID(String resId, Boolean thisLevel) { }
	// RVA: 0x1decdd8 VA: 0x7594404dd8
	public Int32 GetGoldCount(Boolean thisLevel) { }
	// RVA: 0x1dece78 VA: 0x7594404e78
	public Int32 GetAllRepairCost() { }
	// RVA: 0x1ded290 VA: 0x7594405290
	public Int32 GetDimensionCoinItemIdCount(Boolean thisLevel) { }
	// RVA: 0x1ded330 VA: 0x7594405330
	public Int32[] SandboxEntityPackedItems(Entity entity) { }
	// RVA: 0x1ded3b8 VA: 0x75944053b8
	public Void SandboxEntityDropItem(Entity entity, ResDropSourceType type) { }
	// RVA: 0x1ded44c VA: 0x759440544c
	public Void SandboxEntityDropItem(Entity entity, String itemId, Int32 count) { }
	// RVA: 0x1dd7754 VA: 0x75943ef754
	public Void SandboxCollectItem(String itemId, Int32 count) { }
	// RVA: 0x1ded4f8 VA: 0x75944054f8
	public Boolean SandboxCollectRacer(Enemy enemy) { }
	// RVA: 0x1ded810 VA: 0x7594405810
	public Void SandboxBindCollectItemListener(Action`2 onItemCollect) { }
	// RVA: 0x1ded8a8 VA: 0x75944058a8
	public Boolean IsPackedResFull(Entity entity) { }
	// RVA: 0x1ded93c VA: 0x759440593c
	public Int32 GetPackedResMaxCount(Entity entity) { }
	// RVA: 0x1ded9c4 VA: 0x75944059c4
	public Int32 GetPackedResMaxCount(Card card) { }
	// RVA: 0x1deda4c VA: 0x7594405a4c
	public Boolean CollectPackedRes(Entity entity) { }
	// RVA: 0x1dedad4 VA: 0x7594405ad4
	public Boolean TransferAllPackedRes(Entity fromTarget, Entity toTarget) { }
	// RVA: 0x1dedb68 VA: 0x7594405b68
	public Int32 GetTotalPackedResCount(Entity entity) { }
	// RVA: 0x1dedbf0 VA: 0x7594405bf0
	public Void SandboxAvgCollectItem(String itemId, Int32 count) { }
	// RVA: 0x1dee028 VA: 0x7594406028
	public Void SandboxAvgCollectItemList(List`1 models) { }
	// RVA: 0x1dee178 VA: 0x7594406178
	public Boolean CheckItemCount(String itemId, Int32 count, Boolean containsEq) { }
	// RVA: 0x1dee224 VA: 0x7594406224
	public Boolean FetchBossRecordedStatus(String rushEnemyUid, String targetKey, out SandboxRushBossStatus status) { }
	// RVA: 0x1dee2d0 VA: 0x75944062d0
	public Boolean FetchUniEnemyRecordedStatus(String targetKey, out SandboxV2UniEnemyStatus status) { }
	// RVA: 0x1dee364 VA: 0x7594406364
	public Boolean FetchUnitRecordedStatus(SandboxEntityStatusKey targetKey, out SandboxEntityStatusValue status) { }
	// RVA: 0x1dee410 VA: 0x7594406410
	public Boolean FetchPlacedItemRecordedStatus(SandboxPlacedItemStatusKey targetKey, out SandboxPlacedItemStatusValue status) { }
	// RVA: 0x1dee4bc VA: 0x75944064bc
	public Void RecordUnitState(SandboxEntityStatusKey targetKey, SandboxEntityStatusValue newStatus) { }
	// RVA: 0x1dee56c VA: 0x759440656c
	public Void RecordPlacedItemState(SandboxPlacedItemStatusKey targetKey, SandboxPlacedItemStatusValue newStatus) { }
	// RVA: 0x1dee618 VA: 0x7594406618
	public Void RecordUniEnemyState(String targetKey, SandboxV2UniEnemyStatus newStatus) { }
	// RVA: 0x1dee6ac VA: 0x75944066ac
	public Boolean FetchUniEnemyExtraInfo(String targetKey, out RareAnimalExtraInfo extraInfo) { }
	// RVA: 0x1dee740 VA: 0x7594406740
	public Void RecordBossState(String enemyUid, String targetKey, SandboxRushBossStatus newStatus) { }
	// RVA: 0x1dee7ec VA: 0x75944067ec
	public Void RecordUsingConstructItem(Character character) { }
	// RVA: 0x1dee874 VA: 0x7594406874
	public Void MarkRushEnemyDead(RushEnemy rushEnemy) { }
	// RVA: 0x1dee8fc VA: 0x75944068fc
	public Void MarkRushEnemyReachExit(Enemy target) { }
	// RVA: 0x1deeab4 VA: 0x7594406ab4
	public Boolean ProcessSpecialEnemy(Enemy enemy) { }
	// RVA: 0x1deeb40 VA: 0x7594406b40
	public Boolean CheckSpecialUniEnemy(String enemyId) { }
	// RVA: 0x1deebc8 VA: 0x7594406bc8
	public Void ConstructSaveLevelRes() { }
	// RVA: 0x1deec38 VA: 0x7594406c38
	public Void SandboxMarkDeathDetail(String entityId, Int32 count, EnemyDeathDetailType detailType) { }
	// RVA: 0x1deedac VA: 0x7594406dac
	public Void SandboxMarkUniDeathDetail(String rareAnimalInstId, UniEnemyDeathDetailType uniDetailType) { }
	// RVA: 0x1deeec8 VA: 0x7594406ec8
	public Void SandboxLogEnemyEvent(String entityId, String eventId, Int32 count) { }
	// RVA: 0x1def12c VA: 0x759440712c
	public Void SandboxMarkRemoveDeathDetail(String entityId, Int32 count, EnemyDeathDetailType detailType) { }
	// RVA: 0x1def30c VA: 0x759440730c
	public Single GetCompleteProgress() { }
	// RVA: 0x1def38c VA: 0x759440738c
	public Boolean IsLevelUnlockConditionComplete() { }
	// RVA: 0x1deb1dc VA: 0x75944031dc
	private List`1 _GetAvailableCardList() { }
	// RVA: 0x1def408 VA: 0x7594407408
	public Boolean CheckConditionKey(String condition, Int32 count, Boolean containsEq) { }
	// RVA: 0x1def524 VA: 0x7594407524
	public Void ModifyCondition(String condition, Int32 val) { }
	// RVA: 0x1def65c VA: 0x759440765c
	public Boolean CheckFavour(String trapId, Int32 val, Boolean containsEq) { }
	// RVA: 0x1def7a0 VA: 0x75944077a0
	public Void AddFavour(String trapId, Int32 val) { }
	// RVA: 0x1def968 VA: 0x7594407968
	public Void AddOutput(String npcId, BattleDialogType type) { }
	// RVA: 0x1defb18 VA: 0x7594407b18
	public Boolean MakeReactGacha(String npcId, Boolean isAll, Int32 gachaCnt, ref List`1 gachaedItem) { }
	// RVA: 0x1df0058 VA: 0x7594408058
	public Void AddOutputChoice(String npcId, String content, BattleDialogType type) { }
	// RVA: 0x1df0290 VA: 0x7594408290
	public String GetFirstSignal(BattleDialogType type) { }
	// RVA: 0x1df04fc VA: 0x75944084fc
	public NpcBattleInput GetNpcInputData(String signalId, BattleDialogType dialogType) { }
	// RVA: 0x1df0784 VA: 0x7594408784
	public Void SetNpcFinish(String npcId, BattleDialogType type) { }
	// RVA: 0x1df08e4 VA: 0x75944088e4
	public Void OverrideRiftId(String riftId) { }
	// RVA: 0x1df0b44 VA: 0x7594408b44
	public Void SpawnReactNpcIfNot() { }
}
```