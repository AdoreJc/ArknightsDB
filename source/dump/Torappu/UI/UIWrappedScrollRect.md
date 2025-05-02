# UIWrappedScrollRect

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform m_Content`

- `Boolean m_Horizontal`

- `Boolean m_Vertical`

- `MovementType m_MovementType`

- `Single m_Elasticity`

- `Boolean m_Inertia`

- `Single m_DecelerationRate`

- `Boolean m_Friction`

- `Single m_FrictionValue`

- `Single m_ScrollSensitivity`

- `RectTransform m_Viewport`

- `Scrollbar m_HorizontalScrollbar`

- `Scrollbar m_VerticalScrollbar`

- `ScrollbarVisibility m_HorizontalScrollbarVisibility`

- `ScrollbarVisibility m_VerticalScrollbarVisibility`

- `Single m_HorizontalScrollbarSpacing`

- `Single m_VerticalScrollbarSpacing`

- `ScrollRectEvent m_OnValueChanged`

- `FlingConfig _flingConfig`

- `UIFlingGesture m_fling`

- `Int32 m_dragPointerId`

- `Camera m_dragCamera`

- `NormPosRequest m_normPosDuringInactive`

- `Boolean _nestedInParent`

- `DragDelegate m_dragDelegate`

- `InvokeWhenUnlock m_findDelegateLatch`

- `Vector2 m_PointerStartLocalCursor`

- `Vector2 m_ContentStartPosition`

- `RectTransform m_ViewRect`

- `Bounds m_ContentBounds`

- `Bounds m_ViewBounds`

- `Vector2 m_Velocity`

- `Boolean m_Dragging`

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

- `Boolean m_allowScroll`

- `Action eventOnManuallyDragged`


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

- `Boolean nestedInParent`

- `RectTransform viewRect`

- `Vector2 velocity`

- `Boolean isDragging`

- `RectTransform rectTransform`

- `Boolean allowScroll`

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

- `Void _LateUpdateApplyFling(Vector2, Single)`

- `Boolean get_nestedInParent()`

- `Void EnableNestedInParent()`

- `Void SetDragDelegate(IDragHandler)`

- `Void _FindScrollDelegateInParent()`

- `RectTransform get_viewRect()`

- `Vector2 get_velocity()`

- `Void set_velocity(Vector2)`

- `Boolean get_isDragging()`

- `RectTransform get_rectTransform()`

- `Void UpdateCachedData()`

- `Void EnsureLayoutHasRebuilt()`

- `Boolean get_allowScroll()`

- `Void set_allowScroll(Boolean)`

- `Void CancelCurrentDrag()`

- `Void _StopDraggingIfMultiTouch()`

- `Void add_eventOnManuallyDragged(Action)`

- `Void remove_eventOnManuallyDragged(Action)`

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

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnTransformParentChanged()`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`

- `Boolean <>xLuaBaseProxy_IsActive()`

- `Void <>xLuaBaseProxy_OnRectTransformDimensionsChange()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIWrappedScrollRect : UIBehaviour, IInitializePotentialDragHandler, IEventSystemHandler, IBeginDragHandler, IEndDragHandler, IDragHandler, IScrollHandler, ICanvasElement, ILayoutElement, ILayoutGroup, ILayoutController
{
	private const Single DRAG_DIR_THRESHOLD; // 0x0
	private RectTransform m_Content; // 0x18
	private Boolean m_Horizontal; // 0x20
	private Boolean m_Vertical; // 0x21
	private MovementType m_MovementType; // 0x24
	private Single m_Elasticity; // 0x28
	private Boolean m_Inertia; // 0x2c
	private Single m_DecelerationRate; // 0x30
	private Boolean m_Friction; // 0x34
	private Single m_FrictionValue; // 0x38
	private Single m_ScrollSensitivity; // 0x3c
	private RectTransform m_Viewport; // 0x40
	private Scrollbar m_HorizontalScrollbar; // 0x48
	private Scrollbar m_VerticalScrollbar; // 0x50
	private ScrollbarVisibility m_HorizontalScrollbarVisibility; // 0x58
	private ScrollbarVisibility m_VerticalScrollbarVisibility; // 0x5c
	private Single m_HorizontalScrollbarSpacing; // 0x60
	private Single m_VerticalScrollbarSpacing; // 0x64
	private ScrollRectEvent m_OnValueChanged; // 0x68
	private FlingConfig _flingConfig; // 0x70
	private UIFlingGesture m_fling; // 0x78
	private Int32 m_dragPointerId; // 0x80
	private Camera m_dragCamera; // 0x88
	private NormPosRequest m_normPosDuringInactive; // 0x90
	private Boolean _nestedInParent; // 0xa0
	private DragDelegate m_dragDelegate; // 0xa8
	private InvokeWhenUnlock m_findDelegateLatch; // 0xb0
	private Vector2 m_PointerStartLocalCursor; // 0xb8
	protected Vector2 m_ContentStartPosition; // 0xc0
	private RectTransform m_ViewRect; // 0xc8
	protected Bounds m_ContentBounds; // 0xd0
	private Bounds m_ViewBounds; // 0xe8
	private Vector2 m_Velocity; // 0x100
	private Boolean m_Dragging; // 0x108
	private Vector2 m_PrevPosition; // 0x10c
	private Bounds m_PrevContentBounds; // 0x114
	private Bounds m_PrevViewBounds; // 0x12c
	private Boolean m_HasRebuiltLayout; // 0x144
	private Boolean m_HSliderExpand; // 0x145
	private Boolean m_VSliderExpand; // 0x146
	private Single m_HSliderHeight; // 0x148
	private Single m_VSliderWidth; // 0x14c
	private RectTransform m_Rect; // 0x150
	private RectTransform m_HorizontalScrollbarRect; // 0x158
	private RectTransform m_VerticalScrollbarRect; // 0x160
	private DrivenRectTransformTracker m_Tracker; // 0x168
	private Boolean m_allowScroll; // 0x169
	private Action eventOnManuallyDragged; // 0x170
	private readonly Vector3[] m_Corners; // 0x178
	private static DelegateBridge __Hotfix0_get_content; // 0x0
	private static DelegateBridge __Hotfix0_set_content; // 0x8
	private static DelegateBridge __Hotfix0_get_horizontal; // 0x10
	private static DelegateBridge __Hotfix0_set_horizontal; // 0x18
	private static DelegateBridge __Hotfix0_get_vertical; // 0x20
	private static DelegateBridge __Hotfix0_set_vertical; // 0x28
	private static DelegateBridge __Hotfix0_get_movementType; // 0x30
	private static DelegateBridge __Hotfix0_set_movementType; // 0x38
	private static DelegateBridge __Hotfix0_get_elasticity; // 0x40
	private static DelegateBridge __Hotfix0_set_elasticity; // 0x48
	private static DelegateBridge __Hotfix0_get_inertia; // 0x50
	private static DelegateBridge __Hotfix0_set_inertia; // 0x58
	private static DelegateBridge __Hotfix0_get_decelerationRate; // 0x60
	private static DelegateBridge __Hotfix0_set_decelerationRate; // 0x68
	private static DelegateBridge __Hotfix0_get_scrollSensitivity; // 0x70
	private static DelegateBridge __Hotfix0_set_scrollSensitivity; // 0x78
	private static DelegateBridge __Hotfix0_get_viewport; // 0x80
	private static DelegateBridge __Hotfix0_set_viewport; // 0x88
	private static DelegateBridge __Hotfix0_get_horizontalScrollbar; // 0x90
	private static DelegateBridge __Hotfix0_set_horizontalScrollbar; // 0x98
	private static DelegateBridge __Hotfix0_get_verticalScrollbar; // 0xa0
	private static DelegateBridge __Hotfix0_set_verticalScrollbar; // 0xa8
	private static DelegateBridge __Hotfix0_get_horizontalScrollbarVisibility; // 0xb0
	private static DelegateBridge __Hotfix0_set_horizontalScrollbarVisibility; // 0xb8
	private static DelegateBridge __Hotfix0_get_verticalScrollbarVisibility; // 0xc0
	private static DelegateBridge __Hotfix0_set_verticalScrollbarVisibility; // 0xc8
	private static DelegateBridge __Hotfix0_get_horizontalScrollbarSpacing; // 0xd0
	private static DelegateBridge __Hotfix0_set_horizontalScrollbarSpacing; // 0xd8
	private static DelegateBridge __Hotfix0_get_verticalScrollbarSpacing; // 0xe0
	private static DelegateBridge __Hotfix0_set_verticalScrollbarSpacing; // 0xe8
	private static DelegateBridge __Hotfix0_get_onValueChanged; // 0xf0
	private static DelegateBridge __Hotfix0_set_onValueChanged; // 0xf8
	private static DelegateBridge __Hotfix0__LateUpdateApplyFling; // 0x100
	private static DelegateBridge __Hotfix0_get_nestedInParent; // 0x108
	private static DelegateBridge __Hotfix0_EnableNestedInParent; // 0x110
	private static DelegateBridge __Hotfix0_SetDragDelegate; // 0x118
	private static DelegateBridge __Hotfix0_Start; // 0x120
	private static DelegateBridge __Hotfix0_OnTransformParentChanged; // 0x128
	private static DelegateBridge __Hotfix0__FindScrollDelegateInParent; // 0x130
	private static DelegateBridge __Hotfix0_get_viewRect; // 0x138
	private static DelegateBridge __Hotfix0_get_velocity; // 0x140
	private static DelegateBridge __Hotfix0_set_velocity; // 0x148
	private static DelegateBridge __Hotfix0_get_isDragging; // 0x150
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x158
	private static DelegateBridge __Hotfix0_Rebuild; // 0x160
	private static DelegateBridge __Hotfix0_LayoutComplete; // 0x168
	private static DelegateBridge __Hotfix0_GraphicUpdateComplete; // 0x170
	private static DelegateBridge __Hotfix0_UpdateCachedData; // 0x178
	private static DelegateBridge __Hotfix0_OnEnable; // 0x180
	private static DelegateBridge __Hotfix0_OnDisable; // 0x188
	private static DelegateBridge __Hotfix0_IsActive; // 0x190
	private static DelegateBridge __Hotfix0_EnsureLayoutHasRebuilt; // 0x198
	private static DelegateBridge __Hotfix0_StopMovement; // 0x1a0
	private static DelegateBridge __Hotfix0_OnScroll; // 0x1a8
	private static DelegateBridge __Hotfix0_OnInitializePotentialDrag; // 0x1b0
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x1b8
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x1c0
	private static DelegateBridge __Hotfix0_OnDrag; // 0x1c8
	private static DelegateBridge __Hotfix0_get_allowScroll; // 0x1d0
	private static DelegateBridge __Hotfix0_set_allowScroll; // 0x1d8
	private static DelegateBridge __Hotfix0_CancelCurrentDrag; // 0x1e0
	private static DelegateBridge __Hotfix0__StopDraggingIfMultiTouch; // 0x1e8
	private static DelegateBridge __Hotfix0_add_eventOnManuallyDragged; // 0x1f0
	private static DelegateBridge __Hotfix0_remove_eventOnManuallyDragged; // 0x1f8
	private static DelegateBridge __Hotfix0_SetContentAnchoredPosition; // 0x200
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x208
	private static DelegateBridge __Hotfix0_ApplyDeceleration; // 0x210
	private static DelegateBridge __Hotfix0_UpdatePrevData; // 0x218
	private static DelegateBridge __Hotfix0_UpdateScrollbars; // 0x220
	private static DelegateBridge __Hotfix0_get_normalizedPosition; // 0x228
	private static DelegateBridge __Hotfix0_set_normalizedPosition; // 0x230
	private static DelegateBridge __Hotfix0_get_horizontalNormalizedPosition; // 0x238
	private static DelegateBridge __Hotfix0_set_horizontalNormalizedPosition; // 0x240
	private static DelegateBridge __Hotfix0_get_verticalNormalizedPosition; // 0x248
	private static DelegateBridge __Hotfix0_set_verticalNormalizedPosition; // 0x250
	private static DelegateBridge __Hotfix0_SetHorizontalNormalizedPosition; // 0x258
	private static DelegateBridge __Hotfix0_SetVerticalNormalizedPosition; // 0x260
	private static DelegateBridge __Hotfix0_SetNormalizedPosition; // 0x268
	private static DelegateBridge __Hotfix0_RubberDelta; // 0x270
	private static DelegateBridge __Hotfix0_OnRectTransformDimensionsChange; // 0x278
	private static DelegateBridge __Hotfix0_get_hScrollingNeeded; // 0x280
	private static DelegateBridge __Hotfix0_get_vScrollingNeeded; // 0x288
	private static DelegateBridge __Hotfix0_CalculateLayoutInputHorizontal; // 0x290
	private static DelegateBridge __Hotfix0_CalculateLayoutInputVertical; // 0x298
	private static DelegateBridge __Hotfix0_get_minWidth; // 0x2a0
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x2a8
	private static DelegateBridge __Hotfix0_get_flexibleWidth; // 0x2b0
	private static DelegateBridge __Hotfix0_get_minHeight; // 0x2b8
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x2c0
	private static DelegateBridge __Hotfix0_get_flexibleHeight; // 0x2c8
	private static DelegateBridge __Hotfix0_get_layoutPriority; // 0x2d0
	private static DelegateBridge __Hotfix0_SetLayoutHorizontal; // 0x2d8
	private static DelegateBridge __Hotfix0_SetLayoutVertical; // 0x2e0
	private static DelegateBridge __Hotfix0_UpdateScrollbarVisibility; // 0x2e8
	private static DelegateBridge __Hotfix0_UpdateOneScrollbarVisibility; // 0x2f0
	private static DelegateBridge __Hotfix0_UpdateScrollbarLayout; // 0x2f8
	private static DelegateBridge __Hotfix0_UpdateBounds; // 0x300
	private static DelegateBridge __Hotfix0_AdjustBounds; // 0x308
	private static DelegateBridge __Hotfix0_GetBounds; // 0x310
	private static DelegateBridge __Hotfix0_InternalGetBounds; // 0x318
	private static DelegateBridge __Hotfix0_CalculateOffset; // 0x320
	private static DelegateBridge __Hotfix0_InternalCalculateOffset; // 0x328
	private static DelegateBridge __Hotfix0_SetDirty; // 0x330
	private static DelegateBridge __Hotfix0_SetDirtyCaching; // 0x338
	private static DelegateBridge _c__Hotfix0_ctor; // 0x340
	private static DelegateBridge __Hotfix0_UnityEngine.UI.ICanvasElement.get_transform; // 0x348

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
	public Boolean nestedInParent { get; }
	protected RectTransform viewRect { get; }
	public Vector2 velocity { get; set; }
	public Boolean isDragging { get; }
	private RectTransform rectTransform { get; }
	public Boolean allowScroll { get; set; }
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

	// RVA: 0x2259940 VA: 0x7594871940
	public RectTransform get_content() { }
	// RVA: 0x22599a8 VA: 0x75948719a8
	public Void set_content(RectTransform value) { }
	// RVA: 0x2259a2c VA: 0x7594871a2c
	public Boolean get_horizontal() { }
	// RVA: 0x2259a94 VA: 0x7594871a94
	public Void set_horizontal(Boolean value) { }
	// RVA: 0x2259b14 VA: 0x7594871b14
	public Boolean get_vertical() { }
	// RVA: 0x2259b7c VA: 0x7594871b7c
	public Void set_vertical(Boolean value) { }
	// RVA: 0x2259bfc VA: 0x7594871bfc
	public MovementType get_movementType() { }
	// RVA: 0x2259c64 VA: 0x7594871c64
	public Void set_movementType(MovementType value) { }
	// RVA: 0x2259ce0 VA: 0x7594871ce0
	public Single get_elasticity() { }
	// RVA: 0x2259d48 VA: 0x7594871d48
	public Void set_elasticity(Single value) { }
	// RVA: 0x2259dc4 VA: 0x7594871dc4
	public Boolean get_inertia() { }
	// RVA: 0x2259e2c VA: 0x7594871e2c
	public Void set_inertia(Boolean value) { }
	// RVA: 0x2259eac VA: 0x7594871eac
	public Single get_decelerationRate() { }
	// RVA: 0x2259f14 VA: 0x7594871f14
	public Void set_decelerationRate(Single value) { }
	// RVA: 0x2259f90 VA: 0x7594871f90
	public Single get_scrollSensitivity() { }
	// RVA: 0x2259ff8 VA: 0x7594871ff8
	public Void set_scrollSensitivity(Single value) { }
	// RVA: 0x225a074 VA: 0x7594872074
	public RectTransform get_viewport() { }
	// RVA: 0x225a0dc VA: 0x75948720dc
	public Void set_viewport(RectTransform value) { }
	// RVA: 0x225a258 VA: 0x7594872258
	public Scrollbar get_horizontalScrollbar() { }
	// RVA: 0x225a2c0 VA: 0x75948722c0
	public Void set_horizontalScrollbar(Scrollbar value) { }
	// RVA: 0x225a498 VA: 0x7594872498
	public Scrollbar get_verticalScrollbar() { }
	// RVA: 0x225a500 VA: 0x7594872500
	public Void set_verticalScrollbar(Scrollbar value) { }
	// RVA: 0x225a6d8 VA: 0x75948726d8
	public ScrollbarVisibility get_horizontalScrollbarVisibility() { }
	// RVA: 0x225a740 VA: 0x7594872740
	public Void set_horizontalScrollbarVisibility(ScrollbarVisibility value) { }
	// RVA: 0x225a7c0 VA: 0x75948727c0
	public ScrollbarVisibility get_verticalScrollbarVisibility() { }
	// RVA: 0x225a828 VA: 0x7594872828
	public Void set_verticalScrollbarVisibility(ScrollbarVisibility value) { }
	// RVA: 0x225a8a8 VA: 0x75948728a8
	public Single get_horizontalScrollbarSpacing() { }
	// RVA: 0x225a910 VA: 0x7594872910
	public Void set_horizontalScrollbarSpacing(Single value) { }
	// RVA: 0x225aa50 VA: 0x7594872a50
	public Single get_verticalScrollbarSpacing() { }
	// RVA: 0x225aab8 VA: 0x7594872ab8
	public Void set_verticalScrollbarSpacing(Single value) { }
	// RVA: 0x225ab38 VA: 0x7594872b38
	public ScrollRectEvent get_onValueChanged() { }
	// RVA: 0x225aba0 VA: 0x7594872ba0
	public Void set_onValueChanged(ScrollRectEvent value) { }
	// RVA: 0x225ac24 VA: 0x7594872c24
	private Void _LateUpdateApplyFling(Vector2 curDragLocalPos, Single deltaTime) { }
	// RVA: 0x225ae00 VA: 0x7594872e00
	public Boolean get_nestedInParent() { }
	// RVA: 0x225ae68 VA: 0x7594872e68
	public Void EnableNestedInParent() { }
	// RVA: 0x225af48 VA: 0x7594872f48
	public Void SetDragDelegate(IDragHandler target) { }
	// RVA: 0x225aff0 VA: 0x7594872ff0
	protected override Void Start() { }
	// RVA: 0x225b0d8 VA: 0x75948730d8
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x225b1bc VA: 0x75948731bc
	private Void _FindScrollDelegateInParent() { }
	// RVA: 0x225b234 VA: 0x7594873234
	protected RectTransform get_viewRect() { }
	// RVA: 0x225b380 VA: 0x7594873380
	public Vector2 get_velocity() { }
	// RVA: 0x225b3e8 VA: 0x75948733e8
	public Void set_velocity(Vector2 value) { }
	// RVA: 0x225b470 VA: 0x7594873470
	public Boolean get_isDragging() { }
	// RVA: 0x225b4d8 VA: 0x75948734d8
	private RectTransform get_rectTransform() { }
	// RVA: 0x225b5b0 VA: 0x75948735b0
	public virtual Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x225c2ac VA: 0x75948742ac
	public virtual Void LayoutComplete() { }
	// RVA: 0x225c310 VA: 0x7594874310
	public virtual Void GraphicUpdateComplete() { }
	// RVA: 0x225b69c VA: 0x759487369c
	private Void UpdateCachedData() { }
	// RVA: 0x225c374 VA: 0x7594874374
	protected override Void OnEnable() { }
	// RVA: 0x225c6a8 VA: 0x75948746a8
	protected override Void OnDisable() { }
	// RVA: 0x225c9cc VA: 0x75948749cc
	public override Boolean IsActive() { }
	// RVA: 0x225ca84 VA: 0x7594874a84
	private Void EnsureLayoutHasRebuilt() { }
	// RVA: 0x225cb30 VA: 0x7594874b30
	public virtual Void StopMovement() { }
	// RVA: 0x225cbcc VA: 0x7594874bcc
	public virtual Void OnScroll(PointerEventData data) { }
	// RVA: 0x225ce48 VA: 0x7594874e48
	public virtual Void OnInitializePotentialDrag(PointerEventData eventData) { }
	// RVA: 0x225cf28 VA: 0x7594874f28
	public virtual Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x225d110 VA: 0x7594875110
	public virtual Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x225d1c8 VA: 0x75948751c8
	public virtual Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x225d5b4 VA: 0x75948755b4
	public Boolean get_allowScroll() { }
	// RVA: 0x225d61c VA: 0x759487561c
	public Void set_allowScroll(Boolean value) { }
	// RVA: 0x225c91c VA: 0x759487491c
	public Void CancelCurrentDrag() { }
	// RVA: 0x225d474 VA: 0x7594875474
	private Void _StopDraggingIfMultiTouch() { }
	// RVA: 0x225d6a0 VA: 0x75948756a0
	public Void add_eventOnManuallyDragged(Action value) { }
	// RVA: 0x225d780 VA: 0x7594875780
	public Void remove_eventOnManuallyDragged(Action value) { }
	// RVA: 0x225d860 VA: 0x7594875860
	protected virtual Void SetContentAnchoredPosition(Vector2 position) { }
	// RVA: 0x225d97c VA: 0x759487597c
	protected virtual Void LateUpdate() { }
	// RVA: 0x225dff0 VA: 0x7594875ff0
	private static Void ApplyDeceleration(DecelerationConfig config, out Vector2 velocity) { }
	// RVA: 0x225c188 VA: 0x7594874188
	protected Void UpdatePrevData() { }
	// RVA: 0x225bf5c VA: 0x7594873f5c
	private Void UpdateScrollbars(Vector2 offset) { }
	// RVA: 0x225e2a0 VA: 0x75948762a0
	public Vector2 get_normalizedPosition() { }
	// RVA: 0x225e5e0 VA: 0x75948765e0
	public Void set_normalizedPosition(Vector2 value) { }
	// RVA: 0x225e3c0 VA: 0x75948763c0
	public Single get_horizontalNormalizedPosition() { }
	// RVA: 0x225e694 VA: 0x7594876694
	public Void set_horizontalNormalizedPosition(Single value) { }
	// RVA: 0x225e4d0 VA: 0x75948764d0
	public Single get_verticalNormalizedPosition() { }
	// RVA: 0x225e724 VA: 0x7594876724
	public Void set_verticalNormalizedPosition(Single value) { }
	// RVA: 0x225c588 VA: 0x7594874588
	private Void SetHorizontalNormalizedPosition(Single value) { }
	// RVA: 0x225c618 VA: 0x7594874618
	private Void SetVerticalNormalizedPosition(Single value) { }
	// RVA: 0x225e7b4 VA: 0x75948767b4
	protected virtual Void SetNormalizedPosition(Single value, Int32 axis) { }
	// RVA: 0x225d504 VA: 0x7594875504
	private static Single RubberDelta(Single overStretching, Single viewSize) { }
	// RVA: 0x225eb60 VA: 0x7594876b60
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x225ebc8 VA: 0x7594876bc8
	private Boolean get_hScrollingNeeded() { }
	// RVA: 0x225ec78 VA: 0x7594876c78
	private Boolean get_vScrollingNeeded() { }
	// RVA: 0x225ed28 VA: 0x7594876d28
	public virtual Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x225ed8c VA: 0x7594876d8c
	public virtual Void CalculateLayoutInputVertical() { }
	// RVA: 0x225edf0 VA: 0x7594876df0
	public virtual Single get_minWidth() { }
	// RVA: 0x225ee58 VA: 0x7594876e58
	public virtual Single get_preferredWidth() { }
	// RVA: 0x225eec0 VA: 0x7594876ec0
	public virtual Single get_flexibleWidth() { }
	// RVA: 0x225ef28 VA: 0x7594876f28
	public virtual Single get_minHeight() { }
	// RVA: 0x225ef90 VA: 0x7594876f90
	public virtual Single get_preferredHeight() { }
	// RVA: 0x225eff8 VA: 0x7594876ff8
	public virtual Single get_flexibleHeight() { }
	// RVA: 0x225f060 VA: 0x7594877060
	public virtual Int32 get_layoutPriority() { }
	// RVA: 0x225f0c8 VA: 0x75948770c8
	public virtual Void SetLayoutHorizontal() { }
	// RVA: 0x225f798 VA: 0x7594877798
	public virtual Void SetLayoutVertical() { }
	// RVA: 0x225e328 VA: 0x7594876328
	private Void UpdateScrollbarVisibility() { }
	// RVA: 0x225fb58 VA: 0x7594877b58
	private static Void UpdateOneScrollbarVisibility(Boolean xScrollingNeeded, Boolean xAxisEnabled, ScrollbarVisibility scrollbarVisibility, Scrollbar scrollbar) { }
	// RVA: 0x225f8c8 VA: 0x75948778c8
	private Void UpdateScrollbarLayout() { }
	// RVA: 0x225ba70 VA: 0x7594873a70
	protected Void UpdateBounds() { }
	// RVA: 0x225fc98 VA: 0x7594877c98
	internal static Void AdjustBounds(ref Bounds viewBounds, ref Vector2 contentPivot, ref Vector3 contentSize, ref Vector3 contentPos) { }
	// RVA: 0x225f664 VA: 0x7594877664
	private Bounds GetBounds() { }
	// RVA: 0x225fdb4 VA: 0x7594877db4
	internal static Bounds InternalGetBounds(Vector3[] corners, ref Matrix4x4 viewWorldToLocalMatrix) { }
	// RVA: 0x225cd9c VA: 0x7594874d9c
	private Vector2 CalculateOffset(Vector2 delta) { }
	// RVA: 0x225ff64 VA: 0x7594877f64
	internal static Vector2 InternalCalculateOffset(ref Bounds viewBounds, ref Bounds contentBounds, Boolean horizontal, Boolean vertical, MovementType movementType, ref Vector2 delta) { }
	// RVA: 0x225a990 VA: 0x7594872990
	protected Void SetDirty() { }
	// RVA: 0x225a168 VA: 0x7594872168
	protected Void SetDirtyCaching() { }
	// RVA: 0x2260150 VA: 0x7594878150
	public Void .ctor() { }
	// RVA: 0x22603c4 VA: 0x75948783c4
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
	// RVA: 0x2260430 VA: 0x7594878430
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x2260438 VA: 0x7594878438
	private Void <>xLuaBaseProxy_OnTransformParentChanged() { }
	// RVA: 0x2260440 VA: 0x7594878440
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x2260448 VA: 0x7594878448
	private Void <>xLuaBaseProxy_OnDisable() { }
	// RVA: 0x2260450 VA: 0x7594878450
	private Boolean <>xLuaBaseProxy_IsActive() { }
	// RVA: 0x2260458 VA: 0x7594878458
	private Void <>xLuaBaseProxy_OnRectTransformDimensionsChange() { }
}
```