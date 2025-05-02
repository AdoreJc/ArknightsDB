# Text

**Namespace:** `UnityEngine.UI`


## Fields

- `FontData m_FontData`

- `String m_Text`

- `TextGenerator m_TextCache`

- `TextGenerator m_TextCacheForLayout`

- `Boolean m_DisableFontTextureRebuiltCallback`

- `String m_InputText`

- `String m_TextId`

- `TextMode m_Mode`

- `String m_TextToShow`

- `Boolean m_TextNotFound`

- `String aspectsOnlyCachedTextId`

- `String aspectsOnlyCachedTextGetById`


## Properties

- `TextGenerator cachedTextGenerator`

- `TextGenerator cachedTextGeneratorForLayout`

- `Font font`

- `Boolean supportRichText`

- `Boolean resizeTextForBestFit`

- `Int32 resizeTextMinSize`

- `Int32 resizeTextMaxSize`

- `TextAnchor alignment`

- `Boolean alignByGeometry`

- `Int32 fontSize`

- `HorizontalWrapMode horizontalOverflow`

- `VerticalWrapMode verticalOverflow`

- `Single lineSpacing`

- `FontStyle fontStyle`

- `Single pixelsPerUnit`

- `String aspectsOnlyLegacyText`

- `String inputText`

- `TextMode mode`

- `String textId`


## Methods

- `TextGenerator get_cachedTextGenerator()`

- `TextGenerator get_cachedTextGeneratorForLayout()`

- `Void FontTextureChanged()`

- `Font get_font()`

- `Void set_font(Font)`

- `Boolean get_supportRichText()`

- `Void set_supportRichText(Boolean)`

- `Boolean get_resizeTextForBestFit()`

- `Void set_resizeTextForBestFit(Boolean)`

- `Int32 get_resizeTextMinSize()`

- `Void set_resizeTextMinSize(Int32)`

- `Int32 get_resizeTextMaxSize()`

- `Void set_resizeTextMaxSize(Int32)`

- `TextAnchor get_alignment()`

- `Void set_alignment(TextAnchor)`

- `Boolean get_alignByGeometry()`

- `Void set_alignByGeometry(Boolean)`

- `Int32 get_fontSize()`

- `Void set_fontSize(Int32)`

- `HorizontalWrapMode get_horizontalOverflow()`

- `Void set_horizontalOverflow(HorizontalWrapMode)`

- `VerticalWrapMode get_verticalOverflow()`

- `Void set_verticalOverflow(VerticalWrapMode)`

- `Single get_lineSpacing()`

- `Void set_lineSpacing(Single)`

- `FontStyle get_fontStyle()`

- `Void set_fontStyle(FontStyle)`

- `Single get_pixelsPerUnit()`

- `String get_aspectsOnlyLegacyText()`

- `Void set_aspectsOnlyLegacyText(String)`

- `String get_inputText()`

- `Void set_inputText(String)`

- `TextMode get_mode()`

- `Void set_mode(TextMode)`

- `String get_textId()`

- `Void set_textId(String)`

- `TextGenerationSettings GetGenerationSettings(Vector2)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Text : MaskableGraphic, ILayoutElement
{
	private FontData m_FontData; // 0xe0
	protected String m_Text; // 0xe8
	private TextGenerator m_TextCache; // 0xf0
	private TextGenerator m_TextCacheForLayout; // 0xf8
	protected static Material s_DefaultText; // 0x0
	protected Boolean m_DisableFontTextureRebuiltCallback; // 0x100
	protected String m_InputText; // 0x108
	private String m_TextId; // 0x110
	private TextMode m_Mode; // 0x118
	private String m_TextToShow; // 0x120
	private Boolean m_TextNotFound; // 0x128
	public String aspectsOnlyCachedTextId; // 0x130
	public String aspectsOnlyCachedTextGetById; // 0x138
	private static TextAspects s_aspects; // 0x8
	private readonly UIVertex[] m_TempVerts; // 0x140

	public TextGenerator cachedTextGenerator { get; }
	public TextGenerator cachedTextGeneratorForLayout { get; }
	public override Texture mainTexture { get; }
	public Font font { get; set; }
	public virtual String text { get; set; }
	public Boolean supportRichText { get; set; }
	public Boolean resizeTextForBestFit { get; set; }
	public Int32 resizeTextMinSize { get; set; }
	public Int32 resizeTextMaxSize { get; set; }
	public TextAnchor alignment { get; set; }
	public Boolean alignByGeometry { get; set; }
	public Int32 fontSize { get; set; }
	public HorizontalWrapMode horizontalOverflow { get; set; }
	public VerticalWrapMode verticalOverflow { get; set; }
	public Single lineSpacing { get; set; }
	public FontStyle fontStyle { get; set; }
	public Single pixelsPerUnit { get; }
	public String aspectsOnlyLegacyText { get; set; }
	public String inputText { get; set; }
	public TextMode mode { get; set; }
	public String textId { get; set; }
	public virtual Single minWidth { get; }
	public virtual Single preferredWidth { get; }
	public virtual Single flexibleWidth { get; }
	public virtual Single minHeight { get; }
	public virtual Single preferredHeight { get; }
	public virtual Single flexibleHeight { get; }
	public virtual Int32 layoutPriority { get; }

	// RVA: 0x6a695dc VA: 0x75990815dc
	protected Void .ctor() { }
	// RVA: 0x6a696c4 VA: 0x75990816c4
	public TextGenerator get_cachedTextGenerator() { }
	// RVA: 0x6a697a8 VA: 0x75990817a8
	public TextGenerator get_cachedTextGeneratorForLayout() { }
	// RVA: 0x6a69820 VA: 0x7599081820
	public override Texture get_mainTexture() { }
	// RVA: 0x6a699e4 VA: 0x75990819e4
	public Void FontTextureChanged() { }
	// RVA: 0x6a699c8 VA: 0x75990819c8
	public Font get_font() { }
	// RVA: 0x6a69af0 VA: 0x7599081af0
	public Void set_font(Font value) { }
	// RVA: 0x6a69c04 VA: 0x7599081c04
	public virtual String get_text() { }
	// RVA: 0x6a69c70 VA: 0x7599081c70
	public virtual Void set_text(String value) { }
	// RVA: 0x6a69d2c VA: 0x7599081d2c
	public Boolean get_supportRichText() { }
	// RVA: 0x6a69d48 VA: 0x7599081d48
	public Void set_supportRichText(Boolean value) { }
	// RVA: 0x6a69da8 VA: 0x7599081da8
	public Boolean get_resizeTextForBestFit() { }
	// RVA: 0x6a69dc4 VA: 0x7599081dc4
	public Void set_resizeTextForBestFit(Boolean value) { }
	// RVA: 0x6a69e24 VA: 0x7599081e24
	public Int32 get_resizeTextMinSize() { }
	// RVA: 0x6a69e40 VA: 0x7599081e40
	public Void set_resizeTextMinSize(Int32 value) { }
	// RVA: 0x6a69e94 VA: 0x7599081e94
	public Int32 get_resizeTextMaxSize() { }
	// RVA: 0x6a69eb0 VA: 0x7599081eb0
	public Void set_resizeTextMaxSize(Int32 value) { }
	// RVA: 0x6a69f04 VA: 0x7599081f04
	public TextAnchor get_alignment() { }
	// RVA: 0x6a69f20 VA: 0x7599081f20
	public Void set_alignment(TextAnchor value) { }
	// RVA: 0x6a69f74 VA: 0x7599081f74
	public Boolean get_alignByGeometry() { }
	// RVA: 0x6a69f90 VA: 0x7599081f90
	public Void set_alignByGeometry(Boolean value) { }
	// RVA: 0x6a69fd8 VA: 0x7599081fd8
	public Int32 get_fontSize() { }
	// RVA: 0x6a69ff4 VA: 0x7599081ff4
	public Void set_fontSize(Int32 value) { }
	// RVA: 0x6a6a048 VA: 0x7599082048
	public HorizontalWrapMode get_horizontalOverflow() { }
	// RVA: 0x6a6a064 VA: 0x7599082064
	public Void set_horizontalOverflow(HorizontalWrapMode value) { }
	// RVA: 0x6a6a0b8 VA: 0x75990820b8
	public VerticalWrapMode get_verticalOverflow() { }
	// RVA: 0x6a6a0d4 VA: 0x75990820d4
	public Void set_verticalOverflow(VerticalWrapMode value) { }
	// RVA: 0x6a6a128 VA: 0x7599082128
	public Single get_lineSpacing() { }
	// RVA: 0x6a6a144 VA: 0x7599082144
	public Void set_lineSpacing(Single value) { }
	// RVA: 0x6a6a198 VA: 0x7599082198
	public FontStyle get_fontStyle() { }
	// RVA: 0x6a6a1b4 VA: 0x75990821b4
	public Void set_fontStyle(FontStyle value) { }
	// RVA: 0x6a6a208 VA: 0x7599082208
	public Single get_pixelsPerUnit() { }
	// RVA: 0x6a6a350 VA: 0x7599082350
	public String get_aspectsOnlyLegacyText() { }
	// RVA: 0x6a6a358 VA: 0x7599082358
	public Void set_aspectsOnlyLegacyText(String value) { }
	// RVA: 0x6a6a360 VA: 0x7599082360
	public String get_inputText() { }
	// RVA: 0x6a6a368 VA: 0x7599082368
	public Void set_inputText(String value) { }
	// RVA: 0x6a6a378 VA: 0x7599082378
	public TextMode get_mode() { }
	// RVA: 0x6a6a380 VA: 0x7599082380
	public Void set_mode(TextMode value) { }
	// RVA: 0x6a6a388 VA: 0x7599082388
	public String get_textId() { }
	// RVA: 0x6a6a390 VA: 0x7599082390
	public Void set_textId(String value) { }
	// RVA: 0x6a6a3a0 VA: 0x75990823a0
	public static Void BindAspects(TextAspects aspects) { }
	// RVA: 0x6a6a3f0 VA: 0x75990823f0
	protected override Void OnEnable() { }
	// RVA: 0x6a6a46c VA: 0x759908246c
	protected override Void OnDisable() { }
	// RVA: 0x6a6a4d0 VA: 0x75990824d0
	protected override Void UpdateGeometry() { }
	// RVA: 0x6a6a558 VA: 0x7599082558
	internal Void AssignDefaultFont() { }
	// RVA: 0x6a6a5c8 VA: 0x75990825c8
	internal Void AssignDefaultFontIfNecessary() { }
	// RVA: 0x6a6a684 VA: 0x7599082684
	public TextGenerationSettings GetGenerationSettings(Vector2 extents) { }
	// RVA: 0x6a6a818 VA: 0x7599082818
	public static Vector2 GetTextAnchorPivot(TextAnchor anchor) { }
	// RVA: 0x6a6a884 VA: 0x7599082884
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x6a6af84 VA: 0x7599082f84
	public virtual Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x6a6af88 VA: 0x7599082f88
	public virtual Void CalculateLayoutInputVertical() { }
	// RVA: 0x6a6af8c VA: 0x7599082f8c
	public virtual Single get_minWidth() { }
	// RVA: 0x6a6af94 VA: 0x7599082f94
	public virtual Single get_preferredWidth() { }
	// RVA: 0x6a6b0c0 VA: 0x75990830c0
	public virtual Single get_flexibleWidth() { }
	// RVA: 0x6a6b0c8 VA: 0x75990830c8
	public virtual Single get_minHeight() { }
	// RVA: 0x6a6b0d0 VA: 0x75990830d0
	public virtual Single get_preferredHeight() { }
	// RVA: 0x6a6b1ec VA: 0x75990831ec
	public virtual Single get_flexibleHeight() { }
	// RVA: 0x6a6b1f4 VA: 0x75990831f4
	public virtual Int32 get_layoutPriority() { }
}
```