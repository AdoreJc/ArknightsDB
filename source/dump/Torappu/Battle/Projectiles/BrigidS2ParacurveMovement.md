# BrigidS2ParacurveMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `Boolean m_hasReachedTargetOnce`

- `Boolean m_inReachedDelayState`

- `Boolean m_leaveFirstTarget`

- `Single m_delayTimer`

- `Entity m_cacheTraceTarget`


## Methods

- `Boolean _CheckProjectileMissTarget()`

- `Void _DoCheckReachedUpdateState(FP)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DoCheckReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class BrigidS2ParacurveMovement : ParacurveMovement
{
	private TargetOptions _targetOptions; // 0xe0
	private Boolean m_hasReachedTargetOnce; // 0x140
	private Boolean m_inReachedDelayState; // 0x141
	private Boolean m_leaveFirstTarget; // 0x142
	private Single m_delayTimer; // 0x144
	private Entity m_cacheTraceTarget; // 0x148
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_DoCheckReached; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0__CheckProjectileMissTarget; // 0x20
	private static DelegateBridge __Hotfix0__DoCheckReachedUpdateState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1d9f8d8 VA: 0x75943b78d8
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d9fae0 VA: 0x75943b7ae0
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9ff90 VA: 0x75943b7f90
	protected override Void DoCheckReached() { }
	// RVA: 0x1d9fff4 VA: 0x75943b7ff4
	public override Void OnProjectileStop() { }
	// RVA: 0x1da0070 VA: 0x75943b8070
	private Boolean _CheckProjectileMissTarget() { }
	// RVA: 0x1d9fca4 VA: 0x75943b7ca4
	private Void _DoCheckReachedUpdateState(FP deltaTimeFp) { }
	// RVA: 0x1da05fc VA: 0x75943b85fc
	public Void .ctor() { }
	// RVA: 0x1da06f4 VA: 0x75943b86f4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1da06f8 VA: 0x75943b86f8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1da06fc VA: 0x75943b86fc
	private Void <>xLuaBaseProxy_DoCheckReached() { }
	// RVA: 0x1da0890 VA: 0x75943b8890
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```