# Physics2D

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.Physics2DModule.dll
// Namespace : UnityEngine
public class Physics2D
{
	private static List`1 m_LastDisabledRigidbody2D; // 0x0

	public static PhysicsScene2D defaultPhysicsScene { get; }
	public static Vector2 gravity { get; }
	public static Boolean queriesHitTriggers { get; }
	public static SimulationMode2D simulationMode { get; set; }

	// RVA: 0x68daeac VA: 0x7598ef2eac
	public static PhysicsScene2D get_defaultPhysicsScene() { }
	// RVA: 0x68daeb4 VA: 0x7598ef2eb4
	public static Vector2 get_gravity() { }
	// RVA: 0x68daf6c VA: 0x7598ef2f6c
	public static Boolean get_queriesHitTriggers() { }
	// RVA: 0x68daf94 VA: 0x7598ef2f94
	public static SimulationMode2D get_simulationMode() { }
	// RVA: 0x68dafbc VA: 0x7598ef2fbc
	public static Void set_simulationMode(SimulationMode2D value) { }
	// RVA: 0x68daff8 VA: 0x7598ef2ff8
	public static Boolean Simulate(Single step) { }
	// RVA: 0x68db058 VA: 0x7598ef3058
	internal static Boolean Simulate_Internal(PhysicsScene2D physicsScene, Single step) { }
	// RVA: 0x68db138 VA: 0x7598ef3138
	public static RaycastHit2D Raycast(Vector2 origin, Vector2 direction) { }
	// RVA: 0x68db1fc VA: 0x7598ef31fc
	public static RaycastHit2D Raycast(Vector2 origin, Vector2 direction, Single distance) { }
	// RVA: 0x68db2c8 VA: 0x7598ef32c8
	public static RaycastHit2D Raycast(Vector2 origin, Vector2 direction, Single distance, Int32 layerMask) { }
	// RVA: 0x68db3e4 VA: 0x7598ef33e4
	public static RaycastHit2D Raycast(Vector2 origin, Vector2 direction, Single distance, Int32 layerMask, Single minDepth) { }
	// RVA: 0x68db500 VA: 0x7598ef3500
	public static RaycastHit2D Raycast(Vector2 origin, Vector2 direction, Single distance, Int32 layerMask, Single minDepth, Single maxDepth) { }
	// RVA: 0x68db624 VA: 0x7598ef3624
	public static Int32 Raycast(Vector2 origin, Vector2 direction, ContactFilter2D contactFilter, RaycastHit2D[] results) { }
	// RVA: 0x68db6e0 VA: 0x7598ef36e0
	public static Int32 Raycast(Vector2 origin, Vector2 direction, ContactFilter2D contactFilter, RaycastHit2D[] results, Single distance) { }
	// RVA: 0x68db7a4 VA: 0x7598ef37a4
	public static Int32 Raycast(Vector2 origin, Vector2 direction, ContactFilter2D contactFilter, List`1 results, Single distance) { }
	// RVA: 0x68db868 VA: 0x7598ef3868
	public static RaycastHit2D[] GetRayIntersectionAll(Ray ray) { }
	// RVA: 0x68db9c4 VA: 0x7598ef39c4
	public static RaycastHit2D[] GetRayIntersectionAll(Ray ray, Single distance) { }
	// RVA: 0x68dba70 VA: 0x7598ef3a70
	public static RaycastHit2D[] GetRayIntersectionAll(Ray ray, Single distance, Int32 layerMask) { }
	// RVA: 0x68db914 VA: 0x7598ef3914
	private static RaycastHit2D[] GetRayIntersectionAll_Internal(PhysicsScene2D physicsScene, Vector3 origin, Vector3 direction, Single distance, Int32 layerMask) { }
	// RVA: 0x68dbb94 VA: 0x7598ef3b94
	public static Int32 GetRayIntersectionNonAlloc(Ray ray, RaycastHit2D[] results) { }
	// RVA: 0x68dbc2c VA: 0x7598ef3c2c
	public static Int32 GetRayIntersectionNonAlloc(Ray ray, RaycastHit2D[] results, Single distance) { }
	// RVA: 0x68dbccc VA: 0x7598ef3ccc
	public static Int32 GetRayIntersectionNonAlloc(Ray ray, RaycastHit2D[] results, Single distance, Int32 layerMask) { }
	// RVA: 0x68dbd70 VA: 0x7598ef3d70
	public static Int32 OverlapCircleNonAlloc(Vector2 point, Single radius, Collider2D[] results, Int32 layerMask) { }
	// RVA: 0x68dbe44 VA: 0x7598ef3e44
	public static Int32 OverlapAreaNonAlloc(Vector2 pointA, Vector2 pointB, Collider2D[] results, Int32 layerMask) { }
	// RVA: 0x68dbf28 VA: 0x7598ef3f28
	private static Void .cctor() { }
	// RVA: 0x68daf30 VA: 0x7598ef2f30
	private static Void get_gravity_Injected(out Vector2 ret) { }
	// RVA: 0x68db0ec VA: 0x7598ef30ec
	private static Boolean Simulate_Internal_Injected(ref PhysicsScene2D physicsScene, Single step) { }
	// RVA: 0x68dbb28 VA: 0x7598ef3b28
	private static RaycastHit2D[] GetRayIntersectionAll_Internal_Injected(ref PhysicsScene2D physicsScene, ref Vector3 origin, ref Vector3 direction, Single distance, Int32 layerMask) { }
}
```