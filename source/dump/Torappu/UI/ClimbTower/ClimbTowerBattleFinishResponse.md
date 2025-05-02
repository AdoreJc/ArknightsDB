# ClimbTowerBattleFinishResponse

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Boolean isNewRecord`

- `String show`

- `ClimbTowerSettleGameReward reward`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBattleFinishResponse : DefaultFinishBattleResponse
{
	public Boolean isNewRecord; // 0xa0
	public ClimbTowerBattleFinishDropInfo[] drop; // 0xa8
	public ClimbTowerBattleFinishDropInfo[] offer; // 0xb0
	public String show; // 0xb8
	public ClimbTowerBattleFinishTrapInfo[] trap; // 0xc0
	public ClimbTowerSettleGameReward reward; // 0xc8


	// RVA: 0x2c729d8 VA: 0x759528a9d8
	public Void .ctor() { }
}
```