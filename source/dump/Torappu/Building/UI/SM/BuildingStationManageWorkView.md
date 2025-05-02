# BuildingStationManageWorkView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `BuildingSMStationNumView _workNumView`

- `BuildingSMRoomGroupListView _roomGroupList`

- `Text _roomCntText`

- `GameObject _panelNoSelectedRoom`

- `GameObject _panelHasSelectedRoom`

- `Text _roomName`

- `Text _roomIndex`

- `BuildingSMRoomTypeView _panelRoomType`

- `BuildingSMRoomInfoList _charInfoList`

- `GameObject _batchBtnActive`

- `GameObject _batchBtnInactive`

- `GameObject _stopCnt`

- `Text _stopCntText`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(StationManageWorkViewModel, StationRoomStructModel)`

- `Void OnBatchActiveClicked()`

- `Void OnBatchInactiveClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageWorkView : MonoBehaviour, IHotfixable
{
	private BuildingSMStationNumView _workNumView; // 0x18
	private BuildingSMRoomGroupListView _roomGroupList; // 0x20
	private Text _roomCntText; // 0x28
	private GameObject _panelNoSelectedRoom; // 0x30
	private GameObject _panelHasSelectedRoom; // 0x38
	private Text _roomName; // 0x40
	private Text _roomIndex; // 0x48
	private BuildingSMRoomTypeView _panelRoomType; // 0x50
	private BuildingSMRoomInfoList _charInfoList; // 0x58
	private GameObject _batchBtnActive; // 0x60
	private GameObject _batchBtnInactive; // 0x68
	private GameObject _stopCnt; // 0x70
	private Text _stopCntText; // 0x78
	private UIStateFinder m_stateFinder; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnBatchActiveClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnBatchInactiveClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3db18a8 VA: 0x75963c98a8
	public Void Render(StationManageWorkViewModel viewModel, StationRoomStructModel selectedRoom) { }
	// RVA: 0x3db1ce4 VA: 0x75963c9ce4
	public Void OnBatchActiveClicked() { }
	// RVA: 0x3db1d88 VA: 0x75963c9d88
	public Void OnBatchInactiveClicked() { }
	// RVA: 0x3db1e2c VA: 0x75963c9e2c
	public Void .ctor() { }
}
```