# Act42D0ActivityController

**Namespace:** `Torappu.Activity.Act42D0`


## Methods

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityMedalViewModel _GenMedalViewModel()`

- `TemplateActivityMilestoneGroupViewModel _GenMilestoneViewModel()`

- `Act42D0EntryNormalMapBtnViewModel _GenNormalMapBtnViewModel()`

- `Act42D0EntryChallengeMapBtnViewModel _GenChallengeMapBtnViewModel()`

- `Void EventOnOpenMilestone()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ActivityController : TemplateActivityController
{
	private const String NORMAL_PARAM; // 0x0
	private const String CHALLENGE_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x8
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x10
	private static DelegateBridge __Hotfix0__GenMedalViewModel; // 0x18
	private static DelegateBridge __Hotfix0__GenMilestoneViewModel; // 0x20
	private static DelegateBridge __Hotfix0__GenNormalMapBtnViewModel; // 0x28
	private static DelegateBridge __Hotfix0__GenChallengeMapBtnViewModel; // 0x30
	private static DelegateBridge __Hotfix0_EventOnOpenMilestone; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31e2890 VA: 0x75957fa890
	public override Void InitModelDict(String actId) { }
	// RVA: 0x31e2fd0 VA: 0x75957fafd0
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x31e2a00 VA: 0x75957faa00
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x31e2b14 VA: 0x75957fab14
	private TemplateActivityMedalViewModel _GenMedalViewModel() { }
	// RVA: 0x31e2c28 VA: 0x75957fac28
	private TemplateActivityMilestoneGroupViewModel _GenMilestoneViewModel() { }
	// RVA: 0x31e2d90 VA: 0x75957fad90
	private Act42D0EntryNormalMapBtnViewModel _GenNormalMapBtnViewModel() { }
	// RVA: 0x31e2eb0 VA: 0x75957faeb0
	private Act42D0EntryChallengeMapBtnViewModel _GenChallengeMapBtnViewModel() { }
	// RVA: 0x31e3200 VA: 0x75957fb200
	public Void EventOnOpenMilestone() { }
	// RVA: 0x31e3334 VA: 0x75957fb334
	public Void .ctor() { }
	// RVA: 0x31e33a4 VA: 0x75957fb3a4
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
}
```