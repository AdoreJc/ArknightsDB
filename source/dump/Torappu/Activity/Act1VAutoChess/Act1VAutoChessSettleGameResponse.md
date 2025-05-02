# Act1VAutoChessSettleGameResponse

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessSettleGameCompleteStateType completeState`

- `String modeId`

- `Int64 startAt`

- `Int64 finishAt`

- `Int32 rounds`

- `OurSide ourSide`

- `RewardRelated normal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameResponse : PlayerDeltaResponse
{
	public Act1VAutoChessSettleGameCompleteStateType completeState; // 0x28
	public String modeId; // 0x30
	public Int64 startAt; // 0x38
	public Int64 finishAt; // 0x40
	public Int32 rounds; // 0x48
	public OurSide ourSide; // 0x50
	public Dictionary`2 enemySide; // 0x58
	public List`1 unlockBand; // 0x60
	public List`1 onStageChars; // 0x68
	public List`1 onStageEquips; // 0x70
	public RewardRelated normal; // 0x78


	// RVA: 0x3360d68 VA: 0x7595978d68
	public Void .ctor() { }
}
```