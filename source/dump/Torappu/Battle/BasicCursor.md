# BasicCursor

**Namespace:** `Torappu.Battle`


## Fields

- `Route m_route`

- `Int32 m_cursor`

- `Vector2 m_cachedDirection`

- `BObject m_obj`

- `Boolean <ignoreAllButMoveCp>k__BackingField`

- `Boolean <visitEveryTileCenter>k__BackingField`

- `Boolean <visitEveryNodeCenter>k__BackingField`

- `SchedulerSnapshot <snapshot>k__BackingField`

- `Boolean <visitEveryNodeStably>k__BackingField`


## Properties

- `Boolean ignoreAllButMoveCp`

- `Boolean visitEveryTileCenter`

- `Boolean visitEveryNodeCenter`

- `MotionMode motionMode`

- `Route route`

- `SchedulerSnapshot snapshot`

- `Random random`

- `Boolean visitEveryNodeStably`


## Methods

- `Boolean get_ignoreAllButMoveCp()`

- `Void set_ignoreAllButMoveCp(Boolean)`

- `Boolean get_visitEveryTileCenter()`

- `Void set_visitEveryTileCenter(Boolean)`

- `Boolean get_visitEveryNodeCenter()`

- `Void set_visitEveryNodeCenter(Boolean)`

- `MotionMode get_motionMode()`

- `Route get_route()`

- `SchedulerSnapshot get_snapshot()`

- `Void set_snapshot(SchedulerSnapshot)`

- `Random get_random()`

- `Boolean get_visitEveryNodeStably()`

- `Void set_visitEveryNodeStably(Boolean)`

- `Void OnRouteChanged(Route)`

- `Void SkipNextCheckPoint(Boolean)`

- `Void _MoveNext()`

- `Checkpoint _CreateCheckpoint(CheckpointData, Node[, ])`

- `Void IgnoreAllButMoveCp(Boolean)`

- `Void SkipCheckPoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BasicCursor : IHotfixable
{
	protected Route m_route; // 0x10
	protected Int32 m_cursor; // 0x18
	protected Vector2 m_cachedDirection; // 0x1c
	protected Checkpoint[] m_checkpoints; // 0x28
	protected BObject m_obj; // 0x30
	private Boolean <ignoreAllButMoveCp>k__BackingField; // 0x38
	private Boolean <visitEveryTileCenter>k__BackingField; // 0x39
	private Boolean <visitEveryNodeCenter>k__BackingField; // 0x3a
	private SchedulerSnapshot <snapshot>k__BackingField; // 0x40
	private Boolean <visitEveryNodeStably>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_ignoreAllButMoveCp; // 0x0
	private static DelegateBridge __Hotfix0_set_ignoreAllButMoveCp; // 0x8
	private static DelegateBridge __Hotfix0_get_visitEveryTileCenter; // 0x10
	private static DelegateBridge __Hotfix0_set_visitEveryTileCenter; // 0x18
	private static DelegateBridge __Hotfix0_get_visitEveryNodeCenter; // 0x20
	private static DelegateBridge __Hotfix0_set_visitEveryNodeCenter; // 0x28
	private static DelegateBridge __Hotfix0_get_motionMode; // 0x30
	private static DelegateBridge __Hotfix0_get_route; // 0x38
	private static DelegateBridge __Hotfix0_get_snapshot; // 0x40
	private static DelegateBridge __Hotfix0_set_snapshot; // 0x48
	private static DelegateBridge __Hotfix0_get_random; // 0x50
	private static DelegateBridge __Hotfix0_get_visitEveryNodeStably; // 0x58
	private static DelegateBridge __Hotfix0_set_visitEveryNodeStably; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68
	private static DelegateBridge __Hotfix0_OnRouteChanged; // 0x70
	private static DelegateBridge __Hotfix0_Reset; // 0x78
	private static DelegateBridge __Hotfix0_GetContDirectionAfterEnd; // 0x80
	private static DelegateBridge __Hotfix0_SkipNextCheckPoint; // 0x88
	private static DelegateBridge __Hotfix0__MoveNext; // 0x90
	private static DelegateBridge __Hotfix0__CreateCheckpoint; // 0x98
	private static DelegateBridge __Hotfix0_IgnoreAllButMoveCp; // 0xa0
	private static DelegateBridge __Hotfix0_SkipCheckPoint; // 0xa8

	public Boolean ignoreAllButMoveCp { get; set; }
	public Boolean visitEveryTileCenter { get; set; }
	public Boolean visitEveryNodeCenter { get; set; }
	public MotionMode motionMode { get; }
	public Route route { get; }
	public SchedulerSnapshot snapshot { get; set; }
	public Random random { get; }
	protected Boolean visitEveryNodeStably { get; set; }

	// RVA: 0x407b868 VA: 0x7596693868
	public Boolean get_ignoreAllButMoveCp() { }
	// RVA: 0x407b8d0 VA: 0x75966938d0
	private Void set_ignoreAllButMoveCp(Boolean value) { }
	// RVA: 0x407b950 VA: 0x7596693950
	public Boolean get_visitEveryTileCenter() { }
	// RVA: 0x407b9b8 VA: 0x75966939b8
	private Void set_visitEveryTileCenter(Boolean value) { }
	// RVA: 0x407ba38 VA: 0x7596693a38
	public Boolean get_visitEveryNodeCenter() { }
	// RVA: 0x407baa0 VA: 0x7596693aa0
	private Void set_visitEveryNodeCenter(Boolean value) { }
	// RVA: 0x407bb20 VA: 0x7596693b20
	public MotionMode get_motionMode() { }
	// RVA: 0x407a63c VA: 0x759669263c
	public Route get_route() { }
	// RVA: 0x407bb94 VA: 0x7596693b94
	public SchedulerSnapshot get_snapshot() { }
	// RVA: 0x407bc24 VA: 0x7596693c24
	private Void set_snapshot(SchedulerSnapshot value) { }
	// RVA: 0x407bcbc VA: 0x7596693cbc
	public Random get_random() { }
	// RVA: 0x407bd38 VA: 0x7596693d38
	protected Boolean get_visitEveryNodeStably() { }
	// RVA: 0x407bda0 VA: 0x7596693da0
	private Void set_visitEveryNodeStably(Boolean value) { }
	// RVA: 0x407be20 VA: 0x7596693e20
	protected Void .ctor(Route route, SchedulerSnapshot snapshot, BObject obj, Boolean ignoreAllButMoveCp, Boolean visitEveryTileCenter, Boolean visitEveryNodeCenter) { }
	// RVA: 0x407c438 VA: 0x7596694438
	public Void OnRouteChanged(Route route) { }
	// RVA: 0x407c68c VA: 0x759669468c
	public virtual Void Reset() { }
	// RVA: 0x407b0f8 VA: 0x75966930f8
	public virtual Vector2 GetContDirectionAfterEnd() { }
	// RVA: 0x407c924 VA: 0x7596694924
	public Void SkipNextCheckPoint(Boolean skipWait) { }
	// RVA: 0x407c734 VA: 0x7596694734
	protected Void _MoveNext() { }
	// RVA: 0x407c11c VA: 0x759669411c
	private Checkpoint _CreateCheckpoint(CheckpointData data, Node[,] nextMap) { }
	// RVA: 0x407cba8 VA: 0x7596694ba8
	public Void IgnoreAllButMoveCp(Boolean value) { }
	// RVA: 0x407ccc8 VA: 0x7596694cc8
	public Void SkipCheckPoint() { }
}
```