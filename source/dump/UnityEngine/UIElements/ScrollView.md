# ScrollView

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_FirstLayoutPass`

- `ScrollerVisibility m_HorizontalScrollerVisibility`

- `ScrollerVisibility m_VerticalScrollerVisibility`

- `VisualElement m_AttachedRootVisualContainer`

- `Single m_SingleLineHeight`

- `Single m_HorizontalPageSize`

- `Single m_VerticalPageSize`

- `Single m_MouseWheelScrollSize`

- `Single m_ScrollDecelerationRate`

- `Single k_ScaledPixelsPerPointMultiplier`

- `Single k_TouchScrollInertiaBaseTimeInterval`

- `Single m_Elasticity`

- `TouchScrollBehavior m_TouchScrollBehavior`

- `NestedInteractionKind m_NestedInteractionKind`

- `Int64 m_ElasticAnimationIntervalMs`

- `VisualElement <contentViewport>k__BackingField`

- `Scroller <horizontalScroller>k__BackingField`

- `Scroller <verticalScroller>k__BackingField`

- `VisualElement m_ContentContainer`

- `VisualElement m_ContentAndVerticalScrollContainer`

- `Single previousVerticalTouchScrollTimeStamp`

- `Single previousHorizontalTouchScrollTimeStamp`

- `Single elapsedTimeSinceLastVerticalTouchScroll`

- `Single elapsedTimeSinceLastHorizontalTouchScroll`

- `ScrollViewMode m_Mode`

- `IVisualElementScheduledItem m_ScheduledLayoutPassResetItem`

- `Vector2 m_StartPosition`

- `Vector2 m_PointerStartPosition`

- `Vector2 m_Velocity`

- `Vector2 m_SpringBackVelocity`

- `Vector2 m_LowBounds`

- `Vector2 m_HighBounds`

- `Single m_LastVelocityLerpTime`

- `Boolean m_StartedMoving`

- `Boolean m_TouchPointerMoveAllowed`

- `Boolean m_TouchStoppedVelocity`

- `VisualElement m_CapturedTarget`


## Properties

- `ScrollerVisibility horizontalScrollerVisibility`

- `ScrollerVisibility verticalScrollerVisibility`

- `Boolean showHorizontal`

- `Boolean showVertical`

- `Vector2 scrollOffset`

- `Single horizontalPageSize`

- `Single verticalPageSize`

- `Single mouseWheelScrollSize`

- `Boolean hasInertia`

- `Single scrollDecelerationRate`

- `Single elasticity`

- `TouchScrollBehavior touchScrollBehavior`

- `NestedInteractionKind nestedInteractionKind`

- `Int64 elasticAnimationIntervalMs`

- `VisualElement contentViewport`

- `Scroller horizontalScroller`

- `Scroller verticalScroller`

- `ScrollViewMode mode`


## Methods

- `ScrollerVisibility get_horizontalScrollerVisibility()`

- `Void set_horizontalScrollerVisibility(ScrollerVisibility)`

- `ScrollerVisibility get_verticalScrollerVisibility()`

- `Void set_verticalScrollerVisibility(ScrollerVisibility)`

- `Void set_showHorizontal(Boolean)`

- `Void set_showVertical(Boolean)`

- `Vector2 get_scrollOffset()`

- `Void set_scrollOffset(Vector2)`

- `Void set_horizontalPageSize(Single)`

- `Void set_verticalPageSize(Single)`

- `Single get_mouseWheelScrollSize()`

- `Void set_mouseWheelScrollSize(Single)`

- `Boolean get_hasInertia()`

- `Single get_scrollDecelerationRate()`

- `Void set_scrollDecelerationRate(Single)`

- `Single get_elasticity()`

- `Void set_elasticity(Single)`

- `TouchScrollBehavior get_touchScrollBehavior()`

- `Void set_touchScrollBehavior(TouchScrollBehavior)`

- `NestedInteractionKind get_nestedInteractionKind()`

- `Void set_nestedInteractionKind(NestedInteractionKind)`

- `Void set_elasticAnimationIntervalMs(Int64)`

- `Void OnHorizontalScrollDragElementChanged(GeometryChangedEvent)`

- `Void OnVerticalScrollDragElementChanged(GeometryChangedEvent)`

- `Void UpdateHorizontalSliderPageSize()`

- `Void UpdateVerticalSliderPageSize()`

- `Void ScrollTo(VisualElement)`

- `Single GetXDeltaOffset(VisualElement)`

- `Single GetYDeltaOffset(VisualElement)`

- `Single GetDeltaDistance(Single, Single, Single, Single)`

- `VisualElement get_contentViewport()`

- `Void set_contentViewport(VisualElement)`

- `Scroller get_horizontalScroller()`

- `Void set_horizontalScroller(Scroller)`

- `Scroller get_verticalScroller()`

- `Void set_verticalScroller(Scroller)`

- `ScrollViewMode get_mode()`

- `Void set_mode(ScrollViewMode)`

- `Void SetScrollViewMode(ScrollViewMode)`

- `Void OnAttachToPanel(AttachToPanelEvent)`

- `Void OnDetachFromPanel(DetachFromPanelEvent)`

- `Void OnPointerCapture(PointerCaptureEvent)`

- `Void OnPointerCaptureOut(PointerCaptureOutEvent)`

- `Void OnGeometryChanged(GeometryChangedEvent)`

- `Void ScheduleResetLayoutPass()`

- `Void ResetLayoutPass()`

- `Void ComputeInitialSpringBackVelocity()`

- `Void SpringBack()`

- `Void PostPointerUpAnimation()`

- `Void OnPointerDown(PointerDownEvent)`

- `Void OnPointerMove(PointerMoveEvent)`

- `Void OnPointerCancel(PointerCancelEvent)`

- `Void OnPointerUp(PointerUpEvent)`

- `Boolean ApplyTouchScrolling(Vector2)`

- `Boolean ReleaseScrolling(Int32, IEventHandler)`

- `Void ExecuteElasticSpringAnimation()`

- `Void AdjustScrollers()`

- `Void OnScrollersGeometryChanged(GeometryChangedEvent)`

- `Void OnScrollWheel(WheelEvent)`

- `Void OnRootCustomStyleResolved(CustomStyleResolvedEvent)`

- `Void OnRootPointerUp(PointerUpEvent)`

- `Void ReadSingleLineHeight()`

- `Void UpdateElasticBehaviour()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class ScrollView : VisualElement
{
	private Int32 m_FirstLayoutPass; // 0x3b0
	private ScrollerVisibility m_HorizontalScrollerVisibility; // 0x3b4
	private ScrollerVisibility m_VerticalScrollerVisibility; // 0x3b8
	private VisualElement m_AttachedRootVisualContainer; // 0x3c0
	private Single m_SingleLineHeight; // 0x3c8
	internal Boolean m_MouseWheelScrollSizeIsInline; // 0x3cc
	private Single m_HorizontalPageSize; // 0x3d0
	private Single m_VerticalPageSize; // 0x3d4
	private Single m_MouseWheelScrollSize; // 0x3d8
	private static readonly Single k_DefaultScrollDecelerationRate; // 0x0
	private Single m_ScrollDecelerationRate; // 0x3dc
	private Single k_ScaledPixelsPerPointMultiplier; // 0x3e0
	private Single k_TouchScrollInertiaBaseTimeInterval; // 0x3e4
	private static readonly Single k_DefaultElasticity; // 0x4
	private Single m_Elasticity; // 0x3e8
	private TouchScrollBehavior m_TouchScrollBehavior; // 0x3ec
	private NestedInteractionKind m_NestedInteractionKind; // 0x3f0
	private static readonly Int64 k_DefaultElasticAnimationInterval; // 0x8
	private Int64 m_ElasticAnimationIntervalMs; // 0x3f8
	private VisualElement <contentViewport>k__BackingField; // 0x400
	private Scroller <horizontalScroller>k__BackingField; // 0x408
	private Scroller <verticalScroller>k__BackingField; // 0x410
	private VisualElement m_ContentContainer; // 0x418
	private VisualElement m_ContentAndVerticalScrollContainer; // 0x420
	private Single previousVerticalTouchScrollTimeStamp; // 0x428
	private Single previousHorizontalTouchScrollTimeStamp; // 0x42c
	private Single elapsedTimeSinceLastVerticalTouchScroll; // 0x430
	private Single elapsedTimeSinceLastHorizontalTouchScroll; // 0x434
	public static readonly String ussClassName; // 0x10
	public static readonly String viewportUssClassName; // 0x18
	public static readonly String contentAndVerticalScrollUssClassName; // 0x20
	public static readonly String contentUssClassName; // 0x28
	public static readonly String hScrollerUssClassName; // 0x30
	public static readonly String vScrollerUssClassName; // 0x38
	public static readonly String horizontalVariantUssClassName; // 0x40
	public static readonly String verticalVariantUssClassName; // 0x48
	public static readonly String verticalHorizontalVariantUssClassName; // 0x50
	public static readonly String scrollVariantUssClassName; // 0x58
	private ScrollViewMode m_Mode; // 0x438
	private IVisualElementScheduledItem m_ScheduledLayoutPassResetItem; // 0x440
	private Vector2 m_StartPosition; // 0x448
	private Vector2 m_PointerStartPosition; // 0x450
	private Vector2 m_Velocity; // 0x458
	private Vector2 m_SpringBackVelocity; // 0x460
	private Vector2 m_LowBounds; // 0x468
	private Vector2 m_HighBounds; // 0x470
	private Single m_LastVelocityLerpTime; // 0x478
	private Boolean m_StartedMoving; // 0x47c
	private Boolean m_TouchPointerMoveAllowed; // 0x47d
	private Boolean m_TouchStoppedVelocity; // 0x47e
	private VisualElement m_CapturedTarget; // 0x480
	private EventCallback`1 m_CapturedTargetPointerMoveCallback; // 0x488
	private EventCallback`1 m_CapturedTargetPointerUpCallback; // 0x490
	internal IVisualElementScheduledItem m_PostPointerUpAnimation; // 0x498

	public ScrollerVisibility horizontalScrollerVisibility { get; set; }
	public ScrollerVisibility verticalScrollerVisibility { get; set; }
	public Boolean showHorizontal { set; }
	public Boolean showVertical { set; }
	internal Boolean needsHorizontal { get; }
	internal Boolean needsVertical { get; }
	internal Boolean isVerticalScrollDisplayed { get; }
	internal Boolean isHorizontalScrollDisplayed { get; }
	public Vector2 scrollOffset { get; set; }
	public Single horizontalPageSize { set; }
	public Single verticalPageSize { set; }
	public Single mouseWheelScrollSize { get; set; }
	internal Single scrollableWidth { get; }
	internal Single scrollableHeight { get; }
	private Boolean hasInertia { get; }
	public Single scrollDecelerationRate { get; set; }
	public Single elasticity { get; set; }
	public TouchScrollBehavior touchScrollBehavior { get; set; }
	public NestedInteractionKind nestedInteractionKind { get; set; }
	public Int64 elasticAnimationIntervalMs { set; }
	public VisualElement contentViewport { get; set; }
	public Scroller horizontalScroller { get; set; }
	public Scroller verticalScroller { get; set; }
	public override VisualElement contentContainer { get; }
	public ScrollViewMode mode { get; set; }

	// RVA: 0x69bd330 VA: 0x7598fd5330
	public ScrollerVisibility get_horizontalScrollerVisibility() { }
	// RVA: 0x69bd338 VA: 0x7598fd5338
	public Void set_horizontalScrollerVisibility(ScrollerVisibility value) { }
	// RVA: 0x69bd8b0 VA: 0x7598fd58b0
	public ScrollerVisibility get_verticalScrollerVisibility() { }
	// RVA: 0x69bd8b8 VA: 0x7598fd58b8
	public Void set_verticalScrollerVisibility(ScrollerVisibility value) { }
	// RVA: 0x69bd948 VA: 0x7598fd5948
	public Void set_showHorizontal(Boolean value) { }
	// RVA: 0x69bd964 VA: 0x7598fd5964
	public Void set_showVertical(Boolean value) { }
	// RVA: 0x69bd3c4 VA: 0x7598fd53c4
	internal Boolean get_needsHorizontal() { }
	// RVA: 0x69bd404 VA: 0x7598fd5404
	internal Boolean get_needsVertical() { }
	// RVA: 0x69bda88 VA: 0x7598fd5a88
	internal Boolean get_isVerticalScrollDisplayed() { }
	// RVA: 0x69bdb48 VA: 0x7598fd5b48
	internal Boolean get_isHorizontalScrollDisplayed() { }
	// RVA: 0x69bdc08 VA: 0x7598fd5c08
	public Vector2 get_scrollOffset() { }
	// RVA: 0x69bdc70 VA: 0x7598fd5c70
	public Void set_scrollOffset(Vector2 value) { }
	// RVA: 0x69bdf7c VA: 0x7598fd5f7c
	public Void set_horizontalPageSize(Single value) { }
	// RVA: 0x69be190 VA: 0x7598fd6190
	public Void set_verticalPageSize(Single value) { }
	// RVA: 0x69be3a4 VA: 0x7598fd63a4
	public Single get_mouseWheelScrollSize() { }
	// RVA: 0x69be3ac VA: 0x7598fd63ac
	public Void set_mouseWheelScrollSize(Single value) { }
	// RVA: 0x69bd980 VA: 0x7598fd5980
	internal Single get_scrollableWidth() { }
	// RVA: 0x69bda04 VA: 0x7598fd5a04
	internal Single get_scrollableHeight() { }
	// RVA: 0x69be428 VA: 0x7598fd6428
	private Boolean get_hasInertia() { }
	// RVA: 0x69be438 VA: 0x7598fd6438
	public Single get_scrollDecelerationRate() { }
	// RVA: 0x69be440 VA: 0x7598fd6440
	public Void set_scrollDecelerationRate(Single value) { }
	// RVA: 0x69be450 VA: 0x7598fd6450
	public Single get_elasticity() { }
	// RVA: 0x69be458 VA: 0x7598fd6458
	public Void set_elasticity(Single value) { }
	// RVA: 0x69be468 VA: 0x7598fd6468
	public TouchScrollBehavior get_touchScrollBehavior() { }
	// RVA: 0x69be470 VA: 0x7598fd6470
	public Void set_touchScrollBehavior(TouchScrollBehavior value) { }
	// RVA: 0x69be508 VA: 0x7598fd6508
	public NestedInteractionKind get_nestedInteractionKind() { }
	// RVA: 0x69be510 VA: 0x7598fd6510
	public Void set_nestedInteractionKind(NestedInteractionKind value) { }
	// RVA: 0x69be518 VA: 0x7598fd6518
	public Void set_elasticAnimationIntervalMs(Int64 value) { }
	// RVA: 0x69be6c8 VA: 0x7598fd66c8
	private Void OnHorizontalScrollDragElementChanged(GeometryChangedEvent evt) { }
	// RVA: 0x69be75c VA: 0x7598fd675c
	private Void OnVerticalScrollDragElementChanged(GeometryChangedEvent evt) { }
	// RVA: 0x69bdf84 VA: 0x7598fd5f84
	private Void UpdateHorizontalSliderPageSize() { }
	// RVA: 0x69be198 VA: 0x7598fd6198
	private Void UpdateVerticalSliderPageSize() { }
	// RVA: 0x69bdd14 VA: 0x7598fd5d14
	internal Void UpdateContentViewTransform() { }
	// RVA: 0x69be7f0 VA: 0x7598fd67f0
	public Void ScrollTo(VisualElement child) { }
	// RVA: 0x69bec3c VA: 0x7598fd6c3c
	private Single GetXDeltaOffset(VisualElement child) { }
	// RVA: 0x69be9c8 VA: 0x7598fd69c8
	private Single GetYDeltaOffset(VisualElement child) { }
	// RVA: 0x69beeb0 VA: 0x7598fd6eb0
	private Single GetDeltaDistance(Single viewMin, Single viewMax, Single childBoundaryMin, Single childBoundaryMax) { }
	// RVA: 0x69bef00 VA: 0x7598fd6f00
	public VisualElement get_contentViewport() { }
	// RVA: 0x69bef08 VA: 0x7598fd6f08
	private Void set_contentViewport(VisualElement value) { }
	// RVA: 0x69bef18 VA: 0x7598fd6f18
	public Scroller get_horizontalScroller() { }
	// RVA: 0x69bef20 VA: 0x7598fd6f20
	private Void set_horizontalScroller(Scroller value) { }
	// RVA: 0x69bef30 VA: 0x7598fd6f30
	public Scroller get_verticalScroller() { }
	// RVA: 0x69bef38 VA: 0x7598fd6f38
	private Void set_verticalScroller(Scroller value) { }
	// RVA: 0x69bef48 VA: 0x7598fd6f48
	public override VisualElement get_contentContainer() { }
	// RVA: 0x69bef50 VA: 0x7598fd6f50
	public Void .ctor() { }
	// RVA: 0x69bef58 VA: 0x7598fd6f58
	public Void .ctor(ScrollViewMode scrollViewMode) { }
	// RVA: 0x69bfd48 VA: 0x7598fd7d48
	public ScrollViewMode get_mode() { }
	// RVA: 0x69bfd50 VA: 0x7598fd7d50
	public Void set_mode(ScrollViewMode value) { }
	// RVA: 0x69bfbe0 VA: 0x7598fd7be0
	private Void SetScrollViewMode(ScrollViewMode mode) { }
	// RVA: 0x69bfd64 VA: 0x7598fd7d64
	private Void OnAttachToPanel(AttachToPanelEvent evt) { }
	// RVA: 0x69c03fc VA: 0x7598fd83fc
	private Void OnDetachFromPanel(DetachFromPanelEvent evt) { }
	// RVA: 0x69c0a00 VA: 0x7598fd8a00
	private Void OnPointerCapture(PointerCaptureEvent evt) { }
	// RVA: 0x69c0b4c VA: 0x7598fd8b4c
	private Void OnPointerCaptureOut(PointerCaptureOutEvent evt) { }
	// RVA: 0x69c0cf4 VA: 0x7598fd8cf4
	private Void OnGeometryChanged(GeometryChangedEvent evt) { }
	// RVA: 0x69c0e68 VA: 0x7598fd8e68
	private Void ScheduleResetLayoutPass() { }
	// RVA: 0x69c09f4 VA: 0x7598fd89f4
	private Void ResetLayoutPass() { }
	// RVA: 0x69c1068 VA: 0x7598fd9068
	private static Single ComputeElasticOffset(Single deltaPointer, Single initialScrollOffset, Single lowLimit, Single hardLowLimit, Single highLimit, Single hardHighLimit) { }
	// RVA: 0x69c1154 VA: 0x7598fd9154
	private Void ComputeInitialSpringBackVelocity() { }
	// RVA: 0x69c1250 VA: 0x7598fd9250
	private Void SpringBack() { }
	// RVA: 0x69c13dc VA: 0x7598fd93dc
	internal Void ApplyScrollInertia() { }
	// RVA: 0x69c161c VA: 0x7598fd961c
	private Void PostPointerUpAnimation() { }
	// RVA: 0x69c17a8 VA: 0x7598fd97a8
	private Void OnPointerDown(PointerDownEvent evt) { }
	// RVA: 0x69c1af8 VA: 0x7598fd9af8
	private Void OnPointerMove(PointerMoveEvent evt) { }
	// RVA: 0x69c20f4 VA: 0x7598fda0f4
	private Void OnPointerCancel(PointerCancelEvent evt) { }
	// RVA: 0x69c2154 VA: 0x7598fda154
	private Void OnPointerUp(PointerUpEvent evt) { }
	// RVA: 0x69c19dc VA: 0x7598fd99dc
	internal Void InitTouchScrolling(Vector2 position) { }
	// RVA: 0x69c1cf0 VA: 0x7598fd9cf0
	internal TouchScrollingResult ComputeTouchScrolling(Vector2 position) { }
	// RVA: 0x69c21fc VA: 0x7598fda1fc
	private Boolean ApplyTouchScrolling(Vector2 newScrollOffset) { }
	// RVA: 0x69c0c24 VA: 0x7598fd8c24
	private Boolean ReleaseScrolling(Int32 pointerId, IEventHandler target) { }
	// RVA: 0x69c240c VA: 0x7598fda40c
	private Void ExecuteElasticSpringAnimation() { }
	// RVA: 0x69c261c VA: 0x7598fda61c
	private Void AdjustScrollers() { }
	// RVA: 0x69bd444 VA: 0x7598fd5444
	internal Void UpdateScrollers(Boolean displayHorizontal, Boolean displayVertical) { }
	// RVA: 0x69c27b0 VA: 0x7598fda7b0
	private Void OnScrollersGeometryChanged(GeometryChangedEvent evt) { }
	// RVA: 0x69c2960 VA: 0x7598fda960
	private Void OnScrollWheel(WheelEvent evt) { }
	// RVA: 0x69c2e38 VA: 0x7598fdae38
	private Void OnRootCustomStyleResolved(CustomStyleResolvedEvent evt) { }
	// RVA: 0x69c2e3c VA: 0x7598fdae3c
	private Void OnRootPointerUp(PointerUpEvent evt) { }
	// RVA: 0x69c02f0 VA: 0x7598fd82f0
	private Void ReadSingleLineHeight() { }
	// RVA: 0x69c2d60 VA: 0x7598fdad60
	private Void UpdateElasticBehaviour() { }
	// RVA: 0x69c2e44 VA: 0x7598fdae44
	private static Void .cctor() { }
	// RVA: 0x69c313c VA: 0x7598fdb13c
	private Void <.ctor>b__123_0(Single value) { }
	// RVA: 0x69c316c VA: 0x7598fdb16c
	private Void <.ctor>b__123_1(Single value) { }
}
```