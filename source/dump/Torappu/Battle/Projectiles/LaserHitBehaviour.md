# LaserHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _overridePurposeMaskWithTargetOptions`

- `TargetOptions _targetOptions`

- `Boolean _exceptTraceTarget`

- `Single _laserWidth`

- `Boolean _ignoreCamouflage`

- `Boolean _useStartMapPosAsSource`

- `Single _updateBoxColliderInterval`

- `Int32 m_layerMask`

- `BoxCollider2D m_collider`

- `PeriodicTimer m_updateBoxColliderTicker`


## Methods

- `Void _UpdateBoxCollider()`

- `Void _DoTargetEnter(IPtrObject)`

- `Void _DoTargetExit(IPtrObject)`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void OnTriggerExit2D(Collider2D)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class LaserHitBehaviour : Behaviour
{
	private Boolean _overridePurposeMaskWithTargetOptions; // 0x24
	protected TargetOptions _targetOptions; // 0x28
	private Boolean _exceptTraceTarget; // 0x88
	private Single _laserWidth; // 0x8c
	private Boolean _ignoreCamouflage; // 0x90
	private Boolean _useStartMapPosAsSource; // 0x91
	private Single _updateBoxColliderInterval; // 0x94
	protected Int32 m_layerMask; // 0x98
	private BoxCollider2D m_collider; // 0xa0
	private PeriodicTimer m_updateBoxColliderTicker; // 0xa8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__UpdateBoxCollider; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x18
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x20
	private static DelegateBridge __Hotfix0__DoTargetEnter; // 0x28
	private static DelegateBridge __Hotfix0__DoTargetExit; // 0x30
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0x38
	private static DelegateBridge __Hotfix0_OnTriggerExit2D; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x1d68590 VA: 0x7594380590
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6888c VA: 0x759438088c
	private Void _UpdateBoxCollider() { }
	// RVA: 0x1d68b20 VA: 0x7594380b20
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d68be0 VA: 0x7594380be0
	public override Void OnProjectileReached() { }
	// RVA: 0x1d68c54 VA: 0x7594380c54
	protected virtual Void DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d68d58 VA: 0x7594380d58
	private Void _DoTargetEnter(IPtrObject obj) { }
	// RVA: 0x1d68f28 VA: 0x7594380f28
	private Void _DoTargetExit(IPtrObject obj) { }
	// RVA: 0x1d69090 VA: 0x7594381090
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1d692e0 VA: 0x75943812e0
	private Void OnTriggerExit2D(Collider2D collision) { }
	// RVA: 0x1d694d8 VA: 0x75943814d8
	public Void .ctor() { }
	// RVA: 0x1d69564 VA: 0x7594381564
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6956c VA: 0x759438156c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d69574 VA: 0x7594381574
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
}
```