# Act10D5StoryViewModel

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `StoryReviewChapterViewModel chapterModel`


## Methods

- `Void LoadData(PlayerStoryReview, String)`

- `StoryReviewViewModel GetStoryReviewModel(String)`

- `Void RefreshAvailableViewModelList()`

- `Boolean _CheckPrevDependenceUnlocked(String)`

- `Void _RefreshPlayerData(StoryReviewChapterViewModel, PlayerStoryReviewUnlockInfo)`

- `Void _GenStoryReviewViewModel(ref, PlayerStoryReviewUnlockInfo)`

- `Boolean _ChapterShow(Int64, Int64)`

- `Boolean _GenRewardsStatus(String, PlayerStoryReview)`

- `Boolean _GetStoryReviewUnlocked(String, String, PlayerStoryReview)`

- `Boolean _GetStoryReviewRead(String, String, PlayerStoryReview)`

- `Int32 _GetProgress(PlayerStoryReview, String)`

- `Void OnActivityReviewDetailDataRefresh()`

- `Boolean CheckActivityOutOfTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StoryViewModel
{
	public StoryReviewChapterViewModel chapterModel; // 0x10
	public List`1 availableModelList; // 0x18


	// RVA: 0x3484414 VA: 0x7595a9c414
	public Void LoadData(PlayerStoryReview playerData, String activityId) { }
	// RVA: 0x3484a98 VA: 0x7595a9ca98
	public StoryReviewViewModel GetStoryReviewModel(String storyId) { }
	// RVA: 0x3484bd0 VA: 0x7595a9cbd0
	public Void RefreshAvailableViewModelList() { }
	// RVA: 0x3484e08 VA: 0x7595a9ce08
	private Boolean _CheckPrevDependenceUnlocked(String dependId) { }
	// RVA: 0x3484e30 VA: 0x7595a9ce30
	private Void _RefreshPlayerData(StoryReviewChapterViewModel chapter, PlayerStoryReviewUnlockInfo unlockInfo) { }
	// RVA: 0x3484ee4 VA: 0x7595a9cee4
	private Void _GenStoryReviewViewModel(ref StoryReviewViewModel viewModel, PlayerStoryReviewUnlockInfo unlockInfo) { }
	// RVA: 0x3484fe0 VA: 0x7595a9cfe0
	private Boolean _ChapterShow(Int64 startShow, Int64 endShow) { }
	// RVA: 0x34849f4 VA: 0x7595a9c9f4
	private Boolean _GenRewardsStatus(String chapterId, PlayerStoryReview review) { }
	// RVA: 0x348463c VA: 0x7595a9c63c
	private List`1 _GenViewModels(List`1 infoClientDatas, PlayerStoryReview review) { }
	// RVA: 0x34850fc VA: 0x7595a9d0fc
	private Boolean _GetStoryReviewUnlocked(String chapterId, String storyId, PlayerStoryReview review) { }
	// RVA: 0x3485230 VA: 0x7595a9d230
	private Boolean _GetStoryReviewRead(String chapterId, String storyId, PlayerStoryReview review) { }
	// RVA: 0x348458c VA: 0x7595a9c58c
	private Int32 _GetProgress(PlayerStoryReview review, String chapterId) { }
	// RVA: 0x3485390 VA: 0x7595a9d390
	public Void OnActivityReviewDetailDataRefresh() { }
	// RVA: 0x3485448 VA: 0x7595a9d448
	public Boolean CheckActivityOutOfTime() { }
	// RVA: 0x348563c VA: 0x7595a9d63c
	public Void .ctor() { }
}
```