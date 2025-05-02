# FontData

**Namespace:** `UnityEngine.UI`


## Fields

- `Font m_Font`

- `Int32 m_FontSize`

- `FontStyle m_FontStyle`

- `Boolean m_BestFit`

- `Int32 m_MinSize`

- `Int32 m_MaxSize`

- `TextAnchor m_Alignment`

- `Boolean m_AlignByGeometry`

- `Boolean m_RichText`

- `HorizontalWrapMode m_HorizontalOverflow`

- `VerticalWrapMode m_VerticalOverflow`

- `Single m_LineSpacing`


## Properties

- `Font font`

- `Int32 fontSize`

- `FontStyle fontStyle`

- `Boolean bestFit`

- `Int32 minSize`

- `Int32 maxSize`

- `TextAnchor alignment`

- `Boolean alignByGeometry`

- `Boolean richText`

- `HorizontalWrapMode horizontalOverflow`

- `VerticalWrapMode verticalOverflow`

- `Single lineSpacing`


## Methods

- `Font get_font()`

- `Void set_font(Font)`

- `Int32 get_fontSize()`

- `Void set_fontSize(Int32)`

- `FontStyle get_fontStyle()`

- `Void set_fontStyle(FontStyle)`

- `Boolean get_bestFit()`

- `Void set_bestFit(Boolean)`

- `Int32 get_minSize()`

- `Void set_minSize(Int32)`

- `Int32 get_maxSize()`

- `Void set_maxSize(Int32)`

- `TextAnchor get_alignment()`

- `Void set_alignment(TextAnchor)`

- `Boolean get_alignByGeometry()`

- `Void set_alignByGeometry(Boolean)`

- `Boolean get_richText()`

- `Void set_richText(Boolean)`

- `HorizontalWrapMode get_horizontalOverflow()`

- `Void set_horizontalOverflow(HorizontalWrapMode)`

- `VerticalWrapMode get_verticalOverflow()`

- `Void set_verticalOverflow(VerticalWrapMode)`

- `Single get_lineSpacing()`

- `Void set_lineSpacing(Single)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class FontData : ISerializationCallbackReceiver
{
	private Font m_Font; // 0x10
	private Int32 m_FontSize; // 0x18
	private FontStyle m_FontStyle; // 0x1c
	private Boolean m_BestFit; // 0x20
	private Int32 m_MinSize; // 0x24
	private Int32 m_MaxSize; // 0x28
	private TextAnchor m_Alignment; // 0x2c
	private Boolean m_AlignByGeometry; // 0x30
	private Boolean m_RichText; // 0x31
	private HorizontalWrapMode m_HorizontalOverflow; // 0x34
	private VerticalWrapMode m_VerticalOverflow; // 0x38
	private Single m_LineSpacing; // 0x3c

	public static FontData defaultFontData { get; }
	public Font font { get; set; }
	public Int32 fontSize { get; set; }
	public FontStyle fontStyle { get; set; }
	public Boolean bestFit { get; set; }
	public Int32 minSize { get; set; }
	public Int32 maxSize { get; set; }
	public TextAnchor alignment { get; set; }
	public Boolean alignByGeometry { get; set; }
	public Boolean richText { get; set; }
	public HorizontalWrapMode horizontalOverflow { get; set; }
	public VerticalWrapMode verticalOverflow { get; set; }
	public Single lineSpacing { get; set; }

	// RVA: 0x691d574 VA: 0x7598f35574
	public static FontData get_defaultFontData() { }
	// RVA: 0x691d60c VA: 0x7598f3560c
	public Font get_font() { }
	// RVA: 0x691d614 VA: 0x7598f35614
	public Void set_font(Font value) { }
	// RVA: 0x691d61c VA: 0x7598f3561c
	public Int32 get_fontSize() { }
	// RVA: 0x691d624 VA: 0x7598f35624
	public Void set_fontSize(Int32 value) { }
	// RVA: 0x691d62c VA: 0x7598f3562c
	public FontStyle get_fontStyle() { }
	// RVA: 0x691d634 VA: 0x7598f35634
	public Void set_fontStyle(FontStyle value) { }
	// RVA: 0x691d63c VA: 0x7598f3563c
	public Boolean get_bestFit() { }
	// RVA: 0x691d644 VA: 0x7598f35644
	public Void set_bestFit(Boolean value) { }
	// RVA: 0x691d650 VA: 0x7598f35650
	public Int32 get_minSize() { }
	// RVA: 0x691d658 VA: 0x7598f35658
	public Void set_minSize(Int32 value) { }
	// RVA: 0x691d660 VA: 0x7598f35660
	public Int32 get_maxSize() { }
	// RVA: 0x691d668 VA: 0x7598f35668
	public Void set_maxSize(Int32 value) { }
	// RVA: 0x691d670 VA: 0x7598f35670
	public TextAnchor get_alignment() { }
	// RVA: 0x691d678 VA: 0x7598f35678
	public Void set_alignment(TextAnchor value) { }
	// RVA: 0x691d680 VA: 0x7598f35680
	public Boolean get_alignByGeometry() { }
	// RVA: 0x691d688 VA: 0x7598f35688
	public Void set_alignByGeometry(Boolean value) { }
	// RVA: 0x691d694 VA: 0x7598f35694
	public Boolean get_richText() { }
	// RVA: 0x691d69c VA: 0x7598f3569c
	public Void set_richText(Boolean value) { }
	// RVA: 0x691d6a8 VA: 0x7598f356a8
	public HorizontalWrapMode get_horizontalOverflow() { }
	// RVA: 0x691d6b0 VA: 0x7598f356b0
	public Void set_horizontalOverflow(HorizontalWrapMode value) { }
	// RVA: 0x691d6b8 VA: 0x7598f356b8
	public VerticalWrapMode get_verticalOverflow() { }
	// RVA: 0x691d6c0 VA: 0x7598f356c0
	public Void set_verticalOverflow(VerticalWrapMode value) { }
	// RVA: 0x691d6c8 VA: 0x7598f356c8
	public Single get_lineSpacing() { }
	// RVA: 0x691d6d0 VA: 0x7598f356d0
	public Void set_lineSpacing(Single value) { }
	// RVA: 0x691d6d8 VA: 0x7598f356d8
	private Void UnityEngine.ISerializationCallbackReceiver.OnBeforeSerialize() { }
	// RVA: 0x691d6dc VA: 0x7598f356dc
	private Void UnityEngine.ISerializationCallbackReceiver.OnAfterDeserialize() { }
	// RVA: 0x691d604 VA: 0x7598f35604
	public Void .ctor() { }
}
```