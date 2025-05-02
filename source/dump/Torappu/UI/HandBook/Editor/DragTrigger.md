# DragTrigger

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `UnityEvent _beginDragCallBack`

- `UIVector2Event _dragCallBack`

- `UnityEvent _endDragCallBack`

- `UnityEvent _onClickCallBack`

- `Boolean m_isDragging`

- `Vector2 m_beginPos`


## Methods

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void OnPointerClick(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class DragTrigger : MonoBehaviour, IBeginDragHandler, IEventSystemHandler, IDragHandler, IEndDragHandler, IPointerClickHandler
{
	private UnityEvent _beginDragCallBack; // 0x18
	private UIVector2Event _dragCallBack; // 0x20
	private UnityEvent _endDragCallBack; // 0x28
	private UnityEvent _onClickCallBack; // 0x30
	private Boolean m_isDragging; // 0x38
	private Vector2 m_beginPos; // 0x3c


	// RVA: 0x2ee0ce4 VA: 0x75954f8ce4
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x2ee0d20 VA: 0x75954f8d20
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x2ee0d94 VA: 0x75954f8d94
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2ee0e00 VA: 0x75954f8e00
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x2ee0e14 VA: 0x75954f8e14
	public Void .ctor() { }
}
```