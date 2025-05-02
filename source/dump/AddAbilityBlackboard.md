# AddAbilityBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKeys`

- `String _addBlackboardKey`

- `Boolean _fromOwnerBlackBoard`

- `Boolean _isMinus`

- `Boolean _isLimitValue`

- `String _limitValueKey`

- `Single _limitValue`

- `String _abilityName`

- `ActionTargetType _abilityOwnerType`

- `Boolean _isUpdateSelector`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddAbilityBlackboard : ActionNode
{
	private String _blackboardKeys; // 0x10
	private String _addBlackboardKey; // 0x18
	private Boolean _fromOwnerBlackBoard; // 0x20
	private Boolean _isMinus; // 0x21
	private Boolean _isLimitValue; // 0x22
	private String _limitValueKey; // 0x28
	private Single _limitValue; // 0x30
	private String _abilityName; // 0x38
	private ActionTargetType _abilityOwnerType; // 0x40
	private Boolean _isUpdateSelector; // 0x44
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f98614 VA: 0x75945b0614
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9867c VA: 0x75945b067c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f989d4 VA: 0x75945b09d4
	public Void .ctor() { }
}
```