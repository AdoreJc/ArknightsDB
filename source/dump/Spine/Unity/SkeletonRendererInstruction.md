# SkeletonRendererInstruction

**Namespace:** `Spine.Unity`


## Fields

- `Boolean immutableTriangles`

- `Boolean hasActiveClipping`

- `Int32 rawVertexCount`

- `Boolean reverseMesh`


## Methods

- `Void Clear()`

- `Void Dispose()`

- `Void SetWithSubset(ExposedList`1, Int32, Int32)`

- `Void Set(SkeletonRendererInstruction)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonRendererInstruction
{
	public readonly ExposedList`1 submeshInstructions; // 0x10
	public Boolean immutableTriangles; // 0x18
	public Boolean hasActiveClipping; // 0x19
	public Int32 rawVertexCount; // 0x1c
	public readonly ExposedList`1 attachments; // 0x20
	public Boolean reverseMesh; // 0x28


	// RVA: 0x620f158 VA: 0x7598827158
	public Void Clear() { }
	// RVA: 0x621b420 VA: 0x7598833420
	public Void Dispose() { }
	// RVA: 0x620f4ac VA: 0x75988274ac
	public Void SetWithSubset(ExposedList`1 instructions, Int32 startSubmesh, Int32 endSubmesh) { }
	// RVA: 0x62122cc VA: 0x759882a2cc
	public Void Set(SkeletonRendererInstruction other) { }
	// RVA: 0x620f804 VA: 0x7598827804
	public static Boolean GeometryNotEqual(SkeletonRendererInstruction a, SkeletonRendererInstruction b) { }
	// RVA: 0x6212714 VA: 0x759882a714
	public Void .ctor() { }
}
```