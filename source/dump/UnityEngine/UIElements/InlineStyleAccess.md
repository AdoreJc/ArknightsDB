# InlineStyleAccess

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement <ve>k__BackingField`

- `Boolean m_HasInlineCursor`

- `StyleCursor m_InlineCursor`

- `Boolean m_HasInlineTextShadow`

- `StyleTextShadow m_InlineTextShadow`

- `Boolean m_HasInlineTransformOrigin`

- `StyleTransformOrigin m_InlineTransformOrigin`

- `Boolean m_HasInlineTranslate`

- `StyleTranslate m_InlineTranslateOperation`

- `Boolean m_HasInlineRotate`

- `StyleRotate m_InlineRotateOperation`

- `Boolean m_HasInlineScale`

- `StyleScale m_InlineScale`

- `InlineRule m_InlineRule`


## Properties

- `VisualElement ve`


## Methods

- `VisualElement get_ve()`

- `Void set_ve(VisualElement)`

- `Void SetInlineRule(StyleSheet, StyleRule)`

- `Boolean IsValueSet(StylePropertyId)`

- `Void ApplyInlineStyles(ref)`

- `Boolean SetStyleValue(StylePropertyId, StyleLength)`

- `Boolean SetStyleValue(StylePropertyId, StyleFloat)`

- `Boolean SetStyleValue(StylePropertyId, StyleColor)`

- `Boolean SetStyleValue(StylePropertyId, StyleEnum`1)`

- `Boolean SetInlineTranslate(StyleTranslate)`

- `Void ApplyStyleTranslate(StyleTranslate)`

- `Void ApplyStyleValue(StyleValue)`

- `Boolean RemoveInlineStyle(StylePropertyId)`

- `Void ApplyFromComputedStyle(StylePropertyId, ref)`

- `Boolean TryGetInlineCursor(ref)`

- `Boolean TryGetInlineTextShadow(ref)`

- `Boolean TryGetInlineTransformOrigin(ref)`

- `Boolean TryGetInlineTranslate(ref)`

- `Boolean TryGetInlineRotate(ref)`

- `Boolean TryGetInlineScale(ref)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class InlineStyleAccess : StyleValueCollection, IStyle
{
	private static StylePropertyReader s_StylePropertyReader; // 0x0
	private List`1 m_ValuesManaged; // 0x18
	private VisualElement <ve>k__BackingField; // 0x20
	private Boolean m_HasInlineCursor; // 0x28
	private StyleCursor m_InlineCursor; // 0x30
	private Boolean m_HasInlineTextShadow; // 0x50
	private StyleTextShadow m_InlineTextShadow; // 0x54
	private Boolean m_HasInlineTransformOrigin; // 0x74
	private StyleTransformOrigin m_InlineTransformOrigin; // 0x78
	private Boolean m_HasInlineTranslate; // 0x90
	private StyleTranslate m_InlineTranslateOperation; // 0x94
	private Boolean m_HasInlineRotate; // 0xb0
	private StyleRotate m_InlineRotateOperation; // 0xb4
	private Boolean m_HasInlineScale; // 0xd0
	private StyleScale m_InlineScale; // 0xd4
	private InlineRule m_InlineRule; // 0xe8

	private VisualElement ve { get; set; }
	private StyleCursor UnityEngine.UIElements.IStyle.cursor { get; }
	private StyleTextShadow UnityEngine.UIElements.IStyle.textShadow { get; }
	private StyleTransformOrigin UnityEngine.UIElements.IStyle.transformOrigin { get; }
	private StyleTranslate UnityEngine.UIElements.IStyle.translate { get; set; }
	private StyleRotate UnityEngine.UIElements.IStyle.rotate { get; }
	private StyleScale UnityEngine.UIElements.IStyle.scale { get; }
	private StyleColor UnityEngine.UIElements.IStyle.backgroundColor { set; }
	private StyleColor UnityEngine.UIElements.IStyle.borderBottomColor { set; }
	private StyleLength UnityEngine.UIElements.IStyle.borderBottomLeftRadius { set; }
	private StyleLength UnityEngine.UIElements.IStyle.borderBottomRightRadius { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.borderBottomWidth { set; }
	private StyleColor UnityEngine.UIElements.IStyle.borderLeftColor { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.borderLeftWidth { set; }
	private StyleColor UnityEngine.UIElements.IStyle.borderRightColor { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.borderRightWidth { set; }
	private StyleColor UnityEngine.UIElements.IStyle.borderTopColor { set; }
	private StyleLength UnityEngine.UIElements.IStyle.borderTopLeftRadius { set; }
	private StyleLength UnityEngine.UIElements.IStyle.borderTopRightRadius { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.borderTopWidth { set; }
	private StyleLength UnityEngine.UIElements.IStyle.bottom { set; }
	private StyleColor UnityEngine.UIElements.IStyle.color { set; }
	private StyleEnum`1 UnityEngine.UIElements.IStyle.display { get; set; }
	private StyleLength UnityEngine.UIElements.IStyle.flexBasis { set; }
	private StyleEnum`1 UnityEngine.UIElements.IStyle.flexDirection { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.flexGrow { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.flexShrink { set; }
	private StyleLength UnityEngine.UIElements.IStyle.fontSize { set; }
	private StyleLength UnityEngine.UIElements.IStyle.height { set; }
	private StyleLength UnityEngine.UIElements.IStyle.left { set; }
	private StyleLength UnityEngine.UIElements.IStyle.marginBottom { set; }
	private StyleLength UnityEngine.UIElements.IStyle.marginLeft { set; }
	private StyleLength UnityEngine.UIElements.IStyle.marginRight { set; }
	private StyleLength UnityEngine.UIElements.IStyle.marginTop { set; }
	private StyleLength UnityEngine.UIElements.IStyle.maxHeight { set; }
	private StyleLength UnityEngine.UIElements.IStyle.minWidth { set; }
	private StyleFloat UnityEngine.UIElements.IStyle.opacity { set; }
	private StyleLength UnityEngine.UIElements.IStyle.paddingBottom { set; }
	private StyleLength UnityEngine.UIElements.IStyle.paddingLeft { set; }
	private StyleLength UnityEngine.UIElements.IStyle.paddingRight { set; }
	private StyleLength UnityEngine.UIElements.IStyle.paddingTop { get; set; }
	private StyleEnum`1 UnityEngine.UIElements.IStyle.position { set; }
	private StyleLength UnityEngine.UIElements.IStyle.right { set; }
	private StyleLength UnityEngine.UIElements.IStyle.top { set; }
	private StyleColor UnityEngine.UIElements.IStyle.unityBackgroundImageTintColor { set; }
	private StyleEnum`1 UnityEngine.UIElements.IStyle.visibility { set; }
	private StyleLength UnityEngine.UIElements.IStyle.width { get; set; }

	// RVA: 0x6a0f3fc VA: 0x75990273fc
	private VisualElement get_ve() { }
	// RVA: 0x6a0f404 VA: 0x7599027404
	private Void set_ve(VisualElement value) { }
	// RVA: 0x6a0f40c VA: 0x759902740c
	public Void .ctor(VisualElement ve) { }
	// RVA: 0x6a0f438 VA: 0x7599027438
	protected override Void Finalize() { }
	// RVA: 0x6a0f580 VA: 0x7599027580
	public Void SetInlineRule(StyleSheet sheet, StyleRule rule) { }
	// RVA: 0x6a0ffe0 VA: 0x7599027fe0
	public Boolean IsValueSet(StylePropertyId id) { }
	// RVA: 0x6a0f63c VA: 0x759902763c
	public Void ApplyInlineStyles(ref ComputedStyle computedStyle) { }
	// RVA: 0x6a102f0 VA: 0x75990282f0
	private StyleCursor UnityEngine.UIElements.IStyle.get_cursor() { }
	// RVA: 0x6a1038c VA: 0x759902838c
	private StyleTextShadow UnityEngine.UIElements.IStyle.get_textShadow() { }
	// RVA: 0x6a10408 VA: 0x7599028408
	private StyleTransformOrigin UnityEngine.UIElements.IStyle.get_transformOrigin() { }
	// RVA: 0x6a1049c VA: 0x759902849c
	private StyleTranslate UnityEngine.UIElements.IStyle.get_translate() { }
	// RVA: 0x6a1053c VA: 0x759902853c
	private Void UnityEngine.UIElements.IStyle.set_translate(StyleTranslate value) { }
	// RVA: 0x6a106e4 VA: 0x75990286e4
	private StyleRotate UnityEngine.UIElements.IStyle.get_rotate() { }
	// RVA: 0x6a10784 VA: 0x7599028784
	private StyleScale UnityEngine.UIElements.IStyle.get_scale() { }
	// RVA: 0x6a10818 VA: 0x7599028818
	private Boolean SetStyleValue(StylePropertyId id, StyleLength inlineValue) { }
	// RVA: 0x6a10d38 VA: 0x7599028d38
	private Boolean SetStyleValue(StylePropertyId id, StyleFloat inlineValue) { }
	// RVA: 0x6a10e78 VA: 0x7599028e78
	private Boolean SetStyleValue(StylePropertyId id, StyleColor inlineValue) { }
	// RVA: 0x VA: 0x0
	private Boolean SetStyleValue(StylePropertyId id, StyleEnum`1 inlineValue) { }
	// RVA: 0x6a10588 VA: 0x7599028588
	private Boolean SetInlineTranslate(StyleTranslate inlineValue) { }
	// RVA: 0x6a10ffc VA: 0x7599028ffc
	private Void ApplyStyleTranslate(StyleTranslate translate) { }
	// RVA: 0x6a10a58 VA: 0x7599028a58
	private Void ApplyStyleValue(StyleValue value) { }
	// RVA: 0x6a10968 VA: 0x7599028968
	private Boolean RemoveInlineStyle(StylePropertyId id) { }
	// RVA: 0x6a1121c VA: 0x759902921c
	private Void ApplyFromComputedStyle(StylePropertyId id, ref ComputedStyle newStyle) { }
	// RVA: 0x6a10358 VA: 0x7599028358
	public Boolean TryGetInlineCursor(ref StyleCursor value) { }
	// RVA: 0x6a103e4 VA: 0x75990283e4
	public Boolean TryGetInlineTextShadow(ref StyleTextShadow value) { }
	// RVA: 0x6a10474 VA: 0x7599028474
	public Boolean TryGetInlineTransformOrigin(ref StyleTransformOrigin value) { }
	// RVA: 0x6a1050c VA: 0x759902850c
	public Boolean TryGetInlineTranslate(ref StyleTranslate value) { }
	// RVA: 0x6a10754 VA: 0x7599028754
	public Boolean TryGetInlineRotate(ref StyleRotate value) { }
	// RVA: 0x6a107f0 VA: 0x75990287f0
	public Boolean TryGetInlineScale(ref StyleScale value) { }
	// RVA: 0x6a1143c VA: 0x759902943c
	private Void UnityEngine.UIElements.IStyle.set_backgroundColor(StyleColor value) { }
	// RVA: 0x6a1148c VA: 0x759902948c
	private Void UnityEngine.UIElements.IStyle.set_borderBottomColor(StyleColor value) { }
	// RVA: 0x6a114e0 VA: 0x75990294e0
	private Void UnityEngine.UIElements.IStyle.set_borderBottomLeftRadius(StyleLength value) { }
	// RVA: 0x6a11528 VA: 0x7599029528
	private Void UnityEngine.UIElements.IStyle.set_borderBottomRightRadius(StyleLength value) { }
	// RVA: 0x6a11570 VA: 0x7599029570
	private Void UnityEngine.UIElements.IStyle.set_borderBottomWidth(StyleFloat value) { }
	// RVA: 0x6a115dc VA: 0x75990295dc
	private Void UnityEngine.UIElements.IStyle.set_borderLeftColor(StyleColor value) { }
	// RVA: 0x6a11630 VA: 0x7599029630
	private Void UnityEngine.UIElements.IStyle.set_borderLeftWidth(StyleFloat value) { }
	// RVA: 0x6a1169c VA: 0x759902969c
	private Void UnityEngine.UIElements.IStyle.set_borderRightColor(StyleColor value) { }
	// RVA: 0x6a116f0 VA: 0x75990296f0
	private Void UnityEngine.UIElements.IStyle.set_borderRightWidth(StyleFloat value) { }
	// RVA: 0x6a1175c VA: 0x759902975c
	private Void UnityEngine.UIElements.IStyle.set_borderTopColor(StyleColor value) { }
	// RVA: 0x6a117ac VA: 0x75990297ac
	private Void UnityEngine.UIElements.IStyle.set_borderTopLeftRadius(StyleLength value) { }
	// RVA: 0x6a117f4 VA: 0x75990297f4
	private Void UnityEngine.UIElements.IStyle.set_borderTopRightRadius(StyleLength value) { }
	// RVA: 0x6a1183c VA: 0x759902983c
	private Void UnityEngine.UIElements.IStyle.set_borderTopWidth(StyleFloat value) { }
	// RVA: 0x6a118a8 VA: 0x75990298a8
	private Void UnityEngine.UIElements.IStyle.set_bottom(StyleLength value) { }
	// RVA: 0x6a11928 VA: 0x7599029928
	private Void UnityEngine.UIElements.IStyle.set_color(StyleColor value) { }
	// RVA: 0x6a11978 VA: 0x7599029978
	private StyleEnum`1 UnityEngine.UIElements.IStyle.get_display() { }
	// RVA: 0x6a11a0c VA: 0x7599029a0c
	private Void UnityEngine.UIElements.IStyle.set_display(StyleEnum`1 value) { }
	// RVA: 0x6a11ac8 VA: 0x7599029ac8
	private Void UnityEngine.UIElements.IStyle.set_flexBasis(StyleLength value) { }
	// RVA: 0x6a11b48 VA: 0x7599029b48
	private Void UnityEngine.UIElements.IStyle.set_flexDirection(StyleEnum`1 value) { }
	// RVA: 0x6a11c04 VA: 0x7599029c04
	private Void UnityEngine.UIElements.IStyle.set_flexGrow(StyleFloat value) { }
	// RVA: 0x6a11c70 VA: 0x7599029c70
	private Void UnityEngine.UIElements.IStyle.set_flexShrink(StyleFloat value) { }
	// RVA: 0x6a11cdc VA: 0x7599029cdc
	private Void UnityEngine.UIElements.IStyle.set_fontSize(StyleLength value) { }
	// RVA: 0x6a11d20 VA: 0x7599029d20
	private Void UnityEngine.UIElements.IStyle.set_height(StyleLength value) { }
	// RVA: 0x6a11da0 VA: 0x7599029da0
	private Void UnityEngine.UIElements.IStyle.set_left(StyleLength value) { }
	// RVA: 0x6a11e20 VA: 0x7599029e20
	private Void UnityEngine.UIElements.IStyle.set_marginBottom(StyleLength value) { }
	// RVA: 0x6a11ea0 VA: 0x7599029ea0
	private Void UnityEngine.UIElements.IStyle.set_marginLeft(StyleLength value) { }
	// RVA: 0x6a11f20 VA: 0x7599029f20
	private Void UnityEngine.UIElements.IStyle.set_marginRight(StyleLength value) { }
	// RVA: 0x6a11fa0 VA: 0x7599029fa0
	private Void UnityEngine.UIElements.IStyle.set_marginTop(StyleLength value) { }
	// RVA: 0x6a12020 VA: 0x759902a020
	private Void UnityEngine.UIElements.IStyle.set_maxHeight(StyleLength value) { }
	// RVA: 0x6a120a0 VA: 0x759902a0a0
	private Void UnityEngine.UIElements.IStyle.set_minWidth(StyleLength value) { }
	// RVA: 0x6a12120 VA: 0x759902a120
	private Void UnityEngine.UIElements.IStyle.set_opacity(StyleFloat value) { }
	// RVA: 0x6a12160 VA: 0x759902a160
	private Void UnityEngine.UIElements.IStyle.set_paddingBottom(StyleLength value) { }
	// RVA: 0x6a121e0 VA: 0x759902a1e0
	private Void UnityEngine.UIElements.IStyle.set_paddingLeft(StyleLength value) { }
	// RVA: 0x6a12260 VA: 0x759902a260
	private Void UnityEngine.UIElements.IStyle.set_paddingRight(StyleLength value) { }
	// RVA: 0x6a122e0 VA: 0x759902a2e0
	private StyleLength UnityEngine.UIElements.IStyle.get_paddingTop() { }
	// RVA: 0x6a122fc VA: 0x759902a2fc
	private Void UnityEngine.UIElements.IStyle.set_paddingTop(StyleLength value) { }
	// RVA: 0x6a1237c VA: 0x759902a37c
	private Void UnityEngine.UIElements.IStyle.set_position(StyleEnum`1 value) { }
	// RVA: 0x6a12438 VA: 0x759902a438
	private Void UnityEngine.UIElements.IStyle.set_right(StyleLength value) { }
	// RVA: 0x6a124b8 VA: 0x759902a4b8
	private Void UnityEngine.UIElements.IStyle.set_top(StyleLength value) { }
	// RVA: 0x6a12538 VA: 0x759902a538
	private Void UnityEngine.UIElements.IStyle.set_unityBackgroundImageTintColor(StyleColor value) { }
	// RVA: 0x6a1258c VA: 0x759902a58c
	private Void UnityEngine.UIElements.IStyle.set_visibility(StyleEnum`1 value) { }
	// RVA: 0x6a1261c VA: 0x759902a61c
	private StyleLength UnityEngine.UIElements.IStyle.get_width() { }
	// RVA: 0x6a12638 VA: 0x759902a638
	private Void UnityEngine.UIElements.IStyle.set_width(StyleLength value) { }
	// RVA: 0x6a126b8 VA: 0x759902a6b8
	private static Void .cctor() { }
}
```