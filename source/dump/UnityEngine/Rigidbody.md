# Rigidbody

**Namespace:** `UnityEngine`


## Properties

- `Vector3 velocity`

- `Vector3 angularVelocity`

- `Boolean useGravity`

- `Boolean isKinematic`

- `Vector3 position`

- `Quaternion rotation`

- `Single maxAngularVelocity`


## Methods

- `Void set_velocity(Vector3)`

- `Vector3 get_angularVelocity()`

- `Void set_angularVelocity(Vector3)`

- `Void set_useGravity(Boolean)`

- `Boolean get_isKinematic()`

- `Void set_isKinematic(Boolean)`

- `Void set_position(Vector3)`

- `Void set_rotation(Quaternion)`

- `Void set_maxAngularVelocity(Single)`

- `Void MovePosition(Vector3)`

- `Void AddForce(Vector3, ForceMode)`

- `Void AddForce(Vector3)`

- `Void AddRelativeForce(Vector3, ForceMode)`

- `Void AddRelativeForce(Vector3)`

- `Void AddTorque(Vector3, ForceMode)`

- `Void AddTorque(Vector3)`

- `Void AddRelativeTorque(Vector3, ForceMode)`

- `Void AddRelativeTorque(Vector3)`

- `Void set_velocity_Injected(ref)`

- `Void get_angularVelocity_Injected(out)`

- `Void set_angularVelocity_Injected(ref)`

- `Void set_position_Injected(ref)`

- `Void set_rotation_Injected(ref)`

- `Void MovePosition_Injected(ref)`

- `Void AddForce_Injected(ref, ForceMode)`

- `Void AddRelativeForce_Injected(ref, ForceMode)`

- `Void AddTorque_Injected(ref, ForceMode)`

- `Void AddRelativeTorque_Injected(ref, ForceMode)`


## Dump
```C#
// Dll : UnityEngine.PhysicsModule.dll
// Namespace : UnityEngine
public class Rigidbody : Component
{

	public Vector3 velocity { set; }
	public Vector3 angularVelocity { get; set; }
	public Boolean useGravity { set; }
	public Boolean isKinematic { get; set; }
	public Vector3 position { set; }
	public Quaternion rotation { set; }
	public Single maxAngularVelocity { set; }

	// RVA: 0x68dfcb8 VA: 0x7598ef7cb8
	public Void set_velocity(Vector3 value) { }
	// RVA: 0x68dfd50 VA: 0x7598ef7d50
	public Vector3 get_angularVelocity() { }
	// RVA: 0x68dfdf0 VA: 0x7598ef7df0
	public Void set_angularVelocity(Vector3 value) { }
	// RVA: 0x68dfe88 VA: 0x7598ef7e88
	public Void set_useGravity(Boolean value) { }
	// RVA: 0x68dfecc VA: 0x7598ef7ecc
	public Boolean get_isKinematic() { }
	// RVA: 0x68dff08 VA: 0x7598ef7f08
	public Void set_isKinematic(Boolean value) { }
	// RVA: 0x68dff4c VA: 0x7598ef7f4c
	public Void set_position(Vector3 value) { }
	// RVA: 0x68dffe4 VA: 0x7598ef7fe4
	public Void set_rotation(Quaternion value) { }
	// RVA: 0x68e007c VA: 0x7598ef807c
	public Void set_maxAngularVelocity(Single value) { }
	// RVA: 0x68e00c8 VA: 0x7598ef80c8
	public Void MovePosition(Vector3 position) { }
	// RVA: 0x68e0160 VA: 0x7598ef8160
	public Void AddForce(Vector3 force, ForceMode mode) { }
	// RVA: 0x68e0210 VA: 0x7598ef8210
	public Void AddForce(Vector3 force) { }
	// RVA: 0x68e0218 VA: 0x7598ef8218
	public Void AddRelativeForce(Vector3 force, ForceMode mode) { }
	// RVA: 0x68e02c8 VA: 0x7598ef82c8
	public Void AddRelativeForce(Vector3 force) { }
	// RVA: 0x68e02d0 VA: 0x7598ef82d0
	public Void AddTorque(Vector3 torque, ForceMode mode) { }
	// RVA: 0x68e0380 VA: 0x7598ef8380
	public Void AddTorque(Vector3 torque) { }
	// RVA: 0x68e0388 VA: 0x7598ef8388
	public Void AddRelativeTorque(Vector3 torque, ForceMode mode) { }
	// RVA: 0x68e0438 VA: 0x7598ef8438
	public Void AddRelativeTorque(Vector3 torque) { }
	// RVA: 0x68e0440 VA: 0x7598ef8440
	public Void .ctor() { }
	// RVA: 0x68dfd0c VA: 0x7598ef7d0c
	private Void set_velocity_Injected(ref Vector3 value) { }
	// RVA: 0x68dfdac VA: 0x7598ef7dac
	private Void get_angularVelocity_Injected(out Vector3 ret) { }
	// RVA: 0x68dfe44 VA: 0x7598ef7e44
	private Void set_angularVelocity_Injected(ref Vector3 value) { }
	// RVA: 0x68dffa0 VA: 0x7598ef7fa0
	private Void set_position_Injected(ref Vector3 value) { }
	// RVA: 0x68e0038 VA: 0x7598ef8038
	private Void set_rotation_Injected(ref Quaternion value) { }
	// RVA: 0x68e011c VA: 0x7598ef811c
	private Void MovePosition_Injected(ref Vector3 position) { }
	// RVA: 0x68e01bc VA: 0x7598ef81bc
	private Void AddForce_Injected(ref Vector3 force, ForceMode mode) { }
	// RVA: 0x68e0274 VA: 0x7598ef8274
	private Void AddRelativeForce_Injected(ref Vector3 force, ForceMode mode) { }
	// RVA: 0x68e032c VA: 0x7598ef832c
	private Void AddTorque_Injected(ref Vector3 torque, ForceMode mode) { }
	// RVA: 0x68e03e4 VA: 0x7598ef83e4
	private Void AddRelativeTorque_Injected(ref Vector3 torque, ForceMode mode) { }
}
```