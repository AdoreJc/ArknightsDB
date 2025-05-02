# BuildingStationCharacterSortFilterPanelBinder

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `RectTransform _panelHolder`

- `UICharacterSortFilterPanel _panelPrefab`

- `CharacterFilterMessage _onFilterEvent`

- `String pageName`

- `Boolean m_isInited`

- `UICharacterSortFilterPanel m_sortFilterPanel`


## Methods

- `Void _InitIfNot()`

- `Void OnFilterPanelShow()`

- `Void OnFilterPanelHide()`

- `Void OnFilterPanelSwitch(Boolean)`

- `Void <_InitIfNot>b__7_0(CharacterFilterViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationCharacterSortFilterPanelBinder : DataBinder`1, IHotfixable
{
	private RectTransform _panelHolder; // 0x20
	private UICharacterSortFilterPanel _panelPrefab; // 0x28
	private CharacterFilterMessage _onFilterEvent; // 0x30
	public String pageName; // 0x38
	private Boolean m_isInited; // 0x40
	private UICharacterSortFilterPanel m_sortFilterPanel; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnFilterPanelShow; // 0x10
	private static DelegateBridge __Hotfix0_OnFilterPanelHide; // 0x18
	private static DelegateBridge __Hotfix0_OnFilterPanelSwitch; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3d978c0 VA: 0x75963af8c0
	public override Void OnValueChanged(StationCharGroupProperty property) { }
	// RVA: 0x3d979a0 VA: 0x75963af9a0
	private Void _InitIfNot() { }
	// RVA: 0x3d97b94 VA: 0x75963afb94
	public Void OnFilterPanelShow() { }
	// RVA: 0x3d97c50 VA: 0x75963afc50
	public Void OnFilterPanelHide() { }
	// RVA: 0x3d97b04 VA: 0x75963afb04
	public Void OnFilterPanelSwitch(Boolean isShow) { }
	// RVA: 0x3d97d0c VA: 0x75963afd0c
	public Void .ctor() { }
	// RVA: 0x3d97d9c VA: 0x75963afd9c
	private Void <_InitIfNot>b__7_0(CharacterFilterViewModel filterModel) { }
}
```