# TracePositionCursor

**Namespace:** `Torappu.Battle`


## Fields

- `Vector2 m_reachedOffset`

- `Boolean m_isMarkReached`


## Properties

- `Boolean isMarkReached`

- `Boolean isCurrentValid`


## Methods

- `Boolean get_isMarkReached()`

- `Boolean get_isCurrentValid()`

- `Boolean CheckReached(Single)`

- `Void MarkReached()`

- `Void ResetReachedOffset(Vector2, Boolean)`

- `Boolean <>xLuaBaseProxy_PredictReached(Single, out, out)`

- `Vector2 <>xLuaBaseProxy_GetNextDirection()`

- `Boolean <>xLuaBaseProxy_CheckReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TracePositionCursor : DirectionCursor
{
	private Vector2 m_reachedOffset; // 0x7c
	private Boolean m_isMarkReached; // 0x84
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_isMarkReached; // 0x8
	private static DelegateBridge __Hotfix0_get_isCurrentValid; // 0x10
	private static DelegateBridge __Hotfix0_PredictReached; // 0x18
	private static DelegateBridge __Hotfix0_GetNextDirection; // 0x20
	private static DelegateBridge __Hotfix0_CheckReached; // 0x28
	private static DelegateBridge __Hotfix1_CheckReached; // 0x30
	private static DelegateBridge __Hotfix0_MarkReached; // 0x38
	private static DelegateBridge __Hotfix0_ResetReachedOffset; // 0x40

	public Boolean isMarkReached { get; }
	public Boolean isCurrentValid { get; }

	// RVA: 0x40807c0 VA: 0x75966987c0
	public Void .ctor(Route route, SchedulerSnapshot snapshot, Vector2 offset, BObject obj, Boolean ignoreAllButMoveCp, Boolean visitEveryTileCenter, Boolean visitEveryNodeCenter) { }
	// RVA: 0x40809fc VA: 0x75966989fc
	public Boolean get_isMarkReached() { }
	// RVA: 0x4080a64 VA: 0x7596698a64
	public Boolean get_isCurrentValid() { }
	// RVA: 0x4080b6c VA: 0x7596698b6c
	public override Boolean PredictReached(Single stepDistance, out Vector2 direction, out Vector2 nextPos) { }
	// RVA: 0x4080ddc VA: 0x7596698ddc
	public override Vector2 GetNextDirection() { }
	// RVA: 0x4080ffc VA: 0x7596698ffc
	public override Boolean CheckReached() { }
	// RVA: 0x408106c VA: 0x759669906c
	public Boolean CheckReached(Single dist) { }
	// RVA: 0x4081120 VA: 0x7596699120
	public Void MarkReached() { }
	// RVA: 0x408090c VA: 0x759669890c
	public Void ResetReachedOffset(Vector2 offset, Boolean randomize) { }
	// RVA: 0x408118c VA: 0x759669918c
	private Boolean <>xLuaBaseProxy_PredictReached(Single P0, out Vector2 P1, out Vector2 P2) { }
	// RVA: 0x4081190 VA: 0x7596699190
	private Vector2 <>xLuaBaseProxy_GetNextDirection() { }
	// RVA: 0x4081194 VA: 0x7596699194
	private Boolean <>xLuaBaseProxy_CheckReached() { }
}
```