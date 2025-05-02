# UpdateAbilityCoolDown

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`

- `Boolean _loadFromBlackboard`

- `String _coolDownKey`

- `Boolean _useNewPeriod`

- `Single _newPeriod`

- `Boolean _loadAbilityFromBlackboard`

- `Boolean _waitFirstPeriod`

- `Boolean _useAbilityBlackboard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateAbilityCoolDown : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _loadFromBlackboard; // 0x20
	private String _coolDownKey; // 0x28
	private Boolean _useNewPeriod; // 0x30
	private Single _newPeriod; // 0x34
	private Boolean _loadAbilityFromBlackboard; // 0x38
	private Boolean _waitFirstPeriod; // 0x39
	private Boolean _useAbilityBlackboard; // 0x3a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc6ea0 VA: 0x75945deea0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc6f08 VA: 0x75945def08
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc71e4 VA: 0x75945df1e4
	public Void .ctor() { }
}
```