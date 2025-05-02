# DuoRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _duoProjectileKey`

- `MountPointType _duoMountPointType`

- `Boolean _lastTargetDuoAttack`

- `Int32 m_targetCount`


## Methods

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class DuoRangedAttack : RangedAttack
{
	private const Int32 DUO_ATTACK_SPLIT_FACTOR; // 0x0
	private String _duoProjectileKey; // 0x260
	private MountPointType _duoMountPointType; // 0x268
	private Boolean _lastTargetDuoAttack; // 0x26c
	private Int32 m_targetCount; // 0x270
	private ObjectPtr`1 m_cachedTarget; // 0x278
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x8
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x10
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e0c6f0 VA: 0x75944246f0
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0cc58 VA: 0x7594424c58
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0cd4c VA: 0x7594424d4c
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e0cfd8 VA: 0x7594424fd8
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e0d2ec VA: 0x75944252ec
	public Void .ctor() { }
	// RVA: 0x1e0d360 VA: 0x7594425360
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e0d364 VA: 0x7594425364
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e0d368 VA: 0x7594425368
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
	// RVA: 0x1e0d36c VA: 0x759442536c
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
}
```