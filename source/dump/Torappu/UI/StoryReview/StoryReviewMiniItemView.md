# StoryReviewMiniItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _infoPanel`

- `Image _charImage`

- `Text _titleName`

- `Image _newTag`

- `Image _newBg`

- `Image _decoText`

- `Text _newText`

- `StoryReviewUnlockItemView _unlockView`

- `Transform _customContainer`

- `GameObject _titlePanel`

- `StoryReviewViewModel m_cachedModel`

- `StoryReviewUnlockItemView m_unlockView`

- `StoryReviewCustomMiniItemInfoView m_itemInfoView`

- `Color m_lightTextColor`

- `Color m_darkTextColor`


## Methods

- `Void ApplyData(StoryReviewViewModel, Color, Boolean, GameObject, GameObject)`

- `Void _TryRenderCustomInfo(GameObject, Sprite, Boolean, Boolean)`

- `Void EventOnStoryClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewMiniItemView : MonoBehaviour, IHotfixable
{
	private GameObject _infoPanel; // 0x18
	private Image _charImage; // 0x20
	private Text _titleName; // 0x28
	private Image _newTag; // 0x30
	private Image _newBg; // 0x38
	private Image _decoText; // 0x40
	private Text _newText; // 0x48
	private StoryReviewUnlockItemView _unlockView; // 0x50
	private Transform _customContainer; // 0x58
	private GameObject _titlePanel; // 0x60
	public Action`1 onClicked; // 0x68
	public Action`1 onStoryRead; // 0x70
	public Action`1 onUnlockClicked; // 0x78
	private StoryReviewViewModel m_cachedModel; // 0x80
	private StoryReviewUnlockItemView m_unlockView; // 0x88
	private StoryReviewCustomMiniItemInfoView m_itemInfoView; // 0x90
	private const Single DECO_SPRITE_ALPHA; // 0x0
	private Color m_lightTextColor; // 0x98
	private Color m_darkTextColor; // 0xa8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__TryRenderCustomInfo; // 0x8
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x275d6d8 VA: 0x7594d756d8
	public Void ApplyData(StoryReviewViewModel storyModel, Color storyColor, Boolean outOfTime, GameObject customPrefab, GameObject customLockPrefab) { }
	// RVA: 0x275f688 VA: 0x7594d77688
	private Void _TryRenderCustomInfo(GameObject customPrefab, Sprite charSprite, Boolean locked, Boolean read) { }
	// RVA: 0x275f830 VA: 0x7594d77830
	public Void EventOnStoryClicked() { }
	// RVA: 0x275f8f0 VA: 0x7594d778f0
	public Void .ctor() { }
}
```