# TextEditor

**Namespace:** `UnityEngine`


## Fields

- `TouchScreenKeyboard keyboardOnScreen`

- `Int32 controlID`

- `GUIStyle style`

- `Boolean multiline`

- `Boolean hasHorizontalCursorPos`

- `Boolean isPasswordField`

- `Vector2 scrollOffset`

- `GUIContent m_Content`

- `Rect m_Position`

- `Int32 m_CursorIndex`

- `Int32 m_SelectIndex`

- `Boolean m_RevealCursor`

- `Vector2 graphicalCursorPos`

- `Vector2 graphicalSelectCursorPos`

- `Boolean m_MouseDragSelectsWholeWords`

- `Int32 m_DblClickInitPos`

- `DblClickSnapping m_DblClickSnap`

- `Boolean m_bJustSelected`

- `Int32 m_iAltCursorPos`

- `String oldText`

- `Int32 oldPos`

- `Int32 oldSelectPos`


## Properties

- `String text`

- `Rect position`

- `Int32 cursorIndex`

- `Int32 selectIndex`

- `Int32 altCursorPosition`

- `Boolean hasSelection`

- `String SelectedText`


## Methods

- `String get_text()`

- `Void set_text(String)`

- `Rect get_position()`

- `Void set_position(Rect)`

- `Int32 get_cursorIndex()`

- `Void set_cursorIndex(Int32)`

- `Int32 get_selectIndex()`

- `Void set_selectIndex(Int32)`

- `Void ClearCursorPos()`

- `Int32 get_altCursorPosition()`

- `Void OnFocus()`

- `Void OnLostFocus()`

- `Void GrabGraphicalCursorPos()`

- `Boolean HandleKeyEvent(Event)`

- `Boolean DeleteLineBack()`

- `Boolean DeleteWordBack()`

- `Boolean DeleteWordForward()`

- `Boolean Delete()`

- `Boolean CanPaste()`

- `Boolean Backspace()`

- `Void SelectAll()`

- `Void SelectNone()`

- `Boolean get_hasSelection()`

- `String get_SelectedText()`

- `Boolean DeleteSelection()`

- `Void ReplaceSelection(String)`

- `Void Insert(Char)`

- `Void MoveSelectionToAltCursor()`

- `Void MoveRight()`

- `Void MoveLeft()`

- `Void MoveUp()`

- `Void MoveDown()`

- `Void MoveLineStart()`

- `Void MoveLineEnd()`

- `Void MoveGraphicalLineStart()`

- `Void MoveGraphicalLineEnd()`

- `Void MoveTextStart()`

- `Void MoveTextEnd()`

- `Int32 IndexOfEndOfLine(Int32)`

- `Void MoveParagraphForward()`

- `Void MoveParagraphBackward()`

- `Void MoveCursorToPosition(Vector2)`

- `Void MoveAltCursorToPosition(Vector2)`

- `Void SelectToPosition(Vector2)`

- `Void SelectLeft()`

- `Void SelectRight()`

- `Void SelectUp()`

- `Void SelectDown()`

- `Void SelectTextEnd()`

- `Void SelectTextStart()`

- `Void MouseDragSelectsWholeWords(Boolean)`

- `Void DblClickSnap(DblClickSnapping)`

- `Int32 GetGraphicalLineStart(Int32)`

- `Int32 GetGraphicalLineEnd(Int32)`

- `Int32 FindNextSeperator(Int32)`

- `Int32 FindPrevSeperator(Int32)`

- `Void MoveWordRight()`

- `Void MoveToStartOfNextWord()`

- `Void MoveToEndOfPreviousWord()`

- `Void SelectToStartOfNextWord()`

- `Void SelectToEndOfPreviousWord()`

- `CharacterType ClassifyChar(Int32)`

- `Int32 FindStartOfNextWord(Int32)`

- `Int32 FindEndOfPreviousWord(Int32)`

- `Void MoveWordLeft()`

- `Void SelectWordRight()`

- `Void SelectWordLeft()`

- `Void ExpandSelectGraphicalLineStart()`

- `Void ExpandSelectGraphicalLineEnd()`

- `Void SelectGraphicalLineStart()`

- `Void SelectGraphicalLineEnd()`

- `Void SelectParagraphForward()`

- `Void SelectParagraphBackward()`

- `Void SelectCurrentWord()`

- `Int32 FindEndOfClassification(Int32, Direction)`

- `Void SelectCurrentParagraph()`

- `Void UpdateScrollOffsetIfNeeded(Event)`

- `Void DrawCursor(String)`

- `Boolean PerformOperation(TextEditOp, Boolean)`

- `Void SaveBackup()`

- `Boolean Cut()`

- `Void Copy()`

- `Boolean Paste()`

- `Void InitKeyActions()`

- `Void DetectFocusChange()`

- `Void ClampTextIndex(ref)`

- `Void EnsureValidCodePointIndex(ref)`

- `Boolean IsValidCodePointIndex(Int32)`

- `Int32 PreviousCodePointIndex(Int32)`

- `Int32 NextCodePointIndex(Int32)`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
public class TextEditor
{
	public TouchScreenKeyboard keyboardOnScreen; // 0x10
	public Int32 controlID; // 0x18
	public GUIStyle style; // 0x20
	public Boolean multiline; // 0x28
	public Boolean hasHorizontalCursorPos; // 0x29
	public Boolean isPasswordField; // 0x2a
	internal Boolean m_HasFocus; // 0x2b
	public Vector2 scrollOffset; // 0x2c
	private GUIContent m_Content; // 0x38
	private Rect m_Position; // 0x40
	private Int32 m_CursorIndex; // 0x50
	private Int32 m_SelectIndex; // 0x54
	private Boolean m_RevealCursor; // 0x58
	public Vector2 graphicalCursorPos; // 0x5c
	public Vector2 graphicalSelectCursorPos; // 0x64
	private Boolean m_MouseDragSelectsWholeWords; // 0x6c
	private Int32 m_DblClickInitPos; // 0x70
	private DblClickSnapping m_DblClickSnap; // 0x74
	private Boolean m_bJustSelected; // 0x75
	private Int32 m_iAltCursorPos; // 0x78
	private String oldText; // 0x80
	private Int32 oldPos; // 0x88
	private Int32 oldSelectPos; // 0x8c
	private static Dictionary`2 s_Keyactions; // 0x0

	public String text { get; set; }
	public Rect position { get; set; }
	internal virtual Rect localPosition { get; }
	public Int32 cursorIndex { get; set; }
	public Int32 selectIndex { get; set; }
	public Int32 altCursorPosition { get; }
	public Boolean hasSelection { get; }
	public String SelectedText { get; }

	// RVA: 0x68ca0e4 VA: 0x7598ee20e4
	public String get_text() { }
	// RVA: 0x68ca100 VA: 0x7598ee2100
	public Void set_text(String value) { }
	// RVA: 0x68ca1c0 VA: 0x7598ee21c0
	public Rect get_position() { }
	// RVA: 0x68ca1cc VA: 0x7598ee21cc
	public Void set_position(Rect value) { }
	// RVA: 0x68ca628 VA: 0x7598ee2628
	internal virtual Rect get_localPosition() { }
	// RVA: 0x68ca634 VA: 0x7598ee2634
	public Int32 get_cursorIndex() { }
	// RVA: 0x68ca63c VA: 0x7598ee263c
	public Void set_cursorIndex(Int32 value) { }
	// RVA: 0x68ca694 VA: 0x7598ee2694
	public Int32 get_selectIndex() { }
	// RVA: 0x68ca69c VA: 0x7598ee269c
	public Void set_selectIndex(Int32 value) { }
	// RVA: 0x68ca6ec VA: 0x7598ee26ec
	private Void ClearCursorPos() { }
	// RVA: 0x68ca6fc VA: 0x7598ee26fc
	public Int32 get_altCursorPosition() { }
	// RVA: 0x68ca704 VA: 0x7598ee2704
	public Void .ctor() { }
	// RVA: 0x68ca82c VA: 0x7598ee282c
	public Void OnFocus() { }
	// RVA: 0x68ca8b8 VA: 0x7598ee28b8
	public Void OnLostFocus() { }
	// RVA: 0x68ca90c VA: 0x7598ee290c
	private Void GrabGraphicalCursorPos() { }
	// RVA: 0x68ca990 VA: 0x7598ee2990
	public Boolean HandleKeyEvent(Event e) { }
	// RVA: 0x68ca998 VA: 0x7598ee2998
	internal Boolean HandleKeyEvent(Event e, Boolean textIsReadOnly) { }
	// RVA: 0x68cb8f8 VA: 0x7598ee38f8
	public Boolean DeleteLineBack() { }
	// RVA: 0x68cbb78 VA: 0x7598ee3b78
	public Boolean DeleteWordBack() { }
	// RVA: 0x68cbcf0 VA: 0x7598ee3cf0
	public Boolean DeleteWordForward() { }
	// RVA: 0x68cbf68 VA: 0x7598ee3f68
	public Boolean Delete() { }
	// RVA: 0x68cc110 VA: 0x7598ee4110
	public Boolean CanPaste() { }
	// RVA: 0x68cc154 VA: 0x7598ee4154
	public Boolean Backspace() { }
	// RVA: 0x68ca870 VA: 0x7598ee2870
	public Void SelectAll() { }
	// RVA: 0x68cc2cc VA: 0x7598ee42cc
	public Void SelectNone() { }
	// RVA: 0x68cb9d0 VA: 0x7598ee39d0
	public Boolean get_hasSelection() { }
	// RVA: 0x68cc2f0 VA: 0x7598ee42f0
	public String get_SelectedText() { }
	// RVA: 0x68cb9e0 VA: 0x7598ee39e0
	public Boolean DeleteSelection() { }
	// RVA: 0x68cc384 VA: 0x7598ee4384
	public Void ReplaceSelection(String replace) { }
	// RVA: 0x68cc414 VA: 0x7598ee4414
	public Void Insert(Char c) { }
	// RVA: 0x68cc488 VA: 0x7598ee4488
	public Void MoveSelectionToAltCursor() { }
	// RVA: 0x68cc558 VA: 0x7598ee4558
	public Void MoveRight() { }
	// RVA: 0x68cc5d0 VA: 0x7598ee45d0
	public Void MoveLeft() { }
	// RVA: 0x68cc628 VA: 0x7598ee4628
	public Void MoveUp() { }
	// RVA: 0x68cc6d8 VA: 0x7598ee46d8
	public Void MoveDown() { }
	// RVA: 0x68cc7bc VA: 0x7598ee47bc
	public Void MoveLineStart() { }
	// RVA: 0x68cc834 VA: 0x7598ee4834
	public Void MoveLineEnd() { }
	// RVA: 0x68cc8c8 VA: 0x7598ee48c8
	public Void MoveGraphicalLineStart() { }
	// RVA: 0x68cc9c0 VA: 0x7598ee49c0
	public Void MoveGraphicalLineEnd() { }
	// RVA: 0x68ccacc VA: 0x7598ee4acc
	public Void MoveTextStart() { }
	// RVA: 0x68ccaec VA: 0x7598ee4aec
	public Void MoveTextEnd() { }
	// RVA: 0x68ccb34 VA: 0x7598ee4b34
	private Int32 IndexOfEndOfLine(Int32 startIndex) { }
	// RVA: 0x68ccb98 VA: 0x7598ee4b98
	public Void MoveParagraphForward() { }
	// RVA: 0x68ccc20 VA: 0x7598ee4c20
	public Void MoveParagraphBackward() { }
	// RVA: 0x68ccca4 VA: 0x7598ee4ca4
	public Void MoveCursorToPosition(Vector2 cursorPosition) { }
	// RVA: 0x68cccec VA: 0x7598ee4cec
	protected internal Void MoveCursorToPosition_Internal(Vector2 cursorPosition, Boolean shift) { }
	// RVA: 0x68ccd74 VA: 0x7598ee4d74
	public Void MoveAltCursorToPosition(Vector2 cursorPosition) { }
	// RVA: 0x68cce08 VA: 0x7598ee4e08
	public Void SelectToPosition(Vector2 cursorPosition) { }
	// RVA: 0x68cd1a8 VA: 0x7598ee51a8
	public Void SelectLeft() { }
	// RVA: 0x68cd200 VA: 0x7598ee5200
	public Void SelectRight() { }
	// RVA: 0x68cd258 VA: 0x7598ee5258
	public Void SelectUp() { }
	// RVA: 0x68cd2bc VA: 0x7598ee52bc
	public Void SelectDown() { }
	// RVA: 0x68cd33c VA: 0x7598ee533c
	public Void SelectTextEnd() { }
	// RVA: 0x68cd36c VA: 0x7598ee536c
	public Void SelectTextStart() { }
	// RVA: 0x68cd374 VA: 0x7598ee5374
	public Void MouseDragSelectsWholeWords(Boolean on) { }
	// RVA: 0x68cd388 VA: 0x7598ee5388
	public Void DblClickSnap(DblClickSnapping snapping) { }
	// RVA: 0x68cc910 VA: 0x7598ee4910
	private Int32 GetGraphicalLineStart(Int32 p) { }
	// RVA: 0x68cca08 VA: 0x7598ee4a08
	private Int32 GetGraphicalLineEnd(Int32 p) { }
	// RVA: 0x68cd390 VA: 0x7598ee5390
	private Int32 FindNextSeperator(Int32 startPos) { }
	// RVA: 0x68cd530 VA: 0x7598ee5530
	private Int32 FindPrevSeperator(Int32 startPos) { }
	// RVA: 0x68cd5cc VA: 0x7598ee55cc
	public Void MoveWordRight() { }
	// RVA: 0x68cd630 VA: 0x7598ee5630
	public Void MoveToStartOfNextWord() { }
	// RVA: 0x68cd690 VA: 0x7598ee5690
	public Void MoveToEndOfPreviousWord() { }
	// RVA: 0x68cd6f0 VA: 0x7598ee56f0
	public Void SelectToStartOfNextWord() { }
	// RVA: 0x68cd71c VA: 0x7598ee571c
	public Void SelectToEndOfPreviousWord() { }
	// RVA: 0x68cd42c VA: 0x7598ee542c
	private CharacterType ClassifyChar(Int32 index) { }
	// RVA: 0x68cbd9c VA: 0x7598ee3d9c
	public Int32 FindStartOfNextWord(Int32 p) { }
	// RVA: 0x68cbc24 VA: 0x7598ee3c24
	private Int32 FindEndOfPreviousWord(Int32 p) { }
	// RVA: 0x68cd748 VA: 0x7598ee5748
	public Void MoveWordLeft() { }
	// RVA: 0x68cd790 VA: 0x7598ee5790
	public Void SelectWordRight() { }
	// RVA: 0x68cd7f8 VA: 0x7598ee57f8
	public Void SelectWordLeft() { }
	// RVA: 0x68cd860 VA: 0x7598ee5860
	public Void ExpandSelectGraphicalLineStart() { }
	// RVA: 0x68cd8c4 VA: 0x7598ee58c4
	public Void ExpandSelectGraphicalLineEnd() { }
	// RVA: 0x68cd928 VA: 0x7598ee5928
	public Void SelectGraphicalLineStart() { }
	// RVA: 0x68cd954 VA: 0x7598ee5954
	public Void SelectGraphicalLineEnd() { }
	// RVA: 0x68cd980 VA: 0x7598ee5980
	public Void SelectParagraphForward() { }
	// RVA: 0x68cda0c VA: 0x7598ee5a0c
	public Void SelectParagraphBackward() { }
	// RVA: 0x68cdabc VA: 0x7598ee5abc
	public Void SelectCurrentWord() { }
	// RVA: 0x68cd054 VA: 0x7598ee5054
	private Int32 FindEndOfClassification(Int32 p, Direction dir) { }
	// RVA: 0x68cdb28 VA: 0x7598ee5b28
	public Void SelectCurrentParagraph() { }
	// RVA: 0x68cdbc0 VA: 0x7598ee5bc0
	public Void UpdateScrollOffsetIfNeeded(Event evt) { }
	// RVA: 0x68ca284 VA: 0x7598ee2284
	internal Void UpdateScrollOffset() { }
	// RVA: 0x68cdc1c VA: 0x7598ee5c1c
	public Void DrawCursor(String newText) { }
	// RVA: 0x68cb520 VA: 0x7598ee3520
	private Boolean PerformOperation(TextEditOp operation, Boolean textIsReadOnly) { }
	// RVA: 0x68ce190 VA: 0x7598ee6190
	public Void SaveBackup() { }
	// RVA: 0x68ce030 VA: 0x7598ee6030
	public Boolean Cut() { }
	// RVA: 0x68ce05c VA: 0x7598ee605c
	public Void Copy() { }
	// RVA: 0x68ce1cc VA: 0x7598ee61cc
	private static String ReplaceNewlinesWithSpaces(String value) { }
	// RVA: 0x68ce0ec VA: 0x7598ee60ec
	public Boolean Paste() { }
	// RVA: 0x68ce260 VA: 0x7598ee6260
	private static Void MapKey(String key, TextEditOp action) { }
	// RVA: 0x68caab4 VA: 0x7598ee2ab4
	private Void InitKeyActions() { }
	// RVA: 0x68cc5c4 VA: 0x7598ee45c4
	public Void DetectFocusChange() { }
	// RVA: 0x68ce2f0 VA: 0x7598ee62f0
	internal virtual Void OnDetectFocusChange() { }
	// RVA: 0x68ce38c VA: 0x7598ee638c
	internal virtual Void OnCursorIndexChange() { }
	// RVA: 0x68ce390 VA: 0x7598ee6390
	internal virtual Void OnSelectIndexChange() { }
	// RVA: 0x68ce394 VA: 0x7598ee6394
	private Void ClampTextIndex(ref Int32 index) { }
	// RVA: 0x68ca180 VA: 0x7598ee2180
	private Void EnsureValidCodePointIndex(ref Int32 index) { }
	// RVA: 0x68ce3e0 VA: 0x7598ee63e0
	private Boolean IsValidCodePointIndex(Int32 index) { }
	// RVA: 0x68cc208 VA: 0x7598ee4208
	private Int32 PreviousCodePointIndex(Int32 index) { }
	// RVA: 0x68cc024 VA: 0x7598ee4024
	private Int32 NextCodePointIndex(Int32 index) { }
}
```