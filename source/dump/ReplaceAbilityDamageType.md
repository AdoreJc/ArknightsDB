# ReplaceAbilityDamageType

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `DamageType _damageType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReplaceAbilityDamageType : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32[] _modes; // 0x18
	private DamageType _damageType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4176c VA: 0x759455976c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f417d4 VA: 0x75945597d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f41980 VA: 0x7594559980
	public Void .ctor() { }
}
```