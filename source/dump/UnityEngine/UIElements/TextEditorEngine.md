# TextEditorEngine

**Namespace:** `UnityEngine.UIElements`


## Fields

- `OnDetectFocusChangeFunction m_DetectFocusChangeFunction`

- `OnIndexChangeFunction m_IndexChangeFunction`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TextEditorEngine : TextEditor
{
	private OnDetectFocusChangeFunction m_DetectFocusChangeFunction; // 0x90
	private OnIndexChangeFunction m_IndexChangeFunction; // 0x98

	internal override Rect localPosition { get; }

	// RVA: 0x69c5c40 VA: 0x7598fddc40
	public Void .ctor(OnDetectFocusChangeFunction detectFocusChange, OnIndexChangeFunction indexChangeFunction) { }
	// RVA: 0x69c5c84 VA: 0x7598fddc84
	internal override Rect get_localPosition() { }
	// RVA: 0x69c5d0c VA: 0x7598fddd0c
	internal override Void OnDetectFocusChange() { }
	// RVA: 0x69c5d30 VA: 0x7598fddd30
	internal override Void OnCursorIndexChange() { }
	// RVA: 0x69c5d54 VA: 0x7598fddd54
	internal override Void OnSelectIndexChange() { }
}
```