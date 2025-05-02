# DIYListViewState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYListViewStateBean _stateBean`

- `DIYFurnitureDetailPanel _furnitureDetailPanel`

- `DIYFurnitureExpandViewList _expandViewList`


## Methods

- `Boolean _OnInfoButtonPressed(DIYItemViewData)`

- `Void OnFilterPressed(DIYFilterType)`

- `Void OnSubTypePressed(FurnitureSubType)`

- `Void OnExpandPressed()`

- `Void OnListViewBackButtonPressed()`

- `Void OnThemeQuickSetup()`

- `Void EventOnSortPanelItemClicked(DiySortType, Int32)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYListViewState : DIYPopupState
{
	protected DIYListViewStateBean _stateBean; // 0x68
	private DIYFurnitureDetailPanel _furnitureDetailPanel; // 0x70
	private DIYFurnitureExpandViewList _expandViewList; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__OnInfoButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0_OnFilterPressed; // 0x18
	private static DelegateBridge __Hotfix0_OnSubTypePressed; // 0x20
	private static DelegateBridge __Hotfix0_OnExpandPressed; // 0x28
	private static DelegateBridge __Hotfix0_OnListViewBackButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0_OnThemeQuickSetup; // 0x38
	private static DelegateBridge __Hotfix0_EventOnSortPanelItemClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3831194 VA: 0x7595e49194
	public override IStateBean GetCacheBean() { }
	// RVA: 0x38311fc VA: 0x7595e491fc
	protected override Void OnEnter() { }
	// RVA: 0x383134c VA: 0x7595e4934c
	private Boolean _OnInfoButtonPressed(DIYItemViewData data) { }
	// RVA: 0x3831940 VA: 0x7595e49940
	public Void OnFilterPressed(DIYFilterType filterType) { }
	// RVA: 0x3831ac8 VA: 0x7595e49ac8
	public Void OnSubTypePressed(FurnitureSubType subType) { }
	// RVA: 0x3831c50 VA: 0x7595e49c50
	public Void OnExpandPressed() { }
	// RVA: 0x3831d64 VA: 0x7595e49d64
	public Void OnListViewBackButtonPressed() { }
	// RVA: 0x3831ff8 VA: 0x7595e49ff8
	public Void OnThemeQuickSetup() { }
	// RVA: 0x3832114 VA: 0x7595e4a114
	public Void EventOnSortPanelItemClicked(DiySortType diyUIType, Int32 index) { }
	// RVA: 0x383229c VA: 0x7595e4a29c
	public Void .ctor() { }
	// RVA: 0x3832308 VA: 0x7595e4a308
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```