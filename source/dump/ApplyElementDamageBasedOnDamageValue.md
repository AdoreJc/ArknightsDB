# ApplyElementDamageBasedOnDamageValue

**Namespace:** ` `


## Fields

- `ElementType _elementType`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyElementDamageBasedOnDamageValue : ActionNode, IDamageOrHealSourceNode
{
	private ElementType _elementType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private ActionTargetType _targetType; // 0x18
	private Boolean _filterDamageType; // 0x1c
	private DamageTypeMask _damageMask; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4c160 VA: 0x7594564160
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4c1c8 VA: 0x75945641c8
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4c230 VA: 0x7594564230
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4c61c VA: 0x759456461c
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4c694 VA: 0x7594564694
	public Void .ctor() { }
}
```