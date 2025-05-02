# VFurnitureEditor

**Namespace:** `Torappu.Building.EditorTools`


## Fields

- `BuildingDB _buildingDB`

- `BuildingLocalDataDB _buildingLocalDataDB`

- `Boolean <isLoaded>k__BackingField`

- `ObstacleData m_obstacleData`

- `VGridPlane m_obstaclePlane`


## Properties

- `Boolean isLoaded`

- `String furnitureID`

- `VGridPlane obstaclePlane`


## Methods

- `Boolean get_isLoaded()`

- `Void set_isLoaded(Boolean)`

- `String get_furnitureID()`

- `VGridPlane get_obstaclePlane()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.EditorTools
public class VFurnitureEditor : MonoBehaviour
{
	private BuildingDB _buildingDB; // 0x18
	private BuildingLocalDataDB _buildingLocalDataDB; // 0x20
	private Boolean <isLoaded>k__BackingField; // 0x28
	private ObstacleData m_obstacleData; // 0x30
	private VGridPlane m_obstaclePlane; // 0x38

	public Boolean isLoaded { get; set; }
	private String furnitureID { get; }
	public VGridPlane obstaclePlane { get; }

	// RVA: 0x3d11bfc VA: 0x7596329bfc
	public Boolean get_isLoaded() { }
	// RVA: 0x3d11c04 VA: 0x7596329c04
	private Void set_isLoaded(Boolean value) { }
	// RVA: 0x3d11c10 VA: 0x7596329c10
	private String get_furnitureID() { }
	// RVA: 0x3d11c18 VA: 0x7596329c18
	public VGridPlane get_obstaclePlane() { }
	// RVA: 0x3d11c20 VA: 0x7596329c20
	public Void .ctor() { }
}
```