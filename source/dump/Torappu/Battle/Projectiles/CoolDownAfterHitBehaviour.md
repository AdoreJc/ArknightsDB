# CoolDownAfterHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `FP _coolDown`

- `String _coolDownEffect`

- `String _hitEffectOnProjectilePos`

- `String _coolDownReadyEffectOnProjectilePos`

- `Boolean _ignoreCamouflage`

- `Boolean _exceptTraceTarget`

- `Boolean _allowEmptyMainEffect`

- `TargetValidator _targetValidator`

- `Boolean _setAsHitEffectParent`

- `Boolean _setBodyTransformAsCoolDownEffectParent`

- `ParticleEffect m_mainEffect`

- `FP m_coolDown`

- `Boolean m_canHit`

- `Int32 m_layerMask`

- `String m_projectileAudio`


## Properties

- `Boolean canHit`


## Methods

- `Boolean get_canHit()`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void OnTriggerStay2D(Collider2D)`

- `Void OnTriggerExit2D(Collider2D)`

- `Void _DoTargetStay(IPtrObject)`

- `Void _DoTargetEnter(IPtrObject)`

- `Boolean _VerifyTarget(Entity)`

- `Void _DoTargetExit(IPtrObject)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class CoolDownAfterHitBehaviour : Behaviour
{
	private const String PROJECTILE_CAN_HIT_AUDIO; // 0x0
	protected TargetOptions _targetOptions; // 0x28
	private FP _coolDown; // 0x88
	private String _coolDownEffect; // 0x90
	private String _hitEffectOnProjectilePos; // 0x98
	private String _coolDownReadyEffectOnProjectilePos; // 0xa0
	private Boolean _ignoreCamouflage; // 0xa8
	private Boolean _exceptTraceTarget; // 0xa9
	private Boolean _allowEmptyMainEffect; // 0xaa
	private TargetValidator _targetValidator; // 0xb0
	private Boolean _setAsHitEffectParent; // 0xb8
	private Boolean _setBodyTransformAsCoolDownEffectParent; // 0xb9
	private ObjectPtr`1 m_coolDownEffect; // 0xc0
	private ObjectPtr`1 m_coolDownReadyEffect; // 0xd0
	private ParticleEffect m_mainEffect; // 0xe0
	private FP m_coolDown; // 0xe8
	private Boolean m_canHit; // 0xf0
	protected Int32 m_layerMask; // 0xf4
	private String m_projectileAudio; // 0xf8
	private static DelegateBridge __Hotfix0_get_canHit; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0x18
	private static DelegateBridge __Hotfix0_OnTriggerStay2D; // 0x20
	private static DelegateBridge __Hotfix0_OnTriggerExit2D; // 0x28
	private static DelegateBridge __Hotfix0__DoTargetStay; // 0x30
	private static DelegateBridge __Hotfix0__DoTargetEnter; // 0x38
	private static DelegateBridge __Hotfix0__VerifyTarget; // 0x40
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x48
	private static DelegateBridge __Hotfix0__DoTargetExit; // 0x50
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x58
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean canHit { get; }

	// RVA: 0x1d60570 VA: 0x7594378570
	public Boolean get_canHit() { }
	// RVA: 0x1d605d8 VA: 0x75943785d8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d6090c VA: 0x759437890c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d60bb8 VA: 0x7594378bb8
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1d60e10 VA: 0x7594378e10
	private Void OnTriggerStay2D(Collider2D collision) { }
	// RVA: 0x1d61010 VA: 0x7594379010
	private Void OnTriggerExit2D(Collider2D collision) { }
	// RVA: 0x1d61208 VA: 0x7594379208
	private Void _DoTargetStay(IPtrObject obj) { }
	// RVA: 0x1d614c4 VA: 0x75943794c4
	private Void _DoTargetEnter(IPtrObject obj) { }
	// RVA: 0x1d613e4 VA: 0x75943793e4
	private Boolean _VerifyTarget(Entity target) { }
	// RVA: 0x1d616a0 VA: 0x75943796a0
	protected virtual Void DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d61944 VA: 0x7594379944
	private Void _DoTargetExit(IPtrObject obj) { }
	// RVA: 0x1d61aac VA: 0x7594379aac
	public override Void OnProjectileStop() { }
	// RVA: 0x1d61bb0 VA: 0x7594379bb0
	public override Void OnProjectileBorn() { }
	// RVA: 0x1d61e88 VA: 0x7594379e88
	public Void .ctor() { }
	// RVA: 0x1d61f4c VA: 0x7594379f4c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d61f54 VA: 0x7594379f54
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d61f5c VA: 0x7594379f5c
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d61f64 VA: 0x7594379f64
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
}
```