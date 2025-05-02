# StoryReviewActivityItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Image _storyImage`

- `StoryReviewProgressItemView _progressItem`

- `GameObject _canGetRewards`

- `GameObject _completed`

- `GameObject _completedIcon`

- `GameObject _medalContainer`

- `Transform _replicateMarkContainer`

- `GameObject _replicateItemPrefab`

- `Image _medalIcon`

- `String m_cachedStoryReviewId`

- `GameObject m_replicateItem`


## Methods

- `Void ApplyData(StoryReviewChapterViewModel)`

- `Void EventOnChapterClicked()`

- `Void EventOnRewardsGainClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewActivityItemView : MonoBehaviour, IHotfixable
{
	private Image _storyImage; // 0x18
	private StoryReviewProgressItemView _progressItem; // 0x20
	private GameObject _canGetRewards; // 0x28
	private GameObject _completed; // 0x30
	private GameObject _completedIcon; // 0x38
	private GameObject _medalContainer; // 0x40
	private Transform _replicateMarkContainer; // 0x48
	private GameObject _replicateItemPrefab; // 0x50
	private Image _medalIcon; // 0x58
	public Action`1 onClicked; // 0x60
	public Action`1 onGainClicked; // 0x68
	private String m_cachedStoryReviewId; // 0x70
	private GameObject m_replicateItem; // 0x78
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_EventOnChapterClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnRewardsGainClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x275b3e0 VA: 0x7594d733e0
	public Void ApplyData(StoryReviewChapterViewModel chapterModel) { }
	// RVA: 0x275e988 VA: 0x7594d76988
	public Void EventOnChapterClicked() { }
	// RVA: 0x275ea10 VA: 0x7594d76a10
	public Void EventOnRewardsGainClicked() { }
	// RVA: 0x275ea98 VA: 0x7594d76a98
	public Void .ctor() { }
}
```