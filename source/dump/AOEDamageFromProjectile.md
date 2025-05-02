# AOEDamageFromProjectile

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `DamageType _damageType`

- `SourceApplyWay _sourceApplyWay`

- `TargetOptions _targetOptions`

- `SourceAttackType _attackType`

- `Boolean _useDamageFromBlackboard`

- `String _damageKey`

- `Boolean _createEffect`

- `Single _circleRadius`

- `ActionNode _conditionActions`

- `String _succScaleKey`

- `String _failScaleKey`

- `TargetOptions m_targetOptions`

- `SideType m_sideType`

- `PlayerSide m_playerSide`

- `Boolean m_inited`

- `FP m_cachedAtk`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void _DealDamage(Entity, Entity, FP, String)`

- `Void _DealDamageFromBlackboard(Entity, Entity, FP, String, FP)`

- `Void PreprocessForProjectile(Entity)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AOEDamageFromProjectile : ActionNode, IDamageOrHealSourceNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private DamageType _damageType; // 0x14
	private SourceApplyWay _sourceApplyWay; // 0x18
	private TargetOptions _targetOptions; // 0x20
	private BuffData[] _buffs; // 0x80
	private SourceAttackType _attackType; // 0x88
	private Boolean _useDamageFromBlackboard; // 0x8c
	private String _damageKey; // 0x90
	private Boolean _createEffect; // 0x98
	private Single _circleRadius; // 0x9c
	private ActionNode _conditionActions; // 0xa0
	private String _succScaleKey; // 0xa8
	private String _failScaleKey; // 0xb0
	private TargetOptions m_targetOptions; // 0xb8
	private SideType m_sideType; // 0x118
	private PlayerSide m_playerSide; // 0x11c
	private Boolean m_inited; // 0x120
	private FP m_cachedAtk; // 0x128
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__DealDamage; // 0x18
	private static DelegateBridge __Hotfix0__DealDamageFromBlackboard; // 0x20
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f47a50 VA: 0x759455fa50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f47ab8 VA: 0x759455fab8
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f47b20 VA: 0x759455fb20
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f48390 VA: 0x7594560390
	private Void _DealDamage(Entity source, Entity target, FP damageScale, String effectKey) { }
	// RVA: 0x1f485a0 VA: 0x75945605a0
	private Void _DealDamageFromBlackboard(Entity source, Entity target, FP damageScale, String effectKey, FP damageValue) { }
	// RVA: 0x1f48750 VA: 0x7594560750
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f48828 VA: 0x7594560828
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f488dc VA: 0x75945608dc
	public Void .ctor() { }
}
```