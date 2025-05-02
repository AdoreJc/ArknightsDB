# ScrollRect

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_Content`

- `Boolean m_Horizontal`

- `Boolean m_Vertical`

- `MovementType m_MovementType`

- `Single m_Elasticity`

- `Boolean m_Inertia`

- `Single m_DecelerationRate`

- `Single m_ScrollSensitivity`

- `RectTransform m_Viewport`

- `Scrollbar m_HorizontalScrollbar`

- `Scrollbar m_VerticalScrollbar`

- `ScrollbarVisibility m_HorizontalScrollbarVisibility`

- `ScrollbarVisibility m_VerticalScrollbarVisibility`

- `Single m_HorizontalScrollbarSpacing`

- `Single m_VerticalScrollbarSpacing`

- `ScrollRectEvent m_OnValueChanged`

- `Vector2 m_PointerStartLocalCursor`

- `Vector2 m_ContentStartPosition`

- `RectTransform m_ViewRect`

- `Bounds m_ContentBounds`

- `Bounds m_ViewBounds`

- `Vector2 m_Velocity`

- `Boolean m_Dragging`

- `Boolean m_Scrolling`

- `Vector2 m_PrevPosition`

- `Bounds m_PrevContentBounds`

- `Bounds m_PrevViewBounds`

- `Boolean m_HasRebuiltLayout`

- `Boolean m_HSliderExpand`

- `Boolean m_VSliderExpand`

- `Single m_HSliderHeight`

- `Single m_VSliderWidth`

- `RectTransform m_Rect`

- `RectTransform m_HorizontalScrollbarRect`

- `RectTransform m_VerticalScrollbarRect`

- `DrivenRectTransformTracker m_Tracker`


## Properties

- `RectTransform content`

- `Boolean horizontal`

- `Boolean vertical`

- `MovementType movementType`

- `Single elasticity`

- `Boolean inertia`

- `Single decelerationRate`

- `Single scrollSensitivity`

- `RectTransform viewport`

- `Scrollbar horizontalScrollbar`

- `Scrollbar verticalScrollbar`

- `ScrollbarVisibility horizontalScrollbarVisibility`

- `ScrollbarVisibility verticalScrollbarVisibility`

- `Single horizontalScrollbarSpacing`

- `Single verticalScrollbarSpacing`

- `ScrollRectEvent onValueChanged`

- `RectTransform viewRect`

- `Vector2 velocity`

- `RectTransform rectTransform`

- `Vector2 normalizedPosition`

- `Single horizontalNormalizedPosition`

- `Single verticalNormalizedPosition`

- `Boolean hScrollingNeeded`

- `Boolean vScrollingNeeded`


## Methods

- `RectTransform get_content()`

- `Void set_content(RectTransform)`

- `Boolean get_horizontal()`

- `Void set_horizontal(Boolean)`

- `Boolean get_vertical()`

- `Void set_vertical(Boolean)`

- `MovementType get_movementType()`

- `Void set_movementType(MovementType)`

- `Single get_elasticity()`

- `Void set_elasticity(Single)`

- `Boolean get_inertia()`

- `Void set_inertia(Boolean)`

- `Single get_decelerationRate()`

- `Void set_decelerationRate(Single)`

- `Single get_scrollSensitivity()`

- `Void set_scrollSensitivity(Single)`

- `RectTransform get_viewport()`

- `Void set_viewport(RectTransform)`

- `Scrollbar get_horizontalScrollbar()`

- `Void set_horizontalScrollbar(Scrollbar)`

- `Scrollbar get_verticalScrollbar()`

- `Void set_verticalScrollbar(Scrollbar)`

- `ScrollbarVisibility get_horizontalScrollbarVisibility()`

- `Void set_horizontalScrollbarVisibility(ScrollbarVisibility)`

- `ScrollbarVisibility get_verticalScrollbarVisibility()`

- `Void set_verticalScrollbarVisibility(ScrollbarVisibility)`

- `Single get_horizontalScrollbarSpacing()`

- `Void set_horizontalScrollbarSpacing(Single)`

- `Single get_verticalScrollbarSpacing()`

- `Void set_verticalScrollbarSpacing(Single)`

- `ScrollRectEvent get_onValueChanged()`

- `Void set_onValueChanged(ScrollRectEvent)`

- `RectTransform get_viewRect()`

- `Vector2 get_velocity()`

- `Void set_velocity(Vector2)`

- `RectTransform get_rectTransform()`

- `Void UpdateCachedData()`

- `Void EnsureLayoutHasRebuilt()`

- `Void UpdatePrevData()`

- `Void UpdateScrollbars(Vector2)`

- `Vector2 get_normalizedPosition()`

- `Void set_normalizedPosition(Vector2)`

- `Single get_horizontalNormalizedPosition()`

- `Void set_horizontalNormalizedPosition(Single)`

- `Single get_verticalNormalizedPosition()`

- `Void set_verticalNormalizedPosition(Single)`

- `Void SetHorizontalNormalizedPosition(Single)`

- `Void SetVerticalNormalizedPosition(Single)`

- `Boolean get_hScrollingNeeded()`

- `Boolean get_vScrollingNeeded()`

- `Void UpdateScrollbarVisibility()`

- `Void UpdateScrollbarLayout()`

- `Void UpdateBounds()`

- `Bounds GetBounds()`

- `Vector2 CalculateOffset(Vector2)`

- `Void SetDirty()`

- `Void SetDirtyCaching()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class ScrollRect : UIBehaviour, IInitializePotentialDragHandler, IEventSystemHandler, IBeginDragHandler, IEndDragHandler, IDragHandler, IScrollHandler, ICanvasElement, ILayoutElement, ILayoutGroup, ILayoutController
{
	private RectTransform m_Content; // 0x18
	private Boolean m_Horizontal; // 0x20
	private Boolean m_Vertical; // 0x21
	private MovementType m_MovementType; // 0x24
	private Single m_Elasticity; // 0x28
	private Boolean m_Inertia; // 0x2c
	private Single m_DecelerationRate; // 0x30
	private Single m_ScrollSensitivity; // 0x34
	private RectTransform m_Viewport; // 0x38
	private Scrollbar m_HorizontalScrollbar; // 0x40
	private Scrollbar m_VerticalScrollbar; // 0x48
	private ScrollbarVisibility m_HorizontalScrollbarVisibility; // 0x50
	private ScrollbarVisibility m_VerticalScrollbarVisibility; // 0x54
	private Single m_HorizontalScrollbarSpacing; // 0x58
	private Single m_VerticalScrollbarSpacing; // 0x5c
	private ScrollRectEvent m_OnValueChanged; // 0x60
	private Vector2 m_PointerStartLocalCursor; // 0x68
	protected Vector2 m_ContentStartPosition; // 0x70
	private RectTransform m_ViewRect; // 0x78
	protected Bounds m_ContentBounds; // 0x80
	private Bounds m_ViewBounds; // 0x98
	private Vector2 m_Velocity; // 0xb0
	private Boolean m_Dragging; // 0xb8
	private Boolean m_Scrolling; // 0xb9
	private Vector2 m_PrevPosition; // 0xbc
	private Bounds m_PrevContentBounds; // 0xc4
	private Bounds m_PrevViewBounds; // 0xdc
	private Boolean m_HasRebuiltLayout; // 0xf4
	private Boolean m_HSliderExpand; // 0xf5
	private Boolean m_VSliderExpand; // 0xf6
	private Single m_HSliderHeight; // 0xf8
	private Single m_VSliderWidth; // 0xfc
	private RectTransform m_Rect; // 0x100
	private RectTransform m_HorizontalScrollbarRect; // 0x108
	private RectTransform m_VerticalScrollbarRect; // 0x110
	private DrivenRectTransformTracker m_Tracker; // 0x118
	private readonly Vector3[] m_Corners; // 0x120

	public RectTransform content { get; set; }
	public Boolean horizontal { get; set; }
	public Boolean vertical { get; set; }
	public MovementType movementType { get; set; }
	public Single elasticity { get; set; }
	public Boolean inertia { get; set; }
	public Single decelerationRate { get; set; }
	public Single scrollSensitivity { get; set; }
	public RectTransform viewport { get; set; }
	public Scrollbar horizontalScrollbar { get; set; }
	public Scrollbar verticalScrollbar { get; set; }
	public ScrollbarVisibility horizontalScrollbarVisibility { get; set; }
	public ScrollbarVisibility verticalScrollbarVisibility { get; set; }
	public Single horizontalScrollbarSpacing { get; set; }
	public Single verticalScrollbarSpacing { get; set; }
	public ScrollRectEvent onValueChanged { get; set; }
	protected RectTransform viewRect { get; }
	public Vector2 velocity { get; set; }
	private RectTransform rectTransform { get; }
	public Vector2 normalizedPosition { get; set; }
	public Single horizontalNormalizedPosition { get; set; }
	public Single verticalNormalizedPosition { get; set; }
	private Boolean hScrollingNeeded { get; }
	private Boolean vScrollingNeeded { get; }
	public virtual Single minWidth { get; }
	public virtual Single preferredWidth { get; }
	public virtual Single flexibleWidth { get; }
	public virtual Single minHeight { get; }
	public virtual Single preferredHeight { get; }
	public virtual Single flexibleHeight { get; }
	public virtual Int32 layoutPriority { get; }

	// RVA: 0x6a6153c VA: 0x759907953c
	public RectTransform get_content() { }
	// RVA: 0x6a61544 VA: 0x7599079544
	public Void set_content(RectTransform value) { }
	// RVA: 0x6a6154c VA: 0x759907954c
	public Boolean get_horizontal() { }
	// RVA: 0x6a61554 VA: 0x7599079554
	public Void set_horizontal(Boolean value) { }
	// RVA: 0x6a61560 VA: 0x7599079560
	public Boolean get_vertical() { }
	// RVA: 0x6a61568 VA: 0x7599079568
	public Void set_vertical(Boolean value) { }
	// RVA: 0x6a61574 VA: 0x7599079574
	public MovementType get_movementType() { }
	// RVA: 0x6a6157c VA: 0x759907957c
	public Void set_movementType(MovementType value) { }
	// RVA: 0x6a61584 VA: 0x7599079584
	public Single get_elasticity() { }
	// RVA: 0x6a6158c VA: 0x759907958c
	public Void set_elasticity(Single value) { }
	// RVA: 0x6a61594 VA: 0x7599079594
	public Boolean get_inertia() { }
	// RVA: 0x6a6159c VA: 0x759907959c
	public Void set_inertia(Boolean value) { }
	// RVA: 0x6a615a8 VA: 0x75990795a8
	public Single get_decelerationRate() { }
	// RVA: 0x6a615b0 VA: 0x75990795b0
	public Void set_decelerationRate(Single value) { }
	// RVA: 0x6a615b8 VA: 0x75990795b8
	public Single get_scrollSensitivity() { }
	// RVA: 0x6a615c0 VA: 0x75990795c0
	public Void set_scrollSensitivity(Single value) { }
	// RVA: 0x6a615c8 VA: 0x75990795c8
	public RectTransform get_viewport() { }
	// RVA: 0x6a615d0 VA: 0x75990795d0
	public Void set_viewport(RectTransform value) { }
	// RVA: 0x6a616b4 VA: 0x75990796b4
	public Scrollbar get_horizontalScrollbar() { }
	// RVA: 0x6a616bc VA: 0x75990796bc
	public Void set_horizontalScrollbar(Scrollbar value) { }
	// RVA: 0x6a6184c VA: 0x759907984c
	public Scrollbar get_verticalScrollbar() { }
	// RVA: 0x6a61854 VA: 0x7599079854
	public Void set_verticalScrollbar(Scrollbar value) { }
	// RVA: 0x6a619e4 VA: 0x75990799e4
	public ScrollbarVisibility get_horizontalScrollbarVisibility() { }
	// RVA: 0x6a619ec VA: 0x75990799ec
	public Void set_horizontalScrollbarVisibility(ScrollbarVisibility value) { }
	// RVA: 0x6a619f4 VA: 0x75990799f4
	public ScrollbarVisibility get_verticalScrollbarVisibility() { }
	// RVA: 0x6a619fc VA: 0x75990799fc
	public Void set_verticalScrollbarVisibility(ScrollbarVisibility value) { }
	// RVA: 0x6a61a04 VA: 0x7599079a04
	public Single get_horizontalScrollbarSpacing() { }
	// RVA: 0x6a61a0c VA: 0x7599079a0c
	public Void set_horizontalScrollbarSpacing(Single value) { }
	// RVA: 0x6a61a9c VA: 0x7599079a9c
	public Single get_verticalScrollbarSpacing() { }
	// RVA: 0x6a61aa4 VA: 0x7599079aa4
	public Void set_verticalScrollbarSpacing(Single value) { }
	// RVA: 0x6a61aac VA: 0x7599079aac
	public ScrollRectEvent get_onValueChanged() { }
	// RVA: 0x6a61ab4 VA: 0x7599079ab4
	public Void set_onValueChanged(ScrollRectEvent value) { }
	// RVA: 0x6a61abc VA: 0x7599079abc
	protected RectTransform get_viewRect() { }
	// RVA: 0x6a61bcc VA: 0x7599079bcc
	public Vector2 get_velocity() { }
	// RVA: 0x6a61bd4 VA: 0x7599079bd4
	public Void set_velocity(Vector2 value) { }
	// RVA: 0x6a61bdc VA: 0x7599079bdc
	private RectTransform get_rectTransform() { }
	// RVA: 0x6a61c7c VA: 0x7599079c7c
	protected Void .ctor() { }
	// RVA: 0x6a61de0 VA: 0x7599079de0
	public virtual Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x6a62968 VA: 0x759907a968
	public virtual Void LayoutComplete() { }
	// RVA: 0x6a6296c VA: 0x759907a96c
	public virtual Void GraphicUpdateComplete() { }
	// RVA: 0x6a61e68 VA: 0x7599079e68
	private Void UpdateCachedData() { }
	// RVA: 0x6a62970 VA: 0x759907a970
	protected override Void OnEnable() { }
	// RVA: 0x6a62b1c VA: 0x759907ab1c
	protected override Void OnDisable() { }
	// RVA: 0x6a62d4c VA: 0x759907ad4c
	public override Boolean IsActive() { }
	// RVA: 0x6a62dcc VA: 0x759907adcc
	private Void EnsureLayoutHasRebuilt() { }
	// RVA: 0x6a62e40 VA: 0x759907ae40
	public virtual Void StopMovement() { }
	// RVA: 0x6a62e90 VA: 0x759907ae90
	public virtual Void OnScroll(PointerEventData data) { }
	// RVA: 0x6a63038 VA: 0x759907b038
	public virtual Void OnInitializePotentialDrag(PointerEventData eventData) { }
	// RVA: 0x6a63098 VA: 0x759907b098
	public virtual Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x6a631c4 VA: 0x759907b1c4
	public virtual Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x6a631e4 VA: 0x759907b1e4
	public virtual Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x6a63444 VA: 0x759907b444
	protected virtual Void SetContentAnchoredPosition(Vector2 position) { }
	// RVA: 0x6a634f8 VA: 0x759907b4f8
	protected virtual Void LateUpdate() { }
	// RVA: 0x6a6288c VA: 0x759907a88c
	protected Void UpdatePrevData() { }
	// RVA: 0x6a626b4 VA: 0x759907a6b4
	private Void UpdateScrollbars(Vector2 offset) { }
	// RVA: 0x6a63a8c VA: 0x759907ba8c
	public Vector2 get_normalizedPosition() { }
	// RVA: 0x6a63db4 VA: 0x759907bdb4
	public Void set_normalizedPosition(Vector2 value) { }
	// RVA: 0x6a63afc VA: 0x759907bafc
	public Single get_horizontalNormalizedPosition() { }
	// RVA: 0x6a63dfc VA: 0x759907bdfc
	public Void set_horizontalNormalizedPosition(Single value) { }
	// RVA: 0x6a63c58 VA: 0x759907bc58
	public Single get_verticalNormalizedPosition() { }
	// RVA: 0x6a63e10 VA: 0x759907be10
	public Void set_verticalNormalizedPosition(Single value) { }
	// RVA: 0x6a63e24 VA: 0x759907be24
	private Void SetHorizontalNormalizedPosition(Single value) { }
	// RVA: 0x6a63e38 VA: 0x759907be38
	private Void SetVerticalNormalizedPosition(Single value) { }
	// RVA: 0x6a63e4c VA: 0x759907be4c
	protected virtual Void SetNormalizedPosition(Single value, Int32 axis) { }
	// RVA: 0x6a63408 VA: 0x759907b408
	private static Single RubberDelta(Single overStretching, Single viewSize) { }
	// RVA: 0x6a64144 VA: 0x759907c144
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x6a64148 VA: 0x759907c148
	private Boolean get_hScrollingNeeded() { }
	// RVA: 0x6a641a4 VA: 0x759907c1a4
	private Boolean get_vScrollingNeeded() { }
	// RVA: 0x6a64200 VA: 0x759907c200
	public virtual Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x6a64204 VA: 0x759907c204
	public virtual Void CalculateLayoutInputVertical() { }
	// RVA: 0x6a64208 VA: 0x759907c208
	public virtual Single get_minWidth() { }
	// RVA: 0x6a64210 VA: 0x759907c210
	public virtual Single get_preferredWidth() { }
	// RVA: 0x6a64218 VA: 0x759907c218
	public virtual Single get_flexibleWidth() { }
	// RVA: 0x6a64220 VA: 0x759907c220
	public virtual Single get_minHeight() { }
	// RVA: 0x6a64228 VA: 0x759907c228
	public virtual Single get_preferredHeight() { }
	// RVA: 0x6a64230 VA: 0x759907c230
	public virtual Single get_flexibleHeight() { }
	// RVA: 0x6a64238 VA: 0x759907c238
	public virtual Int32 get_layoutPriority() { }
	// RVA: 0x6a64240 VA: 0x759907c240
	public virtual Void SetLayoutHorizontal() { }
	// RVA: 0x6a64894 VA: 0x759907c894
	public virtual Void SetLayoutVertical() { }
	// RVA: 0x6a63abc VA: 0x759907babc
	private Void UpdateScrollbarVisibility() { }
	// RVA: 0x6a64bc4 VA: 0x759907cbc4
	private static Void UpdateOneScrollbarVisibility(Boolean xScrollingNeeded, Boolean xAxisEnabled, ScrollbarVisibility scrollbarVisibility, Scrollbar scrollbar) { }
	// RVA: 0x6a64970 VA: 0x759907c970
	private Void UpdateScrollbarLayout() { }
	// RVA: 0x6a62200 VA: 0x759907a200
	protected Void UpdateBounds() { }
	// RVA: 0x6a64cb8 VA: 0x759907ccb8
	internal static Void AdjustBounds(ref Bounds viewBounds, ref Vector2 contentPivot, ref Vector3 contentSize, ref Vector3 contentPos) { }
	// RVA: 0x6a64798 VA: 0x759907c798
	private Bounds GetBounds() { }
	// RVA: 0x6a64d64 VA: 0x759907cd64
	internal static Bounds InternalGetBounds(Vector3[] corners, ref Matrix4x4 viewWorldToLocalMatrix) { }
	// RVA: 0x6a63008 VA: 0x759907b008
	private Vector2 CalculateOffset(Vector2 delta) { }
	// RVA: 0x6a64ebc VA: 0x759907cebc
	internal static Vector2 InternalCalculateOffset(ref Bounds viewBounds, ref Bounds contentBounds, Boolean horizontal, Boolean vertical, MovementType movementType, ref Vector2 delta) { }
	// RVA: 0x6a61a14 VA: 0x7599079a14
	protected Void SetDirty() { }
	// RVA: 0x6a615ec VA: 0x75990795ec
	protected Void SetDirtyCaching() { }
	// RVA: 0x6a65040 VA: 0x759907d040
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
}
```