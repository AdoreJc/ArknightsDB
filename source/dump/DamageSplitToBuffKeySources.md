# DamageSplitToBuffKeySources

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `SourceAttackType _attackType`

- `String _buffKey`

- `String _hitEffectKey`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Modifier _CreateSplitModifier(FP, Entity)`

- `Boolean _TargetValid(Entity)`

- `Void PreprocessForProjectile(Entity)`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageSplitToBuffKeySources : ActionNode, IDamageOrHealSourceNode, IEffectSource
{
	private ActionTargetType _targetType; // 0x10
	private SourceAttackType _attackType; // 0x14
	private String _buffKey; // 0x18
	private String _hitEffectKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__CreateSplitModifier; // 0x18
	private static DelegateBridge __Hotfix0__TargetValid; // 0x20
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f455e4 VA: 0x759455d5e4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4564c VA: 0x759455d64c
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f456b4 VA: 0x759455d6b4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f45f34 VA: 0x759455df34
	private Modifier _CreateSplitModifier(FP damage, Entity target) { }
	// RVA: 0x1f45e48 VA: 0x759455de48
	private Boolean _TargetValid(Entity entity) { }
	// RVA: 0x1f4608c VA: 0x759455e08c
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f46104 VA: 0x759455e104
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f46218 VA: 0x759455e218
	public Void .ctor() { }
}
```