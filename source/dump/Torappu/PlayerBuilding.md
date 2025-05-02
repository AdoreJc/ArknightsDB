# PlayerBuilding

**Namespace:** `Torappu`


## Fields

- `PlayerBuildingStatus status`

- `PlayerBuildingRoom rooms`

- `PlayerBuildingSolution solution`

- `BuildingMusic music`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerBuilding
{
	public PlayerBuildingStatus status; // 0x10
	public Dictionary`2 chars; // 0x18
	public List`1 assist; // 0x20
	public Dictionary`2 roomSlots; // 0x28
	public PlayerBuildingRoom rooms; // 0x30
	public Dictionary`2 furniture; // 0x38
	public Dictionary`2 diyPresetSolutions; // 0x40
	public PlayerBuildingSolution solution; // 0x48
	public BuildingMusic music; // 0x50


	// RVA: 0x32d7494 VA: 0x75958ef494
	public Void .ctor() { }
}
```