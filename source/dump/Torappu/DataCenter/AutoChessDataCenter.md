# AutoChessDataCenter

**Namespace:** `Torappu.DataCenter`


## Fields

- `AutoChessModelData m_moduleData`

- `Boolean m_inited`

- `Boolean m_isDirty`

- `TileCache m_tileCache`

- `AutoChessViewModel m_viewModel`


## Properties

- `Boolean needUpdate`

- `Boolean isHandCntFull`

- `Boolean isInSpecialRefresh`

- `Boolean isTutorialValid`

- `Boolean chessCntFull`

- `Boolean isBonusRound`

- `Int32 currentRound`

- `Int32 currentShopLevel`

- `Boolean isShopLevelMax`

- `Boolean isHandCntExceed`

- `Int32 validHandCnt`

- `AutoChessModelData moduleData`

- `EffectInfoViewModel effectInfoViewModel`

- `Int32 enemyCnt`

- `Boolean isGameNeedSettled`

- `Int32 enemyMaxCnt`

- `Int32 shopLevel`

- `Int32 reachExitEnemyCnt`

- `Int32 refreshPrice`

- `CommonResponseViewModel startResponse`

- `CommonResponseViewModel refreshResponse`

- `CommonResponseViewModel frozResponse`

- `CommonResponseViewModel upgradeResponse`

- `TipBattleInfoViewModel tipBattleInfo`

- `RoundBattleFinishResponseViewModel finishResponse`

- `CommonResponseViewModel talentResponse`

- `TileCache tileCache`

- `Int32 upgradePrice`

- `Boolean isHudLocked`

- `Boolean isDragLocked`

- `Boolean isShopAllFrozen`

- `Boolean displayShopFrozen`

- `Int32 currentForceEffectCnt`

- `Int32 currentCoin`

- `Boolean isCoinEnoughToUpgrade`

- `Boolean hasEnterBattleStateAlready`

- `String actId`

- `Int32 countdown`

- `Boolean isPaused`

- `SpeedLevel speedLevel`

- `AutoChessGame game`

- `GameStatus status`

- `BattleGameInfo gameInfo`

- `Boolean isHandCntOverflow`

- `Boolean isInSelecting`

- `Act1VAutoChessShopLevelData currentShopLevelDataOrNull`

- `Int32 charShopUnlockCnt`

- `Int32 itemShopUnlockCnt`


## Methods

- `Boolean get_needUpdate()`

- `Boolean get_isHandCntFull()`

- `Boolean get_isInSpecialRefresh()`

- `Boolean get_isTutorialValid()`

- `Boolean get_chessCntFull()`

- `Boolean get_isBonusRound()`

- `Int32 get_currentRound()`

- `Int32 get_currentShopLevel()`

- `Boolean CanLevelUpShop()`

- `Boolean get_isShopLevelMax()`

- `Boolean get_isHandCntExceed()`

- `Int32 get_validHandCnt()`

- `AutoChessModelData get_moduleData()`

- `EffectInfoViewModel get_effectInfoViewModel()`

- `Int32 get_enemyCnt()`

- `Boolean get_isGameNeedSettled()`

- `Int32 get_enemyMaxCnt()`

- `Int32 get_shopLevel()`

- `Int32 get_reachExitEnemyCnt()`

- `Int32 get_refreshPrice()`

- `CommonResponseViewModel get_startResponse()`

- `CommonResponseViewModel get_refreshResponse()`

- `CommonResponseViewModel get_frozResponse()`

- `CommonResponseViewModel get_upgradeResponse()`

- `TipBattleInfoViewModel get_tipBattleInfo()`

- `RoundBattleFinishResponseViewModel get_finishResponse()`

- `CommonResponseViewModel get_talentResponse()`

- `TileCache get_tileCache()`

- `Int32 get_upgradePrice()`

- `Boolean get_isHudLocked()`

- `Boolean get_isDragLocked()`

- `Boolean get_isShopAllFrozen()`

- `Boolean get_displayShopFrozen()`

- `Int32 get_currentForceEffectCnt()`

- `Int32 get_currentCoin()`

- `Boolean get_isCoinEnoughToUpgrade()`

- `Boolean get_hasEnterBattleStateAlready()`

- `String get_actId()`

- `Int32 get_countdown()`

- `Boolean get_isPaused()`

- `SpeedLevel get_speedLevel()`

- `AutoChessGame get_game()`

- `GameStatus get_status()`

- `BattleGameInfo get_gameInfo()`

- `Act1VAutoChessModeType GetAutoChessDifficultyMode()`

- `Int32 CurrentInHandCnt()`

- `Boolean get_isHandCntOverflow()`

- `Boolean IsInstIdGolden(Int32)`

- `Boolean IsChessInstIdValid(Int32)`

- `Boolean TryGetShopPrice(GridPosition, out)`

- `Boolean get_isInSelecting()`

- `Boolean IsSpellInBattleFieldReachLimit(Int32)`

- `Boolean IsSelectTalentValid(String)`

- `Boolean FilterShopSlotChessIdCnt(Int32, Boolean, Int32, CompareType)`

- `Boolean FilterShopSlotOwnedCnt(Int32, Boolean, Int32, CompareType)`

- `Int32 GetShopSlotIndex(GridPosition)`

- `Act1VAutoChessShopLevelData get_currentShopLevelDataOrNull()`

- `Int32 get_charShopUnlockCnt()`

- `Int32 get_itemShopUnlockCnt()`

- `Boolean TryGetSkinData(Int32, out)`

- `Boolean IsSpecialRescuitCard(Int32)`

- `Void CollectInBattleInsts(ref)`

- `Boolean TryGetShopChessTile(ShopChess, out)`

- `Int32 GetSellPrice(String)`

- `Int32 GetShopIndex(GridPosition)`

- `Int32 GetShopIndex(Int32, Boolean)`

- `Boolean HaveNextRoundStart()`

- `Boolean InShopState()`

- `Boolean InSelectTeamState()`

- `Boolean HasCharChessInBattle(out)`

- `Boolean HasEquipInHand(out, Boolean)`

- `Boolean HasCharChessInBattleWithEquipSlot(out)`

- `Boolean HasEnoughCopyChessInShop(Int32, Int32, Boolean, out, Boolean)`

- `Boolean HasOwnedGoldChess()`

- `Boolean HasCharChessInHand(out)`

- `Boolean HasAffordableShopChar(out)`

- `Boolean HasAffordableShopEquip(out)`

- `Boolean HasSpecialMagicInHand(out)`

- `Boolean CanRefreshStore()`

- `Boolean InBattleState()`

- `Boolean InShopOrChooseBandState()`

- `Boolean InShopOrBattleState()`

- `Boolean InCommonGameState()`

- `Boolean IsTutorialPhase1Round()`

- `Boolean IsTutorialPhase2Round()`

- `Boolean IsTutorialPhase1ShopLevel()`

- `Boolean IsTutorialPhase2ShopLevel()`

- `Void ModifyData(IGameInfoModifier)`

- `Void SetReachExitEnemyCnt(Int32, Int32, Int32)`

- `Void SetHudLock(Boolean, String)`

- `Void SetDragLock(Boolean, String)`

- `Void SetSpeedLevel(SpeedLevel)`

- `Void SetGameReadyToFinish()`

- `Void SetDeployStatus(Int32)`

- `Void SetCountDown(Int32)`

- `Void _InitHandler()`

- `Void _InitBattleStatus()`

- `Void _LoadEffectInfo(ValueBundle)`

- `Void _InitTile()`

- `Void _UpdateFromPlayerData()`

- `PlayerAutoChessV1Activity GetAutoChessPlayerData(String)`

- `Void ReceiveMessage(AutoChessServiceMsg, ValueBundle)`

- `Void HandlePushMessage(AutoChessServiceMsg, ValueBundle)`

- `Void PrepareBattle()`

- `Void UpdatePlayerData()`

- `Void UpdateForce()`

- `Void TryNotifyUpdate(Single)`

- `Void LoadData(AutoChessModelData)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataCenter
public class AutoChessDataCenter : SingletonWithMonoHost`2, IDisposable
{
	private AutoChessModelData m_moduleData; // 0x10
	private Boolean m_inited; // 0x18
	private Boolean m_isDirty; // 0x19
	private TileCache m_tileCache; // 0x20
	private AutoChessViewModel m_viewModel; // 0x28
	private ListDict`2 m_serverMsgHandler; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_needUpdate; // 0x8
	private static DelegateBridge __Hotfix0_get_isHandCntFull; // 0x10
	private static DelegateBridge __Hotfix0_get_isInSpecialRefresh; // 0x18
	private static DelegateBridge __Hotfix0_get_isTutorialValid; // 0x20
	private static DelegateBridge __Hotfix0_get_chessCntFull; // 0x28
	private static DelegateBridge __Hotfix0_get_isBonusRound; // 0x30
	private static DelegateBridge __Hotfix0_get_currentRound; // 0x38
	private static DelegateBridge __Hotfix0_get_currentShopLevel; // 0x40
	private static DelegateBridge __Hotfix0_CanLevelUpShop; // 0x48
	private static DelegateBridge __Hotfix0_get_isShopLevelMax; // 0x50
	private static DelegateBridge __Hotfix0_get_isHandCntExceed; // 0x58
	private static DelegateBridge __Hotfix0_get_validHandCnt; // 0x60
	private static DelegateBridge __Hotfix0_get_moduleData; // 0x68
	private static DelegateBridge __Hotfix0_get_effectInfoViewModel; // 0x70
	private static DelegateBridge __Hotfix0_get_enemyCnt; // 0x78
	private static DelegateBridge __Hotfix0_get_isGameNeedSettled; // 0x80
	private static DelegateBridge __Hotfix0_get_enemyMaxCnt; // 0x88
	private static DelegateBridge __Hotfix0_get_shopLevel; // 0x90
	private static DelegateBridge __Hotfix0_get_reachExitEnemyCnt; // 0x98
	private static DelegateBridge __Hotfix0_get_refreshPrice; // 0xa0
	private static DelegateBridge __Hotfix0_get_startResponse; // 0xa8
	private static DelegateBridge __Hotfix0_get_refreshResponse; // 0xb0
	private static DelegateBridge __Hotfix0_get_frozResponse; // 0xb8
	private static DelegateBridge __Hotfix0_get_upgradeResponse; // 0xc0
	private static DelegateBridge __Hotfix0_get_tipBattleInfo; // 0xc8
	private static DelegateBridge __Hotfix0_get_shopChesses; // 0xd0
	private static DelegateBridge __Hotfix0_get_finishResponse; // 0xd8
	private static DelegateBridge __Hotfix0_get_talentResponse; // 0xe0
	private static DelegateBridge __Hotfix0_get_tileCache; // 0xe8
	private static DelegateBridge __Hotfix0_get_upgradePrice; // 0xf0
	private static DelegateBridge __Hotfix0_get_isHudLocked; // 0xf8
	private static DelegateBridge __Hotfix0_get_isDragLocked; // 0x100
	private static DelegateBridge __Hotfix0_get_isShopAllFrozen; // 0x108
	private static DelegateBridge __Hotfix0_get_displayShopFrozen; // 0x110
	private static DelegateBridge __Hotfix0_get_currentForceEffectCnt; // 0x118
	private static DelegateBridge __Hotfix0_get_currentCoin; // 0x120
	private static DelegateBridge __Hotfix0_get_isCoinEnoughToUpgrade; // 0x128
	private static DelegateBridge __Hotfix0_get_hasEnterBattleStateAlready; // 0x130
	private static DelegateBridge __Hotfix0_get_actId; // 0x138
	private static DelegateBridge __Hotfix0_get_countdown; // 0x140
	private static DelegateBridge __Hotfix0_get_isPaused; // 0x148
	private static DelegateBridge __Hotfix0_get_speedLevel; // 0x150
	private static DelegateBridge __Hotfix0_get_game; // 0x158
	private static DelegateBridge __Hotfix0_get_status; // 0x160
	private static DelegateBridge __Hotfix0_get_gameInfo; // 0x168
	private static DelegateBridge __Hotfix0_GetAutoChessDifficultyMode; // 0x170
	private static DelegateBridge __Hotfix0_CurrentInHandCnt; // 0x178
	private static DelegateBridge __Hotfix0_get_isHandCntOverflow; // 0x180
	private static DelegateBridge __Hotfix0_IsInstIdGolden; // 0x188
	private static DelegateBridge __Hotfix0_IsChessInstIdValid; // 0x190
	private static DelegateBridge __Hotfix0_TryGetShopPrice; // 0x198
	private static DelegateBridge __Hotfix0_get_isInSelecting; // 0x1a0
	private static DelegateBridge __Hotfix0_IsSpellInBattleFieldReachLimit; // 0x1a8
	private static DelegateBridge __Hotfix0_IsSelectTalentValid; // 0x1b0
	private static DelegateBridge __Hotfix0_FilterShopSlotChessIdCnt; // 0x1b8
	private static DelegateBridge __Hotfix0_FilterShopSlotOwnedCnt; // 0x1c0
	private static DelegateBridge __Hotfix0_GetShopSlotIndex; // 0x1c8
	private static DelegateBridge __Hotfix0_get_currentShopLevelDataOrNull; // 0x1d0
	private static DelegateBridge __Hotfix0_get_charShopUnlockCnt; // 0x1d8
	private static DelegateBridge __Hotfix0_get_itemShopUnlockCnt; // 0x1e0
	private static DelegateBridge __Hotfix0_TryGetSkinData; // 0x1e8
	private static DelegateBridge __Hotfix0_IsSpecialRescuitCard; // 0x1f0
	private static DelegateBridge __Hotfix0_CollectInBattleInsts; // 0x1f8
	private static DelegateBridge __Hotfix0_TryGetShopChessTile; // 0x200
	private static DelegateBridge __Hotfix0_GetSellPrice; // 0x208
	private static DelegateBridge __Hotfix0_GetShopIndex; // 0x210
	private static DelegateBridge __Hotfix1_GetShopIndex; // 0x218
	private static DelegateBridge __Hotfix0_HaveNextRoundStart; // 0x220
	private static DelegateBridge __Hotfix0_GetAct1VAutoChessData; // 0x228
	private static DelegateBridge __Hotfix0_InShopState; // 0x230
	private static DelegateBridge __Hotfix0_InSelectTeamState; // 0x238
	private static DelegateBridge __Hotfix0_HasCharChessInBattle; // 0x240
	private static DelegateBridge __Hotfix0_HasEquipInHand; // 0x248
	private static DelegateBridge __Hotfix0_HasCharChessInBattleWithEquipSlot; // 0x250
	private static DelegateBridge __Hotfix0_HasEnoughCopyChessInShop; // 0x258
	private static DelegateBridge __Hotfix0_HasOwnedGoldChess; // 0x260
	private static DelegateBridge __Hotfix0_HasCharChessInHand; // 0x268
	private static DelegateBridge __Hotfix0_HasAffordableShopChar; // 0x270
	private static DelegateBridge __Hotfix0_HasAffordableShopEquip; // 0x278
	private static DelegateBridge __Hotfix0_HasSpecialMagicInHand; // 0x280
	private static DelegateBridge __Hotfix0_CanRefreshStore; // 0x288
	private static DelegateBridge __Hotfix0_InBattleState; // 0x290
	private static DelegateBridge __Hotfix0_InShopOrChooseBandState; // 0x298
	private static DelegateBridge __Hotfix0_InShopOrBattleState; // 0x2a0
	private static DelegateBridge __Hotfix0_InCommonGameState; // 0x2a8
	private static DelegateBridge __Hotfix0_IsTutorialPhase1Round; // 0x2b0
	private static DelegateBridge __Hotfix0_IsTutorialPhase2Round; // 0x2b8
	private static DelegateBridge __Hotfix0_IsTutorialPhase1ShopLevel; // 0x2c0
	private static DelegateBridge __Hotfix0_IsTutorialPhase2ShopLevel; // 0x2c8
	private static DelegateBridge __Hotfix0_ModifyData; // 0x2d0
	private static DelegateBridge __Hotfix0_SetReachExitEnemyCnt; // 0x2d8
	private static DelegateBridge __Hotfix0_SetHudLock; // 0x2e0
	private static DelegateBridge __Hotfix0_SetDragLock; // 0x2e8
	private static DelegateBridge __Hotfix0_SetSpeedLevel; // 0x2f0
	private static DelegateBridge __Hotfix0_SetGameReadyToFinish; // 0x2f8
	private static DelegateBridge __Hotfix0_SetDeployStatus; // 0x300
	private static DelegateBridge __Hotfix0_SetCountDown; // 0x308
	private static DelegateBridge __Hotfix0__InitHandler; // 0x310
	private static DelegateBridge __Hotfix0__InitBattleStatus; // 0x318
	private static DelegateBridge __Hotfix0__LoadEffectInfo; // 0x320
	private static DelegateBridge __Hotfix0__InitTile; // 0x328
	private static DelegateBridge __Hotfix0__UpdateFromPlayerData; // 0x330
	private static DelegateBridge __Hotfix0_GetAutoChessPlayerData; // 0x338
	private static DelegateBridge __Hotfix0_ReceiveMessage; // 0x340
	private static DelegateBridge __Hotfix0_HandlePushMessage; // 0x348
	private static DelegateBridge __Hotfix0_PrepareBattle; // 0x350
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x358
	private static DelegateBridge __Hotfix0_UpdateForce; // 0x360
	private static DelegateBridge __Hotfix0_TryNotifyUpdate; // 0x368
	private static DelegateBridge __Hotfix0_LoadData; // 0x370
	private static DelegateBridge __Hotfix0_Dispose; // 0x378

	public Boolean needUpdate { get; }
	public Boolean isHandCntFull { get; }
	public Boolean isInSpecialRefresh { get; }
	public Boolean isTutorialValid { get; }
	public Boolean chessCntFull { get; }
	public Boolean isBonusRound { get; }
	public Int32 currentRound { get; }
	public Int32 currentShopLevel { get; }
	public Boolean isShopLevelMax { get; }
	public Boolean isHandCntExceed { get; }
	public Int32 validHandCnt { get; }
	public AutoChessModelData moduleData { get; }
	public EffectInfoViewModel effectInfoViewModel { get; }
	public Int32 enemyCnt { get; }
	public Boolean isGameNeedSettled { get; }
	public Int32 enemyMaxCnt { get; }
	public Int32 shopLevel { get; }
	public Int32 reachExitEnemyCnt { get; }
	public Int32 refreshPrice { get; }
	public CommonResponseViewModel startResponse { get; }
	public CommonResponseViewModel refreshResponse { get; }
	public CommonResponseViewModel frozResponse { get; }
	public CommonResponseViewModel upgradeResponse { get; }
	public TipBattleInfoViewModel tipBattleInfo { get; }
	public List`1 shopChesses { get; }
	public RoundBattleFinishResponseViewModel finishResponse { get; }
	public CommonResponseViewModel talentResponse { get; }
	public TileCache tileCache { get; }
	public Int32 upgradePrice { get; }
	public Boolean isHudLocked { get; }
	public Boolean isDragLocked { get; }
	public Boolean isShopAllFrozen { get; }
	public Boolean displayShopFrozen { get; }
	public Int32 currentForceEffectCnt { get; }
	public Int32 currentCoin { get; }
	public Boolean isCoinEnoughToUpgrade { get; }
	public Boolean hasEnterBattleStateAlready { get; }
	public String actId { get; }
	public Int32 countdown { get; }
	public Boolean isPaused { get; }
	public SpeedLevel speedLevel { get; }
	public AutoChessGame game { get; }
	public GameStatus status { get; }
	public BattleGameInfo gameInfo { get; }
	public Boolean isHandCntOverflow { get; }
	public Boolean isInSelecting { get; }
	public Act1VAutoChessShopLevelData currentShopLevelDataOrNull { get; }
	public Int32 charShopUnlockCnt { get; }
	public Int32 itemShopUnlockCnt { get; }

	// RVA: 0x3e3cdac VA: 0x7596454dac
	private Void .ctor() { }
	// RVA: 0x3e3cf04 VA: 0x7596454f04
	public Boolean get_needUpdate() { }
	// RVA: 0x3e3cf84 VA: 0x7596454f84
	public Boolean get_isHandCntFull() { }
	// RVA: 0x3e3d124 VA: 0x7596455124
	public Boolean get_isInSpecialRefresh() { }
	// RVA: 0x3e3d1b8 VA: 0x75964551b8
	public Boolean get_isTutorialValid() { }
	// RVA: 0x3e3d24c VA: 0x759645524c
	public Boolean get_chessCntFull() { }
	// RVA: 0x3e3d570 VA: 0x7596455570
	public Boolean get_isBonusRound() { }
	// RVA: 0x3e3d634 VA: 0x7596455634
	public Int32 get_currentRound() { }
	// RVA: 0x3e3d6c8 VA: 0x75964556c8
	public Int32 get_currentShopLevel() { }
	// RVA: 0x3e3d75c VA: 0x759645575c
	public Boolean CanLevelUpShop() { }
	// RVA: 0x3e3d80c VA: 0x759645580c
	public Boolean get_isShopLevelMax() { }
	// RVA: 0x3e3d98c VA: 0x759645598c
	public Boolean get_isHandCntExceed() { }
	// RVA: 0x3e3d0a0 VA: 0x75964550a0
	public Int32 get_validHandCnt() { }
	// RVA: 0x3e3da28 VA: 0x7596455a28
	public AutoChessModelData get_moduleData() { }
	// RVA: 0x3e3da90 VA: 0x7596455a90
	public EffectInfoViewModel get_effectInfoViewModel() { }
	// RVA: 0x3e3db1c VA: 0x7596455b1c
	public Int32 get_enemyCnt() { }
	// RVA: 0x3e3dba0 VA: 0x7596455ba0
	public Boolean get_isGameNeedSettled() { }
	// RVA: 0x3e3dc2c VA: 0x7596455c2c
	public Int32 get_enemyMaxCnt() { }
	// RVA: 0x3e3dcb0 VA: 0x7596455cb0
	public Int32 get_shopLevel() { }
	// RVA: 0x3e3dd58 VA: 0x7596455d58
	public Int32 get_reachExitEnemyCnt() { }
	// RVA: 0x3e3dddc VA: 0x7596455ddc
	public Int32 get_refreshPrice() { }
	// RVA: 0x3e3de84 VA: 0x7596455e84
	public CommonResponseViewModel get_startResponse() { }
	// RVA: 0x3e3defc VA: 0x7596455efc
	public CommonResponseViewModel get_refreshResponse() { }
	// RVA: 0x3e3df74 VA: 0x7596455f74
	public CommonResponseViewModel get_frozResponse() { }
	// RVA: 0x3e3dfec VA: 0x7596455fec
	public CommonResponseViewModel get_upgradeResponse() { }
	// RVA: 0x3e3e064 VA: 0x7596456064
	public TipBattleInfoViewModel get_tipBattleInfo() { }
	// RVA: 0x3e3e10c VA: 0x759645610c
	public List`1 get_shopChesses() { }
	// RVA: 0x3e3e1bc VA: 0x75964561bc
	public RoundBattleFinishResponseViewModel get_finishResponse() { }
	// RVA: 0x3e3e234 VA: 0x7596456234
	public CommonResponseViewModel get_talentResponse() { }
	// RVA: 0x3e3e2ac VA: 0x75964562ac
	public TileCache get_tileCache() { }
	// RVA: 0x3e3d8e4 VA: 0x75964558e4
	public Int32 get_upgradePrice() { }
	// RVA: 0x3e3e314 VA: 0x7596456314
	public Boolean get_isHudLocked() { }
	// RVA: 0x3e3e3ac VA: 0x75964563ac
	public Boolean get_isDragLocked() { }
	// RVA: 0x3e3e444 VA: 0x7596456444
	public Boolean get_isShopAllFrozen() { }
	// RVA: 0x3e3e4f4 VA: 0x75964564f4
	public Boolean get_displayShopFrozen() { }
	// RVA: 0x3e3e5a4 VA: 0x75964565a4
	public Int32 get_currentForceEffectCnt() { }
	// RVA: 0x3e3e64c VA: 0x759645664c
	public Int32 get_currentCoin() { }
	// RVA: 0x3e3e6f4 VA: 0x75964566f4
	public Boolean get_isCoinEnoughToUpgrade() { }
	// RVA: 0x3e3e774 VA: 0x7596456774
	public Boolean get_hasEnterBattleStateAlready() { }
	// RVA: 0x3e3d354 VA: 0x7596455354
	public String get_actId() { }
	// RVA: 0x3e3e800 VA: 0x7596456800
	public Int32 get_countdown() { }
	// RVA: 0x3e3e890 VA: 0x7596456890
	public Boolean get_isPaused() { }
	// RVA: 0x3e3e928 VA: 0x7596456928
	public SpeedLevel get_speedLevel() { }
	// RVA: 0x3e3d4ec VA: 0x75964554ec
	public AutoChessGame get_game() { }
	// RVA: 0x3e3d020 VA: 0x7596455020
	public GameStatus get_status() { }
	// RVA: 0x3e3e9b8 VA: 0x75964569b8
	public BattleGameInfo get_gameInfo() { }
	// RVA: 0x3e3ea60 VA: 0x7596456a60
	public Act1VAutoChessModeType GetAutoChessDifficultyMode() { }
	// RVA: 0x3e3eaf4 VA: 0x7596456af4
	public Int32 CurrentInHandCnt() { }
	// RVA: 0x3e3edb0 VA: 0x7596456db0
	public Boolean get_isHandCntOverflow() { }
	// RVA: 0x3e3ee88 VA: 0x7596456e88
	public Boolean IsInstIdGolden(Int32 instId) { }
	// RVA: 0x3e3efc8 VA: 0x7596456fc8
	public Boolean IsChessInstIdValid(Int32 instId) { }
	// RVA: 0x3e3f3f0 VA: 0x75964573f0
	public Boolean TryGetShopPrice(GridPosition pos, out Int32 price) { }
	// RVA: 0x3e3f6c4 VA: 0x75964576c4
	public Boolean get_isInSelecting() { }
	// RVA: 0x3e3f774 VA: 0x7596457774
	public Boolean IsSpellInBattleFieldReachLimit(Int32 instId) { }
	// RVA: 0x3e3f9a8 VA: 0x75964579a8
	public Boolean IsSelectTalentValid(String talentId) { }
	// RVA: 0x3e3fadc VA: 0x7596457adc
	public Boolean FilterShopSlotChessIdCnt(Int32 shopSlotIndex, Boolean isTrap, Int32 targetCnt, CompareType type) { }
	// RVA: 0x3e3fe00 VA: 0x7596457e00
	public Boolean FilterShopSlotOwnedCnt(Int32 shopSlotIndex, Boolean isTrap, Int32 cnt, CompareType type) { }
	// RVA: 0x3e40074 VA: 0x7596458074
	public Int32 GetShopSlotIndex(GridPosition pos) { }
	// RVA: 0x3e40194 VA: 0x7596458194
	public Act1VAutoChessShopLevelData get_currentShopLevelDataOrNull() { }
	// RVA: 0x3e40308 VA: 0x7596458308
	public Int32 get_charShopUnlockCnt() { }
	// RVA: 0x3e4037c VA: 0x759645837c
	public Int32 get_itemShopUnlockCnt() { }
	// RVA: 0x3e403f0 VA: 0x75964583f0
	public Boolean TryGetSkinData(Int32 instId, out CharSkinData data) { }
	// RVA: 0x3e40574 VA: 0x7596458574
	public Boolean IsSpecialRescuitCard(Int32 instId) { }
	// RVA: 0x3e406b8 VA: 0x75964586b8
	public Void CollectInBattleInsts(ref List`1 insts) { }
	// RVA: 0x3e408e4 VA: 0x75964588e4
	public Boolean TryGetShopChessTile(ShopChess chess, out GridPosition pos) { }
	// RVA: 0x3e40b90 VA: 0x7596458b90
	public Int32 GetSellPrice(String characterChessId) { }
	// RVA: 0x3e40c4c VA: 0x7596458c4c
	public Int32 GetShopIndex(GridPosition pos) { }
	// RVA: 0x3e40a5c VA: 0x7596458a5c
	public Int32 GetShopIndex(Int32 gameDataShopSlotIndex, Boolean isTrap) { }
	// RVA: 0x3e40dac VA: 0x7596458dac
	public Boolean HaveNextRoundStart() { }
	// RVA: 0x3e3d404 VA: 0x7596455404
	public static ActivityAutoChessVerify1Data GetAct1VAutoChessData(String actId) { }
	// RVA: 0x3e40f58 VA: 0x7596458f58
	public Boolean InShopState() { }
	// RVA: 0x3e41028 VA: 0x7596459028
	public Boolean InSelectTeamState() { }
	// RVA: 0x3e410f8 VA: 0x75964590f8
	public Boolean HasCharChessInBattle(out GridPosition validChessPos) { }
	// RVA: 0x3e41354 VA: 0x7596459354
	public Boolean HasEquipInHand(out GridPosition validChessPos, Boolean checkGolden) { }
	// RVA: 0x3e416e8 VA: 0x75964596e8
	public Boolean HasCharChessInBattleWithEquipSlot(out GridPosition validChessPos) { }
	// RVA: 0x3e41a44 VA: 0x7596459a44
	public Boolean HasEnoughCopyChessInShop(Int32 shopCnt, Int32 ownedCnt, Boolean isChar, out GridPosition pos, Boolean isEquip) { }
	// RVA: 0x3e41f30 VA: 0x7596459f30
	public Boolean HasOwnedGoldChess() { }
	// RVA: 0x3e42150 VA: 0x759645a150
	public Boolean HasCharChessInHand(out GridPosition validChessPos) { }
	// RVA: 0x3e423ac VA: 0x759645a3ac
	public Boolean HasAffordableShopChar(out GridPosition pos) { }
	// RVA: 0x3e4266c VA: 0x759645a66c
	public Boolean HasAffordableShopEquip(out GridPosition pos) { }
	// RVA: 0x3e4292c VA: 0x759645a92c
	public Boolean HasSpecialMagicInHand(out GridPosition pos) { }
	// RVA: 0x3e42bc8 VA: 0x759645abc8
	public Boolean CanRefreshStore() { }
	// RVA: 0x3e42c9c VA: 0x759645ac9c
	public Boolean InBattleState() { }
	// RVA: 0x3e42d6c VA: 0x759645ad6c
	public Boolean InShopOrChooseBandState() { }
	// RVA: 0x3e42e7c VA: 0x759645ae7c
	public Boolean InShopOrBattleState() { }
	// RVA: 0x3e40e14 VA: 0x7596458e14
	public Boolean InCommonGameState() { }
	// RVA: 0x3e42f8c VA: 0x759645af8c
	public Boolean IsTutorialPhase1Round() { }
	// RVA: 0x3e43054 VA: 0x759645b054
	public Boolean IsTutorialPhase2Round() { }
	// RVA: 0x3e4311c VA: 0x759645b11c
	public Boolean IsTutorialPhase1ShopLevel() { }
	// RVA: 0x3e431e4 VA: 0x759645b1e4
	public Boolean IsTutorialPhase2ShopLevel() { }
	// RVA: 0x3e432ac VA: 0x759645b2ac
	public Void ModifyData(IGameInfoModifier modifier) { }
	// RVA: 0x3e43568 VA: 0x759645b568
	public Void SetReachExitEnemyCnt(Int32 cnt, Int32 enemyCnt, Int32 enemyMax) { }
	// RVA: 0x3e43650 VA: 0x759645b650
	public Void SetHudLock(Boolean hudLock, String lockKey) { }
	// RVA: 0x3e43704 VA: 0x759645b704
	public Void SetDragLock(Boolean dragLock, String lockKey) { }
	// RVA: 0x3e437bc VA: 0x759645b7bc
	public Void SetSpeedLevel(SpeedLevel speedLevel) { }
	// RVA: 0x3e438a0 VA: 0x759645b8a0
	public Void SetGameReadyToFinish() { }
	// RVA: 0x3e43944 VA: 0x759645b944
	public Void SetDeployStatus(Int32 currentCharacterCnt) { }
	// RVA: 0x3e43a00 VA: 0x759645ba00
	public Void SetCountDown(Int32 countDown) { }
	// RVA: 0x3e43ac0 VA: 0x759645bac0
	private Void _InitHandler() { }
	// RVA: 0x3e43b9c VA: 0x759645bb9c
	private Void _InitBattleStatus() { }
	// RVA: 0x3e440d8 VA: 0x759645c0d8
	private Void _LoadEffectInfo(ValueBundle data) { }
	// RVA: 0x3e43cf8 VA: 0x759645bcf8
	private Void _InitTile() { }
	// RVA: 0x3e441f4 VA: 0x759645c1f4
	private Void _UpdateFromPlayerData() { }
	// RVA: 0x3e43fdc VA: 0x759645bfdc
	public PlayerAutoChessV1Activity GetAutoChessPlayerData(String actId) { }
	// RVA: 0x3e4431c VA: 0x759645c31c
	public Void ReceiveMessage(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x3e44428 VA: 0x759645c428
	public Void HandlePushMessage(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x3e44548 VA: 0x759645c548
	public Void PrepareBattle() { }
	// RVA: 0x3e445d4 VA: 0x759645c5d4
	public Void UpdatePlayerData() { }
	// RVA: 0x3e44648 VA: 0x759645c648
	public Void UpdateForce() { }
	// RVA: 0x3e446b4 VA: 0x759645c6b4
	public Void TryNotifyUpdate(Single deltaTime) { }
	// RVA: 0x3e4481c VA: 0x759645c81c
	public Void LoadData(AutoChessModelData moduleData) { }
	// RVA: 0x3e44968 VA: 0x759645c968
	public Void Dispose() { }
}
```