# Act13sideDailyMissionItemViewModel

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `DailyMissionData m_missionPlayerData`

- `DailyMissionProgress m_progressData`

- `PrincipalData m_principalData`

- `DailyMissionData m_dailyMissionData`

- `OrgData m_orgData`

- `DailyMissionRewardGroupData m_rewardGroupData`

- `Int32 m_principalDescIdx`


## Properties

- `ISharedItemModel randomRewardItemModel`

- `PrincipalData principalData`

- `String principalName`

- `String principalId`

- `String principalDialog`

- `OrgData orgData`

- `DailyMissionData dailyMissionData`

- `DailyMissionProgress progress`

- `Int32 prestigeCount`


## Methods

- `ISharedItemModel get_randomRewardItemModel()`

- `PrincipalData get_principalData()`

- `String get_principalName()`

- `String get_principalId()`

- `String get_principalDialog()`

- `OrgData get_orgData()`

- `DailyMissionData get_dailyMissionData()`

- `DailyMissionProgress get_progress()`

- `Int32 get_prestigeCount()`

- `Void LoadData(String, DailyMissionData, DailyMissionProgress)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionItemViewModel : IHotfixable
{
	private DailyMissionData m_missionPlayerData; // 0x10
	private DailyMissionProgress m_progressData; // 0x18
	private PrincipalData m_principalData; // 0x20
	private DailyMissionData m_dailyMissionData; // 0x28
	private OrgData m_orgData; // 0x30
	private DailyMissionRewardGroupData m_rewardGroupData; // 0x38
	private Int32 m_principalDescIdx; // 0x40
	private List`1 m_rewardList; // 0x48
	private static DelegateBridge __Hotfix0_get_rewardList; // 0x0
	private static DelegateBridge __Hotfix0_get_randomRewardItemModel; // 0x8
	private static DelegateBridge __Hotfix0_get_principalData; // 0x10
	private static DelegateBridge __Hotfix0_get_principalName; // 0x18
	private static DelegateBridge __Hotfix0_get_principalId; // 0x20
	private static DelegateBridge __Hotfix0_get_principalDialog; // 0x28
	private static DelegateBridge __Hotfix0_get_orgData; // 0x30
	private static DelegateBridge __Hotfix0_get_dailyMissionData; // 0x38
	private static DelegateBridge __Hotfix0_get_progress; // 0x40
	private static DelegateBridge __Hotfix0_get_prestigeCount; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public List`1 rewardList { get; }
	public ISharedItemModel randomRewardItemModel { get; }
	public PrincipalData principalData { get; }
	public String principalName { get; }
	public String principalId { get; }
	public String principalDialog { get; }
	public OrgData orgData { get; }
	public DailyMissionData dailyMissionData { get; }
	public DailyMissionProgress progress { get; }
	public Int32 prestigeCount { get; }

	// RVA: 0x3437edc VA: 0x7595a4fedc
	public List`1 get_rewardList() { }
	// RVA: 0x3437f44 VA: 0x7595a4ff44
	public ISharedItemModel get_randomRewardItemModel() { }
	// RVA: 0x3437fe4 VA: 0x7595a4ffe4
	public PrincipalData get_principalData() { }
	// RVA: 0x343804c VA: 0x7595a5004c
	public String get_principalName() { }
	// RVA: 0x34380e0 VA: 0x7595a500e0
	public String get_principalId() { }
	// RVA: 0x3438158 VA: 0x7595a50158
	public String get_principalDialog() { }
	// RVA: 0x3438210 VA: 0x7595a50210
	public OrgData get_orgData() { }
	// RVA: 0x3438278 VA: 0x7595a50278
	public DailyMissionData get_dailyMissionData() { }
	// RVA: 0x34382e0 VA: 0x7595a502e0
	public DailyMissionProgress get_progress() { }
	// RVA: 0x3438348 VA: 0x7595a50348
	public Int32 get_prestigeCount() { }
	// RVA: 0x3437858 VA: 0x7595a4f858
	public Void LoadData(String actId, DailyMissionData missionPlayerData, DailyMissionProgress progressData) { }
	// RVA: 0x3437794 VA: 0x7595a4f794
	public Void .ctor() { }
}
```