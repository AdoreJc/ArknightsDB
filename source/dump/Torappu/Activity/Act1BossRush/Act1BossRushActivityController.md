# Act1BossRushActivityController

**Namespace:** `Torappu.Activity.Act1BossRush`


## Methods

- `Void _TriggerTutorialIfNeed()`

- `ActivityBossRushData GetData()`

- `PlayerBossRushActivity GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityMedalViewModel _GenMedalViewModel()`

- `Act1BossRushEntryRelicButtonViewModel _GenEntryRelicButtonViewModel()`

- `Act1BossRushEntryMileStoneButtonViewModel _GenEntryMileStoneButtonViewModel()`

- `TemplateActivityMissionGroupViewModel _GenActivityMissionGroupViewModel(ActivityBossRushData)`

- `Void SendConfirmAllMission()`

- `Void SendConfirmMission(String)`

- `Void _ResponseOnClaimedMission(List`1)`

- `Boolean _TryGetRelicNameById(String, List`1, out)`

- `MilestoneStruct <_GenEntryMileStoneButtonViewModel>b__11_0()`

- `Boolean <_GenEntryMileStoneButtonViewModel>b__11_1()`

- `Void <SendConfirmAllMission>b__14_0(ActivityMissionCheckResponse)`

- `Void <SendConfirmMission>b__15_0(ActivityConfirmMissionResponse)`

- `Void <>xLuaBaseProxy_AfterEntryAnimPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushActivityController : TemplateActivityController
{
	private const String MILESTONE_VIEWMODEL; // 0x0
	private const String RELIC_VIEWMODEL; // 0x0
	public const String IS_RELIC_TASK; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0__TriggerTutorialIfNeed; // 0x8
	private static DelegateBridge __Hotfix0_AfterEntryAnimPlay; // 0x10
	private static DelegateBridge __Hotfix0_GetData; // 0x18
	private static DelegateBridge __Hotfix0_GetPlayerData; // 0x20
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x28
	private static DelegateBridge __Hotfix0__GenMedalViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenEntryRelicButtonViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenEntryMileStoneButtonViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenActivityMissionGroupViewModel; // 0x48
	private static DelegateBridge __Hotfix0_SendConfirmAllMission; // 0x50
	private static DelegateBridge __Hotfix0_SendConfirmMission; // 0x58
	private static DelegateBridge __Hotfix0__ResponseOnClaimedMission; // 0x60
	private static DelegateBridge __Hotfix0__TryGetRelicNameById; // 0x68
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x70
	private static DelegateBridge __Hotfix0__IsBattleEnd; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x318cccc VA: 0x75957a4ccc
	public override Void InitModelDict(String actId) { }
	// RVA: 0x318daa0 VA: 0x75957a5aa0
	private Void _TriggerTutorialIfNeed() { }
	// RVA: 0x318dd7c VA: 0x75957a5d7c
	protected override Void AfterEntryAnimPlay() { }
	// RVA: 0x318ce4c VA: 0x75957a4e4c
	public ActivityBossRushData GetData() { }
	// RVA: 0x318ddf0 VA: 0x75957a5df0
	public PlayerBossRushActivity GetPlayerData() { }
	// RVA: 0x318cf9c VA: 0x75957a4f9c
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x318d98c VA: 0x75957a598c
	private TemplateActivityMedalViewModel _GenMedalViewModel() { }
	// RVA: 0x318d0b0 VA: 0x75957a50b0
	private Act1BossRushEntryRelicButtonViewModel _GenEntryRelicButtonViewModel() { }
	// RVA: 0x318d3c0 VA: 0x75957a53c0
	private Act1BossRushEntryMileStoneButtonViewModel _GenEntryMileStoneButtonViewModel() { }
	// RVA: 0x318d554 VA: 0x75957a5554
	private TemplateActivityMissionGroupViewModel _GenActivityMissionGroupViewModel(ActivityBossRushData data) { }
	// RVA: 0x318e054 VA: 0x75957a6054
	public Void SendConfirmAllMission() { }
	// RVA: 0x318e458 VA: 0x75957a6458
	public Void SendConfirmMission(String missionId) { }
	// RVA: 0x318e704 VA: 0x75957a6704
	private Void _ResponseOnClaimedMission(List`1 rewardItemModels) { }
	// RVA: 0x318ec88 VA: 0x75957a6c88
	private Boolean _TryGetRelicNameById(String itemId, List`1 relicDatas, out String relicName) { }
	// RVA: 0x318ede8 VA: 0x75957a6de8
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x318dc70 VA: 0x75957a5c70
	private static Boolean _IsBattleEnd(String actId) { }
	// RVA: 0x318eebc VA: 0x75957a6ebc
	public Void .ctor() { }
	// RVA: 0x318ef2c VA: 0x75957a6f2c
	private MilestoneStruct <_GenEntryMileStoneButtonViewModel>b__11_0() { }
	// RVA: 0x318ef70 VA: 0x75957a6f70
	private Boolean <_GenEntryMileStoneButtonViewModel>b__11_1() { }
	// RVA: 0x318ef88 VA: 0x75957a6f88
	private Void <SendConfirmAllMission>b__14_0(ActivityMissionCheckResponse response) { }
	// RVA: 0x318efa0 VA: 0x75957a6fa0
	private Void <SendConfirmMission>b__15_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x318efb8 VA: 0x75957a6fb8
	private Void <>xLuaBaseProxy_AfterEntryAnimPlay() { }
}
```