# StagePage

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageStateBean _stateBean`

- `UICommonPageEffectHolder _zoneSelectEffect`

- `StageZoneTabGroup _tabGroup`

- `StageActivityDataBinder _activityDataBinder`

- `SideStoryMapDecroDataBinder _sideStoryBinder`

- `StageZoneStoryOnlyPanel _storyOnlyPanel`

- `CanvasGroup _blackLoadingOnZoneSelect`

- `RectTransform _dialogContainer`

- `GameObject _globalEventMask`

- `StageZoneSpecialStoryOnlyPanel _specialStoryOnlyPanel`

- `DataBundle m_dataBundle4InitStateEngine`

- `ActivityInitMeta m_stageActInitMeta`

- `ReentrantFloatRef m_globalBlackMask`

- `StageZoneSelectBlackLoadingManager m_blackLoadingOnZoneSelect`

- `UICompDialogMgr m_dmgr`

- `StagePageGameMusicController m_gameMusicController`

- `Boolean m_requestingCrisisData`

- `CrisisV2DataFromServer m_crisisData`


## Properties

- `StageStateBean stageStateBean`

- `UICompDialogMgr dialogMgr`

- `StagePageGameMusicController musicController`

- `StageZoneSelectBlackLoadingManager blackLoadingOnZoneSelect`


## Methods

- `StageStateBean get_stageStateBean()`

- `UICompDialogMgr get_dialogMgr()`

- `StagePageGameMusicController get_musicController()`

- `Void _FetchCrisisV2DataIfNecessary()`

- `UICompDialogMgr GetDialogMgr()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnMissionArchiveClicked(MissionArchiveBtnEventParam)`

- `Void _EventOnFifthAnnivExploreClicked()`

- `Void _EventOnUpdateGlobalMask(Boolean)`

- `Boolean SwitchToZone(String)`

- `Void OpenRetroCoinDetail()`

- `Void OpenTrailDetail()`

- `Void OpenSsTrail(String)`

- `Void OpenCollectTrail(String)`

- `Void OpenStoryReview(String, Boolean)`

- `Void OpenMixStoryOverall()`

- `Void TryTriggerZoneHomeGuide()`

- `ActivityMetaWrapper ConsumeActivityInitMeta(String)`

- `Void NotifyActivityLoadReady(String)`

- `Void TryBackToZoneSelectState()`

- `StageZoneSelectBlackLoadingManager get_blackLoadingOnZoneSelect()`

- `Void ResetToStage(String)`

- `IEnumerator ResetToDefault()`

- `Void EventOnStageButtonClick(String)`

- `Void EventOnMapLoadError(String)`

- `Void EventOnMapLoaded(String)`

- `Void EventOnCampaignBreakRewardConfirmed(String, Int32)`

- `Void EventOnFogClicked(String)`

- `String _GetFogUnlockDesc(StageFogInfo, StageData)`

- `Void EventOnSpecialStageRewardClicked(String)`

- `Void EventOnZoneRecordClicked(String)`

- `CrisisV2ServerDataWrapper _GetValidCrisisData()`

- `Void _OnCrisisDataFetched()`

- `Void _RefreshPermModeModel()`

- `Void _OnSendUnlockStageFog(String)`

- `Void _OnZoneTabClicked(ZoneViewType)`

- `Void _OnSendGetSpecialStageReward(String)`

- `Void _RefreshMutableStages()`

- `Void _RefreshSixStarStages()`

- `Void _OpenSixStarMileStoneDialog(String)`

- `Void _OnStoryStageClicked(String, StageData, DisplayInfo)`

- `Void _OnSpecialStoryStageClicked(String, StageData, DisplayInfo)`

- `Void _OnBattleStageClicked(String, StageData)`

- `IEnumerator _ShowInitToastsAndAlerts()`

- `Void _TriggerHiddenStageToast()`

- `Void _TriggerZoneHomeGuide()`

- `Void _OnZoneHomeGuideFinish(Story)`

- `Void _TryTriggerMixStoryIntro()`

- `Void _InitTopMenu()`

- `Void _TopMenuProcessor(GameObject)`

- `Void _EventOnStateBackBtnClicked()`

- `IEnumerator _ResetToZoneSelectState()`

- `IEnumerator _ResetToStageEntry(StageViewModel)`

- `IEnumerator _ResetToStage(String)`

- `Void _ClearCacheBeforeReset()`

- `IEnumerator _WrapWithBlackLoading(IEnumerator[])`

- `IEnumerator _SetStateViaParam(DataBundle)`

- `IEnumerator _JumpToZoneSelect(String)`

- `IEnumerator _JumpToZoneSelectByViewType(ZoneViewType, String, Boolean)`

- `IEnumerator _JumpToActivity(String)`

- `IEnumerator _JumpToZone(String)`

- `IEnumerator _JumpToStage(String)`

- `IEnumerator _JumpToStageRemain(StageId, StageData)`

- `Boolean _CheckZoneRequireRetroState(String)`

- `Void _RedirectActInitMetaToStage(String, String)`

- `Void _JumpToCampaign()`

- `Void _OnBackToStagePage(UIPageTransContext)`

- `IEnumerator _WaitForActivityReadyCoroutine(String)`

- `Void _ConsumeExpiredTrackPoint()`

- `Void _TryToTrackSixStarFirstPass(DataBundle)`

- `Sprite LoadStartBattleCostIcon(String)`

- `Sprite LoadStartBattleButtonImage(String)`

- `Sprite LoadStartBattleCostBkg(String)`

- `Sprite _LoadSpriteFromStartBattleStyle(String, Func`2, Func`2)`

- `Void Update()`

- `IEnumerator <>n__0(UIPageStackParam)`

- `IEnumerator <>n__1()`

- `IEnumerator <>n__2(Boolean)`

- `IEnumerator <>n__3(Boolean)`

- `Void <_OnSendUnlockStageFog>b__114_0(UnlockStageFogResponse)`

- `Void <_OnSendGetSpecialStageReward>b__116_0(SpecialStoryStageRewardResponse)`

- `Void <_TopMenuProcessor>b__129_0(UIRouteTarget, Object, Action`2)`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Void <>xLuaBaseProxy_OnReuse(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_OnPageReservedDuringReset(UIPageStackParam)`

- `Void <>xLuaBaseProxy_OnPageRouted()`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Void <>xLuaBaseProxy_DisplayWholePage(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePage : StateEnginePage, IValueMsgReceiver, IDialogMgrHolder, IHotfixable
{
	private const Single INIT_TOAST_DELAY; // 0x0
	private const Single CONST_INIT_DURATION; // 0x0
	public const Int32 ZONE_RECORD_BTN_EVENT; // 0x0
	public const Int32 MISSION_ARCHIVE_BTN_EVENT; // 0x0
	public const Int32 FIFTH_ANNIV_EXPLORE_BTN_EVENT; // 0x0
	public const Int32 ON_STATE_BACK_BTN_CLICKED; // 0x0
	public const Int32 UPDATE_GLOBAL_MASK_EVENT; // 0x0
	public const Int32 UPDATE_SIX_STAR_PREVIEW_INFO; // 0x0
	public const Int32 OPEN_SIX_STAR_MILESTONE_DIALOG; // 0x0
	private PrefabInstHolder[] _topMenuHolders; // 0xe8
	private StageStateBean _stateBean; // 0xf0
	private UICommonPageEffectHolder _zoneSelectEffect; // 0xf8
	private StageZoneTabGroup _tabGroup; // 0x100
	private StageActivityDataBinder _activityDataBinder; // 0x108
	private SideStoryMapDecroDataBinder _sideStoryBinder; // 0x110
	private StageZoneStoryOnlyPanel _storyOnlyPanel; // 0x118
	private CanvasGroup _blackLoadingOnZoneSelect; // 0x120
	private RectTransform _dialogContainer; // 0x128
	private GameObject _globalEventMask; // 0x130
	private StageZoneSpecialStoryOnlyPanel _specialStoryOnlyPanel; // 0x138
	private DataBundle m_dataBundle4InitStateEngine; // 0x140
	private List`1 m_initToasts; // 0x148
	private List`1 m_initRewards; // 0x150
	private ActivityInitMeta m_stageActInitMeta; // 0x158
	private YieldSemaphore`1 m_stageActSemaphore; // 0x160
	private ReentrantFloatRef m_globalBlackMask; // 0x168
	private StageZoneSelectBlackLoadingManager m_blackLoadingOnZoneSelect; // 0x170
	private UICompDialogMgr m_dmgr; // 0x178
	private StagePageGameMusicController m_gameMusicController; // 0x180
	private Boolean m_requestingCrisisData; // 0x188
	private CrisisV2DataFromServer m_crisisData; // 0x190
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x0
	private static DelegateBridge __Hotfix0_get_stageStateBean; // 0x8
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x10
	private static DelegateBridge __Hotfix0_get_musicController; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x28
	private static DelegateBridge __Hotfix0_OnReuse; // 0x30
	private static DelegateBridge __Hotfix0_OnPageReservedDuringReset; // 0x38
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x40
	private static DelegateBridge __Hotfix0_OnStart; // 0x48
	private static DelegateBridge __Hotfix0__FetchCrisisV2DataIfNecessary; // 0x50
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x58
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x60
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x68
	private static DelegateBridge __Hotfix0_DisplayWholePage; // 0x70
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x78
	private static DelegateBridge __Hotfix0_GetDialogMgr; // 0x80
	private static DelegateBridge __Hotfix0_OnMessage; // 0x88
	private static DelegateBridge __Hotfix0__EventOnMissionArchiveClicked; // 0x90
	private static DelegateBridge __Hotfix0__EventOnFifthAnnivExploreClicked; // 0x98
	private static DelegateBridge __Hotfix0__EventOnUpdateGlobalMask; // 0xa0
	private static DelegateBridge __Hotfix0_DataBundleToActivity; // 0xa8
	private static DelegateBridge __Hotfix0_DataBundleToStage; // 0xb0
	private static DelegateBridge __Hotfix1_DataBundleToStage; // 0xb8
	private static DelegateBridge __Hotfix0_TryGetStageDataFromSavedInst; // 0xc0
	private static DelegateBridge __Hotfix0_DataBundleToZoneOnZoneSelect; // 0xc8
	private static DelegateBridge __Hotfix1_DataBundleToZoneOnZoneSelect; // 0xd0
	private static DelegateBridge __Hotfix0_DataBundleToZoneViewTab; // 0xd8
	private static DelegateBridge __Hotfix0_DataBundleToMixStory; // 0xe0
	private static DelegateBridge __Hotfix0_DataBundleToMixStoryRetro; // 0xe8
	private static DelegateBridge __Hotfix0_SetAlertInfos2Bundle; // 0xf0
	private static DelegateBridge __Hotfix0__SetCharTmplUnlock2Bundle; // 0xf8
	private static DelegateBridge __Hotfix0__SetSystemUnlock2Bundle; // 0x100
	private static DelegateBridge __Hotfix0__SetMixStoryOverallUnlock2Bunlde; // 0x108
	private static DelegateBridge __Hotfix0__SetPermModeSystemUnlock2Bundle; // 0x110
	private static DelegateBridge __Hotfix0__SetCrisisV2SystemUnlock2Bundle; // 0x118
	private static DelegateBridge __Hotfix0__CheckSystemUnlock; // 0x120
	private static DelegateBridge __Hotfix0__SetHardStageUnlock2Bundle; // 0x128
	private static DelegateBridge __Hotfix0__SetSixStarAdvanceUnlock2Bundle; // 0x130
	private static DelegateBridge __Hotfix0__SetZoneUnlock2Bundle; // 0x138
	private static DelegateBridge __Hotfix0__SetMainlineStageUnlock2Bundle; // 0x140
	private static DelegateBridge __Hotfix0__AddAlertInfo2Bundle; // 0x148
	private static DelegateBridge __Hotfix1__AddAlertInfo2Bundle; // 0x150
	private static DelegateBridge __Hotfix0__SetAlertInfo2Bundle; // 0x158
	private static DelegateBridge __Hotfix0_SetStoryRewardInfo2Bundle; // 0x160
	private static DelegateBridge __Hotfix0_SetStageActivityMeta2Bundle; // 0x168
	private static DelegateBridge __Hotfix0_SetStageJustPlayed2Bundle; // 0x170
	private static DelegateBridge __Hotfix0_SetStageJustPassed2Bundle; // 0x178
	private static DelegateBridge __Hotfix0_SceneParamToStage; // 0x180
	private static DelegateBridge __Hotfix0_SendUnlockStageFog; // 0x188
	private static DelegateBridge __Hotfix0_SendGetSpecialStageReward; // 0x190
	private static DelegateBridge __Hotfix0_SwitchToZone; // 0x198
	private static DelegateBridge __Hotfix0_OpenRetroCoinDetail; // 0x1a0
	private static DelegateBridge __Hotfix0_OpenTrailDetail; // 0x1a8
	private static DelegateBridge __Hotfix0_OpenSsTrail; // 0x1b0
	private static DelegateBridge __Hotfix0_OpenCollectTrail; // 0x1b8
	private static DelegateBridge __Hotfix0_OpenStoryReview; // 0x1c0
	private static DelegateBridge __Hotfix0_OpenMixStoryOverall; // 0x1c8
	private static DelegateBridge __Hotfix0_TryTriggerZoneHomeGuide; // 0x1d0
	private static DelegateBridge __Hotfix0_ConsumeActivityInitMeta; // 0x1d8
	private static DelegateBridge __Hotfix0_NotifyActivityLoadReady; // 0x1e0
	private static DelegateBridge __Hotfix0_TryBackToZoneSelectState; // 0x1e8
	private static DelegateBridge __Hotfix0_get_blackLoadingOnZoneSelect; // 0x1f0
	private static DelegateBridge __Hotfix0_ResetToStage; // 0x1f8
	private static DelegateBridge __Hotfix0_ResetToDefault; // 0x200
	private static DelegateBridge __Hotfix0_EventOnStageButtonClick; // 0x208
	private static DelegateBridge __Hotfix0_EventOnMapLoadError; // 0x210
	private static DelegateBridge __Hotfix0_EventOnMapLoaded; // 0x218
	private static DelegateBridge __Hotfix0_EventOnCampaignBreakRewardConfirmed; // 0x220
	private static DelegateBridge __Hotfix0_EventOnFogClicked; // 0x228
	private static DelegateBridge __Hotfix0__GetFogUnlockDesc; // 0x230
	private static DelegateBridge __Hotfix0_EventOnSpecialStageRewardClicked; // 0x238
	private static DelegateBridge __Hotfix0_EventOnZoneRecordClicked; // 0x240
	private static DelegateBridge __Hotfix0__GetValidCrisisData; // 0x248
	private static DelegateBridge __Hotfix0__OnCrisisDataFetched; // 0x250
	private static DelegateBridge __Hotfix0__RefreshPermModeModel; // 0x258
	private static DelegateBridge __Hotfix0__OnSendUnlockStageFog; // 0x260
	private static DelegateBridge __Hotfix0__OnZoneTabClicked; // 0x268
	private static DelegateBridge __Hotfix0__OnSendGetSpecialStageReward; // 0x270
	private static DelegateBridge __Hotfix0__RefreshMutableStages; // 0x278
	private static DelegateBridge __Hotfix0__RefreshSixStarStages; // 0x280
	private static DelegateBridge __Hotfix0__OpenSixStarMileStoneDialog; // 0x288
	private static DelegateBridge __Hotfix0__OnStoryStageClicked; // 0x290
	private static DelegateBridge __Hotfix0__OnSpecialStoryStageClicked; // 0x298
	private static DelegateBridge __Hotfix0__OnBattleStageClicked; // 0x2a0
	private static DelegateBridge __Hotfix0__ShowInitToastsAndAlerts; // 0x2a8
	private static DelegateBridge __Hotfix0__TriggerHiddenStageToast; // 0x2b0
	private static DelegateBridge __Hotfix0__TriggerZoneHomeGuide; // 0x2b8
	private static DelegateBridge __Hotfix0__OnZoneHomeGuideFinish; // 0x2c0
	private static DelegateBridge __Hotfix0__TryTriggerMixStoryIntro; // 0x2c8
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x2d0
	private static DelegateBridge __Hotfix0__TopMenuProcessor; // 0x2d8
	private static DelegateBridge __Hotfix0__EventOnStateBackBtnClicked; // 0x2e0
	private static DelegateBridge __Hotfix0__ResetToZoneSelectState; // 0x2e8
	private static DelegateBridge __Hotfix0__ResetToStageEntry; // 0x2f0
	private static DelegateBridge __Hotfix0__ResetToStage; // 0x2f8
	private static DelegateBridge __Hotfix0__ClearCacheBeforeReset; // 0x300
	private static DelegateBridge __Hotfix0__WrapWithBlackLoading; // 0x308
	private static DelegateBridge __Hotfix0__SetStateViaParam; // 0x310
	private static DelegateBridge __Hotfix0__JumpToZoneSelect; // 0x318
	private static DelegateBridge __Hotfix0__JumpToZoneSelectByViewType; // 0x320
	private static DelegateBridge __Hotfix0__JumpToActivity; // 0x328
	private static DelegateBridge __Hotfix0__JumpToZone; // 0x330
	private static DelegateBridge __Hotfix0__JumpToStage; // 0x338
	private static DelegateBridge __Hotfix0__JumpToStageRemain; // 0x340
	private static DelegateBridge __Hotfix0__DefaultStackListToZone; // 0x348
	private static DelegateBridge __Hotfix0__DefaultStackListToStage; // 0x350
	private static DelegateBridge __Hotfix0__CheckZoneRequireRetroState; // 0x358
	private static DelegateBridge __Hotfix0__ExtractInitRewards; // 0x360
	private static DelegateBridge __Hotfix0__GenActInitDataWraper; // 0x368
	private static DelegateBridge __Hotfix0__RedirectActInitMetaToStage; // 0x370
	private static DelegateBridge __Hotfix0__JumpToCampaign; // 0x378
	private static DelegateBridge __Hotfix0__OnBackToStagePage; // 0x380
	private static DelegateBridge __Hotfix0__WaitForActivityReadyCoroutine; // 0x388
	private static DelegateBridge __Hotfix0__ConsumeExpiredTrackPoint; // 0x390
	private static DelegateBridge __Hotfix0__TryToTrackSixStarFirstPass; // 0x398
	private static DelegateBridge __Hotfix0_LoadStartBattleCostIcon; // 0x3a0
	private static DelegateBridge __Hotfix0_LoadStartBattleButtonImage; // 0x3a8
	private static DelegateBridge __Hotfix0_LoadStartBattleCostBkg; // 0x3b0
	private static DelegateBridge __Hotfix0__LoadSpriteFromStartBattleStyle; // 0x3b8
	private static DelegateBridge __Hotfix0_Update; // 0x3c0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x3c8

	public override AVGPageKey avgPage { get; }
	public StageStateBean stageStateBean { get; }
	public UICompDialogMgr dialogMgr { get; }
	public StagePageGameMusicController musicController { get; }
	public StageZoneSelectBlackLoadingManager blackLoadingOnZoneSelect { get; }

	// RVA: 0x2f5294c VA: 0x759556a94c
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x2f529b4 VA: 0x759556a9b4
	public StageStateBean get_stageStateBean() { }
	// RVA: 0x2f52a1c VA: 0x759556aa1c
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2f52a84 VA: 0x759556aa84
	public StagePageGameMusicController get_musicController() { }
	// RVA: 0x2f52aec VA: 0x759556aaec
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2f53064 VA: 0x759556b064
	protected override Void OnRecycle() { }
	// RVA: 0x2f530e4 VA: 0x759556b0e4
	protected override Void OnReuse(DataBundle savedInst) { }
	// RVA: 0x2f53178 VA: 0x759556b178
	protected override IEnumerator OnPageReservedDuringReset(UIPageStackParam param) { }
	// RVA: 0x2f53294 VA: 0x759556b294
	protected override Void OnPageRouted() { }
	// RVA: 0x2f533ac VA: 0x759556b3ac
	protected override Void OnStart() { }
	// RVA: 0x2f538f4 VA: 0x759556b8f4
	private Void _FetchCrisisV2DataIfNecessary() { }
	// RVA: 0x2f53a70 VA: 0x759556ba70
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2f53b44 VA: 0x759556bb44
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2f53c34 VA: 0x759556bc34
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2f53d24 VA: 0x759556bd24
	public override Void DisplayWholePage(Boolean isShow) { }
	// RVA: 0x2f53de0 VA: 0x759556bde0
	protected override Void OnDestroy() { }
	// RVA: 0x2f53e70 VA: 0x759556be70
	public UICompDialogMgr GetDialogMgr() { }
	// RVA: 0x2f53ed8 VA: 0x759556bed8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f541d0 VA: 0x759556c1d0
	private Void _EventOnMissionArchiveClicked(MissionArchiveBtnEventParam param) { }
	// RVA: 0x2f54268 VA: 0x759556c268
	private Void _EventOnFifthAnnivExploreClicked() { }
	// RVA: 0x2f544e0 VA: 0x759556c4e0
	private Void _EventOnUpdateGlobalMask(Boolean active) { }
	// RVA: 0x2f54778 VA: 0x759556c778
	public static DataBundle DataBundleToActivity(String activityId) { }
	// RVA: 0x2f5486c VA: 0x759556c86c
	public static DataBundle DataBundleToStage(String zoneId, String stageId) { }
	// RVA: 0x2f54928 VA: 0x759556c928
	public static Void DataBundleToStage(DataBundle bundle, String zoneId, String stageId) { }
	// RVA: 0x2f54a24 VA: 0x759556ca24
	public static Boolean TryGetStageDataFromSavedInst(DataBundle savedInst, out StageDataWrapper stageData) { }
	// RVA: 0x2f54b60 VA: 0x759556cb60
	public static DataBundle DataBundleToZoneOnZoneSelect(String zoneId) { }
	// RVA: 0x2f54c04 VA: 0x759556cc04
	public static Void DataBundleToZoneOnZoneSelect(DataBundle bundle, String zoneId) { }
	// RVA: 0x2f54cd0 VA: 0x759556ccd0
	public static DataBundle DataBundleToZoneViewTab(ZoneViewType zoneViewType) { }
	// RVA: 0x2f54dc4 VA: 0x759556cdc4
	public static DataBundle DataBundleToMixStory(Boolean focusLastUnlockedMainline) { }
	// RVA: 0x2f54ee0 VA: 0x759556cee0
	public static DataBundle DataBundleToMixStoryRetro(String retroRelevantActId) { }
	// RVA: 0x2f54ffc VA: 0x759556cffc
	public static Void SetAlertInfos2Bundle(String lastStageId, Boolean isFirstPassStage, String curZoneId, IList`1 unlockStageIds, IAlertResponse response, DataBundle stageBundle) { }
	// RVA: 0x2f557a0 VA: 0x759556d7a0
	private static Void _SetCharTmplUnlock2Bundle(List`1 msgList, DataBundle bundle) { }
	// RVA: 0x2f55128 VA: 0x759556d128
	private static Void _SetSystemUnlock2Bundle(String lastPassStageId, DataBundle bundle) { }
	// RVA: 0x2f55d68 VA: 0x759556dd68
	private static Void _SetMixStoryOverallUnlock2Bunlde(String lastPassStageId, DataBundle bundle) { }
	// RVA: 0x2f55e34 VA: 0x759556de34
	private static Void _SetPermModeSystemUnlock2Bundle(String lastPassStageId, DataBundle bundle) { }
	// RVA: 0x2f55f00 VA: 0x759556df00
	private static Void _SetCrisisV2SystemUnlock2Bundle(String lastPassStageId, DataBundle bundle) { }
	// RVA: 0x2f56030 VA: 0x759556e030
	private static Boolean _CheckSystemUnlock(String lastPassStageId, UILockTarget target) { }
	// RVA: 0x2f55484 VA: 0x759556d484
	private static Void _SetHardStageUnlock2Bundle(String lastStageId, IList`1 unlockStageIds, DataBundle bundle) { }
	// RVA: 0x2f556ac VA: 0x759556d6ac
	private static Void _SetSixStarAdvanceUnlock2Bundle(String lastStageId, Boolean isFirstPassStage, DataBundle bundle) { }
	// RVA: 0x2f551c0 VA: 0x759556d1c0
	private static Void _SetZoneUnlock2Bundle(String curZoneId, IList`1 unlockStageIds, DataBundle bundle) { }
	// RVA: 0x2f560e4 VA: 0x759556e0e4
	private static Void _SetMainlineStageUnlock2Bundle(List`1 stages, DataBundle bundle) { }
	// RVA: 0x2f55be0 VA: 0x759556dbe0
	private static Void _AddAlertInfo2Bundle(DataBundle bundle, String alert) { }
	// RVA: 0x2f562e4 VA: 0x759556e2e4
	private static Void _AddAlertInfo2Bundle(DataBundle bundle, List`1 alerts) { }
	// RVA: 0x2f55990 VA: 0x759556d990
	private static Void _SetAlertInfo2Bundle(IAlertResponse response, DataBundle bundle) { }
	// RVA: 0x2f563fc VA: 0x759556e3fc
	public static Void SetStoryRewardInfo2Bundle(StoryOnlyStartBattleResponse response, DataBundle bundle) { }
	// RVA: 0x2f565f8 VA: 0x759556e5f8
	public static Void SetStageActivityMeta2Bundle(String actId, String metaInfo, DataBundle outBundle) { }
	// RVA: 0x2f56710 VA: 0x759556e710
	public static Void SetStageJustPlayed2Bundle(String stageId, DataBundle outBundle) { }
	// RVA: 0x2f567c0 VA: 0x759556e7c0
	public static Void SetStageJustPassed2Bundle(String stageId, DataBundle outBundle) { }
	// RVA: 0x2f56870 VA: 0x759556e870
	public static UIPageControllerParam SceneParamToStage(DataBundle bundleToStage) { }
	// RVA: 0x2f56c30 VA: 0x759556ec30
	public static Void SendUnlockStageFog(String stageId, Action`1 handler) { }
	// RVA: 0x2f56e58 VA: 0x759556ee58
	public static Void SendGetSpecialStageReward(String stageId, Action`1 handler) { }
	// RVA: 0x2f57084 VA: 0x759556f084
	public Boolean SwitchToZone(String zoneId) { }
	// RVA: 0x2f57294 VA: 0x759556f294
	public Void OpenRetroCoinDetail() { }
	// RVA: 0x2f57354 VA: 0x759556f354
	public Void OpenTrailDetail() { }
	// RVA: 0x2f5766c VA: 0x759556f66c
	public Void OpenSsTrail(String retroId) { }
	// RVA: 0x2f57880 VA: 0x759556f880
	public Void OpenCollectTrail(String actId) { }
	// RVA: 0x2f5797c VA: 0x759556f97c
	public Void OpenStoryReview(String actId, Boolean isSs) { }
	// RVA: 0x2f57a88 VA: 0x759556fa88
	public Void OpenMixStoryOverall() { }
	// RVA: 0x2f53344 VA: 0x759556b344
	public Void TryTriggerZoneHomeGuide() { }
	// RVA: 0x2f57d9c VA: 0x759556fd9c
	public ActivityMetaWrapper ConsumeActivityInitMeta(String actId) { }
	// RVA: 0x2f57f54 VA: 0x759556ff54
	public Void NotifyActivityLoadReady(String activityId) { }
	// RVA: 0x2f57ff4 VA: 0x759556fff4
	public Void TryBackToZoneSelectState() { }
	// RVA: 0x2f580ec VA: 0x75955700ec
	public StageZoneSelectBlackLoadingManager get_blackLoadingOnZoneSelect() { }
	// RVA: 0x2f58154 VA: 0x7595570154
	public Void ResetToStage(String stageId) { }
	// RVA: 0x2f58378 VA: 0x7595570378
	public IEnumerator ResetToDefault() { }
	// RVA: 0x2f58424 VA: 0x7595570424
	public Void EventOnStageButtonClick(String stageId) { }
	// RVA: 0x2f58cf0 VA: 0x7595570cf0
	public Void EventOnMapLoadError(String zoneId) { }
	// RVA: 0x2f58f50 VA: 0x7595570f50
	public Void EventOnMapLoaded(String zoneId) { }
	// RVA: 0x2f59104 VA: 0x7595571104
	public Void EventOnCampaignBreakRewardConfirmed(String stageId, Int32 index) { }
	// RVA: 0x2f59550 VA: 0x7595571550
	public Void EventOnFogClicked(String stageId) { }
	// RVA: 0x2f598c4 VA: 0x75955718c4
	private String _GetFogUnlockDesc(StageFogInfo fogInfo, StageData stageData) { }
	// RVA: 0x2f5999c VA: 0x759557199c
	public Void EventOnSpecialStageRewardClicked(String stageId) { }
	// RVA: 0x2f540c4 VA: 0x759556c0c4
	public Void EventOnZoneRecordClicked(String zoneId) { }
	// RVA: 0x2f539b0 VA: 0x759556b9b0
	private CrisisV2ServerDataWrapper _GetValidCrisisData() { }
	// RVA: 0x2f59b08 VA: 0x7595571b08
	private Void _OnCrisisDataFetched() { }
	// RVA: 0x2f59bd0 VA: 0x7595571bd0
	private Void _RefreshPermModeModel() { }
	// RVA: 0x2f59c48 VA: 0x7595571c48
	private Void _OnSendUnlockStageFog(String stageId) { }
	// RVA: 0x2f59d14 VA: 0x7595571d14
	private Void _OnZoneTabClicked(ZoneViewType zoneViewType) { }
	// RVA: 0x2f59a3c VA: 0x7595571a3c
	private Void _OnSendGetSpecialStageReward(String stageId) { }
	// RVA: 0x2f59eec VA: 0x7595571eec
	private Void _RefreshMutableStages() { }
	// RVA: 0x2f54564 VA: 0x759556c564
	private Void _RefreshSixStarStages() { }
	// RVA: 0x2f54604 VA: 0x759556c604
	private Void _OpenSixStarMileStoneDialog(String groupId) { }
	// RVA: 0x2f58670 VA: 0x7595570670
	private Void _OnStoryStageClicked(String stageId, StageData stageData, DisplayInfo spstInfo) { }
	// RVA: 0x2f5886c VA: 0x759557086c
	private Void _OnSpecialStoryStageClicked(String stageId, StageData stageData, DisplayInfo spstInfo) { }
	// RVA: 0x2f58b08 VA: 0x7595570b08
	private Void _OnBattleStageClicked(String stageId, StageData stageData) { }
	// RVA: 0x2f59f8c VA: 0x7595571f8c
	private IEnumerator _ShowInitToastsAndAlerts() { }
	// RVA: 0x2f5a038 VA: 0x7595572038
	private Void _TriggerHiddenStageToast() { }
	// RVA: 0x2f57bb8 VA: 0x759556fbb8
	private Void _TriggerZoneHomeGuide() { }
	// RVA: 0x2f5a300 VA: 0x7595572300
	private Void _OnZoneHomeGuideFinish(Story before) { }
	// RVA: 0x2f5a264 VA: 0x7595572264
	private Void _TryTriggerMixStoryIntro() { }
	// RVA: 0x2f52edc VA: 0x759556aedc
	private Void _InitTopMenu() { }
	// RVA: 0x2f5a37c VA: 0x759557237c
	private Void _TopMenuProcessor(GameObject topMenuObj) { }
	// RVA: 0x2f542ec VA: 0x759556c2ec
	private Void _EventOnStateBackBtnClicked() { }
	// RVA: 0x2f5a4d4 VA: 0x75955724d4
	private IEnumerator _ResetToZoneSelectState() { }
	// RVA: 0x2f585a0 VA: 0x75955705a0
	private IEnumerator _ResetToStageEntry(StageViewModel stageEntry) { }
	// RVA: 0x2f582a8 VA: 0x75955702a8
	private IEnumerator _ResetToStage(String stageId) { }
	// RVA: 0x2f5a580 VA: 0x7595572580
	private Void _ClearCacheBeforeReset() { }
	// RVA: 0x2f5a5f0 VA: 0x75955725f0
	private IEnumerator _WrapWithBlackLoading(IEnumerator[] innerSteps) { }
	// RVA: 0x2f5a6c0 VA: 0x75955726c0
	private IEnumerator _SetStateViaParam(DataBundle param) { }
	// RVA: 0x2f5a790 VA: 0x7595572790
	private IEnumerator _JumpToZoneSelect(String zoneId) { }
	// RVA: 0x2f5a860 VA: 0x7595572860
	private IEnumerator _JumpToZoneSelectByViewType(ZoneViewType type, String retroRelevantActId, Boolean focusLastVisitedMainline) { }
	// RVA: 0x2f5a958 VA: 0x7595572958
	private IEnumerator _JumpToActivity(String activityId) { }
	// RVA: 0x2f5aa28 VA: 0x7595572a28
	private IEnumerator _JumpToZone(String zoneId) { }
	// RVA: 0x2f5aaf8 VA: 0x7595572af8
	private IEnumerator _JumpToStage(String stageId) { }
	// RVA: 0x2f5abc8 VA: 0x7595572bc8
	private IEnumerator _JumpToStageRemain(StageId stage, StageData stageData) { }
	// RVA: 0x2f5acd0 VA: 0x7595572cd0
	private List`1 _DefaultStackListToZone(String zoneId) { }
	// RVA: 0x2f5b2dc VA: 0x75955732dc
	private List`1 _DefaultStackListToStage(StageId stageId, StageData stageData) { }
	// RVA: 0x2f5b1a4 VA: 0x75955731a4
	private Boolean _CheckZoneRequireRetroState(String zoneId) { }
	// RVA: 0x2f5b96c VA: 0x759557396c
	private static List`1 _ExtractInitRewards(DataBundle bundle) { }
	// RVA: 0x2f5bb14 VA: 0x7595573b14
	private static ActivityInitMeta _GenActInitDataWraper(DataBundle bundle) { }
	// RVA: 0x2f5bd3c VA: 0x7595573d3c
	private Void _RedirectActInitMetaToStage(String zoneId, String stageId) { }
	// RVA: 0x2f5be28 VA: 0x7595573e28
	private Void _JumpToCampaign() { }
	// RVA: 0x2f534d0 VA: 0x759556b4d0
	private Void _OnBackToStagePage(UIPageTransContext context) { }
	// RVA: 0x2f5bee4 VA: 0x7595573ee4
	private IEnumerator _WaitForActivityReadyCoroutine(String activityId) { }
	// RVA: 0x2f52ff0 VA: 0x759556aff0
	private Void _ConsumeExpiredTrackPoint() { }
	// RVA: 0x2f5bfb4 VA: 0x7595573fb4
	private Void _TryToTrackSixStarFirstPass(DataBundle dataBundle) { }
	// RVA: 0x2f5c118 VA: 0x7595574118
	public Sprite LoadStartBattleCostIcon(String styleId) { }
	// RVA: 0x2f5c578 VA: 0x7595574578
	public Sprite LoadStartBattleButtonImage(String styleId) { }
	// RVA: 0x2f5c750 VA: 0x7595574750
	public Sprite LoadStartBattleCostBkg(String styleId) { }
	// RVA: 0x2f5c2f0 VA: 0x75955742f0
	private Sprite _LoadSpriteFromStartBattleStyle(String styleId, Func`2 returnSpriteFromBuildIn, Func`2 returnSpriteFromActivity) { }
	// RVA: 0x2f5c928 VA: 0x7595574928
	private Void Update() { }
	// RVA: 0x2f5c9d4 VA: 0x75955749d4
	public Void .ctor() { }
	// RVA: 0x2f5cad4 VA: 0x7595574ad4
	private IEnumerator <>n__0(UIPageStackParam param) { }
	// RVA: 0x2f5cb04 VA: 0x7595574b04
	private IEnumerator <>n__1() { }
	// RVA: 0x2f5cb0c VA: 0x7595574b0c
	private IEnumerator <>n__2(Boolean isFromStack) { }
	// RVA: 0x2f5cb18 VA: 0x7595574b18
	private IEnumerator <>n__3(Boolean isIntoStack) { }
	// RVA: 0x2f5cb24 VA: 0x7595574b24
	private Void <_OnSendUnlockStageFog>b__114_0(UnlockStageFogResponse <p0>) { }
	// RVA: 0x2f5cb28 VA: 0x7595574b28
	private Void <_OnSendGetSpecialStageReward>b__116_0(SpecialStoryStageRewardResponse <p0>) { }
	// RVA: 0x2f5cb2c VA: 0x7595574b2c
	private Void <_TopMenuProcessor>b__129_0(UIRouteTarget target, Object param, Action`2 baseHandler) { }
	// RVA: 0x2f5cb90 VA: 0x7595574b90
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x2f5cb98 VA: 0x7595574b98
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2f5cba0 VA: 0x7595574ba0
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x2f5cba8 VA: 0x7595574ba8
	private Void <>xLuaBaseProxy_OnReuse(DataBundle P0) { }
	// RVA: 0x2f5cbb0 VA: 0x7595574bb0
	private IEnumerator <>xLuaBaseProxy_OnPageReservedDuringReset(UIPageStackParam P0) { }
	// RVA: 0x2f5cbe0 VA: 0x7595574be0
	private Void <>xLuaBaseProxy_OnPageRouted() { }
	// RVA: 0x2f5cbe8 VA: 0x7595574be8
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2f5cbf0 VA: 0x7595574bf0
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2f5cbf8 VA: 0x7595574bf8
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x2f5cc04 VA: 0x7595574c04
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x2f5cc10 VA: 0x7595574c10
	private Void <>xLuaBaseProxy_DisplayWholePage(Boolean P0) { }
	// RVA: 0x2f5cc1c VA: 0x7595574c1c
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```