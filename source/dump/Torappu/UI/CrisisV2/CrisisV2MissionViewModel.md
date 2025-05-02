# CrisisV2MissionViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Boolean canClaimAll`

- `String mapId`

- `Int32 sequenceNum`

- `CrisisV2StageType m_stageType`

- `String m_seasonId`

- `Int64 m_rewardEndTime`


## Methods

- `Void LoadData(String)`

- `Void RefreshData()`

- `Void _LoadBagMissionData(Dictionary`2)`

- `Void _LoadChallengeMissionData(Dictionary`2)`

- `Void _LoadTreasureMissionData(Dictionary`2)`

- `Void _RefreshMissionItem(CrisisV2MissionItemModel, Dictionary`2, Dictionary`2, Dictionary`2)`

- `SortState _GetMissionSortState(NodeState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MissionViewModel : IHotfixable
{
	public List`1 sortedMissions; // 0x10
	public Boolean canClaimAll; // 0x18
	public String mapId; // 0x20
	public Int32 sequenceNum; // 0x28
	private CrisisV2StageType m_stageType; // 0x2c
	private String m_seasonId; // 0x30
	private Int64 m_rewardEndTime; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_GetAllCompleteMissions; // 0x10
	private static DelegateBridge __Hotfix0__LoadBagMissionData; // 0x18
	private static DelegateBridge __Hotfix0__LoadChallengeMissionData; // 0x20
	private static DelegateBridge __Hotfix0__LoadTreasureMissionData; // 0x28
	private static DelegateBridge __Hotfix0__RefreshMissionItem; // 0x30
	private static DelegateBridge __Hotfix0__GetMissionSortState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2bf3764 VA: 0x759520b764
	public Void LoadData(String mapId_) { }
	// RVA: 0x2bf45bc VA: 0x759520c5bc
	public Void RefreshData() { }
	// RVA: 0x2bf4a3c VA: 0x759520ca3c
	public List`1 GetAllCompleteMissions() { }
	// RVA: 0x2bf3944 VA: 0x759520b944
	private Void _LoadBagMissionData(Dictionary`2 bag) { }
	// RVA: 0x2bf3d94 VA: 0x759520bd94
	private Void _LoadChallengeMissionData(Dictionary`2 challenge) { }
	// RVA: 0x2bf4204 VA: 0x759520c204
	private Void _LoadTreasureMissionData(Dictionary`2 treasure) { }
	// RVA: 0x2bf4894 VA: 0x759520c894
	private Void _RefreshMissionItem(CrisisV2MissionItemModel missionModel, Dictionary`2 challengeInfo, Dictionary`2 treasureInfo, Dictionary`2 runePackInfo) { }
	// RVA: 0x2bf4be0 VA: 0x759520cbe0
	private SortState _GetMissionSortState(NodeState state) { }
	// RVA: 0x2bf4c68 VA: 0x759520cc68
	public Void .ctor() { }
}
```