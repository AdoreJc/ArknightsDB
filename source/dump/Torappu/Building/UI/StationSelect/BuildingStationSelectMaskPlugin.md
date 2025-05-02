# BuildingStationSelectMaskPlugin

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `Text _textName`

- `GameObject _isAssistantOnWork`

- `GameObject _isAssistantNotWork`

- `GameObject _isSelected`

- `GameObject _panelStationed`

- `Image _imageStationIcon`

- `Image _imageStationBg`

- `Text _textRoomName`

- `RectTransform _panelInvalid`

- `StationSelectStateBean m_stationSelectBean`

- `IBuildingSelectController m_buildingSelectController`


## Properties

- `BuildingCharSelectRoomConfig roomConfig`


## Methods

- `BuildingCharSelectRoomConfig get_roomConfig()`

- `Void _RenderStationed(StationCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectMaskPlugin : BuildingStationSelectCardMaskPlugin
{
	private Text _textName; // 0x18
	private GameObject _isAssistantOnWork; // 0x20
	private GameObject _isAssistantNotWork; // 0x28
	private GameObject _isSelected; // 0x30
	private GameObject _panelStationed; // 0x38
	private Image _imageStationIcon; // 0x40
	private Image _imageStationBg; // 0x48
	private Text _textRoomName; // 0x50
	private RectTransform _panelInvalid; // 0x58
	private StationSelectStateBean m_stationSelectBean; // 0x60
	private IBuildingSelectController m_buildingSelectController; // 0x68
	private static DelegateBridge __Hotfix0_get_roomConfig; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderStationed; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public BuildingCharSelectRoomConfig roomConfig { get; }

	// RVA: 0x3d9f6a0 VA: 0x75963b76a0
	public BuildingCharSelectRoomConfig get_roomConfig() { }
	// RVA: 0x3d9f738 VA: 0x75963b7738
	public override Void Init(BuildingStationSelectCharItemView cardView, StationSelectStateBean stateBean, Object context) { }
	// RVA: 0x3d9f814 VA: 0x75963b7814
	public override Void Render(StationCharViewModel cardModel) { }
	// RVA: 0x3d9fef0 VA: 0x75963b7ef0
	private Void _RenderStationed(StationCharViewModel exclusiveCharModel) { }
	// RVA: 0x3da024c VA: 0x75963b824c
	public Void .ctor() { }
}
```