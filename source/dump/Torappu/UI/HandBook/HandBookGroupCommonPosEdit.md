# HandBookGroupCommonPosEdit

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Int32 x`

- `Int32 y`

- `Boolean isInited`

- `Boolean m_dragLock`


## Methods

- `Void OnDrag(PointerEventData)`

- `Void OnBeginDrag(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookGroupCommonPosEdit : MonoBehaviour, IDragHandler, IEventSystemHandler, IEndDragHandler, IBeginDragHandler
{
	public Int32 x; // 0x18
	public Int32 y; // 0x1c
	public Boolean isInited; // 0x20
	protected Boolean m_dragLock; // 0x21


	// RVA: 0x2ec0ec8 VA: 0x75954d8ec8
	public virtual Void ApplyPos(Vector3 vect) { }
	// RVA: 0x2ec1648 VA: 0x75954d9648
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x2ec1410 VA: 0x75954d9410
	public virtual Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2ec18b0 VA: 0x75954d98b0
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x2ec100c VA: 0x75954d900c
	public Void .ctor() { }
}
```