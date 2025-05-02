# WaitForSecondsCheckpoint

**Namespace:** ` `


## Fields

- `FP m_time`


## Properties

- `Boolean isReached`


## Methods

- `Boolean get_isReached()`

- `Void Skip()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class WaitForSecondsCheckpoint : Checkpoint
{
	private FP m_time; // 0x20

	public Boolean isReached { get; }

	// RVA: 0x407da28 VA: 0x7596695a28
	public Boolean get_isReached() { }
	// RVA: 0x407ca58 VA: 0x7596694a58
	public Void .ctor(CheckpointData data, BasicCursor cursor) { }
	// RVA: 0x407da94 VA: 0x7596695a94
	public override Vector2 GetNextDirection(Vector2 pos) { }
	// RVA: 0x407dad4 VA: 0x7596695ad4
	public override GridPosition GetNextGrid(GridPosition grid) { }
	// RVA: 0x407dadc VA: 0x7596695adc
	public override Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x407dae0 VA: 0x7596695ae0
	public override Boolean CheckReached(GridPosition grid) { }
	// RVA: 0x407dae4 VA: 0x7596695ae4
	public override Void OnBegin() { }
	// RVA: 0x407db5c VA: 0x7596695b5c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x407dc1c VA: 0x7596695c1c
	public Void Skip() { }
}
```