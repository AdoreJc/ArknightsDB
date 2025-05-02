# StationCharGroupViewModel

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `Boolean isProfessionFilterPanelShow`

- `Boolean isStationFilterPanelShow`

- `CharacterSortType sortType`

- `StationSelectStateBeanInputType selectType`

- `StationOrderStruct m_orderStruct`

- `RoomSlotModel m_selectedRoom`

- `Int32 m_maxSelectCount`

- `StationCharViewModel <focusedChar>k__BackingField`


## Properties

- `StationCharViewModel focusedChar`

- `Int32 maxSelectCount`

- `StationOrderStruct orderStruct`


## Methods

- `Void LoadData(Dictionary`2, RoomSlotModel, List`1, Int32)`

- `StationCharViewModel get_focusedChar()`

- `Void set_focusedChar(StationCharViewModel)`

- `Boolean AddSelectedChar(Int32)`

- `Boolean RemoveSelectedChar(Int32)`

- `Int32 get_maxSelectCount()`

- `StationOrderStruct get_orderStruct()`

- `Void set_orderStruct(StationOrderStruct)`

- `Void NotifyFilterChanged(CharacterFilterViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class StationCharGroupViewModel
{
	public static readonly StationOrderStruct SORT_WORK_DECREASE_ORDER; // 0x0
	public static readonly StationOrderStruct SORT_AP_INCREASE_ORDER; // 0xc
	public Boolean isProfessionFilterPanelShow; // 0x10
	public Boolean isStationFilterPanelShow; // 0x11
	public CharacterSortType sortType; // 0x14
	public StationSelectStateBeanInputType selectType; // 0x18
	public readonly CharacterFilterViewModel professionFilterViewModel; // 0x20
	private ListDict`2 m_selectedChars; // 0x28
	private StationOrderStruct m_orderStruct; // 0x30
	private Dictionary`2 m_rawChars; // 0x40
	private RoomSlotModel m_selectedRoom; // 0x48
	private Int32 m_maxSelectCount; // 0x50
	private StationCharViewModel <focusedChar>k__BackingField; // 0x58
	private List`1 m_cachedList; // 0x60

	public StationCharViewModel focusedChar { get; set; }
	public ListDict`2 selectedChars { get; }
	public Int32 maxSelectCount { get; }
	public Dictionary`2 rawChars { get; }
	public StationOrderStruct orderStruct { get; set; }
	public List`1 restrictedList { get; }

	// RVA: 0x3d943cc VA: 0x75963ac3cc
	public Void LoadData(Dictionary`2 rawChars, RoomSlotModel selectedRoom, List`1 selectedInsts, Int32 maxSelectCount) { }
	// RVA: 0x3d95aa8 VA: 0x75963adaa8
	public StationCharViewModel get_focusedChar() { }
	// RVA: 0x3d95ab0 VA: 0x75963adab0
	public Void set_focusedChar(StationCharViewModel value) { }
	// RVA: 0x3d94874 VA: 0x75963ac874
	public Boolean AddSelectedChar(Int32 instId) { }
	// RVA: 0x3d9481c VA: 0x75963ac81c
	public Boolean RemoveSelectedChar(Int32 instId) { }
	// RVA: 0x3d95ab8 VA: 0x75963adab8
	public ListDict`2 get_selectedChars() { }
	// RVA: 0x3d95ac0 VA: 0x75963adac0
	public Int32 get_maxSelectCount() { }
	// RVA: 0x3d95ac8 VA: 0x75963adac8
	public Dictionary`2 get_rawChars() { }
	// RVA: 0x3d95ad0 VA: 0x75963adad0
	public StationOrderStruct get_orderStruct() { }
	// RVA: 0x3d94280 VA: 0x75963ac280
	public Void set_orderStruct(StationOrderStruct value) { }
	// RVA: 0x3d95ae0 VA: 0x75963adae0
	public List`1 get_restrictedList() { }
	// RVA: 0x3d94334 VA: 0x75963ac334
	public Void NotifyFilterChanged(CharacterFilterViewModel filter) { }
	// RVA: 0x3d95f0c VA: 0x75963adf0c
	public Void .ctor() { }
	// RVA: 0x3d9606c VA: 0x75963ae06c
	private static Void .cctor() { }
}
```