# PullHitTargetBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _pullSourceOffset`

- `Single _pullDuration`

- `Int32 m_pullForceLevel`

- `FP m_pullRemainingTime`


## Methods

- `IEnumerator _DoLink(Enemy)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class PullHitTargetBehaviour : Behaviour
{
	private Single _pullSourceOffset; // 0x24
	private Single _pullDuration; // 0x28
	private Int32 m_pullForceLevel; // 0x2c
	private FP m_pullRemainingTime; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0__DoLink; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1d6db08 VA: 0x7594385b08
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6dc08 VA: 0x7594385c08
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d6dd10 VA: 0x7594385d10
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d6df88 VA: 0x7594385f88
	public override Void OnProjectileStop() { }
	// RVA: 0x1d6deb8 VA: 0x7594385eb8
	private IEnumerator _DoLink(Enemy target) { }
	// RVA: 0x1d6e294 VA: 0x7594386294
	public Void .ctor() { }
	// RVA: 0x1d6e340 VA: 0x7594386340
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6e348 VA: 0x7594386348
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d6e350 VA: 0x7594386350
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1d6e358 VA: 0x7594386358
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```