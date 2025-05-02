# TextElement

**Namespace:** `UnityEngine.UIElements`


## Fields

- `ITextHandle m_TextHandle`

- `String m_Text`

- `Boolean m_EnableRichText`

- `Boolean m_DisplayTooltipWhenElided`

- `Boolean <isElided>k__BackingField`

- `Boolean m_WasElided`

- `Boolean m_UpdateTextParams`

- `TextParams m_TextParams`

- `Int32 m_PreviousTextParamsHashCode`


## Properties

- `Boolean enableRichText`

- `Boolean displayTooltipWhenElided`

- `Boolean isElided`


## Methods

- `Void OnGeometryChanged(GeometryChangedEvent)`

- `Boolean get_enableRichText()`

- `Void set_enableRichText(Boolean)`

- `Boolean get_displayTooltipWhenElided()`

- `Void set_displayTooltipWhenElided(Boolean)`

- `Boolean get_isElided()`

- `Void set_isElided(Boolean)`

- `Void OnGenerateVisualContent(MeshGenerationContext)`

- `Void UpdateTooltip()`

- `Void UpdateVisibleText()`

- `Boolean ShouldElide()`

- `Boolean TextLibraryCanElide()`

- `Vector2 MeasureTextSize(String, Single, MeasureMode, Single, MeasureMode)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class TextElement : BindableElement, ITextElement, INotifyValueChanged`1
{
	public static readonly String ussClassName; // 0x0
	private ITextHandle m_TextHandle; // 0x3c0
	internal static Int32 maxTextVertices; // 0x8
	private String m_Text; // 0x3c8
	private Boolean m_EnableRichText; // 0x3d0
	private Boolean m_DisplayTooltipWhenElided; // 0x3d1
	private Boolean <isElided>k__BackingField; // 0x3d2
	internal static readonly String k_EllipsisText; // 0x10
	private Boolean m_WasElided; // 0x3d3
	private Boolean m_UpdateTextParams; // 0x3d4
	private TextParams m_TextParams; // 0x3d8
	private Int32 m_PreviousTextParamsHashCode; // 0x470

	internal ITextHandle textHandle { get; set; }
	public virtual String text { get; set; }
	public Boolean enableRichText { get; set; }
	public Boolean displayTooltipWhenElided { get; set; }
	public Boolean isElided { get; set; }
	private String UnityEngine.UIElements.INotifyValueChanged<System.String>.value { get; set; }

	// RVA: 0x698c4ac VA: 0x7598fa44ac
	public Void .ctor() { }
	// RVA: 0x698c680 VA: 0x7598fa4680
	internal ITextHandle get_textHandle() { }
	// RVA: 0x698c688 VA: 0x7598fa4688
	internal Void set_textHandle(ITextHandle value) { }
	// RVA: 0x698c698 VA: 0x7598fa4698
	public override Void HandleEvent(EventBase evt) { }
	// RVA: 0x698c820 VA: 0x7598fa4820
	private Void OnGeometryChanged(GeometryChangedEvent e) { }
	// RVA: 0x698c9bc VA: 0x7598fa49bc
	public virtual String get_text() { }
	// RVA: 0x698ca50 VA: 0x7598fa4a50
	public virtual Void set_text(String value) { }
	// RVA: 0x698caf8 VA: 0x7598fa4af8
	public Boolean get_enableRichText() { }
	// RVA: 0x698cb00 VA: 0x7598fa4b00
	public Void set_enableRichText(Boolean value) { }
	// RVA: 0x698cb20 VA: 0x7598fa4b20
	public Boolean get_displayTooltipWhenElided() { }
	// RVA: 0x698cb28 VA: 0x7598fa4b28
	public Void set_displayTooltipWhenElided(Boolean value) { }
	// RVA: 0x698cb64 VA: 0x7598fa4b64
	public Boolean get_isElided() { }
	// RVA: 0x698cb6c VA: 0x7598fa4b6c
	private Void set_isElided(Boolean value) { }
	// RVA: 0x698cb78 VA: 0x7598fa4b78
	private Void OnGenerateVisualContent(MeshGenerationContext mgc) { }
	// RVA: 0x698ce2c VA: 0x7598fa4e2c
	internal String ElideText(String drawText, String ellipsisText, Single width, TextOverflowPosition textOverflowPosition) { }
	// RVA: 0x698cdc0 VA: 0x7598fa4dc0
	private Void UpdateTooltip() { }
	// RVA: 0x698c824 VA: 0x7598fa4824
	private Void UpdateVisibleText() { }
	// RVA: 0x698cc98 VA: 0x7598fa4c98
	private Boolean ShouldElide() { }
	// RVA: 0x698cd00 VA: 0x7598fa4d00
	private Boolean TextLibraryCanElide() { }
	// RVA: 0x698d2f8 VA: 0x7598fa52f8
	public Vector2 MeasureTextSize(String textToMeasure, Single width, MeasureMode widthMode, Single height, MeasureMode heightMode) { }
	// RVA: 0x698d304 VA: 0x7598fa5304
	protected internal override Vector2 DoMeasure(Single desiredWidth, MeasureMode widthMode, Single desiredHeight, MeasureMode heightMode) { }
	// RVA: 0x698d364 VA: 0x7598fa5364
	private String UnityEngine.UIElements.INotifyValueChanged<System.String>.get_value() { }
	// RVA: 0x698d3b8 VA: 0x7598fa53b8
	private Void UnityEngine.UIElements.INotifyValueChanged<System.String>.set_value(String value) { }
	// RVA: 0x698d684 VA: 0x7598fa5684
	private Void UnityEngine.UIElements.INotifyValueChanged<System.String>.SetValueWithoutNotify(String newValue) { }
	// RVA: 0x698d6fc VA: 0x7598fa56fc
	private static Void .cctor() { }
}
```