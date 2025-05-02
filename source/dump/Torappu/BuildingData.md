# BuildingData

**Namespace:** `Torappu`


## Fields

- `String controlSlotId`

- `String meetingSlotId`

- `Int32 initMaxLabor`

- `Int32 laborRecoverTime`

- `Int32 manufactInputCapacity`

- `Int32 shopCounterCapacity`

- `Int32 comfortLimit`

- `Int32 creditInitiativeLimit`

- `Int32 creditPassiveLimit`

- `Int32 creditComfortFactor`

- `Int32 creditGuaranteed`

- `Int32 creditCeiling`

- `String manufactUnlockTips`

- `String shopUnlockTips`

- `Single manufactStationBuff`

- `Int32 comfortManpowerRecoverFactor`

- `Int32 manpowerDisplayFactor`

- `Int32 basicFavorPerDay`

- `Int32 humanResourceLimit`

- `Int64 tiredApThreshold`

- `Int32 processedCountRatio`

- `Int32 tradingStrategyUnlockLevel`

- `Int32 tradingReduceTimeUnit`

- `Int32 tradingLaborCostUnit`

- `Int32 manufactReduceTimeUnit`

- `Int32 manufactLaborCostUnit`

- `Int32 laborAssistUnlockLevel`

- `Int32 apToLaborUnlockLevel`

- `Int32 apToLaborRatio`

- `Int32 socialResourceLimit`

- `Int32 socialSlotNum`

- `Int32 furniDuplicationLimit`

- `Int64 assistFavorReport`

- `Int32 trainingBonusMax`

- `Int64 betaRemoveTime`

- `Single furniHighlightTime`

- `String canNotVisitToast`

- `Int64 musicPlayerOpenTime`

- `ControlRoomBean controlData`

- `ManufactRoomBean manufactData`

- `HireRoomBean hireData`

- `MeetingRoomBean meetingData`

- `TradingRoomBean tradingData`

- `TrainingBean trainingData`

- `PowerRoomBean powerData`

- `CustomData customData`

- `CreditFormula creditFormula`

- `StationManageConstData stationManageConstData`

- `MusicData musicData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingData
{
	public const String CONTROL_STOREY_ID; // 0x0
	public String controlSlotId; // 0x10
	public String meetingSlotId; // 0x18
	public Int32 initMaxLabor; // 0x20
	public Int32 laborRecoverTime; // 0x24
	public Int32 manufactInputCapacity; // 0x28
	public Int32 shopCounterCapacity; // 0x2c
	public Int32 comfortLimit; // 0x30
	public Int32 creditInitiativeLimit; // 0x34
	public Int32 creditPassiveLimit; // 0x38
	public Int32 creditComfortFactor; // 0x3c
	public Int32 creditGuaranteed; // 0x40
	public Int32 creditCeiling; // 0x44
	public String manufactUnlockTips; // 0x48
	public String shopUnlockTips; // 0x50
	public Single manufactStationBuff; // 0x58
	public Int32 comfortManpowerRecoverFactor; // 0x5c
	public Int32 manpowerDisplayFactor; // 0x60
	public ListDict`2 shopOutputRatio; // 0x68
	public ListDict`2 shopStackRatio; // 0x70
	public Int32 basicFavorPerDay; // 0x78
	public Int32 humanResourceLimit; // 0x7c
	public Int64 tiredApThreshold; // 0x80
	public Int32 processedCountRatio; // 0x88
	public Int32 tradingStrategyUnlockLevel; // 0x8c
	public Int32 tradingReduceTimeUnit; // 0x90
	public Int32 tradingLaborCostUnit; // 0x94
	public Int32 manufactReduceTimeUnit; // 0x98
	public Int32 manufactLaborCostUnit; // 0x9c
	public Int32 laborAssistUnlockLevel; // 0xa0
	public Int32 apToLaborUnlockLevel; // 0xa4
	public Int32 apToLaborRatio; // 0xa8
	public Int32 socialResourceLimit; // 0xac
	public Int32 socialSlotNum; // 0xb0
	public Int32 furniDuplicationLimit; // 0xb4
	public Int64 assistFavorReport; // 0xb8
	public Int32[] manufactManpowerCostByNum; // 0xc0
	public Int32[] tradingManpowerCostByNum; // 0xc8
	public Int32 trainingBonusMax; // 0xd0
	public Int64 betaRemoveTime; // 0xd8
	public Single furniHighlightTime; // 0xe0
	public String canNotVisitToast; // 0xe8
	public Int64 musicPlayerOpenTime; // 0xf0
	public List`1 roomsWithoutRemoveStaff; // 0xf8
	public List`1 privateFavorLevelThresholds; // 0x100
	public Dictionary`2 roomUnlockConds; // 0x108
	public Dictionary`2 rooms; // 0x110
	public Dictionary`2 layouts; // 0x118
	public Dictionary`2 prefabs; // 0x120
	public ControlRoomBean controlData; // 0x128
	public ManufactRoomBean manufactData; // 0x130
	public RoomBean`1 shopData; // 0x138
	public HireRoomBean hireData; // 0x140
	public RoomBean`1 dormData; // 0x148
	public RoomBean`1 privateRoomData; // 0x150
	public MeetingRoomBean meetingData; // 0x158
	public TradingRoomBean tradingData; // 0x160
	public RoomBean`1 workshopData; // 0x168
	public TrainingBean trainingData; // 0x170
	public PowerRoomBean powerData; // 0x178
	public Dictionary`2 chars; // 0x180
	public Dictionary`2 buffs; // 0x188
	public Dictionary`2 workshopBonus; // 0x190
	public CustomData customData; // 0x198
	public Dictionary`2 manufactFormulas; // 0x1a0
	public Dictionary`2 shopFormulas; // 0x1a8
	public Dictionary`2 workshopFormulas; // 0x1b0
	public CreditFormula creditFormula; // 0x1b8
	public Dictionary`2 goldItems; // 0x1c0
	public List`1 assistantUnlock; // 0x1c8
	public List`1 workshopRarities; // 0x1d0
	public Dictionary`2 todoItemSortPriorityDict; // 0x1d8
	public ListDict`2 slotPrequeDatas; // 0x1e0
	public ListDict`2 dormitoryPrequeDatas; // 0x1e8
	public Dictionary`2 workshopTargetDesDict; // 0x1f0
	public Dictionary`2 tradingOrderDesDict; // 0x1f8
	public StationManageConstData stationManageConstData; // 0x200
	public Dictionary`2 stationManageFilterInfos; // 0x208
	public MusicData musicData; // 0x210
	public List`1 emojis; // 0x218


	// RVA: 0x33c6798 VA: 0x75959de798
	public Void .ctor() { }
}
```