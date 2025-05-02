# DamageViaEs

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `DamageType _damageType`

- `SourceApplyWay _applyWay`

- `Boolean _ignoreForSp`

- `Boolean _isUndeadable`

- `SourceAttackType _attackType`

- `Boolean _skipModifierEvent`

- `Boolean _noSourceDamage`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageViaEs : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private DamageType _damageType; // 0x18
	private SourceApplyWay _applyWay; // 0x1c
	private Boolean _ignoreForSp; // 0x20
	private Boolean _isUndeadable; // 0x21
	private SourceAttackType _attackType; // 0x24
	private Boolean _skipModifierEvent; // 0x28
	private Boolean _noSourceDamage; // 0x29
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3ff70 VA: 0x7594557f70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3ffd8 VA: 0x7594557fd8
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f40040 VA: 0x7594558040
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f40304 VA: 0x7594558304
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4037c VA: 0x759455837c
	public Void .ctor() { }
}
```