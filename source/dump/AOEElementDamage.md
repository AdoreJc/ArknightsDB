# AOEElementDamage

**Namespace:** ` `


## Fields

- `ElementType _elementDamageType`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _isFixedEpDamage`

- `String _fixedEpDamageKey`

- `Single _fixedEpDamage`

- `Boolean _useRadius`

- `String _rangeId`

- `Boolean _excludeTarget`

- `TargetOptions _targetOptions`

- `TargetOptions m_targetOptions`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void _DealEpDamage(Entity, Entity, FP, FP, Entity)`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AOEElementDamage : ActionNode, IDamageOrHealSourceNode
{
	private ElementType _elementDamageType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private ActionTargetType _targetType; // 0x18
	private Boolean _isFixedEpDamage; // 0x1c
	private String _fixedEpDamageKey; // 0x20
	private Single _fixedEpDamage; // 0x28
	private Boolean _useRadius; // 0x2c
	private String _rangeId; // 0x30
	private Boolean _excludeTarget; // 0x38
	private TargetOptions _targetOptions; // 0x40
	private TargetOptions m_targetOptions; // 0xa0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__DealEpDamage; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4b3a4 VA: 0x75945633a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4b40c VA: 0x759456340c
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4b474 VA: 0x7594563474
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4bd4c VA: 0x7594563d4c
	private Void _DealEpDamage(Entity source, Entity target, FP epDamageRatio, FP fixedEpDamage, Entity mainTarget) { }
	// RVA: 0x1f4bf18 VA: 0x7594563f18
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4bf90 VA: 0x7594563f90
	public Void .ctor() { }
}
```