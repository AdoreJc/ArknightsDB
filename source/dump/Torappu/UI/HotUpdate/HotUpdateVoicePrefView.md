# HotUpdateVoicePrefView

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `SimpleLayoutContent _selectionLayout`

- `CanvasGroup _alphaHandler`

- `TwoStateToggle _btnToggle`

- `ViewModel m_viewModel`

- `Adapter m_adapter`

- `FadeSwitchTween m_displayTween`


## Methods

- `Void _InitIfNot()`

- `Void _Show()`

- `Void _Hide()`

- `Void _UpdateView()`

- `Void EventOnConfirmClicked()`

- `Void _OnVoiceItemClicked(HotUpdatePref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateVoicePrefView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _selectionLayout; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private TwoStateToggle _btnToggle; // 0x28
	private ViewModel m_viewModel; // 0x30
	private Adapter m_adapter; // 0x38
	private FadeSwitchTween m_displayTween; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__Show; // 0x8
	private static DelegateBridge __Hotfix0__Hide; // 0x10
	private static DelegateBridge __Hotfix0__UpdateView; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnVoiceItemClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x27d1510 VA: 0x7594de9510
	private Void _InitIfNot() { }
	// RVA: 0x27d1a34 VA: 0x7594de9a34
	private Void _Show() { }
	// RVA: 0x27d1b88 VA: 0x7594de9b88
	private Void _Hide() { }
	// RVA: 0x27d1ad8 VA: 0x7594de9ad8
	private Void _UpdateView() { }
	// RVA: 0x27d1c8c VA: 0x7594de9c8c
	public Void EventOnConfirmClicked() { }
	// RVA: 0x27d1d48 VA: 0x7594de9d48
	private Void _OnVoiceItemClicked(HotUpdatePref pref) { }
	// RVA: 0x27d1e00 VA: 0x7594de9e00
	public Void .ctor() { }
}
```