# StageStorylineSSViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `BasicData m_reopenActBasicData`

- `String m_retroId`

- `RetroActData m_retroActData`

- `RetroTrailData m_retroTrailData`

- `Boolean m_isRecommended`

- `String m_recommendHideStageId`

- `String <name>k__BackingField`

- `String <desc>k__BackingField`

- `String <backgroundId>k__BackingField`

- `String <reopenActivityId>k__BackingField`

- `Boolean m_hasNewTag`

- `Boolean <isReopening>k__BackingField`

- `Boolean <retroValid>k__BackingField`

- `String <retroName>k__BackingField`

- `Boolean <retroUnlocked>k__BackingField`

- `Boolean <retroTrailValid>k__BackingField`

- `String <retroTrailColor>k__BackingField`

- `Int32 <retroTrailProgressValue>k__BackingField`

- `Int32 <retroTrailProgressVolume>k__BackingField`

- `Boolean <retroTrailComplete>k__BackingField`

- `Boolean <hideRecommended>k__BackingField`


## Properties

- `String name`

- `String desc`

- `String backgroundId`

- `String reopenActivityId`

- `Boolean isReopening`

- `Boolean retroValid`

- `String retroName`

- `Boolean retroUnlocked`

- `Boolean retroTrailValid`

- `String retroTrailColor`

- `Int32 retroTrailProgressValue`

- `Int32 retroTrailProgressVolume`

- `Boolean retroTrailComplete`

- `Boolean hideRecommended`


## Methods

- `String get_name()`

- `Void set_name(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `String get_backgroundId()`

- `Void set_backgroundId(String)`

- `String get_reopenActivityId()`

- `Void set_reopenActivityId(String)`

- `Boolean get_isReopening()`

- `Void set_isReopening(Boolean)`

- `Boolean get_retroValid()`

- `Void set_retroValid(Boolean)`

- `String get_retroName()`

- `Void set_retroName(String)`

- `Boolean get_retroUnlocked()`

- `Void set_retroUnlocked(Boolean)`

- `Boolean get_retroTrailValid()`

- `Void set_retroTrailValid(Boolean)`

- `String get_retroTrailColor()`

- `Void set_retroTrailColor(String)`

- `Int32 get_retroTrailProgressValue()`

- `Void set_retroTrailProgressValue(Int32)`

- `Int32 get_retroTrailProgressVolume()`

- `Void set_retroTrailProgressVolume(Int32)`

- `Boolean get_retroTrailComplete()`

- `Void set_retroTrailComplete(Boolean)`

- `Boolean get_hideRecommended()`

- `Void set_hideRecommended(Boolean)`

- `Void _LoadTags(StorylineSSData, Dictionary`2)`

- `Void _LoadReopenInfo(StorylineSSData)`

- `Void _LoadRetroInfo(StorylineSSData)`

- `Void _RefreshReopenRelated()`

- `Void _RefreshRetroRelated()`

- `Void _EnsureProgressStagesFromRelevantStages()`

- `Void _RefreshRetroTrailRelated()`

- `Void OnRetroSelected()`

- `String <>xLuaBaseProxy_get_retroId()`

- `Void <>xLuaBaseProxy_LoadData(StorylineStorySetData, Dictionary`2)`

- `Void <>xLuaBaseProxy_RefreshData()`

- `Boolean <>xLuaBaseProxy_CheckCoreRewardValid()`

- `Boolean <>xLuaBaseProxy_CheckExDropValid()`

- `Boolean <>xLuaBaseProxy_CheckNewTagValid()`

- `Boolean <>xLuaBaseProxy_CheckRecommendedValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageStorylineSSViewModel : StageStorylineStorySetViewModel
{
	private readonly List`1 m_tags; // 0x80
	private readonly ListDict`2 m_retroZones; // 0x88
	private readonly List`1 m_relevantStages; // 0x90
	private readonly List`1 m_progressStages; // 0x98
	private BasicData m_reopenActBasicData; // 0xa0
	private String m_retroId; // 0xa8
	private RetroActData m_retroActData; // 0xb0
	private RetroTrailData m_retroTrailData; // 0xb8
	private Boolean m_isRecommended; // 0xc0
	private String m_recommendHideStageId; // 0xc8
	private String <name>k__BackingField; // 0xd0
	private String <desc>k__BackingField; // 0xd8
	private String <backgroundId>k__BackingField; // 0xe0
	private String <reopenActivityId>k__BackingField; // 0xe8
	private Boolean m_hasNewTag; // 0xf0
	private Boolean <isReopening>k__BackingField; // 0xf1
	private Boolean <retroValid>k__BackingField; // 0xf2
	private String <retroName>k__BackingField; // 0xf8
	private Boolean <retroUnlocked>k__BackingField; // 0x100
	private Boolean <retroTrailValid>k__BackingField; // 0x101
	private String <retroTrailColor>k__BackingField; // 0x108
	private Int32 <retroTrailProgressValue>k__BackingField; // 0x110
	private Int32 <retroTrailProgressVolume>k__BackingField; // 0x114
	private Boolean <retroTrailComplete>k__BackingField; // 0x118
	private Boolean <hideRecommended>k__BackingField; // 0x119
	private static DelegateBridge __Hotfix0_get_name; // 0x0
	private static DelegateBridge __Hotfix0_set_name; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_set_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_backgroundId; // 0x20
	private static DelegateBridge __Hotfix0_set_backgroundId; // 0x28
	private static DelegateBridge __Hotfix0_get_reopenActivityId; // 0x30
	private static DelegateBridge __Hotfix0_set_reopenActivityId; // 0x38
	private static DelegateBridge __Hotfix0_get_retroId; // 0x40
	private static DelegateBridge __Hotfix0_get_retroZones; // 0x48
	private static DelegateBridge __Hotfix0_get_relevantStages; // 0x50
	private static DelegateBridge __Hotfix0_get_tags; // 0x58
	private static DelegateBridge __Hotfix0_get_isReopening; // 0x60
	private static DelegateBridge __Hotfix0_set_isReopening; // 0x68
	private static DelegateBridge __Hotfix0_get_retroValid; // 0x70
	private static DelegateBridge __Hotfix0_set_retroValid; // 0x78
	private static DelegateBridge __Hotfix0_get_retroName; // 0x80
	private static DelegateBridge __Hotfix0_set_retroName; // 0x88
	private static DelegateBridge __Hotfix0_get_retroUnlocked; // 0x90
	private static DelegateBridge __Hotfix0_set_retroUnlocked; // 0x98
	private static DelegateBridge __Hotfix0_get_retroTrailValid; // 0xa0
	private static DelegateBridge __Hotfix0_set_retroTrailValid; // 0xa8
	private static DelegateBridge __Hotfix0_get_retroTrailColor; // 0xb0
	private static DelegateBridge __Hotfix0_set_retroTrailColor; // 0xb8
	private static DelegateBridge __Hotfix0_get_retroTrailProgressValue; // 0xc0
	private static DelegateBridge __Hotfix0_set_retroTrailProgressValue; // 0xc8
	private static DelegateBridge __Hotfix0_get_retroTrailProgressVolume; // 0xd0
	private static DelegateBridge __Hotfix0_set_retroTrailProgressVolume; // 0xd8
	private static DelegateBridge __Hotfix0_get_retroTrailComplete; // 0xe0
	private static DelegateBridge __Hotfix0_set_retroTrailComplete; // 0xe8
	private static DelegateBridge __Hotfix0_get_hideRecommended; // 0xf0
	private static DelegateBridge __Hotfix0_set_hideRecommended; // 0xf8
	private static DelegateBridge __Hotfix0_LoadData; // 0x100
	private static DelegateBridge __Hotfix0__LoadTags; // 0x108
	private static DelegateBridge __Hotfix0__LoadReopenInfo; // 0x110
	private static DelegateBridge __Hotfix0__LoadRetroInfo; // 0x118
	private static DelegateBridge __Hotfix0_RefreshData; // 0x120
	private static DelegateBridge __Hotfix0__RefreshReopenRelated; // 0x128
	private static DelegateBridge __Hotfix0__RefreshRetroRelated; // 0x130
	private static DelegateBridge __Hotfix0__EnsureProgressStagesFromRelevantStages; // 0x138
	private static DelegateBridge __Hotfix0__RefreshRetroTrailRelated; // 0x140
	private static DelegateBridge __Hotfix0_CheckCoreRewardValid; // 0x148
	private static DelegateBridge __Hotfix0_CheckExDropValid; // 0x150
	private static DelegateBridge __Hotfix0_CheckNewTagValid; // 0x158
	private static DelegateBridge __Hotfix0_CheckRecommendedValid; // 0x160
	private static DelegateBridge __Hotfix0_OnRetroSelected; // 0x168
	private static DelegateBridge _c__Hotfix0_ctor; // 0x170

	public String name { get; set; }
	public String desc { get; set; }
	public String backgroundId { get; set; }
	public String reopenActivityId { get; set; }
	public override String retroId { get; }
	public override ListDict`2 retroZones { get; }
	public override List`1 relevantStages { get; }
	public List`1 tags { get; }
	public Boolean isReopening { get; set; }
	public Boolean retroValid { get; set; }
	public String retroName { get; set; }
	public Boolean retroUnlocked { get; set; }
	public Boolean retroTrailValid { get; set; }
	public String retroTrailColor { get; set; }
	public Int32 retroTrailProgressValue { get; set; }
	public Int32 retroTrailProgressVolume { get; set; }
	public Boolean retroTrailComplete { get; set; }
	public Boolean hideRecommended { get; set; }

	// RVA: 0x2ff4594 VA: 0x759560c594
	public String get_name() { }
	// RVA: 0x2ff45fc VA: 0x759560c5fc
	private Void set_name(String value) { }
	// RVA: 0x2ff4680 VA: 0x759560c680
	public String get_desc() { }
	// RVA: 0x2ff46e8 VA: 0x759560c6e8
	private Void set_desc(String value) { }
	// RVA: 0x2ff476c VA: 0x759560c76c
	public String get_backgroundId() { }
	// RVA: 0x2ff47d4 VA: 0x759560c7d4
	private Void set_backgroundId(String value) { }
	// RVA: 0x2ff4858 VA: 0x759560c858
	public String get_reopenActivityId() { }
	// RVA: 0x2ff48c0 VA: 0x759560c8c0
	private Void set_reopenActivityId(String value) { }
	// RVA: 0x2ff4944 VA: 0x759560c944
	public override String get_retroId() { }
	// RVA: 0x2ff49ac VA: 0x759560c9ac
	public override ListDict`2 get_retroZones() { }
	// RVA: 0x2ff4a14 VA: 0x759560ca14
	public override List`1 get_relevantStages() { }
	// RVA: 0x2ff4a7c VA: 0x759560ca7c
	public List`1 get_tags() { }
	// RVA: 0x2ff4ae4 VA: 0x759560cae4
	public Boolean get_isReopening() { }
	// RVA: 0x2ff4b4c VA: 0x759560cb4c
	private Void set_isReopening(Boolean value) { }
	// RVA: 0x2ff4bcc VA: 0x759560cbcc
	public Boolean get_retroValid() { }
	// RVA: 0x2ff4c34 VA: 0x759560cc34
	private Void set_retroValid(Boolean value) { }
	// RVA: 0x2ff4cb4 VA: 0x759560ccb4
	public String get_retroName() { }
	// RVA: 0x2ff4d1c VA: 0x759560cd1c
	private Void set_retroName(String value) { }
	// RVA: 0x2ff4da0 VA: 0x759560cda0
	public Boolean get_retroUnlocked() { }
	// RVA: 0x2ff4e08 VA: 0x759560ce08
	private Void set_retroUnlocked(Boolean value) { }
	// RVA: 0x2ff4e88 VA: 0x759560ce88
	public Boolean get_retroTrailValid() { }
	// RVA: 0x2ff4ef0 VA: 0x759560cef0
	private Void set_retroTrailValid(Boolean value) { }
	// RVA: 0x2ff4f70 VA: 0x759560cf70
	public String get_retroTrailColor() { }
	// RVA: 0x2ff4fd8 VA: 0x759560cfd8
	private Void set_retroTrailColor(String value) { }
	// RVA: 0x2ff505c VA: 0x759560d05c
	public Int32 get_retroTrailProgressValue() { }
	// RVA: 0x2ff50c4 VA: 0x759560d0c4
	private Void set_retroTrailProgressValue(Int32 value) { }
	// RVA: 0x2ff5140 VA: 0x759560d140
	public Int32 get_retroTrailProgressVolume() { }
	// RVA: 0x2ff51a8 VA: 0x759560d1a8
	private Void set_retroTrailProgressVolume(Int32 value) { }
	// RVA: 0x2ff5224 VA: 0x759560d224
	public Boolean get_retroTrailComplete() { }
	// RVA: 0x2ff528c VA: 0x759560d28c
	private Void set_retroTrailComplete(Boolean value) { }
	// RVA: 0x2ff530c VA: 0x759560d30c
	public Boolean get_hideRecommended() { }
	// RVA: 0x2ff5374 VA: 0x759560d374
	public Void set_hideRecommended(Boolean value) { }
	// RVA: 0x2ff53f4 VA: 0x759560d3f4
	public override Void LoadData(StorylineStorySetData data, Dictionary`2 tagDict) { }
	// RVA: 0x2ff5608 VA: 0x759560d608
	private Void _LoadTags(StorylineSSData ssData, Dictionary`2 tagDict) { }
	// RVA: 0x2ff59e0 VA: 0x759560d9e0
	private Void _LoadReopenInfo(StorylineSSData ssData) { }
	// RVA: 0x2ff582c VA: 0x759560d82c
	private Void _LoadRetroInfo(StorylineSSData ssData) { }
	// RVA: 0x2ff5b18 VA: 0x759560db18
	public override Void RefreshData() { }
	// RVA: 0x2ff5b98 VA: 0x759560db98
	private Void _RefreshReopenRelated() { }
	// RVA: 0x2ff5cd8 VA: 0x759560dcd8
	private Void _RefreshRetroRelated() { }
	// RVA: 0x2ff6110 VA: 0x759560e110
	private Void _EnsureProgressStagesFromRelevantStages() { }
	// RVA: 0x2ff5f10 VA: 0x759560df10
	private Void _RefreshRetroTrailRelated() { }
	// RVA: 0x2ff62b8 VA: 0x759560e2b8
	public override Boolean CheckCoreRewardValid() { }
	// RVA: 0x2ff633c VA: 0x759560e33c
	public override Boolean CheckExDropValid() { }
	// RVA: 0x2ff63d4 VA: 0x759560e3d4
	public override Boolean CheckNewTagValid() { }
	// RVA: 0x2ff643c VA: 0x759560e43c
	public override Boolean CheckRecommendedValid() { }
	// RVA: 0x2ff64e8 VA: 0x759560e4e8
	public Void OnRetroSelected() { }
	// RVA: 0x2ff65b0 VA: 0x759560e5b0
	public Void .ctor() { }
	// RVA: 0x2ff6744 VA: 0x759560e744
	private String <>xLuaBaseProxy_get_retroId() { }
	// RVA: 0x2ff6748 VA: 0x759560e748
	private ListDict`2 <>xLuaBaseProxy_get_retroZones() { }
	// RVA: 0x2ff674c VA: 0x759560e74c
	private List`1 <>xLuaBaseProxy_get_relevantStages() { }
	// RVA: 0x2ff6750 VA: 0x759560e750
	private Void <>xLuaBaseProxy_LoadData(StorylineStorySetData P0, Dictionary`2 P1) { }
	// RVA: 0x2ff6754 VA: 0x759560e754
	private Void <>xLuaBaseProxy_RefreshData() { }
	// RVA: 0x2ff6758 VA: 0x759560e758
	private Boolean <>xLuaBaseProxy_CheckCoreRewardValid() { }
	// RVA: 0x2ff675c VA: 0x759560e75c
	private Boolean <>xLuaBaseProxy_CheckExDropValid() { }
	// RVA: 0x2ff6760 VA: 0x759560e760
	private Boolean <>xLuaBaseProxy_CheckNewTagValid() { }
	// RVA: 0x2ff6764 VA: 0x759560e764
	private Boolean <>xLuaBaseProxy_CheckRecommendedValid() { }
}
```