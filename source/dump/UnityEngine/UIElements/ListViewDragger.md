# ListViewDragger

**Namespace:** `UnityEngine.UIElements`


## Fields

- `DragPosition m_LastDragPosition`

- `VisualElement m_DragHoverBar`

- `VisualElement m_DragHoverItemMarker`

- `VisualElement m_DragHoverSiblingMarker`

- `Single m_LeftIndentation`

- `Single m_SiblingBottom`

- `ICollectionDragAndDropController <dragAndDropController>k__BackingField`


## Properties

- `BaseVerticalCollectionView targetView`

- `ScrollView targetScrollView`

- `ICollectionDragAndDropController dragAndDropController`


## Methods

- `BaseVerticalCollectionView get_targetView()`

- `ScrollView get_targetScrollView()`

- `ICollectionDragAndDropController get_dragAndDropController()`

- `Void set_dragAndDropController(ICollectionDragAndDropController)`

- `DragVisualMode GetVisualMode(Vector3, ref)`

- `Void ApplyDragAndDropUI(DragPosition)`

- `Void HandleTreePosition(Vector2, ref)`

- `Void HandleSiblingInsertionAtAvailableDepthsAndChangeTargetIfNeeded(ref, Vector2)`

- `Void GetPreviousAndNextItemsIgnoringDraggedItems(Int32, out, out)`

- `DragAndDropArgs MakeDragAndDropArgs(DragPosition)`

- `Single GetHoverBarTopPosition(ReusableCollectionItem)`

- `Void PlaceHoverBarAtElement(ReusableCollectionItem)`

- `Void PlaceHoverBarAt(Single, Single, Single)`

- `ReusableCollectionItem GetRecycledItem(Vector3)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ListViewDragger : DragEventsProcessor
{
	private DragPosition m_LastDragPosition; // 0x30
	private VisualElement m_DragHoverBar; // 0x50
	private VisualElement m_DragHoverItemMarker; // 0x58
	private VisualElement m_DragHoverSiblingMarker; // 0x60
	private Single m_LeftIndentation; // 0x68
	private Single m_SiblingBottom; // 0x6c
	private ICollectionDragAndDropController <dragAndDropController>k__BackingField; // 0x70

	protected BaseVerticalCollectionView targetView { get; }
	protected ScrollView targetScrollView { get; }
	public ICollectionDragAndDropController dragAndDropController { get; set; }

	// RVA: 0x69d723c VA: 0x7598fef23c
	protected BaseVerticalCollectionView get_targetView() { }
	// RVA: 0x69d72b8 VA: 0x7598fef2b8
	protected ScrollView get_targetScrollView() { }
	// RVA: 0x69d72d4 VA: 0x7598fef2d4
	public ICollectionDragAndDropController get_dragAndDropController() { }
	// RVA: 0x69d72dc VA: 0x7598fef2dc
	public Void set_dragAndDropController(ICollectionDragAndDropController value) { }
	// RVA: 0x69d72e4 VA: 0x7598fef2e4
	public Void .ctor(BaseVerticalCollectionView listView) { }
	// RVA: 0x69d72f0 VA: 0x7598fef2f0
	protected override Boolean CanStartDrag(Vector3 pointerPosition) { }
	// RVA: 0x69d78c4 VA: 0x7598fef8c4
	protected internal override StartDragArgs StartDrag(Vector3 pointerPosition) { }
	// RVA: 0x69d7ae4 VA: 0x7598fefae4
	protected internal override Void UpdateDrag(Vector3 pointerPosition) { }
	// RVA: 0x69d7ca4 VA: 0x7598fefca4
	private DragVisualMode GetVisualMode(Vector3 pointerPosition, ref DragPosition dragPosition) { }
	// RVA: 0x69d8934 VA: 0x7598ff0934
	protected internal override Void OnDrop(Vector3 pointerPosition) { }
	// RVA: 0x69d7dec VA: 0x7598fefdec
	internal Void HandleDragAndScroll(Vector2 pointerPosition) { }
	// RVA: 0x69d8028 VA: 0x7598ff0028
	protected Void ApplyDragAndDropUI(DragPosition dragPosition) { }
	// RVA: 0x69d962c VA: 0x7598ff162c
	protected virtual Boolean TryGetDragPosition(Vector2 pointerPosition, ref DragPosition dragPosition) { }
	// RVA: 0x69d9958 VA: 0x7598ff1958
	private Void HandleTreePosition(Vector2 pointerPosition, ref DragPosition dragPosition) { }
	// RVA: 0x69d9a68 VA: 0x7598ff1a68
	private Void HandleSiblingInsertionAtAvailableDepthsAndChangeTargetIfNeeded(ref DragPosition dragPosition, Vector2 pointerPosition) { }
	// RVA: 0x69da004 VA: 0x7598ff2004
	private Void GetPreviousAndNextItemsIgnoringDraggedItems(Int32 insertAtIndex, out Int32 previousItemId, out Int32 nextItemId) { }
	// RVA: 0x69d87e8 VA: 0x7598ff07e8
	protected DragAndDropArgs MakeDragAndDropArgs(DragPosition dragPosition) { }
	// RVA: 0x69da27c VA: 0x7598ff227c
	private Single GetHoverBarTopPosition(ReusableCollectionItem item) { }
	// RVA: 0x69d9610 VA: 0x7598ff1610
	private Void PlaceHoverBarAtElement(ReusableCollectionItem item) { }
	// RVA: 0x69d8c50 VA: 0x7598ff0c50
	private Void PlaceHoverBarAt(Single top, Single indentationPadding, Single siblingBottom) { }
	// RVA: 0x69da33c VA: 0x7598ff233c
	protected override Void ClearDragAndDropUI(Boolean dragCancelled) { }
	// RVA: 0x69d752c VA: 0x7598fef52c
	protected ReusableCollectionItem GetRecycledItem(Vector3 pointerPosition) { }
	// RVA: 0x69da990 VA: 0x7598ff2990
	private Void <ApplyDragAndDropUI>g__GeometryChangedCallback|26_0(GeometryChangedEvent e) { }
}
```