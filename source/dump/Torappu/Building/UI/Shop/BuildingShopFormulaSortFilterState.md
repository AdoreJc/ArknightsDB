# BuildingShopFormulaSortFilterState

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `SFormulaSortFilterStateBean m_stateBean`


## Methods

- `Void _RefreshSorts()`

- `Void _RefreshFilters()`

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`

- `Void _OnSortTypeClicked(FormulaSortType)`

- `Void _OnFilterTypeClicked(FormulaFilterType)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopFormulaSortFilterState : PopupFloatState
{
	private BuildingShopFormulaFilterItem[] _filterItems; // 0x70
	private BuildingShopFormulaSortItem[] _sortItems; // 0x78
	private SFormulaSortFilterStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__RefreshSorts; // 0x10
	private static DelegateBridge __Hotfix0__RefreshFilters; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnSortTypeClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnFilterTypeClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3dbae50 VA: 0x75963d2e50
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3dbaeb8 VA: 0x75963d2eb8
	protected override Void OnEnter() { }
	// RVA: 0x3dbb184 VA: 0x75963d3184
	private Void _RefreshSorts() { }
	// RVA: 0x3dbb09c VA: 0x75963d309c
	private Void _RefreshFilters() { }
	// RVA: 0x3dbb284 VA: 0x75963d3284
	public Void EventOnConfirmClicked() { }
	// RVA: 0x3dbb30c VA: 0x75963d330c
	public Void EventOnCancelClicked() { }
	// RVA: 0x3dbb380 VA: 0x75963d3380
	private Void _OnSortTypeClicked(FormulaSortType sortType) { }
	// RVA: 0x3dbb428 VA: 0x75963d3428
	private Void _OnFilterTypeClicked(FormulaFilterType filterType) { }
	// RVA: 0x3dbb4c8 VA: 0x75963d34c8
	public Void .ctor() { }
	// RVA: 0x3dbb574 VA: 0x75963d3574
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```