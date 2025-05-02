# HealCurrentGiantBossViaMaxHpRatio

**Namespace:** ` `


## Fields

- `Boolean _canGeneralShield`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`

- `Enemy _GetCurrentGiantBoss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HealCurrentGiantBossViaMaxHpRatio : ActionNode, IDamageOrHealSourceNode
{
	private Boolean _canGeneralShield; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge __Hotfix0__GetCurrentGiantBoss; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5dbb8 VA: 0x7594575bb8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5dc20 VA: 0x7594575c20
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5dc88 VA: 0x7594575c88
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5e090 VA: 0x7594576090
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f5dea0 VA: 0x7594575ea0
	private Enemy _GetCurrentGiantBoss() { }
	// RVA: 0x1f5e108 VA: 0x7594576108
	public Void .ctor() { }
}
```