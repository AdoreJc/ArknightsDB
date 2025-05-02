# StationBPViewModel

**Namespace:** `Torappu.Building.UI`


## Fields

- `String m_selectedSlotId`

- `Int32 totalStationNum`

- `Int32 totalStationNumLimit`

- `GridPosition totalSize`


## Properties

- `String selectedSlotId`


## Methods

- `String get_selectedSlotId()`

- `Void set_selectedSlotId(String)`

- `Void LoadData(BuildingModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class StationBPViewModel
{
	private String m_selectedSlotId; // 0x10
	public Int32 totalStationNum; // 0x18
	public Int32 totalStationNumLimit; // 0x1c
	public GridPosition totalSize; // 0x20
	public ListDict`2 slots; // 0x28

	public String selectedSlotId { get; set; }

	// RVA: 0x3d366c0 VA: 0x759634e6c0
	public String get_selectedSlotId() { }
	// RVA: 0x3d366c8 VA: 0x759634e6c8
	public Void set_selectedSlotId(String value) { }
	// RVA: 0x3d368e8 VA: 0x759634e8e8
	public Void LoadData(BuildingModel buildingModel) { }
	// RVA: 0x3d36bf0 VA: 0x759634ebf0
	public Void .ctor() { }
}
```