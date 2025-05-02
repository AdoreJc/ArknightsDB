# UpdateAttackElementDamageScale

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _epDamageRatioKey`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateAttackElementDamageScale : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _epDamageRatioKey; // 0x18
	private String _abilityName; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f40e30 VA: 0x7594558e30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f40e98 VA: 0x7594558e98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f410b4 VA: 0x75945590b4
	public Void .ctor() { }
}
```