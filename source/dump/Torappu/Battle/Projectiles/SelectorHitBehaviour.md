# SelectorHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetSelector _selector`

- `Boolean _resetRangeSelectorByBB`

- `Boolean _ignoreRangeScale`

- `Single _interval`

- `Boolean _waitFirstPeriod`

- `Single _firstPeriod`

- `Boolean _onlyCheckHitWhenReachTarget`

- `Boolean _onlyCheckHitWhenStop`

- `Boolean _exceptTraceTarget`

- `Boolean _hitPasserby`

- `Boolean _ignoreSmallEps`

- `Single _effectsWhenSelectPredict`

- `Boolean _selectEffectOnGround`

- `Boolean _playAudioWhenSelect`

- `PeriodicTimer m_periodicTimer`

- `Single m_effectsWhenSelectPredict`

- `Boolean m_effectsWhenSelectPredictPlayed`

- `Single m_targetGroundPosZ`

- `ILocatable m_target`


## Properties

- `TargetSelector selector`

- `Boolean playAudioWhenSelect`

- `Boolean selectEffectOnGround`

- `Boolean checkHitWhenTick`


## Methods

- `TargetSelector get_selector()`

- `Boolean get_playAudioWhenSelect()`

- `Boolean get_selectEffectOnGround()`

- `Boolean get_checkHitWhenTick()`

- `Void GatherEffects(List`1)`

- `Void _PlayEffectsWhenSelect()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SelectorHitBehaviour : Behaviour, IEffectSource
{
	private TargetSelector _selector; // 0x28
	private Boolean _resetRangeSelectorByBB; // 0x30
	private Boolean _ignoreRangeScale; // 0x31
	private Single _interval; // 0x34
	private Boolean _waitFirstPeriod; // 0x38
	private Single _firstPeriod; // 0x3c
	private Boolean _onlyCheckHitWhenReachTarget; // 0x40
	private Boolean _onlyCheckHitWhenStop; // 0x41
	private Boolean _exceptTraceTarget; // 0x42
	private Boolean _hitPasserby; // 0x43
	private Boolean _ignoreSmallEps; // 0x44
	private Single _effectsWhenSelectPredict; // 0x48
	private Boolean _selectEffectOnGround; // 0x4c
	protected String[] _effectsWhenSelect; // 0x50
	private Boolean _playAudioWhenSelect; // 0x58
	private PeriodicTimer m_periodicTimer; // 0x60
	protected Single m_effectsWhenSelectPredict; // 0x68
	protected Boolean m_effectsWhenSelectPredictPlayed; // 0x6c
	private Single m_targetGroundPosZ; // 0x70
	private ILocatable m_target; // 0x78
	private static DelegateBridge __Hotfix0_get_selector; // 0x0
	private static DelegateBridge __Hotfix0_get_playAudioWhenSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_selectEffectOnGround; // 0x10
	private static DelegateBridge __Hotfix0_get_checkHitWhenTick; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x30
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x38
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x40
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x48
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x50
	private static DelegateBridge __Hotfix0__PlayEffectsWhenSelect; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected TargetSelector selector { get; }
	protected Boolean playAudioWhenSelect { get; }
	public Boolean selectEffectOnGround { get; }
	private Boolean checkHitWhenTick { get; }

	// RVA: 0x1d6bbd8 VA: 0x7594383bd8
	protected TargetSelector get_selector() { }
	// RVA: 0x1d72488 VA: 0x759438a488
	protected Boolean get_playAudioWhenSelect() { }
	// RVA: 0x1d72ef8 VA: 0x759438aef8
	public Boolean get_selectEffectOnGround() { }
	// RVA: 0x1d72f60 VA: 0x759438af60
	private Boolean get_checkHitWhenTick() { }
	// RVA: 0x1d711a8 VA: 0x75943891a8
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d72fe0 VA: 0x759438afe0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d6bb28 VA: 0x7594383b28
	public override Void OnProjectileReached() { }
	// RVA: 0x1d73294 VA: 0x759438b294
	public override Void OnProjectileStop() { }
	// RVA: 0x1d73360 VA: 0x759438b360
	protected virtual Boolean DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d73468 VA: 0x759438b468
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d71d28 VA: 0x7594389d28
	protected virtual Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d722d0 VA: 0x759438a2d0
	protected Void _PlayEffectsWhenSelect() { }
	// RVA: 0x1d71c24 VA: 0x7594389c24
	public Void .ctor() { }
	// RVA: 0x1d7351c VA: 0x759438b51c
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d73524 VA: 0x759438b524
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d7352c VA: 0x759438b52c
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d73534 VA: 0x759438b534
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```