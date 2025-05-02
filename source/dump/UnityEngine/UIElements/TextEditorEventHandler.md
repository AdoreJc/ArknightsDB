# TextEditorEventHandler

**Namespace:** `UnityEngine.UIElements`


## Fields

- `TextEditorEngine <editorEngine>k__BackingField`

- `ITextInputField <textInputField>k__BackingField`


## Properties

- `TextEditorEngine editorEngine`

- `ITextInputField textInputField`


## Methods

- `TextEditorEngine get_editorEngine()`

- `Void set_editorEngine(TextEditorEngine)`

- `ITextInputField get_textInputField()`

- `Void set_textInputField(ITextInputField)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TextEditorEventHandler
{
	private TextEditorEngine <editorEngine>k__BackingField; // 0x10
	private ITextInputField <textInputField>k__BackingField; // 0x18

	protected TextEditorEngine editorEngine { get; set; }
	protected ITextInputField textInputField { get; set; }

	// RVA: 0x69c59e4 VA: 0x7598fdd9e4
	protected TextEditorEngine get_editorEngine() { }
	// RVA: 0x69c59ec VA: 0x7598fdd9ec
	private Void set_editorEngine(TextEditorEngine value) { }
	// RVA: 0x69c59f4 VA: 0x7598fdd9f4
	protected ITextInputField get_textInputField() { }
	// RVA: 0x69c59fc VA: 0x7598fdd9fc
	private Void set_textInputField(ITextInputField value) { }
	// RVA: 0x69c5a04 VA: 0x7598fdda04
	protected Void .ctor(TextEditorEngine editorEngine, ITextInputField textInputField) { }
	// RVA: 0x69c5ae4 VA: 0x7598fddae4
	public virtual Void ExecuteDefaultActionAtTarget(EventBase evt) { }
	// RVA: 0x69c5ae8 VA: 0x7598fddae8
	public virtual Void ExecuteDefaultAction(EventBase evt) { }
}
```