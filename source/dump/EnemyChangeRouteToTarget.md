# EnemyChangeRouteToTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _enemy`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyChangeRouteToTarget : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _enemy; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f586ec VA: 0x75945706ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f58754 VA: 0x7594570754
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f589b0 VA: 0x75945709b0
	public Void .ctor() { }
}
```