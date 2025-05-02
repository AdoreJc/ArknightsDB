# ElementHealViaMaxHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _healTarget`

- `ActionTargetType _maxHpSource`

- `Boolean _ignoreHealFree`

- `Boolean _skipModifierEvent`

- `Boolean _isIntervalHeal`

- `Boolean _isContinousHeal`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ElementHealViaMaxHpRatio : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _healTarget; // 0x10
	private ActionTargetType _maxHpSource; // 0x14
	private Boolean _ignoreHealFree; // 0x18
	private Boolean _skipModifierEvent; // 0x19
	private Boolean _isIntervalHeal; // 0x1a
	private Boolean _isContinousHeal; // 0x1b
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5f03c VA: 0x759457703c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5f0a4 VA: 0x75945770a4
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5f10c VA: 0x759457710c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5f418 VA: 0x7594577418
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5f490 VA: 0x7594577490
	public Void .ctor() { }
}
```