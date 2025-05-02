# BuildingModel

**Namespace:** `Torappu.Building`


## Fields

- `GridPosition m_buildingBound`

- `BuildingLaborViewModel m_sharedLaborModel`

- `RoomSlotGraph slotGraph`

- `PlayerBuildingRoom <playerRooms>k__BackingField`

- `PlayerBuildingLabor <playerLabor>k__BackingField`

- `BuildingFuncFurnitureModel funcFurnModel`

- `Int32 <curElectric>k__BackingField`

- `Int32 <maxElectric>k__BackingField`

- `String <layoutId>k__BackingField`

- `RoomSlotModel <controlRoom>k__BackingField`

- `RoomSlotModel <meetingRoom>k__BackingField`


## Properties

- `PlayerBuildingRoom playerRooms`

- `PlayerBuildingLabor playerLabor`

- `Int32 currentLabor`

- `PlayerBuildingTraining playerBuildingTraining`

- `String playerBuildingTrainingSlotId`

- `PlayerBuildingHire playerBuildingHiring`

- `String playerBuildingHiringSlotId`

- `PlayerBuildingMeeting playerMeetingRoom`

- `Int32 curElectric`

- `Int32 maxElectric`

- `String layoutId`

- `RoomSlotModel controlRoom`

- `RoomSlotModel meetingRoom`


## Methods

- `Void set_assistants(List`1)`

- `Void set_visitors(List`1)`

- `PlayerBuildingRoom get_playerRooms()`

- `Void set_playerRooms(PlayerBuildingRoom)`

- `Void set_playerChars(Dictionary`2)`

- `PlayerBuildingLabor get_playerLabor()`

- `Void set_playerLabor(PlayerBuildingLabor)`

- `Void set_playerFurnitureInfo(Dictionary`2)`

- `Int32 get_currentLabor()`

- `PlayerBuildingTraining get_playerBuildingTraining()`

- `String get_playerBuildingTrainingSlotId()`

- `PlayerBuildingHire get_playerBuildingHiring()`

- `String get_playerBuildingHiringSlotId()`

- `PlayerBuildingMeeting get_playerMeetingRoom()`

- `Int32 get_curElectric()`

- `Void set_curElectric(Int32)`

- `Int32 get_maxElectric()`

- `Void set_maxElectric(Int32)`

- `String get_layoutId()`

- `Void set_layoutId(String)`

- `RoomSlotModel get_controlRoom()`

- `Void set_controlRoom(RoomSlotModel)`

- `RoomSlotModel get_meetingRoom()`

- `Void set_meetingRoom(RoomSlotModel)`

- `Void LoadDataForCurPlayer(LayoutData, PlayerBuilding)`

- `Void LoadDataForVisiting(LayoutData, VisitBuildingResponse)`

- `Void UpdateData(PlayerBuilding)`

- `RoomSlotModel GetSlotById(String)`

- `BuildingCharModel GetBuildingCharByInstId(Int32)`

- `Boolean CheckOtherRoomChangedByInstId(String, List`1)`

- `Boolean CheckOtherRoomChanged(String, List`1)`

- `Boolean _CheckSpCharRoomChanged(Int32, String)`

- `Boolean CheckOtherRoomChangedByAssist(Int32)`

- `LeftOrRight GetRoomSide(RoomSlotModel)`

- `StoreyViewModel GetStoreyByIndex(Int32)`

- `Boolean CheckIfLaborAccelUnlocked()`

- `BuildingAssistantModel GetBuildingAssitant(Int32)`

- `Int32 GetBuildingAssistantIndex(Int32)`

- `Void UpdateRecentVisitorsCurPlayer(BuildingGetRecentVisitorsResponse)`

- `Void _UpdateRecentVisitorsForVisiting(VisitBuildingResponse, RoomSlotModel)`

- `BuildingVisitorModel FindRecentVisitor(String)`

- `Void _SortSlotsLayout()`

- `BuildingPrivateOwnerModel LoadPrivateOwnerModelBySlot(String)`

- `Void _UpdatePlayerDataPre(PlayerBuilding)`

- `Void _UpdatePlayerDataPre(VisitBuildingResponse)`

- `Void _UpdatePlayerDataPost()`

- `Void _InitDiyRoomInfo()`

- `Int32 QueryRoomIndex(String)`

- `String QueryRoomSlotId(Int32)`

- `Void _InitRoomStoreyInfo()`

- `Void _InitSameRoomIndex()`

- `Void _LoadElectricInfo()`

- `Void _LoadAssistants()`

- `Void _UpdatePrivateOwners()`

- `Void _LoadPrivateOwners()`

- `Void _RefreshRooms(RoomType[])`

- `Boolean CallBackPrivateDormOwner(String)`

- `Boolean CallBackPrivateDormOwner(Int32)`

- `Boolean IsVCharStayedInPrivateDorm(Int32)`

- `Void _RefreshVCharStayedRoom()`

- `Boolean IsVCharStayedRoomValid(Int32, String)`

- `Void RefreshVCharForceStayedRoom(Int32, String)`

- `Void RemoveForceStayedRoom(List`1)`

- `Boolean IsVCharPrivateOwner(Int32)`

- `Void OnReset()`

- `Void OnTick(FP)`

- `Void OnStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingModel : IBlackboard, IHotfixable
{
	private const Int32 MAX_MEETING_VISITOR_NUM; // 0x0
	private Dictionary`2 m_slotSearchTable; // 0x10
	private List`1 m_diySlots; // 0x18
	private GridPosition m_buildingBound; // 0x20
	private BuildingLaborViewModel m_sharedLaborModel; // 0x28
	private Dictionary`2 m_buildingCharSearchTable; // 0x30
	public RoomSlotGraph slotGraph; // 0x38
	public List`1 layout; // 0x40
	public ListDict`2 storeys; // 0x48
	private List`1 <assistants>k__BackingField; // 0x50
	private List`1 m_privateOwners; // 0x58
	private ListDict`2 m_privateOwnerOriginSlots; // 0x60
	private ListDict`2 m_vcharForceStayedRoom; // 0x68
	private ListDict`2 m_vcharStayedRoom; // 0x70
	private List`1 <visitors>k__BackingField; // 0x78
	private PlayerBuildingRoom <playerRooms>k__BackingField; // 0x80
	private Dictionary`2 <playerChars>k__BackingField; // 0x88
	private List`1 m_playerAssist; // 0x90
	private PlayerBuildingLabor <playerLabor>k__BackingField; // 0x98
	private Dictionary`2 <playerFurnitureInfo>k__BackingField; // 0xa0
	public BuildingFuncFurnitureModel funcFurnModel; // 0xa8
	private Int32 <curElectric>k__BackingField; // 0xb0
	private Int32 <maxElectric>k__BackingField; // 0xb4
	private String <layoutId>k__BackingField; // 0xb8
	private RoomSlotModel <controlRoom>k__BackingField; // 0xc0
	private RoomSlotModel <meetingRoom>k__BackingField; // 0xc8
	private static DelegateBridge __Hotfix0_get_assistants; // 0x0
	private static DelegateBridge __Hotfix0_set_assistants; // 0x8
	private static DelegateBridge __Hotfix0_get_visitors; // 0x10
	private static DelegateBridge __Hotfix0_set_visitors; // 0x18
	private static DelegateBridge __Hotfix0_get_playerRooms; // 0x20
	private static DelegateBridge __Hotfix0_set_playerRooms; // 0x28
	private static DelegateBridge __Hotfix0_get_playerChars; // 0x30
	private static DelegateBridge __Hotfix0_set_playerChars; // 0x38
	private static DelegateBridge __Hotfix0_get_playerLabor; // 0x40
	private static DelegateBridge __Hotfix0_set_playerLabor; // 0x48
	private static DelegateBridge __Hotfix0_get_playerFurnitureInfo; // 0x50
	private static DelegateBridge __Hotfix0_set_playerFurnitureInfo; // 0x58
	private static DelegateBridge __Hotfix0_get_currentLabor; // 0x60
	private static DelegateBridge __Hotfix0_get_playerBuildingTraining; // 0x68
	private static DelegateBridge __Hotfix0_get_playerBuildingTrainingSlotId; // 0x70
	private static DelegateBridge __Hotfix0_get_playerBuildingHiring; // 0x78
	private static DelegateBridge __Hotfix0_get_playerBuildingHiringSlotId; // 0x80
	private static DelegateBridge __Hotfix0_get_privateOwners; // 0x88
	private static DelegateBridge __Hotfix0_get_privateOwnerSlots; // 0x90
	private static DelegateBridge __Hotfix0_get_playerMeetingRoom; // 0x98
	private static DelegateBridge __Hotfix0_get_curElectric; // 0xa0
	private static DelegateBridge __Hotfix0_set_curElectric; // 0xa8
	private static DelegateBridge __Hotfix0_get_maxElectric; // 0xb0
	private static DelegateBridge __Hotfix0_set_maxElectric; // 0xb8
	private static DelegateBridge __Hotfix0_get_layoutId; // 0xc0
	private static DelegateBridge __Hotfix0_set_layoutId; // 0xc8
	private static DelegateBridge __Hotfix0_get_controlRoom; // 0xd0
	private static DelegateBridge __Hotfix0_set_controlRoom; // 0xd8
	private static DelegateBridge __Hotfix0_get_meetingRoom; // 0xe0
	private static DelegateBridge __Hotfix0_set_meetingRoom; // 0xe8
	private static DelegateBridge __Hotfix0_LoadDataForCurPlayer; // 0xf0
	private static DelegateBridge __Hotfix0_LoadDataForVisiting; // 0xf8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x100
	private static DelegateBridge __Hotfix0_GetSlotById; // 0x108
	private static DelegateBridge __Hotfix0_GetBuildingCharByInstId; // 0x110
	private static DelegateBridge __Hotfix0_CheckOtherRoomChangedByInstId; // 0x118
	private static DelegateBridge __Hotfix0_CheckOtherRoomChanged; // 0x120
	private static DelegateBridge __Hotfix0__CheckSpCharRoomChanged; // 0x128
	private static DelegateBridge __Hotfix0_CheckOtherRoomChangedByAssist; // 0x130
	private static DelegateBridge __Hotfix0_GetRoomSide; // 0x138
	private static DelegateBridge __Hotfix0_GetStoreyByIndex; // 0x140
	private static DelegateBridge __Hotfix0_CheckIfLaborAccelUnlocked; // 0x148
	private static DelegateBridge __Hotfix0_GetBuildingAssitant; // 0x150
	private static DelegateBridge __Hotfix0_GetBuildingAssistantIndex; // 0x158
	private static DelegateBridge __Hotfix0_UpdateRecentVisitorsCurPlayer; // 0x160
	private static DelegateBridge __Hotfix0__UpdateRecentVisitorsForVisiting; // 0x168
	private static DelegateBridge __Hotfix0_FindRecentVisitor; // 0x170
	private static DelegateBridge __Hotfix0__SortSlotsLayout; // 0x178
	private static DelegateBridge __Hotfix0_LoadPrivateOwnerModelBySlot; // 0x180
	private static DelegateBridge __Hotfix0__UpdatePlayerDataPre; // 0x188
	private static DelegateBridge __Hotfix1__UpdatePlayerDataPre; // 0x190
	private static DelegateBridge __Hotfix0__UpdatePlayerDataPost; // 0x198
	private static DelegateBridge __Hotfix0__InitDiyRoomInfo; // 0x1a0
	private static DelegateBridge __Hotfix0_QueryRoomIndex; // 0x1a8
	private static DelegateBridge __Hotfix0_QueryRoomSlotId; // 0x1b0
	private static DelegateBridge __Hotfix0__InitRoomStoreyInfo; // 0x1b8
	private static DelegateBridge __Hotfix0__InitSameRoomIndex; // 0x1c0
	private static DelegateBridge __Hotfix0__LoadElectricInfo; // 0x1c8
	private static DelegateBridge __Hotfix0__LoadAssistants; // 0x1d0
	private static DelegateBridge __Hotfix0__UpdatePrivateOwners; // 0x1d8
	private static DelegateBridge __Hotfix0__LoadPrivateOwners; // 0x1e0
	private static DelegateBridge __Hotfix0__RefreshRooms; // 0x1e8
	private static DelegateBridge __Hotfix0_CallBackPrivateDormOwner; // 0x1f0
	private static DelegateBridge __Hotfix1_CallBackPrivateDormOwner; // 0x1f8
	private static DelegateBridge __Hotfix0_IsVCharStayedInPrivateDorm; // 0x200
	private static DelegateBridge __Hotfix0__RefreshVCharStayedRoom; // 0x208
	private static DelegateBridge __Hotfix0_IsVCharStayedRoomValid; // 0x210
	private static DelegateBridge __Hotfix0_RefreshVCharForceStayedRoom; // 0x218
	private static DelegateBridge __Hotfix0_RemoveForceStayedRoom; // 0x220
	private static DelegateBridge __Hotfix0_IsVCharPrivateOwner; // 0x228
	private static DelegateBridge __Hotfix0_OnReset; // 0x230
	private static DelegateBridge __Hotfix0_OnTick; // 0x238
	private static DelegateBridge __Hotfix0_OnStop; // 0x240
	private static DelegateBridge _c__Hotfix0_ctor; // 0x248

	public List`1 assistants { get; set; }
	public List`1 visitors { get; set; }
	public PlayerBuildingRoom playerRooms { get; set; }
	public Dictionary`2 playerChars { get; set; }
	public PlayerBuildingLabor playerLabor { get; set; }
	public Dictionary`2 playerFurnitureInfo { get; set; }
	public Int32 currentLabor { get; }
	public PlayerBuildingTraining playerBuildingTraining { get; }
	public String playerBuildingTrainingSlotId { get; }
	public PlayerBuildingHire playerBuildingHiring { get; }
	public String playerBuildingHiringSlotId { get; }
	public List`1 privateOwners { get; }
	public ListDict`2 privateOwnerSlots { get; }
	public PlayerBuildingMeeting playerMeetingRoom { get; }
	public Int32 curElectric { get; set; }
	public Int32 maxElectric { get; set; }
	public String layoutId { get; set; }
	public RoomSlotModel controlRoom { get; set; }
	public RoomSlotModel meetingRoom { get; set; }

	// RVA: 0x37899c0 VA: 0x7595da19c0
	public List`1 get_assistants() { }
	// RVA: 0x3789a28 VA: 0x7595da1a28
	private Void set_assistants(List`1 value) { }
	// RVA: 0x3789aac VA: 0x7595da1aac
	public List`1 get_visitors() { }
	// RVA: 0x3789b14 VA: 0x7595da1b14
	private Void set_visitors(List`1 value) { }
	// RVA: 0x3789b98 VA: 0x7595da1b98
	public PlayerBuildingRoom get_playerRooms() { }
	// RVA: 0x3789c00 VA: 0x7595da1c00
	private Void set_playerRooms(PlayerBuildingRoom value) { }
	// RVA: 0x3789c84 VA: 0x7595da1c84
	public Dictionary`2 get_playerChars() { }
	// RVA: 0x3789cec VA: 0x7595da1cec
	private Void set_playerChars(Dictionary`2 value) { }
	// RVA: 0x37896a0 VA: 0x7595da16a0
	public PlayerBuildingLabor get_playerLabor() { }
	// RVA: 0x3789d70 VA: 0x7595da1d70
	private Void set_playerLabor(PlayerBuildingLabor value) { }
	// RVA: 0x3789df4 VA: 0x7595da1df4
	public Dictionary`2 get_playerFurnitureInfo() { }
	// RVA: 0x3789e5c VA: 0x7595da1e5c
	private Void set_playerFurnitureInfo(Dictionary`2 value) { }
	// RVA: 0x3789ee0 VA: 0x7595da1ee0
	public Int32 get_currentLabor() { }
	// RVA: 0x3789f5c VA: 0x7595da1f5c
	public PlayerBuildingTraining get_playerBuildingTraining() { }
	// RVA: 0x3789fc0 VA: 0x7595da1fc0
	public String get_playerBuildingTrainingSlotId() { }
	// RVA: 0x378a024 VA: 0x7595da2024
	public PlayerBuildingHire get_playerBuildingHiring() { }
	// RVA: 0x378a088 VA: 0x7595da2088
	public String get_playerBuildingHiringSlotId() { }
	// RVA: 0x378a0ec VA: 0x7595da20ec
	public List`1 get_privateOwners() { }
	// RVA: 0x378a154 VA: 0x7595da2154
	public ListDict`2 get_privateOwnerSlots() { }
	// RVA: 0x378a1bc VA: 0x7595da21bc
	public PlayerBuildingMeeting get_playerMeetingRoom() { }
	// RVA: 0x378a2f0 VA: 0x7595da22f0
	public Int32 get_curElectric() { }
	// RVA: 0x378a358 VA: 0x7595da2358
	private Void set_curElectric(Int32 value) { }
	// RVA: 0x378a3d4 VA: 0x7595da23d4
	public Int32 get_maxElectric() { }
	// RVA: 0x378a43c VA: 0x7595da243c
	private Void set_maxElectric(Int32 value) { }
	// RVA: 0x378a4b8 VA: 0x7595da24b8
	public String get_layoutId() { }
	// RVA: 0x378a520 VA: 0x7595da2520
	private Void set_layoutId(String value) { }
	// RVA: 0x378a5a4 VA: 0x7595da25a4
	public RoomSlotModel get_controlRoom() { }
	// RVA: 0x378a60c VA: 0x7595da260c
	private Void set_controlRoom(RoomSlotModel value) { }
	// RVA: 0x378a690 VA: 0x7595da2690
	public RoomSlotModel get_meetingRoom() { }
	// RVA: 0x378a6f8 VA: 0x7595da26f8
	private Void set_meetingRoom(RoomSlotModel value) { }
	// RVA: 0x378a77c VA: 0x7595da277c
	public Void LoadDataForCurPlayer(LayoutData data, PlayerBuilding playerBuilding) { }
	// RVA: 0x378b9fc VA: 0x7595da39fc
	public Void LoadDataForVisiting(LayoutData data, VisitBuildingResponse response) { }
	// RVA: 0x378c500 VA: 0x7595da4500
	public Void UpdateData(PlayerBuilding playerBuilding) { }
	// RVA: 0x378cca4 VA: 0x7595da4ca4
	public RoomSlotModel GetSlotById(String slotId) { }
	// RVA: 0x378cd68 VA: 0x7595da4d68
	public BuildingCharModel GetBuildingCharByInstId(Int32 instId) { }
	// RVA: 0x378cea0 VA: 0x7595da4ea0
	public Boolean CheckOtherRoomChangedByInstId(String slotId, List`1 instIds) { }
	// RVA: 0x378d30c VA: 0x7595da530c
	public Boolean CheckOtherRoomChanged(String slotId, List`1 instModels) { }
	// RVA: 0x378d090 VA: 0x7595da5090
	private Boolean _CheckSpCharRoomChanged(Int32 instId, String slotId) { }
	// RVA: 0x378d710 VA: 0x7595da5710
	public Boolean CheckOtherRoomChangedByAssist(Int32 instId) { }
	// RVA: 0x378d980 VA: 0x7595da5980
	public LeftOrRight GetRoomSide(RoomSlotModel slot) { }
	// RVA: 0x378dac8 VA: 0x7595da5ac8
	public StoreyViewModel GetStoreyByIndex(Int32 index) { }
	// RVA: 0x378db7c VA: 0x7595da5b7c
	public Boolean CheckIfLaborAccelUnlocked() { }
	// RVA: 0x378d538 VA: 0x7595da5538
	public BuildingAssistantModel GetBuildingAssitant(Int32 charInstId) { }
	// RVA: 0x378dc90 VA: 0x7595da5c90
	public Int32 GetBuildingAssistantIndex(Int32 charInstId) { }
	// RVA: 0x378dd9c VA: 0x7595da5d9c
	public Void UpdateRecentVisitorsCurPlayer(BuildingGetRecentVisitorsResponse response) { }
	// RVA: 0x378c068 VA: 0x7595da4068
	private Void _UpdateRecentVisitorsForVisiting(VisitBuildingResponse response, RoomSlotModel meetingSlot) { }
	// RVA: 0x378e1d0 VA: 0x7595da61d0
	public BuildingVisitorModel FindRecentVisitor(String uid) { }
	// RVA: 0x378b0b8 VA: 0x7595da30b8
	private Void _SortSlotsLayout() { }
	// RVA: 0x378e2e8 VA: 0x7595da62e8
	public BuildingPrivateOwnerModel LoadPrivateOwnerModelBySlot(String slotId) { }
	// RVA: 0x378ad50 VA: 0x7595da2d50
	private Void _UpdatePlayerDataPre(PlayerBuilding playerBuilding) { }
	// RVA: 0x378be78 VA: 0x7595da3e78
	private Void _UpdatePlayerDataPre(VisitBuildingResponse response) { }
	// RVA: 0x378b95c VA: 0x7595da395c
	private Void _UpdatePlayerDataPost() { }
	// RVA: 0x378b1fc VA: 0x7595da31fc
	private Void _InitDiyRoomInfo() { }
	// RVA: 0x378f4f0 VA: 0x7595da74f0
	public Int32 QueryRoomIndex(String roomId) { }
	// RVA: 0x378f6fc VA: 0x7595da76fc
	public String QueryRoomSlotId(Int32 index) { }
	// RVA: 0x378b564 VA: 0x7595da3564
	private Void _InitRoomStoreyInfo() { }
	// RVA: 0x378b3b4 VA: 0x7595da33b4
	private Void _InitSameRoomIndex() { }
	// RVA: 0x378e9e4 VA: 0x7595da69e4
	private Void _LoadElectricInfo() { }
	// RVA: 0x378eb70 VA: 0x7595da6b70
	private Void _LoadAssistants() { }
	// RVA: 0x378e54c VA: 0x7595da654c
	private Void _UpdatePrivateOwners() { }
	// RVA: 0x378ecb8 VA: 0x7595da6cb8
	private Void _LoadPrivateOwners() { }
	// RVA: 0x378fb80 VA: 0x7595da7b80
	private Void _RefreshRooms(RoomType[] roomTypes) { }
	// RVA: 0x378ff60 VA: 0x7595da7f60
	public Boolean CallBackPrivateDormOwner(String slotId) { }
	// RVA: 0x3790540 VA: 0x7595da8540
	public Boolean CallBackPrivateDormOwner(Int32 instId) { }
	// RVA: 0x3790388 VA: 0x7595da8388
	public Boolean IsVCharStayedInPrivateDorm(Int32 instId) { }
	// RVA: 0x378ee68 VA: 0x7595da6e68
	private Void _RefreshVCharStayedRoom() { }
	// RVA: 0x37906a0 VA: 0x7595da86a0
	public Boolean IsVCharStayedRoomValid(Int32 instId, String slotId) { }
	// RVA: 0x379047c VA: 0x7595da847c
	public Void RefreshVCharForceStayedRoom(Int32 instId, String slotId) { }
	// RVA: 0x3790774 VA: 0x7595da8774
	public Void RemoveForceStayedRoom(List`1 instIds) { }
	// RVA: 0x3790600 VA: 0x7595da8600
	public Boolean IsVCharPrivateOwner(Int32 instId) { }
	// RVA: 0x3790900 VA: 0x7595da8900
	public Void OnReset() { }
	// RVA: 0x3790964 VA: 0x7595da8964
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x37909dc VA: 0x7595da89dc
	public Void OnStop() { }
	// RVA: 0x3790a40 VA: 0x7595da8a40
	public Void .ctor() { }
}
```