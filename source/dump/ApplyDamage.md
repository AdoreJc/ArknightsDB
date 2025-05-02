# ApplyDamage

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `SourceApplyWay _applyWay`

- `SourceAttackType _attackType`

- `Boolean _useDynamicAttackType`

- `FP m_cachedAtk`

- `FP m_atkScale`


## Properties

- `ActionPurposeMask purposeMask`

- `FP atkScale`

- `FP cacheAtk`

- `DamageType damageType`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `FP get_atkScale()`

- `Void set_atkScale(FP)`

- `FP get_cacheAtk()`

- `DamageType get_damageType()`

- `Modifier CreateDamageModifierWithMainTarget(Entity, Entity, Entity)`

- `Void _SetAttackTypeByMainTarget(Entity, Entity)`

- `Void PreprocessForProjectile(Entity)`

- `Void DeliverPreprocessPara(ApplyDamage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyDamage : ActionNode, IDamageOrHealSourceNode
{
	protected DamageType _damageType; // 0x10
	protected SourceApplyWay _applyWay; // 0x14
	protected SourceAttackType _attackType; // 0x18
	protected Boolean _useDynamicAttackType; // 0x1c
	protected FP m_cachedAtk; // 0x20
	private FP m_atkScale; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_get_atkScale; // 0x10
	private static DelegateBridge __Hotfix0_set_atkScale; // 0x18
	private static DelegateBridge __Hotfix0_get_cacheAtk; // 0x20
	private static DelegateBridge __Hotfix0_get_damageType; // 0x28
	private static DelegateBridge __Hotfix0_Execute; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38
	private static DelegateBridge _c__Hotfix1_ctor; // 0x40
	private static DelegateBridge __Hotfix0_CreateDamageModifier; // 0x48
	private static DelegateBridge __Hotfix0_CreateDamageModifierWithMainTarget; // 0x50
	private static DelegateBridge __Hotfix0__SetAttackTypeByMainTarget; // 0x58
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x60
	private static DelegateBridge __Hotfix0_DeliverPreprocessPara; // 0x68

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }
	public FP atkScale { get; set; }
	public FP cacheAtk { get; }
	public DamageType damageType { get; }

	// RVA: 0x1f39e8c VA: 0x7594551e8c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f39ef4 VA: 0x7594551ef4
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f39f5c VA: 0x7594551f5c
	public FP get_atkScale() { }
	// RVA: 0x1f39fc4 VA: 0x7594551fc4
	public Void set_atkScale(FP value) { }
	// RVA: 0x1f3a040 VA: 0x7594552040
	public FP get_cacheAtk() { }
	// RVA: 0x1f3a0a8 VA: 0x75945520a8
	public DamageType get_damageType() { }
	// RVA: 0x1f3a110 VA: 0x7594552110
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3a3b8 VA: 0x75945523b8
	public Void .ctor() { }
	// RVA: 0x1f3a468 VA: 0x7594552468
	public Void .ctor(DamageType damageType, SourceApplyWay applyWay, FP atkScale, SourceAttackType attackType, Boolean useDynamicAttackType) { }
	// RVA: 0x1f3a578 VA: 0x7594552578
	public virtual Modifier CreateDamageModifier(Entity source, Entity target) { }
	// RVA: 0x1f3a734 VA: 0x7594552734
	public Modifier CreateDamageModifierWithMainTarget(Entity source, Entity target, Entity mainTarget) { }
	// RVA: 0x1f3a2c8 VA: 0x75945522c8
	private Void _SetAttackTypeByMainTarget(Entity target, Entity mainTarget) { }
	// RVA: 0x1f3a810 VA: 0x7594552810
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3a914 VA: 0x7594552914
	public Void DeliverPreprocessPara(ApplyDamage anotherNode) { }
}
```