# BuildingStationSelectSortBar

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `TwoStateToggle _filterNoFilterArrowStatus`

- `TwoStateToggle _filterWithFilterArrowStatus`

- `TwoStateToggle _filterStatus`

- `Text _textFilterType`

- `CanvasGroup _canvasGroupFilterPanel`

- `Boolean m_isInited`

- `CharSortType m_sortType`

- `CharStationFilterType m_filterType`

- `Boolean m_isInverse`

- `Boolean m_isShowStationFilter`

- `FadeSwitchTween m_stationFilterSwitchTween`


## Methods

- `Void _RefreshSort(StationOrderStruct)`

- `Void _RefreshFilter(StationOrderStruct)`

- `Void _InitIfNot()`

- `Void EventOnClickStationFilterBar()`

- `Void _OnSortClicked(CharSortType)`

- `Void _OnFilterItemClicked(CharStationFilterType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectSortBar : DataBinder`1
{
	private const Single STATION_PANEL_FILTER_DURATION_FADE; // 0x0
	private BuildingStationSelectSortItem[] _sortItems; // 0x20
	private BuildingStationSelectStationStatusFilterItem[] _filterItems; // 0x28
	private TwoStateToggle _filterNoFilterArrowStatus; // 0x30
	private TwoStateToggle _filterWithFilterArrowStatus; // 0x38
	private TwoStateToggle _filterStatus; // 0x40
	private Text _textFilterType; // 0x48
	private CanvasGroup _canvasGroupFilterPanel; // 0x50
	public Action`1 onSortClicked; // 0x58
	public Action`1 onFilterShowHideClicked; // 0x60
	public Action`1 onFilterItemClicked; // 0x68
	private Boolean m_isInited; // 0x70
	private CharSortType m_sortType; // 0x74
	private CharStationFilterType m_filterType; // 0x78
	private Boolean m_isInverse; // 0x7c
	private Boolean m_isShowStationFilter; // 0x7d
	private FadeSwitchTween m_stationFilterSwitchTween; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RefreshSort; // 0x8
	private static DelegateBridge __Hotfix0__RefreshFilter; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClickStationFilterBar; // 0x20
	private static DelegateBridge __Hotfix0__OnSortClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnFilterItemClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3da0a28 VA: 0x75963b8a28
	public override Void OnValueChanged(StationCharGroupProperty property) { }
	// RVA: 0x3da0d3c VA: 0x75963b8d3c
	private Void _RefreshSort(StationOrderStruct orderStruct) { }
	// RVA: 0x3da0e58 VA: 0x75963b8e58
	private Void _RefreshFilter(StationOrderStruct orderStruct) { }
	// RVA: 0x3da0b00 VA: 0x75963b8b00
	private Void _InitIfNot() { }
	// RVA: 0x3da102c VA: 0x75963b902c
	public Void EventOnClickStationFilterBar() { }
	// RVA: 0x3da10bc VA: 0x75963b90bc
	private Void _OnSortClicked(CharSortType sortType) { }
	// RVA: 0x3da115c VA: 0x75963b915c
	private Void _OnFilterItemClicked(CharStationFilterType filterType) { }
	// RVA: 0x3da1218 VA: 0x75963b9218
	public Void .ctor() { }
}
```