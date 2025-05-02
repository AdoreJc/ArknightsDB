# HealViaMaxHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _healTarget`

- `Boolean _getMaxHpFromTarget`

- `Boolean _ignoreHealFree`

- `Boolean _skipModifierEvent`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HealViaMaxHpRatio : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _healTarget; // 0x10
	private Boolean _getMaxHpFromTarget; // 0x14
	private Boolean _ignoreHealFree; // 0x15
	private Boolean _skipModifierEvent; // 0x16
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5d778 VA: 0x7594575778
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5d7e0 VA: 0x75945757e0
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5d848 VA: 0x7594575848
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5dad0 VA: 0x7594575ad0
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5db48 VA: 0x7594575b48
	public Void .ctor() { }
}
```