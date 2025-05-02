# ChangeForceWhenHitTgtBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _radius`

- `Int32 _deltaForceLevel`

- `Single m_radius`

- `Int32 m_deltaForceLevel`


## Methods

- `Void _OnBeforeHitTarget(Entity)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ChangeForceWhenHitTgtBehaviour : Behaviour
{
	private Single _radius; // 0x24
	private Int32 _deltaForceLevel; // 0x28
	private Single m_radius; // 0x2c
	private Int32 m_deltaForceLevel; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x8
	private static DelegateBridge __Hotfix0__OnBeforeHitTarget; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d5fe5c VA: 0x7594377e5c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d5ffa0 VA: 0x7594377fa0
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d60030 VA: 0x7594378030
	private Void _OnBeforeHitTarget(Entity target) { }
	// RVA: 0x1d60378 VA: 0x7594378378
	public Void .ctor() { }
	// RVA: 0x1d603f4 VA: 0x75943783f4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d603fc VA: 0x75943783fc
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
}
```