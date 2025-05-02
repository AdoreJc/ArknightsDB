# RacingMoveController

**Namespace:** `Torappu.Battle.Racing`


## Fields

- `Vector2 <dragForce>k__BackingField`


## Properties

- `Vector2 dragForce`


## Methods

- `Vector2 get_dragForce()`

- `Void set_dragForce(Vector2)`

- `Void InitRacingMoveController(RacingEnemy)`

- `Single _CalculateRacingSteeringFactor()`

- `Vector2 <>xLuaBaseProxy_CalculateMoveDelta(Vector2, Single, out)`

- `Vector2 <>xLuaBaseProxy__CalculateSteeringForce(Vector2, Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Racing
public class RacingMoveController : MoveController
{
	private ObjectPtr`1 m_owner; // 0x60
	private Vector2 <dragForce>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_dragForce; // 0x0
	private static DelegateBridge __Hotfix0_set_dragForce; // 0x8
	private static DelegateBridge __Hotfix0_InitRacingMoveController; // 0x10
	private static DelegateBridge __Hotfix0_CalculateMoveDelta; // 0x18
	private static DelegateBridge __Hotfix0__CalculateSteeringForce; // 0x20
	private static DelegateBridge __Hotfix0__CalculateRacingSteeringFactor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Vector2 dragForce { get; set; }

	// RVA: 0x1d5b378 VA: 0x7594373378
	public Vector2 get_dragForce() { }
	// RVA: 0x1d5b3dc VA: 0x75943733dc
	public Void set_dragForce(Vector2 value) { }
	// RVA: 0x1d5b460 VA: 0x7594373460
	public Void InitRacingMoveController(RacingEnemy owner) { }
	// RVA: 0x1d5b524 VA: 0x7594373524
	public override Vector2 CalculateMoveDelta(Vector2 direction, Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1d5b5f8 VA: 0x75943735f8
	protected override Vector2 _CalculateSteeringForce(Vector2 moveForce, Vector2 direction) { }
	// RVA: 0x1d5b744 VA: 0x7594373744
	private Single _CalculateRacingSteeringFactor() { }
	// RVA: 0x1d5b830 VA: 0x7594373830
	public Void .ctor() { }
	// RVA: 0x1d5b8a0 VA: 0x75943738a0
	private Vector2 <>xLuaBaseProxy_CalculateMoveDelta(Vector2 P0, Single P1, out Boolean P2) { }
	// RVA: 0x1d5b8a8 VA: 0x75943738a8
	private Vector2 <>xLuaBaseProxy__CalculateSteeringForce(Vector2 P0, Vector2 P1) { }
}
```