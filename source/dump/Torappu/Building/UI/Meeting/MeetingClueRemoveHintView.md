# MeetingClueRemoveHintView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Image _background`

- `Text _amount`

- `CanvasGroup _canvasGroup`

- `Single _fadeDuration`

- `Action m_okCallback`

- `Boolean m_shown`


## Methods

- `Void Show(Int32, Action)`

- `Void _Hide()`

- `Void OkButtonPressed()`

- `Void CancelButtonPressed()`

- `Void OnDestroy()`

- `Void <Show>b__6_1(Single)`

- `Void <_Hide>b__7_1(Single)`

- `Void <_Hide>b__7_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueRemoveHintView : MonoBehaviour
{
	private Image _background; // 0x18
	private Text _amount; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private Single _fadeDuration; // 0x30
	private Action m_okCallback; // 0x38
	private Boolean m_shown; // 0x40


	// RVA: 0x3df9c0c VA: 0x7596411c0c
	public Void Show(Int32 amount, Action okCallback) { }
	// RVA: 0x3df9e4c VA: 0x7596411e4c
	private Void _Hide() { }
	// RVA: 0x3dfa068 VA: 0x7596412068
	public Void OkButtonPressed() { }
	// RVA: 0x3dfa094 VA: 0x7596412094
	public Void CancelButtonPressed() { }
	// RVA: 0x3dfa098 VA: 0x7596412098
	private Void OnDestroy() { }
	// RVA: 0x3dfa164 VA: 0x7596412164
	public Void .ctor() { }
	// RVA: 0x3dfa178 VA: 0x7596412178
	private Void <Show>b__6_1(Single val) { }
	// RVA: 0x3dfa194 VA: 0x7596412194
	private Void <_Hide>b__7_1(Single val) { }
	// RVA: 0x3dfa1b0 VA: 0x75964121b0
	private Void <_Hide>b__7_2() { }
}
```