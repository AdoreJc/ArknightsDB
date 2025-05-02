# EnemyFallDown

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _exceptDisappearedEnemy`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyFallDown : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _exceptDisappearedEnemy; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd80b0 VA: 0x75945f00b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd8118 VA: 0x75945f0118
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd82c0 VA: 0x75945f02c0
	public Void .ctor() { }
}
```