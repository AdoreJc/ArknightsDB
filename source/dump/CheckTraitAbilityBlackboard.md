# CheckTraitAbilityBlackboard

**Namespace:** ` `


## Fields

- `String _leftBlackboardKey`

- `String _rightBlackboardKey`

- `Single _rightValue`

- `CompareType _compareType`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTraitAbilityBlackboard : ActionNode
{
	private String _leftBlackboardKey; // 0x10
	private String _rightBlackboardKey; // 0x18
	private Single _rightValue; // 0x20
	private CompareType _compareType; // 0x24
	private ActionTargetType _targetType; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef1c30 VA: 0x7594509c30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef1c98 VA: 0x7594509c98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef1f28 VA: 0x7594509f28
	public Void .ctor() { }
}
```