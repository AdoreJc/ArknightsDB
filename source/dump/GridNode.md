# GridNode

**Namespace:** ` `


## Fields

- `State <state>k__BackingField`

- `UInt32 objectId`

- `Object objectRef`


## Properties

- `State state`


## Methods

- `State get_state()`

- `Void set_state(State)`

- `Void MakeEmpty()`

- `Void Abandon(Byte)`

- `Void Occupy(IGridObject, Byte)`

- `Int32 CompareTo(GridNode)`

- `Byte GetEdgeWalkableMask()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GridNode : Node, IComparable`1
{
	private State <state>k__BackingField; // 0x24
	public EdgeNode[] edges; // 0x28
	public UInt32 objectId; // 0x30
	public Object objectRef; // 0x38

	public State state { get; set; }
	public override Boolean isWalkable { get; }
	public override Int32 enterCost { get; }

	// RVA: 0x37819e0 VA: 0x7595d999e0
	public State get_state() { }
	// RVA: 0x37819e8 VA: 0x7595d999e8
	private Void set_state(State value) { }
	// RVA: 0x37819f0 VA: 0x7595d999f0
	public override Boolean get_isWalkable() { }
	// RVA: 0x3781a00 VA: 0x7595d99a00
	public override Int32 get_enterCost() { }
	// RVA: 0x37811f0 VA: 0x7595d991f0
	public Void .ctor(GridPosition pos) { }
	// RVA: 0x3781a08 VA: 0x7595d99a08
	public override Vector2 GetMovePos() { }
	// RVA: 0x37816e4 VA: 0x7595d996e4
	public Void MakeEmpty() { }
	// RVA: 0x378163c VA: 0x7595d9963c
	public Void Abandon(Byte edgeWalkableMask) { }
	// RVA: 0x3781760 VA: 0x7595d99760
	public Void Occupy(IGridObject obj, Byte edgeWalkableMask) { }
	// RVA: 0x3781bb4 VA: 0x7595d99bb4
	public override String ToString() { }
	// RVA: 0x3781c38 VA: 0x7595d99c38
	public Int32 CompareTo(GridNode other) { }
	// RVA: 0x378113c VA: 0x7595d9913c
	public Byte GetEdgeWalkableMask() { }
}
```