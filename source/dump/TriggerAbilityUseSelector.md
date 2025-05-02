# TriggerAbilityUseSelector

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _excludeTarget`

- `ActionTargetType _excludeTargetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerAbilityUseSelector : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _excludeTarget; // 0x20
	private ActionTargetType _excludeTargetType; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f927ec VA: 0x75945aa7ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f92854 VA: 0x75945aa854
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f93004 VA: 0x75945ab004
	public Void .ctor() { }
}
```