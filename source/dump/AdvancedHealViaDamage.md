# AdvancedHealViaDamage

**Namespace:** ` `


## Fields

- `ActionTargetType _owner`

- `String _healAbilityName`

- `String _scaleKey`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AdvancedHealViaDamage : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _owner; // 0x10
	private String _healAbilityName; // 0x18
	private String _scaleKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5d260 VA: 0x7594575260
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5d2c8 VA: 0x75945752c8
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5d330 VA: 0x7594575330
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5d690 VA: 0x7594575690
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5d708 VA: 0x7594575708
	public Void .ctor() { }
}
```