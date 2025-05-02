# FetchEnemyHpToHost

**Namespace:** ` `


## Fields

- `DamageType _damageType`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FetchEnemyHpToHost : ActionNode, IDamageOrHealSourceNode
{
	private DamageType _damageType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4d034 VA: 0x7594565034
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4d09c VA: 0x759456509c
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4d104 VA: 0x7594565104
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4d17c VA: 0x759456517c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4d614 VA: 0x7594565614
	public Void .ctor() { }
}
```