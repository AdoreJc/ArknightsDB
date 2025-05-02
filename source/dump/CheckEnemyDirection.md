# CheckEnemyDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Direction _direction`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyDirection : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Direction _direction; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1edb0 VA: 0x7594536db0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1ee18 VA: 0x7594536e18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1ef90 VA: 0x7594536f90
	public Void .ctor() { }
}
```