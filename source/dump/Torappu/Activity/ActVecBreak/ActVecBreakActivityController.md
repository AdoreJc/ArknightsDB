# ActVecBreakActivityController

**Namespace:** `Torappu.Activity.ActVecBreak`


## Methods

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityMedalViewModel _GenMedalViewModel()`

- `ActVecBreakOffenseEntryViewModel _GenOffenseEntryViewModel()`

- `ActVecBreakDefenseEntryViewModel _GenDefenseEntryViewModel()`

- `TemplateActivityMilestoneGroupViewModel _GenVecBreakMileStoneViewModel()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `Void OnButtonVecBreakMileStoneClicked()`

- `Void OnButtonOffenseClicked()`

- `Void OnButtonDefenseClicked()`

- `String <>xLuaBaseProxy_GetTutorialCustomOperationKey()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakActivityController : TemplateActivityController
{
	public const String OFFENSE_ENTRY_PARAM; // 0x0
	public const String DEFENSE_ENTRY_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_GetTutorialCustomOperationKey; // 0x8
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x10
	private static DelegateBridge __Hotfix0__GenMedalViewModel; // 0x18
	private static DelegateBridge __Hotfix0__GenOffenseEntryViewModel; // 0x20
	private static DelegateBridge __Hotfix0__GenDefenseEntryViewModel; // 0x28
	private static DelegateBridge __Hotfix0__GenVecBreakMileStoneViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x38
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x40
	private static DelegateBridge __Hotfix0_OnButtonVecBreakMileStoneClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnButtonOffenseClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnButtonDefenseClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x30d2d6c VA: 0x75956ead6c
	public override Void InitModelDict(String actId) { }
	// RVA: 0x30d3634 VA: 0x75956eb634
	public override String GetTutorialCustomOperationKey() { }
	// RVA: 0x30d2f0c VA: 0x75956eaf0c
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x30d3020 VA: 0x75956eb020
	private TemplateActivityMedalViewModel _GenMedalViewModel() { }
	// RVA: 0x30d346c VA: 0x75956eb46c
	private ActVecBreakOffenseEntryViewModel _GenOffenseEntryViewModel() { }
	// RVA: 0x30d3550 VA: 0x75956eb550
	private ActVecBreakDefenseEntryViewModel _GenDefenseEntryViewModel() { }
	// RVA: 0x30d334c VA: 0x75956eb34c
	private TemplateActivityMilestoneGroupViewModel _GenVecBreakMileStoneViewModel() { }
	// RVA: 0x30d3134 VA: 0x75956eb134
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x30d36b8 VA: 0x75956eb6b8
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x30d37d0 VA: 0x75956eb7d0
	public Void OnButtonVecBreakMileStoneClicked() { }
	// RVA: 0x30d3950 VA: 0x75956eb950
	public Void OnButtonOffenseClicked() { }
	// RVA: 0x30d3a90 VA: 0x75956eba90
	public Void OnButtonDefenseClicked() { }
	// RVA: 0x30d3bc0 VA: 0x75956ebbc0
	public Void .ctor() { }
	// RVA: 0x30d3c30 VA: 0x75956ebc30
	private String <>xLuaBaseProxy_GetTutorialCustomOperationKey() { }
	// RVA: 0x30d3c38 VA: 0x75956ebc38
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
}
```