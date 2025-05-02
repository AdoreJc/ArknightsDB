# ApplyFixedElementDamage

**Namespace:** ` `


## Fields

- `ElementType _elementType`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _damageValueKey`

- `String _damageScaleKey`

- `Boolean _allowNoSourceDamage`

- `Boolean _isEnvDamage`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyFixedElementDamage : ActionNode, IDamageOrHealSourceNode
{
	private ElementType _elementType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private ActionTargetType _targetType; // 0x18
	private String _damageValueKey; // 0x20
	private String _damageScaleKey; // 0x28
	private Boolean _allowNoSourceDamage; // 0x30
	private Boolean _isEnvDamage; // 0x31
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4c70c VA: 0x759456470c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4c774 VA: 0x7594564774
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4c7dc VA: 0x75945647dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4cab4 VA: 0x7594564ab4
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4cb2c VA: 0x7594564b2c
	public Void .ctor() { }
}
```