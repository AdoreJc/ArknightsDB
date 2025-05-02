# RoguelikeChatSimpleComp

**Namespace:** `Torappu.UI.Roguelike.Chat`


## Fields

- `TextTypeTween _typeTween`

- `CanvasGroupFade _fadeIn`

- `ClickButton _button`

- `UIAnimationLocation _animShow`

- `UIAudioPlayer _audioSignal`

- `Text _text`

- `Image _image`

- `GameObject _activeObj`

- `Single _height`

- `Single _postDelay`

- `DisplayControl m_displayStatus`

- `String m_initTypeWirterText`

- `Action m_onClicked`


## Methods

- `Void _HideContent()`

- `Void _ShowContentImmediately()`

- `IEnumerator _ShowCoroutine()`

- `Void _SetDisplayStatus(DisplayControl)`

- `Void _ClearPlayingItems()`

- `Void EventOnViewClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Chat
public class RoguelikeChatSimpleComp : MonoBehaviour, IHotfixable
{
	private TextTypeTween _typeTween; // 0x18
	private CanvasGroupFade _fadeIn; // 0x28
	private ClickButton _button; // 0x38
	private UIAnimationLocation _animShow; // 0x48
	private UIAudioPlayer _audioSignal; // 0x58
	private Text _text; // 0x70
	private Image _image; // 0x78
	private GameObject _activeObj; // 0x80
	private Single _height; // 0x88
	private Single _postDelay; // 0x8c
	private List`1 m_playList; // 0x90
	private DisplayControl m_displayStatus; // 0x98
	private String m_initTypeWirterText; // 0xb8
	private Action m_onClicked; // 0xc0
	private static DelegateBridge __Hotfix0__HideContent; // 0x0
	private static DelegateBridge __Hotfix0__ShowContentImmediately; // 0x8
	private static DelegateBridge __Hotfix0__ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__SetDisplayStatus; // 0x18
	private static DelegateBridge __Hotfix0__ClearPlayingItems; // 0x20
	private static DelegateBridge __Hotfix0_EventOnViewClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2bb873c VA: 0x75951d073c
	private Void _HideContent() { }
	// RVA: 0x2bb8bd4 VA: 0x75951d0bd4
	private Void _ShowContentImmediately() { }
	// RVA: 0x2bb8d24 VA: 0x75951d0d24
	private IEnumerator _ShowCoroutine() { }
	// RVA: 0x2bb8df8 VA: 0x75951d0df8
	private Void _SetDisplayStatus(DisplayControl config) { }
	// RVA: 0x2bb88a4 VA: 0x75951d08a4
	private Void _ClearPlayingItems() { }
	// RVA: 0x2bb9038 VA: 0x75951d1038
	public Void EventOnViewClicked() { }
	// RVA: 0x2bb90bc VA: 0x75951d10bc
	public Void .ctor() { }
}
```