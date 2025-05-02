# DurBusAbilityCheckPassengers

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _markCurrentPassengers`

- `Boolean _setSearchPassengersStatus`

- `Boolean _searchPassengersStatus`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DurBusAbilityCheckPassengers : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _markCurrentPassengers; // 0x20
	private Boolean _setSearchPassengersStatus; // 0x21
	private Boolean _searchPassengersStatus; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f952a4 VA: 0x75945ad2a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9530c VA: 0x75945ad30c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f95598 VA: 0x75945ad598
	public Void .ctor() { }
}
```