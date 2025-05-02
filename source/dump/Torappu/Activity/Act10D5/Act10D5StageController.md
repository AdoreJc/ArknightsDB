# Act10D5StageController

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `Boolean _disableStageEntryPartical`

- `TrackPointViewProperty m_favorUpTrackProperty`

- `Act10D5ZoneDescGroupViewProperty m_zoneDescGroupProperty`

- `Boolean m_isLoaded`

- `Act10D5InitMeta m_initMetaObj`

- `TemplateActivityMedalViewModel m_medalViewModel`

- `Action <onStageTimeout>k__BackingField`

- `Action <onRewardTimeout>k__BackingField`


## Properties

- `TrackPointViewProperty favorUpTrackProperty`

- `Act10D5ZoneDescGroupViewProperty zoneDescGroupProperty`

- `Boolean isLoaded`

- `Action onStageTimeout`

- `Action onRewardTimeout`

- `Act10D5InitMeta initMetaObj`


## Methods

- `TrackPointViewProperty get_favorUpTrackProperty()`

- `Act10D5ZoneDescGroupViewProperty get_zoneDescGroupProperty()`

- `Boolean get_isLoaded()`

- `Action get_onStageTimeout()`

- `Void set_onStageTimeout(Action)`

- `Action get_onRewardTimeout()`

- `Void set_onRewardTimeout(Action)`

- `Act10D5InitMeta get_initMetaObj()`

- `Void TryRefreshMedalPlugin()`

- `TemplateActivityMedalViewModel _GenMedalViewModel()`

- `Void EventOnZoneClicked(String)`

- `Boolean <>xLuaBaseProxy_get_disableStageEntryPartical()`

- `String <>xLuaBaseProxy_GetBGMSignal()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnRewardTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StageController : ActivityStageController
{
	private Boolean _disableStageEntryPartical; // 0x60
	private TrackPointViewProperty m_favorUpTrackProperty; // 0x68
	private Act10D5ZoneDescGroupViewProperty m_zoneDescGroupProperty; // 0x70
	private Boolean m_isLoaded; // 0x78
	private Act10D5InitMeta m_initMetaObj; // 0x80
	private TemplateActivityMedalViewModel m_medalViewModel; // 0x88
	private Action <onStageTimeout>k__BackingField; // 0x90
	private Action <onRewardTimeout>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_disableStageEntryPartical; // 0x0
	private static DelegateBridge __Hotfix0_get_favorUpTrackProperty; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneDescGroupProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_isLoaded; // 0x18
	private static DelegateBridge __Hotfix0_get_onStageTimeout; // 0x20
	private static DelegateBridge __Hotfix0_set_onStageTimeout; // 0x28
	private static DelegateBridge __Hotfix0_get_onRewardTimeout; // 0x30
	private static DelegateBridge __Hotfix0_set_onRewardTimeout; // 0x38
	private static DelegateBridge __Hotfix0_get_initMetaObj; // 0x40
	private static DelegateBridge __Hotfix0_TryRefreshMedalPlugin; // 0x48
	private static DelegateBridge __Hotfix0__GenMedalViewModel; // 0x50
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x58
	private static DelegateBridge __Hotfix0_GetBGMSignal; // 0x60
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x68
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x70
	private static DelegateBridge __Hotfix0_OnRewardTimeout; // 0x78
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x80
	private static DelegateBridge __Hotfix0_EventOnZoneClicked; // 0x88
	private static DelegateBridge __Hotfix0_CreateInitMeta4StoryState; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public override Boolean disableStageEntryPartical { get; }
	public TrackPointViewProperty favorUpTrackProperty { get; }
	public Act10D5ZoneDescGroupViewProperty zoneDescGroupProperty { get; }
	public Boolean isLoaded { get; }
	public Action onStageTimeout { get; set; }
	public Action onRewardTimeout { get; set; }
	public Act10D5InitMeta initMetaObj { get; }

	// RVA: 0x347f42c VA: 0x7595a9742c
	public override Boolean get_disableStageEntryPartical() { }
	// RVA: 0x347f494 VA: 0x7595a97494
	public TrackPointViewProperty get_favorUpTrackProperty() { }
	// RVA: 0x347f4fc VA: 0x7595a974fc
	public Act10D5ZoneDescGroupViewProperty get_zoneDescGroupProperty() { }
	// RVA: 0x347f564 VA: 0x7595a97564
	public Boolean get_isLoaded() { }
	// RVA: 0x347f5cc VA: 0x7595a975cc
	public Action get_onStageTimeout() { }
	// RVA: 0x347f634 VA: 0x7595a97634
	public Void set_onStageTimeout(Action value) { }
	// RVA: 0x347f6b8 VA: 0x7595a976b8
	public Action get_onRewardTimeout() { }
	// RVA: 0x347f720 VA: 0x7595a97720
	public Void set_onRewardTimeout(Action value) { }
	// RVA: 0x347f7a4 VA: 0x7595a977a4
	public Act10D5InitMeta get_initMetaObj() { }
	// RVA: 0x347f864 VA: 0x7595a97864
	public Void TryRefreshMedalPlugin() { }
	// RVA: 0x347f96c VA: 0x7595a9796c
	private TemplateActivityMedalViewModel _GenMedalViewModel() { }
	// RVA: 0x347fa80 VA: 0x7595a97a80
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x347fb20 VA: 0x7595a97b20
	protected override String GetBGMSignal() { }
	// RVA: 0x347fd74 VA: 0x7595a97d74
	protected override Void OnLoaded() { }
	// RVA: 0x347fee4 VA: 0x7595a97ee4
	protected override Void OnStageTimeout() { }
	// RVA: 0x3480040 VA: 0x7595a98040
	protected override Void OnRewardTimeout() { }
	// RVA: 0x34800e8 VA: 0x7595a980e8
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x3480198 VA: 0x7595a98198
	public Void EventOnZoneClicked(String zoneId) { }
	// RVA: 0x3480238 VA: 0x7595a98238
	public static String CreateInitMeta4StoryState() { }
	// RVA: 0x34802dc VA: 0x7595a982dc
	public Void .ctor() { }
	// RVA: 0x34803c8 VA: 0x7595a983c8
	private Boolean <>xLuaBaseProxy_get_disableStageEntryPartical() { }
	// RVA: 0x34803d0 VA: 0x7595a983d0
	private String <>xLuaBaseProxy_GetBGMSignal() { }
	// RVA: 0x34803d8 VA: 0x7595a983d8
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x34803e0 VA: 0x7595a983e0
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x34803e8 VA: 0x7595a983e8
	private Void <>xLuaBaseProxy_OnRewardTimeout() { }
	// RVA: 0x34803f0 VA: 0x7595a983f0
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
}
```