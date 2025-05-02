# BuildingManufactFormulaSortFilterState

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `MFormulaSortFilterStateBean m_stateBean`


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
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactFormulaSortFilterState : PopupFloatState
{
	private BuildingManufactFormulaFilterItem[] _filterItems; // 0x70
	private BuildingManufactFormulaSortItem[] _sortItems; // 0x78
	private MFormulaSortFilterStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__RefreshSorts; // 0x10
	private static DelegateBridge __Hotfix0__RefreshFilters; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnSortTypeClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnFilterTypeClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3e04c44 VA: 0x759641cc44
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3e04cac VA: 0x759641ccac
	protected override Void OnEnter() { }
	// RVA: 0x3e04f78 VA: 0x759641cf78
	private Void _RefreshSorts() { }
	// RVA: 0x3e04e90 VA: 0x759641ce90
	private Void _RefreshFilters() { }
	// RVA: 0x3e05078 VA: 0x759641d078
	public Void EventOnConfirmClicked() { }
	// RVA: 0x3e05100 VA: 0x759641d100
	public Void EventOnCancelClicked() { }
	// RVA: 0x3e05174 VA: 0x759641d174
	private Void _OnSortTypeClicked(FormulaSortType sortType) { }
	// RVA: 0x3e0521c VA: 0x759641d21c
	private Void _OnFilterTypeClicked(FormulaFilterType filterType) { }
	// RVA: 0x3e052bc VA: 0x759641d2bc
	public Void .ctor() { }
	// RVA: 0x3e05368 VA: 0x759641d368
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```