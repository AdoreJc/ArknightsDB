# FuzeSkill2RangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _offset`

- `Single _beginOffset`

- `String _effectKey`

- `Int32 m_hitTime`

- `FixedPosition m_projectileStartPos`


## Methods

- `Void _CreateProjectiles(Int32)`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class FuzeSkill2RangedAttack : MultiRangedAttack
{
	private Single _offset; // 0x2c8
	private Single _beginOffset; // 0x2cc
	private String _effectKey; // 0x2d0
	private List`1 m_targetTiles; // 0x2d8
	private readonly GridPosition[,] TARGET_GRIDPOSITION_LIST; // 0x2e0
	private readonly Vector2[] PROJEJCTILE_OFFSET_DIRECTION; // 0x2e8
	private readonly Vector3[] BEGIN_OFFSET_POSITION; // 0x2f0
	private readonly Int32 MAX_TARGET_TILE_COUNT; // 0x2f8
	private Int32 m_hitTime; // 0x2fc
	private FixedPosition[] m_targetPositions; // 0x300
	private FixedPosition m_projectileStartPos; // 0x308
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x10
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x18
	private static DelegateBridge __Hotfix0__CreateProjectiles; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean allowNoTarget { get; }

	// RVA: 0x1e0f278 VA: 0x7594427278
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e0f2e0 VA: 0x75944272e0
	protected override Void OnCastStart() { }
	// RVA: 0x1e0f9c0 VA: 0x75944279c0
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0fbb4 VA: 0x7594427bb4
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e0fac4 VA: 0x7594427ac4
	private Void _CreateProjectiles(Int32 i) { }
	// RVA: 0x1e0fd68 VA: 0x7594427d68
	public Void .ctor() { }
	// RVA: 0x1e104b4 VA: 0x75944284b4
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e104bc VA: 0x75944284bc
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e104c0 VA: 0x75944284c0
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e107b8 VA: 0x75944287b8
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
}
```