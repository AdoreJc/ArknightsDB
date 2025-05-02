# HealViaDamage

**Namespace:** ` `


## Fields

- `Boolean _filterModifierCancelled`

- `HealType _healType`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HealViaDamage : ActionNode, IDamageOrHealSourceNode
{
	private Boolean _filterModifierCancelled; // 0x10
	private HealType _healType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5cd48 VA: 0x7594574d48
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5cdb0 VA: 0x7594574db0
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5ce18 VA: 0x7594574e18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5d178 VA: 0x7594575178
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5d1f0 VA: 0x75945751f0
	public Void .ctor() { }
}
```