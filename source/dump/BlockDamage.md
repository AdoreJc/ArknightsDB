# BlockDamage

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Boolean _useDynamicVar`

- `Boolean _allowNegativeDynamicVar`

- `Boolean _useFixedValue`

- `Boolean _showDamageNumber`

- `String _specifyBlockEffect`

- `Boolean _useSource`

- `ActionTargetType _sourceType`

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWayFilter`

- `Boolean _showShieldUI`


## Properties

- `Boolean showShieldUI`

- `DamageTypeMask damageMask`


## Methods

- `Boolean get_showShieldUI()`

- `DamageTypeMask get_damageMask()`

- `Void _AssignDynamicVar(Blackboard, Modifier, FP, FP)`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlockDamage : ActionNode, IEffectSource
{
	private Boolean _filterDamageType; // 0x10
	private DamageTypeMask _damageMask; // 0x14
	private Boolean _useDynamicVar; // 0x18
	private Boolean _allowNegativeDynamicVar; // 0x19
	private Boolean _useFixedValue; // 0x1a
	private Boolean _showDamageNumber; // 0x1b
	private String _specifyBlockEffect; // 0x20
	private Boolean _useSource; // 0x28
	private ActionTargetType _sourceType; // 0x2c
	private Boolean _filterApplyWay; // 0x30
	private SourceApplyWay _applyWayFilter; // 0x34
	private Boolean _showShieldUI; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_showShieldUI; // 0x8
	private static DelegateBridge __Hotfix0_get_damageMask; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0__AssignDynamicVar; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override SourceType allowedSource { get; }
	public Boolean showShieldUI { get; }
	public DamageTypeMask damageMask { get; }

	// RVA: 0x1f42348 VA: 0x759455a348
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f423b0 VA: 0x759455a3b0
	public Boolean get_showShieldUI() { }
	// RVA: 0x1f42418 VA: 0x759455a418
	public DamageTypeMask get_damageMask() { }
	// RVA: 0x1f42480 VA: 0x759455a480
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f42c70 VA: 0x759455ac70
	private Void _AssignDynamicVar(Blackboard blackboard, Modifier modifier, FP dynamicVar, FP damage) { }
	// RVA: 0x1f42de0 VA: 0x759455ade0
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f42ef4 VA: 0x759455aef4
	public Void .ctor() { }
}
```