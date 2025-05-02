# AdvancedApplyHeal

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _useDynamicVar`

- `ActionTargetType _targetType`

- `Boolean _scaleUpIfUnderHpRatio`

- `String _scaleUpByBlackboardKey`

- `String _customModifierKey`

- `FP m_cachedAtk`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AdvancedApplyHeal : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _useDynamicVar; // 0x14
	private ActionTargetType _targetType; // 0x18
	private Boolean _scaleUpIfUnderHpRatio; // 0x1c
	private String _scaleUpByBlackboardKey; // 0x20
	private String _customModifierKey; // 0x28
	private FP m_cachedAtk; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5baec VA: 0x7594573aec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5bb54 VA: 0x7594573b54
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5bbbc VA: 0x7594573bbc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5c07c VA: 0x759457407c
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5c180 VA: 0x7594574180
	public Void .ctor() { }
}
```