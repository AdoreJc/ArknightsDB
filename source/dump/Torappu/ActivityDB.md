# ActivityDB

**Namespace:** `Torappu`


## Methods

- `Boolean HasEventDuringTime(Int64, Int64)`

- `Boolean HasFixedSyncActivity(Int64)`

- `MissionData GetActMission(String)`

- `MissionGroup GetMissionGroupData(String)`

- `ActivityHiddenStageData GetActivityHiddenStageData(String)`

- `String GetStringRes(String, String)`

- `Boolean CheckIsHiddenStage(String)`

- `Void _InitMissionMap()`

- `Void _InitTimeSortedActInfos()`

- `Void _InitTimeSortActThemes()`

- `Void _InitHiddenStageMap()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActivityDB : ConstTable`2
{
	private List`1 m_activityTimePoints; // 0x60
	private Dictionary`2 m_actMissionMap; // 0x68
	private Dictionary`2 m_actMissionGroupMap; // 0x70
	private List`1 m_timeSortedActInfos; // 0x78
	private List`1 m_timeSortedActThemes; // 0x80
	private Dictionary`2 m_hiddenStageDict; // 0x88
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_HasEventDuringTime; // 0x8
	private static DelegateBridge __Hotfix0_HasFixedSyncActivity; // 0x10
	private static DelegateBridge __Hotfix0_GetRecentActBasicDataIter; // 0x18
	private static DelegateBridge __Hotfix0_GetRecentActThemeIter; // 0x20
	private static DelegateBridge __Hotfix0_GetActivityTimePoints; // 0x28
	private static DelegateBridge __Hotfix0_GetActMission; // 0x30
	private static DelegateBridge __Hotfix0_GetMissionEnumerator; // 0x38
	private static DelegateBridge __Hotfix0_GetMissionGroupData; // 0x40
	private static DelegateBridge __Hotfix0_GetAprilFoolScoreDatas; // 0x48
	private static DelegateBridge __Hotfix0_GetActivityHiddenStageData; // 0x50
	private static DelegateBridge __Hotfix0_GetStringRes; // 0x58
	private static DelegateBridge __Hotfix0_CheckIsHiddenStage; // 0x60
	private static DelegateBridge __Hotfix0__InitMissionMap; // 0x68
	private static DelegateBridge __Hotfix0__InitTimeSortedActInfos; // 0x70
	private static DelegateBridge __Hotfix0__InitTimeSortActThemes; // 0x78
	private static DelegateBridge __Hotfix0__InitHiddenStageMap; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x3116dfc VA: 0x759572edfc
	protected override Void OnInit() { }
	// RVA: 0x3117b84 VA: 0x759572fb84
	public Boolean HasEventDuringTime(Int64 startTs, Int64 endTs) { }
	// RVA: 0x3117c70 VA: 0x759572fc70
	public Boolean HasFixedSyncActivity(Int64 curTs) { }
	// RVA: 0x3117df4 VA: 0x759572fdf4
	public IEnumerator`1 GetRecentActBasicDataIter(Int64 curTs) { }
	// RVA: 0x3117eb8 VA: 0x759572feb8
	public IEnumerator`1 GetRecentActThemeIter(Int64 curTs) { }
	// RVA: 0x3117f7c VA: 0x759572ff7c
	public List`1 GetActivityTimePoints() { }
	// RVA: 0x3117fe4 VA: 0x759572ffe4
	public MissionData GetActMission(String missionId) { }
	// RVA: 0x3118080 VA: 0x7595730080
	public IEnumerator`1 GetMissionEnumerator(String actId) { }
	// RVA: 0x3118150 VA: 0x7595730150
	public MissionGroup GetMissionGroupData(String actId) { }
	// RVA: 0x31181ec VA: 0x75957301ec
	public List`1 GetAprilFoolScoreDatas(String stageId) { }
	// RVA: 0x31182e4 VA: 0x75957302e4
	public ActivityHiddenStageData GetActivityHiddenStageData(String stageId) { }
	// RVA: 0x3118428 VA: 0x7595730428
	public String GetStringRes(String actId, String key) { }
	// RVA: 0x3118578 VA: 0x7595730578
	public Boolean CheckIsHiddenStage(String stageId) { }
	// RVA: 0x31172dc VA: 0x759572f2dc
	private Void _InitMissionMap() { }
	// RVA: 0x3117510 VA: 0x759572f510
	private Void _InitTimeSortedActInfos() { }
	// RVA: 0x31177ac VA: 0x759572f7ac
	private Void _InitTimeSortActThemes() { }
	// RVA: 0x3117a38 VA: 0x759572fa38
	private Void _InitHiddenStageMap() { }
	// RVA: 0x3118650 VA: 0x7595730650
	public Void .ctor() { }
}
```