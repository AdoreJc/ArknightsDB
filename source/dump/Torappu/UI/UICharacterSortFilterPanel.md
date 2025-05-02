# UICharacterSortFilterPanel

**Namespace:** `Torappu.UI`


## Fields

- `UICharacterSortGroupOnFloat _sortGroup`

- `UICharacterFilterGroupOnFloat _filterGroup`

- `RectTransform _sortPanel`

- `RectTransform _filterPanel`

- `RectTransform _backBkg`

- `String pageName`

- `Boolean m_isInited`

- `Vector3 m_originSortPanelPos`

- `Vector3 m_targetSortPanelPos`

- `Vector3 m_originFilterPanelPos`

- `Vector3 m_targetFilterPanelPos`


## Properties

- `UICharacterHandbookStageCountItem stageCountItem`


## Methods

- `Void Render(CharacterFilterViewModel, CharacterSortType)`

- `UICharacterHandbookStageCountItem get_stageCountItem()`

- `Void _InitIfNot()`

- `Void _InitFilterState()`

- `Void EventOnDissmissSort()`

- `Void EventOnShowSortPanel()`

- `Void EventOnDismissFilter()`

- `Void EventOnShowFilter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortFilterPanel : MonoBehaviour, IHotfixable
{
	private UICharacterSortGroupOnFloat _sortGroup; // 0x18
	private UICharacterFilterGroupOnFloat _filterGroup; // 0x20
	private RectTransform _sortPanel; // 0x28
	private RectTransform _filterPanel; // 0x30
	private RectTransform _backBkg; // 0x38
	public Action`1 eventOnFilterClick; // 0x40
	public Action`1 eventOnSortClick; // 0x48
	public String pageName; // 0x50
	private Boolean m_isInited; // 0x58
	private const Single PANEL_ANIMATION_DURATION; // 0x0
	private Vector3 m_originSortPanelPos; // 0x5c
	private Vector3 m_targetSortPanelPos; // 0x68
	private Vector3 m_originFilterPanelPos; // 0x74
	private Vector3 m_targetFilterPanelPos; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_get_stageCountItem; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__InitFilterState; // 0x18
	private static DelegateBridge __Hotfix0_EventOnDissmissSort; // 0x20
	private static DelegateBridge __Hotfix0_EventOnShowSortPanel; // 0x28
	private static DelegateBridge __Hotfix0_EventOnDismissFilter; // 0x30
	private static DelegateBridge __Hotfix0_EventOnShowFilter; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public UICharacterHandbookStageCountItem stageCountItem { get; }

	// RVA: 0x21307ac VA: 0x75947487ac
	public Void Render(CharacterFilterViewModel filter, CharacterSortType sortType) { }
	// RVA: 0x2130a3c VA: 0x7594748a3c
	public UICharacterHandbookStageCountItem get_stageCountItem() { }
	// RVA: 0x2131da0 VA: 0x7594749da0
	private Void _InitIfNot() { }
	// RVA: 0x2132018 VA: 0x759474a018
	private Void _InitFilterState() { }
	// RVA: 0x21321a4 VA: 0x759474a1a4
	public Void EventOnDissmissSort() { }
	// RVA: 0x2130b64 VA: 0x7594748b64
	public Void EventOnShowSortPanel() { }
	// RVA: 0x2130e2c VA: 0x7594748e2c
	public Void EventOnDismissFilter() { }
	// RVA: 0x2130cd8 VA: 0x7594748cd8
	public Void EventOnShowFilter() { }
	// RVA: 0x2132260 VA: 0x759474a260
	public Void .ctor() { }
}
```