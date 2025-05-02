# Act20sideEntertainCompViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String activityId`

- `String stage1Id`

- `String stage1Desc`

- `CartCompetitionRank stage1Rank`

- `Boolean hasRecordStage1`

- `Boolean isStage1Locked`

- `String stage1UnlockStr`

- `String stage2Id`

- `String stage2Desc`

- `CartCompetitionRank stage2Rank`

- `Boolean hasRecordStage2`

- `Boolean isStage2Locked`

- `String stage2UnlockStr`

- `Cart battleCar`

- `Int32 stage1RankIndex`

- `Int32 stage2RankIndex`


## Methods

- `Void LoadData(String, Boolean)`

- `Void _LoadPlayerActivityData(String, Boolean)`

- `String _GetUnlockConditionStr(String, Int64, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideEntertainCompViewModel : IHotfixable
{
	private const Int32 SPECIAL_STAGE_COUNT; // 0x0
	public String activityId; // 0x10
	public String stage1Id; // 0x18
	public String stage1Desc; // 0x20
	public CartCompetitionRank stage1Rank; // 0x28
	public Boolean hasRecordStage1; // 0x2c
	public Boolean isStage1Locked; // 0x2d
	public String stage1UnlockStr; // 0x30
	public String stage2Id; // 0x38
	public String stage2Desc; // 0x40
	public CartCompetitionRank stage2Rank; // 0x48
	public Boolean hasRecordStage2; // 0x4c
	public Boolean isStage2Locked; // 0x4d
	public String stage2UnlockStr; // 0x50
	public Cart battleCar; // 0x58
	public Int32 stage1RankIndex; // 0x60
	public Int32 stage2RankIndex; // 0x64
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetRuneList; // 0x8
	private static DelegateBridge __Hotfix0__LoadPlayerActivityData; // 0x10
	private static DelegateBridge __Hotfix0__GetUnlockConditionStr; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32f7044 VA: 0x759590f044
	public Void LoadData(String activityId, Boolean isRetro) { }
	// RVA: 0x32f8078 VA: 0x7595910078
	public List`1 GetRuneList() { }
	// RVA: 0x3303720 VA: 0x759591b720
	private Void _LoadPlayerActivityData(String actId, Boolean isRetro) { }
	// RVA: 0x33038b4 VA: 0x759591b8b4
	private String _GetUnlockConditionStr(String zoneId, Int64 timeStampNow, String conditionStr) { }
	// RVA: 0x32f8190 VA: 0x7595910190
	public Void .ctor() { }
}
```