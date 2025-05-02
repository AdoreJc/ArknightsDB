# GdglowHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Int32 _startIndex`

- `ActionArray _actions`

- `Single m_prob`

- `Int32 m_prdMaxMultiplier`

- `Boolean m_useHookProjectile`

- `Int32 m_projectileKeyIndex`


## Methods

- `Void EmitProjectile(Entity)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Boolean <>xLuaBaseProxy_DealHitTarget()`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class GdglowHitBehaviour : MultiFunnelHitBehaviour
{
	private Int32 _startIndex; // 0xa8
	private String[] _projectileKeys; // 0xb0
	private ActionArray _actions; // 0xb8
	private Single m_prob; // 0xc0
	private Int32 m_prdMaxMultiplier; // 0xc4
	private Boolean m_useHookProjectile; // 0xc8
	private Int32 m_projectileKeyIndex; // 0xcc
	private readonly List`1 m_logicProjectileKeys; // 0xd0
	private readonly List`1 m_graphicProjectileKeys; // 0xd8
	private readonly List`1 m_damageNodeReplacedActionNodes; // 0xe0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x10
	private static DelegateBridge __Hotfix0_EmitProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d64ce4 VA: 0x759437cce4
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d65394 VA: 0x759437d394
	protected override Boolean DealHitTarget() { }
	// RVA: 0x1d65a90 VA: 0x759437da90
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d65678 VA: 0x759437d678
	private Void EmitProjectile(Entity entity) { }
	// RVA: 0x1d65b5c VA: 0x759437db5c
	public Void .ctor() { }
	// RVA: 0x1d65d50 VA: 0x759437dd50
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d65d54 VA: 0x759437dd54
	private Boolean <>xLuaBaseProxy_DealHitTarget() { }
	// RVA: 0x1d65f04 VA: 0x759437df04
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
}
```