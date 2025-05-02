# RoomSlotModel

**Namespace:** `Torappu.Building`


## Fields

- `Boolean m_isContentUpdated`

- `RoomSlot m_slotData`

- `SlotCleanCost m_cleanCostData`

- `RoomData m_roomData`

- `PhaseData m_phaseData`

- `PhaseData m_maxPhaseData`

- `PhaseData m_nextLevelPhaseData`

- `PrefabInfo m_prefabInfo`

- `IRoomBean m_bean`

- `StoreyData m_storeyData`

- `String m_roomCode`

- `String m_roomIndexInSameRooms`

- `DynamicAssetPriority m_dynamicAssetPriority`

- `PlayerSlotStatus m_playerStatus`

- `String <prefabId>k__BackingField`


## Properties

- `String slotId`

- `String prefabId`

- `RoomType roomId`

- `Int32 roomLevel`

- `String name`

- `Int32 maxLevel`

- `String description`

- `Boolean isBuilt`

- `Boolean isUncleaned`

- `Boolean isUpgrading`

- `Boolean isNotEmpty`

- `Boolean isAboutToBuilt`

- `DynamicAssetPriority dynamicAssetPriority`

- `GridPosition offset`

- `GridPosition size`

- `String cleanCostId`

- `Int32 electricity`

- `Int32 cleanCostLabor`

- `Int32 cleanProvideMaxLabor`

- `RoomSlotState state`

- `DateTime constructCompleteTime`

- `Int32 stationedNum`

- `Int32 maxStationedNum`

- `Int32 finalMaxStationedNum`

- `Int64 phaseTimeCost`

- `BuildCost levelupCost`

- `RoomCategory category`

- `String storeyId`

- `PhaseData previousPhaseData`

- `RoomData roomData`

- `PhaseData phaseData`

- `PrefabInfo prefabInfo`

- `RoomSlot slot`

- `IRoomBean bean`

- `ObstacleData obstacleData`


## Methods

- `String get_slotId()`

- `String get_prefabId()`

- `Void set_prefabId(String)`

- `RoomType get_roomId()`

- `Int32 get_roomLevel()`

- `String get_name()`

- `Int32 get_maxLevel()`

- `String get_description()`

- `Boolean get_isBuilt()`

- `Boolean get_isUncleaned()`

- `Boolean get_isUpgrading()`

- `Boolean get_isNotEmpty()`

- `Boolean get_isAboutToBuilt()`

- `DynamicAssetPriority get_dynamicAssetPriority()`

- `GridPosition get_offset()`

- `GridPosition get_size()`

- `String get_cleanCostId()`

- `Int32 get_electricity()`

- `Int32 get_cleanCostLabor()`

- `Int32 get_cleanProvideMaxLabor()`

- `RoomSlotState get_state()`

- `DateTime get_constructCompleteTime()`

- `Int32 get_stationedNum()`

- `Int32 get_maxStationedNum()`

- `Int32 get_finalMaxStationedNum()`

- `Int64 get_phaseTimeCost()`

- `BuildCost get_levelupCost()`

- `RoomCategory get_category()`

- `String get_storeyId()`

- `PhaseData get_previousPhaseData()`

- `RoomData get_roomData()`

- `PhaseData get_phaseData()`

- `PrefabInfo get_prefabInfo()`

- `RoomSlot get_slot()`

- `IRoomBean get_bean()`

- `ObstacleData get_obstacleData()`

- `Void RegisterListener(IListener)`

- `Boolean UnregisterListener(IListener)`

- `String LoadStayChars(ref)`

- `Int32 FindStationSlotUnlockLevel(Int32)`

- `Void SetRoomCode(Int32)`

- `Void SetAssetLoadPriority(DynamicAssetPriority)`

- `Void TrySetRoomIndexInSameRooms(Int32)`

- `Void MarkDirty()`

- `Void UpdateContentForCurrentPlayer(PlayerBuildingRoomSlot, PlayerBuilding, Boolean)`

- `Void UpdateContentForVisiting(PlayerBuildingRoomSlot, VisitBuildingResponse)`

- `Void TryNotifyContentUpdated(Boolean)`

- `Boolean CheckBuildable(String)`

- `Int32 CountNotTiredStationedNum()`

- `Object GetPhaseParam()`

- `T GetPhaseParam()`

- `Int64 GetBasicManpowerCostPerSec()`

- `Void _LoadDataViaStatus()`

- `String _GetInactiveRoomPrefabId(RoomSlot, RoomSlotState)`

- `String GetCompleteRoomPrefabId()`

- `String GetRoomCode()`

- `String GetRoomIndexInSameRooms()`

- `String GetStoreyName()`

- `String GetRoomNameWithCodeAndStorey()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class RoomSlotModel : IHotfixable
{
	public const String PREFAB_UNCLEAN_TEMPLATE; // 0x0
	public const String PREFAB_EMPTY_TEMPALTE; // 0x0
	public const String PREFAB_LEVELUP_TEMPLATE; // 0x0
	public const String PREFAB_COMPLETE_TEMPALTE; // 0x0
	private Boolean m_isContentUpdated; // 0x10
	private RoomSlot m_slotData; // 0x18
	private SlotCleanCost m_cleanCostData; // 0x20
	private RoomData m_roomData; // 0x28
	private PhaseData m_phaseData; // 0x30
	private PhaseData m_maxPhaseData; // 0x38
	private PhaseData m_nextLevelPhaseData; // 0x40
	private PrefabInfo m_prefabInfo; // 0x48
	private IRoomBean m_bean; // 0x50
	private StoreyData m_storeyData; // 0x58
	private String m_roomCode; // 0x60
	private String m_roomIndexInSameRooms; // 0x68
	private DynamicAssetPriority m_dynamicAssetPriority; // 0x70
	private PlayerSlotStatus m_playerStatus; // 0x78
	private List`1 m_listeners; // 0xa8
	private String <prefabId>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_slotId; // 0x0
	private static DelegateBridge __Hotfix0_get_prefabId; // 0x8
	private static DelegateBridge __Hotfix0_set_prefabId; // 0x10
	private static DelegateBridge __Hotfix0_get_roomId; // 0x18
	private static DelegateBridge __Hotfix0_get_roomLevel; // 0x20
	private static DelegateBridge __Hotfix0_get_name; // 0x28
	private static DelegateBridge __Hotfix0_get_maxLevel; // 0x30
	private static DelegateBridge __Hotfix0_get_description; // 0x38
	private static DelegateBridge __Hotfix0_get_isBuilt; // 0x40
	private static DelegateBridge __Hotfix0_get_isUncleaned; // 0x48
	private static DelegateBridge __Hotfix0_get_isUpgrading; // 0x50
	private static DelegateBridge __Hotfix0_get_isNotEmpty; // 0x58
	private static DelegateBridge __Hotfix0_get_isAboutToBuilt; // 0x60
	private static DelegateBridge __Hotfix0_get_dynamicAssetPriority; // 0x68
	private static DelegateBridge __Hotfix0_get_offset; // 0x70
	private static DelegateBridge __Hotfix0_get_size; // 0x78
	private static DelegateBridge __Hotfix0_GetCleanCost; // 0x80
	private static DelegateBridge __Hotfix0_get_cleanCostId; // 0x88
	private static DelegateBridge __Hotfix0_get_electricity; // 0x90
	private static DelegateBridge __Hotfix0_get_cleanCostLabor; // 0x98
	private static DelegateBridge __Hotfix0_get_cleanProvideMaxLabor; // 0xa0
	private static DelegateBridge __Hotfix0_get_state; // 0xa8
	private static DelegateBridge __Hotfix0_get_constructCompleteTime; // 0xb0
	private static DelegateBridge __Hotfix0_get_stationedChars; // 0xb8
	private static DelegateBridge __Hotfix0_get_stationedNum; // 0xc0
	private static DelegateBridge __Hotfix0_get_maxStationedNum; // 0xc8
	private static DelegateBridge __Hotfix0_get_finalMaxStationedNum; // 0xd0
	private static DelegateBridge __Hotfix0_get_phaseTimeCost; // 0xd8
	private static DelegateBridge __Hotfix0_get_levelupCost; // 0xe0
	private static DelegateBridge __Hotfix0_get_category; // 0xe8
	private static DelegateBridge __Hotfix0_get_storeyId; // 0xf0
	private static DelegateBridge __Hotfix0_get_previousPhaseData; // 0xf8
	private static DelegateBridge __Hotfix0_get_roomData; // 0x100
	private static DelegateBridge __Hotfix0_get_phaseData; // 0x108
	private static DelegateBridge __Hotfix0_get_prefabInfo; // 0x110
	private static DelegateBridge __Hotfix0_get_slot; // 0x118
	private static DelegateBridge __Hotfix0_get_bean; // 0x120
	private static DelegateBridge __Hotfix0_get_obstacleData; // 0x128
	private static DelegateBridge __Hotfix0_RegisterListener; // 0x130
	private static DelegateBridge __Hotfix0_UnregisterListener; // 0x138
	private static DelegateBridge __Hotfix0_CreateForObstableEditor; // 0x140
	private static DelegateBridge __Hotfix0_CreateFromCurUser; // 0x148
	private static DelegateBridge __Hotfix0_CreateFromVisiting; // 0x150
	private static DelegateBridge __Hotfix0_LoadStayChars; // 0x158
	private static DelegateBridge __Hotfix0_FindStationSlotUnlockLevel; // 0x160
	private static DelegateBridge __Hotfix0__AddCharToStaySignature; // 0x168
	private static DelegateBridge __Hotfix0_SetRoomCode; // 0x170
	private static DelegateBridge __Hotfix0_SetAssetLoadPriority; // 0x178
	private static DelegateBridge __Hotfix0_TrySetRoomIndexInSameRooms; // 0x180
	private static DelegateBridge __Hotfix0_MarkDirty; // 0x188
	private static DelegateBridge __Hotfix0_UpdateContentForCurrentPlayer; // 0x190
	private static DelegateBridge __Hotfix0_UpdateContentForVisiting; // 0x198
	private static DelegateBridge __Hotfix0_TryNotifyContentUpdated; // 0x1a0
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x1a8
	private static DelegateBridge __Hotfix0_CountNotTiredStationedNum; // 0x1b0
	private static DelegateBridge __Hotfix0_GetPhaseParam; // 0x1b8
	private static DelegateBridge __Hotfix1_GetPhaseParam; // 0x1c0
	private static DelegateBridge __Hotfix0_GetBasicManpowerCostPerSec; // 0x1c8
	private static DelegateBridge __Hotfix0__LoadDataViaStatus; // 0x1d0
	private static DelegateBridge __Hotfix0__GetInactiveRoomPrefabId; // 0x1d8
	private static DelegateBridge __Hotfix0_GetCompleteRoomPrefabId; // 0x1e0
	private static DelegateBridge __Hotfix0_GetRoomCode; // 0x1e8
	private static DelegateBridge __Hotfix0_GetRoomIndexInSameRooms; // 0x1f0
	private static DelegateBridge __Hotfix0__CheckNeedNameIndex; // 0x1f8
	private static DelegateBridge __Hotfix0_GetStoreyName; // 0x200
	private static DelegateBridge __Hotfix0_GetRoomNameWithCodeAndStorey; // 0x208
	private static DelegateBridge _c__Hotfix0_ctor; // 0x210

	public String slotId { get; }
	public String prefabId { get; set; }
	public RoomType roomId { get; }
	public Int32 roomLevel { get; }
	public String name { get; }
	public Int32 maxLevel { get; }
	public String description { get; }
	public Boolean isBuilt { get; }
	public Boolean isUncleaned { get; }
	public Boolean isUpgrading { get; }
	public Boolean isNotEmpty { get; }
	public Boolean isAboutToBuilt { get; }
	public DynamicAssetPriority dynamicAssetPriority { get; }
	public GridPosition offset { get; }
	public GridPosition size { get; }
	public String cleanCostId { get; }
	public Int32 electricity { get; }
	public Int32 cleanCostLabor { get; }
	public Int32 cleanProvideMaxLabor { get; }
	public RoomSlotState state { get; }
	public DateTime constructCompleteTime { get; }
	public BuildingCharModel[] stationedChars { get; }
	public Int32 stationedNum { get; }
	public Int32 maxStationedNum { get; }
	public Int32 finalMaxStationedNum { get; }
	public Int64 phaseTimeCost { get; }
	public BuildCost levelupCost { get; }
	public RoomCategory category { get; }
	public String storeyId { get; }
	public PhaseData previousPhaseData { get; }
	public RoomData roomData { get; }
	public PhaseData phaseData { get; }
	public PrefabInfo prefabInfo { get; }
	public RoomSlot slot { get; }
	public IRoomBean bean { get; }
	public ObstacleData obstacleData { get; }

	// RVA: 0x378af68 VA: 0x7595da2f68
	public String get_slotId() { }
	// RVA: 0x37920ec VA: 0x7595daa0ec
	public String get_prefabId() { }
	// RVA: 0x3792154 VA: 0x7595daa154
	private Void set_prefabId(String value) { }
	// RVA: 0x378af00 VA: 0x7595da2f00
	public RoomType get_roomId() { }
	// RVA: 0x378dc28 VA: 0x7595da5c28
	public Int32 get_roomLevel() { }
	// RVA: 0x37921d8 VA: 0x7595daa1d8
	public String get_name() { }
	// RVA: 0x3792298 VA: 0x7595daa298
	public Int32 get_maxLevel() { }
	// RVA: 0x3792330 VA: 0x7595daa330
	public String get_description() { }
	// RVA: 0x37923a4 VA: 0x7595daa3a4
	public Boolean get_isBuilt() { }
	// RVA: 0x3792414 VA: 0x7595daa414
	public Boolean get_isUncleaned() { }
	// RVA: 0x3792484 VA: 0x7595daa484
	public Boolean get_isUpgrading() { }
	// RVA: 0x37924f4 VA: 0x7595daa4f4
	public Boolean get_isNotEmpty() { }
	// RVA: 0x3792568 VA: 0x7595daa568
	public Boolean get_isAboutToBuilt() { }
	// RVA: 0x3792650 VA: 0x7595daa650
	public DynamicAssetPriority get_dynamicAssetPriority() { }
	// RVA: 0x378afd0 VA: 0x7595da2fd0
	public GridPosition get_offset() { }
	// RVA: 0x378b044 VA: 0x7595da3044
	public GridPosition get_size() { }
	// RVA: 0x37926b8 VA: 0x7595daa6b8
	public List`1 GetCleanCost(Int32 count) { }
	// RVA: 0x37927dc VA: 0x7595daa7dc
	public String get_cleanCostId() { }
	// RVA: 0x3792870 VA: 0x7595daa870
	public Int32 get_electricity() { }
	// RVA: 0x37928e8 VA: 0x7595daa8e8
	public Int32 get_cleanCostLabor() { }
	// RVA: 0x3792960 VA: 0x7595daa960
	public Int32 get_cleanProvideMaxLabor() { }
	// RVA: 0x378fb18 VA: 0x7595da7b18
	public RoomSlotState get_state() { }
	// RVA: 0x37929d8 VA: 0x7595daa9d8
	public DateTime get_constructCompleteTime() { }
	// RVA: 0x3786cd0 VA: 0x7595d9ecd0
	public BuildingCharModel[] get_stationedChars() { }
	// RVA: 0x3792a40 VA: 0x7595daaa40
	public Int32 get_stationedNum() { }
	// RVA: 0x3792aa8 VA: 0x7595daaaa8
	public Int32 get_maxStationedNum() { }
	// RVA: 0x3792b20 VA: 0x7595daab20
	public Int32 get_finalMaxStationedNum() { }
	// RVA: 0x3792b98 VA: 0x7595daab98
	public Int64 get_phaseTimeCost() { }
	// RVA: 0x3792c18 VA: 0x7595daac18
	public BuildCost get_levelupCost() { }
	// RVA: 0x378f888 VA: 0x7595da7888
	public RoomCategory get_category() { }
	// RVA: 0x378f7f4 VA: 0x7595da77f4
	public String get_storeyId() { }
	// RVA: 0x3792c90 VA: 0x7595daac90
	public PhaseData get_previousPhaseData() { }
	// RVA: 0x378fab0 VA: 0x7595da7ab0
	public RoomData get_roomData() { }
	// RVA: 0x3792d1c VA: 0x7595daad1c
	public PhaseData get_phaseData() { }
	// RVA: 0x3792d84 VA: 0x7595daad84
	public PrefabInfo get_prefabInfo() { }
	// RVA: 0x3792dec VA: 0x7595daadec
	public RoomSlot get_slot() { }
	// RVA: 0x3792e54 VA: 0x7595daae54
	public IRoomBean get_bean() { }
	// RVA: 0x3792ebc VA: 0x7595daaebc
	public ObstacleData get_obstacleData() { }
	// RVA: 0x3792f7c VA: 0x7595daaf7c
	public Void RegisterListener(IListener listener) { }
	// RVA: 0x3793128 VA: 0x7595dab128
	public Boolean UnregisterListener(IListener listener) { }
	// RVA: 0x37931c8 VA: 0x7595dab1c8
	public static RoomSlotModel CreateForObstableEditor(GridPosition size, GridPosition offset) { }
	// RVA: 0x378ae1c VA: 0x7595da2e1c
	public static RoomSlotModel CreateFromCurUser(RoomSlot slot, PlayerBuildingRoomSlot inst, PlayerBuilding playerBuilding, SlotCleanCost cleanCost) { }
	// RVA: 0x378bfac VA: 0x7595da3fac
	public static RoomSlotModel CreateFromVisiting(RoomSlot slot, PlayerBuildingRoomSlot inst, VisitBuildingResponse response) { }
	// RVA: 0x3793484 VA: 0x7595dab484
	public String LoadStayChars(ref List`1 stayChars) { }
	// RVA: 0x3793ff0 VA: 0x7595dabff0
	public Int32 FindStationSlotUnlockLevel(Int32 slotIndex) { }
	// RVA: 0x3793e34 VA: 0x7595dabe34
	private static Void _AddCharToStaySignature(StringBuilder sign, BuildingCharModel charModel, RoomStayType type) { }
	// RVA: 0x378f900 VA: 0x7595da7900
	public Void SetRoomCode(Int32 index) { }
	// RVA: 0x378e154 VA: 0x7595da6154
	public Void SetAssetLoadPriority(DynamicAssetPriority priority) { }
	// RVA: 0x378f9d8 VA: 0x7595da79d8
	public Void TrySetRoomIndexInSameRooms(Int32 index) { }
	// RVA: 0x378fef4 VA: 0x7595da7ef4
	public Void MarkDirty() { }
	// RVA: 0x378c940 VA: 0x7595da4940
	public Void UpdateContentForCurrentPlayer(PlayerBuildingRoomSlot playerSlot, PlayerBuilding playerBuilding, Boolean force) { }
	// RVA: 0x379338c VA: 0x7595dab38c
	public Void UpdateContentForVisiting(PlayerBuildingRoomSlot playerSlot, VisitBuildingResponse response) { }
	// RVA: 0x378cab0 VA: 0x7595da4ab0
	public Void TryNotifyContentUpdated(Boolean isForce) { }
	// RVA: 0x37947a4 VA: 0x7595dac7a4
	public Boolean CheckBuildable(String roomId) { }
	// RVA: 0x379487c VA: 0x7595dac87c
	public Int32 CountNotTiredStationedNum() { }
	// RVA: 0x37949f0 VA: 0x7595dac9f0
	public Object GetPhaseParam() { }
	// RVA: 0x VA: 0x0
	public T GetPhaseParam() { }
	// RVA: 0x3794af4 VA: 0x7595dacaf4
	public Int64 GetBasicManpowerCostPerSec() { }
	// RVA: 0x3794184 VA: 0x7595dac184
	private Void _LoadDataViaStatus() { }
	// RVA: 0x3794b78 VA: 0x7595dacb78
	private String _GetInactiveRoomPrefabId(RoomSlot slotData, RoomSlotState state) { }
	// RVA: 0x3794c94 VA: 0x7595dacc94
	public String GetCompleteRoomPrefabId() { }
	// RVA: 0x3794d84 VA: 0x7595dacd84
	public String GetRoomCode() { }
	// RVA: 0x3794dec VA: 0x7595dacdec
	public String GetRoomIndexInSameRooms() { }
	// RVA: 0x37940e8 VA: 0x7595dac0e8
	private static Boolean _CheckNeedNameIndex(RoomType roomType) { }
	// RVA: 0x3794e54 VA: 0x7595dace54
	public String GetStoreyName() { }
	// RVA: 0x3794ee8 VA: 0x7595dacee8
	public String GetRoomNameWithCodeAndStorey() { }
	// RVA: 0x37932c8 VA: 0x7595dab2c8
	public Void .ctor() { }
}
```