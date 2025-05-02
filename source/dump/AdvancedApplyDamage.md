# AdvancedApplyDamage

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `DamageType _damageType`

- `String _atkScaleVar`

- `Single _defaultAtkScale`

- `SourceApplyWay _applyWay`

- `Boolean _baseOnHostAtk`

- `Boolean _emitSourceOnCalculateDamage`

- `SourceAttackType _attackType`

- `Boolean _forceUseProjectileCachedAtk`

- `Boolean _ignoreForSp`

- `DamageTypeMask _ignoreMissFlag`

- `String _modifierKey`

- `Boolean _assignRealDamageToBB`

- `Boolean _skipModifierEvent`

- `FP m_cachedAtk`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`

- `Boolean _TryGetAtkAsHostBased(Entity, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AdvancedApplyDamage : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private DamageType _damageType; // 0x14
	private String _atkScaleVar; // 0x18
	private Single _defaultAtkScale; // 0x20
	private SourceApplyWay _applyWay; // 0x24
	private Boolean _baseOnHostAtk; // 0x28
	private Boolean _emitSourceOnCalculateDamage; // 0x29
	private SourceAttackType _attackType; // 0x2c
	private Boolean _forceUseProjectileCachedAtk; // 0x30
	private Boolean _ignoreForSp; // 0x31
	private DamageTypeMask _ignoreMissFlag; // 0x34
	private String _modifierKey; // 0x38
	private Boolean _assignRealDamageToBB; // 0x40
	private Boolean _skipModifierEvent; // 0x41
	private FP m_cachedAtk; // 0x48
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__SetAtkScale; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x20
	private static DelegateBridge __Hotfix0__TryGetAtkAsHostBased; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3c458 VA: 0x7594554458
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3c4c0 VA: 0x75945544c0
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3c528 VA: 0x7594554528
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3cb40 VA: 0x7594554b40
	protected virtual FP _SetAtkScale(Blackboard blackboard, Entity source) { }
	// RVA: 0x1f3cc20 VA: 0x7594554c20
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3c9e0 VA: 0x75945549e0
	private Boolean _TryGetAtkAsHostBased(Entity source, out FP atk) { }
	// RVA: 0x1f3cd24 VA: 0x7594554d24
	public Void .ctor() { }
}
```