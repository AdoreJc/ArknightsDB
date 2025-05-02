# AroundTargetRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _projectileCnt`

- `Single _projectileAroundRadius`

- `Boolean _clearProjectilesWhenDetached`

- `Boolean _createNewProjectileWhenCastOnTarget`

- `Int32 m_projectileCnt`

- `Single m_projectileAroundRadius`

- `String m_nextProjectileKey`

- `FP m_changeAtkScale`

- `Boolean m_keepLastPos`


## Methods

- `Void _ModifyAtkScaleWhenCreateProjectile()`

- `Projectile _CreateAroundProjectile(ILocatable, out, Int32)`

- `Void _CalculateProjectilesStartPos(Vector3)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_Reset()`

- `String <>xLuaBaseProxy_GetProjectileKey()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AroundTargetRangedAttack : RangedAttack
{
	private const String NEXT_PROJECTILE_KEY; // 0x0
	private Int32 _projectileCnt; // 0x25c
	private Single _projectileAroundRadius; // 0x260
	private Boolean _clearProjectilesWhenDetached; // 0x264
	private Boolean _createNewProjectileWhenCastOnTarget; // 0x265
	private List`1 m_projectileStartPos; // 0x268
	private Int32 m_projectileCnt; // 0x270
	private Single m_projectileAroundRadius; // 0x274
	private List`1 m_projectilesKeepPosList; // 0x278
	private String m_nextProjectileKey; // 0x280
	private FP m_changeAtkScale; // 0x288
	private Boolean m_keepLastPos; // 0x290
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0__ModifyAtkScaleWhenCreateProjectile; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x18
	private static DelegateBridge __Hotfix0_OnDetached; // 0x20
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0x38
	private static DelegateBridge __Hotfix0__CreateAroundProjectile; // 0x40
	private static DelegateBridge __Hotfix0__CalculateProjectilesStartPos; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1e074b8 VA: 0x759441f4b8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e075d4 VA: 0x759441f5d4
	private Void _ModifyAtkScaleWhenCreateProjectile() { }
	// RVA: 0x1e076c4 VA: 0x759441f6c4
	protected override Void OnCastStart() { }
	// RVA: 0x1e078ec VA: 0x759441f8ec
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0826c VA: 0x759442026c
	protected override Void OnDetached() { }
	// RVA: 0x1e08300 VA: 0x7594420300
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e08498 VA: 0x7594420498
	protected override Void Reset() { }
	// RVA: 0x1e08584 VA: 0x7594420584
	protected override String GetProjectileKey() { }
	// RVA: 0x1e0813c VA: 0x759442013c
	private Projectile _CreateAroundProjectile(ILocatable target, out Projectile fakeProjectile, Int32 projectileIndex) { }
	// RVA: 0x1e07d50 VA: 0x759441fd50
	private Void _CalculateProjectilesStartPos(Vector3 target) { }
	// RVA: 0x1e08610 VA: 0x7594420610
	public Void .ctor() { }
	// RVA: 0x1e08734 VA: 0x7594420734
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e08758 VA: 0x7594420758
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e08760 VA: 0x7594420760
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e08768 VA: 0x7594420768
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e08770 VA: 0x7594420770
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e08778 VA: 0x7594420778
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e08780 VA: 0x7594420780
	private String <>xLuaBaseProxy_GetProjectileKey() { }
}
```