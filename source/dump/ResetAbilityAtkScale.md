# ResetAbilityAtkScale

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _abilityName`

- `String _atkScale`

- `Boolean _overwriteAtkScale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ResetAbilityAtkScale : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _abilityName; // 0x18
	private String _atkScale; // 0x20
	private Boolean _overwriteAtkScale; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f413d0 VA: 0x75945593d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f41438 VA: 0x7594559438
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f41698 VA: 0x7594559698
	public Void .ctor() { }
}
```