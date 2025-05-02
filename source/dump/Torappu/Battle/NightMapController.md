# NightMapController

**Namespace:** `Torappu.Battle`


## Methods

- `Void RewriteTileOptions(Tile, AdvancedBuildableMask)`

- `Void _UpdateBrightTiles(Tile)`

- `MapTags <>xLuaBaseProxy_get_tag()`

- `Void <>xLuaBaseProxy_Init(Map)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class NightMapController : MapController
{
	private ListDict`2 m_buildableMarkTilesDict; // 0x18
	private static readonly String BRIGHT_TILE_KEYWORD; // 0x0
	private static DelegateBridge __Hotfix0_get_tag; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_RewriteTileOptions; // 0x18
	private static DelegateBridge __Hotfix0__UpdateBrightTiles; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override MapTags tag { get; }

	// RVA: 0x4011920 VA: 0x7596629920
	public override MapTags get_tag() { }
	// RVA: 0x4011998 VA: 0x7596629998
	public override Void Init(Map battleMap) { }
	// RVA: 0x4011b3c VA: 0x7596629b3c
	public Void RewriteTileOptions(Tile tile, AdvancedBuildableMask mask) { }
	// RVA: 0x4011cf0 VA: 0x7596629cf0
	private Void _UpdateBrightTiles(Tile tile) { }
	// RVA: 0x4011e74 VA: 0x7596629e74
	public override Void Reset() { }
	// RVA: 0x4011f34 VA: 0x7596629f34
	public Void .ctor() { }
	// RVA: 0x4012004 VA: 0x759662a004
	private static Void .cctor() { }
	// RVA: 0x4012070 VA: 0x759662a070
	private MapTags <>xLuaBaseProxy_get_tag() { }
	// RVA: 0x4012074 VA: 0x759662a074
	private Void <>xLuaBaseProxy_Init(Map P0) { }
	// RVA: 0x4012078 VA: 0x759662a078
	private Void <>xLuaBaseProxy_Reset() { }
}
```