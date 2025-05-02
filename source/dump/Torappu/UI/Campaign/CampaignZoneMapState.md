# CampaignZoneMapState

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignZoneMapStateBean _stateBean`

- `CampaignZoneMapContainer _container`

- `PrefabInstHolder _campFeeHolder`

- `TopMenuDynamicPrefabInstHolder _topmenuHolder`

- `AnimationWrapper _animationWrapper`

- `UnityEvent _openCampaign`

- `CampaignStagePreviewConfigController _previewConfigCtrl`

- `CampaignFeeView m_campFeeView`

- `Boolean m_cacheIsToBreakingDetail`

- `String m_cacheJumpStageId`

- `CampaignStageMapViewModel m_targetModelToRuleState`

- `Boolean m_mapLoadedCache`

- `Boolean m_switchZoneLock`

- `FastCampStateParam m_toFastCamp`


## Methods

- `Void _OnJumpToMissionState(IStateBean)`

- `Void _OnJumpToCampaignRuleView(IStateBean)`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void _OnInitCampFee(GameObject)`

- `Void _OnHandleJump(String)`

- `Void ToJumpState()`

- `Void OnOpenRewardClick()`

- `Void OnOpenRuleClick()`

- `Void OnOpenEnemyClick()`

- `Void OnClickStageId(String)`

- `Void OnStartBattleClick()`

- `Void ClosePreviewState()`

- `Void EventOnCampaignBreakRewardConfirmed(String, Int32)`

- `Void _OnCleanSelectStage()`

- `Void _OnSelectStage(String)`

- `Boolean _CheckCostBeforeStartBattle()`

- `Boolean _CheckApBeforeStartBattle(Int32)`

- `Void _SaveCacheStageConfig()`

- `Void _GoToSquad()`

- `Boolean _CheckNeedToLoadBattleLog(out)`

- `Void _OnGoToSquad(String)`

- `Void _EventOnCampFeeClicked()`

- `Boolean _LockSwitchZone()`

- `Void _UnlockSwitchZone()`

- `Void _OnSwitchSelectStateEnd()`

- `IEnumerator _SwitchSelectStateCoroutine(CampaignZoneMapViewModel, CampaignStageMapViewModel, Boolean)`

- `CampAutoSwitchOptions _GenerateAutoSwitchOptions()`

- `Void _OnAutoBattleClicked()`

- `Void _OnFastBattleClicked()`

- `Void _OnTryTriggerFastCampTutorial()`

- `Void _OnFastCampInfoClicked()`

- `Void _OnJumpToFastCampState(IStateBean)`

- `Void _GoToFastBattle()`

- `Void <OnEnter>b__13_0(GameObject)`

- `Void <OnEnter>b__13_2()`

- `Void <_OnJumpToMissionState>b__16_0(String)`

- `Void <_OnJumpToMissionState>b__16_1(String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapState : State
{
	private CampaignZoneMapStateBean _stateBean; // 0x50
	private CampaignZoneMapContainer _container; // 0x58
	private PrefabInstHolder _campFeeHolder; // 0x60
	private TopMenuDynamicPrefabInstHolder _topmenuHolder; // 0x68
	private AnimationWrapper _animationWrapper; // 0x70
	private UnityEvent _openCampaign; // 0x78
	private CampaignStagePreviewConfigController _previewConfigCtrl; // 0x80
	private CampaignFeeView m_campFeeView; // 0x88
	private Boolean m_cacheIsToBreakingDetail; // 0x90
	private String m_cacheJumpStageId; // 0x98
	private CampaignStageMapViewModel m_targetModelToRuleState; // 0xa0
	private Boolean m_mapLoadedCache; // 0xa8
	private Boolean m_switchZoneLock; // 0xa9
	private const Single SWITCH_ZONE_TIME_OUT; // 0x0
	private FastCampStateParam m_toFastCamp; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToMissionState; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToCampaignRuleView; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x38
	private static DelegateBridge __Hotfix0__OnInitCampFee; // 0x40
	private static DelegateBridge __Hotfix0__OnHandleJump; // 0x48
	private static DelegateBridge __Hotfix0_ToJumpState; // 0x50
	private static DelegateBridge __Hotfix0_OnOpenRewardClick; // 0x58
	private static DelegateBridge __Hotfix0_OnOpenRuleClick; // 0x60
	private static DelegateBridge __Hotfix0_OnOpenEnemyClick; // 0x68
	private static DelegateBridge __Hotfix0_OnClickStageId; // 0x70
	private static DelegateBridge __Hotfix0_OnStartBattleClick; // 0x78
	private static DelegateBridge __Hotfix0_ClosePreviewState; // 0x80
	private static DelegateBridge __Hotfix0_EventOnCampaignBreakRewardConfirmed; // 0x88
	private static DelegateBridge __Hotfix0__OnCleanSelectStage; // 0x90
	private static DelegateBridge __Hotfix0__OnSelectStage; // 0x98
	private static DelegateBridge __Hotfix0__CheckCostBeforeStartBattle; // 0xa0
	private static DelegateBridge __Hotfix0__CheckApBeforeStartBattle; // 0xa8
	private static DelegateBridge __Hotfix0__SaveCacheStageConfig; // 0xb0
	private static DelegateBridge __Hotfix0__GoToSquad; // 0xb8
	private static DelegateBridge __Hotfix0__CheckNeedToLoadBattleLog; // 0xc0
	private static DelegateBridge __Hotfix0__OnGoToSquad; // 0xc8
	private static DelegateBridge __Hotfix0__EventOnCampFeeClicked; // 0xd0
	private static DelegateBridge __Hotfix0__LockSwitchZone; // 0xd8
	private static DelegateBridge __Hotfix0__UnlockSwitchZone; // 0xe0
	private static DelegateBridge __Hotfix0__OnSwitchSelectStateEnd; // 0xe8
	private static DelegateBridge __Hotfix0__SwitchSelectStateCoroutine; // 0xf0
	private static DelegateBridge __Hotfix0__GenerateAutoSwitchOptions; // 0xf8
	private static DelegateBridge __Hotfix0__OnAutoBattleClicked; // 0x100
	private static DelegateBridge __Hotfix0__OnFastBattleClicked; // 0x108
	private static DelegateBridge __Hotfix0__OnTryTriggerFastCampTutorial; // 0x110
	private static DelegateBridge __Hotfix0__OnFastCampInfoClicked; // 0x118
	private static DelegateBridge __Hotfix0__OnJumpToFastCampState; // 0x120
	private static DelegateBridge __Hotfix0__GoToFastBattle; // 0x128
	private static DelegateBridge _c__Hotfix0_ctor; // 0x130


	// RVA: 0x2e4de40 VA: 0x7595465e40
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e4dea8 VA: 0x7595465ea8
	protected override Void OnEnter() { }
	// RVA: 0x2e4e680 VA: 0x7595466680
	protected override Void OnResume() { }
	// RVA: 0x2e4eb94 VA: 0x7595466b94
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2e4eed8 VA: 0x7595466ed8
	private Void _OnJumpToMissionState(IStateBean bean) { }
	// RVA: 0x2e4f088 VA: 0x7595467088
	private Void _OnJumpToCampaignRuleView(IStateBean stateBean) { }
	// RVA: 0x2e4f1b4 VA: 0x75954671b4
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2e4f32c VA: 0x759546732c
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x2e4f438 VA: 0x7595467438
	private Void _OnInitCampFee(GameObject campFeeObj) { }
	// RVA: 0x2e4f6a8 VA: 0x75954676a8
	private Void _OnHandleJump(String stageId) { }
	// RVA: 0x2e4f764 VA: 0x7595467764
	public Void ToJumpState() { }
	// RVA: 0x2e4f870 VA: 0x7595467870
	public Void OnOpenRewardClick() { }
	// RVA: 0x2e4f988 VA: 0x7595467988
	public Void OnOpenRuleClick() { }
	// RVA: 0x2e4faec VA: 0x7595467aec
	public Void OnOpenEnemyClick() { }
	// RVA: 0x2e4fc88 VA: 0x7595467c88
	public Void OnClickStageId(String stageId) { }
	// RVA: 0x2e4fd08 VA: 0x7595467d08
	public Void OnStartBattleClick() { }
	// RVA: 0x2e507a0 VA: 0x75954687a0
	public Void ClosePreviewState() { }
	// RVA: 0x2e50898 VA: 0x7595468898
	public Void EventOnCampaignBreakRewardConfirmed(String stageId, Int32 index) { }
	// RVA: 0x2e4e9e8 VA: 0x75954669e8
	private Void _OnCleanSelectStage() { }
	// RVA: 0x2e4e3f4 VA: 0x75954663f4
	private Void _OnSelectStage(String stageId) { }
	// RVA: 0x2e4fdc0 VA: 0x7595467dc0
	private Boolean _CheckCostBeforeStartBattle() { }
	// RVA: 0x2e50de8 VA: 0x7595468de8
	private Boolean _CheckApBeforeStartBattle(Int32 apCost) { }
	// RVA: 0x2e4ff10 VA: 0x7595467f10
	private Void _SaveCacheStageConfig() { }
	// RVA: 0x2e50330 VA: 0x7595468330
	private Void _GoToSquad() { }
	// RVA: 0x2e50f6c VA: 0x7595468f6c
	private Boolean _CheckNeedToLoadBattleLog(out Boolean allowNoBattleLog) { }
	// RVA: 0x2e5105c VA: 0x759546905c
	private Void _OnGoToSquad(String stageId) { }
	// RVA: 0x2e512b0 VA: 0x75954692b0
	private Void _EventOnCampFeeClicked() { }
	// RVA: 0x2e51408 VA: 0x7595469408
	private Boolean _LockSwitchZone() { }
	// RVA: 0x2e51484 VA: 0x7595469484
	private Void _UnlockSwitchZone() { }
	// RVA: 0x2e514ec VA: 0x75954694ec
	private Void _OnSwitchSelectStateEnd() { }
	// RVA: 0x2e4ea90 VA: 0x7595466a90
	private IEnumerator _SwitchSelectStateCoroutine(CampaignZoneMapViewModel zoneViewModel, CampaignStageMapViewModel stageViewModel, Boolean jumpToCampaign) { }
	// RVA: 0x2e4e4f4 VA: 0x75954664f4
	private CampAutoSwitchOptions _GenerateAutoSwitchOptions() { }
	// RVA: 0x2e51578 VA: 0x7595469578
	private Void _OnAutoBattleClicked() { }
	// RVA: 0x2e5168c VA: 0x759546968c
	private Void _OnFastBattleClicked() { }
	// RVA: 0x2e517b0 VA: 0x75954697b0
	private Void _OnTryTriggerFastCampTutorial() { }
	// RVA: 0x2e51924 VA: 0x7595469924
	private Void _OnFastCampInfoClicked() { }
	// RVA: 0x2e51a1c VA: 0x7595469a1c
	private Void _OnJumpToFastCampState(IStateBean rawBean) { }
	// RVA: 0x2e501c4 VA: 0x75954681c4
	private Void _GoToFastBattle() { }
	// RVA: 0x2e51b00 VA: 0x7595469b00
	public Void .ctor() { }
	// RVA: 0x2e51b70 VA: 0x7595469b70
	private Void <OnEnter>b__13_0(GameObject gameObj) { }
	// RVA: 0x2e51c6c VA: 0x7595469c6c
	private Void <OnEnter>b__13_2() { }
	// RVA: 0x2e51c70 VA: 0x7595469c70
	private Void <_OnJumpToMissionState>b__16_0(String stageId) { }
	// RVA: 0x2e51d3c VA: 0x7595469d3c
	private Void <_OnJumpToMissionState>b__16_1(String stageId) { }
	// RVA: 0x2e51e04 VA: 0x7595469e04
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e51e0c VA: 0x7595469e0c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2e51e14 VA: 0x7595469e14
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```