# WaitForPlayTimeCheckpoint

**Namespace:** ` `


## Properties

- `Boolean isReached`


## Methods

- `Boolean get_isReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class WaitForPlayTimeCheckpoint : Checkpoint
{

	public Boolean isReached { get; }

	// RVA: 0x407dc7c VA: 0x7596695c7c
	public Boolean get_isReached() { }
	// RVA: 0x407ca5c VA: 0x7596694a5c
	public Void .ctor(CheckpointData data, BasicCursor cursor) { }
	// RVA: 0x407dd2c VA: 0x7596695d2c
	public override Vector2 GetNextDirection(Vector2 pos) { }
	// RVA: 0x407dd6c VA: 0x7596695d6c
	public override GridPosition GetNextGrid(GridPosition grid) { }
	// RVA: 0x407dd74 VA: 0x7596695d74
	public override Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x407dd78 VA: 0x7596695d78
	public override Boolean CheckReached(GridPosition grid) { }
}
```