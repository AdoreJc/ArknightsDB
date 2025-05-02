# Act25sideActivityController

**Namespace:** `Torappu.Activity.Act25side`


## Methods

- `Void _OnStageFogUnlock(StageData, StageFogInfo, Action)`

- `PlayerAct25SideActivity _GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityFavorViewModel _GenFavorStateViewModel()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityCoinViewModel _GenCoinStateViewModel()`

- `TemplateActivityMissionGroupViewModel _GenActivityMissionViewModel()`

- `Act25sideEntryResearchViewModel _GenResearchViewModel()`

- `Act25sideEntryArchiveViewModel _GenArchiveViewModel()`

- `Act25sideMapDecorMissionGroupViewModel _GenResearchMissionViewModel()`

- `IEnumerator _OpenResearchPage(Act25sideDailyRefreshResponse)`

- `Void OnButtonResearchClicked()`

- `Void OnButtonArchiveClicked()`

- `Int32 <_GenCoinStateViewModel>b__11_0()`

- `Void <OnButtonResearchClicked>b__17_0(Act25sideDailyRefreshResponse)`

- `OnStageFogUnlock <>xLuaBaseProxy_OverrideStageFogUnlock()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideActivityController : TemplateActivityController
{
	public const String RESEARCH_PARAM; // 0x0
	public const String ARCHIVE_PARAM; // 0x0
	public const String RESEARCH_MISSION_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OverrideStageFogUnlock; // 0x8
	private static DelegateBridge __Hotfix0__OnStageFogUnlock; // 0x10
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x18
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x20
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x28
	private static DelegateBridge __Hotfix0__GenFavorStateViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenCoinStateViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenActivityMissionViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenResearchViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GenArchiveViewModel; // 0x58
	private static DelegateBridge __Hotfix0__GenResearchMissionViewModel; // 0x60
	private static DelegateBridge __Hotfix0__OpenResearchPage; // 0x68
	private static DelegateBridge __Hotfix0_OnButtonResearchClicked; // 0x70
	private static DelegateBridge __Hotfix0_OnButtonArchiveClicked; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x326ad00 VA: 0x7595882d00
	public override Void InitModelDict(String actId) { }
	// RVA: 0x326ba40 VA: 0x7595883a40
	public override OnStageFogUnlock OverrideStageFogUnlock() { }
	// RVA: 0x326baf4 VA: 0x7595883af4
	private Void _OnStageFogUnlock(StageData stageData, StageFogInfo stageFogInfo, Action onConfirmed) { }
	// RVA: 0x326bca0 VA: 0x7595883ca0
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x326bf00 VA: 0x7595883f00
	private PlayerAct25SideActivity _GetPlayerData() { }
	// RVA: 0x326af0c VA: 0x7595882f0c
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x326b020 VA: 0x7595883020
	private TemplateActivityFavorViewModel _GenFavorStateViewModel() { }
	// RVA: 0x326b128 VA: 0x7595883128
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x326b668 VA: 0x7595883668
	private TemplateActivityCoinViewModel _GenCoinStateViewModel() { }
	// RVA: 0x326b470 VA: 0x7595883470
	private TemplateActivityMissionGroupViewModel _GenActivityMissionViewModel() { }
	// RVA: 0x326b794 VA: 0x7595883794
	private Act25sideEntryResearchViewModel _GenResearchViewModel() { }
	// RVA: 0x326b878 VA: 0x7595883878
	private Act25sideEntryArchiveViewModel _GenArchiveViewModel() { }
	// RVA: 0x326b95c VA: 0x759588395c
	private Act25sideMapDecorMissionGroupViewModel _GenResearchMissionViewModel() { }
	// RVA: 0x326c020 VA: 0x7595884020
	private IEnumerator _OpenResearchPage(Act25sideDailyRefreshResponse response) { }
	// RVA: 0x326c118 VA: 0x7595884118
	public Void OnButtonResearchClicked() { }
	// RVA: 0x326c4cc VA: 0x75958844cc
	public Void OnButtonArchiveClicked() { }
	// RVA: 0x326c648 VA: 0x7595884648
	public Void .ctor() { }
	// RVA: 0x326c6b8 VA: 0x75958846b8
	private Int32 <_GenCoinStateViewModel>b__11_0() { }
	// RVA: 0x326c6d4 VA: 0x75958846d4
	private Void <OnButtonResearchClicked>b__17_0(Act25sideDailyRefreshResponse response) { }
	// RVA: 0x326c7d0 VA: 0x75958847d0
	private OnStageFogUnlock <>xLuaBaseProxy_OverrideStageFogUnlock() { }
	// RVA: 0x326c7d8 VA: 0x75958847d8
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
}
```