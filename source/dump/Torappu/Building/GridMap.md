# GridMap

**Namespace:** `Torappu.Building`


## Fields

- `Int32 m_verticalEdgeIndexOffset`

- `TwoPointPathFinder m_pathFinder`

- `Int32 <width>k__BackingField`

- `Int32 <height>k__BackingField`


## Properties

- `Int32 width`

- `Int32 height`

- `GridPosition size`

- `Int32 nodeCnt`

- `GridNode Item`

- `GridNode Item`


## Methods

- `Int32 get_width()`

- `Void set_width(Int32)`

- `Int32 get_height()`

- `Void set_height(Int32)`

- `GridPosition get_size()`

- `Int32 get_nodeCnt()`

- `GridNode get_Item(Int32, Int32)`

- `GridNode get_Item(GridPosition)`

- `Path FindPath(GridPosition, GridPosition)`

- `Path FindShortestPath(GridPosition, GridPosition[], Func`3)`

- `Path FindFirstPath(GridPosition, GridPosition[])`

- `Boolean CheckGridValid(GridPosition)`

- `Boolean CheckEmptyGrid(GridPosition)`

- `Boolean TryGetGrid(GridPosition, out)`

- `Boolean CheckOnBoundary(GridPosition, Boolean)`

- `Boolean PickRandomEmptyGrid(out)`

- `Boolean PickRandomGrid(out, Func`3, Boolean)`

- `Boolean PickRandomGridWithWeight(out, Func`3, Boolean)`

- `Boolean PickFirstGrid(out, Func`3, Boolean)`

- `Boolean AddObstacle(ObstaclePoint)`

- `Void AddObstacle(ObstacleRect)`

- `Boolean RemoveObstacle(GridPosition)`

- `Void RemoveObstacle(GridPosition, GridPosition)`

- `Boolean AddObject(GridPosition, IGridObject)`

- `Boolean RemoveObject(IGridObject)`

- `Void PopulateObstacles(List`1)`

- `Void _BuildGraph(Int32, Int32)`

- `EdgeNode _GetEdge(GridPosition, Direction)`

- `Int32 _GetEdgeIndex(GridPosition, Direction)`

- `Boolean _TryParseEdgeIndex(Int32, out, out)`

- `Boolean _AddObstacle(ObstaclePoint)`

- `Void _AddObstacle(ObstacleRect)`

- `Boolean _RemoveObstacle(GridPosition)`

- `Void _RemoveObstacle(GridPosition, GridPosition)`

- `Boolean _AddObject(GridPosition, IGridObject)`

- `Boolean _RemoveObject(IGridObject)`

- `Void _ClearCachedPath()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class GridMap
{
	private const Int32 HORIZONTAL_EDGE_NODE_COST; // 0x0
	private const Int32 VERTICAL_EDGE_NODE_COST; // 0x0
	private static List`1 s_sharedNodeList; // 0x0
	private Int32 m_verticalEdgeIndexOffset; // 0x10
	private Dictionary`2 m_objToPosMap; // 0x18
	private Dictionary`2 m_cachedMapPath; // 0x20
	private GridNode[,] m_map; // 0x28
	private EdgeNode[] m_edges; // 0x30
	private TwoPointPathFinder m_pathFinder; // 0x38
	private Heap`1 m_emptyGrids; // 0x40
	private Int32 <width>k__BackingField; // 0x48
	private Int32 <height>k__BackingField; // 0x4c

	public Int32 width { get; set; }
	public Int32 height { get; set; }
	public GridPosition size { get; }
	public Int32 nodeCnt { get; }
	public GridNode Item { get; }
	public GridNode Item { get; }

	// RVA: 0x377e1a4 VA: 0x7595d961a4
	public Int32 get_width() { }
	// RVA: 0x377e1ac VA: 0x7595d961ac
	private Void set_width(Int32 value) { }
	// RVA: 0x377e1b4 VA: 0x7595d961b4
	public Int32 get_height() { }
	// RVA: 0x377e1bc VA: 0x7595d961bc
	private Void set_height(Int32 value) { }
	// RVA: 0x377e1c4 VA: 0x7595d961c4
	public GridPosition get_size() { }
	// RVA: 0x377e1e8 VA: 0x7595d961e8
	public Int32 get_nodeCnt() { }
	// RVA: 0x377e20c VA: 0x7595d9620c
	public GridNode get_Item(Int32 r, Int32 c) { }
	// RVA: 0x377e258 VA: 0x7595d96258
	public GridNode get_Item(GridPosition pos) { }
	// RVA: 0x377e2a8 VA: 0x7595d962a8
	public Void .ctor(Int32 width, Int32 height, Options options) { }
	// RVA: 0x377f750 VA: 0x7595d97750
	public Path FindPath(GridPosition source, GridPosition destination) { }
	// RVA: 0x377fbf0 VA: 0x7595d97bf0
	public Path FindShortestPath(GridPosition source, GridPosition[] destinations, Func`3 validator) { }
	// RVA: 0x377fe1c VA: 0x7595d97e1c
	public Path FindFirstPath(GridPosition source, GridPosition[] destinations) { }
	// RVA: 0x377f8d4 VA: 0x7595d978d4
	public Boolean CheckGridValid(GridPosition pos) { }
	// RVA: 0x377ff68 VA: 0x7595d97f68
	public Boolean CheckEmptyGrid(GridPosition pos) { }
	// RVA: 0x377ffe0 VA: 0x7595d97fe0
	public Boolean TryGetGrid(GridPosition pos, out GridNode node) { }
	// RVA: 0x3780044 VA: 0x7595d98044
	public Boolean CheckOnBoundary(GridPosition pos, Boolean exceptFirstRow) { }
	// RVA: 0x3780088 VA: 0x7595d98088
	public Boolean PickRandomEmptyGrid(out GridPosition pos) { }
	// RVA: 0x378015c VA: 0x7595d9815c
	public Boolean PickRandomGrid(out GridPosition pos, Func`3 validator, Boolean onlyEmpty) { }
	// RVA: 0x37804b0 VA: 0x7595d984b0
	public Boolean PickRandomGridWithWeight(out GridPosition pos, Func`3 weightGetter, Boolean onlyEmpty) { }
	// RVA: 0x3780880 VA: 0x7595d98880
	public Boolean PickFirstGrid(out GridPosition pos, Func`3 validator, Boolean onlyEmpty) { }
	// RVA: 0x3780a04 VA: 0x7595d98a04
	public Boolean AddObstacle(ObstaclePoint pos) { }
	// RVA: 0x3780a84 VA: 0x7595d98a84
	public Void AddObstacle(ObstacleRect rect) { }
	// RVA: 0x3780ab8 VA: 0x7595d98ab8
	public Boolean RemoveObstacle(GridPosition pos) { }
	// RVA: 0x3780ba0 VA: 0x7595d98ba0
	public Void RemoveObstacle(GridPosition pos, GridPosition size) { }
	// RVA: 0x3780c7c VA: 0x7595d98c7c
	public Boolean AddObject(GridPosition pos, IGridObject obj) { }
	// RVA: 0x3780ca8 VA: 0x7595d98ca8
	public Boolean RemoveObject(IGridObject obj) { }
	// RVA: 0x3780fd0 VA: 0x7595d98fd0
	public Void PopulateObstacles(List`1 obstacles) { }
	// RVA: 0x377e7d8 VA: 0x7595d967d8
	private Void _BuildGraph(Int32 width, Int32 height) { }
	// RVA: 0x3781508 VA: 0x7595d99508
	private EdgeNode _GetEdge(GridPosition pos, Direction dir) { }
	// RVA: 0x3781600 VA: 0x7595d99600
	private Int32 _GetEdgeIndex(GridPosition pos, Direction dir) { }
	// RVA: 0x3781260 VA: 0x7595d99260
	private Boolean _TryParseEdgeIndex(Int32 index, out GridPosition pos, out Direction dir) { }
	// RVA: 0x377ef8c VA: 0x7595d96f8c
	private Boolean _AddObstacle(ObstaclePoint pos) { }
	// RVA: 0x377f07c VA: 0x7595d9707c
	private Void _AddObstacle(ObstacleRect rect) { }
	// RVA: 0x3780abc VA: 0x7595d98abc
	private Boolean _RemoveObstacle(GridPosition pos) { }
	// RVA: 0x3780ba4 VA: 0x7595d98ba4
	private Void _RemoveObstacle(GridPosition pos, GridPosition size) { }
	// RVA: 0x377f1ac VA: 0x7595d971ac
	private Boolean _AddObject(GridPosition pos, IGridObject obj) { }
	// RVA: 0x3780cd4 VA: 0x7595d98cd4
	private Boolean _RemoveObject(IGridObject obj) { }
	// RVA: 0x3780a34 VA: 0x7595d98a34
	private Void _ClearCachedPath() { }
	// RVA: 0x3781890 VA: 0x7595d99890
	private static Void .cctor() { }
}
```