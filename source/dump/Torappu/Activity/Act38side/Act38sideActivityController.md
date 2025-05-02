# Act38sideActivityController

**Namespace:** `Torappu.Activity.Act38side`


## Methods

- `Act38SideData _GetData()`

- `PlayerAct38SideActivity _GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityMissionViewModel _GenTemplateMissionViewModel()`

- `TemplateActivityCoinViewModel _GenCoinViewModel()`

- `TemplateActivityFavorViewModel _GenFavorViewModel()`

- `Act38sideEntryFireworkPuzzleViewModel _GenFireworkPuzzleViewModel()`

- `Act38sideMapDecorFireworkCraftViewModel _GenFireworkCraftViewModel()`

- `Void _UpdateViewModel()`

- `Int32 _GetCoinCount()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideActivityController : TemplateActivityController, IHotfixable
{
	private const String FIREWORK_PUZZLE_VIEWMODEL; // 0x0
	private const String FIREWORK_CRAFT_VIEWMODEL; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x10
	private static DelegateBridge __Hotfix0__GetData; // 0x18
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x20
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x28
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenTemplateMissionViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenCoinViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenFavorViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenFireworkPuzzleViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GenFireworkCraftViewModel; // 0x58
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x60
	private static DelegateBridge __Hotfix0__UpdateViewModel; // 0x68
	private static DelegateBridge __Hotfix0__GetCoinCount; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x323c3e8 VA: 0x75958543e8
	public override Void InitModelDict(String actId) { }
	// RVA: 0x323ce30 VA: 0x7595854e30
	protected override Void OnStageTimeout() { }
	// RVA: 0x323d030 VA: 0x7595855030
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x323d0e0 VA: 0x75958550e0
	private Act38SideData _GetData() { }
	// RVA: 0x323d24c VA: 0x759585524c
	private PlayerAct38SideActivity _GetPlayerData() { }
	// RVA: 0x323c5c4 VA: 0x75958545c4
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x323c6d8 VA: 0x75958546d8
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x323c9bc VA: 0x75958549bc
	private TemplateActivityMissionViewModel _GenTemplateMissionViewModel() { }
	// RVA: 0x323ca74 VA: 0x7595854a74
	private TemplateActivityCoinViewModel _GenCoinViewModel() { }
	// RVA: 0x323cba0 VA: 0x7595854ba0
	private TemplateActivityFavorViewModel _GenFavorViewModel() { }
	// RVA: 0x323cca8 VA: 0x7595854ca8
	private Act38sideEntryFireworkPuzzleViewModel _GenFireworkPuzzleViewModel() { }
	// RVA: 0x323cd90 VA: 0x7595854d90
	private Act38sideMapDecorFireworkCraftViewModel _GenFireworkCraftViewModel() { }
	// RVA: 0x323da4c VA: 0x7595855a4c
	public override TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x323cea4 VA: 0x7595854ea4
	private Void _UpdateViewModel() { }
	// RVA: 0x323db64 VA: 0x7595855b64
	private Int32 _GetCoinCount() { }
	// RVA: 0x323dbdc VA: 0x7595855bdc
	public Void .ctor() { }
	// RVA: 0x323dc4c VA: 0x7595855c4c
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x323dc54 VA: 0x7595855c54
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x323dc84 VA: 0x7595855c84
	private TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam() { }
}
```