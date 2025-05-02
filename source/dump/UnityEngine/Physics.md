# Physics

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.PhysicsModule.dll
// Namespace : UnityEngine
public class Physics
{
	private static Action`2 ContactModifyEvent; // 0x0
	private static Action`2 ContactModifyEventCCD; // 0x8

	public static PhysicsScene defaultPhysicsScene { get; }

	// RVA: 0x68ddc3c VA: 0x7598ef5c3c
	private static Void OnSceneContactModify(PhysicsScene scene, IntPtr buffer, Int32 count, Boolean isCCD) { }
	// RVA: 0x68ddd08 VA: 0x7598ef5d08
	public static PhysicsScene get_defaultPhysicsScene() { }
	// RVA: 0x68ddd88 VA: 0x7598ef5d88
	public static Boolean Raycast(Vector3 origin, Vector3 direction, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68ddfa4 VA: 0x7598ef5fa4
	public static Boolean Raycast(Vector3 origin, Vector3 direction, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68de068 VA: 0x7598ef6068
	public static Boolean Raycast(Vector3 origin, Vector3 direction, Single maxDistance) { }
	// RVA: 0x68de120 VA: 0x7598ef6120
	public static Boolean Raycast(Vector3 origin, Vector3 direction) { }
	// RVA: 0x68de1d0 VA: 0x7598ef61d0
	public static Boolean Raycast(Vector3 origin, Vector3 direction, out RaycastHit hitInfo, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68de410 VA: 0x7598ef6410
	public static Boolean Raycast(Vector3 origin, Vector3 direction, out RaycastHit hitInfo, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68de4dc VA: 0x7598ef64dc
	public static Boolean Raycast(Vector3 origin, Vector3 direction, out RaycastHit hitInfo, Single maxDistance) { }
	// RVA: 0x68de5a4 VA: 0x7598ef65a4
	public static Boolean Raycast(Vector3 origin, Vector3 direction, out RaycastHit hitInfo) { }
	// RVA: 0x68de664 VA: 0x7598ef6664
	public static Boolean Raycast(Ray ray, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68de734 VA: 0x7598ef6734
	public static Boolean Raycast(Ray ray, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68de7f8 VA: 0x7598ef67f8
	public static Boolean Raycast(Ray ray, Single maxDistance) { }
	// RVA: 0x68de8b8 VA: 0x7598ef68b8
	public static Boolean Raycast(Ray ray) { }
	// RVA: 0x68de978 VA: 0x7598ef6978
	public static Boolean Raycast(Ray ray, out RaycastHit hitInfo, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68dea50 VA: 0x7598ef6a50
	public static Boolean Raycast(Ray ray, out RaycastHit hitInfo, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68deacc VA: 0x7598ef6acc
	public static Boolean Raycast(Ray ray, out RaycastHit hitInfo, Single maxDistance) { }
	// RVA: 0x68deb94 VA: 0x7598ef6b94
	public static Boolean Raycast(Ray ray, out RaycastHit hitInfo) { }
	// RVA: 0x68dec5c VA: 0x7598ef6c5c
	public static Boolean Linecast(Vector3 start, Vector3 end, out RaycastHit hitInfo, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68ded80 VA: 0x7598ef6d80
	public static Boolean Linecast(Vector3 start, Vector3 end, out RaycastHit hitInfo) { }
	// RVA: 0x68ded8c VA: 0x7598ef6d8c
	private static RaycastHit[] Internal_RaycastAll(PhysicsScene physicsScene, Ray ray, Single maxDistance, Int32 mask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68dee70 VA: 0x7598ef6e70
	public static RaycastHit[] RaycastAll(Vector3 origin, Vector3 direction, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68df010 VA: 0x7598ef7010
	public static RaycastHit[] RaycastAll(Vector3 origin, Vector3 direction, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68df018 VA: 0x7598ef7018
	public static RaycastHit[] RaycastAll(Vector3 origin, Vector3 direction, Single maxDistance) { }
	// RVA: 0x68df024 VA: 0x7598ef7024
	public static RaycastHit[] RaycastAll(Vector3 origin, Vector3 direction) { }
	// RVA: 0x68df038 VA: 0x7598ef7038
	public static RaycastHit[] RaycastAll(Ray ray, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68df0b0 VA: 0x7598ef70b0
	public static RaycastHit[] RaycastAll(Ray ray, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68df124 VA: 0x7598ef7124
	public static RaycastHit[] RaycastAll(Ray ray, Single maxDistance) { }
	// RVA: 0x68df18c VA: 0x7598ef718c
	public static RaycastHit[] RaycastAll(Ray ray) { }
	// RVA: 0x68df1f4 VA: 0x7598ef71f4
	public static Int32 RaycastNonAlloc(Ray ray, RaycastHit[] results, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68df4a4 VA: 0x7598ef74a4
	public static Int32 RaycastNonAlloc(Ray ray, RaycastHit[] results, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68df574 VA: 0x7598ef7574
	public static Int32 RaycastNonAlloc(Ray ray, RaycastHit[] results, Single maxDistance) { }
	// RVA: 0x68df638 VA: 0x7598ef7638
	public static Int32 RaycastNonAlloc(Ray ray, RaycastHit[] results) { }
	// RVA: 0x68df6fc VA: 0x7598ef76fc
	public static Int32 RaycastNonAlloc(Vector3 origin, Vector3 direction, RaycastHit[] results, Single maxDistance, Int32 layerMask, QueryTriggerInteraction queryTriggerInteraction) { }
	// RVA: 0x68df7d0 VA: 0x7598ef77d0
	public static Int32 RaycastNonAlloc(Vector3 origin, Vector3 direction, RaycastHit[] results, Single maxDistance, Int32 layerMask) { }
	// RVA: 0x68df898 VA: 0x7598ef7898
	public static Int32 RaycastNonAlloc(Vector3 origin, Vector3 direction, RaycastHit[] results, Single maxDistance) { }
	// RVA: 0x68df95c VA: 0x7598ef795c
	public static Int32 RaycastNonAlloc(Vector3 origin, Vector3 direction, RaycastHit[] results) { }
	// RVA: 0x68ddd4c VA: 0x7598ef5d4c
	private static Void get_defaultPhysicsScene_Injected(out PhysicsScene ret) { }
	// RVA: 0x68dee04 VA: 0x7598ef6e04
	private static RaycastHit[] Internal_RaycastAll_Injected(ref PhysicsScene physicsScene, ref Ray ray, Single maxDistance, Int32 mask, QueryTriggerInteraction queryTriggerInteraction) { }
}
```