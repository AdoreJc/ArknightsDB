# StoryReviewGroupViewModel

**Namespace:** `Torappu.UI.StoryReview`


## Methods

- `StoryReviewChapterViewModel FindReviewChapter(String)`

- `Void LoadData(PlayerStoryReview)`

- `Boolean _ChapterShow(Int64, Int64)`

- `Boolean _GenRewardsStatus(String, PlayerStoryReview)`

- `Boolean _GetStoryReviewUnlocked(String, String, PlayerStoryReview)`

- `Boolean _GetStoryReviewRead(String, String, PlayerStoryReview)`

- `Int32 _GetProgress(PlayerStoryReview, String)`

- `Void OnStoryReviewPlayerStatusChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewGroupViewModel : IHotfixable
{
	public List`1 storyReviewChapterList; // 0x10
	private static DelegateBridge __Hotfix0_FindReviewChapter; // 0x0
	private static DelegateBridge __Hotfix0_LoadDataByEntry; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_GetActiveActIdList; // 0x18
	private static DelegateBridge __Hotfix0__ChapterShow; // 0x20
	private static DelegateBridge __Hotfix0__GenRewardsStatus; // 0x28
	private static DelegateBridge __Hotfix0__GenViewModels; // 0x30
	private static DelegateBridge __Hotfix0__GetStoryReviewUnlocked; // 0x38
	private static DelegateBridge __Hotfix0__GetStoryReviewRead; // 0x40
	private static DelegateBridge __Hotfix0__GetProgress; // 0x48
	private static DelegateBridge __Hotfix0_OnStoryReviewPlayerStatusChanged; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2759954 VA: 0x7594d71954
	public StoryReviewChapterViewModel FindReviewChapter(String chapterId) { }
	// RVA: 0x2759a70 VA: 0x7594d71a70
	public List`1 LoadDataByEntry(StoryReviewEntryType entry) { }
	// RVA: 0x2759cf0 VA: 0x7594d71cf0
	public Void LoadData(PlayerStoryReview playerReview) { }
	// RVA: 0x275a8d4 VA: 0x7594d728d4
	public List`1 GetActiveActIdList() { }
	// RVA: 0x275a10c VA: 0x7594d7210c
	private Boolean _ChapterShow(Int64 startShow, Int64 endShow) { }
	// RVA: 0x275a7e0 VA: 0x7594d727e0
	private Boolean _GenRewardsStatus(String chapterId, PlayerStoryReview review) { }
	// RVA: 0x275a3e0 VA: 0x7594d723e0
	private List`1 _GenViewModels(List`1 infoClientDatas, PlayerStoryReview review) { }
	// RVA: 0x275aae8 VA: 0x7594d72ae8
	private Boolean _GetStoryReviewUnlocked(String chapterId, String storyId, PlayerStoryReview review) { }
	// RVA: 0x275ac74 VA: 0x7594d72c74
	private Boolean _GetStoryReviewRead(String chapterId, String storyId, PlayerStoryReview review) { }
	// RVA: 0x275a2e0 VA: 0x7594d722e0
	private Int32 _GetProgress(PlayerStoryReview review, String chapterId) { }
	// RVA: 0x275ae24 VA: 0x7594d72e24
	public Void OnStoryReviewPlayerStatusChanged() { }
	// RVA: 0x275aec0 VA: 0x7594d72ec0
	public Void .ctor() { }
}
```