# DragCancellableClickHandler

**Namespace:** `Torappu`


## Fields

- `ClickEvent onClicked`

- `Boolean m_hasDragDetacted`


## Methods

- `Void OnPointerClick(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnDrag(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DragCancellableClickHandler : MonoBehaviour, IPointerClickHandler, IEventSystemHandler, IPointerDownHandler, IDragHandler
{
	public ClickEvent onClicked; // 0x18
	private Boolean m_hasDragDetacted; // 0x20


	// RVA: 0x2f458a8 VA: 0x759555d8a8
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x2f45914 VA: 0x759555d914
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x2f4591c VA: 0x759555d91c
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x2f45928 VA: 0x759555d928
	public Void .ctor() { }
}
```