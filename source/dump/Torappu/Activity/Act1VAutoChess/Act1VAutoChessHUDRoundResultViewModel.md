# Act1VAutoChessHUDRoundResultViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `AutoChessRoundBattleFinishState finishState`

- `Int32 enemyHpLostSize`

- `Int32 playerHpLostSize`

- `String currForceId`

- `String currForceName`

- `String currForceIcon`

- `Boolean isBonusRound`

- `Boolean isEnemyKilled`


## Methods

- `Void LoadData(AutoChessGame, ActivityAutoChessVerify1Data, AutoChessRoundBattleFinishRespData)`

- `Void _Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDRoundResultViewModel
{
	public AutoChessRoundBattleFinishState finishState; // 0x10
	public Int32 enemyHpLostSize; // 0x14
	public Int32 playerHpLostSize; // 0x18
	public String currForceId; // 0x20
	public String currForceName; // 0x28
	public String currForceIcon; // 0x30
	public Boolean isBonusRound; // 0x38
	public Boolean isEnemyKilled; // 0x39


	// RVA: 0x337f6f0 VA: 0x75959976f0
	public Void LoadData(AutoChessGame game, ActivityAutoChessVerify1Data data, AutoChessRoundBattleFinishRespData resp) { }
	// RVA: 0x337f874 VA: 0x7595997874
	private Void _Clear() { }
	// RVA: 0x337f8ec VA: 0x75959978ec
	public Void .ctor() { }
}
```