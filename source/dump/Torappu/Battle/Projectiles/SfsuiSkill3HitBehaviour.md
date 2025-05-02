# SfsuiSkill3HitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean m_isReached`


## Methods

- `Void _EmitProjectileToRightmostTile()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SfsuiSkill3HitBehaviour : Behaviour
{
	private List`1 _emitProjectiles; // 0x28
	private List`1 m_subProjectiles; // 0x30
	private Boolean m_isReached; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x10
	private static DelegateBridge __Hotfix0__EmitProjectileToRightmostTile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d7469c VA: 0x759438c69c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d74798 VA: 0x759438c798
	public override Void OnProjectileReached() { }
	// RVA: 0x1d74b40 VA: 0x759438cb40
	public override Void OnProjectileStop() { }
	// RVA: 0x1d74820 VA: 0x759438c820
	private Void _EmitProjectileToRightmostTile() { }
	// RVA: 0x1d74d18 VA: 0x759438cd18
	public Void .ctor() { }
	// RVA: 0x1d74e2c VA: 0x759438ce2c
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d74e34 VA: 0x759438ce34
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d74e3c VA: 0x759438ce3c
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```