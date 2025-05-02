# DurBusAbilityReleasePassenger

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _releaseLastOnly`

- `Boolean _releaseOnProjectileTracePos`

- `Boolean _releaseOnProjectileCurrentPos`

- `Boolean _releaseMarkedOnly`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DurBusAbilityReleasePassenger : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _releaseLastOnly; // 0x20
	private Boolean _releaseOnProjectileTracePos; // 0x21
	private Boolean _releaseOnProjectileCurrentPos; // 0x22
	private Boolean _releaseMarkedOnly; // 0x23
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f94b00 VA: 0x75945acb00
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f94b68 VA: 0x75945acb68
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f94e84 VA: 0x75945ace84
	public Void .ctor() { }
}
```