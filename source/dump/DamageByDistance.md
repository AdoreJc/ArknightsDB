# DamageByDistance

**Namespace:** ` `


## Fields

- `Boolean _isInit`

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `SourceAttackType _attackType`

- `DamageType _damageType`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageByDistance : ActionNode, IDamageOrHealSourceNode
{
	private const Int32 MAX_DISTANCE; // 0x0
	private Boolean _isInit; // 0x10
	private ActionTargetType _targetType; // 0x14
	private ActionTargetType _sourceType; // 0x18
	private SourceAttackType _attackType; // 0x1c
	private DamageType _damageType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3f3a0 VA: 0x75945573a0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3f408 VA: 0x7594557408
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3f470 VA: 0x7594557470
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3f8c4 VA: 0x75945578c4
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3f93c VA: 0x759455793c
	public Void .ctor() { }
}
```