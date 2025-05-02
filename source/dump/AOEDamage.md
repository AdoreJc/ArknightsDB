# AOEDamage

**Namespace:** ` `


## Fields

- `Boolean _useAbilitySourceSide`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `DamageType _damageType`

- `SourceApplyWay _sourceApplyWay`

- `TargetOptions _targetOptions`

- `Boolean _excludeTarget`

- `String _rangeId`

- `Boolean _useRadius`

- `Single _radius`

- `Boolean _useAbilitySelector`

- `String _abilityName`

- `String _damageScale`

- `SourceAttackType _attackType`

- `Boolean _createEffect`

- `String _hitEffectKey`

- `Boolean _useDamageFromBB`

- `String _damageKey`

- `Boolean _isNoSourceDamage`

- `Boolean _checkTargetAlive`

- `TargetOptions m_targetOptions`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void _DealDamage(Entity, Entity, FP, String, Blackboard)`

- `Void PreprocessForProjectile(Entity)`

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AOEDamage : ActionNode, IDamageOrHealSourceNode, IBuffSource, IEffectSource
{
	private Boolean _useAbilitySourceSide; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private ActionTargetType _targetType; // 0x18
	private DamageType _damageType; // 0x1c
	private SourceApplyWay _sourceApplyWay; // 0x20
	private TargetOptions _targetOptions; // 0x28
	private Boolean _excludeTarget; // 0x88
	private String _rangeId; // 0x90
	private Boolean _useRadius; // 0x98
	private Single _radius; // 0x9c
	private Boolean _useAbilitySelector; // 0xa0
	private String _abilityName; // 0xa8
	private String _damageScale; // 0xb0
	private BuffData[] _buffs; // 0xb8
	private SourceAttackType _attackType; // 0xc0
	private Boolean _createEffect; // 0xc4
	private String _hitEffectKey; // 0xc8
	private Boolean _useDamageFromBB; // 0xd0
	private String _damageKey; // 0xd8
	private Boolean _isNoSourceDamage; // 0xe0
	private Boolean _checkTargetAlive; // 0xe1
	private TargetOptions m_targetOptions; // 0xe8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__DealDamage; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x20
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f46294 VA: 0x759455e294
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f462fc VA: 0x759455e2fc
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f46364 VA: 0x759455e364
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f473d4 VA: 0x759455f3d4
	private Void _DealDamage(Entity source, Entity target, FP damageScale, String effectKey, Blackboard blackboard) { }
	// RVA: 0x1f47600 VA: 0x759455f600
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f47678 VA: 0x759455f678
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f4772c VA: 0x759455f72c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f47840 VA: 0x759455f840
	public Void .ctor() { }
}
```