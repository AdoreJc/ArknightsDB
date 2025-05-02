# StationManageEditQueueViewModel

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Int32 m_curEditPreQueueRoomIndex`

- `Boolean playerDataUpdated`

- `BuildingModel curBuildingModel`

- `RoomSlotModel curEditPreQueueSlotModel`


## Properties

- `Int32 curEditPreQueueRoomIndex`


## Methods

- `Int32 get_curEditPreQueueRoomIndex()`

- `Void InitData(BuildingModel, RoomSlotModel)`

- `Void LoadData(BuildingModel, RoomSlotModel, Boolean)`

- `RoomSlotModel GetCurEditPreQueueRoom()`

- `RoomSlotModel GetNextPreQueueRoom()`

- `RoomSlotModel GetPrefPreQueueRoom()`

- `Int32 _TrySetSlotIndexInPreQueueLayout(String)`

- `Void SetToNextRoom()`

- `Void SetToPrefRoom()`

- `Void _RefreshData(BuildingModel, RoomSlotModel, Boolean)`

- `Boolean _CheckIsRoomCanSetPreQueue(RoomSlotModel)`

- `Void _InternalSetCurEditPreQueueRoomIndexByOffset(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class StationManageEditQueueViewModel
{
	private Int32 m_curEditPreQueueRoomIndex; // 0x10
	public Boolean playerDataUpdated; // 0x14
	public BuildingModel curBuildingModel; // 0x18
	public RoomSlotModel curEditPreQueueSlotModel; // 0x20
	public List`1 preQueueLayout; // 0x28

	public Int32 curEditPreQueueRoomIndex { get; }

	// RVA: 0x3da19c0 VA: 0x75963b99c0
	public Int32 get_curEditPreQueueRoomIndex() { }
	// RVA: 0x3da166c VA: 0x75963b966c
	public Void InitData(BuildingModel buildingModel, RoomSlotModel slotModel) { }
	// RVA: 0x3da18a0 VA: 0x75963b98a0
	public Void LoadData(BuildingModel buildingModel, RoomSlotModel slotModel, Boolean updateByMsg) { }
	// RVA: 0x3da1c8c VA: 0x75963b9c8c
	public RoomSlotModel GetCurEditPreQueueRoom() { }
	// RVA: 0x3da1cdc VA: 0x75963b9cdc
	public RoomSlotModel GetNextPreQueueRoom() { }
	// RVA: 0x3da1dc0 VA: 0x75963b9dc0
	public RoomSlotModel GetPrefPreQueueRoom() { }
	// RVA: 0x3da1ea4 VA: 0x75963b9ea4
	private Int32 _TrySetSlotIndexInPreQueueLayout(String slotId) { }
	// RVA: 0x3da2068 VA: 0x75963ba068
	public Void SetToNextRoom() { }
	// RVA: 0x3da20f4 VA: 0x75963ba0f4
	public Void SetToPrefRoom() { }
	// RVA: 0x3da19c8 VA: 0x75963b99c8
	private Void _RefreshData(BuildingModel buildingModel, RoomSlotModel slotModel, Boolean updateByMsg) { }
	// RVA: 0x3da20fc VA: 0x75963ba0fc
	private Boolean _CheckIsRoomCanSetPreQueue(RoomSlotModel roomSlotModel) { }
	// RVA: 0x3da2070 VA: 0x75963ba070
	private Void _InternalSetCurEditPreQueueRoomIndexByOffset(Int32 offset) { }
	// RVA: 0x3da15dc VA: 0x75963b95dc
	public Void .ctor() { }
}
```