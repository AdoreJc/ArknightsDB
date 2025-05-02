# BuildingStationManageDormView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `BuildingSMStationNumView _dormNumView`

- `BuildingSMRoomGroupListView _roomGroupList`

- `Text _roomCntText`

- `GameObject _panelNoSelectedRoom`

- `GameObject _panelHasSelectedRoom`

- `Text _roomName`

- `Text _roomIndex`

- `Text _comfort`

- `Text _ap`

- `Text _apBuff`

- `BuildingSMRoomInfoList _charInfoList`

- `GameObject _bottomBatchGroup`

- `GameObject _batchBtnActive`

- `GameObject _batchBtnInactive`

- `Text _tiredText`

- `Text _notFullext`

- `GameObject _editLockBtn`

- `CanvasGroup _editLockBkg`

- `CanvasGroup _editLockPanel`

- `Text _lockNumText`

- `GameObject _enterEditTrackPoint`

- `UIStateFinder m_stateFinder`

- `Boolean m_isInited`

- `FadeSwitchTween m_lockBkgTween`

- `FadeSwitchTween m_lockGroupTween`


## Methods

- `Void Render(StationManageRestViewModel, StationRoomStructModel)`

- `Void OnBatchActiveClicked()`

- `Void OnBatchInactiveClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageDormView : MonoBehaviour, IHotfixable
{
	private const Single LOCK_EDIT_BKG_ALPHA; // 0x0
	private BuildingSMStationNumView _dormNumView; // 0x18
	private BuildingSMRoomGroupListView _roomGroupList; // 0x20
	private Text _roomCntText; // 0x28
	private GameObject _panelNoSelectedRoom; // 0x30
	private GameObject _panelHasSelectedRoom; // 0x38
	private Text _roomName; // 0x40
	private Text _roomIndex; // 0x48
	private Text _comfort; // 0x50
	private Text _ap; // 0x58
	private Text _apBuff; // 0x60
	private BuildingSMRoomInfoList _charInfoList; // 0x68
	private GameObject _bottomBatchGroup; // 0x70
	private GameObject _batchBtnActive; // 0x78
	private GameObject _batchBtnInactive; // 0x80
	private Text _tiredText; // 0x88
	private Text _notFullext; // 0x90
	private GameObject _editLockBtn; // 0x98
	private CanvasGroup _editLockBkg; // 0xa0
	private CanvasGroup _editLockPanel; // 0xa8
	private Text _lockNumText; // 0xb0
	private GameObject _enterEditTrackPoint; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private Boolean m_isInited; // 0xd0
	private FadeSwitchTween m_lockBkgTween; // 0xd8
	private FadeSwitchTween m_lockGroupTween; // 0xe0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnBatchActiveClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnBatchInactiveClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3db0d9c VA: 0x75963c8d9c
	public Void Render(StationManageRestViewModel viewModel, StationRoomStructModel selectedRoom) { }
	// RVA: 0x3db1338 VA: 0x75963c9338
	public Void OnBatchActiveClicked() { }
	// RVA: 0x3db13dc VA: 0x75963c93dc
	public Void OnBatchInactiveClicked() { }
	// RVA: 0x3db11cc VA: 0x75963c91cc
	private Void _InitIfNot() { }
	// RVA: 0x3db1480 VA: 0x75963c9480
	public Void .ctor() { }
}
```