# NavigationMoveEvent

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Direction <direction>k__BackingField`

- `Vector2 <move>k__BackingField`


## Properties

- `Direction direction`

- `Vector2 move`


## Methods

- `Direction get_direction()`

- `Void set_direction(Direction)`

- `Void set_move(Vector2)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class NavigationMoveEvent : NavigationEventBase`1
{
	private Direction <direction>k__BackingField; // 0x7c
	private Vector2 <move>k__BackingField; // 0x80

	public Direction direction { get; set; }
	private Vector2 move { set; }

	// RVA: 0x69e530c VA: 0x7598ffd30c
	internal static Direction DetermineMoveDirection(Single x, Single y, Single deadZone) { }
	// RVA: 0x69e5360 VA: 0x7598ffd360
	public Direction get_direction() { }
	// RVA: 0x69e5368 VA: 0x7598ffd368
	private Void set_direction(Direction value) { }
	// RVA: 0x69e5370 VA: 0x7598ffd370
	private Void set_move(Vector2 value) { }
	// RVA: 0x69e5378 VA: 0x7598ffd378
	public static NavigationMoveEvent GetPooled(Vector2 moveVector) { }
	// RVA: 0x69e5458 VA: 0x7598ffd458
	protected override Void Init() { }
	// RVA: 0x69e54e0 VA: 0x7598ffd4e0
	public Void .ctor() { }
}
```