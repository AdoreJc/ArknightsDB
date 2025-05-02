# DamageSplit

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `SourceAttackType _attackType`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageSplit : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private SourceAttackType _attackType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f44dec VA: 0x759455cdec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f44e54 VA: 0x759455ce54
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f44ebc VA: 0x759455cebc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f451b0 VA: 0x759455d1b0
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f45228 VA: 0x759455d228
	public Void .ctor() { }
}
```