# ActCommonMiniStoryViewModel

**Namespace:** `Torappu.Activity`


## Fields

- `StoryReviewChapterViewModel chapterModel`

- `String activityId`


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
// Namespace : Torappu.Activity
public class ActCommonMiniStoryViewModel
{
	public StoryReviewChapterViewModel chapterModel; // 0x10
	public List`1 availableModelList; // 0x18
	public String activityId; // 0x20


	// RVA: 0x30ca46c VA: 0x75956e246c
	public Void LoadData(PlayerStoryReview playerData, String activityId) { }
	// RVA: 0x30caf34 VA: 0x75956e2f34
	public StoryReviewViewModel GetStoryReviewModel(String storyId) { }
	// RVA: 0x30ca5ec VA: 0x75956e25ec
	public Void RefreshAvailableViewModelList() { }
	// RVA: 0x30cbb28 VA: 0x75956e3b28
	private Boolean _CheckPrevDependenceUnlocked(String dependId) { }
	// RVA: 0x30cbb50 VA: 0x75956e3b50
	private Void _RefreshPlayerData(StoryReviewChapterViewModel chapter, PlayerStoryReviewUnlockInfo unlockInfo) { }
	// RVA: 0x30cbc04 VA: 0x75956e3c04
	private Void _GenStoryReviewViewModel(ref StoryReviewViewModel viewModel, PlayerStoryReviewUnlockInfo unlockInfo) { }
	// RVA: 0x30cbd00 VA: 0x75956e3d00
	private Boolean _ChapterShow(Int64 startShow, Int64 endShow) { }
	// RVA: 0x30cba84 VA: 0x75956e3a84
	private Boolean _GenRewardsStatus(String chapterId, PlayerStoryReview review) { }
	// RVA: 0x30cb6cc VA: 0x75956e36cc
	private List`1 _GenViewModels(List`1 infoClientDatas, PlayerStoryReview review) { }
	// RVA: 0x30cbe1c VA: 0x75956e3e1c
	private Boolean _GetStoryReviewUnlocked(String chapterId, String storyId, PlayerStoryReview review) { }
	// RVA: 0x30cbf50 VA: 0x75956e3f50
	private Boolean _GetStoryReviewRead(String chapterId, String storyId, PlayerStoryReview review) { }
	// RVA: 0x30cb61c VA: 0x75956e361c
	private Int32 _GetProgress(PlayerStoryReview review, String chapterId) { }
	// RVA: 0x30caad0 VA: 0x75956e2ad0
	public Void OnActivityReviewDetailDataRefresh() { }
	// RVA: 0x30cc0b0 VA: 0x75956e40b0
	public Boolean CheckActivityOutOfTime() { }
	// RVA: 0x30cc2a4 VA: 0x75956e42a4
	public Void .ctor() { }
}
```