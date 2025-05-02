# AnimatedActionToTargetAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ActionArray _actions`

- `SourceAttackType _attackType`

- `Boolean _useDynamicAttackType`


## Methods

- `SourceAttackType <>xLuaBaseProxy_get_attackType()`

- `Boolean <>xLuaBaseProxy_get_useDynamicAttackType()`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AnimatedActionToTargetAbility : AbstractAnimatedAbility
{
	private ActionArray _actions; // 0x1c0
	private SourceAttackType _attackType; // 0x1c8
	private Boolean _useDynamicAttackType; // 0x1cc
	private static DelegateBridge __Hotfix0_get_attackType; // 0x0
	private static DelegateBridge __Hotfix0_get_useDynamicAttackType; // 0x8
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x10
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x18
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override SourceAttackType attackType { get; }
	protected override Boolean useDynamicAttackType { get; }

	// RVA: 0x1e02340 VA: 0x759441a340
	protected override SourceAttackType get_attackType() { }
	// RVA: 0x1e023a8 VA: 0x759441a3a8
	protected override Boolean get_useDynamicAttackType() { }
	// RVA: 0x1e02410 VA: 0x759441a410
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e02490 VA: 0x759441a490
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e02528 VA: 0x759441a528
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e025cc VA: 0x759441a5cc
	public Void .ctor() { }
	// RVA: 0x1e02684 VA: 0x759441a684
	private SourceAttackType <>xLuaBaseProxy_get_attackType() { }
	// RVA: 0x1e0268c VA: 0x759441a68c
	private Boolean <>xLuaBaseProxy_get_useDynamicAttackType() { }
	// RVA: 0x1e02694 VA: 0x759441a694
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```