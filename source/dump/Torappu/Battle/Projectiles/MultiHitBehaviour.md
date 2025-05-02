# MultiHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _hitAfterReached`

- `PeriodicTicker m_triggerTicker`


## Methods

- `Void _DoTargetStay(IPtrObject)`

- `Void OnTriggerStay2D(Collider2D)`

- `Void _UpdateRigidBody()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DealHitTarget(Entity, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class MultiHitBehaviour : HitBehaviour
{
	private const Int32 RIGIDBODY_TICK_INTERVAL; // 0x0
	private Boolean _hitAfterReached; // 0xa8
	private Collider2D[] m_colliders; // 0xb0
	private PeriodicTicker m_triggerTicker; // 0xb8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__DoTargetStay; // 0x10
	private static DelegateBridge __Hotfix0_OnTriggerStay2D; // 0x18
	private static DelegateBridge __Hotfix0__UpdateRigidBody; // 0x20
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1d69b74 VA: 0x7594381b74
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d69c60 VA: 0x7594381c60
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d69de0 VA: 0x7594381de0
	private Void _DoTargetStay(IPtrObject obj) { }
	// RVA: 0x1d69f94 VA: 0x7594381f94
	private Void OnTriggerStay2D(Collider2D collision) { }
	// RVA: 0x1d69d14 VA: 0x7594381d14
	private Void _UpdateRigidBody() { }
	// RVA: 0x1d6a1a4 VA: 0x75943821a4
	protected override Void DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d6a258 VA: 0x7594382258
	public Void .ctor() { }
	// RVA: 0x1d6a33c VA: 0x759438233c
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6a340 VA: 0x7594382340
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d6a348 VA: 0x7594382348
	private Void <>xLuaBaseProxy_DealHitTarget(Entity P0, Boolean P1) { }
}
```