# Deck

**Namespace:** `Torappu.Battle`


## Fields

- `SpawnDetailsTracker m_spawnDetailsTracker`

- `Int32 <initCostUp>k__BackingField`

- `Int32 <initCharacterLimitUp>k__BackingField`

- `Options <options>k__BackingField`

- `PlayerSide <playerSide>k__BackingField`

- `DeckManagedCardBuffController m_managedCardBuffController`


## Properties

- `Int32 initCostUp`

- `Int32 initCharacterLimitUp`

- `Options options`

- `PlayerSide playerSide`

- `DeckManagedCardBuffController managedCardBuffController`


## Methods

- `Void set_deckModifiers(List`1)`

- `Void set_deckLikeRuntimeCostModifiers(List`1)`

- `Void set_deckMiscModifier(List`1)`

- `Void set_cards(Card[])`

- `Int32 get_initCostUp()`

- `Void set_initCostUp(Int32)`

- `Int32 get_initCharacterLimitUp()`

- `Void set_initCharacterLimitUp(Int32)`

- `Options get_options()`

- `Void set_options(Options)`

- `PlayerSide get_playerSide()`

- `Void set_playerSide(PlayerSide)`

- `Void _PreprocessOverrideableModifiers(List`1)`

- `Void PreprocessDeck()`

- `Void RechargeToken(UInt32, Int32, RechargeTiming, Boolean)`

- `Void ForceRechargeToken(String, Int32, RechargeTiming)`

- `Void ForceRechargeToken(UInt32, Int32, RechargeTiming, Boolean)`

- `Void RecycleCard(UInt32)`

- `Void RecycleTokenCard(UInt32)`

- `RectTransform LoadCardEffectPluginIfNot(String)`

- `Boolean SpawnCharacterOrToken(UInt32, Direction, Tile, Boolean, Boolean, Boolean, Boolean)`

- `Boolean SpawnTokenFreely(String, Character, Direction, Tile, Boolean, Boolean, Boolean, out, Boolean, Boolean)`

- `Boolean SpawnCharacterOrToken(Card, Direction, Tile, Boolean, Boolean, Boolean, out, Boolean, Boolean, Boolean)`

- `Boolean ActivateHiddenCard(String, out)`

- `Boolean ActivateHiddenCard(Card)`

- `Boolean HideCard(Card)`

- `Void OnFixedUpdate(FP)`

- `Card FindCard(UInt32)`

- `Card FindCardById(String)`

- `Boolean FindAllCardById(String, List`1)`

- `Card FindCardByAlias(String)`

- `Void _PostProcessDeckModifiers(IList`1)`

- `Void _PostProcessDeckLikeRuntimeCostModifiers(IList`1)`

- `Void _PostProcessDeckRuntimeMiscModifiers(IList`1)`

- `Boolean _TryGetToken(Card, out)`

- `Void OnCardListChanged(Card)`

- `Void OnCardCostChanged(Card)`

- `Void OnCardEffectChanged(Card)`

- `Void OnCardAppearanceChangedE(Card)`

- `Void OnCardDrawn(Card)`

- `Void OnCardSpawn(GridPosition, Direction, Card)`

- `Void OnCardGetOffHand(Card)`

- `Void OnCardPutInHand(Card)`

- `Void OnReset()`

- `DeckManagedCardBuffController get_managedCardBuffController()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Deck : IHotfixable
{
	public Action`1 onCardListChanged; // 0x10
	public Action`1 onCardCostChanged; // 0x18
	public Action`1 onCardEffectChanged; // 0x20
	public Action`1 onCardAppearanceChangedE; // 0x28
	public Action`3 onCardSpawn; // 0x30
	private Dictionary`2 m_cardMap; // 0x38
	private Dictionary`2 m_tokenMap; // 0x40
	private Card[] m_cards; // 0x48
	private SpawnDetailsTracker m_spawnDetailsTracker; // 0x50
	private List`1 m_deckModifiers; // 0x58
	private List`1 m_deckLikeRuntimeCostModifiers; // 0x60
	private List`1 m_deckMiscModifier; // 0x68
	private Dictionary`2 m_loadedCardEffectPlugins; // 0x70
	private Int32 <initCostUp>k__BackingField; // 0x78
	private Int32 <initCharacterLimitUp>k__BackingField; // 0x7c
	private Options <options>k__BackingField; // 0x80
	private PlayerSide <playerSide>k__BackingField; // 0x88
	private DeckManagedCardBuffController m_managedCardBuffController; // 0x90
	private static DelegateBridge __Hotfix0_set_deckModifiers; // 0x0
	private static DelegateBridge __Hotfix0_get_deckModifiers; // 0x8
	private static DelegateBridge __Hotfix0_set_deckLikeRuntimeCostModifiers; // 0x10
	private static DelegateBridge __Hotfix0_get_deckLikeRuntimeCostModifiers; // 0x18
	private static DelegateBridge __Hotfix0_set_deckMiscModifier; // 0x20
	private static DelegateBridge __Hotfix0_get_deckMiscModifier; // 0x28
	private static DelegateBridge __Hotfix0_get_cards; // 0x30
	private static DelegateBridge __Hotfix0_set_cards; // 0x38
	private static DelegateBridge __Hotfix0_get_initCostUp; // 0x40
	private static DelegateBridge __Hotfix0_set_initCostUp; // 0x48
	private static DelegateBridge __Hotfix0_get_initCharacterLimitUp; // 0x50
	private static DelegateBridge __Hotfix0_set_initCharacterLimitUp; // 0x58
	private static DelegateBridge __Hotfix0_get_options; // 0x60
	private static DelegateBridge __Hotfix0_set_options; // 0x68
	private static DelegateBridge __Hotfix0_get_playerSide; // 0x70
	private static DelegateBridge __Hotfix0_set_playerSide; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80
	private static DelegateBridge __Hotfix0__PreprocessOverrideableModifiers; // 0x88
	private static DelegateBridge __Hotfix0_PreprocessDeck; // 0x90
	private static DelegateBridge __Hotfix0_RechargeToken; // 0x98
	private static DelegateBridge __Hotfix0_ForceRechargeToken; // 0xa0
	private static DelegateBridge __Hotfix1_ForceRechargeToken; // 0xa8
	private static DelegateBridge __Hotfix0_RecycleCard; // 0xb0
	private static DelegateBridge __Hotfix0_RecycleTokenCard; // 0xb8
	private static DelegateBridge __Hotfix0_LoadCardEffectPluginIfNot; // 0xc0
	private static DelegateBridge __Hotfix0_SpawnCharacterOrToken; // 0xc8
	private static DelegateBridge __Hotfix0_SpawnTokenFreely; // 0xd0
	private static DelegateBridge __Hotfix1_SpawnCharacterOrToken; // 0xd8
	private static DelegateBridge __Hotfix0_ActivateHiddenCard; // 0xe0
	private static DelegateBridge __Hotfix1_ActivateHiddenCard; // 0xe8
	private static DelegateBridge __Hotfix0_HideCard; // 0xf0
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0xf8
	private static DelegateBridge __Hotfix0_FindCard; // 0x100
	private static DelegateBridge __Hotfix0_FindCardById; // 0x108
	private static DelegateBridge __Hotfix0_FindAllCardById; // 0x110
	private static DelegateBridge __Hotfix0_FindCardByAlias; // 0x118
	private static DelegateBridge __Hotfix0__PostProcessDeckModifiers; // 0x120
	private static DelegateBridge __Hotfix0__PostProcessDeckLikeRuntimeCostModifiers; // 0x128
	private static DelegateBridge __Hotfix0__PostProcessDeckRuntimeMiscModifiers; // 0x130
	private static DelegateBridge __Hotfix0__TryGetToken; // 0x138
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x140
	private static DelegateBridge __Hotfix0_OnCardCostChanged; // 0x148
	private static DelegateBridge __Hotfix0_OnCardEffectChanged; // 0x150
	private static DelegateBridge __Hotfix0_OnCardAppearanceChangedE; // 0x158
	private static DelegateBridge __Hotfix0_OnCardDrawn; // 0x160
	private static DelegateBridge __Hotfix0_OnCardSpawn; // 0x168
	private static DelegateBridge __Hotfix0_OnCardGetOffHand; // 0x170
	private static DelegateBridge __Hotfix0_OnCardPutInHand; // 0x178
	private static DelegateBridge __Hotfix0_OnReset; // 0x180
	private static DelegateBridge __Hotfix0_get_managedCardBuffController; // 0x188

	public List`1 deckModifiers { get; set; }
	public List`1 deckLikeRuntimeCostModifiers { get; set; }
	public List`1 deckMiscModifier { get; set; }
	public Card[] cards { get; set; }
	public Int32 initCostUp { get; set; }
	public Int32 initCharacterLimitUp { get; set; }
	public Options options { get; set; }
	public PlayerSide playerSide { get; set; }
	public DeckManagedCardBuffController managedCardBuffController { get; }

	// RVA: 0x3fa81a4 VA: 0x75965c01a4
	public Void set_deckModifiers(List`1 value) { }
	// RVA: 0x3fa8228 VA: 0x75965c0228
	public List`1 get_deckModifiers() { }
	// RVA: 0x3fa8290 VA: 0x75965c0290
	public Void set_deckLikeRuntimeCostModifiers(List`1 value) { }
	// RVA: 0x3fa8314 VA: 0x75965c0314
	public List`1 get_deckLikeRuntimeCostModifiers() { }
	// RVA: 0x3fa837c VA: 0x75965c037c
	public Void set_deckMiscModifier(List`1 value) { }
	// RVA: 0x3fa8400 VA: 0x75965c0400
	public List`1 get_deckMiscModifier() { }
	// RVA: 0x3fa8468 VA: 0x75965c0468
	public Card[] get_cards() { }
	// RVA: 0x3fa84d0 VA: 0x75965c04d0
	public Void set_cards(Card[] value) { }
	// RVA: 0x3fa8554 VA: 0x75965c0554
	public Int32 get_initCostUp() { }
	// RVA: 0x3fa85bc VA: 0x75965c05bc
	private Void set_initCostUp(Int32 value) { }
	// RVA: 0x3fa8638 VA: 0x75965c0638
	public Int32 get_initCharacterLimitUp() { }
	// RVA: 0x3fa86a0 VA: 0x75965c06a0
	public Void set_initCharacterLimitUp(Int32 value) { }
	// RVA: 0x3fa871c VA: 0x75965c071c
	public Options get_options() { }
	// RVA: 0x3fa8780 VA: 0x75965c0780
	private Void set_options(Options value) { }
	// RVA: 0x3fa8804 VA: 0x75965c0804
	public PlayerSide get_playerSide() { }
	// RVA: 0x3fa886c VA: 0x75965c086c
	private Void set_playerSide(PlayerSide value) { }
	// RVA: 0x3fa88e8 VA: 0x75965c08e8
	public Void .ctor(BattlePlayerData playerData, Options options, PlayerSide playerSide) { }
	// RVA: 0x VA: 0x0
	private Void _PreprocessOverrideableModifiers(List`1 modifiers) { }
	// RVA: 0x3fa8f5c VA: 0x75965c0f5c
	public Void PreprocessDeck() { }
	// RVA: 0x3fa9b20 VA: 0x75965c1b20
	public Void RechargeToken(UInt32 uid, Int32 count, RechargeTiming timing, Boolean refreshRemainingCnt) { }
	// RVA: 0x3fa9d6c VA: 0x75965c1d6c
	public Void ForceRechargeToken(String key, Int32 count, RechargeTiming timing) { }
	// RVA: 0x3fa9fd4 VA: 0x75965c1fd4
	public Void ForceRechargeToken(UInt32 uid, Int32 count, RechargeTiming timing, Boolean refreshRemainingCnt) { }
	// RVA: 0x3faa0cc VA: 0x75965c20cc
	public Void RecycleCard(UInt32 instanceUid) { }
	// RVA: 0x3faa300 VA: 0x75965c2300
	public Void RecycleTokenCard(UInt32 instanceUid) { }
	// RVA: 0x3faa3c4 VA: 0x75965c23c4
	private RectTransform LoadCardEffectPluginIfNot(String name) { }
	// RVA: 0x3faa4cc VA: 0x75965c24cc
	public Boolean SpawnCharacterOrToken(UInt32 uid, Direction direction, Tile tile, Boolean strict, Boolean spawnManually, Boolean freely, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x3faaa24 VA: 0x75965c2a24
	public Boolean SpawnTokenFreely(String key, Character host, Direction direction, Tile tile, Boolean strict, Boolean spawnManually, Boolean refreshCooldown, out Character charOrToken, Boolean ignoreAdvancedBuildableMask, Boolean forceSpawn) { }
	// RVA: 0x3faa68c VA: 0x75965c268c
	public Boolean SpawnCharacterOrToken(Card card, Direction direction, Tile tile, Boolean strict, Boolean spawnManually, Boolean freely, out Character charOrToken, Boolean ignoreAdvancedBuildableMask, Boolean forceSpawn, Boolean ignoreHostAlive) { }
	// RVA: 0x3fab59c VA: 0x75965c359c
	public Boolean ActivateHiddenCard(String alias, out Card card) { }
	// RVA: 0x3fab828 VA: 0x75965c3828
	public Boolean ActivateHiddenCard(Card card) { }
	// RVA: 0x3faba60 VA: 0x75965c3a60
	public Boolean HideCard(Card card) { }
	// RVA: 0x3fabb34 VA: 0x75965c3b34
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x3faa5dc VA: 0x75965c25dc
	public Card FindCard(UInt32 uid) { }
	// RVA: 0x3fac154 VA: 0x75965c4154
	public Card FindCardById(String id) { }
	// RVA: 0x3fac38c VA: 0x75965c438c
	public Boolean FindAllCardById(String id, List`1 resultList) { }
	// RVA: 0x3fab658 VA: 0x75965c3658
	public Card FindCardByAlias(String alias) { }
	// RVA: 0x3fa9420 VA: 0x75965c1420
	private Void _PostProcessDeckModifiers(IList`1 deckModifiers) { }
	// RVA: 0x3fa98a4 VA: 0x75965c18a4
	private Void _PostProcessDeckLikeRuntimeCostModifiers(IList`1 decklikeRuntimeCostModifiers) { }
	// RVA: 0x3fa9624 VA: 0x75965c1624
	private Void _PostProcessDeckRuntimeMiscModifiers(IList`1 deckMiscModifiers) { }
	// RVA: 0x3faa1c8 VA: 0x75965c21c8
	private Boolean _TryGetToken(Card card, out TokenCard token) { }
	// RVA: 0x3fa9c20 VA: 0x75965c1c20
	public Void OnCardListChanged(Card newCard) { }
	// RVA: 0x3fac7c4 VA: 0x75965c47c4
	public Void OnCardCostChanged(Card card) { }
	// RVA: 0x3fac864 VA: 0x75965c4864
	public Void OnCardEffectChanged(Card card) { }
	// RVA: 0x3fac904 VA: 0x75965c4904
	public Void OnCardAppearanceChangedE(Card card) { }
	// RVA: 0x3fac9a4 VA: 0x75965c49a4
	public Void OnCardDrawn(Card card) { }
	// RVA: 0x3faca30 VA: 0x75965c4a30
	public Void OnCardSpawn(GridPosition pos, Direction dir, Card card) { }
	// RVA: 0x3facaf8 VA: 0x75965c4af8
	public Void OnCardGetOffHand(Card card) { }
	// RVA: 0x3faccac VA: 0x75965c4cac
	public Void OnCardPutInHand(Card card) { }
	// RVA: 0x3face60 VA: 0x75965c4e60
	public Void OnReset() { }
	// RVA: 0x3fad094 VA: 0x75965c5094
	public DeckManagedCardBuffController get_managedCardBuffController() { }
}
```