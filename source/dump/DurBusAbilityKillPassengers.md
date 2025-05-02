# DurBusAbilityKillPassengers

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _killLastPassenger`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DurBusAbilityKillPassengers : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _killLastPassenger; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f94f34 VA: 0x75945acf34
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f94f9c VA: 0x75945acf9c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f951f4 VA: 0x75945ad1f4
	public Void .ctor() { }
}
```