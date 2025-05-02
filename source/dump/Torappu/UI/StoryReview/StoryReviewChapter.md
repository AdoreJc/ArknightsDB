# StoryReviewChapter

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `StoryReviewChapterViewModel chapterModel`


## Methods

- `StoryReviewViewModel GetStoryReviewModel(String)`

- `Void RefreshAvailableViewModelList()`

- `Boolean CheckActivityOutOfTime()`

- `Void OnActivityReviewDetailDataRefresh()`

- `Boolean _CheckPrevDependenceUnlocked(String)`

- `Void _RefreshPlayerData(StoryReviewChapterViewModel, PlayerStoryReviewUnlockInfo)`

- `Void _GenStoryReviewViewModel(ref, PlayerStoryReviewUnlockInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewChapter
{
	public StoryReviewChapterViewModel chapterModel; // 0x10
	public List`1 availableModelList; // 0x18


	// RVA: 0x275cd54 VA: 0x7594d74d54
	public StoryReviewViewModel GetStoryReviewModel(String storyId) { }
	// RVA: 0x275ce8c VA: 0x7594d74e8c
	public Void RefreshAvailableViewModelList() { }
	// RVA: 0x275c438 VA: 0x7594d74438
	public Boolean CheckActivityOutOfTime() { }
	// RVA: 0x275d0ec VA: 0x7594d750ec
	public Void OnActivityReviewDetailDataRefresh() { }
	// RVA: 0x275d0c4 VA: 0x7594d750c4
	private Boolean _CheckPrevDependenceUnlocked(String dependId) { }
	// RVA: 0x275d1a4 VA: 0x7594d751a4
	private Void _RefreshPlayerData(StoryReviewChapterViewModel chapter, PlayerStoryReviewUnlockInfo unlockInfo) { }
	// RVA: 0x275d258 VA: 0x7594d75258
	private Void _GenStoryReviewViewModel(ref StoryReviewViewModel viewModel, PlayerStoryReviewUnlockInfo unlockInfo) { }
	// RVA: 0x275d354 VA: 0x7594d75354
	public Void .ctor() { }
}
```