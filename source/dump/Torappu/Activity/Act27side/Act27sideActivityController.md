# Act27sideActivityController

**Namespace:** `Torappu.Activity.Act27side`


## Methods

- `Act27SideData _GetData()`

- `PlayerAct27SideActivity _GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityMissionGroupViewModel _GenMissionViewModel()`

- `TemplateActivityMissionViewModel _GenTemplateMissionViewModel()`

- `TemplateActivityCoinViewModel _GenCoinViewModel()`

- `TemplateActivityFavorViewModel _GenFavorViewModel()`

- `Act27sideEntryGroceryViewModel _GenGroceryViewModel()`

- `Void _UpdateViewModel()`

- `Int32 _GetCoinCount()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `String <>xLuaBaseProxy_GetBGMSignal()`

- `TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act27side
public class Act27sideActivityController : TemplateActivityController, IHotfixable
{
	private const String GROCERY_VIEWMODEL; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x10
	private static DelegateBridge __Hotfix0_GetBGMSignal; // 0x18
	private static DelegateBridge __Hotfix0__GetData; // 0x20
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x28
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x30
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenMissionViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenTemplateMissionViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenCoinViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GenFavorViewModel; // 0x58
	private static DelegateBridge __Hotfix0__GenGroceryViewModel; // 0x60
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x68
	private static DelegateBridge __Hotfix0__UpdateViewModel; // 0x70
	private static DelegateBridge __Hotfix0__GetCoinCount; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x32684d8 VA: 0x75958804d8
	public override Void InitModelDict(String actId) { }
	// RVA: 0x32692a0 VA: 0x75958812a0
	protected override Void OnStageTimeout() { }
	// RVA: 0x3269414 VA: 0x7595881414
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x32694c4 VA: 0x75958814c4
	protected override String GetBGMSignal() { }
	// RVA: 0x32696b4 VA: 0x75958816b4
	private Act27SideData _GetData() { }
	// RVA: 0x3269820 VA: 0x7595881820
	private PlayerAct27SideActivity _GetPlayerData() { }
	// RVA: 0x32686c8 VA: 0x75958806c8
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x32687dc VA: 0x75958807dc
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x3268aa0 VA: 0x7595880aa0
	private TemplateActivityMissionGroupViewModel _GenMissionViewModel() { }
	// RVA: 0x3268c98 VA: 0x7595880c98
	private TemplateActivityMissionViewModel _GenTemplateMissionViewModel() { }
	// RVA: 0x3268d50 VA: 0x7595880d50
	private TemplateActivityCoinViewModel _GenCoinViewModel() { }
	// RVA: 0x3268e7c VA: 0x7595880e7c
	private TemplateActivityFavorViewModel _GenFavorViewModel() { }
	// RVA: 0x3268f84 VA: 0x7595880f84
	private Act27sideEntryGroceryViewModel _GenGroceryViewModel() { }
	// RVA: 0x3269b10 VA: 0x7595881b10
	public override TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x3269314 VA: 0x7595881314
	private Void _UpdateViewModel() { }
	// RVA: 0x3269c28 VA: 0x7595881c28
	private Int32 _GetCoinCount() { }
	// RVA: 0x3269ca0 VA: 0x7595881ca0
	public Void .ctor() { }
	// RVA: 0x3269d10 VA: 0x7595881d10
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x3269d18 VA: 0x7595881d18
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x3269d48 VA: 0x7595881d48
	private String <>xLuaBaseProxy_GetBGMSignal() { }
	// RVA: 0x3269d50 VA: 0x7595881d50
	private TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam() { }
}
```