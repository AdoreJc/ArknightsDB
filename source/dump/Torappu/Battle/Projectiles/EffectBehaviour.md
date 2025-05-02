# EffectBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _onlyPlayHitEffectOnTraceTarget`

- `Boolean _onlyPlayHitEffectOnNotTraceTarget`

- `Boolean _onlyPlayHitEffectOnce`

- `Boolean _clearHitEffectOnStop`

- `Boolean _clearPlayEffectOnStop`

- `Boolean _clearReachedEffectWhenStop`

- `Boolean _alwaysPlayStartEffects`

- `Boolean _playStartEffectOnlyOnProjectile`

- `Boolean _useSourceFaceVector`

- `Boolean _useSourceFaceVectorOnHit`

- `Boolean _forceReachTargetGround`

- `Boolean _followTargetGround`

- `Boolean _replaceMainEffectWhenReach`

- `String _mainEffectToReplace`

- `Boolean _useTraceTargetWhenReach`

- `Boolean _setReachEffectOnProjectile`

- `Boolean _syncEffectScaleViaProjectile`

- `Single m_targetGroundPosZ`

- `ILocatable m_target`

- `Int32 m_hitEffectCount`


## Properties

- `Boolean IsReplaceMainEffectWhenReach`


## Methods

- `Boolean get_IsReplaceMainEffectWhenReach()`

- `Void _GetNewEffectIfHooked(ref)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class EffectBehaviour : Behaviour, IEffectSource
{
	private String[] _effectsWhenStart; // 0x28
	private String[] _effectsWhenReached; // 0x30
	private String[] _effectsWhenHit; // 0x38
	private String[] _effectsToTargetWhenStart; // 0x40
	private String[] _effectsToTileWhenStart; // 0x48
	private String[] _effectsWhenStop; // 0x50
	protected Boolean _onlyPlayHitEffectOnTraceTarget; // 0x58
	protected Boolean _onlyPlayHitEffectOnNotTraceTarget; // 0x59
	private Boolean _onlyPlayHitEffectOnce; // 0x5a
	protected Boolean _clearHitEffectOnStop; // 0x5b
	private Boolean _clearPlayEffectOnStop; // 0x5c
	private Boolean _clearReachedEffectWhenStop; // 0x5d
	private Boolean _alwaysPlayStartEffects; // 0x5e
	private Boolean _playStartEffectOnlyOnProjectile; // 0x5f
	private Boolean _useSourceFaceVector; // 0x60
	protected Boolean _useSourceFaceVectorOnHit; // 0x61
	private Boolean _forceReachTargetGround; // 0x62
	private Boolean _followTargetGround; // 0x63
	private Boolean _replaceMainEffectWhenReach; // 0x64
	private String _mainEffectToReplace; // 0x68
	private Boolean _useTraceTargetWhenReach; // 0x70
	private Boolean _setReachEffectOnProjectile; // 0x71
	private Boolean _syncEffectScaleViaProjectile; // 0x72
	private Single m_targetGroundPosZ; // 0x74
	private ILocatable m_target; // 0x78
	private Int32 m_hitEffectCount; // 0x80
	protected List`1 m_effects; // 0x88
	private static DelegateBridge __Hotfix0_get_IsReplaceMainEffectWhenReach; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x28
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x30
	private static DelegateBridge __Hotfix0__GetNewEffectIfHooked; // 0x38
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Boolean IsReplaceMainEffectWhenReach { get; }

	// RVA: 0x1d61f6c VA: 0x7594379f6c
	private Boolean get_IsReplaceMainEffectWhenReach() { }
	// RVA: 0x1d61fd4 VA: 0x7594379fd4
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d62124 VA: 0x759437a124
	public override Void OnProjectileBorn() { }
	// RVA: 0x1d628cc VA: 0x759437a8cc
	public override Void OnProjectileStop() { }
	// RVA: 0x1d62b58 VA: 0x759437ab58
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d62c28 VA: 0x759437ac28
	public override Void OnProjectileReached() { }
	// RVA: 0x1d630e0 VA: 0x759437b0e0
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d62794 VA: 0x759437a794
	protected Void _GetNewEffectIfHooked(ref String effectKey) { }
	// RVA: 0x1d636e0 VA: 0x759437b6e0
	public virtual Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d63898 VA: 0x759437b898
	public Void .ctor() { }
	// RVA: 0x1d639d0 VA: 0x759437b9d0
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d639d8 VA: 0x759437b9d8
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1d639e0 VA: 0x759437b9e0
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d639e8 VA: 0x759437b9e8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d639f0 VA: 0x759437b9f0
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d639f8 VA: 0x759437b9f8
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
}
```