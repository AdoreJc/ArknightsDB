# AutoChessRoundBattleFinishResponse

**Namespace:** ` `


## Fields

- `Int32 result`

- `AutoChessRoundBattleFinishState roundCompleteState`

- `AutoChessRoundBattleFinishOurSideData ourSide`

- `AutoChessRoundBattleFinishEnemySideData enemySide`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessRoundBattleFinishResponse : AutoChessInGameCommonResponse
{
	public Int32 result; // 0x30
	public AutoChessRoundBattleFinishState roundCompleteState; // 0x34
	public AutoChessRoundBattleFinishOurSideData ourSide; // 0x38
	public AutoChessRoundBattleFinishEnemySideData enemySide; // 0x40


	// RVA: 0x3384864 VA: 0x759599c864
	public Void .ctor() { }
}
```