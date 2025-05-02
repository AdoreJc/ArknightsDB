# Act35sideActivityController

**Namespace:** `Torappu.Activity.Act35side`


## Methods

- `Act35SideData _GetData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityCoinViewModel _GenCoinViewModel()`

- `TemplateActivityFavorViewModel _GenFavorViewModel()`

- `Act35sideMilestoneGroupViewModel _GenMilestoneViewModel()`

- `Act35sideEntryCarvingViewModel _GenCarvingViewModel()`

- `TemplateActivityMissionViewModel _GenTemplateMissionViewModel()`

- `Void _UpdateViewModel()`

- `Void EventOnOpenMilestoneState()`

- `TemplateMissionCoinViewModel _GenMissionCoinViewModel()`

- `Int32 _GetCoinCount()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act35side
public class Act35sideActivityController : TemplateActivityController, IHotfixable
{
	private const String CARVING_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x10
	private static DelegateBridge __Hotfix0__GetData; // 0x18
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x20
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x28
	private static DelegateBridge __Hotfix0__GenCoinViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenFavorViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenMilestoneViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenCarvingViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenTemplateMissionViewModel; // 0x50
	private static DelegateBridge __Hotfix0__UpdateViewModel; // 0x58
	private static DelegateBridge __Hotfix0_EventOnOpenMilestoneState; // 0x60
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x68
	private static DelegateBridge __Hotfix0__GenMissionCoinViewModel; // 0x70
	private static DelegateBridge __Hotfix0__GetCoinCount; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x325049c VA: 0x759586849c
	public override Void InitModelDict(String actId) { }
	// RVA: 0x32511c4 VA: 0x75958691c4
	protected override Void OnStageTimeout() { }
	// RVA: 0x3251238 VA: 0x7595869238
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x32512e8 VA: 0x75958692e8
	private Act35SideData _GetData() { }
	// RVA: 0x3250680 VA: 0x7595868680
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x3250794 VA: 0x7595868794
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x3250bac VA: 0x7595868bac
	private TemplateActivityCoinViewModel _GenCoinViewModel() { }
	// RVA: 0x3250a58 VA: 0x7595868a58
	private TemplateActivityFavorViewModel _GenFavorViewModel() { }
	// RVA: 0x3250cd8 VA: 0x7595868cd8
	private Act35sideMilestoneGroupViewModel _GenMilestoneViewModel() { }
	// RVA: 0x3250e1c VA: 0x7595868e1c
	private Act35sideEntryCarvingViewModel _GenCarvingViewModel() { }
	// RVA: 0x3250f98 VA: 0x7595868f98
	private TemplateActivityMissionViewModel _GenTemplateMissionViewModel() { }
	// RVA: 0x3251050 VA: 0x7595869050
	private Void _UpdateViewModel() { }
	// RVA: 0x32519f4 VA: 0x75958699f4
	public Void EventOnOpenMilestoneState() { }
	// RVA: 0x3251be0 VA: 0x7595869be0
	public override TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x3251e28 VA: 0x7595869e28
	private TemplateMissionCoinViewModel _GenMissionCoinViewModel() { }
	// RVA: 0x3251f0c VA: 0x7595869f0c
	private Int32 _GetCoinCount() { }
	// RVA: 0x3251fbc VA: 0x7595869fbc
	public Void .ctor() { }
	// RVA: 0x325202c VA: 0x759586a02c
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x3252034 VA: 0x759586a034
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x3252064 VA: 0x759586a064
	private TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam() { }
}
```