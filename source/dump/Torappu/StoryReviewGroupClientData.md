# StoryReviewGroupClientData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String name`

- `StoryReviewEntryType entryType`

- `StoryReviewType actType`

- `Int64 startTime`

- `Int64 endTime`

- `Int64 startShowTime`

- `Int64 endShowTime`

- `Int64 remakeStartTime`

- `Int64 remakeEndTime`

- `String storyEntryPicId`

- `String storyPicId`

- `String storyMainColor`

- `Int32 customType`

- `String storyCompleteMedalId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryReviewGroupClientData
{
	public String id; // 0x10
	public String name; // 0x18
	public StoryReviewEntryType entryType; // 0x20
	public StoryReviewType actType; // 0x24
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	public Int64 startShowTime; // 0x38
	public Int64 endShowTime; // 0x40
	public Int64 remakeStartTime; // 0x48
	public Int64 remakeEndTime; // 0x50
	public String storyEntryPicId; // 0x58
	public String storyPicId; // 0x60
	public String storyMainColor; // 0x68
	public Int32 customType; // 0x70
	public String storyCompleteMedalId; // 0x78
	public ItemBundle[] rewards; // 0x80
	public List`1 infoUnlockDatas; // 0x88


	// RVA: 0x34f81a0 VA: 0x7595b101a0
	public Void .ctor() { }
}
```