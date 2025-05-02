# FixedValueDamage

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `String _damageKey`

- `Boolean _ignoreForSp`

- `SourceAttackType _attackType`

- `Boolean _skipModifierEvent`

- `Boolean _considerUnhurtable`

- `Boolean _noSourceDamage`

- `ActionTargetType _targetType`

- `Boolean _assignRealDamageToBB`

- `Boolean _multiplierByKey`

- `String _multiplierKey`

- `ActionTargetType _damageTargetType`

- `Boolean _triggerOnCalculateDamage`

- `Boolean _isEnvDamage`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FixedValueDamage : ActionNode, IDamageOrHealSourceNode
{
	private DamageType _damageType; // 0x10
	private String _damageKey; // 0x18
	private Boolean _ignoreForSp; // 0x20
	private SourceAttackType _attackType; // 0x24
	private Boolean _skipModifierEvent; // 0x28
	private Boolean _considerUnhurtable; // 0x29
	private Boolean _noSourceDamage; // 0x2a
	private ActionTargetType _targetType; // 0x2c
	private Boolean _assignRealDamageToBB; // 0x30
	private Boolean _multiplierByKey; // 0x31
	private String _multiplierKey; // 0x38
	private ActionTargetType _damageTargetType; // 0x40
	private Boolean _triggerOnCalculateDamage; // 0x44
	private Boolean _isEnvDamage; // 0x45
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3e2c0 VA: 0x75945562c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3e328 VA: 0x7594556328
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3e390 VA: 0x7594556390
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3e7e8 VA: 0x75945567e8
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3e860 VA: 0x7594556860
	public Void .ctor() { }
}
```