# NestedScrollRect

**Namespace:** `Torappu.UI`


## Fields

- `ScrollRect _anotherScrollRect`


## Methods

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class NestedScrollRect : MonoBehaviour, IBeginDragHandler, IEventSystemHandler, IDragHandler, IEndDragHandler
{
	private ScrollRect _anotherScrollRect; // 0x18


	// RVA: 0x2236378 VA: 0x759484e378
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x2236418 VA: 0x759484e418
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x22364b8 VA: 0x759484e4b8
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2236558 VA: 0x759484e558
	public Void .ctor() { }
}
```