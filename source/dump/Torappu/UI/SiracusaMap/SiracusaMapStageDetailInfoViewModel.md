# SiracusaMapStageDetailInfoViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String <key>k__BackingField`

- `String <stageId>k__BackingField`

- `StageViewModel <stageViewModel>k__BackingField`

- `String <pointId>k__BackingField`

- `Int32 <stageRank>k__BackingField`

- `Boolean <isSelecting>k__BackingField`

- `SIRACUSA_MAP_AVG_TYPE <avgType>k__BackingField`

- `String <storyId>k__BackingField`

- `StoryData <storyData>k__BackingField`

- `String <storyBriefInfo>k__BackingField`


## Properties

- `String key`

- `String stageId`

- `StageViewModel stageViewModel`

- `String pointId`

- `Int32 stageRank`

- `Boolean isSelecting`

- `SIRACUSA_MAP_AVG_TYPE avgType`

- `String storyId`

- `StoryData storyData`

- `String storyBriefInfo`


## Methods

- `String get_key()`

- `Void set_key(String)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `StageViewModel get_stageViewModel()`

- `Void set_stageViewModel(StageViewModel)`

- `String get_pointId()`

- `Void set_pointId(String)`

- `Int32 get_stageRank()`

- `Void set_stageRank(Int32)`

- `Boolean get_isSelecting()`

- `Void set_isSelecting(Boolean)`

- `SIRACUSA_MAP_AVG_TYPE get_avgType()`

- `Void set_avgType(SIRACUSA_MAP_AVG_TYPE)`

- `String get_storyId()`

- `Void set_storyId(String)`

- `StoryData get_storyData()`

- `Void set_storyData(StoryData)`

- `String get_storyBriefInfo()`

- `Void set_storyBriefInfo(String)`

- `Void LoadBasicData(ISiracusaMapStageInfoModel)`

- `Void LoadAvgData(ISiracusaMapStageInfoModel, SIRACUSA_MAP_AVG_TYPE, StoryData, Dictionary`2)`

- `Void UpdateInfoSelectState(Boolean)`

- `String _TryGetBriefInfo(Dictionary`2, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStageDetailInfoViewModel : IHotfixable
{
	private String <key>k__BackingField; // 0x10
	private String <stageId>k__BackingField; // 0x18
	private StageViewModel <stageViewModel>k__BackingField; // 0x20
	private String <pointId>k__BackingField; // 0x28
	private Int32 <stageRank>k__BackingField; // 0x30
	private Boolean <isSelecting>k__BackingField; // 0x34
	private SIRACUSA_MAP_AVG_TYPE <avgType>k__BackingField; // 0x38
	private String <storyId>k__BackingField; // 0x40
	private StoryData <storyData>k__BackingField; // 0x48
	private String <storyBriefInfo>k__BackingField; // 0x50
	public const String EXPLORE_MORE_KEY; // 0x0
	private static DelegateBridge __Hotfix0_get_key; // 0x0
	private static DelegateBridge __Hotfix0_set_key; // 0x8
	private static DelegateBridge __Hotfix0_get_stageId; // 0x10
	private static DelegateBridge __Hotfix0_set_stageId; // 0x18
	private static DelegateBridge __Hotfix0_get_stageViewModel; // 0x20
	private static DelegateBridge __Hotfix0_set_stageViewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_pointId; // 0x30
	private static DelegateBridge __Hotfix0_set_pointId; // 0x38
	private static DelegateBridge __Hotfix0_get_stageRank; // 0x40
	private static DelegateBridge __Hotfix0_set_stageRank; // 0x48
	private static DelegateBridge __Hotfix0_get_isSelecting; // 0x50
	private static DelegateBridge __Hotfix0_set_isSelecting; // 0x58
	private static DelegateBridge __Hotfix0_get_avgType; // 0x60
	private static DelegateBridge __Hotfix0_set_avgType; // 0x68
	private static DelegateBridge __Hotfix0_get_storyId; // 0x70
	private static DelegateBridge __Hotfix0_set_storyId; // 0x78
	private static DelegateBridge __Hotfix0_get_storyData; // 0x80
	private static DelegateBridge __Hotfix0_set_storyData; // 0x88
	private static DelegateBridge __Hotfix0_get_storyBriefInfo; // 0x90
	private static DelegateBridge __Hotfix0_set_storyBriefInfo; // 0x98
	private static DelegateBridge __Hotfix0_LoadBasicData; // 0xa0
	private static DelegateBridge __Hotfix0_LoadAvgData; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateInfoSelectState; // 0xb0
	private static DelegateBridge __Hotfix0_CreateExploreViewModel; // 0xb8
	private static DelegateBridge __Hotfix0_CreateStoryOnlyStageDetailInfo; // 0xc0
	private static DelegateBridge __Hotfix0__TryGetBriefInfo; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public String key { get; set; }
	public String stageId { get; set; }
	public StageViewModel stageViewModel { get; set; }
	public String pointId { get; set; }
	public Int32 stageRank { get; set; }
	public Boolean isSelecting { get; set; }
	public SIRACUSA_MAP_AVG_TYPE avgType { get; set; }
	public String storyId { get; set; }
	public StoryData storyData { get; set; }
	public String storyBriefInfo { get; set; }

	// RVA: 0x23e0144 VA: 0x75949f8144
	public String get_key() { }
	// RVA: 0x23e1330 VA: 0x75949f9330
	private Void set_key(String value) { }
	// RVA: 0x23e13b4 VA: 0x75949f93b4
	public String get_stageId() { }
	// RVA: 0x23e141c VA: 0x75949f941c
	private Void set_stageId(String value) { }
	// RVA: 0x23e14a0 VA: 0x75949f94a0
	public StageViewModel get_stageViewModel() { }
	// RVA: 0x23e1508 VA: 0x75949f9508
	private Void set_stageViewModel(StageViewModel value) { }
	// RVA: 0x23e158c VA: 0x75949f958c
	public String get_pointId() { }
	// RVA: 0x23e15f4 VA: 0x75949f95f4
	private Void set_pointId(String value) { }
	// RVA: 0x23e1678 VA: 0x75949f9678
	public Int32 get_stageRank() { }
	// RVA: 0x23e16e0 VA: 0x75949f96e0
	private Void set_stageRank(Int32 value) { }
	// RVA: 0x23e175c VA: 0x75949f975c
	public Boolean get_isSelecting() { }
	// RVA: 0x23e17c4 VA: 0x75949f97c4
	private Void set_isSelecting(Boolean value) { }
	// RVA: 0x23e1844 VA: 0x75949f9844
	public SIRACUSA_MAP_AVG_TYPE get_avgType() { }
	// RVA: 0x23e18ac VA: 0x75949f98ac
	private Void set_avgType(SIRACUSA_MAP_AVG_TYPE value) { }
	// RVA: 0x23e1928 VA: 0x75949f9928
	public String get_storyId() { }
	// RVA: 0x23e1990 VA: 0x75949f9990
	private Void set_storyId(String value) { }
	// RVA: 0x23e1a14 VA: 0x75949f9a14
	public StoryData get_storyData() { }
	// RVA: 0x23e1a7c VA: 0x75949f9a7c
	private Void set_storyData(StoryData value) { }
	// RVA: 0x23e1b00 VA: 0x75949f9b00
	public String get_storyBriefInfo() { }
	// RVA: 0x23e1b68 VA: 0x75949f9b68
	private Void set_storyBriefInfo(String value) { }
	// RVA: 0x23dfef8 VA: 0x75949f7ef8
	public Void LoadBasicData(ISiracusaMapStageInfoModel stageInfo) { }
	// RVA: 0x23e06cc VA: 0x75949f86cc
	public Void LoadAvgData(ISiracusaMapStageInfoModel stageInfo, SIRACUSA_MAP_AVG_TYPE mapAvgType, StoryData storyInfo, Dictionary`2 briefInfoMap) { }
	// RVA: 0x23e01ac VA: 0x75949f81ac
	public Void UpdateInfoSelectState(Boolean select) { }
	// RVA: 0x23e1298 VA: 0x75949f9298
	public static SiracusaMapStageDetailInfoViewModel CreateExploreViewModel() { }
	// RVA: 0x23e1cf0 VA: 0x75949f9cf0
	public static Boolean CreateStoryOnlyStageDetailInfo(SiracusaMapMapNodeViewModel stageNodeViewModel, ref SiracusaMapStageDetailInfoViewModel detailViewModel) { }
	// RVA: 0x23e1bec VA: 0x75949f9bec
	private String _TryGetBriefInfo(Dictionary`2 briefInfoMap, String storyId) { }
	// RVA: 0x23dfe88 VA: 0x75949f7e88
	public Void .ctor() { }
}
```