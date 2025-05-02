# MoveCheckpoint

**Namespace:** ` `


## Fields

- `Vector2 m_offset`


## Methods

- `Vector2 GetNextTurn(GridPosition)`

- `Single GetEstimatedDistToFinal(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class MoveCheckpoint : PosRelatedCheckpoint
{
	private Vector2 m_offset; // 0x20
	private Node[,] m_nextmap; // 0x28

	public override GridPosition targetGrid { get; }
	public override Vector2 targetPos { get; }

	// RVA: 0x407cdfc VA: 0x7596694dfc
	public override GridPosition get_targetGrid() { }
	// RVA: 0x407ce18 VA: 0x7596694e18
	public override Vector2 get_targetPos() { }
	// RVA: 0x407ca20 VA: 0x7596694a20
	public Void .ctor(CheckpointData data, Node[,] nextMap, BasicCursor cursor) { }
	// RVA: 0x407ce90 VA: 0x7596694e90
	public override Vector2 GetNextDirection(Vector2 pos) { }
	// RVA: 0x407d070 VA: 0x7596695070
	public override GridPosition GetNextGrid(GridPosition grid) { }
	// RVA: 0x407d0c8 VA: 0x75966950c8
	public Vector2 GetNextTurn(GridPosition grid) { }
	// RVA: 0x407d120 VA: 0x7596695120
	public override Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x407d2ac VA: 0x75966952ac
	public override Boolean CheckReached(GridPosition grid) { }
	// RVA: 0x407d3b0 VA: 0x75966953b0
	public Single GetEstimatedDistToFinal(Vector2 pos) { }
	// RVA: 0x407d57c VA: 0x759669557c
	public override Void OnBegin() { }
}
```