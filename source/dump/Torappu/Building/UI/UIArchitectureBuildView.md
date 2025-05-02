# UIArchitectureBuildView

**Namespace:** `Torappu.Building.UI`


## Fields

- `GameObject _roomPanelProtoElectric`

- `RectTransform _listRoot`

- `UIArchitectureRoomListLocator _locator`

- `GameObject _leftButton`

- `GameObject _rightButton`

- `UIRoomIconSpriteHub m_roomIconSpriteHub`

- `BuildingLaborViewModel m_laborModel`

- `Int32 m_curIndex`


## Properties

- `RoomPanelInfo currentRoomPanelInfo`

- `UIArchitectureBuildRoomPanel currentRoomPanel`


## Methods

- `RoomPanelInfo get_currentRoomPanelInfo()`

- `UIArchitectureBuildRoomPanel get_currentRoomPanel()`

- `UIRoomIconSpriteHub _GetIconSpriteHub()`

- `Void _SetupPanel(GameObject, String, RoomData, RoomLevelConditionCheckingResult)`

- `Void SetRoomListLocateIndex(Int32, Boolean)`

- `Void OnLeftButtonPressed()`

- `Void OnRightButtonPressed()`

- `Void <DoSetup>b__20_0(RoomData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureBuildView : UIArchitectureBaseView`1
{
	private GameObject _roomPanelProtoElectric; // 0x48
	private RectTransform _listRoot; // 0x50
	private UIArchitectureRoomListLocator _locator; // 0x58
	private GameObject _leftButton; // 0x60
	private GameObject _rightButton; // 0x68
	private UIRoomIconSpriteHub m_roomIconSpriteHub; // 0x70
	private List`1 m_roomPanelInfos; // 0x78
	private List`1 m_roomPanels; // 0x80
	private BuildingLaborViewModel m_laborModel; // 0x88
	private Int32 m_curIndex; // 0x90
	private static DelegateBridge __Hotfix0_get_currentRoomPanelInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_currentRoomPanel; // 0x8
	private static DelegateBridge __Hotfix0__GetIconSpriteHub; // 0x10
	private static DelegateBridge __Hotfix0__SetupPanel; // 0x18
	private static DelegateBridge __Hotfix0_SetRoomListLocateIndex; // 0x20
	private static DelegateBridge __Hotfix0__RoomPanelInfoComparasion; // 0x28
	private static DelegateBridge __Hotfix0_DoSetup; // 0x30
	private static DelegateBridge __Hotfix0_OnLeftButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0_OnRightButtonPressed; // 0x40
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public RoomPanelInfo currentRoomPanelInfo { get; }
	public UIArchitectureBuildRoomPanel currentRoomPanel { get; }

	// RVA: 0x3d4530c VA: 0x759635d30c
	public RoomPanelInfo get_currentRoomPanelInfo() { }
	// RVA: 0x3d453c4 VA: 0x759635d3c4
	public UIArchitectureBuildRoomPanel get_currentRoomPanel() { }
	// RVA: 0x3d4547c VA: 0x759635d47c
	private UIRoomIconSpriteHub _GetIconSpriteHub() { }
	// RVA: 0x3d455f0 VA: 0x759635d5f0
	private Void _SetupPanel(GameObject inst, String slotId, RoomData roomData, RoomLevelConditionCheckingResult checkingResult) { }
	// RVA: 0x3d45f84 VA: 0x759635df84
	private Void SetRoomListLocateIndex(Int32 index, Boolean easeMove) { }
	// RVA: 0x3d46178 VA: 0x759635e178
	private static Int32 _RoomPanelInfoComparasion(RoomPanelInfo v0, RoomPanelInfo v1) { }
	// RVA: 0x3d462c0 VA: 0x759635e2c0
	protected override Void DoSetup(Argument arg) { }
	// RVA: 0x3d46a74 VA: 0x759635ea74
	public Void OnLeftButtonPressed() { }
	// RVA: 0x3d46ae8 VA: 0x759635eae8
	public Void OnRightButtonPressed() { }
	// RVA: 0x3d46b5c VA: 0x759635eb5c
	protected override Void OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d46cac VA: 0x759635ecac
	public Void .ctor() { }
	// RVA: 0x3d46e24 VA: 0x759635ee24
	private Void <DoSetup>b__20_0(RoomData roomData) { }
}
```