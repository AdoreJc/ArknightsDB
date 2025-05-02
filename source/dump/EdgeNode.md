# EdgeNode

**Namespace:** ` `


## Fields

- `Direction <dir>k__BackingField`


## Properties

- `Direction dir`

- `Boolean isHorizontal`

- `Boolean isVertical`


## Methods

- `Direction get_dir()`

- `Void set_dir(Direction)`

- `Boolean get_isHorizontal()`

- `Boolean get_isVertical()`

- `Void MakeEmpty(GridNode)`

- `Void Occupy(GridNode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EdgeNode : Node
{
	public List`1 occupyGrids; // 0x28
	private Direction <dir>k__BackingField; // 0x30

	public Direction dir { get; set; }
	public override Boolean isWalkable { get; }
	public override Int32 enterCost { get; }
	public Boolean isHorizontal { get; }
	public Boolean isVertical { get; }

	// RVA: 0x3781cb8 VA: 0x7595d99cb8
	public Direction get_dir() { }
	// RVA: 0x3781cc0 VA: 0x7595d99cc0
	private Void set_dir(Direction value) { }
	// RVA: 0x3781cc8 VA: 0x7595d99cc8
	public override Boolean get_isWalkable() { }
	// RVA: 0x3781d18 VA: 0x7595d99d18
	public override Int32 get_enterCost() { }
	// RVA: 0x37815f0 VA: 0x7595d995f0
	public Boolean get_isHorizontal() { }
	// RVA: 0x3781d30 VA: 0x7595d99d30
	public Boolean get_isVertical() { }
	// RVA: 0x37813b4 VA: 0x7595d993b4
	public Void .ctor(GridPosition pos, Direction dir) { }
	// RVA: 0x3781d44 VA: 0x7595d99d44
	public override Vector2 GetMovePos() { }
	// RVA: 0x3781a74 VA: 0x7595d99a74
	public Void MakeEmpty(GridNode node) { }
	// RVA: 0x3781acc VA: 0x7595d99acc
	public Void Occupy(GridNode node) { }
	// RVA: 0x3781e0c VA: 0x7595d99e0c
	public override String ToString() { }
}
```