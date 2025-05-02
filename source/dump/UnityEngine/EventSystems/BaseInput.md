# BaseInput

**Namespace:** `UnityEngine.EventSystems`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class BaseInput : UIBehaviour
{

	public virtual String compositionString { get; }
	public virtual IMECompositionMode imeCompositionMode { get; set; }
	public virtual Vector2 compositionCursorPos { get; set; }
	public virtual Boolean mousePresent { get; }
	public virtual Vector2 mousePosition { get; }
	public virtual Vector2 mouseScrollDelta { get; }
	public virtual Boolean touchSupported { get; }
	public virtual Int32 touchCount { get; }

	// RVA: 0x6a7ae30 VA: 0x7599092e30
	public virtual String get_compositionString() { }
	// RVA: 0x6a7ae38 VA: 0x7599092e38
	public virtual IMECompositionMode get_imeCompositionMode() { }
	// RVA: 0x6a7ae40 VA: 0x7599092e40
	public virtual Void set_imeCompositionMode(IMECompositionMode value) { }
	// RVA: 0x6a7ae4c VA: 0x7599092e4c
	public virtual Vector2 get_compositionCursorPos() { }
	// RVA: 0x6a7ae54 VA: 0x7599092e54
	public virtual Void set_compositionCursorPos(Vector2 value) { }
	// RVA: 0x6a7ae5c VA: 0x7599092e5c
	public virtual Boolean get_mousePresent() { }
	// RVA: 0x6a7ae64 VA: 0x7599092e64
	public virtual Boolean GetMouseButtonDown(Int32 button) { }
	// RVA: 0x6a7ae70 VA: 0x7599092e70
	public virtual Boolean GetMouseButtonUp(Int32 button) { }
	// RVA: 0x6a7ae7c VA: 0x7599092e7c
	public virtual Boolean GetMouseButton(Int32 button) { }
	// RVA: 0x6a7ae88 VA: 0x7599092e88
	public virtual Vector2 get_mousePosition() { }
	// RVA: 0x6a7ae90 VA: 0x7599092e90
	public virtual Vector2 get_mouseScrollDelta() { }
	// RVA: 0x6a7ae98 VA: 0x7599092e98
	public virtual Boolean get_touchSupported() { }
	// RVA: 0x6a7aea0 VA: 0x7599092ea0
	public virtual Int32 get_touchCount() { }
	// RVA: 0x6a7aea8 VA: 0x7599092ea8
	public virtual Touch GetTouch(Int32 index) { }
	// RVA: 0x6a7aee0 VA: 0x7599092ee0
	public virtual Single GetAxisRaw(String axisName) { }
	// RVA: 0x6a7aeec VA: 0x7599092eec
	public virtual Boolean GetButtonDown(String buttonName) { }
	// RVA: 0x6a7aef8 VA: 0x7599092ef8
	public Void .ctor() { }
}
```