# RoguelikeTopicChallengeCard

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RectTransform _transform`

- `UIColorGraphic _colorChanger`

- `Color _darkColor`

- `Image _cover`

- `CanvasGroup _detailNode`

- `Single _hideFade`

- `Text _name`

- `UIAtlasImage _completeTag`

- `Text _initHp`

- `Text _initPopulation`

- `Text _initGold`

- `Text _initCapacity`

- `CanvasGroup _descNode`

- `Text _descLabel`

- `Single _descTweenDur`

- `RoguelikeTopicChallengeCardPlugin _plugin`

- `Single m_fade`

- `Tween m_hideTween`

- `Tween m_showTween`


## Properties

- `Single fade`

- `RectTransform rectTransform`


## Methods

- `Single get_fade()`

- `Void set_fade(Single)`

- `RectTransform get_rectTransform()`

- `Void Render(String, RoguelikeTopicChallengeModel, RoguelikeTopicChallengeModelStyle)`

- `Void EventOnShowDesc()`

- `Void EventOnCloseDesc()`

- `Void _TweenToShowDetail(Boolean)`

- `Void _CleanTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeCard : MonoBehaviour, IPageView, IHotfixable
{
	private RectTransform _transform; // 0x18
	private UIColorGraphic _colorChanger; // 0x20
	private Color _darkColor; // 0x28
	private Image _cover; // 0x38
	private CanvasGroup _detailNode; // 0x40
	private Single _hideFade; // 0x48
	private Text _name; // 0x50
	private UIAtlasImage _completeTag; // 0x58
	private Text _initHp; // 0x60
	private Text _initPopulation; // 0x68
	private Text _initGold; // 0x70
	private Text _initCapacity; // 0x78
	private CanvasGroup _descNode; // 0x80
	private Text _descLabel; // 0x88
	private Single _descTweenDur; // 0x90
	private RoguelikeTopicChallengeCardPlugin _plugin; // 0x98
	private Single m_fade; // 0xa0
	private Tween m_hideTween; // 0xa8
	private Tween m_showTween; // 0xb0
	private static DelegateBridge __Hotfix0_get_fade; // 0x0
	private static DelegateBridge __Hotfix0_set_fade; // 0x8
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnShowDesc; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCloseDesc; // 0x28
	private static DelegateBridge __Hotfix0__TweenToShowDetail; // 0x30
	private static DelegateBridge __Hotfix0__CleanTween; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40
	private static DelegateBridge __Hotfix0_Torappu.UI.LoopPagePicker.IPageView.get_gameObject; // 0x48

	public Single fade { get; set; }
	public RectTransform rectTransform { get; }

	// RVA: 0x2643c70 VA: 0x7594c5bc70
	public Single get_fade() { }
	// RVA: 0x2643cd8 VA: 0x7594c5bcd8
	public Void set_fade(Single value) { }
	// RVA: 0x2643e48 VA: 0x7594c5be48
	public RectTransform get_rectTransform() { }
	// RVA: 0x2643eb0 VA: 0x7594c5beb0
	public Void Render(String topicId, RoguelikeTopicChallengeModel model, RoguelikeTopicChallengeModelStyle style) { }
	// RVA: 0x2644168 VA: 0x7594c5c168
	public Void EventOnShowDesc() { }
	// RVA: 0x2644410 VA: 0x7594c5c410
	public Void EventOnCloseDesc() { }
	// RVA: 0x26441d4 VA: 0x7594c5c1d4
	private Void _TweenToShowDetail(Boolean showDetail) { }
	// RVA: 0x2644484 VA: 0x7594c5c484
	private Void _CleanTween() { }
	// RVA: 0x2644538 VA: 0x7594c5c538
	public Void .ctor() { }
	// RVA: 0x26445c0 VA: 0x7594c5c5c0
	private GameObject Torappu.UI.LoopPagePicker.IPageView.get_gameObject() { }
}
```