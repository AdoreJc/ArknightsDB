# ClampedDragger

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Action dragging`

- `Action draggingEnded`

- `DragDirection <dragDirection>k__BackingField`

- `Vector2 <startMousePosition>k__BackingField`


## Properties

- `DragDirection dragDirection`

- `Vector2 startMousePosition`

- `Vector2 delta`


## Methods

- `Void add_dragging(Action)`

- `Void remove_dragging(Action)`

- `Void add_draggingEnded(Action)`

- `Void remove_draggingEnded(Action)`

- `DragDirection get_dragDirection()`

- `Void set_dragDirection(DragDirection)`

- `Void set_slider(BaseSlider`1)`

- `Vector2 get_startMousePosition()`

- `Void set_startMousePosition(Vector2)`

- `Vector2 get_delta()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ClampedDragger`1 : Clickable
{
	private Action dragging; // 0x0
	private Action draggingEnded; // 0x0
	private DragDirection <dragDirection>k__BackingField; // 0x0
	private BaseSlider`1 <slider>k__BackingField; // 0x0
	private Vector2 <startMousePosition>k__BackingField; // 0x0

	public DragDirection dragDirection { get; set; }
	private BaseSlider`1 slider { set; }
	public Vector2 startMousePosition { get; set; }
	public Vector2 delta { get; }

	// RVA: 0x VA: 0x0
	public Void add_dragging(Action value) { }
	// RVA: 0x VA: 0x0
	public Void remove_dragging(Action value) { }
	// RVA: 0x VA: 0x0
	public Void add_draggingEnded(Action value) { }
	// RVA: 0x VA: 0x0
	public Void remove_draggingEnded(Action value) { }
	// RVA: 0x VA: 0x0
	public DragDirection get_dragDirection() { }
	// RVA: 0x VA: 0x0
	public Void set_dragDirection(DragDirection value) { }
	// RVA: 0x VA: 0x0
	private Void set_slider(BaseSlider`1 value) { }
	// RVA: 0x VA: 0x0
	public Vector2 get_startMousePosition() { }
	// RVA: 0x VA: 0x0
	private Void set_startMousePosition(Vector2 value) { }
	// RVA: 0x VA: 0x0
	public Vector2 get_delta() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(BaseSlider`1 slider, Action clickHandler, Action dragHandler) { }
	// RVA: 0x VA: 0x0
	protected override Void ProcessDownEvent(EventBase evt, Vector2 localPosition, Int32 pointerId) { }
	// RVA: 0x VA: 0x0
	protected override Void ProcessUpEvent(EventBase evt, Vector2 localPosition, Int32 pointerId) { }
	// RVA: 0x VA: 0x0
	protected override Void ProcessMoveEvent(EventBase evt, Vector2 localPosition) { }
}
```