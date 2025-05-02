# UIToast

**Namespace:** `Torappu.UI`


## Fields

- `Text _textContent`

- `UIAnimationLocation _animShow`

- `UIAnimationLocation _animHide`

- `Single _showDuration`

- `Tween m_showTween`

- `Tween m_hideTween`

- `Action m_toastFinishCallback`


## Properties

- `Boolean isShown`

- `String text`


## Methods

- `Boolean get_isShown()`

- `String get_text()`

- `Void set_text(String)`

- `Boolean Show(Action)`

- `Boolean Show()`

- `Void _Hide()`

- `Void <Show>b__12_0()`

- `Void <_Hide>b__15_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIToast : MonoBehaviour
{
	private Text _textContent; // 0x18
	private UIAnimationLocation _animShow; // 0x20
	private UIAnimationLocation _animHide; // 0x30
	private Single _showDuration; // 0x40
	private Tween m_showTween; // 0x48
	private Tween m_hideTween; // 0x50
	private Action m_toastFinishCallback; // 0x58

	public Boolean isShown { get; }
	public String text { get; set; }

	// RVA: 0x22581e4 VA: 0x75948701e4
	public Boolean get_isShown() { }
	// RVA: 0x2258204 VA: 0x7594870204
	public String get_text() { }
	// RVA: 0x224fd14 VA: 0x7594867d14
	public Void set_text(String value) { }
	// RVA: 0x224faa0 VA: 0x7594867aa0
	public Boolean Show(Action finishCallback) { }
	// RVA: 0x2258228 VA: 0x7594870228
	public Boolean Show() { }
	// RVA: 0x2258230 VA: 0x7594870230
	private static IEnumerator _LocalDurationCoroutine(Action callback, Single duration) { }
	// RVA: 0x22582dc VA: 0x75948702dc
	private Void _Hide() { }
	// RVA: 0x2258474 VA: 0x7594870474
	public Void .ctor() { }
	// RVA: 0x2258484 VA: 0x7594870484
	private Void <Show>b__12_0() { }
	// RVA: 0x2258490 VA: 0x7594870490
	private Void <_Hide>b__15_0() { }
}
```