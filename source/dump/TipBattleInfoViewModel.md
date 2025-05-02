# TipBattleInfoViewModel

**Namespace:** ` `


## Fields

- `Int32 m_currentDamage`


## Properties

- `AutoChessDataCenter center`

- `Int32 currentDamage`


## Methods

- `AutoChessDataCenter get_center()`

- `Int32 GetDeployedCharCntByProfession(ProfessionCategory)`

- `Int32 GetDeployedCharCntByTag(String)`

- `Int32 GetPurchasedCharCntByTag(String)`

- `Int32 GetBattleLayerCntByKey(String, Int32)`

- `Int32 GetDeployedCharCntByDifferentChessLevel()`

- `Int32 GetEquipBuffCntInBattle(String, Int32)`

- `Int32 get_currentDamage()`

- `Void LoadData(AutoChessGame, BattleGameInfo, Dictionary`2)`

- `Void _LoadCurrentDamage(AutoChessGame, List`1)`

- `Void _LoadPurchasedCount(ActivityAutoChessVerify1Data)`

- `Void _LoadTagData(DeckChessConfig, ActivityAutoChessVerify1Data, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TipBattleInfoViewModel : AutoChessViewModelBase
{
	private const String BUFF_COUNT_IN_BATTLE; // 0x0
	private Dictionary`2 m_professionCnts; // 0x18
	private Dictionary`2 m_tagCnts; // 0x20
	private Dictionary`2 m_purchasedTagCnts; // 0x28
	private List`1 m_uniqueChessLevels; // 0x30
	private List`1 m_battleInsts; // 0x38
	private Int32 m_currentDamage; // 0x40
	private static DelegateBridge __Hotfix0_get_center; // 0x0
	private static DelegateBridge __Hotfix0_GetDeployedCharCntByProfession; // 0x8
	private static DelegateBridge __Hotfix0_GetDeployedCharCntByTag; // 0x10
	private static DelegateBridge __Hotfix0_GetPurchasedCharCntByTag; // 0x18
	private static DelegateBridge __Hotfix0_GetBattleLayerCntByKey; // 0x20
	private static DelegateBridge __Hotfix0_GetDeployedCharCntByDifferentChessLevel; // 0x28
	private static DelegateBridge __Hotfix0_GetEquipBuffCntInBattle; // 0x30
	private static DelegateBridge __Hotfix0_get_currentDamage; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__LoadCurrentDamage; // 0x48
	private static DelegateBridge __Hotfix0__LoadPurchasedCount; // 0x50
	private static DelegateBridge __Hotfix0__LoadTagData; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private AutoChessDataCenter center { get; }
	public Int32 currentDamage { get; }

	// RVA: 0x1d050b0 VA: 0x759431d0b0
	private AutoChessDataCenter get_center() { }
	// RVA: 0x1d0512c VA: 0x759431d12c
	public Int32 GetDeployedCharCntByProfession(ProfessionCategory profession) { }
	// RVA: 0x1d0520c VA: 0x759431d20c
	public Int32 GetDeployedCharCntByTag(String tag) { }
	// RVA: 0x1d052ec VA: 0x759431d2ec
	public Int32 GetPurchasedCharCntByTag(String tag) { }
	// RVA: 0x1d053cc VA: 0x759431d3cc
	public Int32 GetBattleLayerCntByKey(String key, Int32 instId) { }
	// RVA: 0x1d056ac VA: 0x759431d6ac
	public Int32 GetDeployedCharCntByDifferentChessLevel() { }
	// RVA: 0x1d0572c VA: 0x759431d72c
	public Int32 GetEquipBuffCntInBattle(String key, Int32 instId) { }
	// RVA: 0x1d05e70 VA: 0x759431de70
	public Int32 get_currentDamage() { }
	// RVA: 0x1d05ed8 VA: 0x759431ded8
	public Void LoadData(AutoChessGame game, BattleGameInfo gameInfo, Dictionary`2 deckConfig) { }
	// RVA: 0x1d06f64 VA: 0x759431ef64
	private Void _LoadCurrentDamage(AutoChessGame game, List`1 inBattleInst) { }
	// RVA: 0x1d06c0c VA: 0x759431ec0c
	private Void _LoadPurchasedCount(ActivityAutoChessVerify1Data gameData) { }
	// RVA: 0x1d066ac VA: 0x759431e6ac
	private Void _LoadTagData(DeckChessConfig config, ActivityAutoChessVerify1Data gameData, Int32 instId) { }
	// RVA: 0x1d0723c VA: 0x759431f23c
	public Void .ctor() { }
}
```