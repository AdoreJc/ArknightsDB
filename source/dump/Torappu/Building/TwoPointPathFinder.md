# TwoPointPathFinder

**Namespace:** `Torappu.Building`


## Fields

- `Heap m_openList`

- `GridMap <map>k__BackingField`


## Properties

- `GridMap map`


## Methods

- `GridMap get_map()`

- `Void set_map(GridMap)`

- `InternalNode _GetOrCreateNode(Node)`

- `Void _OptimizePath()`

- `Boolean _RaycastBresenhamLine(GridPosition, GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class TwoPointPathFinder
{
	private Heap m_openList; // 0x10
	private HashSet`1 m_closedList; // 0x18
	private Dictionary`2 m_nodeMap; // 0x20
	private List`1 m_path; // 0x28
	private GridMap <map>k__BackingField; // 0x30

	protected GridMap map { get; set; }

	// RVA: 0x3782194 VA: 0x7595d9a194
	protected GridMap get_map() { }
	// RVA: 0x378219c VA: 0x7595d9a19c
	private Void set_map(GridMap value) { }
	// RVA: 0x377f5b4 VA: 0x7595d975b4
	public Void .ctor(GridMap map) { }
	// RVA: 0x377f90c VA: 0x7595d9790c
	public Node[] FindPath(GridPosition from, GridPosition to, out Int32 retDistance) { }
	// RVA: 0x37823a4 VA: 0x7595d9a3a4
	private InternalNode _GetOrCreateNode(Node rawNode) { }
	// RVA: 0x3782474 VA: 0x7595d9a474
	private static Int32 _GetHeuristicEstimatedCost(Node lhs, Node rhs) { }
	// RVA: 0x3782720 VA: 0x7595d9a720
	private Node[] _ConstructPath(InternalNode node) { }
	// RVA: 0x37828e8 VA: 0x7595d9a8e8
	private Void _OptimizePath() { }
	// RVA: 0x3782c58 VA: 0x7595d9ac58
	private Boolean _RaycastBresenhamLine(GridPosition a, GridPosition b) { }
}
```