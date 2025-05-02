# HandbookStoryStageData

**Namespace:** `Torappu`


## Fields

- `String charId`

- `String stageId`

- `String levelId`

- `String zoneId`

- `String code`

- `String name`

- `String loadingPicId`

- `String description`

- `Int64 stageGetTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HandbookStoryStageData
{
	public String charId; // 0x10
	public String stageId; // 0x18
	public String levelId; // 0x20
	public String zoneId; // 0x28
	public String code; // 0x30
	public String name; // 0x38
	public String loadingPicId; // 0x40
	public String description; // 0x48
	public List`1 unlockParam; // 0x50
	public List`1 rewardItem; // 0x58
	public Int64 stageGetTime; // 0x60


	// RVA: 0x34a2fa4 VA: 0x7595abafa4
	public Void .ctor() { }
}
```