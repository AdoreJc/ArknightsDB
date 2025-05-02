# BoxCollider

**Namespace:** `UnityEngine`


## Properties

- `Vector3 center`

- `Vector3 size`


## Methods

- `Vector3 get_center()`

- `Vector3 get_size()`

- `Void get_center_Injected(out)`

- `Void get_size_Injected(out)`


## Dump
```C#
// Dll : UnityEngine.PhysicsModule.dll
// Namespace : UnityEngine
public class BoxCollider : Collider
{

	public Vector3 center { get; }
	public Vector3 size { get; }

	// RVA: 0x68e0a6c VA: 0x7598ef8a6c
	public Vector3 get_center() { }
	// RVA: 0x68e0b0c VA: 0x7598ef8b0c
	public Vector3 get_size() { }
	// RVA: 0x68e0ac8 VA: 0x7598ef8ac8
	private Void get_center_Injected(out Vector3 ret) { }
	// RVA: 0x68e0b68 VA: 0x7598ef8b68
	private Void get_size_Injected(out Vector3 ret) { }
}
```