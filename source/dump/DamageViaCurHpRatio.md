# DamageViaCurHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `DamageType _damageType`

- `SourceApplyWay _applyWay`

- `Boolean _ignoreForSp`

- `Boolean _isUndeadable`

- `SourceAttackType _attackType`

- `Boolean _skipModifierEvent`

- `Boolean _ceilingDamageToInt`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageViaCurHpRatio : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private DamageType _damageType; // 0x14
	private SourceApplyWay _applyWay; // 0x18
	private Boolean _ignoreForSp; // 0x1c
	private Boolean _isUndeadable; // 0x1d
	private SourceAttackType _attackType; // 0x20
	private Boolean _skipModifierEvent; // 0x24
	private Boolean _ceilingDamageToInt; // 0x25
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3eea8 VA: 0x7594556ea8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3ef10 VA: 0x7594556f10
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3ef78 VA: 0x7594556f78
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3f2a8 VA: 0x75945572a8
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3f320 VA: 0x7594557320
	public Void .ctor() { }
}
```