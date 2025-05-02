# KeyboardTextEditorEventHandler

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_Dragged`

- `Boolean m_DragToPosition`

- `Boolean m_SelectAllOnMouseUp`

- `String m_PreDrawCursorText`

- `Boolean m_IsClicking`

- `Vector2 m_ClickStartPosition`


## Properties

- `Boolean isClicking`


## Methods

- `Boolean get_isClicking()`

- `Void set_isClicking(Boolean)`

- `Void OnFocus(FocusEvent)`

- `Void OnBlur(BlurEvent)`

- `Void OnMouseDown(MouseDownEvent)`

- `Void OnMouseUp(MouseUpEvent)`

- `Void OnMouseMove(MouseMoveEvent)`

- `Void ProcessDragMove(MouseMoveEvent)`

- `Boolean MoveDistanceQualifiesForDrag(Vector2, Vector2)`

- `Void OnKeyDown(KeyDownEvent)`

- `Void OnValidateCommandEvent(ValidateCommandEvent)`

- `Void OnExecuteCommandEvent(ExecuteCommandEvent)`

- `Void PreDrawCursor(String)`

- `Void PostDrawCursor()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class KeyboardTextEditorEventHandler : TextEditorEventHandler
{
	internal Boolean m_Changed; // 0x20
	private Boolean m_Dragged; // 0x21
	private Boolean m_DragToPosition; // 0x22
	private Boolean m_SelectAllOnMouseUp; // 0x23
	private String m_PreDrawCursorText; // 0x28
	private Boolean m_IsClicking; // 0x30
	private Vector2 m_ClickStartPosition; // 0x34
	private readonly Event m_ImguiEvent; // 0x40

	private Boolean isClicking { get; set; }

	// RVA: 0x69b19ec VA: 0x7598fc99ec
	private Boolean get_isClicking() { }
	// RVA: 0x69b19f4 VA: 0x7598fc99f4
	private Void set_isClicking(Boolean value) { }
	// RVA: 0x69b1a28 VA: 0x7598fc9a28
	public Void .ctor(TextEditorEngine editorEngine, ITextInputField textInputField) { }
	// RVA: 0x69b1ab4 VA: 0x7598fc9ab4
	public override Void ExecuteDefaultActionAtTarget(EventBase evt) { }
	// RVA: 0x69b2070 VA: 0x7598fca070
	private Void OnFocus(FocusEvent _) { }
	// RVA: 0x69b2200 VA: 0x7598fca200
	private Void OnBlur(BlurEvent _) { }
	// RVA: 0x69b220c VA: 0x7598fca20c
	private Void OnMouseDown(MouseDownEvent evt) { }
	// RVA: 0x69b2600 VA: 0x7598fca600
	private Void OnMouseUp(MouseUpEvent evt) { }
	// RVA: 0x69b2768 VA: 0x7598fca768
	private Void OnMouseMove(MouseMoveEvent evt) { }
	// RVA: 0x69b3838 VA: 0x7598fcb838
	private Void ProcessDragMove(MouseMoveEvent evt) { }
	// RVA: 0x69b3814 VA: 0x7598fcb814
	private Boolean MoveDistanceQualifiesForDrag(Vector2 start, Vector2 current) { }
	// RVA: 0x69b28b0 VA: 0x7598fca8b0
	private Void OnKeyDown(KeyDownEvent evt) { }
	// RVA: 0x69b2eb8 VA: 0x7598fcaeb8
	private Void OnValidateCommandEvent(ValidateCommandEvent evt) { }
	// RVA: 0x69b321c VA: 0x7598fcb21c
	private Void OnExecuteCommandEvent(ExecuteCommandEvent evt) { }
	// RVA: 0x69b396c VA: 0x7598fcb96c
	public Void PreDrawCursor(String newText) { }
	// RVA: 0x69b3cb8 VA: 0x7598fcbcb8
	public Void PostDrawCursor() { }
}
```