# StageActivityLoader

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SafeParentComponent _embedEntryParent`

- `SafeParentComponent _floatParent`

- `SafeParentComponent _mapDecorParent`

- `SafeParentComponent _stagePreviewParent`

- `SafeParentComponent _floatEntryParent`

- `ScreenEffectHolder _stageEntryPartical`

- `ActivityStageController m_actController`

- `String m_targetActivityId`

- `String m_targetActivityDynEntryId`

- `State m_state`

- `LoadContext m_loadContext`


## Properties

- `ActivityStageController activityController`


## Methods

- `Void Update()`

- `ActivityStageController get_activityController()`

- `Void NotifyStagePageResumed(UIPageTransContext)`

- `Void NotifyPageHideEffect()`

- `Void NotifyStageZoneSelectStateSetEffectEnable(Boolean)`

- `Boolean IsStateStable()`

- `IEnumerator WaitForStateStable()`

- `Void LoadActivity(String)`

- `Void _LoadActivityInternal(String)`

- `IEnumerator _LoadActivityCoroutine(String, LoadExtraParams)`

- `Void _ResetIfNecessary()`

- `ActivityStageController _InstantiateController(ActivityBasicInfo, ActivityStageController, String, ActivityStageDynEntry)`

- `Void _UnloadUnusedResources()`

- `Boolean _CheckResourceUnused(String, ResourceType)`

- `LoadActivityCommonFlowPlugin _GetFlowPlugin(String, LoadExtraParams)`

- `Void _NotifyActivityLoadToStagePage(ActivityStageController)`

- `IEnumerator _WaitForReadySignalFromController(String, IEnumerator)`

- `Coroutine _CoroutineWithPage(IEnumerator)`

- `Void _UpdateStageEntryParticalStatus(ActivityStageController)`

- `Void _GetZonesForActivity(String, List`1)`

- `Boolean _FocusToZone(String)`

- `ZoneViewModel _FindZone(String)`

- `String _GetCurrentSelectedZone()`

- `Void _ExitCurrentActivity()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageActivityLoader : PageSingleComponent
{
	private SafeParentComponent _embedEntryParent; // 0x20
	private SafeParentComponent _floatParent; // 0x28
	private SafeParentComponent _mapDecorParent; // 0x30
	private SafeParentComponent _stagePreviewParent; // 0x38
	private SafeParentComponent _floatEntryParent; // 0x40
	private ScreenEffectHolder _stageEntryPartical; // 0x48
	private ListDict`2 m_activities; // 0x50
	private List`1 m_activityZones; // 0x58
	private ActivityStageController m_actController; // 0x60
	private String m_targetActivityId; // 0x68
	private String m_targetActivityDynEntryId; // 0x70
	private Dictionary`2 m_activeResources; // 0x78
	private State m_state; // 0x80
	private LoadContext m_loadContext; // 0x88
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_RegisterActivityZones; // 0x8
	private static DelegateBridge __Hotfix0_get_activityController; // 0x10
	private static DelegateBridge __Hotfix0_get_activities; // 0x18
	private static DelegateBridge __Hotfix0_NotifyStagePageResumed; // 0x20
	private static DelegateBridge __Hotfix0_NotifyPageHideEffect; // 0x28
	private static DelegateBridge __Hotfix0_NotifyStageZoneSelectStateSetEffectEnable; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0_IsStateStable; // 0x40
	private static DelegateBridge __Hotfix0_WaitForStateStable; // 0x48
	private static DelegateBridge __Hotfix0_LoadActivity; // 0x50
	private static DelegateBridge __Hotfix0__LoadActivityInternal; // 0x58
	private static DelegateBridge __Hotfix0__LoadActivityCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__ResetIfNecessary; // 0x68
	private static DelegateBridge __Hotfix0__InstantiateController; // 0x70
	private static DelegateBridge __Hotfix0__ClearActivity; // 0x78
	private static DelegateBridge __Hotfix0__DeleteExternalComponent; // 0x80
	private static DelegateBridge __Hotfix0__SetupExternalComponentTransition; // 0x88
	private static DelegateBridge __Hotfix0__CheckInst; // 0x90
	private static DelegateBridge __Hotfix0__UnloadUnusedResources; // 0x98
	private static DelegateBridge __Hotfix0__CheckResourceUnused; // 0xa0
	private static DelegateBridge __Hotfix0__GetFlowPlugin; // 0xa8
	private static DelegateBridge __Hotfix0__NotifyActivityLoadToStagePage; // 0xb0
	private static DelegateBridge __Hotfix0__WaitForReadySignalFromController; // 0xb8
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateStageEntryParticalStatus; // 0xc8
	private static DelegateBridge __Hotfix0__GetZonesForActivity; // 0xd0
	private static DelegateBridge __Hotfix0__FocusToZone; // 0xd8
	private static DelegateBridge __Hotfix0__FindZone; // 0xe0
	private static DelegateBridge __Hotfix0__GetCurrentSelectedZone; // 0xe8
	private static DelegateBridge __Hotfix0__ExitCurrentActivity; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public ActivityStageController activityController { get; }
	public ListDict`2 activities { get; }

	// RVA: 0x2f8308c VA: 0x759559b08c
	private Void Update() { }
	// RVA: 0x2f7afb4 VA: 0x7595592fb4
	public static Void RegisterActivityZones(Interface page, ListDict`2 zones) { }
	// RVA: 0x2f8200c VA: 0x759559a00c
	public ActivityStageController get_activityController() { }
	// RVA: 0x2f82074 VA: 0x759559a074
	public ListDict`2 get_activities() { }
	// RVA: 0x2f83228 VA: 0x759559b228
	public Void NotifyStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x2f83330 VA: 0x759559b330
	public Void NotifyPageHideEffect() { }
	// RVA: 0x2f833f8 VA: 0x759559b3f8
	public Void NotifyStageZoneSelectStateSetEffectEnable(Boolean enable) { }
	// RVA: 0x2f834dc VA: 0x759559b4dc
	protected override Void OnDestroy() { }
	// RVA: 0x2f836d8 VA: 0x759559b6d8
	public Boolean IsStateStable() { }
	// RVA: 0x2f83754 VA: 0x759559b754
	public IEnumerator WaitForStateStable() { }
	// RVA: 0x2f81f4c VA: 0x7595599f4c
	public Void LoadActivity(String activityId) { }
	// RVA: 0x2f83828 VA: 0x759559b828
	private Void _LoadActivityInternal(String activityId) { }
	// RVA: 0x2f83a00 VA: 0x759559ba00
	private IEnumerator _LoadActivityCoroutine(String activityId, LoadExtraParams extraParams) { }
	// RVA: 0x2f83550 VA: 0x759559b550
	private Void _ResetIfNecessary() { }
	// RVA: 0x2f843c0 VA: 0x759559c3c0
	private ActivityStageController _InstantiateController(ActivityBasicInfo basicInfo, ActivityStageController prefab, String dynEntryId, ActivityStageDynEntry dynEntryPrefab) { }
	// RVA: 0x2f83bc8 VA: 0x759559bbc8
	private static Void _ClearActivity(ActivityStageController controller) { }
	// RVA: 0x2f848f0 VA: 0x759559c8f0
	private static Void _DeleteExternalComponent(MonoBehaviour comp) { }
	// RVA: 0x2f849b0 VA: 0x759559c9b0
	private static Void _SetupExternalComponentTransition(MonoBehaviour comp, SafeParentComponent parent) { }
	// RVA: 0x2f83154 VA: 0x759559b154
	private static StageActivityLoader _CheckInst(Interface pageInterface) { }
	// RVA: 0x2f83d9c VA: 0x759559bd9c
	private Void _UnloadUnusedResources() { }
	// RVA: 0x2f84b68 VA: 0x759559cb68
	private Boolean _CheckResourceUnused(String resourceId, ResourceType resourceType) { }
	// RVA: 0x2f84cd4 VA: 0x759559ccd4
	private LoadActivityCommonFlowPlugin _GetFlowPlugin(String activityId, LoadExtraParams extraParams) { }
	// RVA: 0x2f84f8c VA: 0x759559cf8c
	private Void _NotifyActivityLoadToStagePage(ActivityStageController controller) { }
	// RVA: 0x2f850c8 VA: 0x759559d0c8
	private IEnumerator _WaitForReadySignalFromController(String activityId, IEnumerator coroutine) { }
	// RVA: 0x2f851b0 VA: 0x759559d1b0
	private Coroutine _CoroutineWithPage(IEnumerator routine) { }
	// RVA: 0x2f842a4 VA: 0x759559c2a4
	private Void _UpdateStageEntryParticalStatus(ActivityStageController controller) { }
	// RVA: 0x2f8526c VA: 0x759559d26c
	private Void _GetZonesForActivity(String acitivtyId, List`1 outputList) { }
	// RVA: 0x2f85424 VA: 0x759559d424
	private Boolean _FocusToZone(String zoneId) { }
	// RVA: 0x2f85554 VA: 0x759559d554
	private ZoneViewModel _FindZone(String zoneId) { }
	// RVA: 0x2f856bc VA: 0x759559d6bc
	private String _GetCurrentSelectedZone() { }
	// RVA: 0x2f8580c VA: 0x759559d80c
	private Void _ExitCurrentActivity() { }
	// RVA: 0x2f85964 VA: 0x759559d964
	public Void .ctor() { }
	// RVA: 0x2f85ad4 VA: 0x759559dad4
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```