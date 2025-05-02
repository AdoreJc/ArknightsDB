# GameStatus

**Namespace:** ` `


## Fields

- `BattlePlayerAutoChessData data`

- `RuntimeIndexer indexer`

- `Int32 sheild`

- `Int32 reachExitEnemyCnt`

- `Int32 enemyMaxCnt`

- `Int32 enemyCnt`

- `Int32 countdown`

- `Int32 playerCharacterCnt`

- `Int32 currentInHandCnt`

- `SpeedLevel speedLevel`

- `EnableStateWithKey isHudLockedKeys`

- `EnableStateWithKey isDragLockedKeys`

- `Boolean hasEnterBattleStateAlready`

- `Boolean isPaused`


## Methods

- `Void InitData(PlayerAutoChessV1Activity, ActivityAutoChessVerify1Data)`

- `Void SetDeployStatus(Int32, Int32)`

- `Void SetSpeedLevel(SpeedLevel)`

- `Void SetPause(Boolean)`

- `DeckChessConfig _GetConfig(String, Act1VAutoChessCharShopChessData, Act1VAutoChessCharChessData, AutoChessCharCard, String)`

- `Void LoadData(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void LoadBattle(AutoChessGame)`

- `Void SetReachExitEnemyCnt(Int32, Int32, Int32)`

- `Void SetHudLock(Boolean, String)`

- `Void SetDragLock(Boolean, String)`

- `Void SetCountDown(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameStatus : AutoChessViewModelBase
{
	public BattlePlayerAutoChessData data; // 0x18
	public RuntimeIndexer indexer; // 0x20
	public Dictionary`2 deckChessConfig; // 0x28
	public ListDict`2 tokenInstId2MaxDeployCnt; // 0x30
	public Int32 sheild; // 0x38
	public Int32 reachExitEnemyCnt; // 0x3c
	public Int32 enemyMaxCnt; // 0x40
	public Int32 enemyCnt; // 0x44
	public Int32 countdown; // 0x48
	public Int32 playerCharacterCnt; // 0x4c
	public Int32 currentInHandCnt; // 0x50
	public SpeedLevel speedLevel; // 0x54
	public EnableStateWithKey isHudLockedKeys; // 0x58
	public EnableStateWithKey isDragLockedKeys; // 0x60
	public Boolean hasEnterBattleStateAlready; // 0x68
	public Boolean isPaused; // 0x69
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_SetDeployStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetSpeedLevel; // 0x10
	private static DelegateBridge __Hotfix0_SetPause; // 0x18
	private static DelegateBridge __Hotfix0__GetConfig; // 0x20
	private static DelegateBridge __Hotfix0__AppendUniequip; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_LoadBattle; // 0x38
	private static DelegateBridge __Hotfix0_SetReachExitEnemyCnt; // 0x40
	private static DelegateBridge __Hotfix0_SetHudLock; // 0x48
	private static DelegateBridge __Hotfix0_SetDragLock; // 0x50
	private static DelegateBridge __Hotfix0_SetCountDown; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x1c9a1a8 VA: 0x75942b21a8
	public Void InitData(PlayerAutoChessV1Activity game, ActivityAutoChessVerify1Data gameData) { }
	// RVA: 0x1c9af6c VA: 0x75942b2f6c
	public Void SetDeployStatus(Int32 currentInHandCnt, Int32 currentCharacterCnt) { }
	// RVA: 0x1c99fac VA: 0x75942b1fac
	public Void SetSpeedLevel(SpeedLevel level) { }
	// RVA: 0x1c94f3c VA: 0x75942acf3c
	public Void SetPause(Boolean isPause) { }
	// RVA: 0x1c9abbc VA: 0x75942b2bbc
	private DeckChessConfig _GetConfig(String charId, Act1VAutoChessCharShopChessData shopChessData, Act1VAutoChessCharChessData chessData, AutoChessCharCard cardData, String chessId) { }
	// RVA: 0x1c9aff8 VA: 0x75942b2ff8
	private static Void _AppendUniequip(Act1VAutoChessCharShopChessData shopChessData, Act1VAutoChessCharChessData chessData, AutoChessCharCard cardData, AdvancedCharacterInst inst) { }
	// RVA: 0x1c9b220 VA: 0x75942b3220
	public Void LoadData(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x1c9b2c8 VA: 0x75942b32c8
	public Void LoadBattle(AutoChessGame game) { }
	// RVA: 0x1c9b3a8 VA: 0x75942b33a8
	public Void SetReachExitEnemyCnt(Int32 cnt, Int32 enemyCnt, Int32 enemyMax) { }
	// RVA: 0x1c9b474 VA: 0x75942b3474
	public Void SetHudLock(Boolean hudLock, String lockKey) { }
	// RVA: 0x1c9b518 VA: 0x75942b3518
	public Void SetDragLock(Boolean hudLock, String lockKey) { }
	// RVA: 0x1c9b5bc VA: 0x75942b35bc
	public Void SetCountDown(Int32 cnt) { }
	// RVA: 0x1c91464 VA: 0x75942a9464
	public Void .ctor() { }
}
```