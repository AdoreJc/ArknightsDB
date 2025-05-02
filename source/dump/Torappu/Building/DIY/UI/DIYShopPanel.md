# DIYShopPanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFilterItemViewAdapter _filterAdapter`

- `DIYFilterItemViewAdapter _themeFilterAdapter`

- `DIYShopItemViewAdapter _furnitureAdapter`

- `DIYFurnitureFilterGroup _filterGroup`

- `FurnitureGenreConfig _furnitureGenreConfig`

- `UIDIYFurnitureTypeIconHub _typeIcons`

- `DIYShopBuyPanel _buyPanel`

- `Text _cashLabel`

- `Text _furnitureCoinLabel`

- `RectTransform _mainPanel`

- `DIYSortPanel _diySortPanel`

- `DIYShopGroupPanel _shopGroupPanel`

- `Image _backgroundImage`

- `IDIYShop m_diyShop`

- `Boolean m_shown`

- `DIYShopFilterViewData m_lastFilterData`

- `Boolean m_tweening`

- `FurnitureSorter m_sorter`

- `Action m_hideCallback`


## Properties

- `Boolean shown`


## Methods

- `Boolean get_shown()`

- `Void _OnViewItemSelected(DIYShopFilterViewData)`

- `Void _OnViewInfoSelected(DIYShopFilterViewData)`

- `Void _OnViewDescSelected(DIYShopFilterViewData)`

- `Void _SetFilterSelection(DIYShopFilterViewData)`

- `Void _SetThemeFilterSelection(DIYShopFilterViewData)`

- `Void _OnShopItemSelected(DIYShopItemViewData)`

- `Void _ShowOKDialog(String, Action)`

- `Void _OnBuyItemCommand(IDIYShopItem, Int32, Int32)`

- `Void _UpdateFurnitureGroupView(String, Predicate`1, Comparison`1)`

- `Void _UpdateFurnitureList(Predicate`1)`

- `Int32 _GetShopItemCountOfTheme(String)`

- `Void _UpdateTabsByTheme(Predicate`1, Comparison`1)`

- `Void _UpdateTabsByGenre(Int32)`

- `Void Setup(IDIYShop)`

- `Void UpdateView()`

- `Void _UpdateResources()`

- `Void _PanelTweenCallback(Single)`

- `Void Show(Action)`

- `Void Hide(Boolean)`

- `Void HandleBackCommon()`

- `Void _RefreshFurnitureCount()`

- `Void OnFilterButtonPressed()`

- `Void OnThemeButtonPressed()`

- `Void OnGroundButtonPresed()`

- `Void OnWallButtonPresed()`

- `Void OnCeilingButtonPresed()`

- `Void OnBackgroundPressed()`

- `Void OnDestroy()`

- `Int32 <_OnViewItemSelected>b__26_0(IDIYShopItem, IDIYShopItem)`

- `Void <_OnBuyItemCommand>b__33_0(Int32)`

- `Boolean <_UpdateFurnitureList>b__35_0(DIYShopItemViewData)`

- `Int32 <_UpdateFurnitureList>b__35_1(DIYShopItemViewData, DIYShopItemViewData)`

- `Int32 <UpdateView>b__40_0(IDIYShopItem, IDIYShopItem)`

- `Void <Show>b__43_1()`

- `Void <Hide>b__44_1()`

- `Void <OnFilterButtonPressed>b__48_0(ISortAndFilterState)`

- `Int32 <OnThemeButtonPressed>b__49_0(IDIYShopItem, IDIYShopItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopPanel : MonoBehaviour, IHotfixable
{
	private DIYFilterItemViewAdapter _filterAdapter; // 0x18
	private DIYFilterItemViewAdapter _themeFilterAdapter; // 0x20
	private DIYShopItemViewAdapter _furnitureAdapter; // 0x28
	private DIYFurnitureFilterGroup _filterGroup; // 0x30
	private FurnitureGenreConfig _furnitureGenreConfig; // 0x38
	private UIDIYFurnitureTypeIconHub _typeIcons; // 0x40
	private DIYShopBuyPanel _buyPanel; // 0x48
	private Text _cashLabel; // 0x50
	private Text _furnitureCoinLabel; // 0x58
	private RectTransform _mainPanel; // 0x60
	private DIYSortPanel _diySortPanel; // 0x68
	private DIYShopGroupPanel _shopGroupPanel; // 0x70
	private Image _backgroundImage; // 0x78
	private IDIYShop m_diyShop; // 0x80
	private Boolean m_shown; // 0x88
	private DIYShopFilterViewData m_lastFilterData; // 0x90
	private Predicate`1 m_currentFurnitureListPredicator; // 0x98
	private Boolean m_tweening; // 0xa0
	private List`1 m_currentItemViewData; // 0xa8
	private FurnitureSorter m_sorter; // 0xb0
	private Predicate`1 m_filterFunction; // 0xb8
	private Func`3 m_sortFunction; // 0xc0
	private Action m_hideCallback; // 0xc8
	private static DelegateBridge __Hotfix0_get_shown; // 0x0
	private static DelegateBridge __Hotfix0__OnViewItemSelected; // 0x8
	private static DelegateBridge __Hotfix0__OnViewInfoSelected; // 0x10
	private static DelegateBridge __Hotfix0__OnViewDescSelected; // 0x18
	private static DelegateBridge __Hotfix0__SetFilterSelection; // 0x20
	private static DelegateBridge __Hotfix0__SetThemeFilterSelection; // 0x28
	private static DelegateBridge __Hotfix0__OnShopItemSelected; // 0x30
	private static DelegateBridge __Hotfix0__ShowOKDialog; // 0x38
	private static DelegateBridge __Hotfix0__OnBuyItemCommand; // 0x40
	private static DelegateBridge __Hotfix0__UpdateFurnitureGroupView; // 0x48
	private static DelegateBridge __Hotfix0__UpdateFurnitureList; // 0x50
	private static DelegateBridge __Hotfix0__GetShopItemCountOfTheme; // 0x58
	private static DelegateBridge __Hotfix0__UpdateTabsByTheme; // 0x60
	private static DelegateBridge __Hotfix0__UpdateTabsByGenre; // 0x68
	private static DelegateBridge __Hotfix0_Setup; // 0x70
	private static DelegateBridge __Hotfix0_UpdateView; // 0x78
	private static DelegateBridge __Hotfix0__UpdateResources; // 0x80
	private static DelegateBridge __Hotfix0__PanelTweenCallback; // 0x88
	private static DelegateBridge __Hotfix0_Show; // 0x90
	private static DelegateBridge __Hotfix0_Hide; // 0x98
	private static DelegateBridge __Hotfix0_HandleBackCommon; // 0xa0
	private static DelegateBridge __Hotfix0__GetShopFilterFunction; // 0xa8
	private static DelegateBridge __Hotfix0__RefreshFurnitureCount; // 0xb0
	private static DelegateBridge __Hotfix0_OnFilterButtonPressed; // 0xb8
	private static DelegateBridge __Hotfix0_OnThemeButtonPressed; // 0xc0
	private static DelegateBridge __Hotfix0_OnGroundButtonPresed; // 0xc8
	private static DelegateBridge __Hotfix0_OnWallButtonPresed; // 0xd0
	private static DelegateBridge __Hotfix0_OnCeilingButtonPresed; // 0xd8
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0xe0
	private static DelegateBridge __Hotfix0__GetFurnitureTotalCount; // 0xe8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public Boolean shown { get; }

	// RVA: 0x380524c VA: 0x7595e1d24c
	public Boolean get_shown() { }
	// RVA: 0x38052b4 VA: 0x7595e1d2b4
	private Void _OnViewItemSelected(DIYShopFilterViewData data) { }
	// RVA: 0x38063ec VA: 0x7595e1e3ec
	private Void _OnViewInfoSelected(DIYShopFilterViewData data) { }
	// RVA: 0x3806544 VA: 0x7595e1e544
	private Void _OnViewDescSelected(DIYShopFilterViewData data) { }
	// RVA: 0x38061d4 VA: 0x7595e1e1d4
	private Void _SetFilterSelection(DIYShopFilterViewData data) { }
	// RVA: 0x3805720 VA: 0x7595e1d720
	private Void _SetThemeFilterSelection(DIYShopFilterViewData data) { }
	// RVA: 0x38066a4 VA: 0x7595e1e6a4
	private Void _OnShopItemSelected(DIYShopItemViewData data) { }
	// RVA: 0x38076a8 VA: 0x7595e1f6a8
	private Void _ShowOKDialog(String content, Action okAction) { }
	// RVA: 0x3807808 VA: 0x7595e1f808
	private Void _OnBuyItemCommand(IDIYShopItem shopItem, Int32 cashCount, Int32 furnitureCoinCount) { }
	// RVA: 0x380558c VA: 0x7595e1d58c
	private Void _UpdateFurnitureGroupView(String themeId, Predicate`1 filter, Comparison`1 sorter) { }
	// RVA: 0x3805940 VA: 0x7595e1d940
	private Void _UpdateFurnitureList(Predicate`1 pred) { }
	// RVA: 0x3807bd8 VA: 0x7595e1fbd8
	private Int32 _GetShopItemCountOfTheme(String themeId) { }
	// RVA: 0x3807f4c VA: 0x7595e1ff4c
	private Void _UpdateTabsByTheme(Predicate`1 filter, Comparison`1 sorter) { }
	// RVA: 0x3808638 VA: 0x7595e20638
	private Void _UpdateTabsByGenre(Int32 index) { }
	// RVA: 0x3808e80 VA: 0x7595e20e80
	public Void Setup(IDIYShop shop) { }
	// RVA: 0x38092d0 VA: 0x7595e212d0
	public Void UpdateView() { }
	// RVA: 0x380939c VA: 0x7595e2139c
	private Void _UpdateResources() { }
	// RVA: 0x3809808 VA: 0x7595e21808
	private Void _PanelTweenCallback(Single val) { }
	// RVA: 0x38099bc VA: 0x7595e219bc
	public Void Show(Action hideCallback) { }
	// RVA: 0x3809de0 VA: 0x7595e21de0
	public Void Hide(Boolean needTween) { }
	// RVA: 0x380a164 VA: 0x7595e22164
	public Void HandleBackCommon() { }
	// RVA: 0x380a240 VA: 0x7595e22240
	private Predicate`1 _GetShopFilterFunction(IEnumerable`1 settings) { }
	// RVA: 0x380a34c VA: 0x7595e2234c
	private Void _RefreshFurnitureCount() { }
	// RVA: 0x380a5b4 VA: 0x7595e225b4
	public Void OnFilterButtonPressed() { }
	// RVA: 0x380a798 VA: 0x7595e22798
	public Void OnThemeButtonPressed() { }
	// RVA: 0x380a864 VA: 0x7595e22864
	public Void OnGroundButtonPresed() { }
	// RVA: 0x380a8d0 VA: 0x7595e228d0
	public Void OnWallButtonPresed() { }
	// RVA: 0x380a93c VA: 0x7595e2293c
	public Void OnCeilingButtonPresed() { }
	// RVA: 0x380a9a8 VA: 0x7595e229a8
	public Void OnBackgroundPressed() { }
	// RVA: 0x38075b0 VA: 0x7595e1f5b0
	private static Int32 _GetFurnitureTotalCount(String furnitureId, IFurnitureStorage storage) { }
	// RVA: 0x380aa30 VA: 0x7595e22a30
	private Void OnDestroy() { }
	// RVA: 0x380aca0 VA: 0x7595e22ca0
	public Void .ctor() { }
	// RVA: 0x380ad50 VA: 0x7595e22d50
	private Int32 <_OnViewItemSelected>b__26_0(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x380ad74 VA: 0x7595e22d74
	private Void <_OnBuyItemCommand>b__33_0(Int32 resultCode) { }
	// RVA: 0x380aec8 VA: 0x7595e22ec8
	private Boolean <_UpdateFurnitureList>b__35_0(DIYShopItemViewData x) { }
	// RVA: 0x380aef4 VA: 0x7595e22ef4
	private Int32 <_UpdateFurnitureList>b__35_1(DIYShopItemViewData lhs, DIYShopItemViewData rhs) { }
	// RVA: 0x380af28 VA: 0x7595e22f28
	private Int32 <UpdateView>b__40_0(IDIYShopItem lhs, IDIYShopItem rhs) { }
	// RVA: 0x380af4c VA: 0x7595e22f4c
	private Void <Show>b__43_1() { }
	// RVA: 0x380af54 VA: 0x7595e22f54
	private Void <Hide>b__44_1() { }
	// RVA: 0x380b034 VA: 0x7595e23034
	private Void <OnFilterButtonPressed>b__48_0(ISortAndFilterState result) { }
	// RVA: 0x380b5d4 VA: 0x7595e235d4
	private Int32 <OnThemeButtonPressed>b__49_0(IDIYShopItem lhs, IDIYShopItem rhs) { }
}
```