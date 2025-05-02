# RoguelikeGameStageData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String linkedStageId`

- `String levelId`

- `String code`

- `String name`

- `String loadingPicId`

- `String description`

- `String eliteDesc`

- `Int32 isBoss`

- `Int32 isElite`

- `Difficulty difficulty`

- `String capsulePool`

- `Single capsuleProb`

- `String specialNodeId`


## Methods

- `Boolean ShouldSerializespecialNodeId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeGameStageData
{
	public String id; // 0x10
	public String linkedStageId; // 0x18
	public String levelId; // 0x20
	public String[] levelReplaceIds; // 0x28
	public String code; // 0x30
	public String name; // 0x38
	public String loadingPicId; // 0x40
	public String description; // 0x48
	public String eliteDesc; // 0x50
	public Int32 isBoss; // 0x58
	public Int32 isElite; // 0x5c
	public Difficulty difficulty; // 0x60
	public String capsulePool; // 0x68
	public Single capsuleProb; // 0x70
	public List`1 vutresProb; // 0x78
	public List`1 boxProb; // 0x80
	public String specialNodeId; // 0x88


	// RVA: 0x34ab778 VA: 0x7595ac3778
	public Boolean ShouldSerializespecialNodeId() { }
	// RVA: 0x34ab798 VA: 0x7595ac3798
	public Void .ctor() { }
}
```