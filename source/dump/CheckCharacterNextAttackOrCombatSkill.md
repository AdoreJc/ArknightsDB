# CheckCharacterNextAttackOrCombatSkill

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharacterNextAttackOrCombatSkill : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2dab8 VA: 0x7594545ab8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2db20 VA: 0x7594545b20
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2dddc VA: 0x7594545ddc
	public Void .ctor() { }
}
```