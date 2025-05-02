# BleedingDamagePerSec

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `String _damageKey`

- `String _baseDamageKey`

- `String _durationToIncreaseKey`

- `Boolean _ignoreForSp`

- `SourceAttackType _attackType`

- `Boolean _isEnvDamage`

- `Boolean _isRatioToMaxHp`

- `Boolean _isIncreasingToCap`

- `Boolean _skipModifierEvent`

- `ElementType _elementDamageType`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BleedingDamagePerSec : ActionNode, IDamageOrHealSourceNode
{
	private DamageType _damageType; // 0x10
	private String _damageKey; // 0x18
	private String _baseDamageKey; // 0x20
	private String _durationToIncreaseKey; // 0x28
	private Boolean _ignoreForSp; // 0x30
	private SourceAttackType _attackType; // 0x34
	private Boolean _isEnvDamage; // 0x38
	private Boolean _isRatioToMaxHp; // 0x39
	private Boolean _isIncreasingToCap; // 0x3a
	private Boolean _skipModifierEvent; // 0x3b
	private ElementType _elementDamageType; // 0x3c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4973c VA: 0x759456173c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f497a4 VA: 0x75945617a4
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4980c VA: 0x759456180c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f49d50 VA: 0x7594561d50
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f49dc8 VA: 0x7594561dc8
	public Void .ctor() { }
}
```