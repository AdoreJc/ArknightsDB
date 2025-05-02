# AssignBuffBlackboardFromAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _abilityName`

- `String _assignedBlackboardKey`

- `String _blackboardKeyInAbility`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignBuffBlackboardFromAbility : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _abilityName; // 0x18
	private String _assignedBlackboardKey; // 0x20
	private String _blackboardKeyInAbility; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eee1b4 VA: 0x75945061b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eee21c VA: 0x759450621c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eee404 VA: 0x7594506404
	public Void .ctor() { }
}
```