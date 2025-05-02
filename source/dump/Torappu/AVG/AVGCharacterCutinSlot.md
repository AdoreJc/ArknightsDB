# AVGCharacterCutinSlot

**Namespace:** `Torappu.AVG`


## Fields

- `CanvasGroup _canvasGroup`

- `RectTransform _offsetTransform`

- `RectTransform _maskRectTransform`

- `RectTransform _zoomAndPovRectTransform`

- `RectTransform _defualtBackground`

- `RectTransform _backgroundRectTransform`

- `Image _backgroundImage`

- `AVGCharacterSlot _characterSlot`

- `Single _defaultFadetime`

- `Int32 _defaultSlotWidth`

- `Align m_align`

- `FadeStyle m_showFadeStyle`


## Methods

- `Void Show(Command, Action)`

- `Void SlotUpdate(Command, Action)`

- `Void Hide(Command, Action)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCharacterCutinSlot : MonoBehaviour, IReusable, IFadeTimeRatio
{
	private CanvasGroup _canvasGroup; // 0x18
	private RectTransform _offsetTransform; // 0x20
	private RectTransform _maskRectTransform; // 0x28
	private RectTransform _zoomAndPovRectTransform; // 0x30
	private RectTransform _defualtBackground; // 0x38
	private RectTransform _backgroundRectTransform; // 0x40
	private Image _backgroundImage; // 0x48
	private AVGCharacterSlot _characterSlot; // 0x50
	private Single _defaultFadetime; // 0x58
	private Int32 _defaultSlotWidth; // 0x5c
	private Align m_align; // 0x60
	private FadeStyle m_showFadeStyle; // 0x64


	// RVA: 0x3e9f778 VA: 0x75964b7778
	public Void Show(Command command, Action onShowEnd) { }
	// RVA: 0x3ea048c VA: 0x75964b848c
	public Void SlotUpdate(Command command, Action onShowEnd) { }
	// RVA: 0x3ea08ac VA: 0x75964b88ac
	public Void Hide(Command command, Action onShowEnd) { }
	// RVA: 0x3ea0c74 VA: 0x75964b8c74
	public Void OnAllocate() { }
	// RVA: 0x3ea0c78 VA: 0x75964b8c78
	public Void OnRecycle() { }
	// RVA: 0x3ea0334 VA: 0x75964b8334
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3ea0d74 VA: 0x75964b8d74
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3ea0dd4 VA: 0x75964b8dd4
	public Void .ctor() { }
}
```