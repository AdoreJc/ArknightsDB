# CheckEnemyRouteCheckpoint

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `CheckpointTypeMask _routeCheckpointMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyRouteCheckpoint : ActionNode
{
	private ActionTargetType _target; // 0x10
	private CheckpointTypeMask _routeCheckpointMask; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f30218 VA: 0x7594548218
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f30280 VA: 0x7594548280
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3041c VA: 0x759454841c
	public Void .ctor() { }
}
```