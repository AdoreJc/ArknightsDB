# Allocator2D

**Namespace:** `UnityEngine.UIElements.UIR`


## Methods

- `Boolean TryAllocate(Int32, Int32, out)`

- `Void Free(Alloc2D)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class Allocator2D
{
	private readonly Vector2Int m_MinSize; // 0x10
	private readonly Vector2Int m_MaxSize; // 0x18
	private readonly Vector2Int m_MaxAllocSize; // 0x20
	private readonly Int32 m_RowHeightBias; // 0x28
	private readonly Row[] m_Rows; // 0x30
	private readonly List`1 m_Areas; // 0x38


	// RVA: 0x6a269a4 VA: 0x759903e9a4
	public Void .ctor(Vector2Int minSize, Vector2Int maxSize, Int32 rowHeightBias) { }
	// RVA: 0x6a27008 VA: 0x759903f008
	public Boolean TryAllocate(Int32 width, Int32 height, out Alloc2D alloc2D) { }
	// RVA: 0x6a274f8 VA: 0x759903f4f8
	public Void Free(Alloc2D alloc2D) { }
	// RVA: 0x6a26bd0 VA: 0x759903ebd0
	private static Void BuildAreas(List`1 areas, Vector2Int minSize, Vector2Int maxSize) { }
	// RVA: 0x6a26e64 VA: 0x759903ee64
	private static Vector2Int ComputeMaxAllocSize(List`1 areas, Int32 rowHeightBias) { }
	// RVA: 0x6a26f80 VA: 0x759903ef80
	private static Row[] BuildRowArray(Int32 maxRowHeight, Int32 rowHeightBias) { }
}
```