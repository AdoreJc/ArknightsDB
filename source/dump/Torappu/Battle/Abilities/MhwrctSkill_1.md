# MhwrctSkill_1

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`


## Methods

- `Void _CreateProjectile(Entity)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_ClearProjectile()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MhwrctSkill_1 : AbstractAnimatedAbility
{
	private String _projectileKey; // 0x1c0
	private ObjectPtr`1 m_projectile; // 0x1c8
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x0
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x8
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x10
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x18
	private static DelegateBridge __Hotfix0_ClearProjectile; // 0x20
	private static DelegateBridge __Hotfix0__CreateProjectile; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e7b674 VA: 0x7594493674
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e7b6ec VA: 0x75944936ec
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e7b76c VA: 0x759449376c
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e7b890 VA: 0x7594493890
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e7bf7c VA: 0x7594493f7c
	public override Void ClearProjectile() { }
	// RVA: 0x1e7be44 VA: 0x7594493e44
	private Void _CreateProjectile(Entity from) { }
	// RVA: 0x1e7c070 VA: 0x7594494070
	public Void .ctor() { }
	// RVA: 0x1e7c0e0 VA: 0x75944940e0
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e7c0e8 VA: 0x75944940e8
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e7c0f0 VA: 0x75944940f0
	private Void <>xLuaBaseProxy_ClearProjectile() { }
}
```