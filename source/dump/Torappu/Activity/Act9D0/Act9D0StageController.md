# Act9D0StageController

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Boolean _disableStageEntryPartical`

- `TrackPointViewProperty m_favorUpTrackProperty`

- `TrackPointViewProperty m_missionTrackProperty`

- `TrackPointViewProperty m_templateTrapTrackProperty`

- `Act9D0ZoneDescGroupViewProperty m_zoneDescGroupProperty`

- `Boolean m_isLoaded`

- `Action <onStageTimeout>k__BackingField`

- `Action <onRewardTimeout>k__BackingField`


## Properties

- `TrackPointViewProperty favorUpTrackProperty`

- `TrackPointViewProperty missionTrackProperty`

- `TrackPointViewProperty templateTrapTrackProperty`

- `Act9D0ZoneDescGroupViewProperty zoneDescGroupProperty`

- `Boolean isLoaded`

- `Action onStageTimeout`

- `Action onRewardTimeout`


## Methods

- `TrackPointViewProperty get_favorUpTrackProperty()`

- `TrackPointViewProperty get_missionTrackProperty()`

- `TrackPointViewProperty get_templateTrapTrackProperty()`

- `Act9D0ZoneDescGroupViewProperty get_zoneDescGroupProperty()`

- `Boolean get_isLoaded()`

- `Action get_onStageTimeout()`

- `Void set_onStageTimeout(Action)`

- `Action get_onRewardTimeout()`

- `Void set_onRewardTimeout(Action)`

- `Void FocusToZone(String)`

- `Void EventOnZoneClicked(String)`

- `TemplateMissionInputParam CreateTemplateMissionInputParam()`

- `IEnumerator <>n__0()`

- `Boolean <>xLuaBaseProxy_get_disableStageEntryPartical()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_TriggerActivityLoadedAVG()`

- `Void <>xLuaBaseProxy_OnStagePageHideEffect()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnRewardTimeout()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0StageController : ActivityStageController
{
	private Boolean _disableStageEntryPartical; // 0x60
	private TrackPointViewProperty m_favorUpTrackProperty; // 0x68
	private TrackPointViewProperty m_missionTrackProperty; // 0x70
	private TrackPointViewProperty m_templateTrapTrackProperty; // 0x78
	private Act9D0ZoneDescGroupViewProperty m_zoneDescGroupProperty; // 0x80
	private Boolean m_isLoaded; // 0x88
	private EventPool`1 m_eventPool; // 0x90
	private Action <onStageTimeout>k__BackingField; // 0x98
	private Action <onRewardTimeout>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_disableStageEntryPartical; // 0x0
	private static DelegateBridge __Hotfix0_get_favorUpTrackProperty; // 0x8
	private static DelegateBridge __Hotfix0_get_missionTrackProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_templateTrapTrackProperty; // 0x18
	private static DelegateBridge __Hotfix0_get_zoneDescGroupProperty; // 0x20
	private static DelegateBridge __Hotfix0_get_isLoaded; // 0x28
	private static DelegateBridge __Hotfix0_get_onStageTimeout; // 0x30
	private static DelegateBridge __Hotfix0_set_onStageTimeout; // 0x38
	private static DelegateBridge __Hotfix0_get_onRewardTimeout; // 0x40
	private static DelegateBridge __Hotfix0_set_onRewardTimeout; // 0x48
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x50
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x58
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x60
	private static DelegateBridge __Hotfix0_TriggerActivityLoadedAVG; // 0x68
	private static DelegateBridge __Hotfix0_OnStagePageHideEffect; // 0x70
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x78
	private static DelegateBridge __Hotfix0_OnRewardTimeout; // 0x80
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x88
	private static DelegateBridge __Hotfix0_FocusToZone; // 0x90
	private static DelegateBridge __Hotfix0_EventOnZoneClicked; // 0x98
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public override Boolean disableStageEntryPartical { get; }
	public TrackPointViewProperty favorUpTrackProperty { get; }
	public TrackPointViewProperty missionTrackProperty { get; }
	public TrackPointViewProperty templateTrapTrackProperty { get; }
	public Act9D0ZoneDescGroupViewProperty zoneDescGroupProperty { get; }
	public Boolean isLoaded { get; }
	public Action onStageTimeout { get; set; }
	public Action onRewardTimeout { get; set; }
	public EventPool`1 eventPool { get; }

	// RVA: 0x319b360 VA: 0x75957b3360
	public override Boolean get_disableStageEntryPartical() { }
	// RVA: 0x319b3c8 VA: 0x75957b33c8
	public TrackPointViewProperty get_favorUpTrackProperty() { }
	// RVA: 0x319b430 VA: 0x75957b3430
	public TrackPointViewProperty get_missionTrackProperty() { }
	// RVA: 0x319b498 VA: 0x75957b3498
	public TrackPointViewProperty get_templateTrapTrackProperty() { }
	// RVA: 0x319b500 VA: 0x75957b3500
	public Act9D0ZoneDescGroupViewProperty get_zoneDescGroupProperty() { }
	// RVA: 0x319b568 VA: 0x75957b3568
	public Boolean get_isLoaded() { }
	// RVA: 0x319b5d0 VA: 0x75957b35d0
	public Action get_onStageTimeout() { }
	// RVA: 0x319b638 VA: 0x75957b3638
	public Void set_onStageTimeout(Action value) { }
	// RVA: 0x319b6bc VA: 0x75957b36bc
	public Action get_onRewardTimeout() { }
	// RVA: 0x319b724 VA: 0x75957b3724
	public Void set_onRewardTimeout(Action value) { }
	// RVA: 0x319b7a8 VA: 0x75957b37a8
	public EventPool`1 get_eventPool() { }
	// RVA: 0x319b810 VA: 0x75957b3810
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x319b8b0 VA: 0x75957b38b0
	protected override Void OnLoaded() { }
	// RVA: 0x319bab4 VA: 0x75957b3ab4
	protected override Void TriggerActivityLoadedAVG() { }
	// RVA: 0x319bb18 VA: 0x75957b3b18
	protected override Void OnStagePageHideEffect() { }
	// RVA: 0x319bbb8 VA: 0x75957b3bb8
	protected override Void OnStageTimeout() { }
	// RVA: 0x319bd44 VA: 0x75957b3d44
	protected override Void OnRewardTimeout() { }
	// RVA: 0x319bdec VA: 0x75957b3dec
	protected override IEnumerator HideCoroutine() { }
	// RVA: 0x319bec0 VA: 0x75957b3ec0
	public Void FocusToZone(String zoneId) { }
	// RVA: 0x319bf60 VA: 0x75957b3f60
	public Void EventOnZoneClicked(String zoneId) { }
	// RVA: 0x319bfe0 VA: 0x75957b3fe0
	public TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x319c2f4 VA: 0x75957b42f4
	public Void .ctor() { }
	// RVA: 0x319c480 VA: 0x75957b4480
	private IEnumerator <>n__0() { }
	// RVA: 0x319c488 VA: 0x75957b4488
	private Boolean <>xLuaBaseProxy_get_disableStageEntryPartical() { }
	// RVA: 0x319c490 VA: 0x75957b4490
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x319c498 VA: 0x75957b4498
	private Void <>xLuaBaseProxy_TriggerActivityLoadedAVG() { }
	// RVA: 0x319c4a0 VA: 0x75957b44a0
	private Void <>xLuaBaseProxy_OnStagePageHideEffect() { }
	// RVA: 0x319c4a8 VA: 0x75957b44a8
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x319c4b0 VA: 0x75957b44b0
	private Void <>xLuaBaseProxy_OnRewardTimeout() { }
	// RVA: 0x319c4b8 VA: 0x75957b44b8
	private IEnumerator <>xLuaBaseProxy_HideCoroutine() { }
}
```