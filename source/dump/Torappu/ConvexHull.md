# ConvexHull

**Namespace:** `Torappu`


## Fields

- `Vector2 <center>k__BackingField`


## Properties

- `Vector2 center`


## Methods

- `Vector2 get_center()`

- `Void set_center(Vector2)`

- `Void _Reset()`

- `Void UpdateVerts(Vector2, List`1)`

- `Boolean TryGetMovementInHull(Vector2, Vector2, out)`

- `Boolean InHullRange(Vector2)`

- `Single _Cross(Vector2, Vector2, Vector2)`

- `Void _DoCalculateHull(List`1, Vector2, ref, out)`

- `Void _ResizeByCenter(Vector2)`

- `Single _GetTriangleArea(Vector2, Vector2, Vector2)`

- `Void _ConstructBorderLines()`

- `Vector2 _GetProjection(Vector2, Vector2)`

- `Boolean _TryGetIntersect(Vector2, Vector2, Vector2, Vector2, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ConvexHull : IHotfixable
{
	private List`1 m_verts; // 0x10
	private List`1 m_borderLines; // 0x18
	private Vector2 <center>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_center; // 0x0
	private static DelegateBridge __Hotfix0_set_center; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0__Reset; // 0x18
	private static DelegateBridge __Hotfix0_UpdateVerts; // 0x20
	private static DelegateBridge __Hotfix0_TryGetMovementInHull; // 0x28
	private static DelegateBridge __Hotfix0_InHullRange; // 0x30
	private static DelegateBridge __Hotfix0__Cross; // 0x38
	private static DelegateBridge __Hotfix0__DoCalculateHull; // 0x40
	private static DelegateBridge __Hotfix0__ResizeByCenter; // 0x48
	private static DelegateBridge __Hotfix0__GetTriangleArea; // 0x50
	private static DelegateBridge __Hotfix0__ConstructBorderLines; // 0x58
	private static DelegateBridge __Hotfix0__IsOnSegment; // 0x60
	private static DelegateBridge __Hotfix0__GetProjection; // 0x68
	private static DelegateBridge __Hotfix0__TryGetIntersect; // 0x70

	public Vector2 center { get; set; }

	// RVA: 0x2d05a34 VA: 0x759531da34
	public Vector2 get_center() { }
	// RVA: 0x2d05a98 VA: 0x759531da98
	private Void set_center(Vector2 value) { }
	// RVA: 0x2d05b1c VA: 0x759531db1c
	public Void .ctor(Vector2 resizeRatio, List`1 corners) { }
	// RVA: 0x2d05da0 VA: 0x759531dda0
	private Void _Reset() { }
	// RVA: 0x2d05c74 VA: 0x759531dc74
	public Void UpdateVerts(Vector2 resizeRatio, List`1 corners) { }
	// RVA: 0x2d06c54 VA: 0x759531ec54
	public Boolean TryGetMovementInHull(Vector2 origin, Vector2 offset, out Vector2 destination) { }
	// RVA: 0x2d07148 VA: 0x759531f148
	public Boolean InHullRange(Vector2 destination) { }
	// RVA: 0x2d07764 VA: 0x759531f764
	private Single _Cross(Vector2 a, Vector2 b, Vector2 c) { }
	// RVA: 0x2d05e80 VA: 0x759531de80
	private Void _DoCalculateHull(List`1 input, Vector2 resizeRatio, ref List`1 result, out Vector2 resizeScale) { }
	// RVA: 0x2d065c8 VA: 0x759531e5c8
	private Void _ResizeByCenter(Vector2 resizeScale) { }
	// RVA: 0x2d07840 VA: 0x759531f840
	private Single _GetTriangleArea(Vector2 p0, Vector2 p1, Vector2 p2) { }
	// RVA: 0x2d06a38 VA: 0x759531ea38
	private Void _ConstructBorderLines() { }
	// RVA: 0x2d0749c VA: 0x759531f49c
	private static Boolean _IsOnSegment(Vector2 intersect, Vector2 lineStart, Vector2 lineEnd) { }
	// RVA: 0x2d0765c VA: 0x759531f65c
	private Vector2 _GetProjection(Vector2 vector, Vector2 direction) { }
	// RVA: 0x2d072f8 VA: 0x759531f2f8
	private Boolean _TryGetIntersect(Vector2 p1_1, Vector2 p1_2, Vector2 p2_1, Vector2 p2_2, out Vector2 result) { }
}
```