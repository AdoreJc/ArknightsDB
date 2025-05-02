# Collider2D

**Namespace:** `UnityEngine`


## Properties

- `Boolean isTrigger`

- `Vector2 offset`

- `Rigidbody2D attachedRigidbody`

- `Bounds bounds`

- `PhysicsMaterial2D sharedMaterial`


## Methods

- `Boolean get_isTrigger()`

- `Void set_isTrigger(Boolean)`

- `Vector2 get_offset()`

- `Void set_offset(Vector2)`

- `Rigidbody2D get_attachedRigidbody()`

- `Bounds get_bounds()`

- `PhysicsMaterial2D get_sharedMaterial()`

- `Void set_sharedMaterial(PhysicsMaterial2D)`

- `Boolean OverlapPoint(Vector2)`

- `Void get_offset_Injected(out)`

- `Void set_offset_Injected(ref)`

- `Void get_bounds_Injected(out)`

- `Boolean OverlapPoint_Injected(ref)`


## Dump
```C#
// Dll : UnityEngine.Physics2DModule.dll
// Namespace : UnityEngine
public class Collider2D : Behaviour
{

	public Boolean isTrigger { get; set; }
	public Vector2 offset { get; set; }
	public Rigidbody2D attachedRigidbody { get; }
	public Bounds bounds { get; }
	public PhysicsMaterial2D sharedMaterial { get; set; }

	// RVA: 0x68dccc0 VA: 0x7598ef4cc0
	public Boolean get_isTrigger() { }
	// RVA: 0x68dccfc VA: 0x7598ef4cfc
	public Void set_isTrigger(Boolean value) { }
	// RVA: 0x68dcd40 VA: 0x7598ef4d40
	public Vector2 get_offset() { }
	// RVA: 0x68dcdd0 VA: 0x7598ef4dd0
	public Void set_offset(Vector2 value) { }
	// RVA: 0x68dc4ec VA: 0x7598ef44ec
	public Rigidbody2D get_attachedRigidbody() { }
	// RVA: 0x68dce5c VA: 0x7598ef4e5c
	public Bounds get_bounds() { }
	// RVA: 0x68dcf08 VA: 0x7598ef4f08
	public PhysicsMaterial2D get_sharedMaterial() { }
	// RVA: 0x68dcf44 VA: 0x7598ef4f44
	public Void set_sharedMaterial(PhysicsMaterial2D value) { }
	// RVA: 0x68dcf88 VA: 0x7598ef4f88
	public Boolean OverlapPoint(Vector2 point) { }
	// RVA: 0x68dd018 VA: 0x7598ef5018
	public Void .ctor() { }
	// RVA: 0x68dcd8c VA: 0x7598ef4d8c
	private Void get_offset_Injected(out Vector2 ret) { }
	// RVA: 0x68dce18 VA: 0x7598ef4e18
	private Void set_offset_Injected(ref Vector2 value) { }
	// RVA: 0x68dcec4 VA: 0x7598ef4ec4
	private Void get_bounds_Injected(out Bounds ret) { }
	// RVA: 0x68dcfd4 VA: 0x7598ef4fd4
	private Boolean OverlapPoint_Injected(ref Vector2 point) { }
}
```