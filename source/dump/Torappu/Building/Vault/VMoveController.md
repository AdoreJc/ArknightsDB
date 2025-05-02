# VMoveController

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Single _steeringFactor`

- `Single _maxSteeringForce`

- `Single _halfBodyWidth`

- `Path m_path`

- `Int32 m_cursor`

- `Vector2 m_finalPosOffset`

- `Vector2 m_lastObstacleAvoidForce`

- `Vector2 m_lastVelocity`

- `PeriodicTicker m_obstacleAvoidTicker`

- `IMovable <mover>k__BackingField`


## Properties

- `Boolean isValid`

- `IMovable mover`

- `GridMap floorMap`

- `Single moveSpeed`


## Methods

- `Boolean get_isValid()`

- `IMovable get_mover()`

- `Void set_mover(IMovable)`

- `GridMap get_floorMap()`

- `Single get_moveSpeed()`

- `Void Init(IMovable)`

- `Void Begin(Path)`

- `Void End()`

- `Boolean Move(Single, out)`

- `Vector2 CalculateMoveDelta(Vector2, Single)`

- `Vector2 CalculateTotalForce(Vector2)`

- `Vector2 CalculateObstacleAvoidForce(Vector2)`

- `Vector2 GetNextDirection()`

- `Boolean PredictReached(Single, out)`

- `Vector2 GetFinalPathPos()`

- `Void _Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VMoveController : MonoBehaviour
{
	private const Int32 OBSTACLE_AVOID_TICK_PERIOD; // 0x0
	private Single _steeringFactor; // 0x18
	private Single _maxSteeringForce; // 0x1c
	private Single _halfBodyWidth; // 0x20
	private Path m_path; // 0x28
	private Int32 m_cursor; // 0x38
	private Vector2 m_finalPosOffset; // 0x3c
	private Vector2 m_lastObstacleAvoidForce; // 0x44
	private Vector2 m_lastVelocity; // 0x4c
	private PeriodicTicker m_obstacleAvoidTicker; // 0x58
	private IMovable <mover>k__BackingField; // 0x60

	public Boolean isValid { get; }
	protected IMovable mover { get; set; }
	protected GridMap floorMap { get; }
	protected Single moveSpeed { get; }

	// RVA: 0x38465c0 VA: 0x7595e5e5c0
	public Boolean get_isValid() { }
	// RVA: 0x384661c VA: 0x7595e5e61c
	protected IMovable get_mover() { }
	// RVA: 0x3846624 VA: 0x7595e5e624
	private Void set_mover(IMovable value) { }
	// RVA: 0x384662c VA: 0x7595e5e62c
	protected GridMap get_floorMap() { }
	// RVA: 0x38466d0 VA: 0x7595e5e6d0
	protected Single get_moveSpeed() { }
	// RVA: 0x3846774 VA: 0x7595e5e774
	public Void Init(IMovable mover) { }
	// RVA: 0x384677c VA: 0x7595e5e77c
	public Void Begin(Path path) { }
	// RVA: 0x38468c0 VA: 0x7595e5e8c0
	public Void End() { }
	// RVA: 0x38468c4 VA: 0x7595e5e8c4
	public Boolean Move(Single deltaTime, out Vector2 direction) { }
	// RVA: 0x3846f1c VA: 0x7595e5ef1c
	protected Vector2 CalculateMoveDelta(Vector2 direction, Single deltaTime) { }
	// RVA: 0x3847098 VA: 0x7595e5f098
	protected Vector2 CalculateTotalForce(Vector2 direction) { }
	// RVA: 0x3847348 VA: 0x7595e5f348
	protected Vector2 CalculateObstacleAvoidForce(Vector2 currentPos) { }
	// RVA: 0x3846d78 VA: 0x7595e5ed78
	protected Vector2 GetNextDirection() { }
	// RVA: 0x3846b84 VA: 0x7595e5eb84
	protected Boolean PredictReached(Single stepDistance, out Vector2 direction) { }
	// RVA: 0x3846d0c VA: 0x7595e5ed0c
	protected Vector2 GetFinalPathPos() { }
	// RVA: 0x3846818 VA: 0x7595e5e818
	private Void _Reset() { }
	// RVA: 0x3847908 VA: 0x7595e5f908
	public Void .ctor() { }
}
```