# CharacterController

**Namespace:** `UnityEngine`


## Properties

- `Boolean isGrounded`


## Methods

- `CollisionFlags Move(Vector3)`

- `Boolean get_isGrounded()`

- `CollisionFlags Move_Injected(ref)`


## Dump
```C#
// Dll : UnityEngine.PhysicsModule.dll
// Namespace : UnityEngine
public class CharacterController : Collider
{

	public Boolean isGrounded { get; }

	// RVA: 0x68e07a0 VA: 0x7598ef87a0
	public CollisionFlags Move(Vector3 motion) { }
	// RVA: 0x68e0838 VA: 0x7598ef8838
	public Boolean get_isGrounded() { }
	// RVA: 0x68e07f4 VA: 0x7598ef87f4
	private CollisionFlags Move_Injected(ref Vector3 motion) { }
}
```