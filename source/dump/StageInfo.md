# StageInfo

**Namespace:** ` `


## Fields

- `String stageId`

- `Int32 apCost`

- `StageDiffGroup diffGroup`

- `PlayerStageState state`

- `Boolean isOnBattle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StageInfo
{
	public String stageId; // 0x10
	public Int32 apCost; // 0x18
	public StageDiffGroup diffGroup; // 0x1c
	public PlayerStageState state; // 0x20
	public List`1 displayRewards; // 0x28
	public Boolean isOnBattle; // 0x30


	// RVA: 0x2f7ff60 VA: 0x7595597f60
	public Void .ctor(StageViewModel viewModel, Boolean isOnBattle) { }
}
```