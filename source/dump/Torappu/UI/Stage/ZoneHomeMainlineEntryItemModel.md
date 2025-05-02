# ZoneHomeMainlineEntryItemModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneHomeEntryLockInfo lockInfo`

- `String <chapterId>k__BackingField`

- `ZoneData <zoneData>k__BackingField`

- `StageData <stageData>k__BackingField`

- `Boolean <isAllChapterPass>k__BackingField`

- `Boolean <isChapterPass>k__BackingField`

- `Int32 <chapterIndex>k__BackingField`


## Properties

- `String chapterId`

- `ZoneData zoneData`

- `StageData stageData`

- `Boolean isAllChapterPass`

- `Boolean isChapterPass`

- `Int32 chapterIndex`


## Methods

- `String get_chapterId()`

- `Void set_chapterId(String)`

- `ZoneData get_zoneData()`

- `Void set_zoneData(ZoneData)`

- `StageData get_stageData()`

- `Void set_stageData(StageData)`

- `Boolean get_isAllChapterPass()`

- `Void set_isAllChapterPass(Boolean)`

- `Boolean get_isChapterPass()`

- `Void set_isChapterPass(Boolean)`

- `Int32 get_chapterIndex()`

- `Void set_chapterIndex(Int32)`

- `ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeMainlineEntryItemModel : ZoneHomeEntryItemModel
{
	private ZoneHomeEntryLockInfo lockInfo; // 0x40
	private String <chapterId>k__BackingField; // 0x58
	private ZoneData <zoneData>k__BackingField; // 0x60
	private StageData <stageData>k__BackingField; // 0x68
	private Boolean <isAllChapterPass>k__BackingField; // 0x70
	private Boolean <isChapterPass>k__BackingField; // 0x71
	private Int32 <chapterIndex>k__BackingField; // 0x74
	private static DelegateBridge __Hotfix0_get_chapterId; // 0x0
	private static DelegateBridge __Hotfix0_set_chapterId; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneData; // 0x10
	private static DelegateBridge __Hotfix0_set_zoneData; // 0x18
	private static DelegateBridge __Hotfix0_get_stageData; // 0x20
	private static DelegateBridge __Hotfix0_set_stageData; // 0x28
	private static DelegateBridge __Hotfix0_get_isAllChapterPass; // 0x30
	private static DelegateBridge __Hotfix0_set_isAllChapterPass; // 0x38
	private static DelegateBridge __Hotfix0_get_isChapterPass; // 0x40
	private static DelegateBridge __Hotfix0_set_isChapterPass; // 0x48
	private static DelegateBridge __Hotfix0_get_chapterIndex; // 0x50
	private static DelegateBridge __Hotfix0_set_chapterIndex; // 0x58
	private static DelegateBridge __Hotfix0_GetLockInfo; // 0x60
	private static DelegateBridge __Hotfix0__GetMainlineZoneGroupViewModel; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge __Hotfix0__UpdateSortIndex; // 0x78
	private static DelegateBridge __Hotfix0_CreateMainlineDisplayThemeEntry; // 0x80
	private static DelegateBridge __Hotfix0__CreateMainlineDisplayLockInfo; // 0x88
	private static DelegateBridge __Hotfix0__LoadFinishZoneData; // 0x90
	private static DelegateBridge __Hotfix0__LoadProcessingZoneData; // 0x98
	private static DelegateBridge __Hotfix0__GetChapterCurGoingStageData; // 0xa0
	private static DelegateBridge __Hotfix0__LoadData; // 0xa8
	private static DelegateBridge __Hotfix0__CreateViewModel; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public String chapterId { get; set; }
	public ZoneData zoneData { get; set; }
	public StageData stageData { get; set; }
	public Boolean isAllChapterPass { get; set; }
	public Boolean isChapterPass { get; set; }
	private Int32 chapterIndex { get; set; }

	// RVA: 0x2effffc VA: 0x7595517ffc
	public String get_chapterId() { }
	// RVA: 0x2f00064 VA: 0x7595518064
	private Void set_chapterId(String value) { }
	// RVA: 0x2f000e8 VA: 0x75955180e8
	public ZoneData get_zoneData() { }
	// RVA: 0x2f00150 VA: 0x7595518150
	private Void set_zoneData(ZoneData value) { }
	// RVA: 0x2efbbe0 VA: 0x7595513be0
	public StageData get_stageData() { }
	// RVA: 0x2f001d4 VA: 0x75955181d4
	private Void set_stageData(StageData value) { }
	// RVA: 0x2efbb10 VA: 0x7595513b10
	public Boolean get_isAllChapterPass() { }
	// RVA: 0x2f00258 VA: 0x7595518258
	private Void set_isAllChapterPass(Boolean value) { }
	// RVA: 0x2efbb78 VA: 0x7595513b78
	public Boolean get_isChapterPass() { }
	// RVA: 0x2f002d8 VA: 0x75955182d8
	private Void set_isChapterPass(Boolean value) { }
	// RVA: 0x2f00358 VA: 0x7595518358
	private Int32 get_chapterIndex() { }
	// RVA: 0x2f003c0 VA: 0x75955183c0
	private Void set_chapterIndex(Int32 value) { }
	// RVA: 0x2f0043c VA: 0x759551843c
	public override ZoneHomeEntryLockInfo GetLockInfo() { }
	// RVA: 0x2f004cc VA: 0x75955184cc
	private static StageStorylineMainlineChapterViewModel _GetMainlineZoneGroupViewModel(StageStateBean stateBean) { }
	// RVA: 0x2f0062c VA: 0x759551862c
	public static IList`1 LoadData(StageStateBean stateBean) { }
	// RVA: 0x2f009f0 VA: 0x75955189f0
	private static Void _UpdateSortIndex(List`1 mainlineList) { }
	// RVA: 0x2f00bf8 VA: 0x7595518bf8
	public static ZoneHomeMainlineEntryItemModel CreateMainlineDisplayThemeEntry(String zoneId, StageStateBean stateBean) { }
	// RVA: 0x2f00dc4 VA: 0x7595518dc4
	private static ZoneHomeEntryLockInfo _CreateMainlineDisplayLockInfo(String curZoneId, String curChapterId, StageStorylineMainlineChapterViewModel mainlineModel) { }
	// RVA: 0x2f00870 VA: 0x7595518870
	private static Void _LoadFinishZoneData(List`1 mainlineList, String chapterId, Int32 chapterIndex, List`1 chapterInfos, Boolean hasOtherChapterUnfinish) { }
	// RVA: 0x2f00938 VA: 0x7595518938
	private static Void _LoadProcessingZoneData(List`1 mainlineList, String chapterId, Int32 chapterIndex, List`1 chapterInfos) { }
	// RVA: 0x2f01524 VA: 0x7595519524
	private static StageData _GetChapterCurGoingStageData(String chapterId, List`1 chapterInfoList) { }
	// RVA: 0x2f01320 VA: 0x7595519320
	private static Void _LoadData(List`1 mainlineList, StageData stageData, String chapterId, Int32 chapterIndex, Boolean isAllChapterPass, Boolean isChapterPass) { }
	// RVA: 0x2f0114c VA: 0x759551914c
	private static ZoneHomeMainlineEntryItemModel _CreateViewModel(StageData stageData, String chapterId, Int32 chapterIndex, Boolean isAllChapterPass, Boolean isChapterPass, ZoneHomeEntryLockInfo lockInfo) { }
	// RVA: 0x2f016e8 VA: 0x75955196e8
	public Void .ctor() { }
	// RVA: 0x2f017a0 VA: 0x75955197a0
	private ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo() { }
}
```