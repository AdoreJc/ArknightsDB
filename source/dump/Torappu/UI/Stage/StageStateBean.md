# StageStateBean

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneViewProperty selectedZoneProperty`

- `PreviewConfigViewProperty previewConfigProperty`

- `UIPageFinder m_pageFinder`


## Properties

- `String selectedZoneId`

- `StageDiffGroup stageDiffGroup`

- `StageId selectedStageId`

- `StageViewModel selectedStageModel`

- `StageViewModel selectedNormalStageModel`

- `StageViewModel selectedHardStageModel`


## Methods

- `Void InitData()`

- `ZoneViewModel FindZone(String)`

- `Void RefreshCampaignZoneData(String)`

- `Void SetZoneTypeHome()`

- `Void SetZoneTypeMixStory()`

- `Void SetZoneTypeWeekly()`

- `Void SetZoneTypePermMode()`

- `Void SetZoneTypeCampaign()`

- `Void SetZoneTypeCrisis()`

- `Void SetZoneTypeActivity(String)`

- `Void FetchCrisisV2Data(CrisisV2CacheServerData)`

- `Void RefreshPermModeModel()`

- `Void _SetZoneTypeWithZoneModel(ZoneViewModel)`

- `Void _GatherMutableStages(Dictionary`2)`

- `Void SetZoneType(ZoneViewType, String)`

- `Void UpdateZoneGroupStatus()`

- `Void _UpdateZoneGroupStatus(ZoneViewType)`

- `Void SetFocusedZone(String)`

- `Void SetSelectZone(String, StageDiffGroup)`

- `Boolean IsZoneUnlocked(String)`

- `String get_selectedZoneId()`

- `StageDiffGroup get_stageDiffGroup()`

- `StageId get_selectedStageId()`

- `StageViewModel get_selectedStageModel()`

- `StageViewModel get_selectedNormalStageModel()`

- `StageViewModel get_selectedHardStageModel()`

- `Void SetSelectStage(String, SpecialStageType)`

- `Void SetSixStarStageSelectingStatus(StageSixStarRuneStatus)`

- `StageViewModel GetStageEntry(String)`

- `Void ToggleAutoBattle()`

- `DisplayInfo GetSpecialStoryStageWithProgress(String)`

- `Void RefreshMutableStages()`

- `Void _GatherSixStarStages(Dictionary`2)`

- `Void RefreshSixStarStages()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public ZoneViewProperty selectedZoneProperty; // 0x18
	public PreviewConfigViewProperty previewConfigProperty; // 0x20
	public ListDict`2 zoneGroups; // 0x28
	private Dictionary`2 m_zoneSearchTable; // 0x30
	private Dictionary`2 m_mutableStages; // 0x38
	private Dictionary`2 m_sixStarStages; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_FindLeftMainlineZone; // 0x8
	private static DelegateBridge __Hotfix0_FindRightMainlineZone; // 0x10
	private static DelegateBridge __Hotfix0_FindZone; // 0x18
	private static DelegateBridge __Hotfix0_RefreshCampaignZoneData; // 0x20
	private static DelegateBridge __Hotfix0_SetZoneTypeHome; // 0x28
	private static DelegateBridge __Hotfix0_SetZoneTypeMixStory; // 0x30
	private static DelegateBridge __Hotfix0_SetZoneTypeWeekly; // 0x38
	private static DelegateBridge __Hotfix0_SetZoneTypePermMode; // 0x40
	private static DelegateBridge __Hotfix0_SetZoneTypeCampaign; // 0x48
	private static DelegateBridge __Hotfix0_SetZoneTypeCrisis; // 0x50
	private static DelegateBridge __Hotfix0_SetZoneTypeActivity; // 0x58
	private static DelegateBridge __Hotfix0_FetchCrisisV2Data; // 0x60
	private static DelegateBridge __Hotfix0_RefreshPermModeModel; // 0x68
	private static DelegateBridge __Hotfix0__FindNeighbourMainlineZone; // 0x70
	private static DelegateBridge __Hotfix0__FindPrevMainlineZoneId; // 0x78
	private static DelegateBridge __Hotfix0__FindNextMainlineZoneId; // 0x80
	private static DelegateBridge __Hotfix0__SetZoneTypeWithZoneModel; // 0x88
	private static DelegateBridge __Hotfix0__GatherMutableStages; // 0x90
	private static DelegateBridge __Hotfix0_SetZoneType; // 0x98
	private static DelegateBridge __Hotfix0_UpdateZoneGroupStatus; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateZoneGroupStatus; // 0xa8
	private static DelegateBridge __Hotfix0_SetFocusedZone; // 0xb0
	private static DelegateBridge __Hotfix0_SetSelectZone; // 0xb8
	private static DelegateBridge __Hotfix0_IsZoneUnlocked; // 0xc0
	private static DelegateBridge __Hotfix0_get_selectedZoneId; // 0xc8
	private static DelegateBridge __Hotfix0_get_stageDiffGroup; // 0xd0
	private static DelegateBridge __Hotfix0_get_selectedStageId; // 0xd8
	private static DelegateBridge __Hotfix0_get_selectedStageModel; // 0xe0
	private static DelegateBridge __Hotfix0_get_selectedNormalStageModel; // 0xe8
	private static DelegateBridge __Hotfix0_get_selectedHardStageModel; // 0xf0
	private static DelegateBridge __Hotfix0_SetSelectStage; // 0xf8
	private static DelegateBridge __Hotfix0_SetSixStarStageSelectingStatus; // 0x100
	private static DelegateBridge __Hotfix0_GetStageEntry; // 0x108
	private static DelegateBridge __Hotfix0_ToggleAutoBattle; // 0x110
	private static DelegateBridge __Hotfix0_GetSpecialStoryStageWithProgress; // 0x118
	private static DelegateBridge __Hotfix0_RefreshMutableStages; // 0x120
	private static DelegateBridge __Hotfix0__GatherSixStarStages; // 0x128
	private static DelegateBridge __Hotfix0_RefreshSixStarStages; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	public String selectedZoneId { get; }
	public StageDiffGroup stageDiffGroup { get; }
	public StageId selectedStageId { get; }
	public StageViewModel selectedStageModel { get; }
	public StageViewModel selectedNormalStageModel { get; }
	public StageViewModel selectedHardStageModel { get; }

	// RVA: 0x2f7ac4c VA: 0x7595592c4c
	public Void InitData() { }
	// RVA: 0x2f7bdf4 VA: 0x7595593df4
	public KeyValuePair`2 FindLeftMainlineZone(String zoneId) { }
	// RVA: 0x2f7c02c VA: 0x759559402c
	public KeyValuePair`2 FindRightMainlineZone(String zoneId) { }
	// RVA: 0x2f7c0b0 VA: 0x75955940b0
	public ZoneViewModel FindZone(String zoneId) { }
	// RVA: 0x2f7c174 VA: 0x7595594174
	public Void RefreshCampaignZoneData(String zoneId) { }
	// RVA: 0x2f7c2f8 VA: 0x75955942f8
	public Void SetZoneTypeHome() { }
	// RVA: 0x2f7c430 VA: 0x7595594430
	public Void SetZoneTypeMixStory() { }
	// RVA: 0x2f7c4a0 VA: 0x75955944a0
	public Void SetZoneTypeWeekly() { }
	// RVA: 0x2f7c510 VA: 0x7595594510
	public Void SetZoneTypePermMode() { }
	// RVA: 0x2f7c580 VA: 0x7595594580
	public Void SetZoneTypeCampaign() { }
	// RVA: 0x2f7c5f0 VA: 0x75955945f0
	public Void SetZoneTypeCrisis() { }
	// RVA: 0x2f7c660 VA: 0x7595594660
	public Void SetZoneTypeActivity(String activityId) { }
	// RVA: 0x2f7c6e4 VA: 0x75955946e4
	public Void FetchCrisisV2Data(CrisisV2CacheServerData sharedData) { }
	// RVA: 0x2f7c820 VA: 0x7595594820
	public Void RefreshPermModeModel() { }
	// RVA: 0x2f7be78 VA: 0x7595593e78
	private KeyValuePair`2 _FindNeighbourMainlineZone(String zoneId, LeftOrRight dir) { }
	// RVA: 0x2f7c944 VA: 0x7595594944
	private static String _FindPrevMainlineZoneId(String zoneId) { }
	// RVA: 0x2f7caa8 VA: 0x7595594aa8
	private static String _FindNextMainlineZoneId(String zoneId) { }
	// RVA: 0x2f7cbd8 VA: 0x7595594bd8
	private Void _SetZoneTypeWithZoneModel(ZoneViewModel zoneModel) { }
	// RVA: 0x2f7b238 VA: 0x7595593238
	private Void _GatherMutableStages(Dictionary`2 seachTable) { }
	// RVA: 0x2f7c368 VA: 0x7595594368
	public Void SetZoneType(ZoneViewType zoneType, String activityId) { }
	// RVA: 0x2f7ce48 VA: 0x7595594e48
	public Void UpdateZoneGroupStatus() { }
	// RVA: 0x2f7cd20 VA: 0x7595594d20
	private Void _UpdateZoneGroupStatus(ZoneViewType selectedType) { }
	// RVA: 0x2f7cec0 VA: 0x7595594ec0
	public Void SetFocusedZone(String zoneId) { }
	// RVA: 0x2f7503c VA: 0x759558d03c
	public Void SetSelectZone(String zoneId, StageDiffGroup diffGroup) { }
	// RVA: 0x2f74eb8 VA: 0x759558ceb8
	public Boolean IsZoneUnlocked(String zoneId) { }
	// RVA: 0x2f74cb0 VA: 0x759558ccb0
	public String get_selectedZoneId() { }
	// RVA: 0x2f74db4 VA: 0x759558cdb4
	public StageDiffGroup get_stageDiffGroup() { }
	// RVA: 0x2f7d028 VA: 0x7595595028
	public StageId get_selectedStageId() { }
	// RVA: 0x2f7d174 VA: 0x7595595174
	public StageViewModel get_selectedStageModel() { }
	// RVA: 0x2f7d2b4 VA: 0x75955952b4
	public StageViewModel get_selectedNormalStageModel() { }
	// RVA: 0x2f7d354 VA: 0x7595595354
	public StageViewModel get_selectedHardStageModel() { }
	// RVA: 0x2f7d3f4 VA: 0x75955953f4
	public Void SetSelectStage(String normalStageId, SpecialStageType stageSelectType) { }
	// RVA: 0x2f7d634 VA: 0x7595595634
	public Void SetSixStarStageSelectingStatus(StageSixStarRuneStatus newStatus) { }
	// RVA: 0x2f7d778 VA: 0x7595595778
	public StageViewModel GetStageEntry(String stageId) { }
	// RVA: 0x2f7d848 VA: 0x7595595848
	public Void ToggleAutoBattle() { }
	// RVA: 0x2f7d918 VA: 0x7595595918
	public DisplayInfo GetSpecialStoryStageWithProgress(String stageId) { }
	// RVA: 0x2f7dc84 VA: 0x7595595c84
	public Void RefreshMutableStages() { }
	// RVA: 0x2f7b890 VA: 0x7595593890
	private Void _GatherSixStarStages(Dictionary`2 searchTable) { }
	// RVA: 0x2f7dfe8 VA: 0x7595595fe8
	public Void RefreshSixStarStages() { }
	// RVA: 0x2f7e1a4 VA: 0x75955961a4
	public Void .ctor() { }
}
```