# AppearAtPosCheckpoint

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class AppearAtPosCheckpoint : PosRelatedCheckpoint
{

	public override GridPosition targetGrid { get; }
	public override Vector2 targetPos { get; }
	public override Boolean needUpdateLocationAfterReached { get; }

	// RVA: 0x407d8cc VA: 0x75966958cc
	public override GridPosition get_targetGrid() { }
	// RVA: 0x407d8e8 VA: 0x75966958e8
	public override Vector2 get_targetPos() { }
	// RVA: 0x407d968 VA: 0x7596695968
	public override Boolean get_needUpdateLocationAfterReached() { }
	// RVA: 0x407ca54 VA: 0x7596694a54
	public Void .ctor(CheckpointData data, BasicCursor cursor) { }
	// RVA: 0x407d970 VA: 0x7596695970
	public override Boolean CheckReached(GridPosition grid) { }
	// RVA: 0x407d978 VA: 0x7596695978
	public override Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x407d980 VA: 0x7596695980
	public override Vector2 GetNextDirection(Vector2 pos) { }
	// RVA: 0x407d9c0 VA: 0x75966959c0
	public override GridPosition GetNextGrid(GridPosition grid) { }
	// RVA: 0x407d9c8 VA: 0x75966959c8
	public override Void OnBegin() { }
}
```