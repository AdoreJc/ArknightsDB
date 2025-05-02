# Act29sideActivityController

**Namespace:** `Torappu.Activity.Act29side`


## Methods

- `Act29SideData _GetData()`

- `PlayerAct29SideActivity _GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityMissionGroupViewModel _GenMissionViewModel()`

- `TemplateActivityMissionViewModel _GenTemplateMissionViewModel()`

- `TemplateActivityCoinViewModel _GenCoinViewModel()`

- `TemplateActivityFavorViewModel _GenFavorViewModel()`

- `Act29sideEntryTuningViewModel _GenGroceryViewModel()`

- `Void _UpdateViewModel()`

- `Int32 _GetCoinCount()`

- `Int32 <_GenCoinViewModel>b__10_0()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29side
public class Act29sideActivityController : TemplateActivityController, IHotfixable
{
	private const String TUNING_VIEWMODEL; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x10
	private static DelegateBridge __Hotfix0__GetData; // 0x18
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x20
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x28
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenMissionViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenTemplateMissionViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenCoinViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenFavorViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GenGroceryViewModel; // 0x58
	private static DelegateBridge __Hotfix0__UpdateViewModel; // 0x60
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x68
	private static DelegateBridge __Hotfix0__GetCoinCount; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x3262278 VA: 0x759587a278
	public override Void InitModelDict(String actId) { }
	// RVA: 0x3262ff8 VA: 0x759587aff8
	protected override Void OnStageTimeout() { }
	// RVA: 0x326316c VA: 0x759587b16c
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x326321c VA: 0x759587b21c
	private Act29SideData _GetData() { }
	// RVA: 0x3263388 VA: 0x759587b388
	private PlayerAct29SideActivity _GetPlayerData() { }
	// RVA: 0x3262468 VA: 0x759587a468
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x326257c VA: 0x759587a57c
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x3262860 VA: 0x759587a860
	private TemplateActivityMissionGroupViewModel _GenMissionViewModel() { }
	// RVA: 0x3262a58 VA: 0x759587aa58
	private TemplateActivityMissionViewModel _GenTemplateMissionViewModel() { }
	// RVA: 0x3262b10 VA: 0x759587ab10
	private TemplateActivityCoinViewModel _GenCoinViewModel() { }
	// RVA: 0x3262c3c VA: 0x759587ac3c
	private TemplateActivityFavorViewModel _GenFavorViewModel() { }
	// RVA: 0x3262d44 VA: 0x759587ad44
	private Act29sideEntryTuningViewModel _GenGroceryViewModel() { }
	// RVA: 0x326306c VA: 0x759587b06c
	private Void _UpdateViewModel() { }
	// RVA: 0x32636e8 VA: 0x759587b6e8
	public override TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x3263800 VA: 0x759587b800
	private Int32 _GetCoinCount() { }
	// RVA: 0x3263874 VA: 0x759587b874
	public Void .ctor() { }
	// RVA: 0x32638e4 VA: 0x759587b8e4
	private Int32 <_GenCoinViewModel>b__10_0() { }
	// RVA: 0x3263900 VA: 0x759587b900
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x3263908 VA: 0x759587b908
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x3263938 VA: 0x759587b938
	private TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam() { }
}
```