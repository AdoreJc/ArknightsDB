# GiantTrap

**Namespace:** `Torappu.Battle`


## Fields

- `Vector2 _locateRangeOffset`

- `Single _minBlockDistToTarget`


## Methods

- `Single <>xLuaBaseProxy_get_blockRadiusSquare()`

- `Single <>xLuaBaseProxy_get_minBlockDistToTarget()`

- `Vector2 <>xLuaBaseProxy_get_hudOffset()`

- `Void <>xLuaBaseProxy_LocateOnTile(Tile)`

- `Boolean <>xLuaBaseProxy_CheckInBlockRange(Entity, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GiantTrap : BossHudTrap
{
	private Vector2 _locateRangeOffset; // 0x538
	private Single _minBlockDistToTarget; // 0x540
	private List`1 m_locatePositions; // 0x548
	private static DelegateBridge __Hotfix0_get_blockRadiusSquare; // 0x0
	private static DelegateBridge __Hotfix0_get_minBlockDistToTarget; // 0x8
	private static DelegateBridge __Hotfix0_get_hudOffset; // 0x10
	private static DelegateBridge __Hotfix0_LocateOnTile; // 0x18
	private static DelegateBridge __Hotfix0_CheckInBlockRange; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Single blockRadiusSquare { get; }
	public override Single minBlockDistToTarget { get; }
	public override Vector2 hudOffset { get; }

	// RVA: 0x1c21500 VA: 0x7594239500
	public override Single get_blockRadiusSquare() { }
	// RVA: 0x1c2156c VA: 0x759423956c
	public override Single get_minBlockDistToTarget() { }
	// RVA: 0x1c215d4 VA: 0x75942395d4
	public override Vector2 get_hudOffset() { }
	// RVA: 0x1c21640 VA: 0x7594239640
	public override Void LocateOnTile(Tile tile) { }
	// RVA: 0x1c21b10 VA: 0x7594239b10
	public override Boolean CheckInBlockRange(Entity target, Single shrink) { }
	// RVA: 0x1c21d2c VA: 0x7594239d2c
	public Void .ctor() { }
	// RVA: 0x1c21e30 VA: 0x7594239e30
	private Single <>xLuaBaseProxy_get_blockRadiusSquare() { }
	// RVA: 0x1c21e9c VA: 0x7594239e9c
	private Single <>xLuaBaseProxy_get_minBlockDistToTarget() { }
	// RVA: 0x1c21ea4 VA: 0x7594239ea4
	private Vector2 <>xLuaBaseProxy_get_hudOffset() { }
	// RVA: 0x1c21f3c VA: 0x7594239f3c
	private Void <>xLuaBaseProxy_LocateOnTile(Tile P0) { }
	// RVA: 0x1c21f44 VA: 0x7594239f44
	private Boolean <>xLuaBaseProxy_CheckInBlockRange(Entity P0, Single P1) { }
}
```