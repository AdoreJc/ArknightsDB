# BuildingLocalDataDB

**Namespace:** `Torappu.Building`


## Methods

- `ObstacleData GetObstacleDataOrDefault(String)`

- `ObstacleData GetFurnirtureObstacleDataOrDefault(String)`

- `Boolean SaveBackToFile()`

- `String SerializeLocalData(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingLocalDataDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_get_obstacleTemplates; // 0x0
	private static DelegateBridge __Hotfix0_get_furnitureObstacleData; // 0x8
	private static DelegateBridge __Hotfix0_GetObstacleDataOrDefault; // 0x10
	private static DelegateBridge __Hotfix0_GetFurnitureLODShowedNames; // 0x18
	private static DelegateBridge __Hotfix0_GetFurnirtureObstacleDataOrDefault; // 0x20
	private static DelegateBridge __Hotfix0_SaveBackToFile; // 0x28
	private static DelegateBridge __Hotfix0_SerializeLocalData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Dictionary`2 obstacleTemplates { get; }
	public Dictionary`2 furnitureObstacleData { get; }

	// RVA: 0x37b218c VA: 0x7595dca18c
	public Dictionary`2 get_obstacleTemplates() { }
	// RVA: 0x37b2218 VA: 0x7595dca218
	public Dictionary`2 get_furnitureObstacleData() { }
	// RVA: 0x37b22a4 VA: 0x7595dca2a4
	public ObstacleData GetObstacleDataOrDefault(String obstableId) { }
	// RVA: 0x37b2380 VA: 0x7595dca380
	public List`1 GetFurnitureLODShowedNames(String furnitureId, LODLEVEL lodLevel) { }
	// RVA: 0x37b24b4 VA: 0x7595dca4b4
	public ObstacleData GetFurnirtureObstacleDataOrDefault(String furnitureId) { }
	// RVA: 0x37b25a4 VA: 0x7595dca5a4
	public Boolean SaveBackToFile() { }
	// RVA: 0x37b260c VA: 0x7595dca60c
	public String SerializeLocalData(Boolean idented) { }
	// RVA: 0x37b26a4 VA: 0x7595dca6a4
	public Void .ctor() { }
}
```