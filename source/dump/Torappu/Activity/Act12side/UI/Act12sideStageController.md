# Act12sideStageController

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Boolean _disableStageEntryPartical`

- `Act12sideZoneDescGroupViewProperty m_zoneDescGroupProperty`

- `Act12sideMissionProperty m_missionProperty`

- `Act12sideMilestoneProperty m_milestoneProperty`

- `TrackPointViewProperty m_favorUpTrackProperty`

- `TrackPointViewProperty m_milestoneTrackPointProperty`

- `TrackPointViewProperty m_missionTrackPointProperty`

- `TrackPointViewProperty m_newCharmTrackProperty`

- `TrackPointViewProperty m_recycleCharmTrackProperty`

- `TrackPointViewProperty m_honorsShowcaseTrackPointProperty`

- `Boolean m_isLoaded`

- `ActFavorUpTrackPointParam m_favorUpTrackPointParam`

- `Action <onStageTimeout>k__BackingField`


## Properties

- `StateEngine floatStateEngine`

- `Act12sideZoneDescGroupViewProperty zoneDescGroupProperty`

- `Act12sideMissionProperty missionProperty`

- `Act12sideMilestoneProperty milestoneProperty`

- `TrackPointViewProperty favorUpTrackProperty`

- `TrackPointViewProperty milestoneTrackPointProp`

- `TrackPointViewProperty missionTrackPointProp`

- `TrackPointViewProperty honorShowcaseProperty`

- `TrackPointViewProperty newCharmTrackPointProp`

- `TrackPointViewProperty recycleCharmTrackPointProp`

- `Boolean isLoaded`

- `Action onStageTimeout`


## Methods

- `StateEngine get_floatStateEngine()`

- `Act12sideZoneDescGroupViewProperty get_zoneDescGroupProperty()`

- `Act12sideMissionProperty get_missionProperty()`

- `Act12sideMilestoneProperty get_milestoneProperty()`

- `TrackPointViewProperty get_favorUpTrackProperty()`

- `TrackPointViewProperty get_milestoneTrackPointProp()`

- `TrackPointViewProperty get_missionTrackPointProp()`

- `TrackPointViewProperty get_honorShowcaseProperty()`

- `TrackPointViewProperty get_newCharmTrackPointProp()`

- `TrackPointViewProperty get_recycleCharmTrackPointProp()`

- `Boolean get_isLoaded()`

- `Action get_onStageTimeout()`

- `Void set_onStageTimeout(Action)`

- `Void EventOnZoneClicked(String)`

- `Void RefreshMilestoneStatus()`

- `Void RefreshFavorUpTrackPoint()`

- `Void RefreshMilestoneTrackPoint()`

- `Void RefreshMissionTrackPoint()`

- `Void RefreshNewCharmTrackPoint()`

- `Void RefreshRecycleCharmTrackPoint()`

- `Void RefreshHonorShowcaseTrackPoint()`

- `Void CheckMissionAndRefreshTrackPoint()`

- `IEnumerator _TrySyncMissionStatus()`

- `Boolean _HasMissionNew()`

- `Boolean _HasPhotoNew()`

- `Void _InitMissionProperty()`

- `Void _RefreshMissionProperty()`

- `Void _InitMilestoneProperty()`

- `IEnumerator <>n__0()`

- `Boolean <>xLuaBaseProxy_get_disableStageEntryPartical()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `IEnumerator <>xLuaBaseProxy_LoadCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideStageController : ActivityStageController
{
	private Boolean _disableStageEntryPartical; // 0x60
	private Act12sideZoneDescGroupViewProperty m_zoneDescGroupProperty; // 0x68
	private Act12sideMissionProperty m_missionProperty; // 0x70
	private Act12sideMilestoneProperty m_milestoneProperty; // 0x78
	private TrackPointViewProperty m_favorUpTrackProperty; // 0x80
	private TrackPointViewProperty m_milestoneTrackPointProperty; // 0x88
	private TrackPointViewProperty m_missionTrackPointProperty; // 0x90
	private TrackPointViewProperty m_newCharmTrackProperty; // 0x98
	private TrackPointViewProperty m_recycleCharmTrackProperty; // 0xa0
	private TrackPointViewProperty m_honorsShowcaseTrackPointProperty; // 0xa8
	private Boolean m_isLoaded; // 0xb0
	private ActFavorUpTrackPointParam m_favorUpTrackPointParam; // 0xb8
	private Action <onStageTimeout>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_get_floatStateEngine; // 0x0
	private static DelegateBridge __Hotfix0_get_zoneDescGroupProperty; // 0x8
	private static DelegateBridge __Hotfix0_get_missionProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_milestoneProperty; // 0x18
	private static DelegateBridge __Hotfix0_get_favorUpTrackProperty; // 0x20
	private static DelegateBridge __Hotfix0_get_milestoneTrackPointProp; // 0x28
	private static DelegateBridge __Hotfix0_get_missionTrackPointProp; // 0x30
	private static DelegateBridge __Hotfix0_get_honorShowcaseProperty; // 0x38
	private static DelegateBridge __Hotfix0_get_newCharmTrackPointProp; // 0x40
	private static DelegateBridge __Hotfix0_get_recycleCharmTrackPointProp; // 0x48
	private static DelegateBridge __Hotfix0_get_disableStageEntryPartical; // 0x50
	private static DelegateBridge __Hotfix0_get_isLoaded; // 0x58
	private static DelegateBridge __Hotfix0_get_onStageTimeout; // 0x60
	private static DelegateBridge __Hotfix0_set_onStageTimeout; // 0x68
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x70
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x78
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x80
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x88
	private static DelegateBridge __Hotfix0_LoadCoroutine; // 0x90
	private static DelegateBridge __Hotfix0_EventOnZoneClicked; // 0x98
	private static DelegateBridge __Hotfix0_RefreshMilestoneStatus; // 0xa0
	private static DelegateBridge __Hotfix0_RefreshFavorUpTrackPoint; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshMilestoneTrackPoint; // 0xb0
	private static DelegateBridge __Hotfix0_RefreshMissionTrackPoint; // 0xb8
	private static DelegateBridge __Hotfix0_RefreshNewCharmTrackPoint; // 0xc0
	private static DelegateBridge __Hotfix0_RefreshRecycleCharmTrackPoint; // 0xc8
	private static DelegateBridge __Hotfix0_RefreshHonorShowcaseTrackPoint; // 0xd0
	private static DelegateBridge __Hotfix0_CheckMissionAndRefreshTrackPoint; // 0xd8
	private static DelegateBridge __Hotfix0_FetchFavorUpList; // 0xe0
	private static DelegateBridge __Hotfix0__TrySyncMissionStatus; // 0xe8
	private static DelegateBridge __Hotfix0__HasMissionNew; // 0xf0
	private static DelegateBridge __Hotfix0__HasPhotoNew; // 0xf8
	private static DelegateBridge __Hotfix0__InitMissionProperty; // 0x100
	private static DelegateBridge __Hotfix0__RefreshMissionProperty; // 0x108
	private static DelegateBridge __Hotfix0__InitMilestoneProperty; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	public StateEngine floatStateEngine { get; }
	public Act12sideZoneDescGroupViewProperty zoneDescGroupProperty { get; }
	public Act12sideMissionProperty missionProperty { get; }
	public Act12sideMilestoneProperty milestoneProperty { get; }
	public TrackPointViewProperty favorUpTrackProperty { get; }
	public TrackPointViewProperty milestoneTrackPointProp { get; }
	public TrackPointViewProperty missionTrackPointProp { get; }
	public TrackPointViewProperty honorShowcaseProperty { get; }
	public TrackPointViewProperty newCharmTrackPointProp { get; }
	public TrackPointViewProperty recycleCharmTrackPointProp { get; }
	public override Boolean disableStageEntryPartical { get; }
	public Boolean isLoaded { get; }
	public Action onStageTimeout { get; set; }

	// RVA: 0x344bcc0 VA: 0x7595a63cc0
	public StateEngine get_floatStateEngine() { }
	// RVA: 0x344be0c VA: 0x7595a63e0c
	public Act12sideZoneDescGroupViewProperty get_zoneDescGroupProperty() { }
	// RVA: 0x344be74 VA: 0x7595a63e74
	public Act12sideMissionProperty get_missionProperty() { }
	// RVA: 0x344bedc VA: 0x7595a63edc
	public Act12sideMilestoneProperty get_milestoneProperty() { }
	// RVA: 0x344bf44 VA: 0x7595a63f44
	public TrackPointViewProperty get_favorUpTrackProperty() { }
	// RVA: 0x344bfac VA: 0x7595a63fac
	public TrackPointViewProperty get_milestoneTrackPointProp() { }
	// RVA: 0x344c014 VA: 0x7595a64014
	public TrackPointViewProperty get_missionTrackPointProp() { }
	// RVA: 0x344c07c VA: 0x7595a6407c
	public TrackPointViewProperty get_honorShowcaseProperty() { }
	// RVA: 0x344c0e4 VA: 0x7595a640e4
	public TrackPointViewProperty get_newCharmTrackPointProp() { }
	// RVA: 0x344c14c VA: 0x7595a6414c
	public TrackPointViewProperty get_recycleCharmTrackPointProp() { }
	// RVA: 0x344c1b4 VA: 0x7595a641b4
	public override Boolean get_disableStageEntryPartical() { }
	// RVA: 0x344c21c VA: 0x7595a6421c
	public Boolean get_isLoaded() { }
	// RVA: 0x344c284 VA: 0x7595a64284
	public Action get_onStageTimeout() { }
	// RVA: 0x344c2ec VA: 0x7595a642ec
	public Void set_onStageTimeout(Action value) { }
	// RVA: 0x344c370 VA: 0x7595a64370
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x344c410 VA: 0x7595a64410
	protected override Void OnLoaded() { }
	// RVA: 0x344d350 VA: 0x7595a65350
	protected override Void OnStageTimeout() { }
	// RVA: 0x344d4ac VA: 0x7595a654ac
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x344d5c0 VA: 0x7595a655c0
	public override IEnumerator LoadCoroutine() { }
	// RVA: 0x344d694 VA: 0x7595a65694
	public Void EventOnZoneClicked(String zoneId) { }
	// RVA: 0x344d734 VA: 0x7595a65734
	public Void RefreshMilestoneStatus() { }
	// RVA: 0x344ce8c VA: 0x7595a64e8c
	public Void RefreshFavorUpTrackPoint() { }
	// RVA: 0x344cf70 VA: 0x7595a64f70
	public Void RefreshMilestoneTrackPoint() { }
	// RVA: 0x344d060 VA: 0x7595a65060
	public Void RefreshMissionTrackPoint() { }
	// RVA: 0x344d134 VA: 0x7595a65134
	public Void RefreshNewCharmTrackPoint() { }
	// RVA: 0x344d1d0 VA: 0x7595a651d0
	public Void RefreshRecycleCharmTrackPoint() { }
	// RVA: 0x344d26c VA: 0x7595a6526c
	public Void RefreshHonorShowcaseTrackPoint() { }
	// RVA: 0x344dd68 VA: 0x7595a65d68
	public Void CheckMissionAndRefreshTrackPoint() { }
	// RVA: 0x344d8ac VA: 0x7595a658ac
	public List`1 FetchFavorUpList() { }
	// RVA: 0x344de70 VA: 0x7595a65e70
	private IEnumerator _TrySyncMissionStatus() { }
	// RVA: 0x344d9a4 VA: 0x7595a659a4
	private Boolean _HasMissionNew() { }
	// RVA: 0x344dabc VA: 0x7595a65abc
	private Boolean _HasPhotoNew() { }
	// RVA: 0x344c5e0 VA: 0x7595a645e0
	private Void _InitMissionProperty() { }
	// RVA: 0x344df44 VA: 0x7595a65f44
	private Void _RefreshMissionProperty() { }
	// RVA: 0x344c978 VA: 0x7595a64978
	private Void _InitMilestoneProperty() { }
	// RVA: 0x344e150 VA: 0x7595a66150
	public Void .ctor() { }
	// RVA: 0x344e3b0 VA: 0x7595a663b0
	private IEnumerator <>n__0() { }
	// RVA: 0x344e3b8 VA: 0x7595a663b8
	private Boolean <>xLuaBaseProxy_get_disableStageEntryPartical() { }
	// RVA: 0x344e3c0 VA: 0x7595a663c0
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x344e3c8 VA: 0x7595a663c8
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x344e3d0 VA: 0x7595a663d0
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x344e400 VA: 0x7595a66400
	private IEnumerator <>xLuaBaseProxy_LoadCoroutine() { }
}
```