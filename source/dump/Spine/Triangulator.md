# Triangulator

**Namespace:** `Spine`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Triangulator
{
	private readonly ExposedList`1 convexPolygons; // 0x10
	private readonly ExposedList`1 convexPolygonsIndices; // 0x18
	private readonly ExposedList`1 indicesArray; // 0x20
	private readonly ExposedList`1 isConcaveArray; // 0x28
	private readonly ExposedList`1 triangles; // 0x30
	private readonly Pool`1 polygonPool; // 0x38
	private readonly Pool`1 polygonIndicesPool; // 0x40


	// RVA: 0x61e39b0 VA: 0x75987fb9b0
	public ExposedList`1 Triangulate(ExposedList`1 verticesArray) { }
	// RVA: 0x61e3f98 VA: 0x75987fbf98
	public ExposedList`1 Decompose(ExposedList`1 verticesArray, ExposedList`1 triangles) { }
	// RVA: 0x61f5720 VA: 0x759880d720
	private static Boolean IsConcave(Int32 index, Int32 vertexCount, Single[] vertices, Int32[] indices) { }
	// RVA: 0x61f5838 VA: 0x759880d838
	private static Boolean PositiveArea(Single p1x, Single p1y, Single p2x, Single p2y, Single p3x, Single p3y) { }
	// RVA: 0x61f5864 VA: 0x759880d864
	private static Int32 Winding(Single p1x, Single p1y, Single p2x, Single p2y, Single p3x, Single p3y) { }
	// RVA: 0x61e5a98 VA: 0x75987fda98
	public Void .ctor() { }
}
```