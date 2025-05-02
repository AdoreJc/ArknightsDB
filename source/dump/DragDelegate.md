# DragDelegate

**Namespace:** ` `


## Fields

- `IDragHandler <target>k__BackingField`

- `IInitializePotentialDragHandler m_initDragHandler`

- `IBeginDragHandler m_beginDragHandler`

- `IEndDragHandler m_endDragHandler`

- `UIWrappedScrollRect m_current`

- `Int32 m_dragStatus`

- `PointerEventData m_beginDragEvt`

- `Vector2 m_beginDragPos`


## Properties

- `IDragHandler target`


## Methods

- `IDragHandler get_target()`

- `Void set_target(IDragHandler)`

- `Boolean IsEmpty()`

- `Void FindDelegateInParent(UIWrappedScrollRect)`

- `Void SetDelegate(UIWrappedScrollRect, IDragHandler)`

- `Void _SetDelegateImpl(UIWrappedScrollRect, IDragHandler)`

- `Void InitDrag(PointerEventData)`

- `Void UpdateDrag(PointerEventData, out, out)`

- `Void EndDrag(PointerEventData)`

- `Void StopCurrentDrag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DragDelegate
{
	private IDragHandler <target>k__BackingField; // 0x10
	private IInitializePotentialDragHandler m_initDragHandler; // 0x18
	private IBeginDragHandler m_beginDragHandler; // 0x20
	private IEndDragHandler m_endDragHandler; // 0x28
	private UIWrappedScrollRect m_current; // 0x30
	private const Int32 SYS_DISABLED; // 0x0
	private const Int32 DRAG_UNKNOWN; // 0x0
	private const Int32 DRAG_ACCEPTED; // 0x0
	private const Int32 DRAG_DELEGATED; // 0x0
	private Int32 m_dragStatus; // 0x38
	private PointerEventData m_beginDragEvt; // 0x40
	private Vector2 m_beginDragPos; // 0x48

	public IDragHandler target { get; set; }

	// RVA: 0x22622d0 VA: 0x759487a2d0
	public IDragHandler get_target() { }
	// RVA: 0x22622d8 VA: 0x759487a2d8
	private Void set_target(IDragHandler value) { }
	// RVA: 0x22622e0 VA: 0x759487a2e0
	public Boolean IsEmpty() { }
	// RVA: 0x2262384 VA: 0x759487a384
	public Void FindDelegateInParent(UIWrappedScrollRect current) { }
	// RVA: 0x2262568 VA: 0x759487a568
	public Void SetDelegate(UIWrappedScrollRect current, IDragHandler handler) { }
	// RVA: 0x2262448 VA: 0x759487a448
	private Void _SetDelegateImpl(UIWrappedScrollRect current, IDragHandler handler) { }
	// RVA: 0x226256c VA: 0x759487a56c
	public Void InitDrag(PointerEventData eventData) { }
	// RVA: 0x2262658 VA: 0x759487a658
	public Void UpdateDrag(PointerEventData eventData, out Boolean isDragValid, out Boolean interruptDragThisFrame) { }
	// RVA: 0x2262928 VA: 0x759487a928
	public Void EndDrag(PointerEventData eventData) { }
	// RVA: 0x22629e0 VA: 0x759487a9e0
	public Void StopCurrentDrag() { }
	// RVA: 0x22629e8 VA: 0x759487a9e8
	public Void .ctor() { }
}
```