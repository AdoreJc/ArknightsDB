# TouchScreenTextEditorEventHandler

**Namespace:** `UnityEngine.UIElements`


## Fields

- `IVisualElementScheduledItem m_TouchKeyboardPoller`

- `VisualElement m_LastPointerDownTarget`


## Methods

- `Void PollTouchScreenKeyboard()`

- `Void DoPollTouchScreenKeyboard()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TouchScreenTextEditorEventHandler : TextEditorEventHandler
{
	private IVisualElementScheduledItem m_TouchKeyboardPoller; // 0x20
	private VisualElement m_LastPointerDownTarget; // 0x28
	private static TouchScreenKeyboard s_KeyboardOnScreen; // 0x0


	// RVA: 0x69c78a4 VA: 0x7598fdf8a4
	public Void .ctor(TextEditorEngine editorEngine, ITextInputField textInputField) { }
	// RVA: 0x69c78dc VA: 0x7598fdf8dc
	private Void PollTouchScreenKeyboard() { }
	// RVA: 0x69c7b58 VA: 0x7598fdfb58
	private Void DoPollTouchScreenKeyboard() { }
	// RVA: 0x69c8298 VA: 0x7598fe0298
	public override Void ExecuteDefaultActionAtTarget(EventBase evt) { }
}
```