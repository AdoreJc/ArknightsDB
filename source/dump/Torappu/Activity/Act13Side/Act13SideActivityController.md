# Act13SideActivityController

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideZoneDescGroupViewProperty m_zoneDescGroupViewProperty`

- `Act13sideMissionFinishViewModel missionFinishViewModel`


## Properties

- `Act13sideZoneDescGroupViewProperty zoneDescGroupViewProperty`


## Methods

- `Act13sideZoneDescGroupViewProperty get_zoneDescGroupViewProperty()`

- `Void _TriggerTutorialIfNeed()`

- `PlayerAct13sideActivity GetPlayerData()`

- `Act13SideData GetData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityZoneGroupViewModel _GenZoneViewModel()`

- `Act13sideButtonViewModel _GenButtonStateViewModel(ActState)`

- `TemplateActivityCoinViewModel _GenCoinStateViewModel()`

- `TemplateActivityFavorViewModel _GenFavorStateViewModel()`

- `TemplateActivityMissionGroupViewModel _GenActivityMissionViewModel(Act13SideData)`

- `Void OnSelectMissionGroup(String)`

- `Void SendConfirmMission(String)`

- `Void SendConfirmAllMission(String)`

- `Void EventOnZoneClicked(String)`

- `Int32 <_GenCoinStateViewModel>b__15_0()`

- `Void <SendConfirmAllMission>b__29_0(Act13SideLongTermMissionAllCommitResponse)`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `ActivityStageBridge <>xLuaBaseProxy_CreateBridge()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13SideActivityController : TemplateActivityController
{
	public const String BUTTON_STATE_VIEWMODEL; // 0x0
	private Act13sideZoneDescGroupViewProperty m_zoneDescGroupViewProperty; // 0x88
	public Act13sideMissionFinishViewModel missionFinishViewModel; // 0x90
	public const String ORG_ID; // 0x0
	public const String MISSION_GROUP; // 0x0
	public const String PRINCIPAL_ID; // 0x0
	public const String FINISH_DESC; // 0x0
	public const String JUMP_STAGEID; // 0x0
	public const String HAVE_STAGE_BTN; // 0x0
	public const String MISSION_TITLE; // 0x0
	public const String MISSION_TYPE; // 0x0
	private static DelegateBridge __Hotfix0_get_zoneDescGroupViewProperty; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x8
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x10
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x18
	private static DelegateBridge __Hotfix0__TriggerTutorialIfNeed; // 0x20
	private static DelegateBridge __Hotfix0_GetPlayerData; // 0x28
	private static DelegateBridge __Hotfix0_GetData; // 0x30
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x38
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenButtonStateViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenCoinStateViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GenFavorStateViewModel; // 0x58
	private static DelegateBridge __Hotfix0__GenActivityMissionViewModel; // 0x60
	private static DelegateBridge __Hotfix0_OnSelectMissionGroup; // 0x68
	private static DelegateBridge __Hotfix0_SendConfirmMission; // 0x70
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x78
	private static DelegateBridge __Hotfix0_SendConfirmAllMission; // 0x80
	private static DelegateBridge __Hotfix0_EventOnZoneClicked; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Act13sideZoneDescGroupViewProperty zoneDescGroupViewProperty { get; }

	// RVA: 0x3422934 VA: 0x7595a3a934
	public Act13sideZoneDescGroupViewProperty get_zoneDescGroupViewProperty() { }
	// RVA: 0x342299c VA: 0x7595a3a99c
	public override Void InitModelDict(String actId) { }
	// RVA: 0x3423c70 VA: 0x7595a3bc70
	protected override Void OnLoaded() { }
	// RVA: 0x3423e88 VA: 0x7595a3be88
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x3423db8 VA: 0x7595a3bdb8
	private Void _TriggerTutorialIfNeed() { }
	// RVA: 0x3424034 VA: 0x7595a3c034
	public PlayerAct13sideActivity GetPlayerData() { }
	// RVA: 0x3422b5c VA: 0x7595a3ab5c
	public Act13SideData GetData() { }
	// RVA: 0x3423810 VA: 0x7595a3b810
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x3422cac VA: 0x7595a3acac
	private TemplateActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x3423a2c VA: 0x7595a3ba2c
	private Act13sideButtonViewModel _GenButtonStateViewModel(ActState actState) { }
	// RVA: 0x3423b3c VA: 0x7595a3bb3c
	private TemplateActivityCoinViewModel _GenCoinStateViewModel() { }
	// RVA: 0x3423924 VA: 0x7595a3b924
	private TemplateActivityFavorViewModel _GenFavorStateViewModel() { }
	// RVA: 0x3423030 VA: 0x7595a3b030
	private TemplateActivityMissionGroupViewModel _GenActivityMissionViewModel(Act13SideData data) { }
	// RVA: 0x3424154 VA: 0x7595a3c154
	public Void OnSelectMissionGroup(String missionGroupId) { }
	// RVA: 0x34242c0 VA: 0x7595a3c2c0
	public Void SendConfirmMission(String missionId) { }
	// RVA: 0x342455c VA: 0x7595a3c55c
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onAfterItemShow) { }
	// RVA: 0x3424654 VA: 0x7595a3c654
	public Void SendConfirmAllMission(String missionGroupId) { }
	// RVA: 0x3424898 VA: 0x7595a3c898
	public Void EventOnZoneClicked(String zoneId) { }
	// RVA: 0x3424938 VA: 0x7595a3c938
	public Void .ctor() { }
	// RVA: 0x34249e8 VA: 0x7595a3c9e8
	private Int32 <_GenCoinStateViewModel>b__15_0() { }
	// RVA: 0x3424a04 VA: 0x7595a3ca04
	private Void <SendConfirmAllMission>b__29_0(Act13SideLongTermMissionAllCommitResponse response) { }
	// RVA: 0x3424c48 VA: 0x7595a3cc48
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x3424c50 VA: 0x7595a3cc50
	private ActivityStageBridge <>xLuaBaseProxy_CreateBridge() { }
}
```