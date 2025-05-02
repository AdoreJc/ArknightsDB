# LegionModeOnlyGlobalDamageFromCard

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `String _damageKey`

- `TargetOptions _targetOptions`

- `SourceAttackType _attackType`

- `String _effectKey`

- `TargetOptions m_targetOptions`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void _DealDamage(FP, Entity)`

- `Void PreprocessForProjectile(Entity)`

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyGlobalDamageFromCard : ActionNode, IDamageOrHealSourceNode, IBuffSource, IEffectSource
{
	private DamageType _damageType; // 0x10
	private String _damageKey; // 0x18
	private TargetOptions _targetOptions; // 0x20
	private SourceAttackType _attackType; // 0x80
	private BuffData[] _buffs; // 0x88
	private String _effectKey; // 0x90
	private TargetOptions m_targetOptions; // 0x98
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

	// RVA: 0x1f69500 VA: 0x7594581500
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f69568 VA: 0x7594581568
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f695d0 VA: 0x75945815d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f69a8c VA: 0x7594581a8c
	private Void _DealDamage(FP damage, Entity target) { }
	// RVA: 0x1f69c24 VA: 0x7594581c24
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f69c9c VA: 0x7594581c9c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f69d50 VA: 0x7594581d50
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f69e64 VA: 0x7594581e64
	public Void .ctor() { }
}
```