# HandBookInfoCharWordTextView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `CanvasGroup _canvasGroup`

- `RectTransform _scrollRect`

- `RectTransform _textRect`

- `Text _voiceText`

- `Image _triangle`


## Methods

- `Void OnEnable()`

- `Void _CloseText()`

- `Void _InitText(String)`

- `IEnumerator _Refresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoCharWordTextView : PageSingleComponent
{
	private CanvasGroup _canvasGroup; // 0x20
	private RectTransform _scrollRect; // 0x28
	private RectTransform _textRect; // 0x30
	private Text _voiceText; // 0x38
	private Image _triangle; // 0x40
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_InitText; // 0x8
	private static DelegateBridge __Hotfix0_CloseText; // 0x10
	private static DelegateBridge __Hotfix0__CloseText; // 0x18
	private static DelegateBridge __Hotfix0__InitText; // 0x20
	private static DelegateBridge __Hotfix0__Refresh; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2eace58 VA: 0x75954c4e58
	private Void OnEnable() { }
	// RVA: 0x2eac5c8 VA: 0x75954c45c8
	public static Void InitText(String voiceText, Interface pageInterface) { }
	// RVA: 0x2ea680c VA: 0x75954be80c
	public static Void CloseText(Interface pageInterface) { }
	// RVA: 0x2eacec0 VA: 0x75954c4ec0
	private Void _CloseText() { }
	// RVA: 0x2eacf70 VA: 0x75954c4f70
	private Void _InitText(String voiceText) { }
	// RVA: 0x2ead030 VA: 0x75954c5030
	private IEnumerator _Refresh() { }
	// RVA: 0x2ead104 VA: 0x75954c5104
	public Void .ctor() { }
}
```