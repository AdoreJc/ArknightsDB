# PatrolMoveCheckpoint

**Namespace:** ` `


## Fields

- `Int32 m_loopCursor`


## Methods

- `Boolean IsValidPatrolCheckPoint(Checkpoint)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class PatrolMoveCheckpoint : MoveCheckpoint
{
	private const Int32 LOOP_MAX; // 0x0
	private Int32 m_loopCursor; // 0x30


	// RVA: 0x407ca6c VA: 0x7596694a6c
	public Void .ctor(CheckpointData data, Node[,] nextMap, BasicCursor cursor) { }
	// RVA: 0x407d624 VA: 0x7596695624
	private Boolean IsValidPatrolCheckPoint(Checkpoint cp) { }
	// RVA: 0x407d650 VA: 0x7596695650
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x407d658 VA: 0x7596695658
	public override Int32 NextCursor(Int32 cur_cursor) { }
}
```