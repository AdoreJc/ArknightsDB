# StorylineLocationData

**Namespace:** `Torappu`


## Fields

- `String locationId`

- `StorylineLocationType locationType`

- `Int32 sortId`

- `Int64 startTime`

- `String presentStageId`

- `String unlockStageId`

- `String relevantStorySetId`

- `StorylineMainlineSplitData mainlineSplitData`


## Methods

- `Boolean ShouldSerializepresentStageId()`

- `Boolean ShouldSerializeunlockStageId()`

- `Boolean ShouldSerializerelevantStorySetId()`

- `Boolean ShouldSerializemainlineSplitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StorylineLocationData
{
	public String locationId; // 0x10
	public StorylineLocationType locationType; // 0x18
	public Int32 sortId; // 0x1c
	public Int64 startTime; // 0x20
	public String presentStageId; // 0x28
	public String unlockStageId; // 0x30
	public String relevantStorySetId; // 0x38
	public StorylineMainlineSplitData mainlineSplitData; // 0x40


	// RVA: 0x34f7f14 VA: 0x7595b0ff14
	public Boolean ShouldSerializepresentStageId() { }
	// RVA: 0x34f7f34 VA: 0x7595b0ff34
	public Boolean ShouldSerializeunlockStageId() { }
	// RVA: 0x34f7f54 VA: 0x7595b0ff54
	public Boolean ShouldSerializerelevantStorySetId() { }
	// RVA: 0x34f7f74 VA: 0x7595b0ff74
	public Boolean ShouldSerializemainlineSplitData() { }
	// RVA: 0x34f7f84 VA: 0x7595b0ff84
	public Void .ctor() { }
}
```