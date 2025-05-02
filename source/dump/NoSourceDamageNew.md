# NoSourceDamageNew

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `String _damageKey`

- `Boolean _ignoreForSp`

- `Boolean _damageWithoutModify`

- `SourceAttackType _attackType`

- `Boolean _isEnvDamage`

- `Boolean _isUndeadable`

- `CancelReasonMask _ignoreCancelReasonMask`

- `Boolean _instantKillLikeDamage`

- `Boolean _multiplierByKey`

- `String _multiplierKey`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NoSourceDamageNew : ActionNode, IDamageOrHealSourceNode
{
	private DamageType _damageType; // 0x10
	private String _damageKey; // 0x18
	private Boolean _ignoreForSp; // 0x20
	private Boolean _damageWithoutModify; // 0x21
	private SourceAttackType _attackType; // 0x24
	private Boolean _isEnvDamage; // 0x28
	private Boolean _isUndeadable; // 0x29
	private CancelReasonMask _ignoreCancelReasonMask; // 0x2c
	private Boolean _instantKillLikeDamage; // 0x30
	private Boolean _multiplierByKey; // 0x31
	private String _multiplierKey; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3d5f4 VA: 0x75945555f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3d65c VA: 0x759455565c
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3d6c4 VA: 0x75945556c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3da08 VA: 0x7594555a08
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3da80 VA: 0x7594555a80
	public Void .ctor() { }
}
```