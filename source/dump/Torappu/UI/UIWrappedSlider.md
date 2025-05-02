# UIWrappedSlider

**Namespace:** `Torappu.UI`


## Fields

- `Boolean <isDragging>k__BackingField`

- `Int32 m_dragPointerId`


## Properties

- `Boolean isDragging`


## Methods

- `Boolean get_isDragging()`

- `Void set_isDragging(Boolean)`

- `Void CancelCurrentDrag()`

- `Boolean _IsPointerDownValid(PointerEventData)`

- `Void _StopCurrentDragImpl()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIWrappedSlider : Slider
{
	private Boolean <isDragging>k__BackingField; // 0x15a
	private Int32 m_dragPointerId; // 0x15c

	public Boolean isDragging { get; set; }

	// RVA: 0x221bec4 VA: 0x7594833ec4
	public Boolean get_isDragging() { }
	// RVA: 0x221becc VA: 0x7594833ecc
	private Void set_isDragging(Boolean value) { }
	// RVA: 0x221bed8 VA: 0x7594833ed8
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x221bf9c VA: 0x7594833f9c
	public override Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x221bfb0 VA: 0x7594833fb0
	protected override Void OnDisable() { }
	// RVA: 0x221ba3c VA: 0x7594833a3c
	public Void CancelCurrentDrag() { }
	// RVA: 0x221bfe4 VA: 0x7594833fe4
	protected override Void Update() { }
	// RVA: 0x221bf38 VA: 0x7594833f38
	private Boolean _IsPointerDownValid(PointerEventData eventData) { }
	// RVA: 0x221bfd4 VA: 0x7594833fd4
	private Void _StopCurrentDragImpl() { }
	// RVA: 0x221c020 VA: 0x7594834020
	public Void .ctor() { }
}
```