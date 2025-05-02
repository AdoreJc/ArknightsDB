# AutoChessGame

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String startTs`

- `Int32 seed`

- `String mode`

- `AutoChessGameState state`

- `String bandId`

- `String currForce`

- `Int32 rewardEnemyRound`

- `Health health`

- `Int32 turn`

- `String roundId`

- `String stageId`

- `Store store`

- `Table table`

- `Buff buff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class AutoChessGame
{
	public String startTs; // 0x10
	public Int32 seed; // 0x18
	public String mode; // 0x20
	public AutoChessGameState state; // 0x28
	public String bandId; // 0x30
	public Effect[] talent; // 0x38
	public String[] talentChoices; // 0x40
	public String currForce; // 0x48
	public Dictionary`2 allForces; // 0x50
	public Int32 rewardEnemyRound; // 0x58
	public Health health; // 0x60
	public Int32 turn; // 0x68
	public String roundId; // 0x70
	public String stageId; // 0x78
	public Store store; // 0x80
	public Table table; // 0x88
	public Buff buff; // 0x90


	// RVA: 0x3384ba0 VA: 0x759599cba0
	public Void .ctor() { }
}
```