# BuildingStationSelectConfirmRoomListItemView

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `GameObject _curRoomPanel`

- `SimpleLayoutContent _curRoomContainer`

- `GameObject _changedRoomPanel`

- `SimpleLayoutContent _changedRoomList`

- `BuildingStationSelectConfirmRoomItemView _roomItemPrefab`

- `Text _textChangedRoomDesc`

- `Boolean m_isInited`

- `RoomAdapter m_adapter`

- `ChangedRoomGroupViewModel m_viewModel`

- `Int32 m_roomCount`


## Methods

- `Void _InitIfNot(SimpleLayoutContent)`

- `Void _RenderCurrentRoom()`

- `Void _RenderChangedRooms()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectConfirmRoomListItemView : DataBinder`1, IHotfixable
{
	private GameObject _curRoomPanel; // 0x20
	private SimpleLayoutContent _curRoomContainer; // 0x28
	private GameObject _changedRoomPanel; // 0x30
	private SimpleLayoutContent _changedRoomList; // 0x38
	private BuildingStationSelectConfirmRoomItemView _roomItemPrefab; // 0x40
	private Text _textChangedRoomDesc; // 0x48
	private Boolean m_isInited; // 0x50
	private RoomAdapter m_adapter; // 0x58
	private ChangedRoomGroupViewModel m_viewModel; // 0x60
	private Int32 m_roomCount; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RenderCurrentRoom; // 0x8
	private static DelegateBridge __Hotfix0__RenderChangedRooms; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3d9eda8 VA: 0x75963b6da8
	private Void _InitIfNot(SimpleLayoutContent content) { }
	// RVA: 0x3d9ef24 VA: 0x75963b6f24
	private Void _RenderCurrentRoom() { }
	// RVA: 0x3d9efb0 VA: 0x75963b6fb0
	public Void _RenderChangedRooms() { }
	// RVA: 0x3d9f03c VA: 0x75963b703c
	public override Void OnValueChanged(ChangedRoomGroupProperty property) { }
	// RVA: 0x3d9f238 VA: 0x75963b7238
	public Void .ctor() { }
}
```