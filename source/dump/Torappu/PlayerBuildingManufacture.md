# PlayerBuildingManufacture

**Namespace:** `Torappu`


## Fields

- `PlayerBuildingManufactureBuff buff`

- `PlayerRoomState state`

- `String formulaId`

- `Int32 remainSolutionCnt`

- `Int32 outputSolutionCnt`

- `DateTime lastUpdateTime`

- `Double processPoint`

- `Int64 saveTime`

- `DateTime completeWorkTime`

- `Int32 capacity`

- `Int32 apCost`

- `BuildingBuffDisplay display`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerBuildingManufacture
{
	public PlayerBuildingManufactureBuff buff; // 0x10
	public PlayerRoomState state; // 0x18
	public String formulaId; // 0x20
	public Int32 remainSolutionCnt; // 0x28
	public Int32 outputSolutionCnt; // 0x2c
	public DateTime lastUpdateTime; // 0x30
	public Double processPoint; // 0x38
	public Int64 saveTime; // 0x40
	public DateTime completeWorkTime; // 0x48
	public Int32 capacity; // 0x50
	public Int32 apCost; // 0x54
	public BuildingBuffDisplay display; // 0x58
	public List`1 presetQueue; // 0x60


	// RVA: 0x32d6ab8 VA: 0x75958eeab8
	public Void .ctor() { }
}
```