# CheckDistanceToProjectileCenter

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDistanceToProjectileCenter : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f779b4 VA: 0x759458f9b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f77a1c VA: 0x759458fa1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f77cdc VA: 0x759458fcdc
	public Void .ctor() { }
}
```