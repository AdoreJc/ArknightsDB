# Act10D5StoryItemView

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `GameObject _infoPanel`

- `Image _charImage`

- `Text _titleName`

- `Image _newTag`

- `Image _newBg`

- `Image _decoText`

- `Text _newText`

- `StoryReviewUnlockItemView _unlockView`

- `String m_cachedStoryTextId`

- `String m_cachedStoryId`

- `StoryReviewUnlockItemView m_unlockView`

- `Color m_lightTextColor`

- `Color m_darkTextColor`


## Methods

- `Void ApplyData(StoryReviewViewModel, Color)`

- `Sprite _LoadSprite(String)`

- `Void EventOnStoryClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StoryItemView : MonoBehaviour, IHotfixable
{
	private GameObject _infoPanel; // 0x18
	private Image _charImage; // 0x20
	private Text _titleName; // 0x28
	private Image _newTag; // 0x30
	private Image _newBg; // 0x38
	private Image _decoText; // 0x40
	private Text _newText; // 0x48
	private StoryReviewUnlockItemView _unlockView; // 0x50
	public Action`1 onClicked; // 0x58
	public Action`1 onStoryRead; // 0x60
	public Action`1 onUnlockClicked; // 0x68
	private String m_cachedStoryTextId; // 0x70
	private String m_cachedStoryId; // 0x78
	private StoryReviewUnlockItemView m_unlockView; // 0x80
	private const Single DECO_SPRITE_ALPHA; // 0x0
	private Color m_lightTextColor; // 0x88
	private Color m_darkTextColor; // 0x98
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x8
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3487988 VA: 0x7595a9f988
	public Void ApplyData(StoryReviewViewModel storyModel, Color storyColor) { }
	// RVA: 0x3487d8c VA: 0x7595a9fd8c
	private Sprite _LoadSprite(String picId) { }
	// RVA: 0x3487ec8 VA: 0x7595a9fec8
	public Void EventOnStoryClicked() { }
	// RVA: 0x3487f6c VA: 0x7595a9ff6c
	public Void .ctor() { }
}
```