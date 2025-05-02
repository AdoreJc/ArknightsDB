# BuildingStationManageRoomStatusView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `UIColorGraphic _mainColorComp`

- `Text _textRoomName`

- `Text _textRoomNameIndex`

- `GameObject _panelOrderTarget`

- `Text _textOrderTarget`

- `GameObject _iconRoomStopped`

- `Text _textRoomIndex`

- `BuildingStationManageRoomQueueView _queueView`

- `BuildingStationManageRoomPreQueueEditView _queueEditViewPrefab`

- `Text _textQueueCount`

- `Transform _queueEditItemHolder`

- `ScrollRect _preQueueScrollRect`

- `GameObject _panelAddPreQueue`

- `Boolean m_isInited`

- `RoomSlotModel m_curRoomSlotModel`

- `BuildingModel m_curBuildingModel`


## Properties

- `BuildingCharSelectRoomConfig roomConfig`


## Methods

- `BuildingCharSelectRoomConfig get_roomConfig()`

- `Void _InitIfNot()`

- `Void ScrollToFirst()`

- `RoomStyle _GetCurRoomStyle()`

- `Void _LoadPreQueue(RoomStyle)`

- `BuildingStationManageRoomPreQueueEditView _CreateNewQueueItem()`

- `StationManageEditRoomQueueStructModel _GenQueueStructModel(RoomStyle, Boolean)`

- `StationManageEditRoomQueueStructModel _GenQueueStructModelByPreQueue(RoomSlotModel, List`1, RoomStyle)`

- `Void _UpdateRoomByRoomType()`

- `Void EventOnAddPreQueueClicked()`

- `Void _EventOnApplyQueueClicked(Int32)`

- `Void _EventOnDeleteQueueClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageRoomStatusView : DataBinder`1, IHotfixable
{
	private UIColorGraphic _mainColorComp; // 0x20
	private RoomStyle[] _roomStyles; // 0x28
	private Text _textRoomName; // 0x30
	private Text _textRoomNameIndex; // 0x38
	private GameObject _panelOrderTarget; // 0x40
	private Text _textOrderTarget; // 0x48
	private GameObject _iconRoomStopped; // 0x50
	private Text _textRoomIndex; // 0x58
	private BuildingStationManageRoomQueueView _queueView; // 0x60
	private BuildingStationManageRoomPreQueueEditView _queueEditViewPrefab; // 0x68
	private Text _textQueueCount; // 0x70
	private Transform _queueEditItemHolder; // 0x78
	private ScrollRect _preQueueScrollRect; // 0x80
	private GameObject _panelAddPreQueue; // 0x88
	public Action`2 onQueueCharClicked; // 0x90
	public Action`2 onPreQueueCharClicked; // 0x98
	public Action`2 onApplyPreQueueClicked; // 0xa0
	private Boolean m_isInited; // 0xa8
	private List`1 m_queueEditItems; // 0xb0
	private RoomSlotModel m_curRoomSlotModel; // 0xb8
	private BuildingModel m_curBuildingModel; // 0xc0
	private static DelegateBridge __Hotfix0_get_roomConfig; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_ScrollToFirst; // 0x18
	private static DelegateBridge __Hotfix0__GetCurRoomStyle; // 0x20
	private static DelegateBridge __Hotfix0__LoadPreQueue; // 0x28
	private static DelegateBridge __Hotfix0__CreateNewQueueItem; // 0x30
	private static DelegateBridge __Hotfix0__GenQueueStructModel; // 0x38
	private static DelegateBridge __Hotfix0__GenQueueStructModelByPreQueue; // 0x40
	private static DelegateBridge __Hotfix0__UpdateRoomByRoomType; // 0x48
	private static DelegateBridge __Hotfix0_EventOnAddPreQueueClicked; // 0x50
	private static DelegateBridge __Hotfix0__EventOnApplyQueueClicked; // 0x58
	private static DelegateBridge __Hotfix0__EventOnDeleteQueueClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public BuildingCharSelectRoomConfig roomConfig { get; }

	// RVA: 0x3db36b0 VA: 0x75963cb6b0
	public BuildingCharSelectRoomConfig get_roomConfig() { }
	// RVA: 0x3db3748 VA: 0x75963cb748
	private Void _InitIfNot() { }
	// RVA: 0x3db38c8 VA: 0x75963cb8c8
	public override Void OnValueChanged(StationManageEditQueueViewProp property) { }
	// RVA: 0x3da9310 VA: 0x75963c1310
	public Void ScrollToFirst() { }
	// RVA: 0x3db3cb0 VA: 0x75963cbcb0
	private RoomStyle _GetCurRoomStyle() { }
	// RVA: 0x3db4240 VA: 0x75963cc240
	private Void _LoadPreQueue(RoomStyle roomStyle) { }
	// RVA: 0x3db47e0 VA: 0x75963cc7e0
	private BuildingStationManageRoomPreQueueEditView _CreateNewQueueItem() { }
	// RVA: 0x3db3e18 VA: 0x75963cbe18
	private StationManageEditRoomQueueStructModel _GenQueueStructModel(RoomStyle roomStyle, Boolean isUpdateByMsg) { }
	// RVA: 0x3db4944 VA: 0x75963cc944
	private StationManageEditRoomQueueStructModel _GenQueueStructModelByPreQueue(RoomSlotModel roomSlotModel, List`1 preQueueList, RoomStyle roomStyle) { }
	// RVA: 0x3db3bdc VA: 0x75963cbbdc
	private Void _UpdateRoomByRoomType() { }
	// RVA: 0x3db4ef8 VA: 0x75963ccef8
	public Void EventOnAddPreQueueClicked() { }
	// RVA: 0x3db5050 VA: 0x75963cd050
	private Void _EventOnApplyQueueClicked(Int32 preQueueIndex) { }
	// RVA: 0x3db521c VA: 0x75963cd21c
	private Void _EventOnDeleteQueueClicked(Int32 preQueueIndex) { }
	// RVA: 0x3db5454 VA: 0x75963cd454
	public Void .ctor() { }
}
```