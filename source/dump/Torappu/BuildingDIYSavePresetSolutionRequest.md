# BuildingDIYSavePresetSolutionRequest

**Namespace:** `Torappu`


## Fields

- `Int32 solutionId`

- `String roomType`

- `String name`

- `PlayerBuildingDIYSolution solution`

- `String thumbnail`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingDIYSavePresetSolutionRequest : BuildingRequest
{
	public Int32 solutionId; // 0x10
	public String roomType; // 0x18
	public String name; // 0x20
	public PlayerBuildingDIYSolution solution; // 0x28
	public String thumbnail; // 0x30


	// RVA: 0x32c994c VA: 0x75958e194c
	public Void .ctor() { }
}
```