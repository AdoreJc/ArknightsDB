# UICharacterSortTypePanelItem

**Namespace:** `Torappu.UI`


## Fields

- `CharacterSortType _firstSortType`

- `CharacterSortType _secondSortType`

- `Text _sortTitle`

- `Image _sortIcon`

- `Image _sortIconBg`

- `GameObject _lightMask`

- `RectTransform _countContainer`

- `UICharacterHandbookStageCountItem _countPrefab`

- `String pageName`

- `UICharacterHandbookStageCountItem m_countItem`

- `ThreeStateToggle m_toggle`

- `Boolean m_isInited`


## Properties

- `UICharacterHandbookStageCountItem countItem`


## Methods

- `Void set_onSortTypeChanged(Action`1)`

- `Void _InitIfNot()`

- `Void _OnToggleClick(State)`

- `UICharacterHandbookStageCountItem get_countItem()`

- `Void _GenHandbookStageCountItem()`

- `Void _ChangeColor(State)`

- `Void _ChangeCntItemColor(Color, Color)`

- `SortItemColorStyle _TryGetColorStyle(State)`

- `String _TryGetStyleId(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortTypePanelItem : UICharacterSortCommonItem
{
	private CharacterSortType _firstSortType; // 0x18
	private CharacterSortType _secondSortType; // 0x1c
	private Text _sortTitle; // 0x20
	private Image _sortIcon; // 0x28
	private Image _sortIconBg; // 0x30
	private SortItemColorStyle[] _colorStyles; // 0x38
	private GameObject _lightMask; // 0x40
	private RectTransform _countContainer; // 0x48
	private UICharacterHandbookStageCountItem _countPrefab; // 0x50
	public String pageName; // 0x58
	private UICharacterHandbookStageCountItem m_countItem; // 0x60
	private ThreeStateToggle m_toggle; // 0x68
	private Boolean m_isInited; // 0x70
	private const String UNSELECTED_COLOR_ID; // 0x0
	private const String SELECTED_COLOR_ID; // 0x0
	private Action`1 <onSortTypeChanged>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onSortTypeChanged; // 0x0
	private static DelegateBridge __Hotfix0_set_onSortTypeChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnToggleClick; // 0x18
	private static DelegateBridge __Hotfix0_RenderSortItem; // 0x20
	private static DelegateBridge __Hotfix0_NotifySortTypeChanged; // 0x28
	private static DelegateBridge __Hotfix0_get_countItem; // 0x30
	private static DelegateBridge __Hotfix0__GenHandbookStageCountItem; // 0x38
	private static DelegateBridge __Hotfix0__ChangeColor; // 0x40
	private static DelegateBridge __Hotfix0__ChangeCntItemColor; // 0x48
	private static DelegateBridge __Hotfix0__TryGetColorStyle; // 0x50
	private static DelegateBridge __Hotfix0__TryGetStyleId; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action`1 onSortTypeChanged { get; set; }
	public UICharacterHandbookStageCountItem countItem { get; }

	// RVA: 0x2135d54 VA: 0x759474dd54
	private Action`1 get_onSortTypeChanged() { }
	// RVA: 0x21334c0 VA: 0x759474b4c0
	public Void set_onSortTypeChanged(Action`1 value) { }
	// RVA: 0x2135dbc VA: 0x759474ddbc
	private Void _InitIfNot() { }
	// RVA: 0x2135ed0 VA: 0x759474ded0
	private Void _OnToggleClick(State state) { }
	// RVA: 0x2135fac VA: 0x759474dfac
	public override Void RenderSortItem(CharacterSortTypePair sortPair, Boolean lightMode) { }
	// RVA: 0x21362d0 VA: 0x759474e2d0
	public override Void NotifySortTypeChanged(CharacterSortType sortType) { }
	// RVA: 0x2133458 VA: 0x759474b458
	public UICharacterHandbookStageCountItem get_countItem() { }
	// RVA: 0x2136208 VA: 0x759474e208
	private Void _GenHandbookStageCountItem() { }
	// RVA: 0x21363a4 VA: 0x759474e3a4
	private Void _ChangeColor(State state) { }
	// RVA: 0x2136674 VA: 0x759474e674
	private Void _ChangeCntItemColor(Color txtColor, Color bgColor) { }
	// RVA: 0x21364b8 VA: 0x759474e4b8
	private SortItemColorStyle _TryGetColorStyle(State state) { }
	// RVA: 0x21367cc VA: 0x759474e7cc
	private String _TryGetStyleId(State state) { }
	// RVA: 0x2136880 VA: 0x759474e880
	public Void .ctor() { }
}
```