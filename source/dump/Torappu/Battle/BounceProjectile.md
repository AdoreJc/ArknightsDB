# BounceProjectile

**Namespace:** `Torappu.Battle`


## Fields

- `LifeType _lifeTimeType`

- `Single _lifeTime`


## Methods

- `Boolean <>xLuaBaseProxy_CheckTargetAlreadyHitAndUpdate(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BounceProjectile : Projectile
{
	private LifeType _lifeTimeType; // 0x181
	private Single _lifeTime; // 0x184
	private static DelegateBridge __Hotfix0_get_stopAfterMaxHit; // 0x0
	private static DelegateBridge __Hotfix0_get_stopAfterFirstHit; // 0x8
	private static DelegateBridge __Hotfix0_get_stopWhenSourceInvalid; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysHitTraceTargetInTheEnd; // 0x18
	private static DelegateBridge __Hotfix0_get_alwaysHitTraceTargetWhenReached; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysReachInTheEnd; // 0x28
	private static DelegateBridge __Hotfix0_GetLifeTime; // 0x30
	private static DelegateBridge __Hotfix0_GetMaxHitNum; // 0x38
	private static DelegateBridge __Hotfix0_CheckTargetAlreadyHitAndUpdate; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected override Boolean stopAfterMaxHit { get; }
	protected override Boolean stopAfterFirstHit { get; }
	protected override Boolean stopWhenSourceInvalid { get; }
	protected override Boolean alwaysHitTraceTargetInTheEnd { get; }
	protected override Boolean alwaysHitTraceTargetWhenReached { get; }
	protected override Boolean alwaysReachInTheEnd { get; }

	// RVA: 0x40a419c VA: 0x75966bc19c
	protected override Boolean get_stopAfterMaxHit() { }
	// RVA: 0x40a4200 VA: 0x75966bc200
	protected override Boolean get_stopAfterFirstHit() { }
	// RVA: 0x40a4264 VA: 0x75966bc264
	protected override Boolean get_stopWhenSourceInvalid() { }
	// RVA: 0x40a42c8 VA: 0x75966bc2c8
	protected override Boolean get_alwaysHitTraceTargetInTheEnd() { }
	// RVA: 0x40a432c VA: 0x75966bc32c
	protected override Boolean get_alwaysHitTraceTargetWhenReached() { }
	// RVA: 0x40a4390 VA: 0x75966bc390
	protected override Boolean get_alwaysReachInTheEnd() { }
	// RVA: 0x40a43f4 VA: 0x75966bc3f4
	protected override Single GetLifeTime() { }
	// RVA: 0x40a44f4 VA: 0x75966bc4f4
	public override Int32 GetMaxHitNum() { }
	// RVA: 0x40a455c VA: 0x75966bc55c
	protected override Boolean CheckTargetAlreadyHitAndUpdate(Entity target) { }
	// RVA: 0x40a45d4 VA: 0x75966bc5d4
	public Void .ctor() { }
	// RVA: 0x40a4860 VA: 0x75966bc860
	private Boolean <>xLuaBaseProxy_CheckTargetAlreadyHitAndUpdate(Entity P0) { }
}
```