# ListViewDraggerAnimated

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_DragStartIndex`

- `Int32 m_CurrentIndex`

- `Single m_SelectionHeight`

- `Single m_LocalOffsetOnStart`

- `Vector3 m_CurrentPointerPosition`

- `ReusableCollectionItem m_Item`

- `ReusableCollectionItem m_OffsetItem`

- `Boolean <isDragging>k__BackingField`


## Properties

- `Boolean isDragging`

- `ReusableCollectionItem draggedItem`


## Methods

- `Boolean get_isDragging()`

- `Void set_isDragging(Boolean)`

- `ReusableCollectionItem get_draggedItem()`

- `Void Animate(ReusableCollectionItem, Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ListViewDraggerAnimated : ListViewDragger
{
	private Int32 m_DragStartIndex; // 0x78
	private Int32 m_CurrentIndex; // 0x7c
	private Single m_SelectionHeight; // 0x80
	private Single m_LocalOffsetOnStart; // 0x84
	private Vector3 m_CurrentPointerPosition; // 0x88
	private ReusableCollectionItem m_Item; // 0x98
	private ReusableCollectionItem m_OffsetItem; // 0xa0
	private Boolean <isDragging>k__BackingField; // 0xa8

	public Boolean isDragging { get; set; }
	public ReusableCollectionItem draggedItem { get; }
	protected override Boolean supportsDragEvents { get; }

	// RVA: 0x69dab7c VA: 0x7598ff2b7c
	public Boolean get_isDragging() { }
	// RVA: 0x69dab84 VA: 0x7598ff2b84
	private Void set_isDragging(Boolean value) { }
	// RVA: 0x69dab90 VA: 0x7598ff2b90
	public ReusableCollectionItem get_draggedItem() { }
	// RVA: 0x69dab98 VA: 0x7598ff2b98
	protected override Boolean get_supportsDragEvents() { }
	// RVA: 0x69daba0 VA: 0x7598ff2ba0
	public Void .ctor(BaseVerticalCollectionView listView) { }
	// RVA: 0x69dabac VA: 0x7598ff2bac
	protected internal override StartDragArgs StartDrag(Vector3 pointerPosition) { }
	// RVA: 0x69db664 VA: 0x7598ff3664
	protected internal override Void UpdateDrag(Vector3 pointerPosition) { }
	// RVA: 0x69db318 VA: 0x7598ff3318
	private Void Animate(ReusableCollectionItem element, Single paddingTop) { }
	// RVA: 0x69dbf74 VA: 0x7598ff3f74
	protected internal override Void OnDrop(Vector3 pointerPosition) { }
	// RVA: 0x69dc3a4 VA: 0x7598ff43a4
	protected override Void ClearDragAndDropUI(Boolean dragCancelled) { }
	// RVA: 0x69dc3a8 VA: 0x7598ff43a8
	protected override Boolean TryGetDragPosition(Vector2 pointerPosition, ref DragPosition dragPosition) { }
}
```