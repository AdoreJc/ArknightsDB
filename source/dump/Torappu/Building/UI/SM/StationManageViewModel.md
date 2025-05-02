# StationManageViewModel

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `ManageMode currMode`

- `StationManageWorkViewModel workViewModel`

- `StationManageRestViewModel restViewModel`

- `StationRoomStructModel selectedRoom`


## Methods

- `Void InitData(BuildingModel)`

- `Void LoadData(BuildingModel)`

- `Void SwitchWorkDormMode()`

- `Void UpdateSelectedSlot(BuildingModel, StationRoomStructModel)`

- `Void UpdateAnimSlot(String)`

- `Void _ClearSelectedRoomInfo()`

- `Void _UpdateSelectedRoomInfo(BuildingModel, RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class StationManageViewModel
{
	public ManageMode currMode; // 0x10
	public StationManageWorkViewModel workViewModel; // 0x18
	public StationManageRestViewModel restViewModel; // 0x20
	public StationRoomStructModel selectedRoom; // 0x28


	// RVA: 0x3da2344 VA: 0x75963ba344
	public Void InitData(BuildingModel model) { }
	// RVA: 0x3da2524 VA: 0x75963ba524
	public Void LoadData(BuildingModel model) { }
	// RVA: 0x3da2bf8 VA: 0x75963babf8
	public Void SwitchWorkDormMode() { }
	// RVA: 0x3da2828 VA: 0x75963ba828
	public Void UpdateSelectedSlot(BuildingModel model, StationRoomStructModel room) { }
	// RVA: 0x3da2968 VA: 0x75963ba968
	public Void UpdateAnimSlot(String slotId) { }
	// RVA: 0x3da54f4 VA: 0x75963bd4f4
	private Void _ClearSelectedRoomInfo() { }
	// RVA: 0x3da5ce4 VA: 0x75963bdce4
	private Void _UpdateSelectedRoomInfo(BuildingModel model, RoomSlotModel slotModel) { }
	// RVA: 0x3da233c VA: 0x75963ba33c
	public Void .ctor() { }
}
```