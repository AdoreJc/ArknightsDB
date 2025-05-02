# SphereCollider

**Namespace:** `UnityEngine`


## Properties

- `Vector3 center`

- `Single radius`


## Methods

- `Vector3 get_center()`

- `Single get_radius()`

- `Void get_center_Injected(out)`


## Dump
```C#
// Dll : UnityEngine.PhysicsModule.dll
// Namespace : UnityEngine
public class SphereCollider : Collider
{

	public Vector3 center { get; }
	public Single radius { get; }

	// RVA: 0x68e0bac VA: 0x7598ef8bac
	public Vector3 get_center() { }
	// RVA: 0x68e0c4c VA: 0x7598ef8c4c
	public Single get_radius() { }
	// RVA: 0x68e0c08 VA: 0x7598ef8c08
	private Void get_center_Injected(out Vector3 ret) { }
}
```