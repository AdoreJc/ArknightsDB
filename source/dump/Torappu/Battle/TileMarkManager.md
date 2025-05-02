# TileMarkManager

**Namespace:** `Torappu.Battle`


## Methods

- `Void MarkTile(GridPosition, Int32)`

- `Void MarkTileWithTime(GridPosition, Int32, FP)`

- `Void _EmitStatusIfNeed()`

- `Void _TickTiles(FP)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TileMarkManager : EnvManager
{
	private List`1 _markSettings; // 0x28
	private Dictionary`2 m_tileStatus; // 0x30
	private Dictionary`2 m_tileStatusOld; // 0x38
	private HashSet`1 m_changedPositions; // 0x40
	private List`1 m_tileTickTimeList; // 0x48
	private static DelegateBridge __Hotfix0_MarkTile; // 0x0
	private static DelegateBridge __Hotfix0_MarkTileWithTime; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__EmitStatusIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__TickTiles; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x40680c8 VA: 0x75966800c8
	public Void MarkTile(GridPosition pos, Int32 value) { }
	// RVA: 0x4068240 VA: 0x7596680240
	public Void MarkTileWithTime(GridPosition pos, Int32 value, FP time) { }
	// RVA: 0x4068454 VA: 0x7596680454
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40687d4 VA: 0x75966807d4
	private Void _EmitStatusIfNeed() { }
	// RVA: 0x4068540 VA: 0x7596680540
	private Void _TickTiles(FP deltaTime) { }
	// RVA: 0x4068d30 VA: 0x7596680d30
	public Void .ctor() { }
	// RVA: 0x4068f18 VA: 0x7596680f18
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```