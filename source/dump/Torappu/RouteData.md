# RouteData

**Namespace:** `Torappu`


## Fields

- `MotionMode motionMode`

- `GridPosition startPosition`

- `GridPosition endPosition`

- `Vector2 spawnRandomRange`

- `Vector2 spawnOffset`

- `Boolean allowDiagonalMove`

- `Boolean visitEveryTileCenter`

- `Boolean visitEveryNodeCenter`

- `Boolean visitEveryCheckPoint`


## Methods

- `RouteData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RouteData
{
	public MotionMode motionMode; // 0x10
	public GridPosition startPosition; // 0x14
	public GridPosition endPosition; // 0x1c
	public Vector2 spawnRandomRange; // 0x24
	public Vector2 spawnOffset; // 0x2c
	public CheckpointData[] checkpoints; // 0x38
	public Boolean allowDiagonalMove; // 0x40
	public Boolean visitEveryTileCenter; // 0x41
	public Boolean visitEveryNodeCenter; // 0x42
	public Boolean visitEveryCheckPoint; // 0x43


	// RVA: 0x34a3bc0 VA: 0x7595abbbc0
	public RouteData Duplicate() { }
	// RVA: 0x34a3d78 VA: 0x7595abbd78
	public Void .ctor() { }
}
```