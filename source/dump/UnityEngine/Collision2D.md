# Collision2D

**Namespace:** `UnityEngine`


## Properties

- `Collider2D collider`

- `Rigidbody2D rigidbody`

- `GameObject gameObject`


## Methods

- `Collider2D get_collider()`

- `Rigidbody2D get_rigidbody()`

- `GameObject get_gameObject()`

- `Int32 GetContacts(ContactPoint2D[])`


## Dump
```C#
// Dll : UnityEngine.Physics2DModule.dll
// Namespace : UnityEngine
public class Collision2D
{
	internal Int32 m_Collider; // 0x10
	internal Int32 m_OtherCollider; // 0x14
	internal Int32 m_Rigidbody; // 0x18
	internal Int32 m_OtherRigidbody; // 0x1c
	internal Vector2 m_RelativeVelocity; // 0x20
	internal Int32 m_Enabled; // 0x28
	internal Int32 m_ContactCount; // 0x2c
	internal ContactPoint2D[] m_ReusedContacts; // 0x30
	internal ContactPoint2D[] m_LegacyContacts; // 0x38

	public Collider2D collider { get; }
	public Rigidbody2D rigidbody { get; }
	public GameObject gameObject { get; }

	// RVA: 0x68dc0ec VA: 0x7598ef40ec
	private ContactPoint2D[] GetContacts_Internal() { }
	// RVA: 0x68dc108 VA: 0x7598ef4108
	public Collider2D get_collider() { }
	// RVA: 0x68dc1b4 VA: 0x7598ef41b4
	public Rigidbody2D get_rigidbody() { }
	// RVA: 0x68dc23c VA: 0x7598ef423c
	public GameObject get_gameObject() { }
	// RVA: 0x68dc2d0 VA: 0x7598ef42d0
	public Int32 GetContacts(ContactPoint2D[] contacts) { }
}
```