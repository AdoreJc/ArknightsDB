# DirectionTile

**Namespace:** `Torappu.Battle`


## Fields

- `Direction m_tileDirection`


## Properties

- `Direction tileDirection`


## Methods

- `Direction get_tileDirection()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DirectionTile : Tile
{
	private Direction m_tileDirection; // 0x10c
	private const String DEFAULT_DIRECTION; // 0x0
	private static DelegateBridge __Hotfix0_get_tileDirection; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Direction tileDirection { get; }

	// RVA: 0x408cc9c VA: 0x75966a4c9c
	public Direction get_tileDirection() { }
	// RVA: 0x408cd04 VA: 0x75966a4d04
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x408ce00 VA: 0x75966a4e00
	public Void .ctor() { }
	// RVA: 0x408ce74 VA: 0x75966a4e74
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
}
```