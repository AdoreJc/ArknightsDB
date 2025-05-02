# UIPointClickListener

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_isValidClick`

- `Action eventPointClicked`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPointClickListener : EventTrigger
{
	private const Single MOVE_SQR_THRESHOLD; // 0x0
	private Nullable`1 m_downPosition; // 0x20
	private Boolean m_isValidClick; // 0x2c
	public Action eventPointClicked; // 0x30


	// RVA: 0x21dfc78 VA: 0x75947f7c78
	public override Void OnPointerDown(PointerEventData param) { }
	// RVA: 0x21dfd00 VA: 0x75947f7d00
	public override Void OnDrag(PointerEventData param) { }
	// RVA: 0x21dfdfc VA: 0x75947f7dfc
	public override Void OnPointerUp(PointerEventData param) { }
	// RVA: 0x21dfe34 VA: 0x75947f7e34
	public Void .ctor() { }
}
```