# GeometryChangedEvent

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Rect <oldRect>k__BackingField`

- `Rect <newRect>k__BackingField`

- `Int32 <layoutPass>k__BackingField`


## Properties

- `Rect oldRect`

- `Rect newRect`


## Methods

- `Void LocalInit()`

- `Rect get_oldRect()`

- `Void set_oldRect(Rect)`

- `Rect get_newRect()`

- `Void set_newRect(Rect)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class GeometryChangedEvent : EventBase`1
{
	private Rect <oldRect>k__BackingField; // 0x7c
	private Rect <newRect>k__BackingField; // 0x8c
	private Int32 <layoutPass>k__BackingField; // 0x9c

	public Rect oldRect { get; set; }
	public Rect newRect { get; set; }
	internal Int32 layoutPass { get; set; }

	// RVA: 0x69e2d84 VA: 0x7598ffad84
	public static GeometryChangedEvent GetPooled(Rect oldRect, Rect newRect) { }
	// RVA: 0x69e2e44 VA: 0x7598ffae44
	protected override Void Init() { }
	// RVA: 0x69e2e94 VA: 0x7598ffae94
	private Void LocalInit() { }
	// RVA: 0x69e2ec8 VA: 0x7598ffaec8
	public Rect get_oldRect() { }
	// RVA: 0x69e2ed4 VA: 0x7598ffaed4
	private Void set_oldRect(Rect value) { }
	// RVA: 0x69e2ee0 VA: 0x7598ffaee0
	public Rect get_newRect() { }
	// RVA: 0x69e2eec VA: 0x7598ffaeec
	private Void set_newRect(Rect value) { }
	// RVA: 0x69e2ef8 VA: 0x7598ffaef8
	internal Int32 get_layoutPass() { }
	// RVA: 0x69e2f00 VA: 0x7598ffaf00
	internal Void set_layoutPass(Int32 value) { }
	// RVA: 0x69e2f08 VA: 0x7598ffaf08
	public Void .ctor() { }
}
```