# DamageViaMaxHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _getMaxHpFromTarget`

- `DamageType _damageType`

- `SourceApplyWay _applyWay`

- `Boolean _ignoreForSp`

- `Boolean _isUndeadable`

- `SourceAttackType _attackType`

- `Boolean _skipModifierEvent`

- `Boolean _multiplyByKey`

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
public class DamageViaMaxHpRatio : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _getMaxHpFromTarget; // 0x14
	private DamageType _damageType; // 0x18
	private SourceApplyWay _applyWay; // 0x1c
	private Boolean _ignoreForSp; // 0x20
	private Boolean _isUndeadable; // 0x21
	private SourceAttackType _attackType; // 0x24
	private Boolean _skipModifierEvent; // 0x28
	private Boolean _multiplyByKey; // 0x29
	private String _multiplierKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3e930 VA: 0x7594556930
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3e998 VA: 0x7594556998
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3ea00 VA: 0x7594556a00
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3ed80 VA: 0x7594556d80
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3edf8 VA: 0x7594556df8
	public Void .ctor() { }
}
```