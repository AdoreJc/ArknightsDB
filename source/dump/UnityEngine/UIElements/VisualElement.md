# VisualElement

**Namespace:** `UnityEngine.UIElements`


## Fields

- `String m_Name`

- `VisualElementFlags m_Flags`

- `String m_ViewDataKey`

- `RenderHints m_RenderHints`

- `Rect m_Layout`

- `Rect m_BoundingBox`

- `Rect m_WorldBoundingBox`

- `Matrix4x4 m_WorldTransformCache`

- `Matrix4x4 m_WorldTransformInverseCache`

- `Rect m_WorldClip`

- `Rect m_WorldClipMinusGroup`

- `Boolean m_WorldClipIsInfinite`

- `PseudoStates m_PseudoStates`

- `Int32 <containedPointerIds>k__BackingField`

- `PickingMode m_PickingMode`

- `YogaNode <yogaNode>k__BackingField`

- `Boolean <enabledSelf>k__BackingField`

- `ProfilerMarker k_GenerateVisualContentMarker`

- `RenderTargetMode m_SubRenderTargetMode`

- `Material m_defaultMaterial`

- `Hierarchy <hierarchy>k__BackingField`

- `Boolean <isRootVisualContainer>k__BackingField`

- `Boolean <cacheAsBitmap>k__BackingField`

- `VisualElement m_PhysicalParent`

- `VisualElement m_LogicalParent`

- `BaseVisualElementPanel <elementPanel>k__BackingField`

- `VisualTreeAsset m_VisualTreeAssetSource`

- `TypeData m_TypeData`


## Properties

- `String viewDataKey`

- `Object userData`

- `UsageHints usageHints`

- `ITransform transform`

- `Rect layout`

- `Rect contentRect`

- `Rect paddingRect`

- `Rect boundingBoxInParentSpace`

- `Rect worldBound`

- `Rect localBound`

- `Matrix4x4 worldTransform`

- `PickingMode pickingMode`

- `String name`

- `Boolean isParentEnabledInHierarchy`

- `Boolean enabledInHierarchy`

- `Boolean enabledSelf`

- `Boolean visible`

- `IExperimentalFeatures experimental`

- `Hierarchy hierarchy`

- `VisualElement parent`

- `IPanel panel`

- `VisualElement Item`

- `Int32 childCount`

- `Vector3 positionWithLayout`

- `IVisualElementScheduler schedule`

- `IStyle style`

- `ICustomStyle customStyle`

- `VisualElementStyleSheetSet styleSheets`

- `String tooltip`

- `TypeData typeData`

- `IResolvedStyle resolvedStyle`


## Methods

- `IStylePropertyAnimationSystem GetStylePropertyAnimationSystem()`

- `String get_viewDataKey()`

- `Void set_viewDataKey(String)`

- `Void set_enableViewDataPersistence(Boolean)`

- `Object get_userData()`

- `Void set_userData(Object)`

- `UsageHints get_usageHints()`

- `Void set_usageHints(UsageHints)`

- `ITransform get_transform()`

- `Void set_isLayoutManual(Boolean)`

- `Rect get_layout()`

- `Rect get_contentRect()`

- `Rect get_paddingRect()`

- `Rect get_boundingBoxInParentSpace()`

- `Rect get_worldBound()`

- `Rect get_localBound()`

- `Matrix4x4 get_worldTransform()`

- `Void UpdateWorldClip()`

- `Rect CombineClipRects(Rect, Rect)`

- `Rect SubstractBorderPadding(Rect)`

- `Void set_containedPointerIds(Int32)`

- `Void UpdateHoverPseudoState()`

- `PickingMode get_pickingMode()`

- `Void set_pickingMode(PickingMode)`

- `String get_name()`

- `Void set_name(String)`

- `Void set_yogaNode(YogaNode)`

- `Void ChangeIMGUIContainerCount(Int32)`

- `Void SetTooltip(TooltipEvent)`

- `Void WillChangePanel(BaseVisualElementPanel)`

- `Void HasChangedPanel(BaseVisualElementPanel)`

- `Boolean SetEnabledFromHierarchyPrivate(Boolean)`

- `Boolean get_isParentEnabledInHierarchy()`

- `Boolean get_enabledInHierarchy()`

- `Boolean get_enabledSelf()`

- `Void set_enabledSelf(Boolean)`

- `Void SetEnabled(Boolean)`

- `Void PropagateEnabledToChildren(Boolean)`

- `Boolean get_visible()`

- `Void set_visible(Boolean)`

- `Void MarkDirtyRepaint()`

- `Void set_generateVisualContent(Action`1)`

- `Void AssignMeasureFunction()`

- `Void RemoveMeasureFunction()`

- `Void FinalizeLayout()`

- `Void AddToClassList(String)`

- `Void RemoveFromClassList(String)`

- `Void EnableInClassList(String, Boolean)`

- `Boolean ClassListContains(String)`

- `Boolean TryGetPropertyInternal(PropertyName, out)`

- `Void SetPropertyInternal(PropertyName, Object)`

- `Void UpdateCursorStyle(Int64)`

- `VisualElementAnimationSystem GetAnimationSystem()`

- `Void UnregisterRunningAnimations()`

- `Void RegisterRunningAnimations()`

- `StyleValues ReadCurrentValues(VisualElement, StyleValues)`

- `IExperimentalFeatures get_experimental()`

- `Hierarchy get_hierarchy()`

- `Void set_hierarchy(Hierarchy)`

- `VisualElement get_parent()`

- `Void set_elementPanel(BaseVisualElementPanel)`

- `IPanel get_panel()`

- `Void Add(VisualElement)`

- `Void Insert(Int32, VisualElement)`

- `Void Clear()`

- `VisualElement ElementAt(Int32)`

- `VisualElement get_Item(Int32)`

- `Int32 get_childCount()`

- `Int32 IndexOf(VisualElement)`

- `Void BringToFront()`

- `Void SendToBack()`

- `Void PlaceBehind(VisualElement)`

- `Void RemoveFromHierarchy()`

- `T GetFirstOfType()`

- `T GetFirstAncestorOfType()`

- `Boolean Contains(VisualElement)`

- `Void GatherAllChildren(List`1)`

- `VisualElement FindCommonAncestor(VisualElement)`

- `Vector3 get_positionWithLayout()`

- `Void TransformAlignedRectToParentSpace(ref)`

- `IVisualElementScheduler get_schedule()`

- `IStyle get_style()`

- `ICustomStyle get_customStyle()`

- `VisualElementStyleSheetSet get_styleSheets()`

- `StyleFloat ResolveLengthValue(Length, Boolean)`

- `Vector3 ResolveTranslate()`

- `Vector3 ResolveTransformOrigin()`

- `Quaternion ResolveRotation()`

- `Vector3 ResolveScale()`

- `String get_tooltip()`

- `Void set_tooltip(String)`

- `TypeData get_typeData()`

- `IResolvedStyle get_resolvedStyle()`

- `YogaSize <AssignMeasureFunction>b__254_0(YogaNode, Single, YogaMeasureMode, Single, YogaMeasureMode)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class VisualElement : Focusable, IStylePropertyAnimations, ITransform, ITransitionAnimations, IExperimentalFeatures, IVisualElementScheduler, IResolvedStyle
{
	private Int32 <UnityEngine.UIElements.IStylePropertyAnimations.runningAnimationCount>k__BackingField; // 0x24
	private Int32 <UnityEngine.UIElements.IStylePropertyAnimations.completedAnimationCount>k__BackingField; // 0x28
	private static UInt32 s_NextId; // 0x0
	private static List`1 s_EmptyClassList; // 0x8
	internal static readonly PropertyName userDataPropertyKey; // 0x10
	public static readonly String disabledUssClassName; // 0x18
	private String m_Name; // 0x30
	private List`1 m_ClassList; // 0x38
	private List`1 m_PropertyBag; // 0x40
	private VisualElementFlags m_Flags; // 0x48
	private String m_ViewDataKey; // 0x50
	private RenderHints m_RenderHints; // 0x58
	internal Rect lastLayout; // 0x5c
	internal Rect lastPseudoPadding; // 0x6c
	internal RenderChainVEData renderChainData; // 0x80
	private Rect m_Layout; // 0x1d8
	private Rect m_BoundingBox; // 0x1e8
	private Rect m_WorldBoundingBox; // 0x1f8
	private Matrix4x4 m_WorldTransformCache; // 0x208
	private Matrix4x4 m_WorldTransformInverseCache; // 0x248
	private Rect m_WorldClip; // 0x288
	private Rect m_WorldClipMinusGroup; // 0x298
	private Boolean m_WorldClipIsInfinite; // 0x2a8
	internal static readonly Rect s_InfiniteRect; // 0x20
	internal PseudoStates triggerPseudoMask; // 0x2ac
	internal PseudoStates dependencyPseudoMask; // 0x2b0
	private PseudoStates m_PseudoStates; // 0x2b4
	private Int32 <containedPointerIds>k__BackingField; // 0x2b8
	private PickingMode m_PickingMode; // 0x2bc
	private YogaNode <yogaNode>k__BackingField; // 0x2c0
	internal ComputedStyle m_Style; // 0x2c8
	internal StyleVariableContext variableContext; // 0x320
	internal Int32 inheritedStylesHash; // 0x328
	internal readonly UInt32 controlid; // 0x32c
	internal Int32 imguiContainerDescendantCount; // 0x330
	private Boolean <enabledSelf>k__BackingField; // 0x334
	private Action`1 <generateVisualContent>k__BackingField; // 0x338
	private ProfilerMarker k_GenerateVisualContentMarker; // 0x340
	private RenderTargetMode m_SubRenderTargetMode; // 0x348
	private static Material s_runtimeMaterial; // 0x30
	private Material m_defaultMaterial; // 0x350
	private List`1 m_RunningAnimations; // 0x358
	internal const String k_RootVisualContainerName; // 0x0
	private Hierarchy <hierarchy>k__BackingField; // 0x360
	private Boolean <isRootVisualContainer>k__BackingField; // 0x368
	private Boolean <cacheAsBitmap>k__BackingField; // 0x369
	private VisualElement m_PhysicalParent; // 0x370
	private VisualElement m_LogicalParent; // 0x378
	private static readonly List`1 s_EmptyList; // 0x38
	private List`1 m_Children; // 0x380
	private BaseVisualElementPanel <elementPanel>k__BackingField; // 0x388
	private VisualTreeAsset m_VisualTreeAssetSource; // 0x390
	internal static CustomStyleAccess s_CustomStyleAccess; // 0x40
	internal InlineStyleAccess inlineStyleAccess; // 0x398
	internal List`1 styleSheetList; // 0x3a0
	private static readonly Regex s_InternalStyleSheetPath; // 0x48
	internal static readonly PropertyName tooltipPropertyKey; // 0x50
	private static readonly Dictionary`2 s_TypeData; // 0x58
	private TypeData m_TypeData; // 0x3a8

	internal Boolean hasRunningAnimations { get; }
	internal Boolean hasCompletedAnimations { get; }
	private Int32 UnityEngine.UIElements.IStylePropertyAnimations.runningAnimationCount { get; set; }
	private Int32 UnityEngine.UIElements.IStylePropertyAnimations.completedAnimationCount { get; set; }
	internal IStylePropertyAnimations styleAnimation { get; }
	internal Boolean isCompositeRoot { get; set; }
	internal Boolean isHierarchyDisplayed { get; set; }
	public String viewDataKey { get; set; }
	internal Boolean enableViewDataPersistence { get; set; }
	public Object userData { get; set; }
	public override Boolean canGrabFocus { get; }
	public override FocusController focusController { get; }
	public UsageHints usageHints { get; set; }
	internal RenderHints renderHints { get; set; }
	public ITransform transform { get; }
	private Vector3 UnityEngine.UIElements.ITransform.position { get; set; }
	private Vector3 UnityEngine.UIElements.ITransform.scale { get; }
	internal Boolean isLayoutManual { get; set; }
	internal Single scaledPixelsPerPoint { get; }
	public Rect layout { get; set; }
	public Rect contentRect { get; }
	protected Rect paddingRect { get; }
	internal Boolean isBoundingBoxDirty { get; set; }
	internal Boolean isWorldBoundingBoxDirty { get; set; }
	internal Rect boundingBox { get; }
	internal Rect worldBoundingBox { get; }
	private Rect boundingBoxInParentSpace { get; }
	public Rect worldBound { get; }
	public Rect localBound { get; }
	internal Rect rect { get; }
	internal Boolean isWorldTransformDirty { get; set; }
	internal Boolean isWorldTransformInverseDirty { get; set; }
	public Matrix4x4 worldTransform { get; }
	internal Matrix4x4 worldTransformRef { get; }
	internal Matrix4x4 worldTransformInverse { get; }
	internal Boolean isWorldClipDirty { get; set; }
	internal Rect worldClip { get; }
	internal Rect worldClipMinusGroup { get; }
	internal Boolean worldClipIsInfinite { get; }
	internal PseudoStates pseudoStates { get; set; }
	internal Int32 containedPointerIds { get; set; }
	public PickingMode pickingMode { get; set; }
	public String name { get; set; }
	internal List`1 classList { get; }
	internal String fullTypeName { get; }
	internal String typeName { get; }
	internal YogaNode yogaNode { get; set; }
	internal ComputedStyle computedStyle { get; }
	internal Boolean hasInlineStyle { get; }
	internal Boolean styleInitialized { get; set; }
	private Boolean isParentEnabledInHierarchy { get; }
	public Boolean enabledInHierarchy { get; }
	public Boolean enabledSelf { get; set; }
	public Boolean visible { get; set; }
	public Action`1 generateVisualContent { get; set; }
	internal Boolean requireMeasureFunction { get; set; }
	internal RenderTargetMode subRenderTargetMode { get; }
	internal Material defaultMaterial { get; }
	public IExperimentalFeatures experimental { get; }
	private ITransitionAnimations UnityEngine.UIElements.IExperimentalFeatures.animation { get; }
	public Hierarchy hierarchy { get; set; }
	internal Boolean isRootVisualContainer { get; set; }
	internal Boolean disableClipping { get; set; }
	public VisualElement parent { get; }
	internal BaseVisualElementPanel elementPanel { get; set; }
	public IPanel panel { get; }
	public virtual VisualElement contentContainer { get; }
	internal VisualTreeAsset visualTreeAssetSource { set; }
	public VisualElement Item { get; }
	public Int32 childCount { get; }
	private Vector3 positionWithLayout { get; }
	internal Boolean hasDefaultRotationAndScale { get; }
	public IVisualElementScheduler schedule { get; }
	public IStyle style { get; }
	public ICustomStyle customStyle { get; }
	public VisualElementStyleSheetSet styleSheets { get; }
	public String tooltip { get; set; }
	private TypeData typeData { get; }
	public IResolvedStyle resolvedStyle { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.backgroundColor { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.borderBottomColor { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderBottomLeftRadius { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderBottomRightRadius { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderBottomWidth { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.borderLeftColor { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderLeftWidth { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.borderRightColor { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderRightWidth { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.borderTopColor { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderTopLeftRadius { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderTopRightRadius { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.borderTopWidth { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.bottom { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.color { get; }
	private DisplayStyle UnityEngine.UIElements.IResolvedStyle.display { get; }
	private FlexDirection UnityEngine.UIElements.IResolvedStyle.flexDirection { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.flexGrow { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.flexShrink { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.height { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.left { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.marginBottom { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.marginLeft { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.marginRight { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.marginTop { get; }
	private StyleFloat UnityEngine.UIElements.IResolvedStyle.minHeight { get; }
	private StyleFloat UnityEngine.UIElements.IResolvedStyle.minWidth { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.opacity { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.paddingBottom { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.paddingLeft { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.paddingRight { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.paddingTop { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.right { get; }
	private Scale UnityEngine.UIElements.IResolvedStyle.scale { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.top { get; }
	private Vector3 UnityEngine.UIElements.IResolvedStyle.transformOrigin { get; }
	private Vector3 UnityEngine.UIElements.IResolvedStyle.translate { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.unityBackgroundImageTintColor { get; }
	private Int32 UnityEngine.UIElements.IResolvedStyle.unitySliceLeft { get; }
	private Int32 UnityEngine.UIElements.IResolvedStyle.unitySliceRight { get; }
	private Color UnityEngine.UIElements.IResolvedStyle.unityTextOutlineColor { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.unityTextOutlineWidth { get; }
	private Visibility UnityEngine.UIElements.IResolvedStyle.visibility { get; }
	private WhiteSpace UnityEngine.UIElements.IResolvedStyle.whiteSpace { get; }
	private Single UnityEngine.UIElements.IResolvedStyle.width { get; }

	// RVA: 0x69443a4 VA: 0x7598f5c3a4
	internal Boolean get_hasRunningAnimations() { }
	// RVA: 0x6944454 VA: 0x7598f5c454
	internal Boolean get_hasCompletedAnimations() { }
	// RVA: 0x6944500 VA: 0x7598f5c500
	private Int32 UnityEngine.UIElements.IStylePropertyAnimations.get_runningAnimationCount() { }
	// RVA: 0x6944508 VA: 0x7598f5c508
	private Void UnityEngine.UIElements.IStylePropertyAnimations.set_runningAnimationCount(Int32 value) { }
	// RVA: 0x6944510 VA: 0x7598f5c510
	private Int32 UnityEngine.UIElements.IStylePropertyAnimations.get_completedAnimationCount() { }
	// RVA: 0x6944518 VA: 0x7598f5c518
	private Void UnityEngine.UIElements.IStylePropertyAnimations.set_completedAnimationCount(Int32 value) { }
	// RVA: 0x6944520 VA: 0x7598f5c520
	private IStylePropertyAnimationSystem GetStylePropertyAnimationSystem() { }
	// RVA: 0x6944450 VA: 0x7598f5c450
	internal IStylePropertyAnimations get_styleAnimation() { }
	// RVA: 0x694453c VA: 0x7598f5c53c
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Single from, Single to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6944640 VA: 0x7598f5c640
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Int32 from, Int32 to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x694475c VA: 0x7598f5c75c
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Length from, Length to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6944878 VA: 0x7598f5c878
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Color from, Color to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69449c8 VA: 0x7598f5c9c8
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.StartEnum(StylePropertyId id, Int32 from, Int32 to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6944ae4 VA: 0x7598f5cae4
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Background from, Background to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6944c3c VA: 0x7598f5cc3c
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, FontDefinition from, FontDefinition to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6944d6c VA: 0x7598f5cd6c
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Font from, Font to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6944e88 VA: 0x7598f5ce88
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, TextShadow from, TextShadow to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6945014 VA: 0x7598f5d014
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Scale from, Scale to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6945144 VA: 0x7598f5d144
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Translate from, Translate to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69452cc VA: 0x7598f5d2cc
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, Rotate from, Rotate to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x6945454 VA: 0x7598f5d454
	private Boolean UnityEngine.UIElements.IStylePropertyAnimations.Start(StylePropertyId id, TransformOrigin from, TransformOrigin to, Int32 durationMs, Int32 delayMs, Func`2 easingCurve) { }
	// RVA: 0x69455dc VA: 0x7598f5d5dc
	private Void UnityEngine.UIElements.IStylePropertyAnimations.CancelAnimation(StylePropertyId id) { }
	// RVA: 0x69456ac VA: 0x7598f5d6ac
	private Void UnityEngine.UIElements.IStylePropertyAnimations.CancelAllAnimations() { }
	// RVA: 0x694578c VA: 0x7598f5d78c
	private Void UnityEngine.UIElements.IStylePropertyAnimations.UpdateAnimation(StylePropertyId id) { }
	// RVA: 0x6945854 VA: 0x7598f5d854
	private Void UnityEngine.UIElements.IStylePropertyAnimations.GetAllAnimations(List`1 outPropertyIds) { }
	// RVA: 0x6945940 VA: 0x7598f5d940
	internal Boolean TryConvertLengthUnits(StylePropertyId id, ref Length from, ref Length to, Int32 subPropertyIndex) { }
	// RVA: 0x6945fb4 VA: 0x7598f5dfb4
	internal Boolean TryConvertTransformOriginUnits(ref TransformOrigin from, ref TransformOrigin to) { }
	// RVA: 0x6946058 VA: 0x7598f5e058
	internal Boolean TryConvertTranslateUnits(ref Translate from, ref Translate to) { }
	// RVA: 0x6945c60 VA: 0x7598f5dc60
	private Nullable`1 GetParentSizeForLengthConversion(StylePropertyId id, Int32 subPropertyIndex) { }
	// RVA: 0x694611c VA: 0x7598f5e11c
	internal Boolean get_isCompositeRoot() { }
	// RVA: 0x6946128 VA: 0x7598f5e128
	internal Void set_isCompositeRoot(Boolean value) { }
	// RVA: 0x6946154 VA: 0x7598f5e154
	internal Boolean get_isHierarchyDisplayed() { }
	// RVA: 0x6946160 VA: 0x7598f5e160
	internal Void set_isHierarchyDisplayed(Boolean value) { }
	// RVA: 0x694618c VA: 0x7598f5e18c
	public String get_viewDataKey() { }
	// RVA: 0x6946194 VA: 0x7598f5e194
	public Void set_viewDataKey(String value) { }
	// RVA: 0x6946234 VA: 0x7598f5e234
	internal Boolean get_enableViewDataPersistence() { }
	// RVA: 0x6946240 VA: 0x7598f5e240
	private Void set_enableViewDataPersistence(Boolean value) { }
	// RVA: 0x694626c VA: 0x7598f5e26c
	public Object get_userData() { }
	// RVA: 0x69463e0 VA: 0x7598f5e3e0
	public Void set_userData(Object value) { }
	// RVA: 0x694670c VA: 0x7598f5e70c
	public override Boolean get_canGrabFocus() { }
	// RVA: 0x69468e0 VA: 0x7598f5e8e0
	public override FocusController get_focusController() { }
	// RVA: 0x6946998 VA: 0x7598f5e998
	public UsageHints get_usageHints() { }
	// RVA: 0x69469c4 VA: 0x7598f5e9c4
	public Void set_usageHints(UsageHints value) { }
	// RVA: 0x69469bc VA: 0x7598f5e9bc
	internal RenderHints get_renderHints() { }
	// RVA: 0x6946a48 VA: 0x7598f5ea48
	internal Void set_renderHints(RenderHints value) { }
	// RVA: 0x6946a94 VA: 0x7598f5ea94
	internal Void MarkRenderHintsClean() { }
	// RVA: 0x6946aa4 VA: 0x7598f5eaa4
	public ITransform get_transform() { }
	// RVA: 0x6946aa8 VA: 0x7598f5eaa8
	private Vector3 UnityEngine.UIElements.ITransform.get_position() { }
	// RVA: 0x6946b48 VA: 0x7598f5eb48
	private Void UnityEngine.UIElements.ITransform.set_position(Vector3 value) { }
	// RVA: 0x6946d34 VA: 0x7598f5ed34
	private Vector3 UnityEngine.UIElements.ITransform.get_scale() { }
	// RVA: 0x6946de8 VA: 0x7598f5ede8
	internal Boolean get_isLayoutManual() { }
	// RVA: 0x6946df4 VA: 0x7598f5edf4
	private Void set_isLayoutManual(Boolean value) { }
	// RVA: 0x6946e20 VA: 0x7598f5ee20
	internal Single get_scaledPixelsPerPoint() { }
	// RVA: 0x6946e34 VA: 0x7598f5ee34
	public Rect get_layout() { }
	// RVA: 0x6946edc VA: 0x7598f5eedc
	internal Void set_layout(Rect value) { }
	// RVA: 0x69477bc VA: 0x7598f5f7bc
	internal Void ClearManualLayout() { }
	// RVA: 0x69440fc VA: 0x7598f5c0fc
	public Rect get_contentRect() { }
	// RVA: 0x6947d80 VA: 0x7598f5fd80
	protected Rect get_paddingRect() { }
	// RVA: 0x6947fdc VA: 0x7598f5ffdc
	internal Boolean get_isBoundingBoxDirty() { }
	// RVA: 0x6947fe8 VA: 0x7598f5ffe8
	internal Void set_isBoundingBoxDirty(Boolean value) { }
	// RVA: 0x6948014 VA: 0x7598f60014
	internal Boolean get_isWorldBoundingBoxDirty() { }
	// RVA: 0x6948020 VA: 0x7598f60020
	internal Void set_isWorldBoundingBoxDirty(Boolean value) { }
	// RVA: 0x694804c VA: 0x7598f6004c
	internal Rect get_boundingBox() { }
	// RVA: 0x6948434 VA: 0x7598f60434
	internal Rect get_worldBoundingBox() { }
	// RVA: 0x6948570 VA: 0x7598f60570
	private Rect get_boundingBoxInParentSpace() { }
	// RVA: 0x6948088 VA: 0x7598f60088
	internal Void UpdateBoundingBox() { }
	// RVA: 0x6948474 VA: 0x7598f60474
	internal Void UpdateWorldBoundingBox() { }
	// RVA: 0x6948754 VA: 0x7598f60754
	public Rect get_worldBound() { }
	// RVA: 0x6948824 VA: 0x7598f60824
	public Rect get_localBound() { }
	// RVA: 0x6947f70 VA: 0x7598f5ff70
	internal Rect get_rect() { }
	// RVA: 0x69489b8 VA: 0x7598f609b8
	internal Boolean get_isWorldTransformDirty() { }
	// RVA: 0x69489c4 VA: 0x7598f609c4
	internal Void set_isWorldTransformDirty(Boolean value) { }
	// RVA: 0x69489f0 VA: 0x7598f609f0
	internal Boolean get_isWorldTransformInverseDirty() { }
	// RVA: 0x69489fc VA: 0x7598f609fc
	internal Void set_isWorldTransformInverseDirty(Boolean value) { }
	// RVA: 0x6948a28 VA: 0x7598f60a28
	public Matrix4x4 get_worldTransform() { }
	// RVA: 0x6948730 VA: 0x7598f60730
	internal ref Matrix4x4 get_worldTransformRef() { }
	// RVA: 0x6948d0c VA: 0x7598f60d0c
	internal ref Matrix4x4 get_worldTransformInverse() { }
	// RVA: 0x6948a68 VA: 0x7598f60a68
	internal Void UpdateWorldTransform() { }
	// RVA: 0x6948d34 VA: 0x7598f60d34
	internal Void UpdateWorldTransformInverse() { }
	// RVA: 0x6949160 VA: 0x7598f61160
	internal Boolean get_isWorldClipDirty() { }
	// RVA: 0x694916c VA: 0x7598f6116c
	internal Void set_isWorldClipDirty(Boolean value) { }
	// RVA: 0x6949198 VA: 0x7598f61198
	internal Rect get_worldClip() { }
	// RVA: 0x6949454 VA: 0x7598f61454
	internal Rect get_worldClipMinusGroup() { }
	// RVA: 0x6949490 VA: 0x7598f61490
	internal Boolean get_worldClipIsInfinite() { }
	// RVA: 0x69494c0 VA: 0x7598f614c0
	internal Void EnsureWorldTransformAndClipUpToDate() { }
	// RVA: 0x69491d4 VA: 0x7598f611d4
	private Void UpdateWorldClip() { }
	// RVA: 0x6949b38 VA: 0x7598f61b38
	private Rect CombineClipRects(Rect rect, Rect parentRect) { }
	// RVA: 0x69494fc VA: 0x7598f614fc
	private Rect SubstractBorderPadding(Rect worldRect) { }
	// RVA: 0x6949c30 VA: 0x7598f61c30
	internal static Rect ComputeAAAlignedBound(Rect position, Matrix4x4 mat) { }
	// RVA: 0x6949e00 VA: 0x7598f61e00
	internal PseudoStates get_pseudoStates() { }
	// RVA: 0x6949e08 VA: 0x7598f61e08
	internal Void set_pseudoStates(PseudoStates value) { }
	// RVA: 0x6949e8c VA: 0x7598f61e8c
	internal Int32 get_containedPointerIds() { }
	// RVA: 0x6949e94 VA: 0x7598f61e94
	private Void set_containedPointerIds(Int32 value) { }
	// RVA: 0x6949e9c VA: 0x7598f61e9c
	private Void UpdateHoverPseudoState() { }
	// RVA: 0x6949f68 VA: 0x7598f61f68
	public PickingMode get_pickingMode() { }
	// RVA: 0x6949f70 VA: 0x7598f61f70
	public Void set_pickingMode(PickingMode value) { }
	// RVA: 0x6949fa8 VA: 0x7598f61fa8
	public String get_name() { }
	// RVA: 0x6949fb0 VA: 0x7598f61fb0
	public Void set_name(String value) { }
	// RVA: 0x694a018 VA: 0x7598f62018
	internal List`1 get_classList() { }
	// RVA: 0x694a0d4 VA: 0x7598f620d4
	internal String get_fullTypeName() { }
	// RVA: 0x694a280 VA: 0x7598f62280
	internal String get_typeName() { }
	// RVA: 0x694a350 VA: 0x7598f62350
	internal YogaNode get_yogaNode() { }
	// RVA: 0x694a358 VA: 0x7598f62358
	private Void set_yogaNode(YogaNode value) { }
	// RVA: 0x69440f4 VA: 0x7598f5c0f4
	internal ref ComputedStyle get_computedStyle() { }
	// RVA: 0x694a368 VA: 0x7598f62368
	internal Boolean get_hasInlineStyle() { }
	// RVA: 0x694a378 VA: 0x7598f62378
	internal Boolean get_styleInitialized() { }
	// RVA: 0x694a384 VA: 0x7598f62384
	internal Void set_styleInitialized(Boolean value) { }
	// RVA: 0x694a3b0 VA: 0x7598f623b0
	private Void ChangeIMGUIContainerCount(Int32 delta) { }
	// RVA: 0x694a3e0 VA: 0x7598f623e0
	public Void .ctor() { }
	// RVA: 0x694a708 VA: 0x7598f62708
	protected override Void ExecuteDefaultAction(EventBase evt) { }
	// RVA: 0x694b120 VA: 0x7598f63120
	internal virtual Rect GetTooltipRect() { }
	// RVA: 0x694b038 VA: 0x7598f63038
	private Void SetTooltip(TooltipEvent e) { }
	// RVA: 0x694b1b8 VA: 0x7598f631b8
	public sealed override Void Focus() { }
	// RVA: 0x694b20c VA: 0x7598f6320c
	internal Void SetPanel(BaseVisualElementPanel p) { }
	// RVA: 0x694bcfc VA: 0x7598f63cfc
	private Void WillChangePanel(BaseVisualElementPanel destinationPanel) { }
	// RVA: 0x694bee4 VA: 0x7598f63ee4
	private Void HasChangedPanel(BaseVisualElementPanel prevPanel) { }
	// RVA: 0x694c2dc VA: 0x7598f642dc
	public sealed override Void SendEvent(EventBase e) { }
	// RVA: 0x694c2f4 VA: 0x7598f642f4
	internal sealed override Void SendEvent(EventBase e, DispatchMode dispatchMode) { }
	// RVA: 0x694620c VA: 0x7598f5e20c
	internal Void IncrementVersion(VersionChangeType changeType) { }
	// RVA: 0x694c308 VA: 0x7598f64308
	internal Void InvokeHierarchyChanged(HierarchyChangeType changeType) { }
	// RVA: 0x694c328 VA: 0x7598f64328
	private Boolean SetEnabledFromHierarchyPrivate(Boolean state) { }
	// RVA: 0x694c6a4 VA: 0x7598f646a4
	private Boolean get_isParentEnabledInHierarchy() { }
	// RVA: 0x69468d0 VA: 0x7598f5e8d0
	public Boolean get_enabledInHierarchy() { }
	// RVA: 0x694ca30 VA: 0x7598f64a30
	public Boolean get_enabledSelf() { }
	// RVA: 0x694ca38 VA: 0x7598f64a38
	private Void set_enabledSelf(Boolean value) { }
	// RVA: 0x694a6e4 VA: 0x7598f626e4
	public Void SetEnabled(Boolean value) { }
	// RVA: 0x694ca44 VA: 0x7598f64a44
	private Void PropagateEnabledToChildren(Boolean value) { }
	// RVA: 0x6946824 VA: 0x7598f5e824
	public Boolean get_visible() { }
	// RVA: 0x694caf4 VA: 0x7598f64af4
	public Void set_visible(Boolean value) { }
	// RVA: 0x694cbd8 VA: 0x7598f64bd8
	public Void MarkDirtyRepaint() { }
	// RVA: 0x694cbfc VA: 0x7598f64bfc
	public Action`1 get_generateVisualContent() { }
	// RVA: 0x694cc04 VA: 0x7598f64c04
	public Void set_generateVisualContent(Action`1 value) { }
	// RVA: 0x694cc14 VA: 0x7598f64c14
	internal Void InvokeGenerateVisualContent(MeshGenerationContext mgc) { }
	// RVA: 0x694ce48 VA: 0x7598f64e48
	internal Void GetFullHierarchicalViewDataKey(StringBuilder key) { }
	// RVA: 0x694cedc VA: 0x7598f64edc
	internal String GetFullHierarchicalViewDataKey() { }
	// RVA: 0x694cf50 VA: 0x7598f64f50
	internal Void OverwriteFromViewData(Object obj, String key) { }
	// RVA: 0x694d270 VA: 0x7598f65270
	internal Void SaveViewData() { }
	// RVA: 0x694d2ec VA: 0x7598f652ec
	internal Boolean IsViewDataPersitenceSupportedOnChildren(Boolean existingState) { }
	// RVA: 0x694d360 VA: 0x7598f65360
	internal Void OnViewDataReady(Boolean enablePersistence) { }
	// RVA: 0x694d398 VA: 0x7598f65398
	internal virtual Void OnViewDataReady() { }
	// RVA: 0x694d39c VA: 0x7598f6539c
	public virtual Boolean ContainsPoint(Vector2 localPoint) { }
	// RVA: 0x694d3e4 VA: 0x7598f653e4
	internal Boolean get_requireMeasureFunction() { }
	// RVA: 0x694d3f0 VA: 0x7598f653f0
	internal Void set_requireMeasureFunction(Boolean value) { }
	// RVA: 0x694d460 VA: 0x7598f65460
	private Void AssignMeasureFunction() { }
	// RVA: 0x694d4ec VA: 0x7598f654ec
	private Void RemoveMeasureFunction() { }
	// RVA: 0x694d50c VA: 0x7598f6550c
	protected internal virtual Vector2 DoMeasure(Single desiredWidth, MeasureMode widthMode, Single desiredHeight, MeasureMode heightMode) { }
	// RVA: 0x694d51c VA: 0x7598f6551c
	internal YogaSize Measure(YogaNode node, Single width, YogaMeasureMode widthMode, Single height, YogaMeasureMode heightMode) { }
	// RVA: 0x694d644 VA: 0x7598f65644
	private Void FinalizeLayout() { }
	// RVA: 0x694d690 VA: 0x7598f65690
	internal Void SetInlineRule(StyleSheet sheet, StyleRule rule) { }
	// RVA: 0x694d730 VA: 0x7598f65730
	internal Void SetComputedStyle(ref ComputedStyle newStyle) { }
	// RVA: 0x694d8fc VA: 0x7598f658fc
	public override String ToString() { }
	// RVA: 0x694dbb4 VA: 0x7598f65bb4
	internal List`1 GetClassesForIteration() { }
	// RVA: 0x694c80c VA: 0x7598f6480c
	public Void AddToClassList(String className) { }
	// RVA: 0x694c6d8 VA: 0x7598f646d8
	public Void RemoveFromClassList(String className) { }
	// RVA: 0x694ca24 VA: 0x7598f64a24
	public Void EnableInClassList(String className, Boolean enable) { }
	// RVA: 0x694dbbc VA: 0x7598f65bbc
	public Boolean ClassListContains(String cls) { }
	// RVA: 0x694dc64 VA: 0x7598f65c64
	internal Object GetProperty(PropertyName key) { }
	// RVA: 0x694de4c VA: 0x7598f65e4c
	internal Void SetProperty(PropertyName key, Object value) { }
	// RVA: 0x694dec4 VA: 0x7598f65ec4
	internal Boolean HasProperty(PropertyName key) { }
	// RVA: 0x69462e4 VA: 0x7598f5e2e4
	private Boolean TryGetPropertyInternal(PropertyName key, out Object value) { }
	// RVA: 0x694dce4 VA: 0x7598f65ce4
	private static Void CheckUserKeyArgument(PropertyName key) { }
	// RVA: 0x6946450 VA: 0x7598f5e450
	private Void SetPropertyInternal(PropertyName key, Object value) { }
	// RVA: 0x694adb0 VA: 0x7598f62db0
	private Void UpdateCursorStyle(Int64 eventType) { }
	// RVA: 0x694df44 VA: 0x7598f65f44
	internal RenderTargetMode get_subRenderTargetMode() { }
	// RVA: 0x694df4c VA: 0x7598f65f4c
	internal Material get_defaultMaterial() { }
	// RVA: 0x694df54 VA: 0x7598f65f54
	private VisualElementAnimationSystem GetAnimationSystem() { }
	// RVA: 0x694dfe8 VA: 0x7598f65fe8
	internal Void RegisterAnimation(IValueAnimationUpdate anim) { }
	// RVA: 0x694e120 VA: 0x7598f66120
	internal Void UnregisterAnimation(IValueAnimationUpdate anim) { }
	// RVA: 0x694c1a0 VA: 0x7598f641a0
	private Void UnregisterRunningAnimations() { }
	// RVA: 0x694c270 VA: 0x7598f64270
	private Void RegisterRunningAnimations() { }
	// RVA: 0x VA: 0x0
	private static ValueAnimation`1 StartAnimation(ValueAnimation`1 anim, Func`2 fromValueGetter, T to, Int32 durationMs, Action`2 onValueChanged) { }
	// RVA: 0x694e198 VA: 0x7598f66198
	private static Void AssignStyleValues(VisualElement ve, StyleValues src) { }
	// RVA: 0x694f778 VA: 0x7598f67778
	private StyleValues ReadCurrentValues(VisualElement ve, StyleValues targetValuesToRead) { }
	// RVA: 0x695065c VA: 0x7598f6865c
	private ValueAnimation`1 UnityEngine.UIElements.Experimental.ITransitionAnimations.Start(StyleValues to, Int32 durationMs) { }
	// RVA: 0x6950748 VA: 0x7598f68748
	private ValueAnimation`1 Start(Func`2 fromValueGetter, StyleValues to, Int32 durationMs) { }
	// RVA: 0x69508cc VA: 0x7598f688cc
	public IExperimentalFeatures get_experimental() { }
	// RVA: 0x69508d0 VA: 0x7598f688d0
	private ITransitionAnimations UnityEngine.UIElements.IExperimentalFeatures.get_animation() { }
	// RVA: 0x69508d4 VA: 0x7598f688d4
	public Hierarchy get_hierarchy() { }
	// RVA: 0x69508dc VA: 0x7598f688dc
	private Void set_hierarchy(Hierarchy value) { }
	// RVA: 0x69508f0 VA: 0x7598f688f0
	internal Boolean get_isRootVisualContainer() { }
	// RVA: 0x69508f8 VA: 0x7598f688f8
	internal Void set_isRootVisualContainer(Boolean value) { }
	// RVA: 0x6950904 VA: 0x7598f68904
	internal Boolean get_disableClipping() { }
	// RVA: 0x6950910 VA: 0x7598f68910
	internal Void set_disableClipping(Boolean value) { }
	// RVA: 0x6948704 VA: 0x7598f60704
	internal Boolean ShouldClip() { }
	// RVA: 0x694681c VA: 0x7598f5e81c
	public VisualElement get_parent() { }
	// RVA: 0x695093c VA: 0x7598f6893c
	internal BaseVisualElementPanel get_elementPanel() { }
	// RVA: 0x6950944 VA: 0x7598f68944
	private Void set_elementPanel(BaseVisualElementPanel value) { }
	// RVA: 0x6946990 VA: 0x7598f5e990
	public IPanel get_panel() { }
	// RVA: 0x6950954 VA: 0x7598f68954
	public virtual VisualElement get_contentContainer() { }
	// RVA: 0x6950958 VA: 0x7598f68958
	internal Void set_visualTreeAssetSource(VisualTreeAsset value) { }
	// RVA: 0x6950968 VA: 0x7598f68968
	public Void Add(VisualElement child) { }
	// RVA: 0x6950aa0 VA: 0x7598f68aa0
	public Void Insert(Int32 index, VisualElement element) { }
	// RVA: 0x6950e60 VA: 0x7598f68e60
	public Void Clear() { }
	// RVA: 0x6951218 VA: 0x7598f69218
	public VisualElement ElementAt(Int32 index) { }
	// RVA: 0x695121c VA: 0x7598f6921c
	public VisualElement get_Item(Int32 key) { }
	// RVA: 0x69512f0 VA: 0x7598f692f0
	public Int32 get_childCount() { }
	// RVA: 0x69513a4 VA: 0x7598f693a4
	public Int32 IndexOf(VisualElement element) { }
	// RVA: 0x6951480 VA: 0x7598f69480
	internal VisualElement ElementAtTreePath(List`1 childIndexes) { }
	// RVA: 0x6951628 VA: 0x7598f69628
	internal Boolean FindElementInTree(VisualElement element, List`1 outChildIndexes) { }
	// RVA: 0x6951710 VA: 0x7598f69710
	public Void BringToFront() { }
	// RVA: 0x69517fc VA: 0x7598f697fc
	public Void SendToBack() { }
	// RVA: 0x69518cc VA: 0x7598f698cc
	public Void PlaceBehind(VisualElement sibling) { }
	// RVA: 0x6951a90 VA: 0x7598f69a90
	public Void RemoveFromHierarchy() { }
	// RVA: 0x VA: 0x0
	public T GetFirstOfType() { }
	// RVA: 0x VA: 0x0
	public T GetFirstAncestorOfType() { }
	// RVA: 0x6951bbc VA: 0x7598f69bbc
	public Boolean Contains(VisualElement child) { }
	// RVA: 0x694bc24 VA: 0x7598f63c24
	private Void GatherAllChildren(List`1 elements) { }
	// RVA: 0x6951bf0 VA: 0x7598f69bf0
	public VisualElement FindCommonAncestor(VisualElement other) { }
	// RVA: 0x6951d08 VA: 0x7598f69d08
	internal VisualElement GetRoot() { }
	// RVA: 0x6951dc8 VA: 0x7598f69dc8
	internal VisualElement GetRootVisualContainer() { }
	// RVA: 0x6951e00 VA: 0x7598f69e00
	internal VisualElement GetNextElementDepthFirst() { }
	// RVA: 0x6951ef0 VA: 0x7598f69ef0
	internal VisualElement GetPreviousElementDepthFirst() { }
	// RVA: 0x6951fd8 VA: 0x7598f69fd8
	internal VisualElement RetargetElement(VisualElement retargetAgainst) { }
	// RVA: 0x6948d8c VA: 0x7598f60d8c
	private Vector3 get_positionWithLayout() { }
	// RVA: 0x6948df0 VA: 0x7598f60df0
	internal Void GetPivotedMatrixWithLayout(out Matrix4x4 result) { }
	// RVA: 0x69529b8 VA: 0x7598f6a9b8
	internal Boolean get_hasDefaultRotationAndScale() { }
	// RVA: 0x6952a88 VA: 0x7598f6aa88
	internal static Single Min(Single a, Single b, Single c, Single d) { }
	// RVA: 0x6952aa4 VA: 0x7598f6aaa4
	internal static Single Max(Single a, Single b, Single c, Single d) { }
	// RVA: 0x6952ac0 VA: 0x7598f6aac0
	private Void TransformAlignedRectToParentSpace(ref Rect rect) { }
	// RVA: 0x6952c44 VA: 0x7598f6ac44
	internal static Rect CalculateConservativeRect(ref Matrix4x4 matrix, Rect rect) { }
	// RVA: 0x69530ec VA: 0x7598f6b0ec
	internal static Void TransformAlignedRect(ref Matrix4x4 matrix, ref Rect rect) { }
	// RVA: 0x6953018 VA: 0x7598f6b018
	internal static Void OrderMinMaxRect(ref Rect rect) { }
	// RVA: 0x6953180 VA: 0x7598f6b180
	internal static Vector2 MultiplyMatrix44Point2(ref Matrix4x4 lhs, Vector2 point) { }
	// RVA: 0x69531a4 VA: 0x7598f6b1a4
	internal static Vector2 MultiplyVector2(ref Matrix4x4 lhs, Vector2 vector) { }
	// RVA: 0x6948f88 VA: 0x7598f60f88
	internal static Void MultiplyMatrix34(ref Matrix4x4 lhs, ref Matrix4x4 rhs, out Matrix4x4 res) { }
	// RVA: 0x69531c0 VA: 0x7598f6b1c0
	private static Void TranslateMatrix34(ref Matrix4x4 lhs, Vector3 rhs, out Matrix4x4 res) { }
	// RVA: 0x69532ac VA: 0x7598f6b2ac
	private static Void TranslateMatrix34InPlace(ref Matrix4x4 lhs, Vector3 rhs) { }
	// RVA: 0x6953308 VA: 0x7598f6b308
	public IVisualElementScheduler get_schedule() { }
	// RVA: 0x695330c VA: 0x7598f6b30c
	private IVisualElementScheduledItem UnityEngine.UIElements.IVisualElementScheduler.Execute(Action`1 timerUpdateEvent) { }
	// RVA: 0x6953440 VA: 0x7598f6b440
	private IVisualElementScheduledItem UnityEngine.UIElements.IVisualElementScheduler.Execute(Action updateEvent) { }
	// RVA: 0x6946cb4 VA: 0x7598f5ecb4
	public IStyle get_style() { }
	// RVA: 0x6953554 VA: 0x7598f6b554
	public ICustomStyle get_customStyle() { }
	// RVA: 0x6953608 VA: 0x7598f6b608
	public VisualElementStyleSheetSet get_styleSheets() { }
	// RVA: 0x695362c VA: 0x7598f6b62c
	internal Void AddStyleSheetPath(String sheetPath) { }
	// RVA: 0x6953860 VA: 0x7598f6b860
	private StyleFloat ResolveLengthValue(Length length, Boolean isRow) { }
	// RVA: 0x695203c VA: 0x7598f6a03c
	private Vector3 ResolveTranslate() { }
	// RVA: 0x6952334 VA: 0x7598f6a334
	private Vector3 ResolveTransformOrigin() { }
	// RVA: 0x69526f4 VA: 0x7598f6a6f4
	private Quaternion ResolveRotation() { }
	// RVA: 0x6952878 VA: 0x7598f6a878
	private Vector3 ResolveScale() { }
	// RVA: 0x694b124 VA: 0x7598f63124
	public String get_tooltip() { }
	// RVA: 0x69539f0 VA: 0x7598f6b9f0
	public Void set_tooltip(String value) { }
	// RVA: 0x694a0ec VA: 0x7598f620ec
	private TypeData get_typeData() { }
	// RVA: 0x6946118 VA: 0x7598f5e118
	public IResolvedStyle get_resolvedStyle() { }
	// RVA: 0x6953b90 VA: 0x7598f6bb90
	private Color UnityEngine.UIElements.IResolvedStyle.get_backgroundColor() { }
	// RVA: 0x6953b9c VA: 0x7598f6bb9c
	private Color UnityEngine.UIElements.IResolvedStyle.get_borderBottomColor() { }
	// RVA: 0x6953ba8 VA: 0x7598f6bba8
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderBottomLeftRadius() { }
	// RVA: 0x6953bc4 VA: 0x7598f6bbc4
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderBottomRightRadius() { }
	// RVA: 0x6953be0 VA: 0x7598f6bbe0
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderBottomWidth() { }
	// RVA: 0x6953bfc VA: 0x7598f6bbfc
	private Color UnityEngine.UIElements.IResolvedStyle.get_borderLeftColor() { }
	// RVA: 0x6953c08 VA: 0x7598f6bc08
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderLeftWidth() { }
	// RVA: 0x6953c24 VA: 0x7598f6bc24
	private Color UnityEngine.UIElements.IResolvedStyle.get_borderRightColor() { }
	// RVA: 0x6953c30 VA: 0x7598f6bc30
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderRightWidth() { }
	// RVA: 0x6953c4c VA: 0x7598f6bc4c
	private Color UnityEngine.UIElements.IResolvedStyle.get_borderTopColor() { }
	// RVA: 0x6953c58 VA: 0x7598f6bc58
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderTopLeftRadius() { }
	// RVA: 0x6953c74 VA: 0x7598f6bc74
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderTopRightRadius() { }
	// RVA: 0x6953c90 VA: 0x7598f6bc90
	private Single UnityEngine.UIElements.IResolvedStyle.get_borderTopWidth() { }
	// RVA: 0x6953cac VA: 0x7598f6bcac
	private Single UnityEngine.UIElements.IResolvedStyle.get_bottom() { }
	// RVA: 0x6953cc8 VA: 0x7598f6bcc8
	private Color UnityEngine.UIElements.IResolvedStyle.get_color() { }
	// RVA: 0x6953cd4 VA: 0x7598f6bcd4
	private DisplayStyle UnityEngine.UIElements.IResolvedStyle.get_display() { }
	// RVA: 0x6953ce0 VA: 0x7598f6bce0
	private FlexDirection UnityEngine.UIElements.IResolvedStyle.get_flexDirection() { }
	// RVA: 0x6953cec VA: 0x7598f6bcec
	private Single UnityEngine.UIElements.IResolvedStyle.get_flexGrow() { }
	// RVA: 0x6953cf8 VA: 0x7598f6bcf8
	private Single UnityEngine.UIElements.IResolvedStyle.get_flexShrink() { }
	// RVA: 0x6953d04 VA: 0x7598f6bd04
	private Single UnityEngine.UIElements.IResolvedStyle.get_height() { }
	// RVA: 0x6953d20 VA: 0x7598f6bd20
	private Single UnityEngine.UIElements.IResolvedStyle.get_left() { }
	// RVA: 0x6953d3c VA: 0x7598f6bd3c
	private Single UnityEngine.UIElements.IResolvedStyle.get_marginBottom() { }
	// RVA: 0x6953d58 VA: 0x7598f6bd58
	private Single UnityEngine.UIElements.IResolvedStyle.get_marginLeft() { }
	// RVA: 0x6953d74 VA: 0x7598f6bd74
	private Single UnityEngine.UIElements.IResolvedStyle.get_marginRight() { }
	// RVA: 0x6953d90 VA: 0x7598f6bd90
	private Single UnityEngine.UIElements.IResolvedStyle.get_marginTop() { }
	// RVA: 0x6953dac VA: 0x7598f6bdac
	private StyleFloat UnityEngine.UIElements.IResolvedStyle.get_minHeight() { }
	// RVA: 0x6953dd4 VA: 0x7598f6bdd4
	private StyleFloat UnityEngine.UIElements.IResolvedStyle.get_minWidth() { }
	// RVA: 0x6953dfc VA: 0x7598f6bdfc
	private Single UnityEngine.UIElements.IResolvedStyle.get_opacity() { }
	// RVA: 0x6953e08 VA: 0x7598f6be08
	private Single UnityEngine.UIElements.IResolvedStyle.get_paddingBottom() { }
	// RVA: 0x6953e24 VA: 0x7598f6be24
	private Single UnityEngine.UIElements.IResolvedStyle.get_paddingLeft() { }
	// RVA: 0x6953e40 VA: 0x7598f6be40
	private Single UnityEngine.UIElements.IResolvedStyle.get_paddingRight() { }
	// RVA: 0x6953e5c VA: 0x7598f6be5c
	private Single UnityEngine.UIElements.IResolvedStyle.get_paddingTop() { }
	// RVA: 0x6953e78 VA: 0x7598f6be78
	private Single UnityEngine.UIElements.IResolvedStyle.get_right() { }
	// RVA: 0x6953e94 VA: 0x7598f6be94
	private Scale UnityEngine.UIElements.IResolvedStyle.get_scale() { }
	// RVA: 0x6953ea0 VA: 0x7598f6bea0
	private Single UnityEngine.UIElements.IResolvedStyle.get_top() { }
	// RVA: 0x6953ebc VA: 0x7598f6bebc
	private Vector3 UnityEngine.UIElements.IResolvedStyle.get_transformOrigin() { }
	// RVA: 0x6953ec0 VA: 0x7598f6bec0
	private Vector3 UnityEngine.UIElements.IResolvedStyle.get_translate() { }
	// RVA: 0x6953ec4 VA: 0x7598f6bec4
	private Color UnityEngine.UIElements.IResolvedStyle.get_unityBackgroundImageTintColor() { }
	// RVA: 0x6953ed0 VA: 0x7598f6bed0
	private Int32 UnityEngine.UIElements.IResolvedStyle.get_unitySliceLeft() { }
	// RVA: 0x6953edc VA: 0x7598f6bedc
	private Int32 UnityEngine.UIElements.IResolvedStyle.get_unitySliceRight() { }
	// RVA: 0x6953ee8 VA: 0x7598f6bee8
	private Color UnityEngine.UIElements.IResolvedStyle.get_unityTextOutlineColor() { }
	// RVA: 0x6953ef4 VA: 0x7598f6bef4
	private Single UnityEngine.UIElements.IResolvedStyle.get_unityTextOutlineWidth() { }
	// RVA: 0x6953f00 VA: 0x7598f6bf00
	private Visibility UnityEngine.UIElements.IResolvedStyle.get_visibility() { }
	// RVA: 0x6953f0c VA: 0x7598f6bf0c
	private WhiteSpace UnityEngine.UIElements.IResolvedStyle.get_whiteSpace() { }
	// RVA: 0x6953f18 VA: 0x7598f6bf18
	private Single UnityEngine.UIElements.IResolvedStyle.get_width() { }
	// RVA: 0x6953f34 VA: 0x7598f6bf34
	private static Void .cctor() { }
	// RVA: 0x69541f0 VA: 0x7598f6c1f0
	private YogaSize <AssignMeasureFunction>b__254_0(YogaNode node, Single f, YogaMeasureMode mode, Single f1, YogaMeasureMode heightMode) { }
}
```