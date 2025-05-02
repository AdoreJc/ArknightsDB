# Collider

**Namespace:** `UnityEngine`


## Properties

- `Boolean enabled`

- `Rigidbody attachedRigidbody`

- `Bounds bounds`


## Methods

- `Boolean get_enabled()`

- `Rigidbody get_attachedRigidbody()`

- `Vector3 ClosestPoint(Vector3)`

- `Bounds get_bounds()`

- `RaycastHit Raycast(Ray, Single, ref)`

- `Boolean Raycast(Ray, out, Single)`

- `Void ClosestPoint_Injected(ref, out)`

- `Void get_bounds_Injected(out)`

- `Void Raycast_Injected(ref, Single, ref, out)`


## Dump
```C#
// Dll : UnityEngine.PhysicsModule.dll
// Namespace : UnityEngine
public class Collider : Component
{

	public Boolean enabled { get; }
	public Rigidbody attachedRigidbody { get; }
	public Bounds bounds { get; }

	// RVA: 0x68e0448 VA: 0x7598ef8448
	public Boolean get_enabled() { }
	// RVA: 0x68dfc7c VA: 0x7598ef7c7c
	public Rigidbody get_attachedRigidbody() { }
	// RVA: 0x68e0484 VA: 0x7598ef8484
	public Vector3 ClosestPoint(Vector3 position) { }
	// RVA: 0x68e0540 VA: 0x7598ef8540
	public Bounds get_bounds() { }
	// RVA: 0x68e05ec VA: 0x7598ef85ec
	private RaycastHit Raycast(Ray ray, Single maxDistance, ref Boolean hasHit) { }
	// RVA: 0x68e06ec VA: 0x7598ef86ec
	public Boolean Raycast(Ray ray, out RaycastHit hitInfo, Single maxDistance) { }
	// RVA: 0x68e0798 VA: 0x7598ef8798
	public Void .ctor() { }
	// RVA: 0x68e04ec VA: 0x7598ef84ec
	private Void ClosestPoint_Injected(ref Vector3 position, out Vector3 ret) { }
	// RVA: 0x68e05a8 VA: 0x7598ef85a8
	private Void get_bounds_Injected(out Bounds ret) { }
	// RVA: 0x68e0680 VA: 0x7598ef8680
	private Void Raycast_Injected(ref Ray ray, Single maxDistance, ref Boolean hasHit, out RaycastHit ret) { }
}
```