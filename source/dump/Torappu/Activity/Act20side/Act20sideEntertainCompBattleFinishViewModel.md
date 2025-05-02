# Act20sideEntertainCompBattleFinishViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String stageName`

- `Int32 performanceScore`

- `Int32 expressionScore`

- `Int32 operationScore`

- `Int32 totalScore`

- `CartCompetitionRank rank`

- `Boolean isNewRank`

- `Int32 rankIndex`


## Methods

- `Void LoadData(CommonFinishBattleResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideEntertainCompBattleFinishViewModel : IHotfixable
{
	public String stageName; // 0x10
	public Int32 performanceScore; // 0x18
	public Int32 expressionScore; // 0x1c
	public Int32 operationScore; // 0x20
	public Int32 totalScore; // 0x24
	public CartCompetitionRank rank; // 0x28
	public Boolean isNewRank; // 0x2c
	public Int32 rankIndex; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32ff9d4 VA: 0x75959179d4
	public Void LoadData(CommonFinishBattleResponse response) { }
	// RVA: 0x32ff964 VA: 0x7595917964
	public Void .ctor() { }
}
```