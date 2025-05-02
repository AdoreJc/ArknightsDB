# SimpleProjectile

**Namespace:** `Torappu.Battle`


## Fields

- `LifeType _lifeTimeType`

- `Single _lifeTime`

- `Boolean _getLifeTimeFromBB`

- `LifeType _hitNumType`

- `Int32 _maxHitNum`

- `Boolean _getMaxHitNumFromBB`

- `String _maxHitNumBBKey`

- `Boolean _stopAfterMaxHit`

- `Boolean _stopAfterFirstHit`

- `Boolean _stopWhenSourceInvalid`

- `Boolean _alwaysHitTraceTargetInTheEnd`

- `Boolean _alwaysHitTraceTargetWhenReached`

- `Boolean _alwaysReachInTheEnd`

- `Boolean _limitedMaxHitNumToSourceBlockedCnt`

- `Boolean _allowZeroBlockCntLimit`


## Properties

- `Boolean needLifeTime`

- `Boolean limitedHitNum`


## Methods

- `Boolean get_needLifeTime()`

- `Boolean get_limitedHitNum()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SimpleProjectile : Projectile
{
	private LifeType _lifeTimeType; // 0x181
	private Single _lifeTime; // 0x184
	private Boolean _getLifeTimeFromBB; // 0x188
	private LifeType _hitNumType; // 0x189
	private Int32 _maxHitNum; // 0x18c
	private Boolean _getMaxHitNumFromBB; // 0x190
	private String _maxHitNumBBKey; // 0x198
	private Boolean _stopAfterMaxHit; // 0x1a0
	private Boolean _stopAfterFirstHit; // 0x1a1
	private Boolean _stopWhenSourceInvalid; // 0x1a2
	private Boolean _alwaysHitTraceTargetInTheEnd; // 0x1a3
	private Boolean _alwaysHitTraceTargetWhenReached; // 0x1a4
	private Boolean _alwaysReachInTheEnd; // 0x1a5
	private Boolean _limitedMaxHitNumToSourceBlockedCnt; // 0x1a6
	private Boolean _allowZeroBlockCntLimit; // 0x1a7
	private static DelegateBridge __Hotfix0_get_needLifeTime; // 0x0
	private static DelegateBridge __Hotfix0_get_limitedHitNum; // 0x8
	private static DelegateBridge __Hotfix0_get_stopAfterMaxHit; // 0x10
	private static DelegateBridge __Hotfix0_get_stopAfterFirstHit; // 0x18
	private static DelegateBridge __Hotfix0_get_stopWhenSourceInvalid; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysHitTraceTargetInTheEnd; // 0x28
	private static DelegateBridge __Hotfix0_get_alwaysHitTraceTargetWhenReached; // 0x30
	private static DelegateBridge __Hotfix0_get_alwaysReachInTheEnd; // 0x38
	private static DelegateBridge __Hotfix0_GetLifeTime; // 0x40
	private static DelegateBridge __Hotfix0_GetMaxHitNum; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Boolean needLifeTime { get; }
	private Boolean limitedHitNum { get; }
	protected override Boolean stopAfterMaxHit { get; }
	protected override Boolean stopAfterFirstHit { get; }
	protected override Boolean stopWhenSourceInvalid { get; }
	protected override Boolean alwaysHitTraceTargetInTheEnd { get; }
	protected override Boolean alwaysHitTraceTargetWhenReached { get; }
	protected override Boolean alwaysReachInTheEnd { get; }

	// RVA: 0x40b58d4 VA: 0x75966cd8d4
	private Boolean get_needLifeTime() { }
	// RVA: 0x40b5944 VA: 0x75966cd944
	private Boolean get_limitedHitNum() { }
	// RVA: 0x40b59b4 VA: 0x75966cd9b4
	protected override Boolean get_stopAfterMaxHit() { }
	// RVA: 0x40b5a1c VA: 0x75966cda1c
	protected override Boolean get_stopAfterFirstHit() { }
	// RVA: 0x40b5a84 VA: 0x75966cda84
	protected override Boolean get_stopWhenSourceInvalid() { }
	// RVA: 0x40b5aec VA: 0x75966cdaec
	protected override Boolean get_alwaysHitTraceTargetInTheEnd() { }
	// RVA: 0x40b5b54 VA: 0x75966cdb54
	protected override Boolean get_alwaysHitTraceTargetWhenReached() { }
	// RVA: 0x40b5bbc VA: 0x75966cdbbc
	protected override Boolean get_alwaysReachInTheEnd() { }
	// RVA: 0x40b5c24 VA: 0x75966cdc24
	protected override Single GetLifeTime() { }
	// RVA: 0x40b5d7c VA: 0x75966cdd7c
	public override Int32 GetMaxHitNum() { }
	// RVA: 0x40b5eb4 VA: 0x75966cdeb4
	public Void .ctor() { }
}
```