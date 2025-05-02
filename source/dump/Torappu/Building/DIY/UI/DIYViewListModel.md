# DIYViewListModel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYViewListData m_viewList`

- `DIYViewListData m_funcViewList`

- `UIExpandListState m_expandedState`

- `DIYViewListThemeState m_themeState`

- `Boolean m_isUpdateRebuild`

- `ThemeData m_themeData`

- `UIHandler m_pageHandler`

- `Boolean m_hasFuncCountExceedLimit`


## Properties

- `UIHandler pageHandler`

- `DIYViewListData dataSource`

- `DIYViewListData funcDataSource`

- `UIExpandListState expandedState`

- `DIYViewListThemeState themeState`

- `Boolean dataRebuilded`

- `ThemeData themeData`


## Methods

- `UIHandler get_pageHandler()`

- `Void set_pageHandler(UIHandler)`

- `DIYViewListData get_dataSource()`

- `Void set_dataSource(DIYViewListData)`

- `DIYViewListData get_funcDataSource()`

- `Void set_funcDataSource(DIYViewListData)`

- `UIExpandListState get_expandedState()`

- `Void set_expandedState(UIExpandListState)`

- `DIYViewListThemeState get_themeState()`

- `Void set_themeState(DIYViewListThemeState)`

- `Boolean get_dataRebuilded()`

- `Void set_dataRebuilded(Boolean)`

- `ThemeData get_themeData()`

- `Void set_themeData(ThemeData)`

- `DIYItemViewData _GenerateDIYItemViewData(IDIYItem)`

- `DIYItemViewData _GenerateDIYItemViewData(ThemeData)`

- `Boolean _UpdateDIYItemViewData(DIYItemViewData)`

- `Boolean _UpdateThemeDIYItemViewData(DIYItemViewData)`

- `Boolean _UpdateFurnitureInThemeDIYItemViewData(DIYItemViewData)`

- `Boolean _UpdateFurnitureDIYItemViewData(DIYItemViewData)`

- `Void _PostHandler(List`1)`

- `Void _PostHandlerAppendFloorModifier(List`1)`

- `Void _PostHandlerAppendWallModifier(List`1)`

- `Void _UpdateViewListByTheme(UpdateViewListInput, Updater)`

- `Void _UpdateViewListByFurniture(UpdateViewListInput, Updater)`

- `Updater _GetUpdater()`

- `PostHandler _GetPostHandler(DIYFilterType, FurnitureSubType)`

- `Int32 _FuncItemCompare(DIYItemViewData, DIYItemViewData)`

- `Void _SetFuncTypePlacedData()`

- `Void UpdateViewList(UpdateViewListInput)`

- `Boolean UpdateViewCount()`

- `Boolean SetExpandState(UIExpandListState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYViewListModel : IHotfixable
{
	private DIYViewListData m_viewList; // 0x10
	private DIYViewListData m_funcViewList; // 0x18
	private UIExpandListState m_expandedState; // 0x20
	private DIYViewListThemeState m_themeState; // 0x24
	private Boolean m_isUpdateRebuild; // 0x28
	private ThemeData m_themeData; // 0x30
	private UIHandler m_pageHandler; // 0x38
	private List`1 m_currentItemViewList; // 0x40
	private List`1 m_functionItemList; // 0x48
	private Boolean m_hasFuncCountExceedLimit; // 0x50
	private Comparison`1 m_currComparer; // 0x58
	private static DelegateBridge __Hotfix0_get_pageHandler; // 0x0
	private static DelegateBridge __Hotfix0_set_pageHandler; // 0x8
	private static DelegateBridge __Hotfix0_get_dataSource; // 0x10
	private static DelegateBridge __Hotfix0_set_dataSource; // 0x18
	private static DelegateBridge __Hotfix0_get_funcDataSource; // 0x20
	private static DelegateBridge __Hotfix0_set_funcDataSource; // 0x28
	private static DelegateBridge __Hotfix0_get_expandedState; // 0x30
	private static DelegateBridge __Hotfix0_set_expandedState; // 0x38
	private static DelegateBridge __Hotfix0_get_themeState; // 0x40
	private static DelegateBridge __Hotfix0_set_themeState; // 0x48
	private static DelegateBridge __Hotfix0_get_dataRebuilded; // 0x50
	private static DelegateBridge __Hotfix0_set_dataRebuilded; // 0x58
	private static DelegateBridge __Hotfix0_get_themeData; // 0x60
	private static DelegateBridge __Hotfix0_set_themeData; // 0x68
	private static DelegateBridge __Hotfix0_GetFurnitureTotalCount; // 0x70
	private static DelegateBridge __Hotfix0_GetFurnitureCount; // 0x78
	private static DelegateBridge __Hotfix0__GenerateDIYItemViewData; // 0x80
	private static DelegateBridge __Hotfix1__GenerateDIYItemViewData; // 0x88
	private static DelegateBridge __Hotfix0__UpdateDIYItemViewData; // 0x90
	private static DelegateBridge __Hotfix0__UpdateThemeDIYItemViewData; // 0x98
	private static DelegateBridge __Hotfix0__UpdateFurnitureInThemeDIYItemViewData; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateFurnitureDIYItemViewData; // 0xa8
	private static DelegateBridge __Hotfix0__PostHandler; // 0xb0
	private static DelegateBridge __Hotfix0__PostHandlerAppendFloorModifier; // 0xb8
	private static DelegateBridge __Hotfix0__PostHandlerAppendWallModifier; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateViewListByTheme; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateViewListByFurniture; // 0xd0
	private static DelegateBridge __Hotfix0__GetUpdater; // 0xd8
	private static DelegateBridge __Hotfix0__GetPostHandler; // 0xe0
	private static DelegateBridge __Hotfix0__GetSubTypeSortId; // 0xe8
	private static DelegateBridge __Hotfix0__FuncItemCompare; // 0xf0
	private static DelegateBridge __Hotfix0__SetFuncTypePlacedData; // 0xf8
	private static DelegateBridge __Hotfix0_UpdateViewList; // 0x100
	private static DelegateBridge __Hotfix0_UpdateViewCount; // 0x108
	private static DelegateBridge __Hotfix0_SetExpandState; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	public UIHandler pageHandler { get; set; }
	public DIYViewListData dataSource { get; set; }
	public DIYViewListData funcDataSource { get; set; }
	public UIExpandListState expandedState { get; set; }
	public DIYViewListThemeState themeState { get; set; }
	public Boolean dataRebuilded { get; set; }
	public ThemeData themeData { get; set; }

	// RVA: 0x3842614 VA: 0x7595e5a614
	public UIHandler get_pageHandler() { }
	// RVA: 0x38325b8 VA: 0x7595e4a5b8
	public Void set_pageHandler(UIHandler value) { }
	// RVA: 0x384267c VA: 0x7595e5a67c
	public DIYViewListData get_dataSource() { }
	// RVA: 0x38426e4 VA: 0x7595e5a6e4
	public Void set_dataSource(DIYViewListData value) { }
	// RVA: 0x3842768 VA: 0x7595e5a768
	public DIYViewListData get_funcDataSource() { }
	// RVA: 0x38427d0 VA: 0x7595e5a7d0
	public Void set_funcDataSource(DIYViewListData value) { }
	// RVA: 0x3835318 VA: 0x7595e4d318
	public UIExpandListState get_expandedState() { }
	// RVA: 0x383529c VA: 0x7595e4d29c
	public Void set_expandedState(UIExpandListState value) { }
	// RVA: 0x38323f8 VA: 0x7595e4a3f8
	public DIYViewListThemeState get_themeState() { }
	// RVA: 0x3835220 VA: 0x7595e4d220
	public Void set_themeState(DIYViewListThemeState value) { }
	// RVA: 0x3842854 VA: 0x7595e5a854
	public Boolean get_dataRebuilded() { }
	// RVA: 0x383486c VA: 0x7595e4c86c
	public Void set_dataRebuilded(Boolean value) { }
	// RVA: 0x3836f50 VA: 0x7595e4ef50
	public ThemeData get_themeData() { }
	// RVA: 0x3836154 VA: 0x7595e4e154
	public Void set_themeData(ThemeData value) { }
	// RVA: 0x38363dc VA: 0x7595e4e3dc
	public static Int32 GetFurnitureTotalCount(String furnitureId) { }
	// RVA: 0x3837c14 VA: 0x7595e4fc14
	public static FurnitureCount GetFurnitureCount(String furnitureId, UIHandler pageHandler) { }
	// RVA: 0x38428bc VA: 0x7595e5a8bc
	private DIYItemViewData _GenerateDIYItemViewData(IDIYItem diyItem) { }
	// RVA: 0x3842954 VA: 0x7595e5a954
	private DIYItemViewData _GenerateDIYItemViewData(ThemeData themeData) { }
	// RVA: 0x3842a1c VA: 0x7595e5aa1c
	private Boolean _UpdateDIYItemViewData(DIYItemViewData itemViewData) { }
	// RVA: 0x3842a94 VA: 0x7595e5aa94
	private Boolean _UpdateThemeDIYItemViewData(DIYItemViewData itemViewData) { }
	// RVA: 0x384313c VA: 0x7595e5b13c
	private Boolean _UpdateFurnitureInThemeDIYItemViewData(DIYItemViewData itemViewData) { }
	// RVA: 0x3843448 VA: 0x7595e5b448
	private Boolean _UpdateFurnitureDIYItemViewData(DIYItemViewData itemViewData) { }
	// RVA: 0x384370c VA: 0x7595e5b70c
	private Void _PostHandler(List`1 list) { }
	// RVA: 0x3843784 VA: 0x7595e5b784
	private Void _PostHandlerAppendFloorModifier(List`1 list) { }
	// RVA: 0x38438a8 VA: 0x7595e5b8a8
	private Void _PostHandlerAppendWallModifier(List`1 list) { }
	// RVA: 0x38439d0 VA: 0x7595e5b9d0
	private Void _UpdateViewListByTheme(UpdateViewListInput input, Updater updater) { }
	// RVA: 0x3843e24 VA: 0x7595e5be24
	private Void _UpdateViewListByFurniture(UpdateViewListInput input, Updater updater) { }
	// RVA: 0x384485c VA: 0x7595e5c85c
	private Updater _GetUpdater() { }
	// RVA: 0x38449a0 VA: 0x7595e5c9a0
	private PostHandler _GetPostHandler(DIYFilterType filterType, FurnitureSubType filterSubType) { }
	// RVA: 0x3844ad8 VA: 0x7595e5cad8
	private static Int32 _GetSubTypeSortId(IDIYItem furnitureData) { }
	// RVA: 0x3844c2c VA: 0x7595e5cc2c
	private Int32 _FuncItemCompare(DIYItemViewData x, DIYItemViewData y) { }
	// RVA: 0x3844d90 VA: 0x7595e5cd90
	private Void _SetFuncTypePlacedData() { }
	// RVA: 0x38345fc VA: 0x7595e4c5fc
	public Void UpdateViewList(UpdateViewListInput input) { }
	// RVA: 0x38358d8 VA: 0x7595e4d8d8
	public Boolean UpdateViewCount() { }
	// RVA: 0x3835c14 VA: 0x7595e4dc14
	public Boolean SetExpandState(UIExpandListState expandState) { }
	// RVA: 0x3845350 VA: 0x7595e5d350
	public Void .ctor() { }
}
```