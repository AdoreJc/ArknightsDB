# BuildingStationSelectCharItemView

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `BuildingStationSelectCharCard _cardPrefab`

- `RectTransform _cardContainer`

- `Text _textSelectIndex`

- `CanvasGroup _panelSelected`

- `TwoStateToggle _selectedMaskTypeTag`

- `RectTransform _pluginContainer`

- `BuildingStationSelectCharCard m_cardPanel`

- `StationCharViewModel m_viewModel`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeSwitch`

- `Int32 m_lastInst`

- `Int32 m_selectPluginPrefabId`

- `BuildingStationSelectMaskPlugin m_selectPluginInst`


## Properties

- `FadeSwitchTween securedFadeSwitch`


## Methods

- `FadeSwitchTween get_securedFadeSwitch()`

- `Void SetSelectionInfo(Boolean, Int32, Int32)`

- `Void Render(StationCharViewModel, CharSortType, StationSelectStateBeanInputType)`

- `Void RenderSelectPlugin(BuildingStationSelectMaskPlugin, StationSelectStateBean, Object)`

- `Void _InitIfNot(StationCharViewModel)`

- `Void _OnCardClick(Int32)`

- `Void _InitSelectPluginIfNot(BuildingStationSelectMaskPlugin, StationSelectStateBean, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectCharItemView : MonoBehaviour, IHotfixable
{
	private BuildingStationSelectCharCard _cardPrefab; // 0x18
	private RectTransform _cardContainer; // 0x20
	private Text _textSelectIndex; // 0x28
	private CanvasGroup _panelSelected; // 0x30
	private TwoStateToggle _selectedMaskTypeTag; // 0x38
	private RectTransform _pluginContainer; // 0x40
	private BuildingStationSelectCharCard m_cardPanel; // 0x48
	private StationCharViewModel m_viewModel; // 0x50
	private Boolean m_isInited; // 0x58
	private FadeSwitchTween m_fadeSwitch; // 0x60
	private Int32 m_lastInst; // 0x68
	private Int32 m_selectPluginPrefabId; // 0x6c
	private BuildingStationSelectMaskPlugin m_selectPluginInst; // 0x70
	public Action`1 onCharClicked; // 0x78
	private static DelegateBridge __Hotfix0_get_securedFadeSwitch; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectionInfo; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_RenderSelectPlugin; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnCardClick; // 0x28
	private static DelegateBridge __Hotfix0__InitSelectPluginIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private FadeSwitchTween securedFadeSwitch { get; }

	// RVA: 0x3d9c0cc VA: 0x75963b40cc
	private FadeSwitchTween get_securedFadeSwitch() { }
	// RVA: 0x3d99cdc VA: 0x75963b1cdc
	public Void SetSelectionInfo(Boolean isSelected, Int32 selectIndex, Int32 maxSelectCount) { }
	// RVA: 0x3d99b48 VA: 0x75963b1b48
	public Void Render(StationCharViewModel viewModel, CharSortType sortType, StationSelectStateBeanInputType selectType) { }
	// RVA: 0x3d99de4 VA: 0x75963b1de4
	public Void RenderSelectPlugin(BuildingStationSelectMaskPlugin maskPluginPrefab, StationSelectStateBean stateBean, Object context) { }
	// RVA: 0x3d9c194 VA: 0x75963b4194
	private Void _InitIfNot(StationCharViewModel viewModel) { }
	// RVA: 0x3d9c4ec VA: 0x75963b44ec
	private Void _OnCardClick(Int32 _) { }
	// RVA: 0x3d9c2ec VA: 0x75963b42ec
	private Void _InitSelectPluginIfNot(BuildingStationSelectMaskPlugin prefab, StationSelectStateBean stateBean, Object context) { }
	// RVA: 0x3d9c58c VA: 0x75963b458c
	public Void .ctor() { }
}
```