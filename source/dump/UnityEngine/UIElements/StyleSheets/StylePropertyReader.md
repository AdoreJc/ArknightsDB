# StylePropertyReader

**Namespace:** `UnityEngine.UIElements.StyleSheets`


## Fields

- `StyleVariableResolver m_Resolver`

- `StyleSheet m_Sheet`

- `Int32 m_CurrentValueIndex`

- `Int32 m_CurrentPropertyIndex`

- `StyleProperty <property>k__BackingField`

- `StylePropertyId <propertyId>k__BackingField`

- `Int32 <valueCount>k__BackingField`

- `Single <dpiScaling>k__BackingField`


## Properties

- `StyleProperty property`

- `StylePropertyId propertyId`

- `Int32 valueCount`

- `Single dpiScaling`


## Methods

- `StyleProperty get_property()`

- `Void set_property(StyleProperty)`

- `StylePropertyId get_propertyId()`

- `Void set_propertyId(StylePropertyId)`

- `Int32 get_valueCount()`

- `Void set_valueCount(Int32)`

- `Single get_dpiScaling()`

- `Void set_dpiScaling(Single)`

- `Void SetContext(StyleSheet, StyleComplexSelector, StyleVariableContext, Single)`

- `Void SetInlineContext(StyleSheet, StyleProperty[], StylePropertyId[], Single)`

- `StylePropertyId MoveNextProperty()`

- `StylePropertyValue GetValue(Int32)`

- `StyleValueType GetValueType(Int32)`

- `Boolean IsValueType(Int32, StyleValueType)`

- `Boolean IsKeyword(Int32, StyleValueKeyword)`

- `String ReadAsString(Int32)`

- `Length ReadLength(Int32)`

- `TimeValue ReadTimeValue(Int32)`

- `Translate ReadTranslate(Int32)`

- `TransformOrigin ReadTransformOrigin(Int32)`

- `Rotate ReadRotate(Int32)`

- `Scale ReadScale(Int32)`

- `Single ReadFloat(Int32)`

- `Int32 ReadInt(Int32)`

- `Color ReadColor(Int32)`

- `Int32 ReadEnum(StyleEnumType, Int32)`

- `FontDefinition ReadFontDefinition(Int32)`

- `Font ReadFont(Int32)`

- `Background ReadBackground(Int32)`

- `Cursor ReadCursor(Int32)`

- `TextShadow ReadTextShadow(Int32)`

- `Void ReadListEasingFunction(List`1, Int32)`

- `Void ReadListTimeValue(List`1, Int32)`

- `Void ReadListStylePropertyName(List`1, Int32)`

- `Void LoadProperties()`

- `Void SetCurrentProperty()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.StyleSheets
internal class StylePropertyReader
{
	internal static GetCursorIdFunction getCursorIdFunc; // 0x0
	private List`1 m_Values; // 0x10
	private List`1 m_ValueCount; // 0x18
	private StyleVariableResolver m_Resolver; // 0x20
	private StyleSheet m_Sheet; // 0x28
	private StyleProperty[] m_Properties; // 0x30
	private StylePropertyId[] m_PropertyIds; // 0x38
	private Int32 m_CurrentValueIndex; // 0x40
	private Int32 m_CurrentPropertyIndex; // 0x44
	private StyleProperty <property>k__BackingField; // 0x48
	private StylePropertyId <propertyId>k__BackingField; // 0x50
	private Int32 <valueCount>k__BackingField; // 0x54
	private Single <dpiScaling>k__BackingField; // 0x58

	public StyleProperty property { get; set; }
	public StylePropertyId propertyId { get; set; }
	public Int32 valueCount { get; set; }
	public Single dpiScaling { get; set; }

	// RVA: 0x697dba8 VA: 0x7598f95ba8
	public StyleProperty get_property() { }
	// RVA: 0x697dbb0 VA: 0x7598f95bb0
	private Void set_property(StyleProperty value) { }
	// RVA: 0x697dbb8 VA: 0x7598f95bb8
	public StylePropertyId get_propertyId() { }
	// RVA: 0x697dbc0 VA: 0x7598f95bc0
	private Void set_propertyId(StylePropertyId value) { }
	// RVA: 0x697dbc8 VA: 0x7598f95bc8
	public Int32 get_valueCount() { }
	// RVA: 0x697dbd0 VA: 0x7598f95bd0
	private Void set_valueCount(Int32 value) { }
	// RVA: 0x697dbd8 VA: 0x7598f95bd8
	public Single get_dpiScaling() { }
	// RVA: 0x697dbe0 VA: 0x7598f95be0
	private Void set_dpiScaling(Single value) { }
	// RVA: 0x697dbe8 VA: 0x7598f95be8
	public Void SetContext(StyleSheet sheet, StyleComplexSelector selector, StyleVariableContext varContext, Single dpiScaling) { }
	// RVA: 0x697e304 VA: 0x7598f96304
	public Void SetInlineContext(StyleSheet sheet, StyleProperty[] properties, StylePropertyId[] propertyIds, Single dpiScaling) { }
	// RVA: 0x697e360 VA: 0x7598f96360
	public StylePropertyId MoveNextProperty() { }
	// RVA: 0x697e470 VA: 0x7598f96470
	public StylePropertyValue GetValue(Int32 index) { }
	// RVA: 0x697bc44 VA: 0x7598f93c44
	public StyleValueType GetValueType(Int32 index) { }
	// RVA: 0x697bb0c VA: 0x7598f93b0c
	public Boolean IsValueType(Int32 index, StyleValueType type) { }
	// RVA: 0x697bba0 VA: 0x7598f93ba0
	public Boolean IsKeyword(Int32 index, StyleValueKeyword keyword) { }
	// RVA: 0x697bfbc VA: 0x7598f93fbc
	public String ReadAsString(Int32 index) { }
	// RVA: 0x697bcc4 VA: 0x7598f93cc4
	public Length ReadLength(Int32 index) { }
	// RVA: 0x697bf24 VA: 0x7598f93f24
	public TimeValue ReadTimeValue(Int32 index) { }
	// RVA: 0x697e7a8 VA: 0x7598f967a8
	public Translate ReadTranslate(Int32 index) { }
	// RVA: 0x697eb60 VA: 0x7598f96b60
	public TransformOrigin ReadTransformOrigin(Int32 index) { }
	// RVA: 0x697ee58 VA: 0x7598f96e58
	public Rotate ReadRotate(Int32 index) { }
	// RVA: 0x697f048 VA: 0x7598f97048
	public Scale ReadScale(Int32 index) { }
	// RVA: 0x697bdb8 VA: 0x7598f93db8
	public Single ReadFloat(Int32 index) { }
	// RVA: 0x697f344 VA: 0x7598f97344
	public Int32 ReadInt(Int32 index) { }
	// RVA: 0x697be20 VA: 0x7598f93e20
	public Color ReadColor(Int32 index) { }
	// RVA: 0x697f4bc VA: 0x7598f974bc
	public Int32 ReadEnum(StyleEnumType enumType, Int32 index) { }
	// RVA: 0x697f5b8 VA: 0x7598f975b8
	public FontDefinition ReadFontDefinition(Int32 index) { }
	// RVA: 0x697fae0 VA: 0x7598f97ae0
	public Font ReadFont(Int32 index) { }
	// RVA: 0x697fe24 VA: 0x7598f97e24
	public Background ReadBackground(Int32 index) { }
	// RVA: 0x69808e0 VA: 0x7598f988e0
	public Cursor ReadCursor(Int32 index) { }
	// RVA: 0x6980bb8 VA: 0x7598f98bb8
	public TextShadow ReadTextShadow(Int32 index) { }
	// RVA: 0x6980e2c VA: 0x7598f98e2c
	public Void ReadListEasingFunction(List`1 list, Int32 index) { }
	// RVA: 0x698101c VA: 0x7598f9901c
	public Void ReadListTimeValue(List`1 list, Int32 index) { }
	// RVA: 0x69811b0 VA: 0x7598f991b0
	public Void ReadListStylePropertyName(List`1 list, Int32 index) { }
	// RVA: 0x697de8c VA: 0x7598f95e8c
	private Void LoadProperties() { }
	// RVA: 0x697e38c VA: 0x7598f9638c
	private Void SetCurrentProperty() { }
	// RVA: 0x697ec94 VA: 0x7598f96c94
	public static TransformOrigin ReadTransformOrigin(Int32 valCount, StylePropertyValue val1, StylePropertyValue val2, StylePropertyValue zVvalue) { }
	// RVA: 0x6981388 VA: 0x7598f99388
	private static Length ReadTransformOriginEnum(StylePropertyValue value, out Boolean isVertical, out Boolean isHorizontal) { }
	// RVA: 0x697e8d8 VA: 0x7598f968d8
	public static Translate ReadTranslate(Int32 valCount, StylePropertyValue val1, StylePropertyValue val2, StylePropertyValue val3) { }
	// RVA: 0x697f148 VA: 0x7598f97148
	public static Scale ReadScale(Int32 valCount, StylePropertyValue val1, StylePropertyValue val2, StylePropertyValue val3) { }
	// RVA: 0x697ef7c VA: 0x7598f96f7c
	public static Rotate ReadRotate(Int32 valCount, StylePropertyValue val1, StylePropertyValue val2, StylePropertyValue val3, StylePropertyValue val4) { }
	// RVA: 0x69814e0 VA: 0x7598f994e0
	private static Int32 ReadEnum(StyleEnumType enumType, StylePropertyValue value) { }
	// RVA: 0x69815a8 VA: 0x7598f995a8
	public static Angle ReadAngle(StylePropertyValue value) { }
	// RVA: 0x6980090 VA: 0x7598f98090
	internal static Boolean TryGetImageSourceFromValue(StylePropertyValue propertyValue, Single dpiScaling, out ImageSource source) { }
	// RVA: 0x6981620 VA: 0x7598f99620
	public Void .ctor() { }
}
```