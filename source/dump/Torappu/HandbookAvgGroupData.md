# HandbookAvgGroupData

**Namespace:** `Torappu`


## Fields

- `String storySetId`

- `String storySetName`

- `Int32 sortId`

- `Int64 storyGetTime`

- `String charId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HandbookAvgGroupData
{
	public String storySetId; // 0x10
	public String storySetName; // 0x18
	public Int32 sortId; // 0x20
	public Int64 storyGetTime; // 0x28
	public List`1 rewardItem; // 0x30
	public List`1 unlockParam; // 0x38
	public List`1 avgList; // 0x40
	public String charId; // 0x48


	// RVA: 0x34a2fb4 VA: 0x7595abafb4
	public Void .ctor() { }
}
```