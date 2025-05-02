# SnsantSkill2ProjectileEffectBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _movingEffectsWhenReached`

- `Boolean _initMovingEffectWithMainEffect`

- `String _harpoonEffect`

- `Single _harpoonHeight`

- `Single _adjustRangeEffectOffset`

- `Boolean _hookStartPoint`

- `MountPointType _hookedStartPointType`

- `MountPoint m_startMountPoint`

- `Boolean m_targetIsMarkedEnemy`

- `Enemy m_markedEnemy`

- `UInt32 m_traceTargetUid`

- `Single m_cachedSqrDist`

- `Boolean m_forceInactiveMainEffect`


## Properties

- `Boolean hookStartPoint`


## Methods

- `Boolean get_hookStartPoint()`

- `Void _HarpoonInit(ILocatable)`

- `Boolean _TryHookStartPoint(out)`

- `Boolean _RefreshTargetAndEffect()`

- `Void _DoEffectMovement()`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SnsantSkill2ProjectileEffectBehaviour : Behaviour, IEffectSource
{
	private String[] _effectsWhenReached; // 0x28
	private String _movingEffectsWhenReached; // 0x30
	private Boolean _initMovingEffectWithMainEffect; // 0x38
	private String _harpoonEffect; // 0x40
	private Single _harpoonHeight; // 0x48
	private Single _adjustRangeEffectOffset; // 0x4c
	private Boolean _hookStartPoint; // 0x50
	private MountPointType _hookedStartPointType; // 0x54
	private const Single MAX_PULL_SQR_DIST; // 0x0
	private LineRenderer[] m_lineRenderers; // 0x58
	private MountPoint m_startMountPoint; // 0x60
	private Vector3[] m_positions; // 0x68
	private List`1 m_effects; // 0x70
	private Boolean m_targetIsMarkedEnemy; // 0x78
	private Enemy m_markedEnemy; // 0x80
	private ObjectPtr`1 m_cachedMovingEffect; // 0x88
	private UInt32 m_traceTargetUid; // 0x98
	private Single m_cachedSqrDist; // 0x9c
	private Boolean m_forceInactiveMainEffect; // 0xa0
	private static DelegateBridge __Hotfix0_get_hookStartPoint; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__HarpoonInit; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x18
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x20
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x28
	private static DelegateBridge __Hotfix0__TryHookStartPoint; // 0x30
	private static DelegateBridge __Hotfix0__RefreshTargetAndEffect; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0__DoEffectMovement; // 0x48
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Boolean hookStartPoint { get; }

	// RVA: 0x1d76524 VA: 0x759438e524
	private Boolean get_hookStartPoint() { }
	// RVA: 0x1d7658c VA: 0x759438e58c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d769f4 VA: 0x759438e9f4
	private Void _HarpoonInit(ILocatable start) { }
	// RVA: 0x1d76eec VA: 0x759438eeec
	public override Void OnProjectileBorn() { }
	// RVA: 0x1d76ffc VA: 0x759438effc
	public override Void OnProjectileStop() { }
	// RVA: 0x1d7722c VA: 0x759438f22c
	public override Void OnProjectileReached() { }
	// RVA: 0x1d76d74 VA: 0x759438ed74
	private Boolean _TryHookStartPoint(out MountPoint startPoint) { }
	// RVA: 0x1d766c8 VA: 0x759438e6c8
	private Boolean _RefreshTargetAndEffect() { }
	// RVA: 0x1d777c0 VA: 0x759438f7c0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d77ad4 VA: 0x759438fad4
	private Void _DoEffectMovement() { }
	// RVA: 0x1d77d8c VA: 0x759438fd8c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d77f30 VA: 0x759438ff30
	public Void .ctor() { }
	// RVA: 0x1d78060 VA: 0x7594390060
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d78068 VA: 0x7594390068
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1d78070 VA: 0x7594390070
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d78078 VA: 0x7594390078
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d78080 VA: 0x7594390080
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```