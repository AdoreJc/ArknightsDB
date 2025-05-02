# StageStorylineMainlineViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `String m_zoneId`

- `RetroActData m_retroActData`

- `String m_timelyDropId`

- `String <decoImageId>k__BackingField`

- `Boolean <retroValid>k__BackingField`


## Properties

- `String decoImageId`

- `Boolean retroValid`


## Methods

- `String get_decoImageId()`

- `Void set_decoImageId(String)`

- `Boolean get_retroValid()`

- `Void set_retroValid(Boolean)`

- `Void _LoadMainlineRetroStatusIfHave(StorylineMainlineData)`

- `Void _RefreshStageProgress()`

- `Void _EnsureProgressStagesFromRelevantStages()`

- `String <>xLuaBaseProxy_get_zoneId()`

- `String <>xLuaBaseProxy_get_retroId()`

- `Void <>xLuaBaseProxy_LoadData(StorylineStorySetData, Dictionary`2)`

- `Void <>xLuaBaseProxy_RefreshData()`

- `Boolean <>xLuaBaseProxy_CheckExDropValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageStorylineMainlineViewModel : StageStorylineStorySetViewModel
{
	private readonly ListDict`2 m_retroZones; // 0x80
	private readonly List`1 m_relevantStages; // 0x88
	private readonly List`1 m_progressStages; // 0x90
	private String m_zoneId; // 0x98
	private RetroActData m_retroActData; // 0xa0
	private String m_timelyDropId; // 0xa8
	private String <decoImageId>k__BackingField; // 0xb0
	private Boolean <retroValid>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_decoImageId; // 0x0
	private static DelegateBridge __Hotfix0_set_decoImageId; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x10
	private static DelegateBridge __Hotfix0_get_retroId; // 0x18
	private static DelegateBridge __Hotfix0_get_retroZones; // 0x20
	private static DelegateBridge __Hotfix0_get_relevantStages; // 0x28
	private static DelegateBridge __Hotfix0_get_retroValid; // 0x30
	private static DelegateBridge __Hotfix0_set_retroValid; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__LoadMainlineRetroStatusIfHave; // 0x48
	private static DelegateBridge __Hotfix0_RefreshData; // 0x50
	private static DelegateBridge __Hotfix0__RefreshStageProgress; // 0x58
	private static DelegateBridge __Hotfix0__EnsureProgressStagesFromRelevantStages; // 0x60
	private static DelegateBridge __Hotfix0_CheckExDropValid; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String decoImageId { get; set; }
	public override String zoneId { get; }
	public override String retroId { get; }
	public override ListDict`2 retroZones { get; }
	public override List`1 relevantStages { get; }
	public Boolean retroValid { get; set; }

	// RVA: 0x2ff3a90 VA: 0x759560ba90
	public String get_decoImageId() { }
	// RVA: 0x2ff3af8 VA: 0x759560baf8
	private Void set_decoImageId(String value) { }
	// RVA: 0x2ff3b7c VA: 0x759560bb7c
	public override String get_zoneId() { }
	// RVA: 0x2ff3be4 VA: 0x759560bbe4
	public override String get_retroId() { }
	// RVA: 0x2ff3c78 VA: 0x759560bc78
	public override ListDict`2 get_retroZones() { }
	// RVA: 0x2ff3ce0 VA: 0x759560bce0
	public override List`1 get_relevantStages() { }
	// RVA: 0x2ff3d48 VA: 0x759560bd48
	public Boolean get_retroValid() { }
	// RVA: 0x2ff3db0 VA: 0x759560bdb0
	private Void set_retroValid(Boolean value) { }
	// RVA: 0x2ff3e30 VA: 0x759560be30
	public override Void LoadData(StorylineStorySetData data, Dictionary`2 tagDict) { }
	// RVA: 0x2ff3f90 VA: 0x759560bf90
	private Void _LoadMainlineRetroStatusIfHave(StorylineMainlineData mainlineData) { }
	// RVA: 0x2ff4100 VA: 0x759560c100
	public override Void RefreshData() { }
	// RVA: 0x2ff4170 VA: 0x759560c170
	private Void _RefreshStageProgress() { }
	// RVA: 0x2ff4210 VA: 0x759560c210
	private Void _EnsureProgressStagesFromRelevantStages() { }
	// RVA: 0x2ff43b8 VA: 0x759560c3b8
	public override Boolean CheckExDropValid() { }
	// RVA: 0x2ff4434 VA: 0x759560c434
	public Void .ctor() { }
	// RVA: 0x2ff4578 VA: 0x759560c578
	private String <>xLuaBaseProxy_get_zoneId() { }
	// RVA: 0x2ff457c VA: 0x759560c57c
	private String <>xLuaBaseProxy_get_retroId() { }
	// RVA: 0x2ff4580 VA: 0x759560c580
	private ListDict`2 <>xLuaBaseProxy_get_retroZones() { }
	// RVA: 0x2ff4584 VA: 0x759560c584
	private List`1 <>xLuaBaseProxy_get_relevantStages() { }
	// RVA: 0x2ff4588 VA: 0x759560c588
	private Void <>xLuaBaseProxy_LoadData(StorylineStorySetData P0, Dictionary`2 P1) { }
	// RVA: 0x2ff458c VA: 0x759560c58c
	private Void <>xLuaBaseProxy_RefreshData() { }
	// RVA: 0x2ff4590 VA: 0x759560c590
	private Boolean <>xLuaBaseProxy_CheckExDropValid() { }
}
```