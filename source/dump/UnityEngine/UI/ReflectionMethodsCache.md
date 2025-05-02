# ReflectionMethodsCache

**Namespace:** `UnityEngine.UI`


## Fields

- `Raycast3DCallback raycast3D`

- `RaycastAllCallback raycast3DAll`

- `GetRaycastNonAllocCallback getRaycastNonAlloc`

- `Raycast2DCallback raycast2D`

- `GetRayIntersectionAllCallback getRayIntersectionAll`

- `GetRayIntersectionAllNonAllocCallback getRayIntersectionAllNonAlloc`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
internal class ReflectionMethodsCache
{
	public Raycast3DCallback raycast3D; // 0x10
	public RaycastAllCallback raycast3DAll; // 0x18
	public GetRaycastNonAllocCallback getRaycastNonAlloc; // 0x20
	public Raycast2DCallback raycast2D; // 0x28
	public GetRayIntersectionAllCallback getRayIntersectionAll; // 0x30
	public GetRayIntersectionAllNonAllocCallback getRayIntersectionAllNonAlloc; // 0x38
	private static ReflectionMethodsCache s_ReflectionMethodsCache; // 0x0

	public static ReflectionMethodsCache Singleton { get; }

	// RVA: 0x6a6c640 VA: 0x7599084640
	public Void .ctor() { }
	// RVA: 0x6a6d3e4 VA: 0x75990853e4
	public static ReflectionMethodsCache get_Singleton() { }
}
```