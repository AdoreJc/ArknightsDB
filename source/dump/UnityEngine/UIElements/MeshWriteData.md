# MeshWriteData

**Namespace:** `UnityEngine.UIElements`


## Properties

- `Int32 vertexCount`

- `Int32 indexCount`

- `Rect uvRegion`


## Methods

- `Int32 get_vertexCount()`

- `Int32 get_indexCount()`

- `Rect get_uvRegion()`

- `Void SetNextVertex(Vertex)`

- `Void SetNextIndex(UInt16)`

- `Void SetAllVertices(Vertex[])`

- `Void SetAllIndices(UInt16[])`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class MeshWriteData
{
	internal NativeSlice`1 m_Vertices; // 0x10
	internal NativeSlice`1 m_Indices; // 0x20
	internal Rect m_UVRegion; // 0x30
	internal Int32 currentIndex; // 0x40
	internal Int32 currentVertex; // 0x44

	public Int32 vertexCount { get; }
	public Int32 indexCount { get; }
	public Rect uvRegion { get; }

	// RVA: 0x6a06dd4 VA: 0x759901edd4
	internal Void .ctor() { }
	// RVA: 0x6a06ddc VA: 0x759901eddc
	public Int32 get_vertexCount() { }
	// RVA: 0x6a06e24 VA: 0x759901ee24
	public Int32 get_indexCount() { }
	// RVA: 0x6a06e6c VA: 0x759901ee6c
	public Rect get_uvRegion() { }
	// RVA: 0x6a06e78 VA: 0x759901ee78
	public Void SetNextVertex(Vertex vertex) { }
	// RVA: 0x6a06f14 VA: 0x759901ef14
	public Void SetNextIndex(UInt16 index) { }
	// RVA: 0x6a06f78 VA: 0x759901ef78
	public Void SetAllVertices(Vertex[] vertices) { }
	// RVA: 0x6a07050 VA: 0x759901f050
	public Void SetAllIndices(UInt16[] indices) { }
	// RVA: 0x6a07128 VA: 0x759901f128
	internal Void Reset(NativeSlice`1 vertices, NativeSlice`1 indices) { }
	// RVA: 0x6a07174 VA: 0x759901f174
	internal Void Reset(NativeSlice`1 vertices, NativeSlice`1 indices, Rect uvRegion) { }
}
```