# SkeletonClipping

**Namespace:** `Spine`


## Properties

- `Boolean IsClipping`


## Methods

- `Boolean get_IsClipping()`

- `Int32 ClipStart(Slot, ClippingAttachment)`

- `Void ClipEnd(Slot)`

- `Void ClipEnd()`

- `Void ClipTriangles(Single[], Int32, Int32[], Int32, Single[])`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class SkeletonClipping
{
	internal readonly Triangulator triangulator; // 0x10
	internal readonly ExposedList`1 clippingPolygon; // 0x18
	internal readonly ExposedList`1 clipOutput; // 0x20
	internal readonly ExposedList`1 clippedVertices; // 0x28
	internal readonly ExposedList`1 clippedTriangles; // 0x30
	internal readonly ExposedList`1 clippedUVs; // 0x38
	internal readonly ExposedList`1 scratch; // 0x40
	internal ClippingAttachment clipAttachment; // 0x48
	internal ExposedList`1 clippingPolygons; // 0x50

	public ExposedList`1 ClippedVertices { get; }
	public ExposedList`1 ClippedTriangles { get; }
	public ExposedList`1 ClippedUVs { get; }
	public Boolean IsClipping { get; }

	// RVA: 0x61e359c VA: 0x75987fb59c
	public ExposedList`1 get_ClippedVertices() { }
	// RVA: 0x61e35a4 VA: 0x75987fb5a4
	public ExposedList`1 get_ClippedTriangles() { }
	// RVA: 0x61e35ac VA: 0x75987fb5ac
	public ExposedList`1 get_ClippedUVs() { }
	// RVA: 0x61e35b4 VA: 0x75987fb5b4
	public Boolean get_IsClipping() { }
	// RVA: 0x61e35c4 VA: 0x75987fb5c4
	public Int32 ClipStart(Slot slot, ClippingAttachment clip) { }
	// RVA: 0x61e4a70 VA: 0x75987fca70
	public Void ClipEnd(Slot slot) { }
	// RVA: 0x61e4aa4 VA: 0x75987fcaa4
	public Void ClipEnd() { }
	// RVA: 0x61e4b6c VA: 0x75987fcb6c
	public Void ClipTriangles(Single[] vertices, Int32 verticesLength, Int32[] triangles, Int32 trianglesLength, Single[] uvs) { }
	// RVA: 0x61e52d4 VA: 0x75987fd2d4
	internal Boolean Clip(Single x1, Single y1, Single x2, Single y2, Single x3, Single y3, ExposedList`1 clippingArea, ExposedList`1 output) { }
	// RVA: 0x61e3864 VA: 0x75987fb864
	public static Void MakeClockwise(ExposedList`1 polygon) { }
	// RVA: 0x61e58b4 VA: 0x75987fd8b4
	public Void .ctor() { }
}
```