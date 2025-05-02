# InputField

**Namespace:** `UnityEngine.UI`


## Fields

- `TouchScreenKeyboard m_Keyboard`

- `Text m_TextComponent`

- `Graphic m_Placeholder`

- `ContentType m_ContentType`

- `InputType m_InputType`

- `Char m_AsteriskChar`

- `TouchScreenKeyboardType m_KeyboardType`

- `LineType m_LineType`

- `Boolean m_HideMobileInput`

- `CharacterValidation m_CharacterValidation`

- `Int32 m_CharacterLimit`

- `SubmitEvent m_OnSubmit`

- `EndEditEvent m_OnDidEndEdit`

- `OnChangeEvent m_OnValueChanged`

- `OnValidateInput m_OnValidateInput`

- `Color m_CaretColor`

- `Boolean m_CustomCaretColor`

- `Color m_SelectionColor`

- `String m_Text`

- `Single m_CaretBlinkRate`

- `Int32 m_CaretWidth`

- `Boolean m_ReadOnly`

- `Boolean m_ShouldActivateOnSelect`

- `Int32 m_CaretPosition`

- `Int32 m_CaretSelectPosition`

- `RectTransform caretRectTrans`

- `TextGenerator m_InputTextCache`

- `CanvasRenderer m_CachedInputRenderer`

- `Boolean m_PreventFontCallback`

- `Mesh m_Mesh`

- `Boolean m_AllowInput`

- `Boolean m_ShouldActivateNextUpdate`

- `Boolean m_UpdateDrag`

- `Boolean m_DragPositionOutOfBounds`

- `Boolean m_CaretVisible`

- `Coroutine m_BlinkCoroutine`

- `Single m_BlinkStartTime`

- `Int32 m_DrawStart`

- `Int32 m_DrawEnd`

- `Coroutine m_DragCoroutine`

- `String m_OriginalText`

- `Boolean m_WasCanceled`

- `Boolean m_HasDoneFocusTransition`

- `WaitForSecondsRealtime m_WaitForSecondsRealtime`

- `Boolean m_TouchKeyboardAllowsInPlaceEditing`

- `Boolean m_IsCompositionActive`

- `Event m_ProcessingEvent`


## Properties

- `BaseInput input`

- `String compositionString`

- `Mesh mesh`

- `TextGenerator cachedInputTextGenerator`

- `Boolean shouldHideMobileInput`

- `String text`

- `Boolean isFocused`

- `Single caretBlinkRate`

- `Int32 caretWidth`

- `Text textComponent`

- `Graphic placeholder`

- `Color caretColor`

- `Boolean customCaretColor`

- `Color selectionColor`

- `EndEditEvent onEndEdit`

- `SubmitEvent onSubmit`

- `OnChangeEvent onValueChange`

- `OnChangeEvent onValueChanged`

- `OnValidateInput onValidateInput`

- `Int32 characterLimit`

- `ContentType contentType`

- `LineType lineType`

- `InputType inputType`

- `TouchScreenKeyboard touchScreenKeyboard`

- `TouchScreenKeyboardType keyboardType`

- `CharacterValidation characterValidation`

- `Boolean readOnly`

- `Boolean multiLine`

- `Char asteriskChar`

- `Boolean wasCanceled`

- `Int32 caretPositionInternal`

- `Int32 caretSelectPositionInternal`

- `Boolean hasSelection`

- `Int32 caretPosition`

- `Int32 selectionAnchorPosition`

- `Int32 selectionFocusPosition`


## Methods

- `BaseInput get_input()`

- `String get_compositionString()`

- `Mesh get_mesh()`

- `TextGenerator get_cachedInputTextGenerator()`

- `Void set_shouldHideMobileInput(Boolean)`

- `Boolean get_shouldHideMobileInput()`

- `String get_text()`

- `Void set_text(String)`

- `Void SetTextWithoutNotify(String)`

- `Void SetText(String, Boolean)`

- `Boolean get_isFocused()`

- `Single get_caretBlinkRate()`

- `Void set_caretBlinkRate(Single)`

- `Int32 get_caretWidth()`

- `Void set_caretWidth(Int32)`

- `Text get_textComponent()`

- `Void set_textComponent(Text)`

- `Graphic get_placeholder()`

- `Void set_placeholder(Graphic)`

- `Color get_caretColor()`

- `Void set_caretColor(Color)`

- `Boolean get_customCaretColor()`

- `Void set_customCaretColor(Boolean)`

- `Color get_selectionColor()`

- `Void set_selectionColor(Color)`

- `EndEditEvent get_onEndEdit()`

- `Void set_onEndEdit(EndEditEvent)`

- `SubmitEvent get_onSubmit()`

- `Void set_onSubmit(SubmitEvent)`

- `OnChangeEvent get_onValueChange()`

- `Void set_onValueChange(OnChangeEvent)`

- `OnChangeEvent get_onValueChanged()`

- `Void set_onValueChanged(OnChangeEvent)`

- `OnValidateInput get_onValidateInput()`

- `Void set_onValidateInput(OnValidateInput)`

- `Int32 get_characterLimit()`

- `Void set_characterLimit(Int32)`

- `ContentType get_contentType()`

- `Void set_contentType(ContentType)`

- `LineType get_lineType()`

- `Void set_lineType(LineType)`

- `InputType get_inputType()`

- `Void set_inputType(InputType)`

- `TouchScreenKeyboard get_touchScreenKeyboard()`

- `TouchScreenKeyboardType get_keyboardType()`

- `Void set_keyboardType(TouchScreenKeyboardType)`

- `CharacterValidation get_characterValidation()`

- `Void set_characterValidation(CharacterValidation)`

- `Boolean get_readOnly()`

- `Void set_readOnly(Boolean)`

- `Boolean get_multiLine()`

- `Char get_asteriskChar()`

- `Void set_asteriskChar(Char)`

- `Boolean get_wasCanceled()`

- `Void ClampPos(ref)`

- `Int32 get_caretPositionInternal()`

- `Void set_caretPositionInternal(Int32)`

- `Int32 get_caretSelectPositionInternal()`

- `Void set_caretSelectPositionInternal(Int32)`

- `Boolean get_hasSelection()`

- `Int32 get_caretPosition()`

- `Void set_caretPosition(Int32)`

- `Int32 get_selectionAnchorPosition()`

- `Void set_selectionAnchorPosition(Int32)`

- `Int32 get_selectionFocusPosition()`

- `Void set_selectionFocusPosition(Int32)`

- `IEnumerator CaretBlink()`

- `Void SetCaretVisible()`

- `Void SetCaretActive()`

- `Void UpdateCaretMaterial()`

- `Void OnFocus()`

- `Void SelectAll()`

- `Void MoveTextEnd(Boolean)`

- `Void MoveTextStart(Boolean)`

- `Boolean TouchScreenKeyboardShouldBeUsed()`

- `Boolean InPlaceEditing()`

- `Boolean InPlaceEditingChanged()`

- `Void UpdateCaretFromKeyboard()`

- `Vector2 ScreenToLocal(Vector2)`

- `Int32 GetUnclampedCharacterLineFromPosition(Vector2, TextGenerator)`

- `Int32 GetCharacterIndexFromPosition(Vector2)`

- `Boolean MayDrag(PointerEventData)`

- `IEnumerator MouseDragOutsideRect(PointerEventData)`

- `EditState KeyPressed(Event)`

- `Boolean IsValidChar(Char)`

- `Void ProcessEvent(Event)`

- `String GetSelectedString()`

- `Int32 FindtNextWordBegin()`

- `Void MoveRight(Boolean, Boolean)`

- `Int32 FindtPrevWordBegin()`

- `Void MoveLeft(Boolean, Boolean)`

- `Int32 DetermineCharacterLine(Int32, TextGenerator)`

- `Int32 LineUpCharacterPosition(Int32, Boolean)`

- `Int32 LineDownCharacterPosition(Int32, Boolean)`

- `Void MoveDown(Boolean)`

- `Void MoveDown(Boolean, Boolean)`

- `Void MoveUp(Boolean)`

- `Void MoveUp(Boolean, Boolean)`

- `Void Delete()`

- `Void ForwardSpace()`

- `Void Backspace()`

- `Void Insert(Char)`

- `Void UpdateTouchKeyboardFromEditChanges()`

- `Void SendOnValueChangedAndUpdateLabel()`

- `Void SendOnValueChanged()`

- `Void SendOnEndEdit()`

- `Void SendOnSubmit()`

- `Void UpdateLabel()`

- `Boolean IsSelectionVisible()`

- `Void SetDrawRangeToContainCaretPosition(Int32)`

- `Void ForceLabelUpdate()`

- `Void MarkGeometryAsDirty()`

- `Void UpdateGeometry()`

- `Void AssignPositioningIfNeeded()`

- `Void OnFillVBO(Mesh)`

- `Void GenerateCaret(VertexHelper, Vector2)`

- `Void CreateCursorVerts()`

- `Void GenerateHighlight(VertexHelper, Vector2)`

- `Char Validate(String, Int32, Char)`

- `Void ActivateInputField()`

- `Void ActivateInputFieldInternal()`

- `Void DeactivateInputField()`

- `Void EnforceContentType()`

- `Void EnforceTextHOverflow()`

- `Void SetToCustomIfContentTypeIsNot(ContentType[])`

- `Void SetToCustom()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class InputField : Selectable, IUpdateSelectedHandler, IEventSystemHandler, IBeginDragHandler, IDragHandler, IEndDragHandler, IPointerClickHandler, ISubmitHandler, ICanvasElement, ILayoutElement
{
	protected TouchScreenKeyboard m_Keyboard; // 0xf8
	private static readonly Char[] kSeparators; // 0x0
	private static Boolean s_IsQuestDeviceEvaluated; // 0x8
	private static Boolean s_IsQuestDevice; // 0x9
	protected Text m_TextComponent; // 0x100
	protected Graphic m_Placeholder; // 0x108
	private ContentType m_ContentType; // 0x110
	private InputType m_InputType; // 0x114
	private Char m_AsteriskChar; // 0x118
	private TouchScreenKeyboardType m_KeyboardType; // 0x11c
	private LineType m_LineType; // 0x120
	private Boolean m_HideMobileInput; // 0x124
	private CharacterValidation m_CharacterValidation; // 0x128
	private Int32 m_CharacterLimit; // 0x12c
	private SubmitEvent m_OnSubmit; // 0x130
	private EndEditEvent m_OnDidEndEdit; // 0x138
	private OnChangeEvent m_OnValueChanged; // 0x140
	private OnValidateInput m_OnValidateInput; // 0x148
	private Color m_CaretColor; // 0x150
	private Boolean m_CustomCaretColor; // 0x160
	private Color m_SelectionColor; // 0x164
	protected String m_Text; // 0x178
	private Single m_CaretBlinkRate; // 0x180
	private Int32 m_CaretWidth; // 0x184
	private Boolean m_ReadOnly; // 0x188
	private Boolean m_ShouldActivateOnSelect; // 0x189
	protected Int32 m_CaretPosition; // 0x18c
	protected Int32 m_CaretSelectPosition; // 0x190
	private RectTransform caretRectTrans; // 0x198
	protected UIVertex[] m_CursorVerts; // 0x1a0
	private TextGenerator m_InputTextCache; // 0x1a8
	private CanvasRenderer m_CachedInputRenderer; // 0x1b0
	private Boolean m_PreventFontCallback; // 0x1b8
	protected Mesh m_Mesh; // 0x1c0
	private Boolean m_AllowInput; // 0x1c8
	private Boolean m_ShouldActivateNextUpdate; // 0x1c9
	private Boolean m_UpdateDrag; // 0x1ca
	private Boolean m_DragPositionOutOfBounds; // 0x1cb
	private const Single kHScrollSpeed; // 0x0
	private const Single kVScrollSpeed; // 0x0
	protected Boolean m_CaretVisible; // 0x1cc
	private Coroutine m_BlinkCoroutine; // 0x1d0
	private Single m_BlinkStartTime; // 0x1d8
	protected Int32 m_DrawStart; // 0x1dc
	protected Int32 m_DrawEnd; // 0x1e0
	private Coroutine m_DragCoroutine; // 0x1e8
	private String m_OriginalText; // 0x1f0
	private Boolean m_WasCanceled; // 0x1f8
	private Boolean m_HasDoneFocusTransition; // 0x1f9
	private WaitForSecondsRealtime m_WaitForSecondsRealtime; // 0x200
	private Boolean m_TouchKeyboardAllowsInPlaceEditing; // 0x208
	private Boolean m_IsCompositionActive; // 0x209
	private const String kEmailSpecialCharacters; // 0x0
	private const String kOculusQuestDeviceModel; // 0x0
	private Event m_ProcessingEvent; // 0x210
	private const Int32 k_MaxTextLength; // 0x0

	private BaseInput input { get; }
	private String compositionString { get; }
	protected Mesh mesh { get; }
	protected TextGenerator cachedInputTextGenerator { get; }
	public Boolean shouldHideMobileInput { get; set; }
	public virtual Boolean shouldActivateOnSelect { get; set; }
	public String text { get; set; }
	public Boolean isFocused { get; }
	public Single caretBlinkRate { get; set; }
	public Int32 caretWidth { get; set; }
	public Text textComponent { get; set; }
	public Graphic placeholder { get; set; }
	public Color caretColor { get; set; }
	public Boolean customCaretColor { get; set; }
	public Color selectionColor { get; set; }
	public EndEditEvent onEndEdit { get; set; }
	public SubmitEvent onSubmit { get; set; }
	public OnChangeEvent onValueChange { get; set; }
	public OnChangeEvent onValueChanged { get; set; }
	public OnValidateInput onValidateInput { get; set; }
	public Int32 characterLimit { get; set; }
	public ContentType contentType { get; set; }
	public LineType lineType { get; set; }
	public InputType inputType { get; set; }
	public TouchScreenKeyboard touchScreenKeyboard { get; }
	public TouchScreenKeyboardType keyboardType { get; set; }
	public CharacterValidation characterValidation { get; set; }
	public Boolean readOnly { get; set; }
	public Boolean multiLine { get; }
	public Char asteriskChar { get; set; }
	public Boolean wasCanceled { get; }
	protected Int32 caretPositionInternal { get; set; }
	protected Int32 caretSelectPositionInternal { get; set; }
	private Boolean hasSelection { get; }
	public Int32 caretPosition { get; set; }
	public Int32 selectionAnchorPosition { get; set; }
	public Int32 selectionFocusPosition { get; set; }
	private static String clipboard { get; set; }
	public virtual Single minWidth { get; }
	public virtual Single preferredWidth { get; }
	public virtual Single flexibleWidth { get; }
	public virtual Single minHeight { get; }
	public virtual Single preferredHeight { get; }
	public virtual Single flexibleHeight { get; }
	public virtual Int32 layoutPriority { get; }

	// RVA: 0x6a4747c VA: 0x759905f47c
	private BaseInput get_input() { }
	// RVA: 0x6a4758c VA: 0x759905f58c
	private String get_compositionString() { }
	// RVA: 0x6a47620 VA: 0x759905f620
	protected Void .ctor() { }
	// RVA: 0x6a47968 VA: 0x759905f968
	protected Mesh get_mesh() { }
	// RVA: 0x6a47a18 VA: 0x759905fa18
	protected TextGenerator get_cachedInputTextGenerator() { }
	// RVA: 0x6a47a94 VA: 0x759905fa94
	public Void set_shouldHideMobileInput(Boolean value) { }
	// RVA: 0x6a47aec VA: 0x759905faec
	public Boolean get_shouldHideMobileInput() { }
	// RVA: 0x6a47b34 VA: 0x759905fb34
	public virtual Void set_shouldActivateOnSelect(Boolean value) { }
	// RVA: 0x6a47b40 VA: 0x759905fb40
	public virtual Boolean get_shouldActivateOnSelect() { }
	// RVA: 0x6a47b6c VA: 0x759905fb6c
	public String get_text() { }
	// RVA: 0x6a47b74 VA: 0x759905fb74
	public Void set_text(String value) { }
	// RVA: 0x6a47ed0 VA: 0x759905fed0
	public Void SetTextWithoutNotify(String input) { }
	// RVA: 0x6a47b7c VA: 0x759905fb7c
	private Void SetText(String value, Boolean sendCallback) { }
	// RVA: 0x6a4845c VA: 0x759906045c
	public Boolean get_isFocused() { }
	// RVA: 0x6a48464 VA: 0x7599060464
	public Single get_caretBlinkRate() { }
	// RVA: 0x6a4846c VA: 0x759906046c
	public Void set_caretBlinkRate(Single value) { }
	// RVA: 0x6a48558 VA: 0x7599060558
	public Int32 get_caretWidth() { }
	// RVA: 0x6a48560 VA: 0x7599060560
	public Void set_caretWidth(Int32 value) { }
	// RVA: 0x6a4862c VA: 0x759906062c
	public Text get_textComponent() { }
	// RVA: 0x6a48634 VA: 0x7599060634
	public Void set_textComponent(Text value) { }
	// RVA: 0x6a488d8 VA: 0x75990608d8
	public Graphic get_placeholder() { }
	// RVA: 0x6a488e0 VA: 0x75990608e0
	public Void set_placeholder(Graphic value) { }
	// RVA: 0x6a48938 VA: 0x7599060938
	public Color get_caretColor() { }
	// RVA: 0x6a4897c VA: 0x759906097c
	public Void set_caretColor(Color value) { }
	// RVA: 0x6a489a8 VA: 0x75990609a8
	public Boolean get_customCaretColor() { }
	// RVA: 0x6a489b0 VA: 0x75990609b0
	public Void set_customCaretColor(Boolean value) { }
	// RVA: 0x6a489cc VA: 0x75990609cc
	public Color get_selectionColor() { }
	// RVA: 0x6a489e0 VA: 0x75990609e0
	public Void set_selectionColor(Color value) { }
	// RVA: 0x6a48a0c VA: 0x7599060a0c
	public EndEditEvent get_onEndEdit() { }
	// RVA: 0x6a48a14 VA: 0x7599060a14
	public Void set_onEndEdit(EndEditEvent value) { }
	// RVA: 0x6a48a6c VA: 0x7599060a6c
	public SubmitEvent get_onSubmit() { }
	// RVA: 0x6a48a74 VA: 0x7599060a74
	public Void set_onSubmit(SubmitEvent value) { }
	// RVA: 0x6a48acc VA: 0x7599060acc
	public OnChangeEvent get_onValueChange() { }
	// RVA: 0x6a48ad4 VA: 0x7599060ad4
	public Void set_onValueChange(OnChangeEvent value) { }
	// RVA: 0x6a48b30 VA: 0x7599060b30
	public OnChangeEvent get_onValueChanged() { }
	// RVA: 0x6a48ad8 VA: 0x7599060ad8
	public Void set_onValueChanged(OnChangeEvent value) { }
	// RVA: 0x6a48b38 VA: 0x7599060b38
	public OnValidateInput get_onValidateInput() { }
	// RVA: 0x6a48b40 VA: 0x7599060b40
	public Void set_onValidateInput(OnValidateInput value) { }
	// RVA: 0x6a48b98 VA: 0x7599060b98
	public Int32 get_characterLimit() { }
	// RVA: 0x6a48ba0 VA: 0x7599060ba0
	public Void set_characterLimit(Int32 value) { }
	// RVA: 0x6a48c60 VA: 0x7599060c60
	public ContentType get_contentType() { }
	// RVA: 0x6a48c68 VA: 0x7599060c68
	public Void set_contentType(ContentType value) { }
	// RVA: 0x6a48d98 VA: 0x7599060d98
	public LineType get_lineType() { }
	// RVA: 0x6a48da0 VA: 0x7599060da0
	public Void set_lineType(LineType value) { }
	// RVA: 0x6a48eb8 VA: 0x7599060eb8
	public InputType get_inputType() { }
	// RVA: 0x6a48ec0 VA: 0x7599060ec0
	public Void set_inputType(InputType value) { }
	// RVA: 0x6a48f5c VA: 0x7599060f5c
	public TouchScreenKeyboard get_touchScreenKeyboard() { }
	// RVA: 0x6a48f64 VA: 0x7599060f64
	public TouchScreenKeyboardType get_keyboardType() { }
	// RVA: 0x6a48f6c VA: 0x7599060f6c
	public Void set_keyboardType(TouchScreenKeyboardType value) { }
	// RVA: 0x6a48ff0 VA: 0x7599060ff0
	public CharacterValidation get_characterValidation() { }
	// RVA: 0x6a48ff8 VA: 0x7599060ff8
	public Void set_characterValidation(CharacterValidation value) { }
	// RVA: 0x6a4907c VA: 0x759906107c
	public Boolean get_readOnly() { }
	// RVA: 0x6a49084 VA: 0x7599061084
	public Void set_readOnly(Boolean value) { }
	// RVA: 0x6a49090 VA: 0x7599061090
	public Boolean get_multiLine() { }
	// RVA: 0x6a490a4 VA: 0x75990610a4
	public Char get_asteriskChar() { }
	// RVA: 0x6a490ac VA: 0x75990610ac
	public Void set_asteriskChar(Char value) { }
	// RVA: 0x6a49120 VA: 0x7599061120
	public Boolean get_wasCanceled() { }
	// RVA: 0x6a49128 VA: 0x7599061128
	protected Void ClampPos(ref Int32 pos) { }
	// RVA: 0x6a49160 VA: 0x7599061160
	protected Int32 get_caretPositionInternal() { }
	// RVA: 0x6a49184 VA: 0x7599061184
	protected Void set_caretPositionInternal(Int32 value) { }
	// RVA: 0x6a491bc VA: 0x75990611bc
	protected Int32 get_caretSelectPositionInternal() { }
	// RVA: 0x6a491e0 VA: 0x75990611e0
	protected Void set_caretSelectPositionInternal(Int32 value) { }
	// RVA: 0x6a49218 VA: 0x7599061218
	private Boolean get_hasSelection() { }
	// RVA: 0x6a49248 VA: 0x7599061248
	public Int32 get_caretPosition() { }
	// RVA: 0x6a4926c VA: 0x759906126c
	public Void set_caretPosition(Int32 value) { }
	// RVA: 0x6a4934c VA: 0x759906134c
	public Int32 get_selectionAnchorPosition() { }
	// RVA: 0x6a49294 VA: 0x7599061294
	public Void set_selectionAnchorPosition(Int32 value) { }
	// RVA: 0x6a49370 VA: 0x7599061370
	public Int32 get_selectionFocusPosition() { }
	// RVA: 0x6a492f0 VA: 0x75990612f0
	public Void set_selectionFocusPosition(Int32 value) { }
	// RVA: 0x6a49394 VA: 0x7599061394
	protected override Void Awake() { }
	// RVA: 0x6a49454 VA: 0x7599061454
	protected override Void OnEnable() { }
	// RVA: 0x6a496cc VA: 0x75990616cc
	protected override Void OnDisable() { }
	// RVA: 0x6a49aa8 VA: 0x7599061aa8
	protected override Void OnDestroy() { }
	// RVA: 0x6a49b0c VA: 0x7599061b0c
	private IEnumerator CaretBlink() { }
	// RVA: 0x6a49ba8 VA: 0x7599061ba8
	private Void SetCaretVisible() { }
	// RVA: 0x6a484e8 VA: 0x75990604e8
	private Void SetCaretActive() { }
	// RVA: 0x6a49be0 VA: 0x7599061be0
	private Void UpdateCaretMaterial() { }
	// RVA: 0x6a49cf0 VA: 0x7599061cf0
	protected Void OnFocus() { }
	// RVA: 0x6a49cf4 VA: 0x7599061cf4
	protected Void SelectAll() { }
	// RVA: 0x6a49d28 VA: 0x7599061d28
	public Void MoveTextEnd(Boolean shift) { }
	// RVA: 0x6a49d88 VA: 0x7599061d88
	public Void MoveTextStart(Boolean shift) { }
	// RVA: 0x6a49e04 VA: 0x7599061e04
	private static String get_clipboard() { }
	// RVA: 0x6a49e0c VA: 0x7599061e0c
	private static Void set_clipboard(String value) { }
	// RVA: 0x6a49e14 VA: 0x7599061e14
	private Boolean TouchScreenKeyboardShouldBeUsed() { }
	// RVA: 0x6a49e94 VA: 0x7599061e94
	private Boolean InPlaceEditing() { }
	// RVA: 0x6a49ec4 VA: 0x7599061ec4
	private Boolean InPlaceEditingChanged() { }
	// RVA: 0x6a49f48 VA: 0x7599061f48
	private Void UpdateCaretFromKeyboard() { }
	// RVA: 0x6a4a030 VA: 0x7599062030
	protected virtual Void LateUpdate() { }
	// RVA: 0x6a4b67c VA: 0x759906367c
	public Vector2 ScreenToLocal(Vector2 screen) { }
	// RVA: 0x6a4b8ec VA: 0x75990638ec
	private Int32 GetUnclampedCharacterLineFromPosition(Vector2 pos, TextGenerator generator) { }
	// RVA: 0x6a4bafc VA: 0x7599063afc
	protected Int32 GetCharacterIndexFromPosition(Vector2 pos) { }
	// RVA: 0x6a4bef4 VA: 0x7599063ef4
	private Boolean MayDrag(PointerEventData eventData) { }
	// RVA: 0x6a4bfcc VA: 0x7599063fcc
	public virtual Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x6a4bfec VA: 0x7599063fec
	public virtual Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x6a4c1e8 VA: 0x75990641e8
	private IEnumerator MouseDragOutsideRect(PointerEventData eventData) { }
	// RVA: 0x6a4c2a0 VA: 0x75990642a0
	public virtual Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x6a4c2bc VA: 0x75990642bc
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x6a4c4ac VA: 0x75990644ac
	protected EditState KeyPressed(Event evt) { }
	// RVA: 0x6a4cf80 VA: 0x7599064f80
	private Boolean IsValidChar(Char c) { }
	// RVA: 0x6a4cff0 VA: 0x7599064ff0
	public Void ProcessEvent(Event e) { }
	// RVA: 0x6a4cff4 VA: 0x7599064ff4
	public virtual Void OnUpdateSelected(BaseEventData eventData) { }
	// RVA: 0x6a4ca4c VA: 0x7599064a4c
	private String GetSelectedString() { }
	// RVA: 0x6a4d17c VA: 0x759906517c
	private Int32 FindtNextWordBegin() { }
	// RVA: 0x6a4ce3c VA: 0x7599064e3c
	private Void MoveRight(Boolean shift, Boolean ctrl) { }
	// RVA: 0x6a4d238 VA: 0x7599065238
	private Int32 FindtPrevWordBegin() { }
	// RVA: 0x6a4cd10 VA: 0x7599064d10
	private Void MoveLeft(Boolean shift, Boolean ctrl) { }
	// RVA: 0x6a4d2d8 VA: 0x75990652d8
	private Int32 DetermineCharacterLine(Int32 charPos, TextGenerator generator) { }
	// RVA: 0x6a4d3e8 VA: 0x75990653e8
	private Int32 LineUpCharacterPosition(Int32 originalPos, Boolean goToFirstChar) { }
	// RVA: 0x6a4d740 VA: 0x7599065740
	private Int32 LineDownCharacterPosition(Int32 originalPos, Boolean goToLastChar) { }
	// RVA: 0x6a4cf74 VA: 0x7599064f74
	private Void MoveDown(Boolean shift) { }
	// RVA: 0x6a4d9f4 VA: 0x75990659f4
	private Void MoveDown(Boolean shift, Boolean goToLastChar) { }
	// RVA: 0x6a4cf68 VA: 0x7599064f68
	private Void MoveUp(Boolean shift) { }
	// RVA: 0x6a4db28 VA: 0x7599065b28
	private Void MoveUp(Boolean shift, Boolean goToFirstChar) { }
	// RVA: 0x6a4caf4 VA: 0x7599064af4
	private Void Delete() { }
	// RVA: 0x6a4c998 VA: 0x7599064998
	private Void ForwardSpace() { }
	// RVA: 0x6a4c884 VA: 0x7599064884
	private Void Backspace() { }
	// RVA: 0x6a4dc68 VA: 0x7599065c68
	private Void Insert(Char c) { }
	// RVA: 0x6a4ccc8 VA: 0x7599064cc8
	private Void UpdateTouchKeyboardFromEditChanges() { }
	// RVA: 0x6a4b664 VA: 0x7599063664
	private Void SendOnValueChangedAndUpdateLabel() { }
	// RVA: 0x6a47fc0 VA: 0x759905ffc0
	private Void SendOnValueChanged() { }
	// RVA: 0x6a4dd98 VA: 0x7599065d98
	protected Void SendOnEndEdit() { }
	// RVA: 0x6a4af10 VA: 0x7599062f10
	protected Void SendOnSubmit() { }
	// RVA: 0x6a4de18 VA: 0x7599065e18
	protected virtual Void Append(String input) { }
	// RVA: 0x6a4ded4 VA: 0x7599065ed4
	protected virtual Void Append(Char input) { }
	// RVA: 0x6a48040 VA: 0x7599060040
	protected Void UpdateLabel() { }
	// RVA: 0x6a4ec60 VA: 0x7599066c60
	private Boolean IsSelectionVisible() { }
	// RVA: 0x6a4eccc VA: 0x7599066ccc
	private static Int32 GetLineStartPosition(TextGenerator gen, Int32 line) { }
	// RVA: 0x6a4bd90 VA: 0x7599063d90
	private static Int32 GetLineEndPosition(TextGenerator gen, Int32 line) { }
	// RVA: 0x6a4e144 VA: 0x7599066144
	private Void SetDrawRangeToContainCaretPosition(Int32 caretPos) { }
	// RVA: 0x6a4ee1c VA: 0x7599066e1c
	public Void ForceLabelUpdate() { }
	// RVA: 0x6a485d4 VA: 0x75990605d4
	private Void MarkGeometryAsDirty() { }
	// RVA: 0x6a4ee20 VA: 0x7599066e20
	public virtual Void Rebuild(CanvasUpdate update) { }
	// RVA: 0x6a4f2b4 VA: 0x75990672b4
	public virtual Void LayoutComplete() { }
	// RVA: 0x6a4f2b8 VA: 0x75990672b8
	public virtual Void GraphicUpdateComplete() { }
	// RVA: 0x6a4ee30 VA: 0x7599066e30
	private Void UpdateGeometry() { }
	// RVA: 0x6a4aa10 VA: 0x7599062a10
	private Void AssignPositioningIfNeeded() { }
	// RVA: 0x6a4f2bc VA: 0x75990672bc
	private Void OnFillVBO(Mesh vbo) { }
	// RVA: 0x6a4f534 VA: 0x7599067534
	private Void GenerateCaret(VertexHelper vbo, Vector2 roundingOffset) { }
	// RVA: 0x6a50964 VA: 0x7599068964
	private Void CreateCursorVerts() { }
	// RVA: 0x6a4ff08 VA: 0x7599067f08
	private Void GenerateHighlight(VertexHelper vbo, Vector2 roundingOffset) { }
	// RVA: 0x6a4af90 VA: 0x7599062f90
	protected Char Validate(String text, Int32 pos, Char ch) { }
	// RVA: 0x6a50ac4 VA: 0x7599068ac4
	public Void ActivateInputField() { }
	// RVA: 0x6a4a6a8 VA: 0x75990626a8
	private Void ActivateInputFieldInternal() { }
	// RVA: 0x6a50be4 VA: 0x7599068be4
	public override Void OnSelect(BaseEventData eventData) { }
	// RVA: 0x6a50c20 VA: 0x7599068c20
	public virtual Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x6a4991c VA: 0x759906191c
	public Void DeactivateInputField() { }
	// RVA: 0x6a50c44 VA: 0x7599068c44
	public override Void OnDeselect(BaseEventData eventData) { }
	// RVA: 0x6a50c70 VA: 0x7599068c70
	public virtual Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x6a48cdc VA: 0x7599060cdc
	private Void EnforceContentType() { }
	// RVA: 0x6a478d4 VA: 0x759905f8d4
	private Void EnforceTextHOverflow() { }
	// RVA: 0x6a48e60 VA: 0x7599060e60
	private Void SetToCustomIfContentTypeIsNot(ContentType[] allowedContentTypes) { }
	// RVA: 0x6a48f44 VA: 0x7599060f44
	private Void SetToCustom() { }
	// RVA: 0x6a50cb8 VA: 0x7599068cb8
	protected override Void DoStateTransition(SelectionState state, Boolean instant) { }
	// RVA: 0x6a50ce4 VA: 0x7599068ce4
	public virtual Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x6a50ce8 VA: 0x7599068ce8
	public virtual Void CalculateLayoutInputVertical() { }
	// RVA: 0x6a50cec VA: 0x7599068cec
	public virtual Single get_minWidth() { }
	// RVA: 0x6a50cf4 VA: 0x7599068cf4
	public virtual Single get_preferredWidth() { }
	// RVA: 0x6a50e50 VA: 0x7599068e50
	public virtual Single get_flexibleWidth() { }
	// RVA: 0x6a50e58 VA: 0x7599068e58
	public virtual Single get_minHeight() { }
	// RVA: 0x6a50e60 VA: 0x7599068e60
	public virtual Single get_preferredHeight() { }
	// RVA: 0x6a50fbc VA: 0x7599068fbc
	public virtual Single get_flexibleHeight() { }
	// RVA: 0x6a50fc4 VA: 0x7599068fc4
	public virtual Int32 get_layoutPriority() { }
	// RVA: 0x6a50fcc VA: 0x7599068fcc
	private static Void .cctor() { }
	// RVA: 0x6a5107c VA: 0x759906907c
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
}
```