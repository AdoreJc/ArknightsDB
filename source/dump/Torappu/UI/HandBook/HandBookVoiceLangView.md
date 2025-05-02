# HandBookVoiceLangView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `CanvasGroup _panelCanvasGroup`

- `SimpleLayoutContent _simpleLayout`

- `Boolean m_isInited`

- `VoiceLangAdapter m_voiceLangAdapter`

- `FadeSwitchTween m_tween`


## Methods

- `Void SetClickAction(Action`1)`

- `Void _InitIfNot()`

- `Void Show()`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookVoiceLangView : DataBinder`1
{
	private const Single FADE_DURATION; // 0x0
	private CanvasGroup _panelCanvasGroup; // 0x20
	private SimpleLayoutContent _simpleLayout; // 0x28
	private Boolean m_isInited; // 0x30
	private VoiceLangAdapter m_voiceLangAdapter; // 0x38
	private FadeSwitchTween m_tween; // 0x40
	private static DelegateBridge __Hotfix0_SetClickAction; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2eb75e4 VA: 0x75954cf5e4
	public Void SetClickAction(Action`1 onItemClick) { }
	// RVA: 0x2eb7818 VA: 0x75954cf818
	public override Void OnValueChanged(HandBookVoiceLangViewProperty property) { }
	// RVA: 0x2eb7678 VA: 0x75954cf678
	private Void _InitIfNot() { }
	// RVA: 0x2eb78e8 VA: 0x75954cf8e8
	public Void Show() { }
	// RVA: 0x2eb795c VA: 0x75954cf95c
	public Void Hide() { }
	// RVA: 0x2eb79d0 VA: 0x75954cf9d0
	public Void .ctor() { }
}
```