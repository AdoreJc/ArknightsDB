# FunnelHitbehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `Boolean _waitFirstPeriod`

- `PeriodicTimer m_periodTimer`

- `CammouTrait m_trait`


## Methods

- `Void _DealHitTarget()`

- `Boolean _CheckProjectileInValid()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class FunnelHitbehaviour : Behaviour
{
	private TargetOptions _targetOptions; // 0x28
	private Boolean _waitFirstPeriod; // 0x88
	private PeriodicTimer m_periodTimer; // 0x90
	private CammouTrait m_trait; // 0x98
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__DealHitTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0x20
	private static DelegateBridge __Hotfix0__CheckProjectileInValid; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1d6424c VA: 0x759437c24c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d64594 VA: 0x759437c594
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d64898 VA: 0x759437c898
	private Void _DealHitTarget() { }
	// RVA: 0x1d64a70 VA: 0x759437ca70
	public override Void OnProjectileStop() { }
	// RVA: 0x1d64b78 VA: 0x759437cb78
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1d6469c VA: 0x759437c69c
	private Boolean _CheckProjectileInValid() { }
	// RVA: 0x1d64c14 VA: 0x759437cc14
	public Void .ctor() { }
	// RVA: 0x1d64cc4 VA: 0x759437ccc4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d64ccc VA: 0x759437cccc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d64cd4 VA: 0x759437ccd4
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d64cdc VA: 0x759437ccdc
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
}
```