# ModifyAbilityBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKeys`

- `String _fromBlackboardKeys`

- `Boolean fromAbilityBlackBoard`

- `Single _value`

- `Boolean _useOtherAbility`

- `String _abilityName`

- `ActionTargetType _abilityOwnerType`

- `Boolean _isUpdateSelector`

- `Boolean _assignString`

- `String _stringValue`


## Properties

- `Boolean useFromBlackboardKeys`

- `Boolean useOtherAbility`

- `Boolean assignString`


## Methods

- `Boolean get_useFromBlackboardKeys()`

- `Boolean get_useOtherAbility()`

- `Boolean get_assignString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAbilityBlackboard : ActionNode
{
	private String _blackboardKeys; // 0x10
	private String _fromBlackboardKeys; // 0x18
	private Boolean fromAbilityBlackBoard; // 0x20
	private Single _value; // 0x24
	private Boolean _useOtherAbility; // 0x28
	private String _abilityName; // 0x30
	private ActionTargetType _abilityOwnerType; // 0x38
	private Boolean _isUpdateSelector; // 0x3c
	private Boolean _assignString; // 0x3d
	private String _stringValue; // 0x40
	private static DelegateBridge __Hotfix0_get_useFromBlackboardKeys; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_get_useOtherAbility; // 0x10
	private static DelegateBridge __Hotfix0_get_assignString; // 0x18
	private static DelegateBridge __Hotfix0_Execute; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean useFromBlackboardKeys { get; }
	public override SourceType allowedSource { get; }
	private Boolean useOtherAbility { get; }
	private Boolean assignString { get; }

	// RVA: 0x1f97c3c VA: 0x75945afc3c
	public Boolean get_useFromBlackboardKeys() { }
	// RVA: 0x1f97cb4 VA: 0x75945afcb4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f97d1c VA: 0x75945afd1c
	private Boolean get_useOtherAbility() { }
	// RVA: 0x1f97d84 VA: 0x75945afd84
	private Boolean get_assignString() { }
	// RVA: 0x1f97dec VA: 0x75945afdec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9816c VA: 0x75945b016c
	public Void .ctor() { }
}
```