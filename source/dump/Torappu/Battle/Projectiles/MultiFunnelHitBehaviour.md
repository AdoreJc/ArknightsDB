# MultiFunnelHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `Boolean _waitFirstPeriod`

- `MultiFunnelTrait m_trait`

- `FP m_remainingTime`


## Properties

- `MultiFunnelTrait trait`


## Methods

- `MultiFunnelTrait get_trait()`

- `Void StopProjectile()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class MultiFunnelHitBehaviour : Behaviour
{
	private TargetOptions _targetOptions; // 0x28
	private Boolean _waitFirstPeriod; // 0x88
	protected readonly PeriodicTimer m_periodTimer; // 0x90
	private MultiFunnelTrait m_trait; // 0x98
	private FP m_remainingTime; // 0xa0
	private static DelegateBridge __Hotfix0_get_trait; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_StopProjectile; // 0x18
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x20
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x28
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0x30
	private static DelegateBridge __Hotfix0__CheckProjectileInValid; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected MultiFunnelTrait trait { get; }

	// RVA: 0x1d65a28 VA: 0x759437da28
	protected MultiFunnelTrait get_trait() { }
	// RVA: 0x1d64ff4 VA: 0x759437cff4
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6957c VA: 0x759438157c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d65920 VA: 0x759437d920
	protected Void StopProjectile() { }
	// RVA: 0x1d65d58 VA: 0x759437dd58
	protected virtual Boolean DealHitTarget() { }
	// RVA: 0x1d69698 VA: 0x7594381698
	public override Void OnProjectileStop() { }
	// RVA: 0x1d69850 VA: 0x7594381850
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1d69958 VA: 0x7594381958
	protected virtual Boolean _CheckProjectileInValid() { }
	// RVA: 0x1d65ca0 VA: 0x759437dca0
	public Void .ctor() { }
	// RVA: 0x1d69b54 VA: 0x7594381b54
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d69b5c VA: 0x7594381b5c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d69b64 VA: 0x7594381b64
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d69b6c VA: 0x7594381b6c
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
}
```