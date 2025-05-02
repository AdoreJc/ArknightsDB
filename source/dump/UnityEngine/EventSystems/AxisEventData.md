# AxisEventData

**Namespace:** `UnityEngine.EventSystems`


## Fields

- `Vector2 <moveVector>k__BackingField`

- `MoveDirection <moveDir>k__BackingField`


## Properties

- `Vector2 moveVector`

- `MoveDirection moveDir`


## Methods

- `Vector2 get_moveVector()`

- `Void set_moveVector(Vector2)`

- `MoveDirection get_moveDir()`

- `Void set_moveDir(MoveDirection)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class AxisEventData : BaseEventData
{
	private Vector2 <moveVector>k__BackingField; // 0x20
	private MoveDirection <moveDir>k__BackingField; // 0x28

	public Vector2 moveVector { get; set; }
	public MoveDirection moveDir { get; set; }

	// RVA: 0x6a75558 VA: 0x759908d558
	public Vector2 get_moveVector() { }
	// RVA: 0x6a75560 VA: 0x759908d560
	public Void set_moveVector(Vector2 value) { }
	// RVA: 0x6a75568 VA: 0x759908d568
	public MoveDirection get_moveDir() { }
	// RVA: 0x6a75570 VA: 0x759908d570
	public Void set_moveDir(MoveDirection value) { }
	// RVA: 0x6a75578 VA: 0x759908d578
	public Void .ctor(EventSystem eventSystem) { }
}
```