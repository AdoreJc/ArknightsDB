# StoryReviewInfoClientData

**Namespace:** `Torappu`


## Fields

- `StoryReviewType storyReviewType`

- `String storyId`

- `String storyGroup`

- `Int32 storySort`

- `String storyDependence`

- `Int32 storyCanShow`

- `String storyCode`

- `String storyName`

- `String storyPic`

- `String storyInfo`

- `Int32 storyCanEnter`

- `String storyTxt`

- `String avgTag`

- `StoryReviewUnlockType unLockType`

- `ItemType costItemType`

- `String costItemId`

- `Int32 costItemCount`

- `Int32 stageCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryReviewInfoClientData
{
	public StoryReviewType storyReviewType; // 0x10
	public String storyId; // 0x18
	public String storyGroup; // 0x20
	public Int32 storySort; // 0x28
	public String storyDependence; // 0x30
	public Int32 storyCanShow; // 0x38
	public String storyCode; // 0x40
	public String storyName; // 0x48
	public String storyPic; // 0x50
	public String storyInfo; // 0x58
	public Int32 storyCanEnter; // 0x60
	public String storyTxt; // 0x68
	public String avgTag; // 0x70
	public StoryReviewUnlockType unLockType; // 0x78
	public ItemType costItemType; // 0x7c
	public String costItemId; // 0x80
	public Int32 costItemCount; // 0x88
	public Int32 stageCount; // 0x8c
	public StageCondition[] requiredStages; // 0x90


	// RVA: 0x34f8198 VA: 0x7595b10198
	public Void .ctor() { }
}
```