# AssignDamageValueToBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _owner`

- `DamageType _damageType`

- `Boolean _assignValueWithoutCalculate`

- `String _scaleKey`

- `Boolean _assignRealDelta`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignDamageValueToBlackboard : ActionNode
{
	private ActionTargetType _owner; // 0x10
	private DamageType _damageType; // 0x14
	private Boolean _assignValueWithoutCalculate; // 0x18
	private String _scaleKey; // 0x20
	private Boolean _assignRealDelta; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eecec8 VA: 0x7594504ec8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eecf30 VA: 0x7594504f30
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eed270 VA: 0x7594505270
	public Void .ctor() { }
}
```