# SplashDamage

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _excludeTargetType`

- `DamageType _damageType`

- `SourceApplyWay _sourceApplyWay`

- `Boolean _excludeTarget`

- `String _damageScale`

- `Boolean _createEffect`

- `SourceAttackType _attackType`


## Methods

- `Void _DealDamage(Entity, Entity, FP, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SplashDamage : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _excludeTargetType; // 0x14
	private DamageType _damageType; // 0x18
	private SourceApplyWay _sourceApplyWay; // 0x1c
	private Boolean _excludeTarget; // 0x20
	private String _damageScale; // 0x28
	private Boolean _createEffect; // 0x30
	private SourceAttackType _attackType; // 0x34
	private static readonly FP LOCK; // 0x0
	private static readonly FP UNLOCK; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0__DealDamage; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }

	// RVA: 0x1f48a08 VA: 0x7594560a08
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f48a80 VA: 0x7594560a80
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f49330 VA: 0x7594561330
	private Void _DealDamage(Entity source, Entity target, FP damageScale, String effectKey) { }
	// RVA: 0x1f49480 VA: 0x7594561480
	public Void .ctor() { }
	// RVA: 0x1f4950c VA: 0x759456150c
	private static Void .cctor() { }
}
```