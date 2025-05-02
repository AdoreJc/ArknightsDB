# StationManageWorkViewModel

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Boolean canBatchWork`

- `Int32 totalRoomCnt`

- `Int32 stoppedRoomCnt`

- `Int32 canPresetEmptyRoomCnt`

- `Int32 canPresetTiredCharCnt`

- `Int32 cannotPresetTiredCharCnt`

- `Int32 stationLimit`

- `Int32 stationCharCnt`

- `String animSlotId`

- `SelectedRoomDetailViewModel selectedRoomDetailModel`


## Methods

- `Void InitData(BuildingModel)`

- `Void LoadData(BuildingModel)`

- `Void LoadSelectedRoomDetail(BuildingModel, RoomSlotModel)`

- `Void UpdateSelectedSlotId(String)`

- `Void _LoadRoomGroupData(BuildingModel)`

- `Void _LoadBatchWorkData()`

- `Void _LoadRoomNumData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class StationManageWorkViewModel
{
	public Boolean canBatchWork; // 0x10
	public Int32 totalRoomCnt; // 0x14
	public Int32 stoppedRoomCnt; // 0x18
	public Int32 canPresetEmptyRoomCnt; // 0x1c
	public Int32 canPresetTiredCharCnt; // 0x20
	public Int32 cannotPresetTiredCharCnt; // 0x24
	public Int32 stationLimit; // 0x28
	public Int32 stationCharCnt; // 0x2c
	public String animSlotId; // 0x30
	public SelectedRoomDetailViewModel selectedRoomDetailModel; // 0x38
	public List`1 workRoomGroups; // 0x40


	// RVA: 0x3da4b84 VA: 0x75963bcb84
	public Void InitData(BuildingModel model) { }
	// RVA: 0x3da549c VA: 0x75963bd49c
	public Void LoadData(BuildingModel model) { }
	// RVA: 0x3da62a4 VA: 0x75963be2a4
	public Void LoadSelectedRoomDetail(BuildingModel buildingModel, RoomSlotModel slotModel) { }
	// RVA: 0x3da5d8c VA: 0x75963bdd8c
	public Void UpdateSelectedSlotId(String slotId) { }
	// RVA: 0x3da6678 VA: 0x75963be678
	private Void _LoadRoomGroupData(BuildingModel model) { }
	// RVA: 0x3da6ac0 VA: 0x75963beac0
	private Void _LoadBatchWorkData() { }
	// RVA: 0x3da6df8 VA: 0x75963bedf8
	private Void _LoadRoomNumData() { }
	// RVA: 0x3da49e8 VA: 0x75963bc9e8
	public Void .ctor() { }
}
```