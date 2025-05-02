# TileData

**Namespace:** `Torappu`


## Fields

- `String tileKey`

- `HeightType heightType`

- `BuildableType buildableType`

- `MotionMask passableMask`

- `PlayerSideMask playerSideMask`

- `AdvancedBuildableMask advancedBuildableMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TileData
{
	public String tileKey; // 0x10
	public HeightType heightType; // 0x18
	public BuildableType buildableType; // 0x1c
	public MotionMask passableMask; // 0x20
	public PlayerSideMask playerSideMask; // 0x24
	public AdvancedBuildableMask advancedBuildableMask; // 0x28
	public List`1 blackboard; // 0x30
	public MapEffectData[] effects; // 0x38


	// RVA: 0x34a4d5c VA: 0x7595abcd5c
	public Void .ctor() { }
}
```