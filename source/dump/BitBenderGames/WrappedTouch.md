# WrappedTouch

**Namespace:** `BitBenderGames`


## Fields

- `Vector3 <Position>k__BackingField`

- `Int32 <FingerId>k__BackingField`


## Properties

- `Vector3 Position`

- `Int32 FingerId`


## Methods

- `Vector3 get_Position()`

- `Void set_Position(Vector3)`

- `Int32 get_FingerId()`

- `Void set_FingerId(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class WrappedTouch
{
	private Vector3 <Position>k__BackingField; // 0x10
	private Int32 <FingerId>k__BackingField; // 0x1c

	public Vector3 Position { get; set; }
	public Int32 FingerId { get; set; }

	// RVA: 0x2c2e150 VA: 0x7595246150
	public Vector3 get_Position() { }
	// RVA: 0x2c2e15c VA: 0x759524615c
	public Void set_Position(Vector3 value) { }
	// RVA: 0x2c2e168 VA: 0x7595246168
	public Int32 get_FingerId() { }
	// RVA: 0x2c2e170 VA: 0x7595246170
	public Void set_FingerId(Int32 value) { }
	// RVA: 0x2c2e178 VA: 0x7595246178
	public Void .ctor() { }
	// RVA: 0x2c2dca0 VA: 0x7595245ca0
	public static WrappedTouch FromTouch(Touch touch) { }
}
```