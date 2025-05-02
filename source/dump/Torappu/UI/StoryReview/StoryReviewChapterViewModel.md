# StoryReviewChapterViewModel

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `String id`

- `String name`

- `StoryReviewEntryType entryType`

- `StoryReviewType actType`

- `Int64 startTime`

- `Int64 endTime`

- `Int64 remakeStartTime`

- `Int64 remakeEndTime`

- `String storyEntryPicId`

- `String storyPicId`

- `String storyMainColor`

- `StoryReviewCustomType customType`

- `String storyCompleteMedalId`

- `Boolean rewardGot`

- `Int32 progress`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewChapterViewModel : IHotfixable
{
	public String id; // 0x10
	public String name; // 0x18
	public StoryReviewEntryType entryType; // 0x20
	public StoryReviewType actType; // 0x24
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	public Int64 remakeStartTime; // 0x38
	public Int64 remakeEndTime; // 0x40
	public String storyEntryPicId; // 0x48
	public String storyPicId; // 0x50
	public String storyMainColor; // 0x58
	public StoryReviewCustomType customType; // 0x60
	public String storyCompleteMedalId; // 0x68
	public ItemBundle[] rewards; // 0x70
	public List`1 storyReviewList; // 0x78
	public Boolean rewardGot; // 0x80
	public Int32 progress; // 0x84
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x275a270 VA: 0x7594d72270
	public Void .ctor() { }
}
```