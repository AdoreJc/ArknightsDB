# Route

**Namespace:** `Torappu.Battle`


## Fields

- `Map m_map`

- `RouteData m_data`

- `IPathFinding m_pathFinder`


## Properties

- `Map map`

- `MotionMode motionMode`

- `Int32 checkpointCnt`

- `RouteData data`


## Methods

- `Map get_map()`

- `MotionMode get_motionMode()`

- `Int32 get_checkpointCnt()`

- `RouteData get_data()`

- `Void ReconstructRoute(RouteData)`

- `Single GetDistToFinal()`

- `Single GetDistToFinal(GridPosition)`

- `Int32 GetIndexInMap(Boolean)`

- `Boolean GetIndexInMap(out)`

- `Void ReconstructNextMap()`

- `Single GetEstimatedDistToFinalWithoutCheckpoints(Vector2)`

- `Vector2 GetPredictFuturePositionWithoutCheckpoints(Vector2, Single)`

- `Vector2 GetSpawnPosition()`

- `Vector2 GetSpawnOffset()`

- `Vector2 GetContDirectionAfterEnd()`

- `Boolean CheckReached(Vector2)`

- `Boolean CheckReached(Vector2, Single)`

- `Boolean CheckReached(GridPosition)`

- `Boolean CheckReachable(Boolean)`

- `Boolean CheckReachable(Vector2)`

- `Boolean CheckReachable(GridPosition)`

- `Boolean CheckContainsOffsetCheckpoint(Single)`

- `Void _GenerateNextMap(GridPosition, Node[, ])`

- `Void _ComplementFinalDistance(Node[, ], Node[, ], GridPosition)`

- `Void _GenerateNextTurn(GridPosition, Node[, ], Node[, ])`

- `Vector2 _GetNextTurn(Node, Node)`

- `Single _GetEstimatedDistToFinalWithoutCheckpoints(Vector2, out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Route
{
	private static GridPosition[] s_sharedSingleNode; // 0x0
	private Map m_map; // 0x10
	private RouteData m_data; // 0x18
	private IPathFinding m_pathFinder; // 0x20
	private Node[,] m_targetNextMap; // 0x28
	private Node[,][] m_checkpointsNextMap; // 0x30

	public Map map { get; }
	public MotionMode motionMode { get; }
	public Int32 checkpointCnt { get; }
	public RouteData data { get; }

	// RVA: 0x4083f4c VA: 0x759669bf4c
	public Map get_map() { }
	// RVA: 0x4083f54 VA: 0x759669bf54
	public MotionMode get_motionMode() { }
	// RVA: 0x4083f70 VA: 0x759669bf70
	public Int32 get_checkpointCnt() { }
	// RVA: 0x4083f8c VA: 0x759669bf8c
	public RouteData get_data() { }
	// RVA: 0x4083f94 VA: 0x759669bf94
	public Void .ctor(RouteData data, Map map, IPathFinding pathFinder) { }
	// RVA: 0x40841e0 VA: 0x759669c1e0
	public Void ReconstructRoute(RouteData data) { }
	// RVA: 0x4084518 VA: 0x759669c518
	public Single GetDistToFinal() { }
	// RVA: 0x4084534 VA: 0x759669c534
	public Single GetDistToFinal(GridPosition position) { }
	// RVA: 0x4084614 VA: 0x759669c614
	public Int32 GetIndexInMap(Boolean useExtraRoute) { }
	// RVA: 0x408464c VA: 0x759669c64c
	public Boolean GetIndexInMap(out Int32 routeIndex) { }
	// RVA: 0x408436c VA: 0x759669c36c
	public Void ReconstructNextMap() { }
	// RVA: 0x4084ab4 VA: 0x759669cab4
	public Single GetEstimatedDistToFinalWithoutCheckpoints(Vector2 pos) { }
	// RVA: 0x4084cb4 VA: 0x759669ccb4
	public Vector2 GetPredictFuturePositionWithoutCheckpoints(Vector2 pos, Single predictDist) { }
	// RVA: 0x4085074 VA: 0x759669d074
	public Vector2 GetSpawnPosition() { }
	// RVA: 0x40850dc VA: 0x759669d0dc
	public Vector2 GetSpawnOffset() { }
	// RVA: 0x4085180 VA: 0x759669d180
	public Vector2 GetContDirectionAfterEnd() { }
	// RVA: 0x4085320 VA: 0x759669d320
	public Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x408532c VA: 0x759669d32c
	public Boolean CheckReached(Vector2 pos, Single dist) { }
	// RVA: 0x4085454 VA: 0x759669d454
	public Boolean CheckReached(GridPosition gridPos) { }
	// RVA: 0x40854c4 VA: 0x759669d4c4
	public Boolean CheckReachable(Boolean avoidObstacleLike) { }
	// RVA: 0x4085588 VA: 0x759669d588
	public Boolean CheckReachable(Vector2 pos) { }
	// RVA: 0x4085674 VA: 0x759669d674
	public Boolean CheckReachable(GridPosition gridPos) { }
	// RVA: 0x4085700 VA: 0x759669d700
	public Boolean CheckContainsOffsetCheckpoint(Single tolerance) { }
	// RVA: 0x4085780 VA: 0x759669d780
	public Node[,] GetCheckpointNextMap(Int32 index) { }
	// RVA: 0x40857b0 VA: 0x759669d7b0
	public Node[,] GetTargetNextMap() { }
	// RVA: 0x4084150 VA: 0x759669c150
	private Node[,] _CreateNextMap() { }
	// RVA: 0x40846b4 VA: 0x759669c6b4
	private Void _GenerateNextMap(GridPosition target, Node[,] nextMap) { }
	// RVA: 0x40849a4 VA: 0x759669c9a4
	private Void _ComplementFinalDistance(Node[,] currentNextMap, Node[,] nextNextMap, GridPosition targetPosInNext) { }
	// RVA: 0x4084784 VA: 0x759669c784
	private Void _GenerateNextTurn(GridPosition currentTarget, Node[,] currentNextMap, Node[,] nextNextMap) { }
	// RVA: 0x40857b8 VA: 0x759669d7b8
	private Vector2 _GetNextTurn(Node node, Node targetNodeInNext) { }
	// RVA: 0x4084ad8 VA: 0x759669cad8
	private Single _GetEstimatedDistToFinalWithoutCheckpoints(Vector2 pos, out GridPosition gridPos, out Node curNode) { }
	// RVA: 0x4085914 VA: 0x759669d914
	private static Void .cctor() { }
}
```