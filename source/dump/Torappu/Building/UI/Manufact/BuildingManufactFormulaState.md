# BuildingManufactFormulaState

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingManufactFormulaSortBar _sortBar`

- `BuildingManufactFormulaList _itemList`

- `MFormulaStateBean m_stateBean`


## Methods

- `Void Start()`

- `Void EventOnFilterBtnClicked()`

- `Void _OnJumpToSortFilterState(MFormulaSortFilterStateBean)`

- `Void _OnJumpBackFromSortFilterState(MFormulaSortFilterStateBean)`

- `Void _OnItemTypeClicked(FormulaItemType)`

- `Void _OnSortItemClicked(FormulaSortType)`

- `Void _OnFormulaClicked(MFormulaViewModel)`

- `Void <Start>b__6_0(GameObject)`

- `Void <RegisterFromDataListener>b__8_0(IStateBean)`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactFormulaState : PopupFloatState
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private BuildingManufactFormulaSortBar _sortBar; // 0x78
	private BuildingManufactFormulaList _itemList; // 0x80
	private BuildingManufactFormulaCategoryTab[] _itemTabs; // 0x88
	private MFormulaStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_EventOnFilterBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToSortFilterState; // 0x40
	private static DelegateBridge __Hotfix0__OnJumpBackFromSortFilterState; // 0x48
	private static DelegateBridge __Hotfix0__OnItemTypeClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnSortItemClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnFormulaClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x3e05370 VA: 0x759641d370
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3e053d8 VA: 0x759641d3d8
	private Void Start() { }
	// RVA: 0x3e0549c VA: 0x759641d49c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3e05514 VA: 0x759641d514
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x3e0568c VA: 0x759641d68c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3e05804 VA: 0x759641d804
	protected override Void OnEnter() { }
	// RVA: 0x3e05a98 VA: 0x759641da98
	protected override Void OnResume() { }
	// RVA: 0x3e05b38 VA: 0x759641db38
	public Void EventOnFilterBtnClicked() { }
	// RVA: 0x3e05c50 VA: 0x759641dc50
	private Void _OnJumpToSortFilterState(MFormulaSortFilterStateBean filterBean) { }
	// RVA: 0x3e05d08 VA: 0x759641dd08
	private Void _OnJumpBackFromSortFilterState(MFormulaSortFilterStateBean filterBean) { }
	// RVA: 0x3e05e00 VA: 0x759641de00
	private Void _OnItemTypeClicked(FormulaItemType formulaType) { }
	// RVA: 0x3e05e88 VA: 0x759641de88
	private Void _OnSortItemClicked(FormulaSortType sortType) { }
	// RVA: 0x3e05f10 VA: 0x759641df10
	private Void _OnFormulaClicked(MFormulaViewModel selectedFormula) { }
	// RVA: 0x3e06010 VA: 0x759641e010
	public Void .ctor() { }
	// RVA: 0x3e060bc VA: 0x759641e0bc
	private Void <Start>b__6_0(GameObject obj) { }
	// RVA: 0x3e06174 VA: 0x759641e174
	private Void <RegisterFromDataListener>b__8_0(IStateBean stateBean) { }
	// RVA: 0x3e061f4 VA: 0x759641e1f4
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x3e06274 VA: 0x759641e274
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3e0627c VA: 0x759641e27c
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x3e06284 VA: 0x759641e284
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3e0628c VA: 0x759641e28c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e06294 VA: 0x759641e294
	private Void <>xLuaBaseProxy_OnResume() { }
}
```