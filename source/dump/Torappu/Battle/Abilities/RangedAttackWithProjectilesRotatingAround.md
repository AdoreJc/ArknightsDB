# RangedAttackWithProjectilesRotatingAround

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _radius`

- `String _radiusKey`

- `Int32 _initCount`

- `String _initCountKey`

- `ProjectileType _projectileType`

- `Single m_radius`

- `Single m_speed`

- `Int32 m_maxprojectileNum`

- `Int32 m_initCount`

- `Single m_projectileRadius`


## Properties

- `Int32 managedProjectileCount`


## Methods

- `Int32 get_managedProjectileCount()`

- `ProjectileWrapper GetProjectileWrapper(Int32)`

- `Void _CreateProjectile(ILocatable)`

- `Void _CreateProjectileEnemyMain14(ILocatable)`

- `Void _CreateProjectileLrtsia(ILocatable)`

- `Projectile _GenerateProjectile(ILocatable, ILocatable, out)`

- `Void _CalculateProjectileGeneratePos(ILocatable)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangedAttackWithProjectilesRotatingAround : RangedAttack
{
	private Single _radius; // 0x25c
	private String _radiusKey; // 0x260
	private Int32 _initCount; // 0x268
	private String _initCountKey; // 0x270
	protected ProjectileType _projectileType; // 0x278
	protected Single m_radius; // 0x27c
	protected Single m_speed; // 0x280
	protected Int32 m_maxprojectileNum; // 0x284
	protected Int32 m_initCount; // 0x288
	protected Single m_projectileRadius; // 0x28c
	protected List`1 m_ProjectileWrapperList; // 0x290
	protected List`1 m_projectileStartPos; // 0x298
	private static DelegateBridge __Hotfix0_get_managedProjectileCount; // 0x0
	private static DelegateBridge __Hotfix0_GetProjectileWrapper; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x18
	private static DelegateBridge __Hotfix0__CreateProjectile; // 0x20
	private static DelegateBridge __Hotfix0__CreateProjectileEnemyMain14; // 0x28
	private static DelegateBridge __Hotfix0__CreateProjectileLrtsia; // 0x30
	private static DelegateBridge __Hotfix0__GenerateProjectile; // 0x38
	private static DelegateBridge __Hotfix0__CalculateProjectileGeneratePos; // 0x40
	private static DelegateBridge __Hotfix0_OnDetached; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 managedProjectileCount { get; }

	// RVA: 0x1e18b10 VA: 0x7594430b10
	public Int32 get_managedProjectileCount() { }
	// RVA: 0x1e18b94 VA: 0x7594430b94
	public ProjectileWrapper GetProjectileWrapper(Int32 index) { }
	// RVA: 0x1e18c68 VA: 0x7594430c68
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e18f78 VA: 0x7594430f78
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e193b4 VA: 0x75944313b4
	private Void _CreateProjectile(ILocatable target) { }
	// RVA: 0x1e1946c VA: 0x759443146c
	private Void _CreateProjectileEnemyMain14(ILocatable target) { }
	// RVA: 0x1e19620 VA: 0x7594431620
	private Void _CreateProjectileLrtsia(ILocatable target) { }
	// RVA: 0x1e197ec VA: 0x75944317ec
	private Projectile _GenerateProjectile(ILocatable target, ILocatable startPoint, out Projectile fakeProjectile) { }
	// RVA: 0x1e19028 VA: 0x7594431028
	private Void _CalculateProjectileGeneratePos(ILocatable target) { }
	// RVA: 0x1e198fc VA: 0x75944318fc
	protected override Void OnDetached() { }
	// RVA: 0x1e19b44 VA: 0x7594431b44
	public Void .ctor() { }
	// RVA: 0x1e19c68 VA: 0x7594431c68
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e19c90 VA: 0x7594431c90
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e19c94 VA: 0x7594431c94
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```