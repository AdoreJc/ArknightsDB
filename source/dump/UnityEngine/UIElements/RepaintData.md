# RepaintData

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Matrix4x4 <currentOffset>k__BackingField`

- `Vector2 <mousePosition>k__BackingField`

- `Rect <currentWorldClip>k__BackingField`

- `Event <repaintEvent>k__BackingField`


## Properties

- `Matrix4x4 currentOffset`

- `Rect currentWorldClip`

- `Event repaintEvent`


## Methods

- `Matrix4x4 get_currentOffset()`

- `Rect get_currentWorldClip()`

- `Event get_repaintEvent()`

- `Void set_repaintEvent(Event)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class RepaintData
{
	private Matrix4x4 <currentOffset>k__BackingField; // 0x10
	private Vector2 <mousePosition>k__BackingField; // 0x50
	private Rect <currentWorldClip>k__BackingField; // 0x58
	private Event <repaintEvent>k__BackingField; // 0x68

	public Matrix4x4 currentOffset { get; }
	public Rect currentWorldClip { get; }
	public Event repaintEvent { get; set; }

	// RVA: 0x693dfc0 VA: 0x7598f55fc0
	public Matrix4x4 get_currentOffset() { }
	// RVA: 0x693dfd4 VA: 0x7598f55fd4
	public Rect get_currentWorldClip() { }
	// RVA: 0x693dfe0 VA: 0x7598f55fe0
	public Event get_repaintEvent() { }
	// RVA: 0x693dfe8 VA: 0x7598f55fe8
	public Void set_repaintEvent(Event value) { }
	// RVA: 0x693dff0 VA: 0x7598f55ff0
	public Void .ctor() { }
}
```