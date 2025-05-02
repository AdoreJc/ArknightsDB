# DirectionCursor

**Namespace:** `Torappu.Battle`


## Fields

- `Vector2 m_offset`

- `GridPosition m_nextGrid`

- `Single <totalDist>k__BackingField`


## Properties

- `Single totalDist`

- `Int32 cursorIndex`


## Methods

- `Single get_totalDist()`

- `Void set_totalDist(Single)`

- `Int32 get_cursorIndex()`

- `Boolean TryGetCurrentCheckpointType(out)`

- `Boolean CheckObstacleLikeOrInvalid()`

- `Void AssignHostRouteProgress(Int32)`

- `Vector2 GetNextTarget()`

- `Vector2 _GetNextTarget()`

- `Vector2 GetNextTurn(Vector2)`

- `Vector2 PredictFuturePosition(Single, Boolean, Boolean)`

- `Boolean TryGetDistanceToNextCheckpoint(out)`

- `Boolean TryGetCheckpointTargetPos(Int32, out)`

- `Boolean TryGetNextAppearCheckpoint(out, out)`

- `Boolean TryGetDistanceToMapPosInCheckpointsAhead(GridPosition, out)`

- `Boolean _CheckNextCpShouldNotSkip(Int32)`

- `Void OnTick(FP)`

- `CheckpointType GetCurCheckpointType()`

- `Boolean TrySkipIfCurrentCheckpointIsWaitForSeconds(Boolean)`

- `GridPosition _GetNextGrid(GridPosition)`

- `Vector2 GetLocatorPosition()`

- `GridPosition GetNextGrid(GridPosition)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DirectionCursor : BasicCursor
{
	private Boolean[,] m_visitedMap; // 0x60
	private Vector2 m_offset; // 0x68
	private GridPosition m_nextGrid; // 0x70
	private Single <totalDist>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_distToExit; // 0x0
	private static DelegateBridge __Hotfix0_get_distToExitPrecise; // 0x8
	private static DelegateBridge __Hotfix0_get_totalDist; // 0x10
	private static DelegateBridge __Hotfix0_set_totalDist; // 0x18
	private static DelegateBridge __Hotfix0_get_cursorIndex; // 0x20
	private static DelegateBridge __Hotfix0_TryGetCurrentCheckpointType; // 0x28
	private static DelegateBridge __Hotfix0_CheckObstacleLikeOrInvalid; // 0x30
	private static DelegateBridge __Hotfix0_AssignHostRouteProgress; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40
	private static DelegateBridge __Hotfix0_Reset; // 0x48
	private static DelegateBridge __Hotfix0_CheckReached; // 0x50
	private static DelegateBridge __Hotfix0_PredictReached; // 0x58
	private static DelegateBridge __Hotfix0_GetNextTarget; // 0x60
	private static DelegateBridge __Hotfix0__GetNextTarget; // 0x68
	private static DelegateBridge __Hotfix0_GetNextDirection; // 0x70
	private static DelegateBridge __Hotfix0_GetNextTurn; // 0x78
	private static DelegateBridge __Hotfix0_PredictFuturePosition; // 0x80
	private static DelegateBridge __Hotfix0_TryGetDistanceToNextCheckpoint; // 0x88
	private static DelegateBridge __Hotfix0_TryGetCheckpointTargetPos; // 0x90
	private static DelegateBridge __Hotfix0_TryGetNextAppearCheckpoint; // 0x98
	private static DelegateBridge __Hotfix0_TryGetDistanceToMapPosInCheckpointsAhead; // 0xa0
	private static DelegateBridge __Hotfix0__CheckNextCpShouldNotSkip; // 0xa8
	private static DelegateBridge __Hotfix0_OnTick; // 0xb0
	private static DelegateBridge __Hotfix0_GetCurCheckpointType; // 0xb8
	private static DelegateBridge __Hotfix0_TrySkipIfCurrentCheckpointIsWaitForSeconds; // 0xc0
	private static DelegateBridge __Hotfix0__GetNextGrid; // 0xc8
	private static DelegateBridge __Hotfix0_GetLocatorPosition; // 0xd0
	private static DelegateBridge __Hotfix0_GetNextGrid; // 0xd8

	public virtual Single distToExit { get; }
	public virtual Single distToExitPrecise { get; }
	public Single totalDist { get; set; }
	public Int32 cursorIndex { get; }

	// RVA: 0x407ac2c VA: 0x7596692c2c
	public virtual Single get_distToExit() { }
	// RVA: 0x407ad84 VA: 0x7596692d84
	public virtual Single get_distToExitPrecise() { }
	// RVA: 0x407e47c VA: 0x759669647c
	public Single get_totalDist() { }
	// RVA: 0x407e4e4 VA: 0x75966964e4
	private Void set_totalDist(Single value) { }
	// RVA: 0x407e560 VA: 0x7596696560
	public Int32 get_cursorIndex() { }
	// RVA: 0x407e5c8 VA: 0x75966965c8
	public Boolean TryGetCurrentCheckpointType(out CheckpointType cpType) { }
	// RVA: 0x407e6a8 VA: 0x75966966a8
	public Boolean CheckObstacleLikeOrInvalid() { }
	// RVA: 0x407e7c8 VA: 0x75966967c8
	public Void AssignHostRouteProgress(Int32 hostCursorIndex) { }
	// RVA: 0x407aaec VA: 0x7596692aec
	public Void .ctor(Route route, SchedulerSnapshot snapshot, Vector2 offset, BObject obj, Boolean ignoreAllButMoveCp, Boolean visitEveryTileCenter, Boolean visitEveryNodeCenter) { }
	// RVA: 0x407e844 VA: 0x7596696844
	public override Void Reset() { }
	// RVA: 0x407b174 VA: 0x7596693174
	public virtual Boolean CheckReached() { }
	// RVA: 0x407e9ec VA: 0x75966969ec
	public virtual Boolean PredictReached(Single stepDistance, out Vector2 direction, out Vector2 nextPos) { }
	// RVA: 0x407f108 VA: 0x7596697108
	public Vector2 GetNextTarget() { }
	// RVA: 0x407ebcc VA: 0x7596696bcc
	private Vector2 _GetNextTarget() { }
	// RVA: 0x407b244 VA: 0x7596693244
	public virtual Vector2 GetNextDirection() { }
	// RVA: 0x407f2fc VA: 0x75966972fc
	public Vector2 GetNextTurn(Vector2 moveDir) { }
	// RVA: 0x407f654 VA: 0x7596697654
	public Vector2 PredictFuturePosition(Single predictDist, Boolean updateCursor, Boolean skipDisappearCheckpoint) { }
	// RVA: 0x407fa58 VA: 0x7596697a58
	public Boolean TryGetDistanceToNextCheckpoint(out Single distance) { }
	// RVA: 0x407fc10 VA: 0x7596697c10
	public Boolean TryGetCheckpointTargetPos(Int32 cursorOffset, out GridPosition targetGrid) { }
	// RVA: 0x407fd80 VA: 0x7596697d80
	public Boolean TryGetNextAppearCheckpoint(out Int32 nextMoveCp, out Vector2 mapPos) { }
	// RVA: 0x407feec VA: 0x7596697eec
	public Boolean TryGetDistanceToMapPosInCheckpointsAhead(GridPosition gridPos, out Single distance) { }
	// RVA: 0x407f920 VA: 0x7596697920
	private Boolean _CheckNextCpShouldNotSkip(Int32 cur_cursor) { }
	// RVA: 0x408017c VA: 0x759669817c
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x4080280 VA: 0x7596698280
	public CheckpointType GetCurCheckpointType() { }
	// RVA: 0x4080340 VA: 0x7596698340
	public Boolean TrySkipIfCurrentCheckpointIsWaitForSeconds(Boolean _useSkipInsteadOfSetToZero) { }
	// RVA: 0x407f17c VA: 0x759669717c
	private GridPosition _GetNextGrid(GridPosition gridPos) { }
	// RVA: 0x407a954 VA: 0x7596692954
	public Vector2 GetLocatorPosition() { }
	// RVA: 0x4080454 VA: 0x7596698454
	public GridPosition GetNextGrid(GridPosition gridPos) { }
	// RVA: 0x40804d4 VA: 0x75966984d4
	private Void <>xLuaBaseProxy_Reset() { }
}
```