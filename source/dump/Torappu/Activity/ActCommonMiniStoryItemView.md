# ActCommonMiniStoryItemView

**Namespace:** `Torappu.Activity`


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

- `String m_cachedStoryTextId`

- `String m_cachedStoryId`

- `StoryReviewUnlockItemView m_unlockView`

- `StoryReviewCustomMiniItemInfoView m_itemInfoView`

- `Color m_lightTextColor`

- `Color m_darkTextColor`


## Methods

- `Void ApplyData(StoryReviewViewModel, Color, GameObject, GameObject)`

- `Void _TryRenderCustomInfo(GameObject, Sprite, Boolean, Boolean)`

- `Sprite _LoadSprite(String)`

- `Void EventOnStoryClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonMiniStoryItemView : MonoBehaviour, IHotfixable
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
	private String m_cachedStoryTextId; // 0x80
	private String m_cachedStoryId; // 0x88
	private StoryReviewUnlockItemView m_unlockView; // 0x90
	private StoryReviewCustomMiniItemInfoView m_itemInfoView; // 0x98
	private const Single DECO_SPRITE_ALPHA; // 0x0
	private Color m_lightTextColor; // 0xa0
	private Color m_darkTextColor; // 0xb0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__TryRenderCustomInfo; // 0x8
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x10
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30c8ecc VA: 0x75956e0ecc
	public Void ApplyData(StoryReviewViewModel storyModel, Color storyColor, GameObject customPrefab, GameObject customLockPrefab) { }
	// RVA: 0x30c9a50 VA: 0x75956e1a50
	private Void _TryRenderCustomInfo(GameObject customPrefab, Sprite charSprite, Boolean locked, Boolean read) { }
	// RVA: 0x30c99cc VA: 0x75956e19cc
	private Sprite _LoadSprite(String picId) { }
	// RVA: 0x30c9c1c VA: 0x75956e1c1c
	public Void EventOnStoryClicked() { }
	// RVA: 0x30c9cc0 VA: 0x75956e1cc0
	public Void .ctor() { }
}
```