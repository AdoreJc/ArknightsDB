# YogaNode

**Namespace:** `UnityEngine.Yoga`


## Fields

- `YogaConfig _config`

- `WeakReference _parent`

- `MeasureFunction _measureFunction`

- `BaselineFunction _baselineFunction`

- `Object _data`


## Properties

- `Boolean IsDirty`

- `Boolean HasNewLayout`

- `Boolean IsMeasureDefined`

- `Boolean IsBaselineDefined`

- `YogaFlexDirection FlexDirection`

- `YogaJustify JustifyContent`

- `YogaDisplay Display`

- `YogaAlign AlignItems`

- `YogaAlign AlignSelf`

- `YogaAlign AlignContent`

- `YogaPositionType PositionType`

- `YogaWrap Wrap`

- `Single Flex`

- `Single FlexGrow`

- `Single FlexShrink`

- `YogaValue FlexBasis`

- `YogaValue Width`

- `YogaValue Height`

- `YogaValue MaxWidth`

- `YogaValue MaxHeight`

- `YogaValue MinWidth`

- `YogaValue MinHeight`

- `Single LayoutX`

- `Single LayoutY`

- `Single LayoutRight`

- `Single LayoutBottom`

- `Single LayoutWidth`

- `Single LayoutHeight`

- `YogaOverflow Overflow`

- `Int32 Count`

- `YogaValue Left`

- `YogaValue Top`

- `YogaValue Right`

- `YogaValue Bottom`

- `YogaValue MarginLeft`

- `YogaValue MarginTop`

- `YogaValue MarginRight`

- `YogaValue MarginBottom`

- `YogaValue PaddingLeft`

- `YogaValue PaddingTop`

- `YogaValue PaddingRight`

- `YogaValue PaddingBottom`

- `Single BorderLeftWidth`

- `Single BorderTopWidth`

- `Single BorderRightWidth`

- `Single BorderBottomWidth`

- `Single LayoutMarginLeft`

- `Single LayoutMarginTop`

- `Single LayoutMarginRight`

- `Single LayoutMarginBottom`

- `Single LayoutPaddingLeft`

- `Single LayoutPaddingTop`

- `Single LayoutPaddingRight`

- `Single LayoutPaddingBottom`

- `Single LayoutBorderLeft`

- `Single LayoutBorderTop`

- `Single LayoutBorderRight`

- `Single LayoutBorderBottom`


## Methods

- `Boolean get_IsDirty()`

- `Boolean get_HasNewLayout()`

- `Boolean get_IsMeasureDefined()`

- `Boolean get_IsBaselineDefined()`

- `Void CopyStyle(YogaNode)`

- `Void set_FlexDirection(YogaFlexDirection)`

- `Void set_JustifyContent(YogaJustify)`

- `Void set_Display(YogaDisplay)`

- `Void set_AlignItems(YogaAlign)`

- `Void set_AlignSelf(YogaAlign)`

- `Void set_AlignContent(YogaAlign)`

- `Void set_PositionType(YogaPositionType)`

- `Void set_Wrap(YogaWrap)`

- `Void set_Flex(Single)`

- `Void set_FlexGrow(Single)`

- `Void set_FlexShrink(Single)`

- `Void set_FlexBasis(YogaValue)`

- `Void set_Width(YogaValue)`

- `Void set_Height(YogaValue)`

- `Void set_MaxWidth(YogaValue)`

- `Void set_MaxHeight(YogaValue)`

- `Void set_MinWidth(YogaValue)`

- `Void set_MinHeight(YogaValue)`

- `Single get_LayoutX()`

- `Single get_LayoutY()`

- `Single get_LayoutRight()`

- `Single get_LayoutBottom()`

- `Single get_LayoutWidth()`

- `Single get_LayoutHeight()`

- `Void set_Overflow(YogaOverflow)`

- `Int32 get_Count()`

- `Void MarkLayoutSeen()`

- `Void Insert(Int32, YogaNode)`

- `Void RemoveAt(Int32)`

- `Void Clear()`

- `Void SetMeasureFunction(MeasureFunction)`

- `Void CalculateLayout(Single, Single)`

- `Void set_Left(YogaValue)`

- `Void set_Top(YogaValue)`

- `Void set_Right(YogaValue)`

- `Void set_Bottom(YogaValue)`

- `Void SetStylePosition(YogaEdge, YogaValue)`

- `Void set_MarginLeft(YogaValue)`

- `Void set_MarginTop(YogaValue)`

- `Void set_MarginRight(YogaValue)`

- `Void set_MarginBottom(YogaValue)`

- `Void SetStyleMargin(YogaEdge, YogaValue)`

- `Void set_PaddingLeft(YogaValue)`

- `Void set_PaddingTop(YogaValue)`

- `Void set_PaddingRight(YogaValue)`

- `Void set_PaddingBottom(YogaValue)`

- `Void SetStylePadding(YogaEdge, YogaValue)`

- `Void set_BorderLeftWidth(Single)`

- `Void set_BorderTopWidth(Single)`

- `Void set_BorderRightWidth(Single)`

- `Void set_BorderBottomWidth(Single)`

- `Single get_LayoutMarginLeft()`

- `Single get_LayoutMarginTop()`

- `Single get_LayoutMarginRight()`

- `Single get_LayoutMarginBottom()`

- `Single get_LayoutPaddingLeft()`

- `Single get_LayoutPaddingTop()`

- `Single get_LayoutPaddingRight()`

- `Single get_LayoutPaddingBottom()`

- `Single get_LayoutBorderLeft()`

- `Single get_LayoutBorderTop()`

- `Single get_LayoutBorderRight()`

- `Single get_LayoutBorderBottom()`


## Dump
```C#
// Dll : UnityEngine.UIElementsNativeModule.dll
// Namespace : UnityEngine.Yoga
internal class YogaNode : IEnumerable`1, IEnumerable
{
	internal IntPtr _ygNode; // 0x10
	private YogaConfig _config; // 0x18
	private WeakReference _parent; // 0x20
	private List`1 _children; // 0x28
	private MeasureFunction _measureFunction; // 0x30
	private BaselineFunction _baselineFunction; // 0x38
	private Object _data; // 0x40

	internal YogaConfig Config { set; }
	public Boolean IsDirty { get; }
	public Boolean HasNewLayout { get; }
	public Boolean IsMeasureDefined { get; }
	public Boolean IsBaselineDefined { get; }
	public YogaFlexDirection FlexDirection { set; }
	public YogaJustify JustifyContent { set; }
	public YogaDisplay Display { set; }
	public YogaAlign AlignItems { set; }
	public YogaAlign AlignSelf { set; }
	public YogaAlign AlignContent { set; }
	public YogaPositionType PositionType { set; }
	public YogaWrap Wrap { set; }
	public Single Flex { set; }
	public Single FlexGrow { set; }
	public Single FlexShrink { set; }
	public YogaValue FlexBasis { set; }
	public YogaValue Width { set; }
	public YogaValue Height { set; }
	public YogaValue MaxWidth { set; }
	public YogaValue MaxHeight { set; }
	public YogaValue MinWidth { set; }
	public YogaValue MinHeight { set; }
	public Single LayoutX { get; }
	public Single LayoutY { get; }
	public Single LayoutRight { get; }
	public Single LayoutBottom { get; }
	public Single LayoutWidth { get; }
	public Single LayoutHeight { get; }
	public YogaOverflow Overflow { set; }
	public Int32 Count { get; }
	public YogaValue Left { set; }
	public YogaValue Top { set; }
	public YogaValue Right { set; }
	public YogaValue Bottom { set; }
	public YogaValue MarginLeft { set; }
	public YogaValue MarginTop { set; }
	public YogaValue MarginRight { set; }
	public YogaValue MarginBottom { set; }
	public YogaValue PaddingLeft { set; }
	public YogaValue PaddingTop { set; }
	public YogaValue PaddingRight { set; }
	public YogaValue PaddingBottom { set; }
	public Single BorderLeftWidth { set; }
	public Single BorderTopWidth { set; }
	public Single BorderRightWidth { set; }
	public Single BorderBottomWidth { set; }
	public Single LayoutMarginLeft { get; }
	public Single LayoutMarginTop { get; }
	public Single LayoutMarginRight { get; }
	public Single LayoutMarginBottom { get; }
	public Single LayoutPaddingLeft { get; }
	public Single LayoutPaddingTop { get; }
	public Single LayoutPaddingRight { get; }
	public Single LayoutPaddingBottom { get; }
	public Single LayoutBorderLeft { get; }
	public Single LayoutBorderTop { get; }
	public Single LayoutBorderRight { get; }
	public Single LayoutBorderBottom { get; }

	// RVA: 0x6a40a44 VA: 0x7599058a44
	public Void .ctor(YogaConfig config) { }
	// RVA: 0x6a40b88 VA: 0x7599058b88
	protected override Void Finalize() { }
	// RVA: 0x6a40c20 VA: 0x7599058c20
	internal Void set_Config(YogaConfig value) { }
	// RVA: 0x6a40ce0 VA: 0x7599058ce0
	public Boolean get_IsDirty() { }
	// RVA: 0x6a40d1c VA: 0x7599058d1c
	public virtual Void MarkDirty() { }
	// RVA: 0x6a40d58 VA: 0x7599058d58
	public Boolean get_HasNewLayout() { }
	// RVA: 0x6a40d94 VA: 0x7599058d94
	public Boolean get_IsMeasureDefined() { }
	// RVA: 0x6a40da4 VA: 0x7599058da4
	public Boolean get_IsBaselineDefined() { }
	// RVA: 0x6a40db4 VA: 0x7599058db4
	public Void CopyStyle(YogaNode srcNode) { }
	// RVA: 0x6a40e00 VA: 0x7599058e00
	public Void set_FlexDirection(YogaFlexDirection value) { }
	// RVA: 0x6a40e44 VA: 0x7599058e44
	public Void set_JustifyContent(YogaJustify value) { }
	// RVA: 0x6a40e88 VA: 0x7599058e88
	public Void set_Display(YogaDisplay value) { }
	// RVA: 0x6a40ecc VA: 0x7599058ecc
	public Void set_AlignItems(YogaAlign value) { }
	// RVA: 0x6a40f10 VA: 0x7599058f10
	public Void set_AlignSelf(YogaAlign value) { }
	// RVA: 0x6a40f54 VA: 0x7599058f54
	public Void set_AlignContent(YogaAlign value) { }
	// RVA: 0x6a40f98 VA: 0x7599058f98
	public Void set_PositionType(YogaPositionType value) { }
	// RVA: 0x6a40fdc VA: 0x7599058fdc
	public Void set_Wrap(YogaWrap value) { }
	// RVA: 0x6a41020 VA: 0x7599059020
	public Void set_Flex(Single value) { }
	// RVA: 0x6a4106c VA: 0x759905906c
	public Void set_FlexGrow(Single value) { }
	// RVA: 0x6a410b8 VA: 0x75990590b8
	public Void set_FlexShrink(Single value) { }
	// RVA: 0x6a41104 VA: 0x7599059104
	public Void set_FlexBasis(YogaValue value) { }
	// RVA: 0x6a411d0 VA: 0x75990591d0
	public Void set_Width(YogaValue value) { }
	// RVA: 0x6a4128c VA: 0x759905928c
	public Void set_Height(YogaValue value) { }
	// RVA: 0x6a41348 VA: 0x7599059348
	public Void set_MaxWidth(YogaValue value) { }
	// RVA: 0x6a413c4 VA: 0x75990593c4
	public Void set_MaxHeight(YogaValue value) { }
	// RVA: 0x6a41440 VA: 0x7599059440
	public Void set_MinWidth(YogaValue value) { }
	// RVA: 0x6a414bc VA: 0x75990594bc
	public Void set_MinHeight(YogaValue value) { }
	// RVA: 0x6a41538 VA: 0x7599059538
	public Single get_LayoutX() { }
	// RVA: 0x6a41574 VA: 0x7599059574
	public Single get_LayoutY() { }
	// RVA: 0x6a415b0 VA: 0x75990595b0
	public Single get_LayoutRight() { }
	// RVA: 0x6a415ec VA: 0x75990595ec
	public Single get_LayoutBottom() { }
	// RVA: 0x6a41628 VA: 0x7599059628
	public Single get_LayoutWidth() { }
	// RVA: 0x6a41664 VA: 0x7599059664
	public Single get_LayoutHeight() { }
	// RVA: 0x6a416a0 VA: 0x75990596a0
	public Void set_Overflow(YogaOverflow value) { }
	// RVA: 0x6a416e4 VA: 0x75990596e4
	public Int32 get_Count() { }
	// RVA: 0x6a41730 VA: 0x7599059730
	public Void MarkLayoutSeen() { }
	// RVA: 0x6a41770 VA: 0x7599059770
	public Void Insert(Int32 index, YogaNode node) { }
	// RVA: 0x6a418b4 VA: 0x75990598b4
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x6a41984 VA: 0x7599059984
	public Void Clear() { }
	// RVA: 0x6a419e8 VA: 0x75990599e8
	public Void SetMeasureFunction(MeasureFunction measureFunction) { }
	// RVA: 0x6a41ac8 VA: 0x7599059ac8
	public Void CalculateLayout(Single width, Single height) { }
	// RVA: 0x6a3fb64 VA: 0x7599057b64
	public static YogaSize MeasureInternal(YogaNode node, Single width, YogaMeasureMode widthMode, Single height, YogaMeasureMode heightMode) { }
	// RVA: 0x6a3fc2c VA: 0x7599057c2c
	public static Single BaselineInternal(YogaNode node, Single width, Single height) { }
	// RVA: 0x6a41b4c VA: 0x7599059b4c
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x6a41c78 VA: 0x7599059c78
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x6a41da4 VA: 0x7599059da4
	public Void set_Left(YogaValue value) { }
	// RVA: 0x6a41e34 VA: 0x7599059e34
	public Void set_Top(YogaValue value) { }
	// RVA: 0x6a41e40 VA: 0x7599059e40
	public Void set_Right(YogaValue value) { }
	// RVA: 0x6a41e4c VA: 0x7599059e4c
	public Void set_Bottom(YogaValue value) { }
	// RVA: 0x6a41db0 VA: 0x7599059db0
	private Void SetStylePosition(YogaEdge edge, YogaValue value) { }
	// RVA: 0x6a41e58 VA: 0x7599059e58
	public Void set_MarginLeft(YogaValue value) { }
	// RVA: 0x6a41f2c VA: 0x7599059f2c
	public Void set_MarginTop(YogaValue value) { }
	// RVA: 0x6a41f38 VA: 0x7599059f38
	public Void set_MarginRight(YogaValue value) { }
	// RVA: 0x6a41f44 VA: 0x7599059f44
	public Void set_MarginBottom(YogaValue value) { }
	// RVA: 0x6a41e64 VA: 0x7599059e64
	private Void SetStyleMargin(YogaEdge edge, YogaValue value) { }
	// RVA: 0x6a41f50 VA: 0x7599059f50
	public Void set_PaddingLeft(YogaValue value) { }
	// RVA: 0x6a41fe0 VA: 0x7599059fe0
	public Void set_PaddingTop(YogaValue value) { }
	// RVA: 0x6a41fec VA: 0x7599059fec
	public Void set_PaddingRight(YogaValue value) { }
	// RVA: 0x6a41ff8 VA: 0x7599059ff8
	public Void set_PaddingBottom(YogaValue value) { }
	// RVA: 0x6a41f5c VA: 0x7599059f5c
	private Void SetStylePadding(YogaEdge edge, YogaValue value) { }
	// RVA: 0x6a42004 VA: 0x759905a004
	public Void set_BorderLeftWidth(Single value) { }
	// RVA: 0x6a42054 VA: 0x759905a054
	public Void set_BorderTopWidth(Single value) { }
	// RVA: 0x6a420a4 VA: 0x759905a0a4
	public Void set_BorderRightWidth(Single value) { }
	// RVA: 0x6a420f4 VA: 0x759905a0f4
	public Void set_BorderBottomWidth(Single value) { }
	// RVA: 0x6a42144 VA: 0x759905a144
	public Single get_LayoutMarginLeft() { }
	// RVA: 0x6a42184 VA: 0x759905a184
	public Single get_LayoutMarginTop() { }
	// RVA: 0x6a421c4 VA: 0x759905a1c4
	public Single get_LayoutMarginRight() { }
	// RVA: 0x6a42204 VA: 0x759905a204
	public Single get_LayoutMarginBottom() { }
	// RVA: 0x6a42244 VA: 0x759905a244
	public Single get_LayoutPaddingLeft() { }
	// RVA: 0x6a42284 VA: 0x759905a284
	public Single get_LayoutPaddingTop() { }
	// RVA: 0x6a422c4 VA: 0x759905a2c4
	public Single get_LayoutPaddingRight() { }
	// RVA: 0x6a42304 VA: 0x759905a304
	public Single get_LayoutPaddingBottom() { }
	// RVA: 0x6a42344 VA: 0x759905a344
	public Single get_LayoutBorderLeft() { }
	// RVA: 0x6a42384 VA: 0x759905a384
	public Single get_LayoutBorderTop() { }
	// RVA: 0x6a423c4 VA: 0x759905a3c4
	public Single get_LayoutBorderRight() { }
	// RVA: 0x6a42404 VA: 0x759905a404
	public Single get_LayoutBorderBottom() { }
}
```