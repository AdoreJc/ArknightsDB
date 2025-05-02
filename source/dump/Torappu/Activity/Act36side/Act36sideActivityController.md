# Act36sideActivityController

**Namespace:** `Torappu.Activity.Act36side`


## Methods

- `Act36SideData _GetData()`

- `PlayerAct36SideActivity _GetPlayerData()`

- `Int32 _GetCoinCount()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityMissionViewModel _GenTemplateMissionViewModel()`

- `TemplateMissionCoinViewModel _GenMissionCoinViewModel()`

- `TemplateActivityCoinViewModel _GenCoinViewModel()`

- `TemplateActivityFavorViewModel _GenFavorViewModel()`

- `Act36sideEntryFoodHandbookViewModel _GenFoodHandbookViewModel()`

- `Void _UpdateViewModel()`

- `Int32 <_GenCoinViewModel>b__12_0()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideActivityController : TemplateActivityController, IHotfixable
{
	private const String FOOD_HANDBOOK_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x10
	private static DelegateBridge __Hotfix0__GetData; // 0x18
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x20
	private static DelegateBridge __Hotfix0__GetCoinCount; // 0x28
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x30
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenTemplateMissionViewModel; // 0x40
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x48
	private static DelegateBridge __Hotfix0__GenMissionCoinViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GenCoinViewModel; // 0x58
	private static DelegateBridge __Hotfix0__GenFavorViewModel; // 0x60
	private static DelegateBridge __Hotfix0__GenFoodHandbookViewModel; // 0x68
	private static DelegateBridge __Hotfix0__UpdateViewModel; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x32420a8 VA: 0x759585a0a8
	public override Void InitModelDict(String actId) { }
	// RVA: 0x3242b74 VA: 0x759585ab74
	protected override Void OnStageTimeout() { }
	// RVA: 0x3242ce8 VA: 0x759585ace8
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x3242d98 VA: 0x759585ad98
	private Act36SideData _GetData() { }
	// RVA: 0x3242f04 VA: 0x759585af04
	private PlayerAct36SideActivity _GetPlayerData() { }
	// RVA: 0x324307c VA: 0x759585b07c
	private Int32 _GetCoinCount() { }
	// RVA: 0x324225c VA: 0x759585a25c
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x3242370 VA: 0x759585a370
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x3242654 VA: 0x759585a654
	private TemplateActivityMissionViewModel _GenTemplateMissionViewModel() { }
	// RVA: 0x32430f0 VA: 0x759585b0f0
	public override TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x3243338 VA: 0x759585b338
	private TemplateMissionCoinViewModel _GenMissionCoinViewModel() { }
	// RVA: 0x324270c VA: 0x759585a70c
	private TemplateActivityCoinViewModel _GenCoinViewModel() { }
	// RVA: 0x3242838 VA: 0x759585a838
	private TemplateActivityFavorViewModel _GenFavorViewModel() { }
	// RVA: 0x3242940 VA: 0x759585a940
	private Act36sideEntryFoodHandbookViewModel _GenFoodHandbookViewModel() { }
	// RVA: 0x3242be8 VA: 0x759585abe8
	private Void _UpdateViewModel() { }
	// RVA: 0x32434ec VA: 0x759585b4ec
	public Void .ctor() { }
	// RVA: 0x324355c VA: 0x759585b55c
	private Int32 <_GenCoinViewModel>b__12_0() { }
	// RVA: 0x3243578 VA: 0x759585b578
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x3243580 VA: 0x759585b580
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x32435b0 VA: 0x759585b5b0
	private TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam() { }
}
```