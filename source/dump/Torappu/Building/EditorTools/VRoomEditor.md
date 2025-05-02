# VRoomEditor

**Namespace:** `Torappu.Building.EditorTools`


## Fields

- `BuildingDB _buildingDB`

- `BuildingLocalDataDB _buildingLocalDataDB`

- `String _prefabId`

- `String _obstacleId`

- `RoomType _roomId`

- `Boolean <isLoaded>k__BackingField`

- `VRoom <room>k__BackingField`

- `PrefabInfo m_prefabInfo`

- `ObstacleData m_obstacleData`


## Properties

- `Boolean isLoaded`

- `VGridPlane floorPlane`

- `VGridPlane backwallPlane`

- `VRoom room`

- `VRoomGraphic graphic`


## Methods

- `Boolean get_isLoaded()`

- `Void set_isLoaded(Boolean)`

- `VGridPlane get_floorPlane()`

- `VGridPlane get_backwallPlane()`

- `VRoom get_room()`

- `Void set_room(VRoom)`

- `VRoomGraphic get_graphic()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.EditorTools
public class VRoomEditor : MonoBehaviour
{
	private BuildingDB _buildingDB; // 0x18
	private BuildingLocalDataDB _buildingLocalDataDB; // 0x20
	private String _prefabId; // 0x28
	private String _obstacleId; // 0x30
	private RoomType _roomId; // 0x38
	private Boolean <isLoaded>k__BackingField; // 0x3c
	private VRoom <room>k__BackingField; // 0x40
	private PrefabInfo m_prefabInfo; // 0x48
	private ObstacleData m_obstacleData; // 0x50

	public Boolean isLoaded { get; set; }
	public VGridPlane floorPlane { get; }
	public VGridPlane backwallPlane { get; }
	protected VRoom room { get; set; }
	protected VRoomGraphic graphic { get; }

	// RVA: 0x3d11c28 VA: 0x7596329c28
	public Boolean get_isLoaded() { }
	// RVA: 0x3d11c30 VA: 0x7596329c30
	private Void set_isLoaded(Boolean value) { }
	// RVA: 0x3d11c3c VA: 0x7596329c3c
	public VGridPlane get_floorPlane() { }
	// RVA: 0x3d11c58 VA: 0x7596329c58
	public VGridPlane get_backwallPlane() { }
	// RVA: 0x3d11c74 VA: 0x7596329c74
	protected VRoom get_room() { }
	// RVA: 0x3d11c7c VA: 0x7596329c7c
	private Void set_room(VRoom value) { }
	// RVA: 0x3d11c84 VA: 0x7596329c84
	protected VRoomGraphic get_graphic() { }
	// RVA: 0x3d11ca0 VA: 0x7596329ca0
	public Void .ctor() { }
}
```