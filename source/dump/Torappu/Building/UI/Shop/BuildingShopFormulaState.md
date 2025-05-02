# BuildingShopFormulaState

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `BuildingShopFormulaSortBar _sortBar`

- `BuildingShopFormulaList _itemList`

- `SFormulaStateBean m_stateBean`


## Methods

- `Void Start()`

- `Void EventOnFilterBtnClicked()`

- `Void _OnJumpToSortFilterState(SFormulaSortFilterStateBean)`

- `Void _OnJumpBackFromSortFilterState(SFormulaSortFilterStateBean)`

- `Void _OnItemTypeClicked(FormulaItemType)`

- `Void _OnSortItemClicked(FormulaSortType)`

- `Void _OnFormulaClicked(SFormulaViewModel)`

- `Void <Start>b__6_0(GameObject)`

- `Void <RegisterFromDataListener>b__8_0(IStateBean)`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopFormulaState : PopupFloatState
{
	private PrefabInstHolder _topMenuHolder; // 0x70
	private BuildingShopFormulaSortBar _sortBar; // 0x78
	private BuildingShopFormulaList _itemList; // 0x80
	private BuildingShopFormulaCategoryTab[] _itemTabs; // 0x88
	private SFormulaStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_EventOnFilterBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToSortFilterState; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpBackFromSortFilterState; // 0x40
	private static DelegateBridge __Hotfix0__OnItemTypeClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnSortItemClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnFormulaClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x3dbb57c VA: 0x75963d357c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3dbb5e4 VA: 0x75963d35e4
	private Void Start() { }
	// RVA: 0x3dbb6a8 VA: 0x75963d36a8
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3dbb720 VA: 0x75963d3720
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x3dbb898 VA: 0x75963d3898
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3dbba10 VA: 0x75963d3a10
	protected override Void OnEnter() { }
	// RVA: 0x3dbbca4 VA: 0x75963d3ca4
	public Void EventOnFilterBtnClicked() { }
	// RVA: 0x3dbbdbc VA: 0x75963d3dbc
	private Void _OnJumpToSortFilterState(SFormulaSortFilterStateBean filterBean) { }
	// RVA: 0x3dbbe74 VA: 0x75963d3e74
	private Void _OnJumpBackFromSortFilterState(SFormulaSortFilterStateBean filterBean) { }
	// RVA: 0x3dbbf6c VA: 0x75963d3f6c
	private Void _OnItemTypeClicked(FormulaItemType formulaType) { }
	// RVA: 0x3dbbff4 VA: 0x75963d3ff4
	private Void _OnSortItemClicked(FormulaSortType sortType) { }
	// RVA: 0x3dbc07c VA: 0x75963d407c
	private Void _OnFormulaClicked(SFormulaViewModel selectedFormula) { }
	// RVA: 0x3dbc180 VA: 0x75963d4180
	public Void .ctor() { }
	// RVA: 0x3dbc22c VA: 0x75963d422c
	private Void <Start>b__6_0(GameObject obj) { }
	// RVA: 0x3dbc2e4 VA: 0x75963d42e4
	private Void <RegisterFromDataListener>b__8_0(IStateBean stateBean) { }
	// RVA: 0x3dbc364 VA: 0x75963d4364
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x3dbc3e4 VA: 0x75963d43e4
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3dbc3ec VA: 0x75963d43ec
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x3dbc3f4 VA: 0x75963d43f4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3dbc3fc VA: 0x75963d43fc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```