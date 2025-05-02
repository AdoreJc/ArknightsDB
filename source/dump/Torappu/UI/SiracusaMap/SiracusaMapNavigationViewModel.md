# SiracusaMapNavigationViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String <groupId>k__BackingField`

- `String <selectingEntryId>k__BackingField`

- `SiracusaMapStageDetailInfoViewModel <selectingStageInfo>k__BackingField`

- `Boolean needAutoPlayNaviTween`


## Properties

- `String groupId`

- `String selectingEntryId`

- `SiracusaMapStageDetailInfoViewModel selectingStageInfo`


## Methods

- `String get_groupId()`

- `Void set_groupId(String)`

- `String get_selectingEntryId()`

- `Void set_selectingEntryId(String)`

- `SiracusaMapStageDetailInfoViewModel get_selectingStageInfo()`

- `Void set_selectingStageInfo(SiracusaMapStageDetailInfoViewModel)`

- `Void LoadData(String, Dictionary`2)`

- `String TryGetNavigationIdByType(NavigationType)`

- `String TryToCalcInitStageKey(String, String)`

- `Void UpdateNavigation(Dictionary`2, String)`

- `Void _UpdateAvgNavigation(Dictionary`2, SiracusaMapNavigationDetailViewModel, String)`

- `Void _UpdateLevelNavigation(Dictionary`2, SiracusaMapNavigationDetailViewModel, String)`

- `Void UpdateSelectingEntry(String)`

- `Void UpdateSelectingStage(SiracusaMapStageDetailInfoViewModel)`

- `SiracusaMapNavigationDetailViewModel TryGetCurNavigationDetailViewModel()`

- `Boolean _IsZoneAllStagePassed(List`1)`

- `Boolean _IsZoneLastStageAvg(List`1)`

- `Boolean _NeedShowExploreMore(List`1, List`1, Boolean)`

- `Boolean _NeedShowLevelExploreMore(List`1, List`1)`

- `Boolean _NeedShowAvgExploreMore(List`1, Dictionary`2)`

- `NavigationInfoData _TryGetNavigationInfoData(Dictionary`2, String)`

- `Void _TryLoadAvgData(List`1, List`1, SiracusaMapStageInfoViewModel, SIRACUSA_MAP_AVG_TYPE, StoryData, Dictionary`2, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapNavigationViewModel : IHotfixable
{
	private String <groupId>k__BackingField; // 0x10
	public Dictionary`2 navigationDetailViewModelDic; // 0x18
	private String <selectingEntryId>k__BackingField; // 0x20
	private SiracusaMapStageDetailInfoViewModel <selectingStageInfo>k__BackingField; // 0x28
	public Boolean needAutoPlayNaviTween; // 0x30
	private List`1 m_filteredPointIds; // 0x38
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_set_groupId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectingEntryId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectingEntryId; // 0x18
	private static DelegateBridge __Hotfix0_get_selectingStageInfo; // 0x20
	private static DelegateBridge __Hotfix0_set_selectingStageInfo; // 0x28
	private static DelegateBridge __Hotfix0_get_filteredPointIds; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_TryGetNavigationIdByType; // 0x40
	private static DelegateBridge __Hotfix0_TryToCalcInitStageKey; // 0x48
	private static DelegateBridge __Hotfix0_UpdateNavigation; // 0x50
	private static DelegateBridge __Hotfix0__UpdateAvgNavigation; // 0x58
	private static DelegateBridge __Hotfix0__UpdateLevelNavigation; // 0x60
	private static DelegateBridge __Hotfix0_UpdateSelectingEntry; // 0x68
	private static DelegateBridge __Hotfix0_UpdateSelectingStage; // 0x70
	private static DelegateBridge __Hotfix0_TryGetCurNavigationDetailViewModel; // 0x78
	private static DelegateBridge __Hotfix0__IsZoneAllStagePassed; // 0x80
	private static DelegateBridge __Hotfix0__IsZoneLastStageAvg; // 0x88
	private static DelegateBridge __Hotfix0__NeedShowExploreMore; // 0x90
	private static DelegateBridge __Hotfix0__NeedShowLevelExploreMore; // 0x98
	private static DelegateBridge __Hotfix0__NeedShowAvgExploreMore; // 0xa0
	private static DelegateBridge __Hotfix0__TryGetNavigationInfoData; // 0xa8
	private static DelegateBridge __Hotfix0__TryLoadAvgData; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public String groupId { get; set; }
	public String selectingEntryId { get; set; }
	public SiracusaMapStageDetailInfoViewModel selectingStageInfo { get; set; }
	public List`1 filteredPointIds { get; }

	// RVA: 0x23dd7f0 VA: 0x75949f57f0
	public String get_groupId() { }
	// RVA: 0x23dd964 VA: 0x75949f5964
	private Void set_groupId(String value) { }
	// RVA: 0x23dd9e8 VA: 0x75949f59e8
	public String get_selectingEntryId() { }
	// RVA: 0x23dda50 VA: 0x75949f5a50
	private Void set_selectingEntryId(String value) { }
	// RVA: 0x23ddad4 VA: 0x75949f5ad4
	public SiracusaMapStageDetailInfoViewModel get_selectingStageInfo() { }
	// RVA: 0x23ddb3c VA: 0x75949f5b3c
	private Void set_selectingStageInfo(SiracusaMapStageDetailInfoViewModel value) { }
	// RVA: 0x23ddbc0 VA: 0x75949f5bc0
	public List`1 get_filteredPointIds() { }
	// RVA: 0x23ddc28 VA: 0x75949f5c28
	public Void LoadData(String groupId, Dictionary`2 mapZoneInfoViewModels) { }
	// RVA: 0x23de738 VA: 0x75949f6738
	public String TryGetNavigationIdByType(NavigationType type) { }
	// RVA: 0x23de8f0 VA: 0x75949f68f0
	public String TryToCalcInitStageKey(String stageId, String storyId) { }
	// RVA: 0x23de9dc VA: 0x75949f69dc
	public Void UpdateNavigation(Dictionary`2 mapZoneInfoViewModels, String initSelectingStageKey) { }
	// RVA: 0x23dec7c VA: 0x75949f6c7c
	private Void _UpdateAvgNavigation(Dictionary`2 mapZoneInfoViewModels, SiracusaMapNavigationDetailViewModel selectNavModel, String initSelectingStageKey) { }
	// RVA: 0x23df1bc VA: 0x75949f71bc
	private Void _UpdateLevelNavigation(Dictionary`2 mapZoneInfoViewModels, SiracusaMapNavigationDetailViewModel selectNavModel, String initSelectingStageKey) { }
	// RVA: 0x23e033c VA: 0x75949f833c
	public Void UpdateSelectingEntry(String entryId) { }
	// RVA: 0x23e022c VA: 0x75949f822c
	public Void UpdateSelectingStage(SiracusaMapStageDetailInfoViewModel infoViewModel) { }
	// RVA: 0x23dd6fc VA: 0x75949f56fc
	public SiracusaMapNavigationDetailViewModel TryGetCurNavigationDetailViewModel() { }
	// RVA: 0x23e03e8 VA: 0x75949f83e8
	private Boolean _IsZoneAllStagePassed(List`1 stageNodes) { }
	// RVA: 0x23e04e8 VA: 0x75949f84e8
	private Boolean _IsZoneLastStageAvg(List`1 stageNodes) { }
	// RVA: 0x23e05e8 VA: 0x75949f85e8
	private Boolean _NeedShowExploreMore(List`1 naviInfoViewModels, List`1 stageNodes, Boolean isAvgNavigation) { }
	// RVA: 0x23e02ac VA: 0x75949f82ac
	private Boolean _NeedShowLevelExploreMore(List`1 naviInfoViewModels, List`1 stageNodes) { }
	// RVA: 0x23dfb2c VA: 0x75949f7b2c
	private Boolean _NeedShowAvgExploreMore(List`1 naviInfoViewModels, Dictionary`2 mapZoneInfoViewModels) { }
	// RVA: 0x23de4d4 VA: 0x75949f64d4
	private NavigationInfoData _TryGetNavigationInfoData(Dictionary`2 navigationInfoMap, String entryId) { }
	// RVA: 0x23df878 VA: 0x75949f7878
	private Void _TryLoadAvgData(List`1 avgInfoViewModels, List`1 filteredPointIdList, SiracusaMapStageInfoViewModel stageNodeViewModel, SIRACUSA_MAP_AVG_TYPE siracusaMapAvgType, StoryData story, Dictionary`2 briefInfoMap, String initSelectingStageKey) { }
	// RVA: 0x23e0808 VA: 0x75949f8808
	public Void .ctor() { }
}
```