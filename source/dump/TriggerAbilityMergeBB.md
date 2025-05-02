# TriggerAbilityMergeBB

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _checkCanUseAblityFlag`

- `Boolean _castDirectly`

- `Boolean _resetSelector`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerAbilityMergeBB : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _checkCanUseAblityFlag; // 0x20
	private Boolean _castDirectly; // 0x21
	private Boolean _resetSelector; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f90590 VA: 0x75945a8590
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f905f8 VA: 0x75945a85f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f908c4 VA: 0x75945a88c4
	public Void .ctor() { }
}
```