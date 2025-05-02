# CharacterRepoStateBean

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `CharacterRepoCardGroupViewProperty cardGroupProperty`

- `IntProperty _trackPointCountProperty`

- `BoolProperty _trackPointSelectedProperty`

- `BoolProperty _starMarkSelectedProperty`

- `CharacterCardSortTypeViewProperty _sortTypeProperty`


## Properties

- `CharacterFilterViewModel cardFilter`

- `CharacterSortType sortType`

- `Boolean trackPointFilterState`

- `Boolean starMarkTopState`

- `Boolean filterPanelShow`


## Methods

- `Void LoadData(String)`

- `Void LoadData(CharacterSortType, Boolean, String)`

- `Void ReloadAllCards()`

- `CharacterFilterViewModel get_cardFilter()`

- `Void SetCardFilter(CharacterFilterViewModel)`

- `CharacterSortType get_sortType()`

- `Void SetSortType(CharacterSortType)`

- `Boolean get_trackPointFilterState()`

- `Void set_trackPointFilterState(Boolean)`

- `Void ToggleTrackPointSelected()`

- `Boolean get_starMarkTopState()`

- `Void set_starMarkTopState(Boolean)`

- `Void ToggleStarMarkTopSelected()`

- `Boolean get_filterPanelShow()`

- `Void set_filterPanelShow(Boolean)`

- `Void ClearStarMarkEditSelectIds()`

- `Void ExitStarMarkEditMode()`

- `Void NotifyCardGroupChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public CharacterRepoCardGroupViewProperty cardGroupProperty; // 0x18
	private IntProperty _trackPointCountProperty; // 0x20
	private BoolProperty _trackPointSelectedProperty; // 0x28
	private BoolProperty _starMarkSelectedProperty; // 0x30
	private CharacterCardSortTypeViewProperty _sortTypeProperty; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix1_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ReloadAllCards; // 0x10
	private static DelegateBridge __Hotfix0_get_cardFilter; // 0x18
	private static DelegateBridge __Hotfix0_SetCardFilter; // 0x20
	private static DelegateBridge __Hotfix0_get_sortType; // 0x28
	private static DelegateBridge __Hotfix0_SetSortType; // 0x30
	private static DelegateBridge __Hotfix0_get_trackPointFilterState; // 0x38
	private static DelegateBridge __Hotfix0_set_trackPointFilterState; // 0x40
	private static DelegateBridge __Hotfix0_ToggleTrackPointSelected; // 0x48
	private static DelegateBridge __Hotfix0_get_starMarkTopState; // 0x50
	private static DelegateBridge __Hotfix0_set_starMarkTopState; // 0x58
	private static DelegateBridge __Hotfix0_ToggleStarMarkTopSelected; // 0x60
	private static DelegateBridge __Hotfix0_get_filterPanelShow; // 0x68
	private static DelegateBridge __Hotfix0_set_filterPanelShow; // 0x70
	private static DelegateBridge __Hotfix0_ClearStarMarkEditSelectIds; // 0x78
	private static DelegateBridge __Hotfix0_ExitStarMarkEditMode; // 0x80
	private static DelegateBridge __Hotfix0_NotifyCardGroupChanged; // 0x88
	private static DelegateBridge __Hotfix0__GenStageStatusDict; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public CharacterFilterViewModel cardFilter { get; }
	public CharacterSortType sortType { get; }
	public Boolean trackPointFilterState { get; set; }
	public Boolean starMarkTopState { get; set; }
	public Boolean filterPanelShow { get; set; }

	// RVA: 0x2cfa2c8 VA: 0x75953122c8
	public Void LoadData(String pageName) { }
	// RVA: 0x2cfb9f8 VA: 0x75953139f8
	public Void LoadData(CharacterSortType charSortType, Boolean cachedStarMarkTop, String pageName) { }
	// RVA: 0x2cf7d84 VA: 0x759530fd84
	public Void ReloadAllCards() { }
	// RVA: 0x2cfc040 VA: 0x7595314040
	public CharacterFilterViewModel get_cardFilter() { }
	// RVA: 0x2cfb138 VA: 0x7595313138
	public Void SetCardFilter(CharacterFilterViewModel filter) { }
	// RVA: 0x2cf9054 VA: 0x7595311054
	public CharacterSortType get_sortType() { }
	// RVA: 0x2cf9bf8 VA: 0x7595311bf8
	public Void SetSortType(CharacterSortType sortType) { }
	// RVA: 0x2cfc0d0 VA: 0x75953140d0
	public Boolean get_trackPointFilterState() { }
	// RVA: 0x2cfbbac VA: 0x7595313bac
	public Void set_trackPointFilterState(Boolean value) { }
	// RVA: 0x2cf9d74 VA: 0x7595311d74
	public Void ToggleTrackPointSelected() { }
	// RVA: 0x2cfc150 VA: 0x7595314150
	public Boolean get_starMarkTopState() { }
	// RVA: 0x2cfbcd8 VA: 0x7595313cd8
	public Void set_starMarkTopState(Boolean value) { }
	// RVA: 0x2cf9dec VA: 0x7595311dec
	public Void ToggleStarMarkTopSelected() { }
	// RVA: 0x2cfa39c VA: 0x759531239c
	public Boolean get_filterPanelShow() { }
	// RVA: 0x2cfb2d4 VA: 0x75953132d4
	public Void set_filterPanelShow(Boolean value) { }
	// RVA: 0x2cfc1e0 VA: 0x75953141e0
	public Void ClearStarMarkEditSelectIds() { }
	// RVA: 0x2cfadc8 VA: 0x7595312dc8
	public Void ExitStarMarkEditMode() { }
	// RVA: 0x2cfa85c VA: 0x759531285c
	public Void NotifyCardGroupChanged() { }
	// RVA: 0x2cfbe28 VA: 0x7595313e28
	private Dictionary`2 _GenStageStatusDict(out Int32 unlockedCount) { }
	// RVA: 0x2cfc2a0 VA: 0x75953142a0
	public Void .ctor() { }
}
```