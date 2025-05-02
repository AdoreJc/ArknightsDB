# SkeletonBounds

**Namespace:** `Spine`


## Fields

- `Single minX`

- `Single minY`

- `Single maxX`

- `Single maxY`


## Properties

- `Single MinX`

- `Single MinY`

- `Single MaxX`

- `Single MaxY`

- `Single Width`

- `Single Height`


## Methods

- `Void set_BoundingBoxes(ExposedList`1)`

- `Void set_Polygons(ExposedList`1)`

- `Single get_MinX()`

- `Void set_MinX(Single)`

- `Single get_MinY()`

- `Void set_MinY(Single)`

- `Single get_MaxX()`

- `Void set_MaxX(Single)`

- `Single get_MaxY()`

- `Void set_MaxY(Single)`

- `Single get_Width()`

- `Single get_Height()`

- `Void Update(Skeleton, Boolean)`

- `Void AabbCompute()`

- `Boolean AabbContainsPoint(Single, Single)`

- `Boolean AabbIntersectsSegment(Single, Single, Single, Single)`

- `Boolean AabbIntersectsSkeleton(SkeletonBounds)`

- `Boolean ContainsPoint(Polygon, Single, Single)`

- `BoundingBoxAttachment ContainsPoint(Single, Single)`

- `BoundingBoxAttachment IntersectsSegment(Single, Single, Single, Single)`

- `Boolean IntersectsSegment(Polygon, Single, Single, Single, Single)`

- `Polygon GetPolygon(BoundingBoxAttachment)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class SkeletonBounds
{
	private ExposedList`1 polygonPool; // 0x10
	private Single minX; // 0x18
	private Single minY; // 0x1c
	private Single maxX; // 0x20
	private Single maxY; // 0x24
	private ExposedList`1 <BoundingBoxes>k__BackingField; // 0x28
	private ExposedList`1 <Polygons>k__BackingField; // 0x30

	public ExposedList`1 BoundingBoxes { get; set; }
	public ExposedList`1 Polygons { get; set; }
	public Single MinX { get; set; }
	public Single MinY { get; set; }
	public Single MaxX { get; set; }
	public Single MaxY { get; set; }
	public Single Width { get; }
	public Single Height { get; }

	// RVA: 0x61e290c VA: 0x75987fa90c
	public ExposedList`1 get_BoundingBoxes() { }
	// RVA: 0x61e2914 VA: 0x75987fa914
	private Void set_BoundingBoxes(ExposedList`1 value) { }
	// RVA: 0x61e291c VA: 0x75987fa91c
	public ExposedList`1 get_Polygons() { }
	// RVA: 0x61e2924 VA: 0x75987fa924
	private Void set_Polygons(ExposedList`1 value) { }
	// RVA: 0x61e292c VA: 0x75987fa92c
	public Single get_MinX() { }
	// RVA: 0x61e2934 VA: 0x75987fa934
	public Void set_MinX(Single value) { }
	// RVA: 0x61e293c VA: 0x75987fa93c
	public Single get_MinY() { }
	// RVA: 0x61e2944 VA: 0x75987fa944
	public Void set_MinY(Single value) { }
	// RVA: 0x61e294c VA: 0x75987fa94c
	public Single get_MaxX() { }
	// RVA: 0x61e2954 VA: 0x75987fa954
	public Void set_MaxX(Single value) { }
	// RVA: 0x61e295c VA: 0x75987fa95c
	public Single get_MaxY() { }
	// RVA: 0x61e2964 VA: 0x75987fa964
	public Void set_MaxY(Single value) { }
	// RVA: 0x61e296c VA: 0x75987fa96c
	public Single get_Width() { }
	// RVA: 0x61e297c VA: 0x75987fa97c
	public Single get_Height() { }
	// RVA: 0x61e298c VA: 0x75987fa98c
	public Void .ctor() { }
	// RVA: 0x61e2a94 VA: 0x75987faa94
	public Void Update(Skeleton skeleton, Boolean updateAabb) { }
	// RVA: 0x61e2df8 VA: 0x75987fadf8
	private Void AabbCompute() { }
	// RVA: 0x61e2f9c VA: 0x75987faf9c
	public Boolean AabbContainsPoint(Single x, Single y) { }
	// RVA: 0x61e2fd8 VA: 0x75987fafd8
	public Boolean AabbIntersectsSegment(Single x1, Single y1, Single x2, Single y2) { }
	// RVA: 0x61e30b4 VA: 0x75987fb0b4
	public Boolean AabbIntersectsSkeleton(SkeletonBounds bounds) { }
	// RVA: 0x61e3110 VA: 0x75987fb110
	public Boolean ContainsPoint(Polygon polygon, Single x, Single y) { }
	// RVA: 0x61e31f8 VA: 0x75987fb1f8
	public BoundingBoxAttachment ContainsPoint(Single x, Single y) { }
	// RVA: 0x61e32ac VA: 0x75987fb2ac
	public BoundingBoxAttachment IntersectsSegment(Single x1, Single y1, Single x2, Single y2) { }
	// RVA: 0x61e3378 VA: 0x75987fb378
	public Boolean IntersectsSegment(Polygon polygon, Single x1, Single y1, Single x2, Single y2) { }
	// RVA: 0x61e34e8 VA: 0x75987fb4e8
	public Polygon GetPolygon(BoundingBoxAttachment attachment) { }
}
```