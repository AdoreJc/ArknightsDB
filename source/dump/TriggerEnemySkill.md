# TriggerEnemySkill

**Namespace:** ` `


## Fields

- `String _skillName`

- `Boolean _checkSkillActive`

- `Boolean _checkSkillReady`

- `ActionTargetType _ownerType`

- `ActionTargetType _targetType`

- `Boolean _interruptCurAbility`

- `Boolean _interruptCurAbilityUnlessItIsExpectedAbility`

- `Boolean _assignCombatAbility`

- `Boolean _forceFindTargetBySkillSelector`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerEnemySkill : ActionNode
{
	private String _skillName; // 0x10
	private Boolean _checkSkillActive; // 0x18
	private Boolean _checkSkillReady; // 0x19
	private ActionTargetType _ownerType; // 0x1c
	private ActionTargetType _targetType; // 0x20
	private Boolean _interruptCurAbility; // 0x24
	private Boolean _interruptCurAbilityUnlessItIsExpectedAbility; // 0x25
	private Boolean _assignCombatAbility; // 0x26
	private Boolean _forceFindTargetBySkillSelector; // 0x27
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f939d0 VA: 0x75945ab9d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f93a38 VA: 0x75945aba38
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f93fb8 VA: 0x75945abfb8
	public Void .ctor() { }
}
```