# CheckEnemyCurrentCheckpoint

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyCurrentCheckpoint : ActionNode
{
	private CheckpointType[] _checkpointTypes; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2ff54 VA: 0x7594547f54
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2ffbc VA: 0x7594547fbc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f301a8 VA: 0x75945481a8
	public Void .ctor() { }
}
```