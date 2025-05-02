# AuraHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `Range _rangeToLoad`

- `TargetValidator _targetValidator`

- `Boolean _onlyCheckHitWhenReachTarget`

- `Boolean _hitTargetNoDamage`

- `Int32 m_layerMask`

- `Boolean m_collisionHandlerInited`

- `TargetEnterExitHandler m_eeHandler`


## Properties

- `Range rangeToLoad`

- `Boolean onlyCheckHitWhenReachTarget`

- `TargetEnterExitHandler eeHandler`


## Methods

- `Range get_rangeToLoad()`

- `Boolean get_onlyCheckHitWhenReachTarget()`

- `TargetEnterExitHandler get_eeHandler()`

- `Boolean _DoTargetEnter(Entity)`

- `Void _DoTargetExit(Entity)`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void OnTriggerExit2D(Collider2D)`

- `Void _InitCollisionHandler()`

- `Void _EnableColliders(Boolean)`

- `Void _RefreshColliders()`

- `Boolean _VerifyTarget(Entity)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class AuraHitBehaviour : Behaviour
{
	private const Int32 TRIGGER_TICK; // 0x0
	protected TargetOptions _targetOptions; // 0x28
	private Range _rangeToLoad; // 0x88
	private TargetValidator _targetValidator; // 0x90
	private Boolean _onlyCheckHitWhenReachTarget; // 0x98
	private Boolean _hitTargetNoDamage; // 0x99
	private Int32 m_layerMask; // 0x9c
	private Boolean m_collisionHandlerInited; // 0xa0
	private Collider2D[] m_colliders; // 0xa8
	private TargetEnterExitHandler m_eeHandler; // 0xb0
	private static DelegateBridge __Hotfix0_get_rangeToLoad; // 0x0
	private static DelegateBridge __Hotfix0_get_onlyCheckHitWhenReachTarget; // 0x8
	private static DelegateBridge __Hotfix0_get_eeHandler; // 0x10
	private static DelegateBridge __Hotfix0__DoTargetEnter; // 0x18
	private static DelegateBridge __Hotfix0__DoTargetExit; // 0x20
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0x28
	private static DelegateBridge __Hotfix0_OnTriggerExit2D; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0__InitCollisionHandler; // 0x48
	private static DelegateBridge __Hotfix0__EnableColliders; // 0x50
	private static DelegateBridge __Hotfix0__RefreshColliders; // 0x58
	private static DelegateBridge __Hotfix0__VerifyTarget; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	protected Range rangeToLoad { get; }
	protected Boolean onlyCheckHitWhenReachTarget { get; }
	private TargetEnterExitHandler eeHandler { get; }

	// RVA: 0x1d5b8b0 VA: 0x75943738b0
	protected Range get_rangeToLoad() { }
	// RVA: 0x1d5b918 VA: 0x7594373918
	protected Boolean get_onlyCheckHitWhenReachTarget() { }
	// RVA: 0x1d5b980 VA: 0x7594373980
	private TargetEnterExitHandler get_eeHandler() { }
	// RVA: 0x1d5bb2c VA: 0x7594373b2c
	private Boolean _DoTargetEnter(Entity target) { }
	// RVA: 0x1d5bddc VA: 0x7594373ddc
	private Void _DoTargetExit(Entity target) { }
	// RVA: 0x1d5bef8 VA: 0x7594373ef8
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1d5c114 VA: 0x7594374114
	private Void OnTriggerExit2D(Collider2D collision) { }
	// RVA: 0x1d5c2a0 VA: 0x75943742a0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d5c528 VA: 0x7594374528
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d5c3dc VA: 0x75943743dc
	private Void _InitCollisionHandler() { }
	// RVA: 0x1d5c460 VA: 0x7594374460
	private Void _EnableColliders(Boolean enabled) { }
	// RVA: 0x1d5c964 VA: 0x7594374964
	private Void _RefreshColliders() { }
	// RVA: 0x1d5bcfc VA: 0x7594373cfc
	private Boolean _VerifyTarget(Entity target) { }
	// RVA: 0x1d5ca2c VA: 0x7594374a2c
	public Void .ctor() { }
	// RVA: 0x1d5ca9c VA: 0x7594374a9c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d5caa4 VA: 0x7594374aa4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
}
```