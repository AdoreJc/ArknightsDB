# DamageViaAttr

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `AttributeType _attributeType`

- `Boolean _getAttrFromTarget`

- `DamageType _damageType`

- `SourceApplyWay _applyWay`

- `Boolean _ignoreForSp`

- `Boolean _isUndeadable`

- `SourceAttackType _attackType`

- `String _blackboardKey`

- `Boolean _multiplierByKey`

- `String _multiplierKey`


## Properties

- `ActionPurposeMask purposeMask`

- `Boolean multiplierByKey`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Boolean get_multiplierByKey()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageViaAttr : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private AttributeType _attributeType; // 0x18
	private Boolean _getAttrFromTarget; // 0x1c
	private DamageType _damageType; // 0x20
	private SourceApplyWay _applyWay; // 0x24
	private Boolean _ignoreForSp; // 0x28
	private Boolean _isUndeadable; // 0x29
	private SourceAttackType _attackType; // 0x2c
	private String _blackboardKey; // 0x30
	private Boolean _multiplierByKey; // 0x38
	private String _multiplierKey; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_get_multiplierByKey; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }
	public Boolean multiplierByKey { get; }

	// RVA: 0x1f3f9b8 VA: 0x75945579b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3fa20 VA: 0x7594557a20
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3fa88 VA: 0x7594557a88
	public Boolean get_multiplierByKey() { }
	// RVA: 0x1f3faf0 VA: 0x7594557af0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3fe20 VA: 0x7594557e20
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3fe98 VA: 0x7594557e98
	public Void .ctor() { }
}
```