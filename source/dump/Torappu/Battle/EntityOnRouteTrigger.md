# EntityOnRouteTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `DirectionCursor m_cursor`

- `Enemy m_owner`

- `Tile m_currTargetTile`

- `GridPosition m_currTargetGridPos`


## Methods

- `Void GetMyCursorIfNot()`

- `GridPosition _GetNextGridPosExactly(GridPosition, GridPosition)`

- `Void _UpdateTilesOnRoute(GridPosition, GridPosition)`

- `Void _GetTilesOnSegmentToNextGrid(GridPosition, GridPosition, MotionMode, Node[, ])`

- `Void _AddNearbyTiles(Int32, Int32, Node[, ], Int32, Boolean)`

- `Void _AddTilesOnRouteIfNot(Tile, Node[, ])`

- `Void _FilterNearbyRouteTiles(Vector2, Vector2)`

- `Boolean _IsSegmentIntersectWithTile(Vector3, Vector3, Vector3)`

- `Boolean _SameSide(Vector3, Vector3, Vector3)`

- `Boolean <>xLuaBaseProxy_Validator(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EntityOnRouteTrigger : SelectorTrigger
{
	private DirectionCursor m_cursor; // 0x50
	private Enemy m_owner; // 0x58
	private Tile m_currTargetTile; // 0x60
	private GridPosition m_currTargetGridPos; // 0x68
	private ListSet`1 m_tilesOnRoute; // 0x70
	private static DelegateBridge __Hotfix0_GetMyCursorIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Search; // 0x8
	private static DelegateBridge __Hotfix0__GetNextGridPosExactly; // 0x10
	private static DelegateBridge __Hotfix0__UpdateTilesOnRoute; // 0x18
	private static DelegateBridge __Hotfix0__GetTilesOnSegmentToNextGrid; // 0x20
	private static DelegateBridge __Hotfix0__AddNearbyTiles; // 0x28
	private static DelegateBridge __Hotfix0__AddTilesOnRouteIfNot; // 0x30
	private static DelegateBridge __Hotfix0__FilterNearbyRouteTiles; // 0x38
	private static DelegateBridge __Hotfix0__IsSegmentIntersectWithTile; // 0x40
	private static DelegateBridge __Hotfix0__SameSide; // 0x48
	private static DelegateBridge __Hotfix0_Validator; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x1bd4f88 VA: 0x75941ecf88
	private Void GetMyCursorIfNot() { }
	// RVA: 0x1bd51a4 VA: 0x75941ed1a4
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd5408 VA: 0x75941ed408
	private GridPosition _GetNextGridPosExactly(GridPosition from, GridPosition to) { }
	// RVA: 0x1bd5660 VA: 0x75941ed660
	private Void _UpdateTilesOnRoute(GridPosition currGridPos, GridPosition targetGridPos) { }
	// RVA: 0x1bd5928 VA: 0x75941ed928
	private Void _GetTilesOnSegmentToNextGrid(GridPosition a, GridPosition b, MotionMode motion, Node[,] nextMap) { }
	// RVA: 0x1bd5dd8 VA: 0x75941eddd8
	private Void _AddNearbyTiles(Int32 x, Int32 y, Node[,] nextMap, Int32 yDir, Boolean swapXY) { }
	// RVA: 0x1bd5c9c VA: 0x75941edc9c
	private Void _AddTilesOnRouteIfNot(Tile tile, Node[,] nextMap) { }
	// RVA: 0x1bd5794 VA: 0x75941ed794
	private Void _FilterNearbyRouteTiles(Vector2 currMapPos, Vector2 targetMapPos) { }
	// RVA: 0x1bd6048 VA: 0x75941ee048
	private Boolean _IsSegmentIntersectWithTile(Vector3 currMapPos, Vector3 targetMapPos, Vector3 tilePosition) { }
	// RVA: 0x1bd629c VA: 0x75941ee29c
	private Boolean _SameSide(Vector3 line, Vector3 lhs, Vector3 rhs) { }
	// RVA: 0x1bd63e8 VA: 0x75941ee3e8
	protected override Boolean Validator(Entity target) { }
	// RVA: 0x1bd65a4 VA: 0x75941ee5a4
	public Void .ctor() { }
	// RVA: 0x1bd6664 VA: 0x75941ee664
	private Boolean <>xLuaBaseProxy_Validator(Entity P0) { }
}
```