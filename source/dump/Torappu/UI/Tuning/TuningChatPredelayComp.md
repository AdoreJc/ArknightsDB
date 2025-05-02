# TuningChatPredelayComp

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Single _preferedHeight`

- `CanvasGroup _canvasGroup`

- `Single _fadeDuration`

- `FadeSwitchTween m_switchTween`


## Methods

- `Void _SetDisplay(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatPredelayComp : MonoBehaviour, IHotfixable
{
	private Single _preferedHeight; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Single _fadeDuration; // 0x28
	private FadeSwitchTween m_switchTween; // 0x30
	private static DelegateBridge __Hotfix0__SetDisplay; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2313474 VA: 0x759492b474
	private Void _SetDisplay(Boolean isShow, Boolean useFastMode) { }
	// RVA: 0x2313590 VA: 0x759492b590
	public Void .ctor() { }
}
```