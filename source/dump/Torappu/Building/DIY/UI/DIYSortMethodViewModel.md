# DIYSortMethodViewModel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DiyUISortTemplateListData currDiyUISortConfig`

- `Int32 currSelectedIndex`


## Methods

- `Void set_recentThemes(ListDict`2)`

- `Void set_recentFurnitures(ListDict`2)`

- `Boolean UpdateSortMethod(DIYListViewConfig, UIExpandListState)`

- `Boolean OnSortPanelItemClicked(DiySortType, Int32)`

- `Void _SetCurrSelectedIndex(Int32)`

- `Void _ToggleSortOrder(Int32)`

- `DiySortType _GetDIYSortType(DiyUIType)`

- `Boolean _UpdateComparers()`

- `Int32 _GetSelectedIndexFromCache(Int32)`

- `DiyUISortOrder _GetSortOrderFromCache(Int32, DiyUISortOrder)`

- `Void _SetSelectedIndexToCache(Int32)`

- `Void _SetSortOrderToCache(Int32, DiyUISortOrder)`

- `Int32 Compare(DIYItemViewData, DIYItemViewData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYSortMethodViewModel : IHotfixable
{
	public const String FALLBACK_SORT_TEMPLATE_NAME; // 0x0
	public static Dictionary`2 SORT_TEMPLATES; // 0x0
	public List`1 sortMethods; // 0x10
	public DiyUISortTemplateListData currDiyUISortConfig; // 0x18
	public Int32 currSelectedIndex; // 0x20
	public Dictionary`2 sortConfigCaches; // 0x28
	private List`1 m_comparers; // 0x30
	private ListDict`2 m_recentThemes; // 0x38
	private ListDict`2 m_recentFurnitures; // 0x40
	private static DelegateBridge __Hotfix0_get_recentThemes; // 0x8
	private static DelegateBridge __Hotfix0_set_recentThemes; // 0x10
	private static DelegateBridge __Hotfix0_get_recentFurnitures; // 0x18
	private static DelegateBridge __Hotfix0_set_recentFurnitures; // 0x20
	private static DelegateBridge __Hotfix0_UpdateSortMethod; // 0x28
	private static DelegateBridge __Hotfix0_OnSortPanelItemClicked; // 0x30
	private static DelegateBridge __Hotfix0__SetCurrSelectedIndex; // 0x38
	private static DelegateBridge __Hotfix0__ToggleSortOrder; // 0x40
	private static DelegateBridge __Hotfix0__GetDIYSortType; // 0x48
	private static DelegateBridge __Hotfix0__UpdateComparers; // 0x50
	private static DelegateBridge __Hotfix0__GetDiyUISortComparer; // 0x58
	private static DelegateBridge __Hotfix0__IsEqual; // 0x60
	private static DelegateBridge __Hotfix0__GetSelectedIndexFromCache; // 0x68
	private static DelegateBridge __Hotfix0__GetSortOrderFromCache; // 0x70
	private static DelegateBridge __Hotfix0__SetSelectedIndexToCache; // 0x78
	private static DelegateBridge __Hotfix0__SetSortOrderToCache; // 0x80
	private static DelegateBridge __Hotfix0_Compare; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public ListDict`2 recentThemes { get; set; }
	public ListDict`2 recentFurnitures { get; set; }

	// RVA: 0x383ee8c VA: 0x7595e56e8c
	public ListDict`2 get_recentThemes() { }
	// RVA: 0x38364ec VA: 0x7595e4e4ec
	public Void set_recentThemes(ListDict`2 value) { }
	// RVA: 0x383f4d4 VA: 0x7595e574d4
	public ListDict`2 get_recentFurnitures() { }
	// RVA: 0x3836580 VA: 0x7595e4e580
	public Void set_recentFurnitures(ListDict`2 value) { }
	// RVA: 0x3835380 VA: 0x7595e4d380
	public Boolean UpdateSortMethod(DIYListViewConfig config, UIExpandListState expandState) { }
	// RVA: 0x3836614 VA: 0x7595e4e614
	public Boolean OnSortPanelItemClicked(DiySortType diySortType, Int32 index) { }
	// RVA: 0x38404e4 VA: 0x7595e584e4
	private Void _SetCurrSelectedIndex(Int32 index) { }
	// RVA: 0x384040c VA: 0x7595e5840c
	private Void _ToggleSortOrder(Int32 index) { }
	// RVA: 0x383fcd0 VA: 0x7595e57cd0
	private DiySortType _GetDIYSortType(DiyUIType diyUIType) { }
	// RVA: 0x383ff48 VA: 0x7595e57f48
	private Boolean _UpdateComparers() { }
	// RVA: 0x38409b0 VA: 0x7595e589b0
	private static DIYItemViewComparer _GetDiyUISortComparer(String sortTemplate, DiyUISortOrder sortOrder) { }
	// RVA: 0x3840850 VA: 0x7595e58850
	private static Boolean _IsEqual(List`1 a, List`1 b) { }
	// RVA: 0x3840244 VA: 0x7595e58244
	private Int32 _GetSelectedIndexFromCache(Int32 defaultIndex) { }
	// RVA: 0x384030c VA: 0x7595e5830c
	private DiyUISortOrder _GetSortOrderFromCache(Int32 methodIndex, DiyUISortOrder defaultOrder) { }
	// RVA: 0x3840580 VA: 0x7595e58580
	private Void _SetSelectedIndexToCache(Int32 index) { }
	// RVA: 0x38406cc VA: 0x7595e586cc
	private Void _SetSortOrderToCache(Int32 methodIndex, DiyUISortOrder sortOrder) { }
	// RVA: 0x3840d4c VA: 0x7595e58d4c
	public Int32 Compare(DIYItemViewData x, DIYItemViewData y) { }
	// RVA: 0x3840fb0 VA: 0x7595e58fb0
	public Void .ctor() { }
	// RVA: 0x38411a8 VA: 0x7595e591a8
	private static Void .cctor() { }
}
```