# MixStoryZoneGroupViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `Boolean m_guideHideRecommend`

- `StageStorylineStorySetViewModel m_lastVisitedStorySet`

- `StageStorylineStorySetViewModel m_focusedStorySet`

- `StageStorylineMainlineChapterViewModel m_chapterModel`

- `Int32 <dataSequence>k__BackingField`

- `Boolean <hasTrackPoint>k__BackingField`

- `StageStorylineStorySetViewModel <selectedRetroStorySet>k__BackingField`

- `StageStorylineViewModel <selectedRetroStoryline>k__BackingField`

- `Int32 <selectedRetroIndex>k__BackingField`


## Properties

- `StageStorylineMainlineChapterViewModel chapterModel`

- `StageStorylineViewModel lastVisitedStoryline`

- `StageStorylineStorySetLocationViewModel lastVisitedLocation`

- `StageStorylineViewModel focusedStoryline`

- `StageStorylineStorySetLocationViewModel focusedLocation`

- `Int32 dataSequence`

- `Boolean hasTrackPoint`

- `StageStorylineStorySetViewModel selectedRetroStorySet`

- `StageStorylineViewModel selectedRetroStoryline`

- `Int32 selectedRetroIndex`


## Methods

- `StageStorylineMainlineChapterViewModel get_chapterModel()`

- `StageStorylineViewModel get_lastVisitedStoryline()`

- `StageStorylineStorySetLocationViewModel get_lastVisitedLocation()`

- `StageStorylineViewModel get_focusedStoryline()`

- `StageStorylineStorySetLocationViewModel get_focusedLocation()`

- `Int32 get_dataSequence()`

- `Void set_dataSequence(Int32)`

- `Boolean get_hasTrackPoint()`

- `Void set_hasTrackPoint(Boolean)`

- `StageStorylineStorySetViewModel get_selectedRetroStorySet()`

- `Void set_selectedRetroStorySet(StageStorylineStorySetViewModel)`

- `StageStorylineViewModel get_selectedRetroStoryline()`

- `Void set_selectedRetroStoryline(StageStorylineViewModel)`

- `Int32 get_selectedRetroIndex()`

- `Void set_selectedRetroIndex(Int32)`

- `Void LoadData()`

- `Void RefreshData()`

- `Void _LoadTags(Dictionary`2)`

- `Void _LoadStorySets(Dictionary`2)`

- `Void _LoadStorylines(ListDict`2)`

- `Void _PostProcessStorySet(StageStorylineStorySetViewModel)`

- `Void _PostProcessThroughZonesAndStages(ListDict`2)`

- `Void _PostProcessThroughRetros(ListDict`2)`

- `Void _PostProcessThroughZones()`

- `Void _PostProcessThroughRetroZone(ZoneViewModel, StageStorylineStorySetViewModel)`

- `Void _RefreshStorySets(StorylineConstData)`

- `Void _PostRefreshSideStory(StageStorylineSSViewModel)`

- `Void _RefreshStorylines()`

- `Void _InitLastVisitAndFocusIfNot()`

- `Void _InitLastVisitedIfNot()`

- `Void _InitFocusIfNot()`

- `Boolean CheckZoneRequireRetroZone(String)`

- `String GetRetroIdByZoneId(String)`

- `Void FocusLastVisitedMainline()`

- `Void OnZoneSelected(String)`

- `Void SetFocusedStorySet(String)`

- `Void _SetFocusedStorySet(StageStorylineStorySetViewModel)`

- `Void SetFocusedStoryline(String)`

- `Void SetLastVisitedStorySet(StageStorylineStorySetViewModel)`

- `Void SetLastVisitedStorySet(String)`

- `Boolean SelectRetro(String)`

- `Boolean SelectRetroByZoneId(String)`

- `Boolean SelectRetroByRelevantActId(String)`

- `Void _OnStorySetSelectedInRetro(StageStorylineStorySetViewModel)`

- `Boolean SwitchRetro(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class MixStoryZoneGroupViewModel : ZoneGroupViewModel, IHotfixable
{
	private readonly Dictionary`2 m_tags; // 0x28
	private readonly Dictionary`2 m_storySets; // 0x30
	private readonly Dictionary`2 m_storylines; // 0x38
	private readonly List`1 m_presentedStorylineList; // 0x40
	private readonly Dictionary`2 m_cachedRetroToStorySets; // 0x48
	private readonly Dictionary`2 m_cacheZoneToStorySets; // 0x50
	private Boolean m_guideHideRecommend; // 0x58
	private StageStorylineStorySetViewModel m_lastVisitedStorySet; // 0x60
	private StageStorylineStorySetViewModel m_focusedStorySet; // 0x68
	private StageStorylineMainlineChapterViewModel m_chapterModel; // 0x70
	private Dictionary`2 m_zoneDict; // 0x78
	private Int32 <dataSequence>k__BackingField; // 0x80
	private Boolean <hasTrackPoint>k__BackingField; // 0x84
	private StageStorylineStorySetViewModel <selectedRetroStorySet>k__BackingField; // 0x88
	private StageStorylineViewModel <selectedRetroStoryline>k__BackingField; // 0x90
	private Int32 <selectedRetroIndex>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_chapterModel; // 0x0
	private static DelegateBridge __Hotfix0_get_lastVisitedStoryline; // 0x8
	private static DelegateBridge __Hotfix0_get_lastVisitedLocation; // 0x10
	private static DelegateBridge __Hotfix0_get_focusedStoryline; // 0x18
	private static DelegateBridge __Hotfix0_get_focusedLocation; // 0x20
	private static DelegateBridge __Hotfix0_get_presentedStorylines; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSequence; // 0x30
	private static DelegateBridge __Hotfix0_set_dataSequence; // 0x38
	private static DelegateBridge __Hotfix0_get_hasTrackPoint; // 0x40
	private static DelegateBridge __Hotfix0_set_hasTrackPoint; // 0x48
	private static DelegateBridge __Hotfix0_get_selectedRetroStorySet; // 0x50
	private static DelegateBridge __Hotfix0_set_selectedRetroStorySet; // 0x58
	private static DelegateBridge __Hotfix0_get_selectedRetroStoryline; // 0x60
	private static DelegateBridge __Hotfix0_set_selectedRetroStoryline; // 0x68
	private static DelegateBridge __Hotfix0_get_selectedRetroIndex; // 0x70
	private static DelegateBridge __Hotfix0_set_selectedRetroIndex; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0_RefreshData; // 0x88
	private static DelegateBridge __Hotfix0__LoadTags; // 0x90
	private static DelegateBridge __Hotfix0__LoadStorySets; // 0x98
	private static DelegateBridge __Hotfix0__LoadStorylines; // 0xa0
	private static DelegateBridge __Hotfix0__PostProcessStorySet; // 0xa8
	private static DelegateBridge __Hotfix0__PostProcessThroughZonesAndStages; // 0xb0
	private static DelegateBridge __Hotfix0__PostProcessThroughRetros; // 0xb8
	private static DelegateBridge __Hotfix0__PostProcessThroughZones; // 0xc0
	private static DelegateBridge __Hotfix0__PostProcessThroughRetroZone; // 0xc8
	private static DelegateBridge __Hotfix0__RefreshStorySets; // 0xd0
	private static DelegateBridge __Hotfix0__PostRefreshSideStory; // 0xd8
	private static DelegateBridge __Hotfix0__RefreshStorylines; // 0xe0
	private static DelegateBridge __Hotfix0__InitLastVisitAndFocusIfNot; // 0xe8
	private static DelegateBridge __Hotfix0__InitLastVisitedIfNot; // 0xf0
	private static DelegateBridge __Hotfix0__InitFocusIfNot; // 0xf8
	private static DelegateBridge __Hotfix0_CheckZoneRequireRetroZone; // 0x100
	private static DelegateBridge __Hotfix0_GetRetroIdByZoneId; // 0x108
	private static DelegateBridge __Hotfix0_FocusLastVisitedMainline; // 0x110
	private static DelegateBridge __Hotfix0_OnZoneSelected; // 0x118
	private static DelegateBridge __Hotfix0_SetFocusedStorySet; // 0x120
	private static DelegateBridge __Hotfix0__SetFocusedStorySet; // 0x128
	private static DelegateBridge __Hotfix0_SetFocusedStoryline; // 0x130
	private static DelegateBridge __Hotfix0_SetLastVisitedStorySet; // 0x138
	private static DelegateBridge __Hotfix1_SetLastVisitedStorySet; // 0x140
	private static DelegateBridge __Hotfix0_SelectRetro; // 0x148
	private static DelegateBridge __Hotfix0_SelectRetroByZoneId; // 0x150
	private static DelegateBridge __Hotfix0_SelectRetroByRelevantActId; // 0x158
	private static DelegateBridge __Hotfix0__OnStorySetSelectedInRetro; // 0x160
	private static DelegateBridge __Hotfix0_SwitchRetro; // 0x168
	private static DelegateBridge __Hotfix0__SortStoryline; // 0x170
	private static DelegateBridge _c__Hotfix0_ctor; // 0x178

	public StageStorylineMainlineChapterViewModel chapterModel { get; }
	public StageStorylineViewModel lastVisitedStoryline { get; }
	public StageStorylineStorySetLocationViewModel lastVisitedLocation { get; }
	public StageStorylineViewModel focusedStoryline { get; }
	public StageStorylineStorySetLocationViewModel focusedLocation { get; }
	public List`1 presentedStorylines { get; }
	public Int32 dataSequence { get; set; }
	public Boolean hasTrackPoint { get; set; }
	public StageStorylineStorySetViewModel selectedRetroStorySet { get; set; }
	public StageStorylineViewModel selectedRetroStoryline { get; set; }
	public Int32 selectedRetroIndex { get; set; }

	// RVA: 0x2feb49c VA: 0x759560349c
	public StageStorylineMainlineChapterViewModel get_chapterModel() { }
	// RVA: 0x2feb504 VA: 0x7595603504
	public StageStorylineViewModel get_lastVisitedStoryline() { }
	// RVA: 0x2feb580 VA: 0x7595603580
	public StageStorylineStorySetLocationViewModel get_lastVisitedLocation() { }
	// RVA: 0x2fe6e38 VA: 0x75955fee38
	public StageStorylineViewModel get_focusedStoryline() { }
	// RVA: 0x2fe6dbc VA: 0x75955fedbc
	public StageStorylineStorySetLocationViewModel get_focusedLocation() { }
	// RVA: 0x2feb5fc VA: 0x75956035fc
	public List`1 get_presentedStorylines() { }
	// RVA: 0x2feb664 VA: 0x7595603664
	public Int32 get_dataSequence() { }
	// RVA: 0x2feb6cc VA: 0x75956036cc
	private Void set_dataSequence(Int32 value) { }
	// RVA: 0x2feb748 VA: 0x7595603748
	public Boolean get_hasTrackPoint() { }
	// RVA: 0x2feb7b0 VA: 0x75956037b0
	private Void set_hasTrackPoint(Boolean value) { }
	// RVA: 0x2feb830 VA: 0x7595603830
	public StageStorylineStorySetViewModel get_selectedRetroStorySet() { }
	// RVA: 0x2feb898 VA: 0x7595603898
	private Void set_selectedRetroStorySet(StageStorylineStorySetViewModel value) { }
	// RVA: 0x2feb91c VA: 0x759560391c
	public StageStorylineViewModel get_selectedRetroStoryline() { }
	// RVA: 0x2feb984 VA: 0x7595603984
	private Void set_selectedRetroStoryline(StageStorylineViewModel value) { }
	// RVA: 0x2feba08 VA: 0x7595603a08
	public Int32 get_selectedRetroIndex() { }
	// RVA: 0x2feba70 VA: 0x7595603a70
	private Void set_selectedRetroIndex(Int32 value) { }
	// RVA: 0x2febaec VA: 0x7595603aec
	public Void LoadData() { }
	// RVA: 0x2fec8fc VA: 0x75956048fc
	public Void RefreshData() { }
	// RVA: 0x2febcfc VA: 0x7595603cfc
	private Void _LoadTags(Dictionary`2 tags) { }
	// RVA: 0x2febf74 VA: 0x7595603f74
	private Void _LoadStorySets(Dictionary`2 storySets) { }
	// RVA: 0x2fec2c8 VA: 0x75956042c8
	private Void _LoadStorylines(ListDict`2 storylines) { }
	// RVA: 0x2feced4 VA: 0x7595604ed4
	private Void _PostProcessStorySet(StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fec874 VA: 0x7595604874
	private Void _PostProcessThroughZonesAndStages(ListDict`2 zoneToRetro) { }
	// RVA: 0x2fecfe4 VA: 0x7595604fe4
	private Void _PostProcessThroughRetros(ListDict`2 zoneToRetro) { }
	// RVA: 0x2fed148 VA: 0x7595605148
	private Void _PostProcessThroughZones() { }
	// RVA: 0x2fed328 VA: 0x7595605328
	private Void _PostProcessThroughRetroZone(ZoneViewModel zone, StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fec9c8 VA: 0x75956049c8
	private Void _RefreshStorySets(StorylineConstData constData) { }
	// RVA: 0x2fed420 VA: 0x7595605420
	private Void _PostRefreshSideStory(StageStorylineSSViewModel model) { }
	// RVA: 0x2fecce4 VA: 0x7595604ce4
	private Void _RefreshStorylines() { }
	// RVA: 0x2fece64 VA: 0x7595604e64
	private Void _InitLastVisitAndFocusIfNot() { }
	// RVA: 0x2fed4cc VA: 0x75956054cc
	private Void _InitLastVisitedIfNot() { }
	// RVA: 0x2fed7b8 VA: 0x75956057b8
	private Void _InitFocusIfNot() { }
	// RVA: 0x2fed83c VA: 0x759560583c
	public Boolean CheckZoneRequireRetroZone(String zoneId) { }
	// RVA: 0x2fed930 VA: 0x7595605930
	public String GetRetroIdByZoneId(String zoneId) { }
	// RVA: 0x2feda8c VA: 0x7595605a8c
	public Void FocusLastVisitedMainline() { }
	// RVA: 0x2fedc40 VA: 0x7595605c40
	public Void OnZoneSelected(String zoneId) { }
	// RVA: 0x2fedd9c VA: 0x7595605d9c
	public Void SetFocusedStorySet(String storySetId) { }
	// RVA: 0x2fedd04 VA: 0x7595605d04
	private Void _SetFocusedStorySet(StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fe35d0 VA: 0x75955fb5d0
	public Void SetFocusedStoryline(String storylineId) { }
	// RVA: 0x2fede60 VA: 0x7595605e60
	public Void SetLastVisitedStorySet(StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fedf60 VA: 0x7595605f60
	public Void SetLastVisitedStorySet(String storySetId) { }
	// RVA: 0x2fee024 VA: 0x7595606024
	public Boolean SelectRetro(String storySetId) { }
	// RVA: 0x2fee338 VA: 0x7595606338
	public Boolean SelectRetroByZoneId(String zoneId) { }
	// RVA: 0x2fee4a8 VA: 0x75956064a8
	public Boolean SelectRetroByRelevantActId(String relevantActId) { }
	// RVA: 0x2fee1e4 VA: 0x75956061e4
	private Void _OnStorySetSelectedInRetro(StageStorylineStorySetViewModel storySet) { }
	// RVA: 0x2fee6b8 VA: 0x75956066b8
	public Boolean SwitchRetro(String storySetId) { }
	// RVA: 0x2fee844 VA: 0x7595606844
	private static Int32 _SortStoryline(StageStorylineViewModel x, StageStorylineViewModel y) { }
	// RVA: 0x2fee924 VA: 0x7595606924
	public Void .ctor() { }
}
```