# WheelEvent

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Vector3 <delta>k__BackingField`


## Properties

- `Vector3 delta`


## Methods

- `Vector3 get_delta()`

- `Void set_delta(Vector3)`

- `Void LocalInit()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class WheelEvent : MouseEventBase`1
{
	private Vector3 <delta>k__BackingField; // 0xb0

	public Vector3 delta { get; set; }

	// RVA: 0x69e45e0 VA: 0x7598ffc5e0
	public Vector3 get_delta() { }
	// RVA: 0x69e45ec VA: 0x7598ffc5ec
	private Void set_delta(Vector3 value) { }
	// RVA: 0x69e45f8 VA: 0x7598ffc5f8
	public static WheelEvent GetPooled(Event systemEvent) { }
	// RVA: 0x69e4674 VA: 0x7598ffc674
	internal static WheelEvent GetPooled(Vector3 delta, IPointerEvent pointerEvent) { }
	// RVA: 0x69e46ec VA: 0x7598ffc6ec
	protected override Void Init() { }
	// RVA: 0x69e473c VA: 0x7598ffc73c
	private Void LocalInit() { }
	// RVA: 0x69e479c VA: 0x7598ffc79c
	public Void .ctor() { }
}
```