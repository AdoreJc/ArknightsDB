# StoryReviewActivityDetailItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Text _titleCode`

- `Text _titleName`

- `Text _storyTag`

- `Text _storyInfo`

- `StoryReviewUnlockItemView _unlockItem`

- `String m_cachedStoryReviewId`

- `String m_cachedStoryId`


## Methods

- `Void ApplyData(StoryReviewViewModel, Boolean)`

- `Void EventOnStoryClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewActivityDetailItemView : MonoBehaviour, IHotfixable
{
	private Text _titleCode; // 0x18
	private Text _titleName; // 0x20
	private Text _storyTag; // 0x28
	private Text _storyInfo; // 0x30
	private StoryReviewUnlockItemView _unlockItem; // 0x38
	public Action`1 onStoryPlayClicked; // 0x40
	public Action`1 onStoryRead; // 0x48
	public Action`1 onStoryUnlockClicked; // 0x50
	private String m_cachedStoryReviewId; // 0x58
	private String m_cachedStoryId; // 0x60
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x275bfa0 VA: 0x7594d73fa0
	public Void ApplyData(StoryReviewViewModel storyModel, Boolean outOfTime) { }
	// RVA: 0x275e5c8 VA: 0x7594d765c8
	public Void EventOnStoryClicked() { }
	// RVA: 0x275e66c VA: 0x7594d7666c
	public Void .ctor() { }
}
```