# FixedValueHeal

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `Boolean _ignoreHealFree`

- `String _healValueKey`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FixedValueHeal : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private Boolean _ignoreHealFree; // 0x18
	private String _healValueKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5b690 VA: 0x7594573690
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5b6f8 VA: 0x75945736f8
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5b760 VA: 0x7594573760
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5b9cc VA: 0x75945739cc
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5ba44 VA: 0x7594573a44
	public Void .ctor() { }
}
```