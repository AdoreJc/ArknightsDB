# AVGStickerTextView

**Namespace:** `Torappu.AVG`


## Fields

- `AVGTypeWriterText _typeWriter`

- `Single _hideDuration`

- `Single _autoWaitBaseTime`

- `Single _autoWaitTimePerText`

- `Ease _hideEase`

- `Text _message`

- `RectTransform _textTransform`

- `CanvasGroup _canvasGroup`

- `Boolean m_hidden`

- `FadeSwitchTween m_animSwitch`

- `Single m_duration`


## Properties

- `Boolean isTyping`

- `Boolean isHidden`


## Methods

- `Boolean get_isTyping()`

- `Boolean get_isHidden()`

- `Void TryFinishType()`

- `Void RenderSticker(StickerParam, Action`1)`

- `FadeSwitchTween _EnsureSwitch()`

- `Void _OnTypeWriterEnd()`

- `Void _ResetView()`

- `Void SetTypeWriterDelay(Object)`

- `Void HideSticker(Single)`

- `Void AppendText(String)`

- `Void _SetHiddenInternal(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGStickerTextView : MonoBehaviour, IHotfixable
{
	private const Single SCREEN_WIDTH; // 0x0
	private const Single SCREEN_HEIGHT; // 0x0
	private AVGTypeWriterText _typeWriter; // 0x18
	private Single _hideDuration; // 0x20
	private Single _autoWaitBaseTime; // 0x24
	private Single _autoWaitTimePerText; // 0x28
	private Ease _hideEase; // 0x2c
	private Text _message; // 0x30
	private RectTransform _textTransform; // 0x38
	private CanvasGroup _canvasGroup; // 0x40
	private const Single TWEEN_DURATION; // 0x0
	private Boolean m_hidden; // 0x48
	private Action`1 m_OnTypeEnd; // 0x50
	private FadeSwitchTween m_animSwitch; // 0x58
	private Single m_duration; // 0x60
	private static DelegateBridge __Hotfix0_get_isTyping; // 0x0
	private static DelegateBridge __Hotfix0_get_isHidden; // 0x8
	private static DelegateBridge __Hotfix0_TryFinishType; // 0x10
	private static DelegateBridge __Hotfix0_RenderSticker; // 0x18
	private static DelegateBridge __Hotfix0__EnsureSwitch; // 0x20
	private static DelegateBridge __Hotfix0__OnTypeWriterEnd; // 0x28
	private static DelegateBridge __Hotfix0__ResetView; // 0x30
	private static DelegateBridge __Hotfix0_SetTypeWriterDelay; // 0x38
	private static DelegateBridge __Hotfix0_HideSticker; // 0x40
	private static DelegateBridge __Hotfix0_AppendText; // 0x48
	private static DelegateBridge __Hotfix0__SetHiddenInternal; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isTyping { get; }
	public Boolean isHidden { get; }

	// RVA: 0x3eab0b8 VA: 0x75964c30b8
	public Boolean get_isTyping() { }
	// RVA: 0x3eab190 VA: 0x75964c3190
	public Boolean get_isHidden() { }
	// RVA: 0x3eab1f8 VA: 0x75964c31f8
	public Void TryFinishType() { }
	// RVA: 0x3eab300 VA: 0x75964c3300
	public Void RenderSticker(StickerParam param, Action`1 eventOnTypeEnd) { }
	// RVA: 0x3eab694 VA: 0x75964c3694
	private FadeSwitchTween _EnsureSwitch() { }
	// RVA: 0x3eabc3c VA: 0x75964c3c3c
	private Void _OnTypeWriterEnd() { }
	// RVA: 0x3eab5ec VA: 0x75964c35ec
	private Void _ResetView() { }
	// RVA: 0x3eabe9c VA: 0x75964c3e9c
	public Void SetTypeWriterDelay(Object arg) { }
	// RVA: 0x3eabf4c VA: 0x75964c3f4c
	public Void HideSticker(Single duration) { }
	// RVA: 0x3eac138 VA: 0x75964c4138
	public Void AppendText(String text) { }
	// RVA: 0x3eac01c VA: 0x75964c401c
	private Void _SetHiddenInternal(Boolean isHide) { }
	// RVA: 0x3eac210 VA: 0x75964c4210
	public Void .ctor() { }
}
```