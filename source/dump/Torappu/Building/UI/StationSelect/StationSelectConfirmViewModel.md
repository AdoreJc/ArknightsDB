# StationSelectConfirmViewModel

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `StationConfirmModel stationConfirmModel`


## Methods

- `Void LoadData()`

- `ChangedRoomViewModel _GenCurrentChangedRoom(String, List`1)`

- `ChangedRoomViewModel _GenCurrentChangedAssistant(Int32, Int32)`

- `Void _ProcessChangedRoomsByInstId(Int32)`

- `Void _UpdateChangedRoom(String, Int32)`

- `ChangedRoomViewModel _GenChangedAssistRoom(Int32, Int32)`

- `ChangedRoomViewModel _GenChangedRoom(Int32, RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class StationSelectConfirmViewModel : IHotfixable
{
	public StationConfirmModel stationConfirmModel; // 0x10
	public List`1 changedRoomGroupList; // 0x18
	private List`1 m_tempListForExclusiveInstIds; // 0x20
	private Dictionary`2 m_changedRoomDict; // 0x28
	private Dictionary`2 m_changedAssistDict; // 0x30
	private Dictionary`2 m_changedModelSearchTable; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GenCurrentChangedRoom; // 0x8
	private static DelegateBridge __Hotfix0__GenCurrentChangedAssistant; // 0x10
	private static DelegateBridge __Hotfix0__ProcessChangedRoomsByInstId; // 0x18
	private static DelegateBridge __Hotfix0__UpdateChangedRoom; // 0x20
	private static DelegateBridge __Hotfix0__GenChangedAssistRoom; // 0x28
	private static DelegateBridge __Hotfix0__GenChangedRoom; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3d8f034 VA: 0x75963a7034
	public Void LoadData() { }
	// RVA: 0x3d9100c VA: 0x75963a900c
	private ChangedRoomViewModel _GenCurrentChangedRoom(String slotId, List`1 instIds) { }
	// RVA: 0x3d90664 VA: 0x75963a8664
	private ChangedRoomViewModel _GenCurrentChangedAssistant(Int32 assistIdx, Int32 instId) { }
	// RVA: 0x3d911f4 VA: 0x75963a91f4
	private Void _ProcessChangedRoomsByInstId(Int32 originInstId) { }
	// RVA: 0x3d91bb4 VA: 0x75963a9bb4
	private Void _UpdateChangedRoom(String slotId, Int32 exInstId) { }
	// RVA: 0x3d90b48 VA: 0x75963a8b48
	private ChangedRoomViewModel _GenChangedAssistRoom(Int32 assistIdx, Int32 instId) { }
	// RVA: 0x3d90824 VA: 0x75963a8824
	private ChangedRoomViewModel _GenChangedRoom(Int32 exInstId, RoomSlotModel roomSlot) { }
	// RVA: 0x3d91d44 VA: 0x75963a9d44
	public Void .ctor() { }
}
```