# Act24sideActivityController

**Namespace:** `Torappu.Activity.Act24side`


## Methods

- `Void NotifyBtnQuestClicked(String)`

- `PlayerAct24SideActivity _GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityFavorViewModel _GenFavorStateViewModel()`

- `Act24sideEntryViewModel _GenButtonGroupViewModel()`

- `Act24sideStageMeldingViewModel _GenMeldingViewModel()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideActivityController : TemplateActivityController
{
	public const String BUTTON_VIEWMODEL; // 0x0
	public const String STAGE_MELDING; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x8
	private static DelegateBridge __Hotfix0_NotifyBtnQuestClicked; // 0x10
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x18
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x20
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x28
	private static DelegateBridge __Hotfix0__GenFavorStateViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenButtonGroupViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenMeldingViewModel; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x328b434 VA: 0x75958a3434
	public override Void InitModelDict(String actId) { }
	// RVA: 0x328bcd0 VA: 0x75958a3cd0
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x328be10 VA: 0x75958a3e10
	public Void NotifyBtnQuestClicked(String zoneId) { }
	// RVA: 0x328bfb4 VA: 0x75958a3fb4
	private PlayerAct24SideActivity _GetPlayerData() { }
	// RVA: 0x328b5a4 VA: 0x75958a35a4
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x328b7c0 VA: 0x75958a37c0
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x328b6b8 VA: 0x75958a36b8
	private TemplateActivityFavorViewModel _GenFavorStateViewModel() { }
	// RVA: 0x328bb08 VA: 0x75958a3b08
	private Act24sideEntryViewModel _GenButtonGroupViewModel() { }
	// RVA: 0x328bbec VA: 0x75958a3bec
	private Act24sideStageMeldingViewModel _GenMeldingViewModel() { }
	// RVA: 0x328c0d4 VA: 0x75958a40d4
	public Void .ctor() { }
	// RVA: 0x328c144 VA: 0x75958a4144
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
}
```