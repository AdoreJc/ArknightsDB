# MovementSwitchControllerBasedOnTime

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `PeriodicTimer m_timer`


## Methods

- `Void _UpdateMovementIndexAndTimer()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile, GroupedMovement)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class MovementSwitchControllerBasedOnTime : MovementSwitchController
{
	private List`1 _periodTimeBBKeys; // 0x40
	private List`1 m_timeSlots; // 0x48
	private PeriodicTimer m_timer; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__UpdateMovementIndexAndTimer; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1da390c VA: 0x75943bb90c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile, GroupedMovement groupedMovement) { }
	// RVA: 0x1da3d2c VA: 0x75943bbd2c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1da3e10 VA: 0x75943bbe10
	private Void _UpdateMovementIndexAndTimer() { }
	// RVA: 0x1da3f48 VA: 0x75943bbf48
	public Void .ctor() { }
	// RVA: 0x1da4008 VA: 0x75943bc008
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2, GroupedMovement P3) { }
	// RVA: 0x1da400c VA: 0x75943bc00c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```