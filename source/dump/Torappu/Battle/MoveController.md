# MoveController

**Namespace:** `Torappu.Battle`


## Fields

- `Single _steeringFactor`

- `Single _maxSteeringForce`

- `Single _halfBodyWidth`

- `Single m_steeringFactor`

- `IMovable m_target`

- `Vector2 m_footOffset`

- `Vector2 m_lastVelocity`

- `Vector2 m_lastObstacleAvoidForce`

- `Vector2 m_lastSeparationForce`

- `PeriodicTicker m_obstacleAvoidTicker`

- `PeriodicTicker m_separationTicker`


## Properties

- `Vector2 velocity`

- `Single steeringFactor`

- `Vector2 footOffset`

- `Single halfBodyWidth`


## Methods

- `Vector2 get_velocity()`

- `Void set_velocity(Vector2)`

- `Single get_steeringFactor()`

- `Void set_steeringFactor(Single)`

- `Vector2 get_footOffset()`

- `Single get_halfBodyWidth()`

- `Void Reset(IMovable)`

- `Vector2 CalculateTotalForce(Vector2, out)`

- `Vector2 _CalculateObstacleAvoidForce(Vector2, Vector2, MotionMode)`

- `Vector2 _GetFootMapPosition()`

- `Vector2 GetBodyEdgeOffset(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MoveController : MonoBehaviour, IHotfixable
{
	private const Int32 OBSTACLE_AVOID_TICK_PERIOD; // 0x0
	private const Single OBSTACLE_AVOID_FORCE_FACTOR; // 0x0
	private const Single MIN_OBSTACLE_AVOID_INFLUENCE_FACTOR; // 0x0
	private const Int32 SEPARATION_TICK_PERIOD; // 0x0
	private const Single SEPARATION_FORCE_FACTOR; // 0x0
	private const Single SEPARATION_RADIUS; // 0x0
	private const Single MIN_SEPARATION_SUM_DELTA; // 0x0
	private const Single TILE_NEAR_THRESHOLD; // 0x0
	private Single _steeringFactor; // 0x18
	protected Single _maxSteeringForce; // 0x1c
	private Single _halfBodyWidth; // 0x20
	protected Single m_steeringFactor; // 0x24
	protected IMovable m_target; // 0x28
	private Vector2 m_footOffset; // 0x30
	protected Vector2 m_lastVelocity; // 0x38
	private Vector2 m_lastObstacleAvoidForce; // 0x40
	protected Vector2 m_lastSeparationForce; // 0x48
	protected PeriodicTicker m_obstacleAvoidTicker; // 0x50
	protected PeriodicTicker m_separationTicker; // 0x58
	private static DelegateBridge __Hotfix0_get_moveSpeed; // 0x0
	private static DelegateBridge __Hotfix0_get_velocity; // 0x8
	private static DelegateBridge __Hotfix0_set_velocity; // 0x10
	private static DelegateBridge __Hotfix0_get_steeringFactor; // 0x18
	private static DelegateBridge __Hotfix0_set_steeringFactor; // 0x20
	private static DelegateBridge __Hotfix0_get_footOffset; // 0x28
	private static DelegateBridge __Hotfix0_get_halfBodyWidth; // 0x30
	private static DelegateBridge __Hotfix0_Reset; // 0x38
	private static DelegateBridge __Hotfix0_OnStart; // 0x40
	private static DelegateBridge __Hotfix0_CalculateMoveDelta; // 0x48
	private static DelegateBridge __Hotfix0_CalculateTotalForce; // 0x50
	private static DelegateBridge __Hotfix0__CalculateSteeringForce; // 0x58
	private static DelegateBridge __Hotfix0_CalculateIsHanging; // 0x60
	private static DelegateBridge __Hotfix0__CalculateObstacleAvoidForce; // 0x68
	private static DelegateBridge __Hotfix0__GetFootMapPosition; // 0x70
	private static DelegateBridge __Hotfix0_GetBodyEdgeOffset; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public virtual Single moveSpeed { get; }
	public Vector2 velocity { get; set; }
	public Single steeringFactor { get; set; }
	public Vector2 footOffset { get; }
	public Single halfBodyWidth { get; }

	// RVA: 0x40a0cbc VA: 0x75966b8cbc
	public virtual Single get_moveSpeed() { }
	// RVA: 0x40a0d94 VA: 0x75966b8d94
	public Vector2 get_velocity() { }
	// RVA: 0x40a0df8 VA: 0x75966b8df8
	public Void set_velocity(Vector2 value) { }
	// RVA: 0x40a0e7c VA: 0x75966b8e7c
	public Single get_steeringFactor() { }
	// RVA: 0x40a0ee4 VA: 0x75966b8ee4
	public Void set_steeringFactor(Single value) { }
	// RVA: 0x40a0f60 VA: 0x75966b8f60
	public Vector2 get_footOffset() { }
	// RVA: 0x40a0fc4 VA: 0x75966b8fc4
	public Single get_halfBodyWidth() { }
	// RVA: 0x40a102c VA: 0x75966b902c
	public Void Reset(IMovable target) { }
	// RVA: 0x40a1138 VA: 0x75966b9138
	public virtual Void OnStart() { }
	// RVA: 0x40a12ac VA: 0x75966b92ac
	public virtual Vector2 CalculateMoveDelta(Vector2 direction, Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x40a1500 VA: 0x75966b9500
	private Vector2 CalculateTotalForce(Vector2 direction, out Boolean isHanging) { }
	// RVA: 0x40a1708 VA: 0x75966b9708
	protected virtual Vector2 _CalculateSteeringForce(Vector2 moveForce, Vector2 direction) { }
	// RVA: 0x40a1908 VA: 0x75966b9908
	protected virtual Void CalculateIsHanging(Vector2 direction, ref Vector2 resultForce) { }
	// RVA: 0x40a1c6c VA: 0x75966b9c6c
	private Vector2 _CalculateObstacleAvoidForce(Vector2 mapPos, Vector2 footPos, MotionMode motionMode) { }
	// RVA: 0x40a1b88 VA: 0x75966b9b88
	private Vector2 _GetFootMapPosition() { }
	// RVA: 0x40a22a0 VA: 0x75966ba2a0
	public Vector2 GetBodyEdgeOffset(Vector2 direction) { }
	// RVA: 0x40a2378 VA: 0x75966ba378
	public Void .ctor() { }
}
```