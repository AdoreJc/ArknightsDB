# BuildSlotViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `State m_playerBuildState`

- `Boolean m_isBuildFinish`

- `Int32 <slotIndex>k__BackingField`

- `DateTime maxFinishTime`

- `Int64 remainTimeReal`

- `Int64 remainTimeShow`

- `Int32 selectCostMinutes`

- `String <lockedText>k__BackingField`

- `BuildingRoomInfoModel <hireRoom>k__BackingField`


## Properties

- `Int32 slotIndex`

- `String lockedText`

- `BuildingRoomInfoModel hireRoom`

- `RecruitBuildSlotState state`


## Methods

- `Int32 get_slotIndex()`

- `Void set_slotIndex(Int32)`

- `String get_lockedText()`

- `Void set_lockedText(String)`

- `BuildingRoomInfoModel get_hireRoom()`

- `Void set_hireRoom(BuildingRoomInfoModel)`

- `RecruitBuildSlotState get_state()`

- `Void LoadData(Int32)`

- `Void RefreshData(Int64, Int32, TagItem[])`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class BuildSlotViewModel : BuildConfigCostViewModel
{
	private State m_playerBuildState; // 0x3c
	private Boolean m_isBuildFinish; // 0x40
	private Int32 <slotIndex>k__BackingField; // 0x44
	public DateTime maxFinishTime; // 0x48
	public Int64 remainTimeReal; // 0x50
	public Int64 remainTimeShow; // 0x58
	public Int32 selectCostMinutes; // 0x60
	public BuildTagModel[] selectTags; // 0x68
	private String <lockedText>k__BackingField; // 0x70
	private BuildingRoomInfoModel <hireRoom>k__BackingField; // 0x78

	public Int32 slotIndex { get; set; }
	public String lockedText { get; set; }
	public BuildingRoomInfoModel hireRoom { get; set; }
	public RecruitBuildSlotState state { get; }

	// RVA: 0x26fc26c VA: 0x7594d1426c
	public Int32 get_slotIndex() { }
	// RVA: 0x26fc274 VA: 0x7594d14274
	private Void set_slotIndex(Int32 value) { }
	// RVA: 0x26fc27c VA: 0x7594d1427c
	public String get_lockedText() { }
	// RVA: 0x26fc284 VA: 0x7594d14284
	private Void set_lockedText(String value) { }
	// RVA: 0x26fc28c VA: 0x7594d1428c
	public BuildingRoomInfoModel get_hireRoom() { }
	// RVA: 0x26fc2a4 VA: 0x7594d142a4
	private Void set_hireRoom(BuildingRoomInfoModel value) { }
	// RVA: 0x26fc2c8 VA: 0x7594d142c8
	public RecruitBuildSlotState get_state() { }
	// RVA: 0x26fc318 VA: 0x7594d14318
	public Void LoadData(Int32 slotIndex) { }
	// RVA: 0x26fc79c VA: 0x7594d1479c
	public Void RefreshData(Int64 costTime, Int32 selectTagCount, TagItem[] tagLists) { }
	// RVA: 0x26fcc88 VA: 0x7594d14c88
	private Void _InitIfNot() { }
	// RVA: 0x26fcdb8 VA: 0x7594d14db8
	public Void .ctor() { }
}
```