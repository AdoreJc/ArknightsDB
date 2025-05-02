# BuildingMessageLeaveBoardTopView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `BuildingUIRoomTitle _roomTitle`

- `CommonResourceBarItem _socialPointBar`

- `Text _textRoomName`

- `TwoStateToggle _roomNameTwoStateToggle`

- `CommonBasicRoomViewProperty m_basicRoomProperty`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _UpdatePlayerView(RoomSlotModel)`

- `Void _UpdateVisitorView()`

- `Void _UpdateRoomName(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardTopView : DataBinder`1, IHotfixable
{
	private BuildingUIRoomTitle _roomTitle; // 0x20
	private CommonResourceBarItem _socialPointBar; // 0x28
	private Text _textRoomName; // 0x30
	private TwoStateToggle _roomNameTwoStateToggle; // 0x38
	private CommonBasicRoomViewProperty m_basicRoomProperty; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdatePlayerView; // 0x10
	private static DelegateBridge __Hotfix0__UpdateVisitorView; // 0x18
	private static DelegateBridge __Hotfix0__UpdateRoomName; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3dc80a8 VA: 0x75963e00a8
	private Void _InitIfNot() { }
	// RVA: 0x3dc8150 VA: 0x75963e0150
	public override Void OnValueChanged(BuildingMessageLeaveBoardProperty property) { }
	// RVA: 0x3dc82f0 VA: 0x75963e02f0
	private Void _UpdatePlayerView(RoomSlotModel meetingRoom) { }
	// RVA: 0x3dc844c VA: 0x75963e044c
	private Void _UpdateVisitorView() { }
	// RVA: 0x3dc8594 VA: 0x75963e0594
	private Void _UpdateRoomName(String ownerName) { }
	// RVA: 0x3dc8664 VA: 0x75963e0664
	public Void .ctor() { }
}
```