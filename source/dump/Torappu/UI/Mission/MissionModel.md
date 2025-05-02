# MissionModel

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MissionViewModel mainMissions`

- `Boolean haveNotUnlockedSubMissionFlag`

- `BranchWrappedGroup branchGroup`

- `MissionDailyRewards dailyReward`


## Methods

- `Boolean _TryGetCurrStartMissionGroup(out)`

- `Boolean TryGetCurrStartMissionGroup(out)`

- `GuideMissionGroupInfo GetCurrGuideMissionGroupInfo()`

- `Boolean IsResFullOpen()`

- `Boolean IsResFullPause()`

- `Int32 GetResFullOpenRemainDay()`

- `Boolean IsStartMissionGroupUnlock()`

- `Boolean IsAllStartMissionsComplete()`

- `Void RefreshPlayerData(MissionType)`

- `Void _DealWithMissionData(Dictionary`2, MissionType)`

- `Void DealWithPlayerData(Dictionary`2)`

- `Single GetRandomSeed(String)`

- `Void SetBranchFold(String)`

- `Void SetBranchSpread(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionModel : PageSingleComponent, IStateBean, IHotfixable, IDataBindWrapper
{
	public const Single DEFAULT_ITEM_DESC_SCALE; // 0x0
	public List`1 startMissions; // 0x20
	public MissionViewModel mainMissions; // 0x28
	public List`1 branchMissions; // 0x30
	public Boolean haveNotUnlockedSubMissionFlag; // 0x38
	public BranchWrappedGroup branchGroup; // 0x40
	public List`1 dailyMissions; // 0x48
	public List`1 weeklyMissions; // 0x50
	public MissionDailyRewards dailyReward; // 0x58
	public Action`1 missionTypeRefresh; // 0x60
	private static DelegateBridge __Hotfix0__TryGetCurrStartMissionGroup; // 0x0
	private static DelegateBridge __Hotfix0_TryGetCurrStartMissionGroup; // 0x8
	private static DelegateBridge __Hotfix0_GetCurrGuideMissionGroupInfo; // 0x10
	private static DelegateBridge __Hotfix0_IsResFullOpen; // 0x18
	private static DelegateBridge __Hotfix0_IsResFullPause; // 0x20
	private static DelegateBridge __Hotfix0_GetResFullOpenRemainDay; // 0x28
	private static DelegateBridge __Hotfix0_IsStartMissionGroupUnlock; // 0x30
	private static DelegateBridge __Hotfix0_IsAllStartMissionsComplete; // 0x38
	private static DelegateBridge __Hotfix0_RefreshRewardData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshPlayerDataStatic; // 0x48
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x50
	private static DelegateBridge __Hotfix0__MissionSortingRefVal; // 0x58
	private static DelegateBridge __Hotfix0__MissionSortingCompare; // 0x60
	private static DelegateBridge __Hotfix0__DealWithMissionData; // 0x68
	private static DelegateBridge __Hotfix0_DealWithPlayerData; // 0x70
	private static DelegateBridge __Hotfix0_GetRandomSeed; // 0x78
	private static DelegateBridge __Hotfix0_SetBranchFold; // 0x80
	private static DelegateBridge __Hotfix0_SetBranchSpread; // 0x88
	private static DelegateBridge __Hotfix0_GetHashString; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x273575c VA: 0x7594d4d75c
	private Boolean _TryGetCurrStartMissionGroup(out MissionGroup missionGroupData) { }
	// RVA: 0x2735894 VA: 0x7594d4d894
	public Boolean TryGetCurrStartMissionGroup(out MissionGroup missionGruopData) { }
	// RVA: 0x2735914 VA: 0x7594d4d914
	public GuideMissionGroupInfo GetCurrGuideMissionGroupInfo() { }
	// RVA: 0x2735a24 VA: 0x7594d4da24
	public Boolean IsResFullOpen() { }
	// RVA: 0x2735adc VA: 0x7594d4dadc
	public Boolean IsResFullPause() { }
	// RVA: 0x2735b94 VA: 0x7594d4db94
	public Int32 GetResFullOpenRemainDay() { }
	// RVA: 0x2735c44 VA: 0x7594d4dc44
	public Boolean IsStartMissionGroupUnlock() { }
	// RVA: 0x2735d40 VA: 0x7594d4dd40
	public Boolean IsAllStartMissionsComplete() { }
	// RVA: 0x2735e7c VA: 0x7594d4de7c
	public static Void RefreshRewardData(MissionType type, Boolean ignoreNotify) { }
	// RVA: 0x2735fe4 VA: 0x7594d4dfe4
	public static Void RefreshPlayerDataStatic(MissionType missionType) { }
	// RVA: 0x27360dc VA: 0x7594d4e0dc
	public Void RefreshPlayerData(MissionType missionType) { }
	// RVA: 0x2736d08 VA: 0x7594d4ed08
	private static Int32 _MissionSortingRefVal(MissionViewModel v) { }
	// RVA: 0x2736d94 VA: 0x7594d4ed94
	private static Int32 _MissionSortingCompare(MissionViewModel v0, MissionViewModel v1) { }
	// RVA: 0x2736448 VA: 0x7594d4e448
	private Void _DealWithMissionData(Dictionary`2 missionPlayerData, MissionType missionType) { }
	// RVA: 0x2737368 VA: 0x7594d4f368
	public Void DealWithPlayerData(Dictionary`2 missionPlayerData) { }
	// RVA: 0x2737c64 VA: 0x7594d4fc64
	public Single GetRandomSeed(String missionName) { }
	// RVA: 0x2737d94 VA: 0x7594d4fd94
	public Void SetBranchFold(String foldId) { }
	// RVA: 0x2737e70 VA: 0x7594d4fe70
	public Void SetBranchSpread(String foldId) { }
	// RVA: 0x2737cf4 VA: 0x7594d4fcf4
	public static Single GetHashString(String hashId) { }
	// RVA: 0x2737f48 VA: 0x7594d4ff48
	public Void .ctor() { }
}
```