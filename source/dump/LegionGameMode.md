# LegionGameMode

**Namespace:** ` `


## Fields

- `Int32 m_currentCardPrice`

- `Int32 m_drawCardFromLibLogIndex`

- `Int32 m_currentDangerLevel`

- `Int32 m_addPriceWhenReShuffle`

- `Boolean m_hasReshuffled`

- `Boolean m_needShowAddPrice`

- `Int32 m_allCharacterCardCnt`

- `Card m_cachedCardLastDraw`

- `LegionModeSettings gameSettings`

- `Action onWaveWillStart`

- `LegionCharacterStatusManager m_charStatusManager`


## Properties

- `Int32 maxProfessionBuffCount`

- `Int32 professionLevelAdd`

- `Int32 usedCardCount`

- `Int32 remainingCardCount`

- `Boolean needPlayReshuffle`

- `Int32 goldForEndPrepare`

- `Int32 goldForWaveEnd`

- `Int32 initRedrawCount`

- `Int32 ingameRedrawCount`

- `Int32 inHandCardCount`

- `Int32 maxCardCount`

- `Boolean ableToDrawNextCard`

- `Boolean handCardNotFull`

- `Boolean currentGoldEnough`

- `Int32 addPriceWhenReshuffle`

- `Boolean showAddPriceWhenReshuffle`

- `Int32 currentCardPrice`

- `Int32 currentGold`

- `Card cachedCardLastDraw`


## Methods

- `Int32 get_maxProfessionBuffCount()`

- `Int32 get_professionLevelAdd()`

- `Int32 get_usedCardCount()`

- `Int32 get_remainingCardCount()`

- `Void set_needPlayReshuffle(Boolean)`

- `Boolean get_needPlayReshuffle()`

- `Int32 get_goldForEndPrepare()`

- `Int32 get_goldForWaveEnd()`

- `Int32 get_initRedrawCount()`

- `Int32 get_ingameRedrawCount()`

- `Int32 get_inHandCardCount()`

- `Int32 get_maxCardCount()`

- `Boolean get_ableToDrawNextCard()`

- `Boolean get_handCardNotFull()`

- `Boolean get_currentGoldEnough()`

- `Int32 get_addPriceWhenReshuffle()`

- `Boolean get_showAddPriceWhenReshuffle()`

- `Int32 get_currentCardPrice()`

- `Void set_currentCardPrice(Int32)`

- `Int32 get_currentGold()`

- `Void set_currentGold(Int32)`

- `Card get_cachedCardLastDraw()`

- `Void ShuffleAllPendingAndUsedCards()`

- `Void _OnCardPutToHand(Card)`

- `Void _DrawCardToHand(Card)`

- `Void _DrawCardToHandDirectly(Card)`

- `Void _DrawCardsFromPendingToHand(Int32)`

- `Void _DrawCardFromPendingToHand()`

- `Void _PickDifferentKindCard(List`1, List`1)`

- `Void _PickCardBySpecificKeys(List`1, List`1)`

- `Void SelectCardToHandFromOtherLibrary(BattleLegionSelectCardParam)`

- `Boolean RefreshSelectCardList(ref)`

- `Void DrawCardFromCardLibrary(List`1, List`1, BattleLegionSelectCardParam)`

- `Void AddProfessionLevelFromLastSelectCards(Character)`

- `Void DrawNextCard(Boolean, Boolean)`

- `Boolean DrawNextProfessionCard(ProfessionCategory, Boolean)`

- `Boolean DrawNextProfessionCard(ProfessionCategory, Int32, out, Boolean)`

- `Void _PutCardToUsed(Card)`

- `Void _PutCardToPending(Card)`

- `Void _UpdateCharacterCardCnt(Card, Boolean)`

- `Void _PutCardToDiscard(Card)`

- `Void _ReleaseFromDiscardLibraryIfNeed(Card)`

- `Void _PutCardToBlastCardList(Card)`

- `Void _RedrawCardToHandNextTick(Card)`

- `Void ForceRecycleCard(Card)`

- `Void DiscardCardFromLibrary(LegionCardLibraryType, Card)`

- `Void GainCardToLibrary(LegionCardLibraryType, Card)`

- `Void DrawCardFromLibraryViaTag(LegionCardLibraryType, String[], Int32)`

- `Void DrawCardFromLibraryViaId(LegionCardLibraryType, String)`

- `Void RedrawCards(List`1)`

- `Void SetCardUseOnlyOnce(UInt32)`

- `Void PutCardToUsed(Card)`

- `Void ModifyCharacterOverlapState(Character, Boolean)`

- `Boolean ReleaseDiscardCardByKey(String)`

- `Void _ProcessLevelConfig(Blackboard)`

- `Void _OnCardRecycle(Card)`

- `Void ShowStatusMessage(Character)`

- `Int32 GetLegionGold(PlayerSide)`

- `Int32 SetLegionGold(Int32, PlayerSide)`

- `Void AddLegionGold(Int32, PlayerSide)`

- `Void GetGoldViaProfessionBuffCount(Character, Int32)`

- `Int32 GetCardsNumByType(LegionCardLibraryType)`

- `Int32 GetLegionDangerLevel()`

- `Void RefreshLegionModeDangerLevel(Int32)`

- `LegionCharacterStatus GetOwnerStatus(Character, Boolean)`

- `Boolean ReplaceCharacter(Character, Character)`

- `Boolean CheckCharacterNoOverlap(Character)`

- `Void AddTargetProfessionLevelDirectly(ProfessionCategory, Character, Int32)`

- `Void ClearTargetProfessionLevel(Character)`

- `Void RefreshTargetProfessionBuff(Character)`

- `Void MarkCharReturnToHandAndKeepStatues(Character, Boolean)`

- `Void TemporaryAddEachProfessionStatus(Character)`

- `Void FinishTemporaryProfessionStatus(Character)`

- `Void MarkCardReturnToHand(Character, Boolean)`

- `Int32 GetProfessionBuffMaxCnt(Character)`

- `Void ModifyProfessionBuffMaxCnt(Character, Int32, Boolean)`

- `Boolean CheckLastSelectCardsContainsProfessionCategory(ProfessionCategory)`

- `Void ModifyProfessionBuffDefaultAddCnt(Character, Int32, Boolean)`

- `Int32 GetProfessionBuffNum(Character)`

- `Int32 GetStatusProfessionCnt(Character)`

- `Int32 GetSpecifiedProfessionStatusBuffCnt(Character, ProfessionCategory)`

- `Card FindUsingCardByUniqueId(UInt32)`

- `Void _DoAnimForCardFullToHand(Card)`

- `Boolean CheckCardIsInAllCardLibrary(Card)`

- `Boolean CheckCardIsInSomeCardLibrary(LegionCardLibraryType, Card)`

- `Boolean CheckCardIsInOnlyCardLibrary(Card)`

- `Boolean CheckCardIsUsing(Card)`

- `Void _CheckRefreshedTokenCardList()`

- `Void _CheckRedrawToHandCardList()`

- `Void _CheckBlastCardList()`

- `Void _CheckNeedRefillPendingFromUsed(Boolean)`

- `Boolean _CheckNeedInitReShuffle(List`1)`

- `Void _OnDrawNextCardByManualEvent()`

- `Void _OnRefreshCardEvent()`

- `Void _LogDrawCardFromCardLibrary(Card, String)`

- `Void _LogCurrentDangerLevel(Int32)`

- `Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_PreprocessPlayerData(List`1)`

- `Void <>xLuaBaseProxy_PreprocessPlayerDeckList(ListDict`2)`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Options <>xLuaBaseProxy_PostprocessLevelOptions(Options)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_ParseBattleEvents(ActionData)`

- `Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition, Tile, Direction, Boolean, Boolean, BattleCharacterData, PlayerSide)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Void <>xLuaBaseProxy_OnCharacterFinished(Character, FinishReason)`

- `Void <>xLuaBaseProxy_OnCardListChanged(Card)`

- `Void <>xLuaBaseProxy_OnCardRecycle(Card)`

- `Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionGameMode : DefaultGameMode
{
	private readonly LegionInput m_input; // 0x20
	private readonly ListDict`2 m_legionGoldDict; // 0x28
	private readonly List`1 m_preLocatedCharacterCardList; // 0x30
	private readonly List`1 m_usingCharacterCardList; // 0x38
	private readonly List`1 m_pendingCharacterCardList; // 0x40
	private readonly List`1 m_usedCharacterCardList; // 0x48
	private Int32 m_currentCardPrice; // 0x50
	private Int32 m_drawCardFromLibLogIndex; // 0x54
	private Int32 m_currentDangerLevel; // 0x58
	private Int32 m_addPriceWhenReShuffle; // 0x5c
	private Boolean m_hasReshuffled; // 0x60
	private Boolean m_needShowAddPrice; // 0x61
	private Int32 m_allCharacterCardCnt; // 0x64
	private Card m_cachedCardLastDraw; // 0x68
	private readonly List`1 m_redrawToHandCharacterCardList; // 0x70
	private readonly List`1 m_refreshedTokenCardList; // 0x78
	private readonly List`1 m_cachedBlastCardList; // 0x80
	private readonly List`1 m_rewardCardList; // 0x88
	private readonly List`1 m_discardCardCardList; // 0x90
	private readonly List`1 m_lastSelectCharacterCardList; // 0x98
	private readonly List`1 m_useOnlyOnceCardUIDList; // 0xa0
	private readonly List`1 m_characterDataOrderList; // 0xa8
	private readonly List`1 m_preGivenTokenList; // 0xb0
	public LegionModeSettings gameSettings; // 0xb8
	public Action`1 onCardFullPutToUsed; // 0xc0
	public Action onWaveWillStart; // 0xc8
	private readonly List`1 m_globalBuffs; // 0xd0
	private LegionCharacterStatusManager m_charStatusManager; // 0xd8
	private List`1 m_bannedOverlapList; // 0xe0
	private List`1 m_getCardLibraryByTypeResult; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_maxProfessionBuffCount; // 0x8
	private static DelegateBridge __Hotfix0_get_professionLevelAdd; // 0x10
	private static DelegateBridge __Hotfix0_get_usedCardCount; // 0x18
	private static DelegateBridge __Hotfix0_get_remainingCardCount; // 0x20
	private static DelegateBridge __Hotfix0_set_needPlayReshuffle; // 0x28
	private static DelegateBridge __Hotfix0_get_needPlayReshuffle; // 0x30
	private static DelegateBridge __Hotfix0_get_goldForEndPrepare; // 0x38
	private static DelegateBridge __Hotfix0_get_goldForWaveEnd; // 0x40
	private static DelegateBridge __Hotfix0_get_initRedrawCount; // 0x48
	private static DelegateBridge __Hotfix0_get_ingameRedrawCount; // 0x50
	private static DelegateBridge __Hotfix0_get_inHandCardCount; // 0x58
	private static DelegateBridge __Hotfix0_get_maxCardCount; // 0x60
	private static DelegateBridge __Hotfix0_get_ableToDrawNextCard; // 0x68
	private static DelegateBridge __Hotfix0_get_handCardNotFull; // 0x70
	private static DelegateBridge __Hotfix0_get_currentGoldEnough; // 0x78
	private static DelegateBridge __Hotfix0_get_addPriceWhenReshuffle; // 0x80
	private static DelegateBridge __Hotfix0_get_showAddPriceWhenReshuffle; // 0x88
	private static DelegateBridge __Hotfix0_get_currentCardPrice; // 0x90
	private static DelegateBridge __Hotfix0_set_currentCardPrice; // 0x98
	private static DelegateBridge __Hotfix0_get_currentGold; // 0xa0
	private static DelegateBridge __Hotfix0_set_currentGold; // 0xa8
	private static DelegateBridge __Hotfix0_get_cachedCardLastDraw; // 0xb0
	private static DelegateBridge __Hotfix0_GetCardLibraryByType; // 0xb8
	private static DelegateBridge __Hotfix0_ShuffleAllPendingAndUsedCards; // 0xc0
	private static DelegateBridge __Hotfix0__OnCardPutToHand; // 0xc8
	private static DelegateBridge __Hotfix0__DrawCardToHand; // 0xd0
	private static DelegateBridge __Hotfix0__DrawCardToHandDirectly; // 0xd8
	private static DelegateBridge __Hotfix0__DrawCardsFromPendingToHand; // 0xe0
	private static DelegateBridge __Hotfix0__DrawCardFromPendingToHand; // 0xe8
	private static DelegateBridge __Hotfix0__PickDifferentKindCard; // 0xf0
	private static DelegateBridge __Hotfix0__PickCardBySpecificKeys; // 0xf8
	private static DelegateBridge __Hotfix0_SelectCardToHandFromOtherLibrary; // 0x100
	private static DelegateBridge __Hotfix0_RefreshSelectCardList; // 0x108
	private static DelegateBridge __Hotfix0_DrawCardFromCardLibrary; // 0x110
	private static DelegateBridge __Hotfix0_AddProfessionLevelFromLastSelectCards; // 0x118
	private static DelegateBridge __Hotfix0_DrawNextCard; // 0x120
	private static DelegateBridge __Hotfix0_DrawNextProfessionCard; // 0x128
	private static DelegateBridge __Hotfix1_DrawNextProfessionCard; // 0x130
	private static DelegateBridge __Hotfix0__PutCardToUsed; // 0x138
	private static DelegateBridge __Hotfix0__PutCardToPending; // 0x140
	private static DelegateBridge __Hotfix0__UpdateCharacterCardCnt; // 0x148
	private static DelegateBridge __Hotfix0__PutCardToDiscard; // 0x150
	private static DelegateBridge __Hotfix0__ReleaseFromDiscardLibraryIfNeed; // 0x158
	private static DelegateBridge __Hotfix0__PutCardToBlastCardList; // 0x160
	private static DelegateBridge __Hotfix0__RedrawCardToHandNextTick; // 0x168
	private static DelegateBridge __Hotfix0_ForceRecycleCard; // 0x170
	private static DelegateBridge __Hotfix0_DiscardCardFromLibrary; // 0x178
	private static DelegateBridge __Hotfix0_GainCardToLibrary; // 0x180
	private static DelegateBridge __Hotfix0_DrawCardFromLibraryViaTag; // 0x188
	private static DelegateBridge __Hotfix0_DrawCardFromLibraryViaId; // 0x190
	private static DelegateBridge __Hotfix0_RedrawCards; // 0x198
	private static DelegateBridge __Hotfix0_SetCardUseOnlyOnce; // 0x1a0
	private static DelegateBridge __Hotfix0_PutCardToUsed; // 0x1a8
	private static DelegateBridge __Hotfix0_ModifyCharacterOverlapState; // 0x1b0
	private static DelegateBridge __Hotfix0_ReleaseDiscardCardByKey; // 0x1b8
	private static DelegateBridge __Hotfix0_get_hasExtraBuildCondition; // 0x1c0
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x1c8
	private static DelegateBridge __Hotfix0_PreprocessPlayerData; // 0x1d0
	private static DelegateBridge __Hotfix0_PreprocessPlayerDeckList; // 0x1d8
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x1e0
	private static DelegateBridge __Hotfix0_PostprocessLevelOptions; // 0x1e8
	private static DelegateBridge __Hotfix0__ProcessLevelConfig; // 0x1f0
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x1f8
	private static DelegateBridge __Hotfix0_ParseBattleEvents; // 0x200
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x208
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x210
	private static DelegateBridge __Hotfix0_GatherGlobalBuffs; // 0x218
	private static DelegateBridge __Hotfix0_Init; // 0x220
	private static DelegateBridge __Hotfix0_Tick; // 0x228
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x230
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x238
	private static DelegateBridge __Hotfix0_OnCardRecycle; // 0x240
	private static DelegateBridge __Hotfix0__OnCardRecycle; // 0x248
	private static DelegateBridge __Hotfix0_CheckCardReadyToSpawn; // 0x250
	private static DelegateBridge __Hotfix0_GatherPreloadAssets; // 0x258
	private static DelegateBridge __Hotfix0__GetPreGivenTokens; // 0x260
	private static DelegateBridge __Hotfix0_ShowStatusMessage; // 0x268
	private static DelegateBridge __Hotfix0_GetLegionGold; // 0x270
	private static DelegateBridge __Hotfix0_SetLegionGold; // 0x278
	private static DelegateBridge __Hotfix0_AddLegionGold; // 0x280
	private static DelegateBridge __Hotfix0_GetGoldViaProfessionBuffCount; // 0x288
	private static DelegateBridge __Hotfix0_GetCardsNumByType; // 0x290
	private static DelegateBridge __Hotfix0_GetLegionDangerLevel; // 0x298
	private static DelegateBridge __Hotfix0_RefreshLegionModeDangerLevel; // 0x2a0
	private static DelegateBridge __Hotfix0_GetOwnerStatus; // 0x2a8
	private static DelegateBridge __Hotfix0_ReplaceCharacter; // 0x2b0
	private static DelegateBridge __Hotfix0_CheckCharacterNoOverlap; // 0x2b8
	private static DelegateBridge __Hotfix0_AddTargetProfessionLevelDirectly; // 0x2c0
	private static DelegateBridge __Hotfix0_ClearTargetProfessionLevel; // 0x2c8
	private static DelegateBridge __Hotfix0_RefreshTargetProfessionBuff; // 0x2d0
	private static DelegateBridge __Hotfix0_MarkCharReturnToHandAndKeepStatues; // 0x2d8
	private static DelegateBridge __Hotfix0_TemporaryAddEachProfessionStatus; // 0x2e0
	private static DelegateBridge __Hotfix0_FinishTemporaryProfessionStatus; // 0x2e8
	private static DelegateBridge __Hotfix0_MarkCardReturnToHand; // 0x2f0
	private static DelegateBridge __Hotfix0_GetProfessionBuffMaxCnt; // 0x2f8
	private static DelegateBridge __Hotfix0_ModifyProfessionBuffMaxCnt; // 0x300
	private static DelegateBridge __Hotfix0_CheckLastSelectCardsContainsProfessionCategory; // 0x308
	private static DelegateBridge __Hotfix0_ModifyProfessionBuffDefaultAddCnt; // 0x310
	private static DelegateBridge __Hotfix0_GetCharacterProfessionStatus; // 0x318
	private static DelegateBridge __Hotfix0_GetCharacterProfessionStatusWithHighLight; // 0x320
	private static DelegateBridge __Hotfix0_GetProfessionBuffNum; // 0x328
	private static DelegateBridge __Hotfix0_GetStatusProfessionCnt; // 0x330
	private static DelegateBridge __Hotfix0_GetSpecifiedProfessionStatusBuffCnt; // 0x338
	private static DelegateBridge __Hotfix0_FindUsingCardByUniqueId; // 0x340
	private static DelegateBridge __Hotfix0__DoAnimForCardFullToHand; // 0x348
	private static DelegateBridge __Hotfix0_CheckCardIsInAllCardLibrary; // 0x350
	private static DelegateBridge __Hotfix0_CheckCardIsInSomeCardLibrary; // 0x358
	private static DelegateBridge __Hotfix0_CheckCardIsInOnlyCardLibrary; // 0x360
	private static DelegateBridge __Hotfix0_CheckCardIsUsing; // 0x368
	private static DelegateBridge __Hotfix0__CheckRefreshedTokenCardList; // 0x370
	private static DelegateBridge __Hotfix0__CheckRedrawToHandCardList; // 0x378
	private static DelegateBridge __Hotfix0__CheckBlastCardList; // 0x380
	private static DelegateBridge __Hotfix0__CheckNeedRefillPendingFromUsed; // 0x388
	private static DelegateBridge __Hotfix0__CheckNeedInitReShuffle; // 0x390
	private static DelegateBridge __Hotfix0__OnDrawNextCardByManualEvent; // 0x398
	private static DelegateBridge __Hotfix0__OnRefreshCardEvent; // 0x3a0
	private static DelegateBridge __Hotfix0__LogDrawCardFromCardLibrary; // 0x3a8
	private static DelegateBridge __Hotfix0__LogCurrentDangerLevel; // 0x3b0

	public Int32 maxProfessionBuffCount { get; }
	public Int32 professionLevelAdd { get; }
	public Int32 usedCardCount { get; }
	public Int32 remainingCardCount { get; }
	public Boolean needPlayReshuffle { get; set; }
	public Int32 goldForEndPrepare { get; }
	public Int32 goldForWaveEnd { get; }
	public Int32 initRedrawCount { get; }
	public Int32 ingameRedrawCount { get; }
	public Int32 inHandCardCount { get; }
	public Int32 maxCardCount { get; }
	public Boolean ableToDrawNextCard { get; }
	public Boolean handCardNotFull { get; }
	public Boolean currentGoldEnough { get; }
	public Int32 addPriceWhenReshuffle { get; }
	public Boolean showAddPriceWhenReshuffle { get; }
	public Int32 currentCardPrice { get; set; }
	public Int32 currentGold { get; set; }
	public Card cachedCardLastDraw { get; }
	public override Boolean hasExtraBuildCondition { get; }
	public override GameModeType gameModeType { get; }

	// RVA: 0x1ce10c8 VA: 0x75942f90c8
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1ce1690 VA: 0x75942f9690
	public Int32 get_maxProfessionBuffCount() { }
	// RVA: 0x1ce1704 VA: 0x75942f9704
	public Int32 get_professionLevelAdd() { }
	// RVA: 0x1ce1778 VA: 0x75942f9778
	public Int32 get_usedCardCount() { }
	// RVA: 0x1ce17f8 VA: 0x75942f97f8
	public Int32 get_remainingCardCount() { }
	// RVA: 0x1ce1878 VA: 0x75942f9878
	public Void set_needPlayReshuffle(Boolean value) { }
	// RVA: 0x1ce18f8 VA: 0x75942f98f8
	public Boolean get_needPlayReshuffle() { }
	// RVA: 0x1ce1960 VA: 0x75942f9960
	public Int32 get_goldForEndPrepare() { }
	// RVA: 0x1ce19d4 VA: 0x75942f99d4
	public Int32 get_goldForWaveEnd() { }
	// RVA: 0x1ce1a48 VA: 0x75942f9a48
	public Int32 get_initRedrawCount() { }
	// RVA: 0x1ce1abc VA: 0x75942f9abc
	public Int32 get_ingameRedrawCount() { }
	// RVA: 0x1ce1b30 VA: 0x75942f9b30
	public Int32 get_inHandCardCount() { }
	// RVA: 0x1ce1c8c VA: 0x75942f9c8c
	public Int32 get_maxCardCount() { }
	// RVA: 0x1ce1d00 VA: 0x75942f9d00
	public Boolean get_ableToDrawNextCard() { }
	// RVA: 0x1ce1d94 VA: 0x75942f9d94
	public Boolean get_handCardNotFull() { }
	// RVA: 0x1ce1e18 VA: 0x75942f9e18
	public Boolean get_currentGoldEnough() { }
	// RVA: 0x1ce1f74 VA: 0x75942f9f74
	public Int32 get_addPriceWhenReshuffle() { }
	// RVA: 0x1ce1fe8 VA: 0x75942f9fe8
	public Boolean get_showAddPriceWhenReshuffle() { }
	// RVA: 0x1ce1f04 VA: 0x75942f9f04
	public Int32 get_currentCardPrice() { }
	// RVA: 0x1ce2050 VA: 0x75942fa050
	public Void set_currentCardPrice(Int32 value) { }
	// RVA: 0x1ce1e98 VA: 0x75942f9e98
	public Int32 get_currentGold() { }
	// RVA: 0x1ce21e8 VA: 0x75942fa1e8
	public Void set_currentGold(Int32 value) { }
	// RVA: 0x1ce23e4 VA: 0x75942fa3e4
	public Card get_cachedCardLastDraw() { }
	// RVA: 0x1ce244c VA: 0x75942fa44c
	public List`1 GetCardLibraryByType(LegionCardLibraryType cardType) { }
	// RVA: 0x1ce2568 VA: 0x75942fa568
	public Void ShuffleAllPendingAndUsedCards() { }
	// RVA: 0x1ce26c8 VA: 0x75942fa6c8
	private Void _OnCardPutToHand(Card card) { }
	// RVA: 0x1ce2824 VA: 0x75942fa824
	private Void _DrawCardToHand(Card card) { }
	// RVA: 0x1ce2e84 VA: 0x75942fae84
	private Void _DrawCardToHandDirectly(Card card) { }
	// RVA: 0x1ce3134 VA: 0x75942fb134
	private Void _DrawCardsFromPendingToHand(Int32 count) { }
	// RVA: 0x1ce35fc VA: 0x75942fb5fc
	private Void _DrawCardFromPendingToHand() { }
	// RVA: 0x1ce3710 VA: 0x75942fb710
	private Void _PickDifferentKindCard(List`1 sourceList, List`1 resultList) { }
	// RVA: 0x1ce396c VA: 0x75942fb96c
	private Void _PickCardBySpecificKeys(List`1 cardKeys, List`1 resultList) { }
	// RVA: 0x1ce3e50 VA: 0x75942fbe50
	public Void SelectCardToHandFromOtherLibrary(BattleLegionSelectCardParam param) { }
	// RVA: 0x1ce3f40 VA: 0x75942fbf40
	public Boolean RefreshSelectCardList(ref BattleLegionSelectCardParam param) { }
	// RVA: 0x1ce4278 VA: 0x75942fc278
	public Void DrawCardFromCardLibrary(List`1 selectRangeIds, List`1 selectIds, BattleLegionSelectCardParam selectData) { }
	// RVA: 0x1ce53b0 VA: 0x75942fd3b0
	public Void AddProfessionLevelFromLastSelectCards(Character character) { }
	// RVA: 0x1ce5634 VA: 0x75942fd634
	public Void DrawNextCard(Boolean noCost, Boolean isManual) { }
	// RVA: 0x1ce58e4 VA: 0x75942fd8e4
	public Boolean DrawNextProfessionCard(ProfessionCategory professionGroup, Boolean drawCardFromUsedAndPending) { }
	// RVA: 0x1ce5b10 VA: 0x75942fdb10
	public Boolean DrawNextProfessionCard(ProfessionCategory professionGroup, Int32 cnt, out List`1 cardList, Boolean drawCardFromUsedAndPending) { }
	// RVA: 0x1ce2b1c VA: 0x75942fab1c
	private Void _PutCardToUsed(Card card) { }
	// RVA: 0x1ce4efc VA: 0x75942fcefc
	private Void _PutCardToPending(Card card) { }
	// RVA: 0x1ce5f9c VA: 0x75942fdf9c
	private Void _UpdateCharacterCardCnt(Card card, Boolean isAdd) { }
	// RVA: 0x1ce5044 VA: 0x75942fd044
	private Void _PutCardToDiscard(Card card) { }
	// RVA: 0x1ce6080 VA: 0x75942fe080
	private Void _ReleaseFromDiscardLibraryIfNeed(Card card) { }
	// RVA: 0x1ce2d04 VA: 0x75942fad04
	private Void _PutCardToBlastCardList(Card card) { }
	// RVA: 0x1ce6168 VA: 0x75942fe168
	private Void _RedrawCardToHandNextTick(Card card) { }
	// RVA: 0x1ce6278 VA: 0x75942fe278
	public Void ForceRecycleCard(Card card) { }
	// RVA: 0x1ce64fc VA: 0x75942fe4fc
	public Void DiscardCardFromLibrary(LegionCardLibraryType cardType, Card discardCard) { }
	// RVA: 0x1ce6634 VA: 0x75942fe634
	public Void GainCardToLibrary(LegionCardLibraryType libraryType, Card gainCard) { }
	// RVA: 0x1ce6724 VA: 0x75942fe724
	public Void DrawCardFromLibraryViaTag(LegionCardLibraryType cardType, String[] tags, Int32 count) { }
	// RVA: 0x1ce68d8 VA: 0x75942fe8d8
	public Void DrawCardFromLibraryViaId(LegionCardLibraryType cardType, String id) { }
	// RVA: 0x1ce6a58 VA: 0x75942fea58
	public Void RedrawCards(List`1 cardList) { }
	// RVA: 0x1ce6c60 VA: 0x75942fec60
	public Void SetCardUseOnlyOnce(UInt32 uid) { }
	// RVA: 0x1ce6d80 VA: 0x75942fed80
	public Void PutCardToUsed(Card card) { }
	// RVA: 0x1ce6e8c VA: 0x75942fee8c
	public Void ModifyCharacterOverlapState(Character character, Boolean noOverlap) { }
	// RVA: 0x1ce3c2c VA: 0x75942fbc2c
	public Boolean ReleaseDiscardCardByKey(String cardKey) { }
	// RVA: 0x1ce7008 VA: 0x75942ff008
	public override Boolean get_hasExtraBuildCondition() { }
	// RVA: 0x1ce7070 VA: 0x75942ff070
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1ce70d8 VA: 0x75942ff0d8
	public override Void PreprocessPlayerData(List`1 dataList) { }
	// RVA: 0x1ce7f4c VA: 0x75942fff4c
	public override Void PreprocessPlayerDeckList(ListDict`2 deckList) { }
	// RVA: 0x1ce83bc VA: 0x75943003bc
	public override Void OnPostInit() { }
	// RVA: 0x1ce8520 VA: 0x7594300520
	public override Options PostprocessLevelOptions(Options options) { }
	// RVA: 0x1ce85b4 VA: 0x75943005b4
	private Void _ProcessLevelConfig(Blackboard blackboard) { }
	// RVA: 0x1ce894c VA: 0x759430094c
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1ce89e8 VA: 0x75943009e8
	public override Void ParseBattleEvents(ActionData data) { }
	// RVA: 0x1ce8ba0 VA: 0x7594300ba0
	public override Boolean CheckBuildable(BuildCondition buildCondition, Tile tile, Direction direction, Boolean spawnManually, Boolean overflowOccupiedCnt, BattleCharacterData sourceData, PlayerSide operationSide) { }
	// RVA: 0x1ce8e80 VA: 0x7594300e80
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1ce8f18 VA: 0x7594300f18
	public override List`1 GatherGlobalBuffs() { }
	// RVA: 0x1ce91e4 VA: 0x75943011e4
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1ce9a2c VA: 0x7594301a2c
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cea014 VA: 0x7594302014
	public override Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cea0a0 VA: 0x75943020a0
	public override Void OnCardListChanged(Card card) { }
	// RVA: 0x1cea29c VA: 0x759430229c
	public override Void OnCardRecycle(Card card) { }
	// RVA: 0x1ce634c VA: 0x75942fe34c
	private Void _OnCardRecycle(Card card) { }
	// RVA: 0x1cea370 VA: 0x7594302370
	public override Boolean CheckCardReadyToSpawn(Card card) { }
	// RVA: 0x1cea458 VA: 0x7594302458
	public static Dictionary`2 GatherPreloadAssets() { }
	// RVA: 0x1ce97a4 VA: 0x75943017a4
	private static List`1 _GetPreGivenTokens(LegionInput input) { }
	// RVA: 0x1cea618 VA: 0x7594302618
	public Void ShowStatusMessage(Character character) { }
	// RVA: 0x1ce20e4 VA: 0x75942fa0e4
	public Int32 GetLegionGold(PlayerSide side) { }
	// RVA: 0x1ce226c VA: 0x75942fa26c
	public Int32 SetLegionGold(Int32 value, PlayerSide side) { }
	// RVA: 0x1ce515c VA: 0x75942fd15c
	public Void AddLegionGold(Int32 addValue, PlayerSide side) { }
	// RVA: 0x1cea728 VA: 0x7594302728
	public Void GetGoldViaProfessionBuffCount(Character source, Int32 goldPerBuff) { }
	// RVA: 0x1cea7e4 VA: 0x75943027e4
	public Int32 GetCardsNumByType(LegionCardLibraryType cardType) { }
	// RVA: 0x1cea8d4 VA: 0x75943028d4
	public Int32 GetLegionDangerLevel() { }
	// RVA: 0x1cea93c VA: 0x759430293c
	public Void RefreshLegionModeDangerLevel(Int32 level) { }
	// RVA: 0x1ceaadc VA: 0x7594302adc
	public LegionCharacterStatus GetOwnerStatus(Character character, Boolean initIfNull) { }
	// RVA: 0x1ceab74 VA: 0x7594302b74
	public Boolean ReplaceCharacter(Character source, Character target) { }
	// RVA: 0x1cead24 VA: 0x7594302d24
	public Boolean CheckCharacterNoOverlap(Character character) { }
	// RVA: 0x1ce5584 VA: 0x75942fd584
	public Void AddTargetProfessionLevelDirectly(ProfessionCategory profession, Character target, Int32 levelCount) { }
	// RVA: 0x1ceadc4 VA: 0x7594302dc4
	public Void ClearTargetProfessionLevel(Character character) { }
	// RVA: 0x1ceae50 VA: 0x7594302e50
	public Void RefreshTargetProfessionBuff(Character character) { }
	// RVA: 0x1ceaedc VA: 0x7594302edc
	public Void MarkCharReturnToHandAndKeepStatues(Character source, Boolean isRedrawOnReplace) { }
	// RVA: 0x1ceaf74 VA: 0x7594302f74
	public Void TemporaryAddEachProfessionStatus(Character target) { }
	// RVA: 0x1ceb000 VA: 0x7594303000
	public Void FinishTemporaryProfessionStatus(Character target) { }
	// RVA: 0x1ceb08c VA: 0x759430308c
	public Void MarkCardReturnToHand(Character source, Boolean needKeepStatus) { }
	// RVA: 0x1ceb178 VA: 0x7594303178
	public Int32 GetProfessionBuffMaxCnt(Character character) { }
	// RVA: 0x1ceb204 VA: 0x7594303204
	public Void ModifyProfessionBuffMaxCnt(Character character, Int32 addValue, Boolean isReset) { }
	// RVA: 0x1ceb2b4 VA: 0x75943032b4
	public Boolean CheckLastSelectCardsContainsProfessionCategory(ProfessionCategory profession) { }
	// RVA: 0x1ceb4a8 VA: 0x75943034a8
	public Void ModifyProfessionBuffDefaultAddCnt(Character character, Int32 addValue, Boolean isReset) { }
	// RVA: 0x1ceb558 VA: 0x7594303558
	public List`1 GetCharacterProfessionStatus(UInt32 characterUid) { }
	// RVA: 0x1ceb5e4 VA: 0x75943035e4
	public List`1 GetCharacterProfessionStatusWithHighLight(Character fromTarget, Character toTarget, List`1 hlList) { }
	// RVA: 0x1ceb694 VA: 0x7594303694
	public Int32 GetProfessionBuffNum(Character character) { }
	// RVA: 0x1ceb720 VA: 0x7594303720
	public Int32 GetStatusProfessionCnt(Character character) { }
	// RVA: 0x1ceb7ac VA: 0x75943037ac
	public Int32 GetSpecifiedProfessionStatusBuffCnt(Character character, ProfessionCategory queryProfession) { }
	// RVA: 0x1ceb844 VA: 0x7594303844
	public Card FindUsingCardByUniqueId(UInt32 uid) { }
	// RVA: 0x1ceb9fc VA: 0x75943039fc
	private Void _DoAnimForCardFullToHand(Card card) { }
	// RVA: 0x1ce3d68 VA: 0x75942fbd68
	public Boolean CheckCardIsInAllCardLibrary(Card card) { }
	// RVA: 0x1cebac4 VA: 0x7594303ac4
	public Boolean CheckCardIsInSomeCardLibrary(LegionCardLibraryType type, Card card) { }
	// RVA: 0x1cebba0 VA: 0x7594303ba0
	public Boolean CheckCardIsInOnlyCardLibrary(Card card) { }
	// RVA: 0x1ce3564 VA: 0x75942fb564
	public Boolean CheckCardIsUsing(Card card) { }
	// RVA: 0x1ce9cac VA: 0x7594301cac
	private Void _CheckRefreshedTokenCardList() { }
	// RVA: 0x1ce9adc VA: 0x7594301adc
	private Void _CheckRedrawToHandCardList() { }
	// RVA: 0x1ce9ec8 VA: 0x7594301ec8
	private Void _CheckBlastCardList() { }
	// RVA: 0x1ce345c VA: 0x75942fb45c
	private Void _CheckNeedRefillPendingFromUsed(Boolean isRedraw) { }
	// RVA: 0x1ce7da8 VA: 0x75942ffda8
	private Boolean _CheckNeedInitReShuffle(List`1 dataList) { }
	// RVA: 0x1ce5778 VA: 0x75942fd778
	private Void _OnDrawNextCardByManualEvent() { }
	// RVA: 0x1cebc50 VA: 0x7594303c50
	private Void _OnRefreshCardEvent() { }
	// RVA: 0x1ce5200 VA: 0x75942fd200
	private Void _LogDrawCardFromCardLibrary(Card rewardCard, String logKey) { }
	// RVA: 0x1cea9c0 VA: 0x75943029c0
	private Void _LogCurrentDangerLevel(Int32 level) { }
	// RVA: 0x1cebdbc VA: 0x7594303dbc
	private Boolean <>xLuaBaseProxy_get_hasExtraBuildCondition() { }
	// RVA: 0x1cebdc0 VA: 0x7594303dc0
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cebdc4 VA: 0x7594303dc4
	private Void <>xLuaBaseProxy_PreprocessPlayerData(List`1 P0) { }
	// RVA: 0x1cebdc8 VA: 0x7594303dc8
	private Void <>xLuaBaseProxy_PreprocessPlayerDeckList(ListDict`2 P0) { }
	// RVA: 0x1cebdcc VA: 0x7594303dcc
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x1cebdd0 VA: 0x7594303dd0
	private Options <>xLuaBaseProxy_PostprocessLevelOptions(Options P0) { }
	// RVA: 0x1cebdd4 VA: 0x7594303dd4
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cebdd8 VA: 0x7594303dd8
	private Void <>xLuaBaseProxy_ParseBattleEvents(ActionData P0) { }
	// RVA: 0x1cebddc VA: 0x7594303ddc
	private Boolean <>xLuaBaseProxy_CheckBuildable(BuildCondition P0, Tile P1, Direction P2, Boolean P3, Boolean P4, BattleCharacterData P5, PlayerSide P6) { }
	// RVA: 0x1cebe58 VA: 0x7594303e58
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cebe5c VA: 0x7594303e5c
	private List`1 <>xLuaBaseProxy_GatherGlobalBuffs() { }
	// RVA: 0x1cebe60 VA: 0x7594303e60
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cebe64 VA: 0x7594303e64
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cebe68 VA: 0x7594303e68
	private Void <>xLuaBaseProxy_OnCharacterFinished(Character P0, FinishReason P1) { }
	// RVA: 0x1cebe6c VA: 0x7594303e6c
	private Void <>xLuaBaseProxy_OnCardListChanged(Card P0) { }
	// RVA: 0x1cebe70 VA: 0x7594303e70
	private Void <>xLuaBaseProxy_OnCardRecycle(Card P0) { }
	// RVA: 0x1cebe74 VA: 0x7594303e74
	private Boolean <>xLuaBaseProxy_CheckCardReadyToSpawn(Card P0) { }
}
```