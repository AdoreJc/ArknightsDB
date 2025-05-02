# StationManageRestViewModel

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Boolean canBatchRest`

- `Int32 totalDormCnt`

- `Int32 charTiredCnt`

- `Int32 charPowerNotFullCnt`

- `Int32 dormAvailSlotCnt`

- `Int32 stationLimit`

- `Int32 stationCharCnt`

- `Int32 selectedRoomComfort`

- `String textRecoverBase`

- `String textRecoverBuff`

- `Boolean hasBuiltDorm`

- `Boolean isEditLockMode`

- `Int32 editModeLockCnt`

- `IntHashSet m_inPrequeChars`


## Methods

- `Void InitData(BuildingModel)`

- `Void LoadData(BuildingModel)`

- `Void LoadSelectedRoomDetail(BuildingModel, RoomSlotModel)`

- `Void UpdateSelectedSlotId(String)`

- `Void UpdateEditDormLockMode(BuildingModel, Boolean)`

- `Int32 UpdateEditDormLockData(BuildingModel, String, Int32)`

- `Void ClearAllEditDormLock(BuildingModel)`

- `Int32 CalcLockedCharInPreQueCnt()`

- `Void _CalcEditModeLockCnt()`

- `Void _LoadRoomGroupData(BuildingModel)`

- `Void _LoadCharTiredData(BuildingModel)`

- `Void _LoadRoomNumData()`

- `Void _LoadBatchRestData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class StationManageRestViewModel
{
	public Boolean canBatchRest; // 0x10
	public Int32 totalDormCnt; // 0x14
	public Int32 charTiredCnt; // 0x18
	public Int32 charPowerNotFullCnt; // 0x1c
	public Int32 dormAvailSlotCnt; // 0x20
	public Int32 stationLimit; // 0x24
	public Int32 stationCharCnt; // 0x28
	public Int32 selectedRoomComfort; // 0x2c
	public String textRecoverBase; // 0x30
	public String textRecoverBuff; // 0x38
	public Boolean hasBuiltDorm; // 0x40
	public Boolean isEditLockMode; // 0x41
	public Int32 editModeLockCnt; // 0x44
	public Dictionary`2 editModeLockStatus; // 0x48
	public List`1 dormGroups; // 0x50
	private IntHashSet m_inPrequeChars; // 0x58


	// RVA: 0x3da5080 VA: 0x75963bd080
	public Void InitData(BuildingModel model) { }
	// RVA: 0x3da54bc VA: 0x75963bd4bc
	public Void LoadData(BuildingModel model) { }
	// RVA: 0x3da6034 VA: 0x75963be034
	public Void LoadSelectedRoomDetail(BuildingModel model, RoomSlotModel slotModel) { }
	// RVA: 0x3da5ee0 VA: 0x75963bdee0
	public Void UpdateSelectedSlotId(String slotId) { }
	// RVA: 0x3da2f30 VA: 0x75963baf30
	public Void UpdateEditDormLockMode(BuildingModel model, Boolean isEnter) { }
	// RVA: 0x3da2d10 VA: 0x75963bad10
	public Int32 UpdateEditDormLockData(BuildingModel model, String slotId, Int32 index) { }
	// RVA: 0x3da340c VA: 0x75963bb40c
	public Void ClearAllEditDormLock(BuildingModel model) { }
	// RVA: 0x3da8270 VA: 0x75963c0270
	public Int32 CalcLockedCharInPreQueCnt() { }
	// RVA: 0x3da80ac VA: 0x75963c00ac
	private Void _CalcEditModeLockCnt() { }
	// RVA: 0x3da714c VA: 0x75963bf14c
	private Void _LoadRoomGroupData(BuildingModel model) { }
	// RVA: 0x3da75fc VA: 0x75963bf5fc
	private Void _LoadCharTiredData(BuildingModel model) { }
	// RVA: 0x3da7dc4 VA: 0x75963bfdc4
	private Void _LoadRoomNumData() { }
	// RVA: 0x3da7928 VA: 0x75963bf928
	private Void _LoadBatchRestData() { }
	// RVA: 0x3da4a70 VA: 0x75963bca70
	public Void .ctor() { }
}
```