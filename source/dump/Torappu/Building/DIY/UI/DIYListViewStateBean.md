# DIYListViewStateBean

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFilterGroupProperty _filterProperty`

- `DIYViewListProperty _viewListProperty`

- `DIYMenuProperty _menuProperty`

- `StringProperty _atmosphereProperty`

- `DIYSortMethodViewProperty _sortMethodProperty`

- `UIHandler m_pageHandler`

- `Boolean m_hasFuncCountExceedLimit`


## Properties

- `DIYListViewConfig currConfig`

- `UIHandler pageHandler`

- `DIYViewListThemeState viewListState`

- `Boolean hasFuncCountExceedLimit`


## Methods

- `DIYListViewConfig get_currConfig()`

- `UIHandler get_pageHandler()`

- `DIYViewListThemeState get_viewListState()`

- `Boolean get_hasFuncCountExceedLimit()`

- `Void _Setup(UIHandler)`

- `Void _Reload()`

- `Void _UpdateOverViewData()`

- `Void _UpdateRecentData()`

- `Void _UpdateMenuData()`

- `Void _UpdateViewList()`

- `Void _UpdateFilter(Boolean)`

- `Void _UpdateByConfig()`

- `Void _UpdateAtmosphereText()`

- `Void _UpdateViewCount()`

- `Void _UpdateExpand(UIExpandListState)`

- `Void OnExpand()`

- `Void OnFilterPressed(DIYFilterType)`

- `Void OnSubTypePressed(FurnitureSubType)`

- `Boolean OnViewItemPressed(DIYItemViewData)`

- `Void _UpdateRecentFurnitureData()`

- `Void _ResetConfig()`

- `Void AddConfig(DIYListViewConfig)`

- `Void RemoveConfig()`

- `Void OnSortPanelItemClicked(DiySortType, Int32)`

- `Void _ConsumeTrackPoint(String)`

- `Void ConsumeTrackpointInTheme(String)`

- `Void ConsumeTrackpointInAllThemes()`

- `Void ConsumeTrackPointInAllRecentThemes()`

- `Void ConsumeTrackPointInAllRecentFurnitures()`

- `Void ConsumeAllTrackpoint()`

- `Void ApplyTheme()`

- `Void LoadPreset(Int32, IDIYPreset)`

- `Void _AddDIYItemToRoom(IDIYItem)`

- `Void _SelectSameDIYItem(IDIYItem)`

- `Void _UnequipModifierFromRoom(DIYRoomPart)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYListViewStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private const Int64 RECENT_FURNITURE_TIMESTAMP_THRESHOLD; // 0x0
	private const Int32 RECENT_FURNITURE_MAX_THEME_COUNT; // 0x0
	private const Int32 RECENT_FURNITURE_MAX_SINGLE_COUNT; // 0x0
	private const Int32 RECENT_COUNT_IN_MENU; // 0x0
	private DIYFilterGroupProperty _filterProperty; // 0x18
	private DIYViewListProperty _viewListProperty; // 0x20
	private DIYMenuProperty _menuProperty; // 0x28
	private StringProperty _atmosphereProperty; // 0x30
	private DIYSortMethodViewProperty _sortMethodProperty; // 0x38
	private ListDict`2 m_recentThemes; // 0x40
	private ListDict`2 m_recentFurnitures; // 0x48
	private UIHandler m_pageHandler; // 0x50
	private List`1 m_configStack; // 0x58
	private Boolean m_hasFuncCountExceedLimit; // 0x60
	private static DelegateBridge __Hotfix0_get_currConfig; // 0x0
	private static DelegateBridge __Hotfix0_get_pageHandler; // 0x8
	private static DelegateBridge __Hotfix0_get_viewListState; // 0x10
	private static DelegateBridge __Hotfix0_get_hasFuncCountExceedLimit; // 0x18
	private static DelegateBridge __Hotfix0__Setup; // 0x20
	private static DelegateBridge __Hotfix0__Reload; // 0x28
	private static DelegateBridge __Hotfix0__UpdateOverViewData; // 0x30
	private static DelegateBridge __Hotfix0__UpdateRecentData; // 0x38
	private static DelegateBridge __Hotfix0__UpdateMenuData; // 0x40
	private static DelegateBridge __Hotfix0__UpdateViewList; // 0x48
	private static DelegateBridge __Hotfix0__UpdateFilter; // 0x50
	private static DelegateBridge __Hotfix0__UpdateByConfig; // 0x58
	private static DelegateBridge __Hotfix0__UpdateAtmosphereText; // 0x60
	private static DelegateBridge __Hotfix0__UpdateViewCount; // 0x68
	private static DelegateBridge __Hotfix0__UpdateExpand; // 0x70
	private static DelegateBridge __Hotfix0_OnExpand; // 0x78
	private static DelegateBridge __Hotfix0_OnFilterPressed; // 0x80
	private static DelegateBridge __Hotfix0_OnSubTypePressed; // 0x88
	private static DelegateBridge __Hotfix0_OnViewItemPressed; // 0x90
	private static DelegateBridge __Hotfix0__UpdateRecentFurnitureData; // 0x98
	private static DelegateBridge __Hotfix0__ResetConfig; // 0xa0
	private static DelegateBridge __Hotfix0_AddConfig; // 0xa8
	private static DelegateBridge __Hotfix0_RemoveConfig; // 0xb0
	private static DelegateBridge __Hotfix0_OnSortPanelItemClicked; // 0xb8
	private static DelegateBridge __Hotfix0__ConsumeTrackPoint; // 0xc0
	private static DelegateBridge __Hotfix0_ConsumeTrackpointInTheme; // 0xc8
	private static DelegateBridge __Hotfix0_ConsumeTrackpointInAllThemes; // 0xd0
	private static DelegateBridge __Hotfix0_ConsumeTrackPointInAllRecentThemes; // 0xd8
	private static DelegateBridge __Hotfix0_ConsumeTrackPointInAllRecentFurnitures; // 0xe0
	private static DelegateBridge __Hotfix0_ConsumeAllTrackpoint; // 0xe8
	private static DelegateBridge __Hotfix0_ApplyTheme; // 0xf0
	private static DelegateBridge __Hotfix0_LoadPreset; // 0xf8
	private static DelegateBridge __Hotfix0__AddDIYItemToRoom; // 0x100
	private static DelegateBridge __Hotfix0__SelectSameDIYItem; // 0x108
	private static DelegateBridge __Hotfix0__UnequipModifierFromRoom; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	private DIYListViewConfig currConfig { get; }
	public UIHandler pageHandler { get; }
	public DIYViewListThemeState viewListState { get; }
	public Boolean hasFuncCountExceedLimit { get; }

	// RVA: 0x3832310 VA: 0x7595e4a310
	private DIYListViewConfig get_currConfig() { }
	// RVA: 0x3832390 VA: 0x7595e4a390
	public UIHandler get_pageHandler() { }
	// RVA: 0x3831ecc VA: 0x7595e49ecc
	public DIYViewListThemeState get_viewListState() { }
	// RVA: 0x3832460 VA: 0x7595e4a460
	public Boolean get_hasFuncCountExceedLimit() { }
	// RVA: 0x38324c8 VA: 0x7595e4a4c8
	private Void _Setup(UIHandler pageHandler) { }
	// RVA: 0x38326ac VA: 0x7595e4a6ac
	private Void _Reload() { }
	// RVA: 0x3833290 VA: 0x7595e4b290
	private Void _UpdateOverViewData() { }
	// RVA: 0x3833f10 VA: 0x7595e4bf10
	private Void _UpdateRecentData() { }
	// RVA: 0x3834294 VA: 0x7595e4c294
	private Void _UpdateMenuData() { }
	// RVA: 0x383432c VA: 0x7595e4c32c
	private Void _UpdateViewList() { }
	// RVA: 0x38348ec VA: 0x7595e4c8ec
	private Void _UpdateFilter(Boolean isReset) { }
	// RVA: 0x3834ffc VA: 0x7595e4cffc
	private Void _UpdateByConfig() { }
	// RVA: 0x3832fe4 VA: 0x7595e4afe4
	private Void _UpdateAtmosphereText() { }
	// RVA: 0x38357fc VA: 0x7595e4d7fc
	private Void _UpdateViewCount() { }
	// RVA: 0x3835a6c VA: 0x7595e4da6c
	private Void _UpdateExpand(UIExpandListState expandState) { }
	// RVA: 0x3831cc0 VA: 0x7595e49cc0
	public Void OnExpand() { }
	// RVA: 0x38319c8 VA: 0x7595e499c8
	public Void OnFilterPressed(DIYFilterType filterType) { }
	// RVA: 0x3831b50 VA: 0x7595e49b50
	public Void OnSubTypePressed(FurnitureSubType subType) { }
	// RVA: 0x3835da8 VA: 0x7595e4dda8
	public Boolean OnViewItemPressed(DIYItemViewData data) { }
	// RVA: 0x3832724 VA: 0x7595e4a724
	private Void _UpdateRecentFurnitureData() { }
	// RVA: 0x383312c VA: 0x7595e4b12c
	private Void _ResetConfig() { }
	// RVA: 0x382fa78 VA: 0x7595e47a78
	public Void AddConfig(DIYListViewConfig config) { }
	// RVA: 0x3831f5c VA: 0x7595e49f5c
	public Void RemoveConfig() { }
	// RVA: 0x38321a8 VA: 0x7595e4a1a8
	public Void OnSortPanelItemClicked(DiySortType diyUIType, Int32 index) { }
	// RVA: 0x38361d8 VA: 0x7595e4e1d8
	private Void _ConsumeTrackPoint(String furnitureId) { }
	// RVA: 0x3836714 VA: 0x7595e4e714
	public Void ConsumeTrackpointInTheme(String themeId) { }
	// RVA: 0x38368ec VA: 0x7595e4e8ec
	public Void ConsumeTrackpointInAllThemes() { }
	// RVA: 0x3836bcc VA: 0x7595e4ebcc
	public Void ConsumeTrackPointInAllRecentThemes() { }
	// RVA: 0x3836d3c VA: 0x7595e4ed3c
	public Void ConsumeTrackPointInAllRecentFurnitures() { }
	// RVA: 0x3836eac VA: 0x7595e4eeac
	public Void ConsumeAllTrackpoint() { }
	// RVA: 0x3832068 VA: 0x7595e4a068
	public Void ApplyTheme() { }
	// RVA: 0x3836fb8 VA: 0x7595e4efb8
	public Void LoadPreset(Int32 index, IDIYPreset preset) { }
	// RVA: 0x38362c4 VA: 0x7595e4e2c4
	private Void _AddDIYItemToRoom(IDIYItem diyItem) { }
	// RVA: 0x3836350 VA: 0x7595e4e350
	private Void _SelectSameDIYItem(IDIYItem diyItem) { }
	// RVA: 0x38360c8 VA: 0x7595e4e0c8
	private Void _UnequipModifierFromRoom(DIYRoomPart roomPart) { }
	// RVA: 0x3837050 VA: 0x7595e4f050
	public Void .ctor() { }
}
```