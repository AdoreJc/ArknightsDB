# BattlePlayerAutoChessData

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `Boolean isInSelecting`

- `Int32 round`

- `Int32 shopLevel`

- `Int32 lifePoint`

- `Int32 gameState`

- `Int32 charLimitAdd`

- `Int32 currentForceEffectCnt`

- `Int32 upgradeStoreNeedCoin`

- `Int32 currentCoin`

- `Int32 refreshPrice`

- `String roundId`

- `String modeId`

- `String enemyForceId`

- `Boolean isGameReadyToFinished`

- `Act1VAutoChessModeType modeType`

- `Boolean isInSpecialRefresh`

- `Boolean isShopFrozen`

- `BattleGameInfo gameInfo`

- `BattleGameInfo gameInfoCached`

- `EffectInfoViewModel effectInfo`

- `TipBattleInfoViewModel tipBattleInfoInfo`

- `ShopViewModel shopViewModel`


## Properties

- `Boolean displayShopFrozen`


## Methods

- `Boolean get_displayShopFrozen()`

- `Void LoadData(AutoChessGame, ActivityAutoChessVerify1Data, Dictionary`2)`

- `Void _UpdateBasic(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void _UpdateInst(AutoChessGame)`

- `Void LoadFromGame(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void LoadBattle(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void _LoadExtraEnabledLevel(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void _UpdateMisc(AutoChessGame, ActivityAutoChessVerify1Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public class BattlePlayerAutoChessData : AutoChessViewModelBase
{
	private static HashSet`1 s_sharedNeedRemoveSet; // 0x0
	private static List`1 s_cachedInsts; // 0x8
	private static List`1 s_cachedAutoChessInsts; // 0x10
	public Boolean isInSelecting; // 0x14
	public Int32 round; // 0x18
	public Int32 shopLevel; // 0x1c
	public Int32 lifePoint; // 0x20
	public Int32 gameState; // 0x24
	public Int32 charLimitAdd; // 0x28
	public Int32 currentForceEffectCnt; // 0x2c
	public Int32 upgradeStoreNeedCoin; // 0x30
	public Int32 currentCoin; // 0x34
	public Int32 refreshPrice; // 0x38
	public String roundId; // 0x40
	public String modeId; // 0x48
	public String enemyForceId; // 0x50
	public List`1 extraEnabledEnemyBranch; // 0x58
	public Dictionary`2 chessPurchase; // 0x60
	public Dictionary`2 battleLayers; // 0x68
	public Boolean isGameReadyToFinished; // 0x70
	public Act1VAutoChessModeType modeType; // 0x74
	public Boolean isInSpecialRefresh; // 0x78
	public Boolean isShopFrozen; // 0x79
	public List`1 battle; // 0x80
	public List`1 equips; // 0x88
	public ListDict`2 instId2ChessId; // 0x90
	public ListDict`2 ownedChessIdCnt; // 0x98
	public ListDict`2 instId2Equips; // 0xa0
	public Dictionary`2 spellUsing; // 0xa8
	public BattleGameInfo gameInfo; // 0xb0
	public BattleGameInfo gameInfoCached; // 0xb8
	public EffectInfoViewModel effectInfo; // 0xc0
	public TipBattleInfoViewModel tipBattleInfoInfo; // 0xc8
	public ShopViewModel shopViewModel; // 0xd0
	private static DelegateBridge __Hotfix0_get_displayShopFrozen; // 0x18
	private static DelegateBridge __Hotfix0_get_shopChesses; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0__UpdateBasic; // 0x30
	private static DelegateBridge __Hotfix0__UpdateInst; // 0x38
	private static DelegateBridge __Hotfix0_LoadFromGame; // 0x40
	private static DelegateBridge __Hotfix0_LoadBattle; // 0x48
	private static DelegateBridge __Hotfix0__LoadExtraEnabledLevel; // 0x50
	private static DelegateBridge __Hotfix0__UpdateMisc; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean displayShopFrozen { get; }
	public List`1 shopChesses { get; }

	// RVA: 0x1cfad94 VA: 0x7594312d94
	public Boolean get_displayShopFrozen() { }
	// RVA: 0x1cfae24 VA: 0x7594312e24
	public List`1 get_shopChesses() { }
	// RVA: 0x1cfaea8 VA: 0x7594312ea8
	public Void LoadData(AutoChessGame game, ActivityAutoChessVerify1Data gamedata, Dictionary`2 deckConfig) { }
	// RVA: 0x1cfafdc VA: 0x7594312fdc
	private Void _UpdateBasic(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x1cfb784 VA: 0x7594313784
	private Void _UpdateInst(AutoChessGame game) { }
	// RVA: 0x1cfc118 VA: 0x7594314118
	public Void LoadFromGame(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x1cfc990 VA: 0x7594314990
	public Void LoadBattle(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x1cfc240 VA: 0x7594314240
	private Void _LoadExtraEnabledLevel(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x1cfc474 VA: 0x7594314474
	private Void _UpdateMisc(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x1cfce50 VA: 0x7594314e50
	public Void .ctor() { }
	// RVA: 0x1cfd3c4 VA: 0x75943153c4
	private static Void .cctor() { }
}
```