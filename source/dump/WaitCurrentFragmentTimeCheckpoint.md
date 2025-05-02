# WaitCurrentFragmentTimeCheckpoint

**Namespace:** ` `


## Properties

- `Boolean isReached`


## Methods

- `Boolean get_isReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class WaitCurrentFragmentTimeCheckpoint : Checkpoint
{

	public Boolean isReached { get; }

	// RVA: 0x407deac VA: 0x7596695eac
	public Boolean get_isReached() { }
	// RVA: 0x407ca64 VA: 0x7596694a64
	public Void .ctor(CheckpointData data, BasicCursor cursor) { }
	// RVA: 0x407df8c VA: 0x7596695f8c
	public override Vector2 GetNextDirection(Vector2 pos) { }
	// RVA: 0x407dfcc VA: 0x7596695fcc
	public override GridPosition GetNextGrid(GridPosition grid) { }
	// RVA: 0x407dfd4 VA: 0x7596695fd4
	public override Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x407dfd8 VA: 0x7596695fd8
	public override Boolean CheckReached(GridPosition grid) { }
}
```