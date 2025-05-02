# HitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `Boolean _goThroughWall`

- `Boolean _onlyCheckHitWhenReachTarget`

- `Boolean _onlyCheckHitWhenStop`

- `Boolean _canFlyThroughTheDeathArea`

- `Boolean _exceptTraceTarget`

- `Boolean _overridePurposeMaskWithTargetOptions`

- `Range _rangeToLoad`

- `Boolean _ignoreCamouflage`

- `Boolean _ignoreRangeScale`

- `Boolean _exceptSource`

- `Boolean _mergeTraceTargetMotion`

- `Boolean _markReachedOnlyWhenTargetEnter`

- `Boolean m_goThroughWall`

- `Int32 m_layerMask`

- `MotionMask m_originTargetMotion`


## Methods

- `Void _DoTargetEnter(IPtrObject)`

- `Void _DoTargetExit(IPtrObject)`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void OnTriggerExit2D(Collider2D)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class HitBehaviour : Behaviour
{
	private static List`1 s_sharedList; // 0x0
	protected TargetOptions _targetOptions; // 0x28
	private Boolean _goThroughWall; // 0x88
	protected Boolean _onlyCheckHitWhenReachTarget; // 0x89
	protected Boolean _onlyCheckHitWhenStop; // 0x8a
	protected Boolean _canFlyThroughTheDeathArea; // 0x8b
	private Boolean _exceptTraceTarget; // 0x8c
	private Boolean _overridePurposeMaskWithTargetOptions; // 0x8d
	protected Range _rangeToLoad; // 0x90
	private Boolean _ignoreCamouflage; // 0x98
	private Boolean _ignoreRangeScale; // 0x99
	private Boolean _exceptSource; // 0x9a
	private Boolean _mergeTraceTargetMotion; // 0x9b
	protected Boolean _markReachedOnlyWhenTargetEnter; // 0x9c
	private Boolean m_goThroughWall; // 0x9d
	protected Int32 m_layerMask; // 0xa0
	private MotionMask m_originTargetMotion; // 0xa4
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x20
	private static DelegateBridge __Hotfix0__DoTargetEnter; // 0x28
	private static DelegateBridge __Hotfix0__DoTargetExit; // 0x30
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0x38
	private static DelegateBridge __Hotfix0_OnTriggerExit2D; // 0x40
	private static DelegateBridge __Hotfix0_ClearStaticMethods; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1d66d18 VA: 0x759437ed18
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d67218 VA: 0x759437f218
	public override Void OnProjectileReached() { }
	// RVA: 0x1d675a8 VA: 0x759437f5a8
	public override Void OnProjectileStop() { }
	// RVA: 0x1d67964 VA: 0x759437f964
	protected virtual Void DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d67ad4 VA: 0x759437fad4
	private Void _DoTargetEnter(IPtrObject obj) { }
	// RVA: 0x1d67cf0 VA: 0x759437fcf0
	private Void _DoTargetExit(IPtrObject obj) { }
	// RVA: 0x1d67e68 VA: 0x759437fe68
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1d68174 VA: 0x7594380174
	private Void OnTriggerExit2D(Collider2D collision) { }
	// RVA: 0x1d6838c VA: 0x759438038c
	public static Void ClearStaticMethods() { }
	// RVA: 0x1d68454 VA: 0x7594380454
	public Void .ctor() { }
	// RVA: 0x1d684e0 VA: 0x75943804e0
	private static Void .cctor() { }
	// RVA: 0x1d68578 VA: 0x7594380578
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d68580 VA: 0x7594380580
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d68588 VA: 0x7594380588
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```