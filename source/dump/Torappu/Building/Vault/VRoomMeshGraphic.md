# VRoomMeshGraphic

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Single _roomDepth`

- `Single _floorOffset`

- `Rect _floorValidRegion`

- `Vector3 _walkThicknessScale`

- `Boolean _autoScaleMesh`

- `Vector3 _builtInSize`

- `Transform _leftDoorPlaceholder`

- `Transform _rightDoorPlaceholder`

- `Animator _animator`

- `String _doorId`


## Methods

- `Void _ResizeMeshToMatchSize()`

- `Transform _GetDoorPlaceholder(LeftOrRight)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VRoomMeshGraphic : VRoomGraphic
{
	private const String NAME_LDOOR; // 0x0
	private const String NAME_RDOOR; // 0x0
	private const String DEFAULT_DOOR_ID; // 0x0
	public Single _roomDepth; // 0x24
	public Single _floorOffset; // 0x28
	public Rect _floorValidRegion; // 0x2c
	public Vector3 _walkThicknessScale; // 0x3c
	public Boolean _autoScaleMesh; // 0x48
	public Vector3 _builtInSize; // 0x4c
	public Transform _leftDoorPlaceholder; // 0x58
	public Transform _rightDoorPlaceholder; // 0x60
	private Animator _animator; // 0x68
	private String _doorId; // 0x70

	public override Animator animator { get; }
	protected override Single floorAltitude { get; }
	protected override Single roomDepth { get; }
	protected override Vector3 wallThickness { get; }
	protected override String doorId { get; }

	// RVA: 0x3859018 VA: 0x7595e71018
	public override Animator get_animator() { }
	// RVA: 0x3859020 VA: 0x7595e71020
	protected override Single get_floorAltitude() { }
	// RVA: 0x3859044 VA: 0x7595e71044
	protected override Single get_roomDepth() { }
	// RVA: 0x385904c VA: 0x7595e7104c
	protected override Vector3 get_wallThickness() { }
	// RVA: 0x3859120 VA: 0x7595e71120
	protected override String get_doorId() { }
	// RVA: 0x3859128 VA: 0x7595e71128
	public override Void UpdateDoor(Boolean hasDoor, LeftOrRight side, ref VDoor door) { }
	// RVA: 0x38592f0 VA: 0x7595e712f0
	protected override Void OnInit(Options options) { }
	// RVA: 0x3859488 VA: 0x7595e71488
	protected override Boolean FetchDoorPos(Boolean hasDoor, LeftOrRight side, out Vector3 worldPos) { }
	// RVA: 0x38595a4 VA: 0x7595e715a4
	protected override Void LocateDoor(VDoor door, Vector3 worldPos, LeftOrRight side) { }
	// RVA: 0x3859698 VA: 0x7595e71698
	protected override Rect GetFloorBoundary() { }
	// RVA: 0x38592f4 VA: 0x7595e712f4
	private Void _ResizeMeshToMatchSize() { }
	// RVA: 0x3859208 VA: 0x7595e71208
	private Transform _GetDoorPlaceholder(LeftOrRight side) { }
	// RVA: 0x385980c VA: 0x7595e7180c
	public Void .ctor() { }
}
```