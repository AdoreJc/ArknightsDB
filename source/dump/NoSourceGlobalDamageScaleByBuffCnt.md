# NoSourceGlobalDamageScaleByBuffCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `DamageType _damageType`

- `String _damageKey`

- `String _buffKey`

- `TargetOptions _targetOptions`

- `Boolean _ignoreForSp`

- `Boolean _damageWithoutModify`

- `SourceAttackType _attackType`

- `Boolean _isEnvDamage`

- `Boolean _noSourceDamage`

- `TargetOptions m_targetOptions`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NoSourceGlobalDamageScaleByBuffCnt : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _sourceType; // 0x10
	private DamageType _damageType; // 0x14
	private String _damageKey; // 0x18
	private String _buffKey; // 0x20
	private TargetOptions _targetOptions; // 0x28
	private Boolean _ignoreForSp; // 0x88
	private Boolean _damageWithoutModify; // 0x89
	private SourceAttackType _attackType; // 0x8c
	private Boolean _isEnvDamage; // 0x90
	private Boolean _noSourceDamage; // 0x91
	private TargetOptions m_targetOptions; // 0x98
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f3db50 VA: 0x7594555b50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3dbb8 VA: 0x7594555bb8
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f3dc20 VA: 0x7594555c20
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3e19c VA: 0x759455619c
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f3e214 VA: 0x7594556214
	public Void .ctor() { }
}
```