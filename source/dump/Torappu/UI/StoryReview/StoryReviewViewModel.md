# StoryReviewViewModel

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `String storyId`

- `String storyGroup`

- `Int32 storySort`

- `String storyName`

- `String storyPic`

- `String storyInfo`

- `String storyText`

- `String avgTag`

- `String storyMainPicId`

- `StoryReviewUnlockType unlockType`

- `ItemType costItemType`

- `String costItemId`

- `Int32 costItemCount`

- `String storyCode`

- `String storyDependence`

- `Boolean isLocked`

- `Boolean isRead`


## Methods

- `Int32 CompareTo(StoryReviewViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewViewModel : IHotfixable, IComparable`1
{
	public String storyId; // 0x10
	public String storyGroup; // 0x18
	public Int32 storySort; // 0x20
	public String storyName; // 0x28
	public String storyPic; // 0x30
	public String storyInfo; // 0x38
	public String storyText; // 0x40
	public String avgTag; // 0x48
	public String storyMainPicId; // 0x50
	public StoryReviewUnlockType unlockType; // 0x58
	public ItemType costItemType; // 0x5c
	public String costItemId; // 0x60
	public Int32 costItemCount; // 0x68
	public String storyCode; // 0x70
	public String storyDependence; // 0x78
	public StageCondition[] requiredStages; // 0x80
	public Boolean isLocked; // 0x88
	public Boolean isRead; // 0x89
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x275af9c VA: 0x7594d72f9c
	public Int32 CompareTo(StoryReviewViewModel viewModel) { }
	// RVA: 0x275aa78 VA: 0x7594d72a78
	public Void .ctor() { }
}
```