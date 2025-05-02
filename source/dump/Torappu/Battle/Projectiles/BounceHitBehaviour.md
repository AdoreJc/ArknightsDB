# BounceHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Int32 m_bounceTimes`

- `Boolean _bounceTimesAsDamageTimes`

- `Single _perDamageInterval`

- `Boolean _allowRepetitionIfNoTarget`

- `Boolean _isChainLightingUse`

- `Single _atkScaleRatePerBounce`

- `Boolean _canSelectAllExceptTracetarget`

- `Boolean _dealHitWithOtherSelector`

- `Boolean _hitTraceTargetIfNoOtherTarget`

- `Boolean _useMapPosIfTargetInvalid`

- `TargetSelector _hitSelector`

- `Boolean _fixAllowRepetitionIfNoTarget`

- `BouncedAdvancedMovement m_movement`

- `Single m_maxBounceDamageDuration`

- `Int32 m_allBounceTime`

- `FP m_atkScaleRatePerBounce`


## Properties

- `Boolean BounceTimesAsDamageTimes`

- `Boolean DealHitWithOtherSelector`


## Methods

- `Boolean get_BounceTimesAsDamageTimes()`

- `Boolean get_DealHitWithOtherSelector()`

- `Void _StopProjectile()`

- `Void <_StopProjectile>b__24_0()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class BounceHitBehaviour : SelectorHitBehaviour
{
	private Int32 m_bounceTimes; // 0x80
	private Boolean _bounceTimesAsDamageTimes; // 0x84
	private Single _perDamageInterval; // 0x88
	private Boolean _allowRepetitionIfNoTarget; // 0x8c
	private Boolean _isChainLightingUse; // 0x8d
	private Single _atkScaleRatePerBounce; // 0x90
	private Boolean _canSelectAllExceptTracetarget; // 0x94
	private Boolean _dealHitWithOtherSelector; // 0x95
	private Boolean _hitTraceTargetIfNoOtherTarget; // 0x96
	private Boolean _useMapPosIfTargetInvalid; // 0x97
	private TargetSelector _hitSelector; // 0x98
	private Boolean _fixAllowRepetitionIfNoTarget; // 0xa0
	private BouncedAdvancedMovement m_movement; // 0xa8
	private List`1 m_targetsList; // 0xb0
	private Single m_maxBounceDamageDuration; // 0xb8
	private List`1 m_coroutineIdList; // 0xc0
	private Int32 m_allBounceTime; // 0xc8
	private FP m_atkScaleRatePerBounce; // 0xd0
	private static DelegateBridge __Hotfix0_get_BounceTimesAsDamageTimes; // 0x0
	private static DelegateBridge __Hotfix0_get_DealHitWithOtherSelector; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x18
	private static DelegateBridge __Hotfix0__StopProjectile; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected Boolean BounceTimesAsDamageTimes { get; }
	protected Boolean DealHitWithOtherSelector { get; }

	// RVA: 0x1d5ce58 VA: 0x7594374e58
	protected Boolean get_BounceTimesAsDamageTimes() { }
	// RVA: 0x1d5cec0 VA: 0x7594374ec0
	protected Boolean get_DealHitWithOtherSelector() { }
	// RVA: 0x1d5cf28 VA: 0x7594374f28
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d5d380 VA: 0x7594375380
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d5ded0 VA: 0x7594375ed0
	private Void _StopProjectile() { }
	// RVA: 0x1d5e004 VA: 0x7594376004
	public Void .ctor() { }
	// RVA: 0x1d5e12c VA: 0x759437612c
	private Void <_StopProjectile>b__24_0() { }
	// RVA: 0x1d5e2b0 VA: 0x75943762b0
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d5e2b8 VA: 0x75943762b8
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
}
```