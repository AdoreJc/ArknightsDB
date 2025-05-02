# StationSelectStateBean

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `Input stateInput`

- `StationCharGroupProperty charGroupProperty`

- `StationSelectRoomStatusModelProperty roomStatusProperty`

- `RoomType m_lastRoomType`

- `IPlugin <statePlugin>k__BackingField`


## Properties

- `Boolean professionFilterPanelShow`

- `Boolean stationStatusFilterPanelShow`

- `Boolean isSingleMode`

- `RoomType lastRoomType`

- `IPlugin statePlugin`


## Methods

- `Boolean get_professionFilterPanelShow()`

- `Void set_professionFilterPanelShow(Boolean)`

- `Boolean get_stationStatusFilterPanelShow()`

- `Void set_stationStatusFilterPanelShow(Boolean)`

- `Boolean get_isSingleMode()`

- `RoomType get_lastRoomType()`

- `SelectResultModel GenerateSelectedCharsForRequest()`

- `Void LoadData()`

- `Void ToggleSelectedChar(StationCharViewModel)`

- `Void ClearSelectedChars()`

- `Void ToggleSortType(CharSortType)`

- `Void ToggleStationFilterType(CharStationFilterType)`

- `IPlugin get_statePlugin()`

- `Void set_statePlugin(IPlugin)`

- `IPlugin _GenerateStatePlugin(Input)`

- `Void ChangeFilter(CharacterFilterViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class StationSelectStateBean : IStateBean, IHotfixable
{
	public Input stateInput; // 0x10
	public StationCharGroupProperty charGroupProperty; // 0x48
	public StationSelectRoomStatusModelProperty roomStatusProperty; // 0x50
	private RoomType m_lastRoomType; // 0x58
	private List`1 m_tempListForExclusiveInstIds; // 0x60
	private IPlugin <statePlugin>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_ParseInputFromPageParam; // 0x0
	private static DelegateBridge __Hotfix0_get_professionFilterPanelShow; // 0x8
	private static DelegateBridge __Hotfix0_set_professionFilterPanelShow; // 0x10
	private static DelegateBridge __Hotfix0_get_stationStatusFilterPanelShow; // 0x18
	private static DelegateBridge __Hotfix0_set_stationStatusFilterPanelShow; // 0x20
	private static DelegateBridge __Hotfix0_get_isSingleMode; // 0x28
	private static DelegateBridge __Hotfix0_get_lastRoomType; // 0x30
	private static DelegateBridge __Hotfix0_GenerateSelectedCharsForRequest; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_ToggleSelectedChar; // 0x48
	private static DelegateBridge __Hotfix0_ClearSelectedChars; // 0x50
	private static DelegateBridge __Hotfix0_ToggleSortType; // 0x58
	private static DelegateBridge __Hotfix0_ToggleStationFilterType; // 0x60
	private static DelegateBridge __Hotfix0_get_statePlugin; // 0x68
	private static DelegateBridge __Hotfix0_set_statePlugin; // 0x70
	private static DelegateBridge __Hotfix0__GenerateStatePlugin; // 0x78
	private static DelegateBridge __Hotfix0_ChangeFilter; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean professionFilterPanelShow { get; set; }
	public Boolean stationStatusFilterPanelShow { get; set; }
	public Boolean isSingleMode { get; }
	public RoomType lastRoomType { get; }
	public IPlugin statePlugin { get; set; }

	// RVA: 0x3d933c4 VA: 0x75963ab3c4
	public static Input ParseInputFromPageParam(Param pageParam) { }
	// RVA: 0x3d93630 VA: 0x75963ab630
	public Boolean get_professionFilterPanelShow() { }
	// RVA: 0x3d936c8 VA: 0x75963ab6c8
	public Void set_professionFilterPanelShow(Boolean value) { }
	// RVA: 0x3d937a0 VA: 0x75963ab7a0
	public Boolean get_stationStatusFilterPanelShow() { }
	// RVA: 0x3d93838 VA: 0x75963ab838
	public Void set_stationStatusFilterPanelShow(Boolean value) { }
	// RVA: 0x3d93910 VA: 0x75963ab910
	public Boolean get_isSingleMode() { }
	// RVA: 0x3d93980 VA: 0x75963ab980
	public RoomType get_lastRoomType() { }
	// RVA: 0x3d939e8 VA: 0x75963ab9e8
	public SelectResultModel GenerateSelectedCharsForRequest() { }
	// RVA: 0x3d93d0c VA: 0x75963abd0c
	public Void LoadData() { }
	// RVA: 0x3d94614 VA: 0x75963ac614
	public Void ToggleSelectedChar(StationCharViewModel selectedChar) { }
	// RVA: 0x3d949a0 VA: 0x75963ac9a0
	public Void ClearSelectedChars() { }
	// RVA: 0x3d94aa4 VA: 0x75963acaa4
	public Void ToggleSortType(CharSortType sortType) { }
	// RVA: 0x3d94b98 VA: 0x75963acb98
	public Void ToggleStationFilterType(CharStationFilterType stationFilterType) { }
	// RVA: 0x3d94364 VA: 0x75963ac364
	public IPlugin get_statePlugin() { }
	// RVA: 0x3d941fc VA: 0x75963ac1fc
	private Void set_statePlugin(IPlugin value) { }
	// RVA: 0x3d940dc VA: 0x75963ac0dc
	private IPlugin _GenerateStatePlugin(Input input) { }
	// RVA: 0x3d94c68 VA: 0x75963acc68
	public Void ChangeFilter(CharacterFilterViewModel filter) { }
	// RVA: 0x3d94d38 VA: 0x75963acd38
	public Void .ctor() { }
}
```