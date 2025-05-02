# EnemyDuelSingleBattleFinishResponse

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `ChoiceCntInfo choiceCnt`

- `String commentId`

- `Boolean isHighScore`

- `DailyMissionInfo dailyMission`

- `Int32 bp`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelSingleBattleFinishResponse : DefaultFinishBattleResponse
{
	public ChoiceCntInfo choiceCnt; // 0xa0
	public String commentId; // 0xa8
	public Boolean isHighScore; // 0xb0
	public List`1 rankList; // 0xb8
	public DailyMissionInfo dailyMission; // 0xc0
	public Int32 bp; // 0xc8


	// RVA: 0x2943ddc VA: 0x7594f5bddc
	public Void .ctor() { }
}
```