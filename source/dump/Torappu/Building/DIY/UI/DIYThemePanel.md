# DIYThemePanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFilterItemViewAdapter _filterAdapter`

- `DIYThemeGroupPanel _themeGroupPanel`

- `FurnitureGenreConfig _furnitureGenreConfig`

- `RectTransform _mainPanel`

- `Boolean m_shown`

- `Boolean m_tweening`

- `Action m_hideCallback`

- `IFurnitureStorage m_storage`

- `IFurnitureProvider m_furnitureProvider`

- `IDIYRoomModifierProvider m_modifierProvider`

- `IFurnitureDataProvider m_furnitureDatabase`

- `IDIYRoomModifierDataProvider m_modifierDatabase`

- `DIYShopFilterViewData m_lastFilterData`

- `String m_currentThemeId`


## Properties

- `Boolean shown`


## Methods

- `Boolean get_shown()`

- `Void _OnViewItemSelected(DIYShopFilterViewData)`

- `Void _OnViewInfoSelected(DIYShopFilterViewData)`

- `Void _OnViewDescSelected(DIYShopFilterViewData)`

- `Void _SetFilterSelection(DIYShopFilterViewData)`

- `Void _OnFurnitureItemSelected(IDIYItem)`

- `Void _OnFurnitureInfoButtonPressed(DIYItemViewData)`

- `Void _ShowOKDialog(String, Action)`

- `Void _OnBuyItemCommand(IDIYShopItem, Int32, Int32)`

- `Void _UpdateGroupListWithTheme(String)`

- `Void _UpdateTabsByTheme()`

- `Void Setup(IFurnitureProvider, IDIYRoomModifierProvider)`

- `Void UpdateView()`

- `Void _PanelTweenCallback(Single)`

- `Void Show(Action, Action`1, Action`1, Action`1)`

- `Void Hide(Boolean)`

- `Void OnThemeButtonPressed()`

- `Void OnBackgroundPressed()`

- `Void OnOneClickSetupButtonPressed()`

- `Void OnDestroy()`

- `Void <Show>b__33_1()`

- `Void <Hide>b__34_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYThemePanel : MonoBehaviour, IHotfixable
{
	private DIYFilterItemViewAdapter _filterAdapter; // 0x18
	private DIYThemeGroupPanel _themeGroupPanel; // 0x20
	private FurnitureGenreConfig _furnitureGenreConfig; // 0x28
	private RectTransform _mainPanel; // 0x30
	private Boolean m_shown; // 0x38
	private Boolean m_tweening; // 0x39
	private List`1 m_currentItemViewData; // 0x40
	private Action m_hideCallback; // 0x48
	private Action`1 m_itemSelectCallback; // 0x50
	private Action`1 m_oneClickSetupCallback; // 0x58
	private Action`1 m_furnitureInfoCallback; // 0x60
	private IFurnitureStorage m_storage; // 0x68
	private IFurnitureProvider m_furnitureProvider; // 0x70
	private IDIYRoomModifierProvider m_modifierProvider; // 0x78
	private IFurnitureDataProvider m_furnitureDatabase; // 0x80
	private IDIYRoomModifierDataProvider m_modifierDatabase; // 0x88
	private DIYShopFilterViewData m_lastFilterData; // 0x90
	private String m_currentThemeId; // 0x98
	private static DelegateBridge __Hotfix0_get_shown; // 0x0
	private static DelegateBridge __Hotfix0__OnViewItemSelected; // 0x8
	private static DelegateBridge __Hotfix0__OnViewInfoSelected; // 0x10
	private static DelegateBridge __Hotfix0__OnViewDescSelected; // 0x18
	private static DelegateBridge __Hotfix0__SetFilterSelection; // 0x20
	private static DelegateBridge __Hotfix0__OnFurnitureItemSelected; // 0x28
	private static DelegateBridge __Hotfix0__OnFurnitureInfoButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0__ShowOKDialog; // 0x38
	private static DelegateBridge __Hotfix0__OnBuyItemCommand; // 0x40
	private static DelegateBridge __Hotfix0__UpdateGroupListWithTheme; // 0x48
	private static DelegateBridge __Hotfix0__UpdateTabsByTheme; // 0x50
	private static DelegateBridge __Hotfix0_Setup; // 0x58
	private static DelegateBridge __Hotfix0_UpdateView; // 0x60
	private static DelegateBridge __Hotfix0__PanelTweenCallback; // 0x68
	private static DelegateBridge __Hotfix0_Show; // 0x70
	private static DelegateBridge __Hotfix0_Hide; // 0x78
	private static DelegateBridge __Hotfix0_OnThemeButtonPressed; // 0x80
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0x88
	private static DelegateBridge __Hotfix0_OnOneClickSetupButtonPressed; // 0x90
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x98
	private static DelegateBridge __Hotfix0__GetFurnitureTotalCount; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Boolean shown { get; }

	// RVA: 0x38104d0 VA: 0x7595e284d0
	public Boolean get_shown() { }
	// RVA: 0x3810538 VA: 0x7595e28538
	private Void _OnViewItemSelected(DIYShopFilterViewData data) { }
	// RVA: 0x38109fc VA: 0x7595e289fc
	private Void _OnViewInfoSelected(DIYShopFilterViewData data) { }
	// RVA: 0x3810b54 VA: 0x7595e28b54
	private Void _OnViewDescSelected(DIYShopFilterViewData data) { }
	// RVA: 0x38107e4 VA: 0x7595e287e4
	private Void _SetFilterSelection(DIYShopFilterViewData data) { }
	// RVA: 0x3810cb4 VA: 0x7595e28cb4
	private Void _OnFurnitureItemSelected(IDIYItem data) { }
	// RVA: 0x3810d58 VA: 0x7595e28d58
	private Void _OnFurnitureInfoButtonPressed(DIYItemViewData viewData) { }
	// RVA: 0x3810df8 VA: 0x7595e28df8
	private Void _ShowOKDialog(String content, Action okAction) { }
	// RVA: 0x3810f58 VA: 0x7595e28f58
	private Void _OnBuyItemCommand(IDIYShopItem shopItem, Int32 cashCount, Int32 furnitureCoinCount) { }
	// RVA: 0x3810634 VA: 0x7595e28634
	public Void _UpdateGroupListWithTheme(String themeId) { }
	// RVA: 0x3811250 VA: 0x7595e29250
	private Void _UpdateTabsByTheme() { }
	// RVA: 0x38118d8 VA: 0x7595e298d8
	public Void Setup(IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider modifierProvider) { }
	// RVA: 0x3811c00 VA: 0x7595e29c00
	public Void UpdateView() { }
	// RVA: 0x3811c68 VA: 0x7595e29c68
	private Void _PanelTweenCallback(Single val) { }
	// RVA: 0x3811d70 VA: 0x7595e29d70
	public Void Show(Action hideCallback, Action`1 selectCallback, Action`1 oneClickSetupCallback, Action`1 furnitureInfoButtonCallback) { }
	// RVA: 0x3812130 VA: 0x7595e2a130
	public Void Hide(Boolean needTween) { }
	// RVA: 0x38124b4 VA: 0x7595e2a4b4
	public Void OnThemeButtonPressed() { }
	// RVA: 0x381251c VA: 0x7595e2a51c
	public Void OnBackgroundPressed() { }
	// RVA: 0x38125a4 VA: 0x7595e2a5a4
	public Void OnOneClickSetupButtonPressed() { }
	// RVA: 0x3812648 VA: 0x7595e2a648
	private Void OnDestroy() { }
	// RVA: 0x38127f0 VA: 0x7595e2a7f0
	private static Int32 _GetFurnitureTotalCount(String furnitureId, IFurnitureStorage storage) { }
	// RVA: 0x38128e8 VA: 0x7595e2a8e8
	public Void .ctor() { }
	// RVA: 0x3812958 VA: 0x7595e2a958
	private Void <Show>b__33_1() { }
	// RVA: 0x3812960 VA: 0x7595e2a960
	private Void <Hide>b__34_1() { }
}
```