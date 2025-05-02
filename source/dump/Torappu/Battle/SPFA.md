# SPFA

**Namespace:** `Torappu.Battle`


## Fields

- `Map m_map`


## Methods

- `Void GenerateNextMap(PathRequest, Node[, ])`

- `Boolean TryCalculatePathFindingDistance(PathRequest, GridPosition, out)`

- `Boolean CheckReachable(PathRequest, GridPosition, Boolean)`

- `Void ClearCache(MotionMode)`

- `Void ClearAllCaches()`

- `Boolean _CheckCachedMapReachable(Node[, ], GridPosition, Boolean)`

- `Void _LoadedCacheMap(Node[, ], Node[, ])`

- `Void _PostprocessAndMakeNextMapSmoothly(PathRequest, Node[, ])`

- `Boolean _RaycastBresenhamLine(GridPosition, GridPosition, MotionMode, Node[, ])`

- `Boolean _RaycastSegmentLine(GridPosition, GridPosition, MotionMode, Node[, ])`

- `Boolean _CheckRectangeAllClear(GridPosition, GridPosition, MotionMode, Node[, ])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SPFA : IPathFinding, IHotfixable
{
	private static Queue`1 s_openList; // 0x0
	private Map m_map; // 0x10
	private Dictionary`2[] m_cacheMap; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_GenerateNextMap; // 0x10
	private static DelegateBridge __Hotfix0_TryCalculatePathFindingDistance; // 0x18
	private static DelegateBridge __Hotfix0_CheckReachable; // 0x20
	private static DelegateBridge __Hotfix0_ClearCache; // 0x28
	private static DelegateBridge __Hotfix0_ClearAllCaches; // 0x30
	private static DelegateBridge __Hotfix0__CheckCachedMapReachable; // 0x38
	private static DelegateBridge __Hotfix0__LoadedCacheMap; // 0x40
	private static DelegateBridge __Hotfix0__PostprocessAndMakeNextMapSmoothly; // 0x48
	private static DelegateBridge __Hotfix0__RaycastBresenhamLine; // 0x50
	private static DelegateBridge __Hotfix0__RaycastSegmentLine; // 0x58
	private static DelegateBridge __Hotfix0__CheckRectangeAllClear; // 0x60


	// RVA: 0x40752b4 VA: 0x759668d2b4
	public Void .ctor(Map map) { }
	// RVA: 0x4081348 VA: 0x7596699348
	public Void GenerateNextMap(PathRequest request, Node[,] nextMap) { }
	// RVA: 0x4081e70 VA: 0x7596699e70
	public Boolean TryCalculatePathFindingDistance(PathRequest request, GridPosition startPos, out Int32 distance) { }
	// RVA: 0x40820b4 VA: 0x759669a0b4
	public Boolean CheckReachable(PathRequest request, GridPosition targetPos, Boolean avoidObstacleLike) { }
	// RVA: 0x40823f4 VA: 0x759669a3f4
	public Void ClearCache(MotionMode motionMode) { }
	// RVA: 0x40824bc VA: 0x759669a4bc
	public Void ClearAllCaches() { }
	// RVA: 0x408228c VA: 0x759669a28c
	private Boolean _CheckCachedMapReachable(Node[,] cachedMap, GridPosition targetPos, Boolean avoidObstacleLike) { }
	// RVA: 0x4081978 VA: 0x7596699978
	private Void _LoadedCacheMap(Node[,] cache, Node[,] destination) { }
	// RVA: 0x4081c70 VA: 0x7596699c70
	private Void _PostprocessAndMakeNextMapSmoothly(PathRequest request, Node[,] nextMap) { }
	// RVA: 0x408254c VA: 0x759669a54c
	private Boolean _RaycastBresenhamLine(GridPosition a, GridPosition b, MotionMode motion, Node[,] nextMap) { }
	// RVA: 0x4082ca4 VA: 0x759669aca4
	private Boolean _RaycastSegmentLine(GridPosition a, GridPosition b, MotionMode motion, Node[,] nextMap) { }
	// RVA: 0x4082d6c VA: 0x759669ad6c
	private Boolean _CheckRectangeAllClear(GridPosition a, GridPosition b, MotionMode motion, Node[,] nextMap) { }
	// RVA: 0x4082eb4 VA: 0x759669aeb4
	private static Void .cctor() { }
}
```