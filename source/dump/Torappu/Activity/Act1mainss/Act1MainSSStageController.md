# Act1MainSSStageController

**Namespace:** `Torappu.Activity.Act1mainss`


## Fields

- `MissionArchiveDataServiceProxy _missionArchiveProxy`

- `RectTransform _entryContainer`

- `UICompDialogMgr m_dlgMgr`


## Properties

- `UICompDialogMgr dlgMgr`


## Methods

- `UICompDialogMgr get_dlgMgr()`

- `Void ClaimApReward()`

- `Void _OnApRewardProceed(Act1MainSSGetInfRewardResponse)`

- `Void OnZoneClick(String)`

- `Void OnActDetailClick()`

- `Void OpenMissionArchive(String)`

- `ActivityYear5GeneralData _GetGameData()`

- `PlayerYear5GeneralActivity _GetPlayerData()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `Act1MainSSZoneGroupViewModel _GenZoneViewModel(TemplateActivityLifeCycleViewModel)`

- `TemplateActivityFavorViewModel _GenFavorStateViewModel()`

- `TemplateActivityMissionArchiveViewModel _GenMissionArchiveViewModel()`

- `Act1MainSSApCostRewardViewModel _GenApCostRewardViewModel()`

- `TemplateActivityCoinViewModel _GenCoinStateViewModel()`

- `Act1MainSSHomeExploreViewModel _GenExploreViewModel(TemplateActivityLifeCycleViewModel)`

- `Int32 <_GenCoinStateViewModel>b__21_0()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1mainss
public class Act1MainSSStageController : TemplateActivityController, IMissionArchiveEntry
{
	private MissionArchiveDataServiceProxy _missionArchiveProxy; // 0x88
	private RectTransform _entryContainer; // 0x90
	private UICompDialogMgr m_dlgMgr; // 0x98
	public const String AP_COST_REWARD; // 0x0
	public const String EXPLORE; // 0x0
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x8
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x10
	private static DelegateBridge __Hotfix0_ClaimApReward; // 0x18
	private static DelegateBridge __Hotfix0__OnApRewardProceed; // 0x20
	private static DelegateBridge __Hotfix0_OnZoneClick; // 0x28
	private static DelegateBridge __Hotfix0_OnActDetailClick; // 0x30
	private static DelegateBridge __Hotfix0_OpenMissionArchive; // 0x38
	private static DelegateBridge __Hotfix0__GetGameData; // 0x40
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x48
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x50
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x58
	private static DelegateBridge __Hotfix0__GenFavorStateViewModel; // 0x60
	private static DelegateBridge __Hotfix0__GenMissionArchiveViewModel; // 0x68
	private static DelegateBridge __Hotfix0__GenApCostRewardViewModel; // 0x70
	private static DelegateBridge __Hotfix0__GenCoinStateViewModel; // 0x78
	private static DelegateBridge __Hotfix0__GenExploreViewModel; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public UICompDialogMgr dlgMgr { get; }

	// RVA: 0x338f630 VA: 0x75959a7630
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x338f698 VA: 0x75959a7698
	public override Void InitModelDict(String actId) { }
	// RVA: 0x33901dc VA: 0x75959a81dc
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x33903dc VA: 0x75959a83dc
	public Void ClaimApReward() { }
	// RVA: 0x33907b4 VA: 0x75959a87b4
	private Void _OnApRewardProceed(Act1MainSSGetInfRewardResponse response) { }
	// RVA: 0x3390954 VA: 0x75959a8954
	public Void OnZoneClick(String zoneId) { }
	// RVA: 0x3390c08 VA: 0x75959a8c08
	public Void OnActDetailClick() { }
	// RVA: 0x3390cc0 VA: 0x75959a8cc0
	public Void OpenMissionArchive(String topicId) { }
	// RVA: 0x3390dac VA: 0x75959a8dac
	private ActivityYear5GeneralData _GetGameData() { }
	// RVA: 0x3390ec0 VA: 0x75959a8ec0
	private PlayerYear5GeneralActivity _GetPlayerData() { }
	// RVA: 0x338f8c4 VA: 0x75959a78c4
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x338fae0 VA: 0x75959a7ae0
	private Act1MainSSZoneGroupViewModel _GenZoneViewModel(TemplateActivityLifeCycleViewModel lfViewModel) { }
	// RVA: 0x338f9d8 VA: 0x75959a79d8
	private TemplateActivityFavorViewModel _GenFavorStateViewModel() { }
	// RVA: 0x338fda4 VA: 0x75959a7da4
	private TemplateActivityMissionArchiveViewModel _GenMissionArchiveViewModel() { }
	// RVA: 0x338fee4 VA: 0x75959a7ee4
	private Act1MainSSApCostRewardViewModel _GenApCostRewardViewModel() { }
	// RVA: 0x338ffc4 VA: 0x75959a7fc4
	private TemplateActivityCoinViewModel _GenCoinStateViewModel() { }
	// RVA: 0x33900f0 VA: 0x75959a80f0
	private Act1MainSSHomeExploreViewModel _GenExploreViewModel(TemplateActivityLifeCycleViewModel lfViewModel) { }
	// RVA: 0x3391394 VA: 0x75959a9394
	public Void .ctor() { }
	// RVA: 0x3391404 VA: 0x75959a9404
	private Int32 <_GenCoinStateViewModel>b__21_0() { }
	// RVA: 0x3391420 VA: 0x75959a9420
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
}
```