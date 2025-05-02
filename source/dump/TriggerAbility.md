# TriggerAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _checkCanUseAblityFlag`

- `Boolean _castDirectly`

- `Boolean _useFirstActiveAbility`

- `Boolean _useCastResult`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _checkCanUseAblityFlag; // 0x20
	private Boolean _castDirectly; // 0x21
	private Boolean _useFirstActiveAbility; // 0x22
	private Boolean _useCastResult; // 0x23
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f90218 VA: 0x75945a8218
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f90280 VA: 0x75945a8280
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f904e0 VA: 0x75945a84e0
	public Void .ctor() { }
}
```