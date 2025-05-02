# TriggerSpecifiedAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _checkCanUseAblityFlag`

- `Boolean _triggerStealAttrAbility`

- `Boolean _triggerEnergyBuffAbility`

- `Boolean _triggerProjectileToTileOnceAbilityBySubSelector`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerSpecifiedAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _checkCanUseAblityFlag; // 0x20
	private Boolean _triggerStealAttrAbility; // 0x21
	private Boolean _triggerEnergyBuffAbility; // 0x22
	private Boolean _triggerProjectileToTileOnceAbilityBySubSelector; // 0x23
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f90974 VA: 0x75945a8974
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f909dc VA: 0x75945a89dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f90da0 VA: 0x75945a8da0
	public Void .ctor() { }
}
```