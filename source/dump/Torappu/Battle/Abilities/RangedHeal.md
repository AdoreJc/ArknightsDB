# RangedHeal

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`

- `Boolean _useCachedAtkOnly`

- `MountPointType _mountPointType`


## Methods

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `ApplyHeal <>xLuaBaseProxy_NewHealNode(FP)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangedHeal : Heal
{
	private String _projectileKey; // 0x1f0
	private Boolean _useCachedAtkOnly; // 0x1f8
	private MountPointType _mountPointType; // 0x1fc
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x8
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x10
	private static DelegateBridge __Hotfix0_NewHealNode; // 0x18
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x20
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x28
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e1fac0 VA: 0x7594437ac0
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e1fb28 VA: 0x7594437b28
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e1fc8c VA: 0x7594437c8c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e1fd04 VA: 0x7594437d04
	protected override ApplyHeal NewHealNode(FP healScale) { }
	// RVA: 0x1e1fe24 VA: 0x7594437e24
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e1eb54 VA: 0x7594436b54
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e1e9cc VA: 0x75944369cc
	protected virtual String GetProjectileKey() { }
	// RVA: 0x1e1eddc VA: 0x7594436ddc
	public Void .ctor() { }
	// RVA: 0x1e1fecc VA: 0x7594437ecc
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1e1fed4 VA: 0x7594437ed4
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e1fedc VA: 0x7594437edc
	private IList`1 <>xLuaBaseProxy_GetEventActions(Event P0) { }
	// RVA: 0x1e1fee0 VA: 0x7594437ee0
	private ApplyHeal <>xLuaBaseProxy_NewHealNode(FP P0) { }
	// RVA: 0x1e1fee4 VA: 0x7594437ee4
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e1fee8 VA: 0x7594437ee8
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
}
```