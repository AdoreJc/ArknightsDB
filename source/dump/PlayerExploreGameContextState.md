# PlayerExploreGameContextState

**Namespace:** ` `


## Fields

- `String groupId`

- `String groupCode`

- `GameState state`

- `String stageId`

- `String nextStageId`

- `Int32 stageNodeIndex`

- `String blockStageId`

- `Int64 startTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayerExploreGameContextState
{
	public Dictionary`2 abilities; // 0x10
	public String groupId; // 0x18
	public String groupCode; // 0x20
	public GameState state; // 0x28
	public List`1 targets; // 0x30
	public String stageId; // 0x38
	public String nextStageId; // 0x40
	public Int32 stageNodeIndex; // 0x48
	public String blockStageId; // 0x50
	public List`1 broadCast; // 0x58
	public Int64 startTs; // 0x60


	// RVA: 0x32dc644 VA: 0x75958f4644
	public Void .ctor() { }
}
```