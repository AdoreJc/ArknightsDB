# InverseDamage

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `SideType _sideMask`

- `SourceAttackType _attackType`

- `Boolean _hasSource`

- `Boolean _skipSourceEvent`

- `ActionTargetType _sourceType`

- `Boolean _skipModifierEvent`

- `Boolean _fixValue`

- `String _damageValueKey`

- `Boolean _filterModifierCancelled`


## Properties

- `ActionPurposeMask purposeMask`

- `Boolean fixValue`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Boolean get_fixValue()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InverseDamage : ActionNode, IDamageOrHealSourceNode
{
	private DamageType _damageType; // 0x10
	private SideType _sideMask; // 0x14
	private SourceAttackType _attackType; // 0x18
	private Boolean _hasSource; // 0x1c
	private Boolean _skipSourceEvent; // 0x1d
	private ActionTargetType _sourceType; // 0x20
	private Boolean _skipModifierEvent; // 0x24
	private Boolean _fixValue; // 0x25
	private String _damageValueKey; // 0x28
	private Boolean _filterModifierCancelled; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_get_fixValue; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }
	public Boolean fixValue { get; }

	// RVA: 0x1f40400 VA: 0x7594558400
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f40468 VA: 0x7594558468
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f404d0 VA: 0x75945584d0
	public Boolean get_fixValue() { }
	// RVA: 0x1f40538 VA: 0x7594558538
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f409e8 VA: 0x75945589e8
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f40a60 VA: 0x7594558a60
	public Void .ctor() { }
}
```