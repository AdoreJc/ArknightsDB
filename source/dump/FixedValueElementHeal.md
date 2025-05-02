# FixedValueElementHeal

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `Boolean _ignoreHealFree`

- `String _valueKey`

- `Boolean _isCont`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FixedValueElementHeal : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private Boolean _ignoreHealFree; // 0x18
	private String _valueKey; // 0x20
	private String[] _scaleUpKeys; // 0x28
	private Boolean _isCont; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5f500 VA: 0x7594577500
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5f568 VA: 0x7594577568
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5f5d0 VA: 0x75945775d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5f920 VA: 0x7594577920
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5f998 VA: 0x7594577998
	public Void .ctor() { }
}
```