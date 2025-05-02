# RoguelikeDungeonController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeCommonTopMenu _commonTopMenuPrefab`

- `StateEngine _stateEngine`

- `RoguelikeDungeonZoneView _zoneView`

- `RoguelikeFocusNodeView _focusNodeView`

- `RoguelikeCameraController _cameraController`

- `RoguelikeCustomNotifyController _customNotifyController`

- `EventTrigger _backGroundEventTrigger`

- `RectTransform _menuHolder`

- `PrefabInstHolder _dungeonFloatHolder`

- `RectTransform _mapPreviewRoot`

- `RectTransform _panelRaycastBlock`

- `RectTransform _dialogContainer`

- `RoguelikeDungeonZoneViewProperty m_dungeonZoneProp`

- `RoguelikeFocusViewProperty m_focusProp`

- `RoguelikeRewardViewProperty m_rewardProp`

- `OnStateChangeListener m_stateEngineListener`

- `Boolean m_isGachaShowing`

- `Boolean m_inited`

- `Boolean m_accessedInitState`

- `RoguelikeMenu m_menu`

- `RoguelikeSingleTopicResHolder m_resHolder`

- `String m_topicId`

- `PendingEventHandler m_pendingEvtHandler`

- `StateStackContext m_stateStackContext`

- `Boolean isBinding`

- `UICompDialogMgr m_dialogMgr`

- `RoguelikeDungeonFloatView <dungeonFloat>k__BackingField`

- `Input input`

- `Coroutine m_interDialogCoro`

- `Boolean m_coroAvail`


## Properties

- `UICompDialogMgr dialogMgr`

- `RoguelikeCommonTopMenu commonTopMenuPrefab`

- `RoguelikeDungeonZoneViewProperty dungeonZoneProp`

- `RoguelikeFocusViewProperty focusProp`

- `RoguelikeRewardViewProperty rewardProp`

- `StateEngine stateEngine`

- `EventTrigger backGroundEventTrigger`

- `RectTransform mapPreviewRoot`

- `RoguelikeCameraController cameraController`

- `RoguelikeDungeonFloatView dungeonFloat`

- `RoguelikeDungeonZoneView zoneView`

- `RoguelikeSingleTopicResHolder resHolder`

- `String topicId`

- `PendingEventHandler pendingEvtHandler`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `RoguelikeCommonTopMenu get_commonTopMenuPrefab()`

- `RoguelikeDungeonZoneViewProperty get_dungeonZoneProp()`

- `RoguelikeFocusViewProperty get_focusProp()`

- `RoguelikeRewardViewProperty get_rewardProp()`

- `StateEngine get_stateEngine()`

- `EventTrigger get_backGroundEventTrigger()`

- `RectTransform get_mapPreviewRoot()`

- `RoguelikeCameraController get_cameraController()`

- `RoguelikeDungeonFloatView get_dungeonFloat()`

- `Void set_dungeonFloat(RoguelikeDungeonFloatView)`

- `RoguelikeDungeonZoneView get_zoneView()`

- `RoguelikeSingleTopicResHolder get_resHolder()`

- `String get_topicId()`

- `PendingEventHandler get_pendingEvtHandler()`

- `Void _InitController()`

- `Void _OnNodeClicked(RoguelikeDungeonNode)`

- `Void _OnZoneCreated(RoguelikeOnDungeonZoneCreatedArgs)`

- `Void _OnMenuCreated(RoguelikeMenu)`

- `Void _OnDungeonFloatCreated(GameObject)`

- `Void _OnStateEnter(Type, Additions)`

- `Void _OnStateResume(Type, Boolean, Additions)`

- `Void _OnBeforeTransition(Type, Type, Additions)`

- `Void _OnStatePause(Type, Additions)`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void SelectRecruitChar(String, Action`3, Action)`

- `Void OnCommonSelectRecruitChar(String, Action)`

- `Void ConsumeRecruitUpgradeTicket(String, Int32, Action)`

- `Boolean CheckIfHaveActiveRecruitAndOpen(Action)`

- `Void OpenDialog(UICompBuilder`2, out)`

- `Void BindDialogCallBack(CallBackHandler, Int32)`

- `Void _CheckNeedToBind()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `IEnumerator _UpdateGacha(List`1, Action)`

- `Int64 _GetBGMInstId()`

- `Void ReloadDungeon(Boolean)`

- `Boolean TryLoadFocusStage()`

- `Boolean CheckIfCanLoadShopState()`

- `Void HandlerRelicGetPushMsg(List`1)`

- `Boolean TryProcessTicket()`

- `Void RequestGiveUpNodeMission(String)`

- `Boolean NeedZoneTransition()`

- `Void SetZoneTransitionViewed()`

- `Void SetRaycastBlock(Boolean)`

- `Void RegisterMenuAdapter(RoguelikeMenuAdapter, Type)`

- `Void RegisterMenuAdapter(State, RoguelikeMenuAdapter, Type)`

- `TEffect AttachRoguelikeEffect(TEffect)`

- `Void ShowDungeon(Boolean, Boolean)`

- `Boolean RequestExitRoguelike()`

- `Void CleanEffect()`

- `Boolean CheckDialogCoroActive()`

- `IEnumerator _OpenAvailInterDialogCoro()`

- `Void OpenAvailInterDialog()`

- `Boolean SetModuleState(Boolean)`

- `Boolean CheckIfStateDirectOpenByDungeon(Type)`

- `Boolean CheckFrontStateDontShowMsg()`

- `Void TriggerRoguelikeCustomNotify(String, ValueBundle)`

- `Void <OnCommonSelectRecruitChar>b__81_0(String, Int32, Action)`

- `Void <_UpdateGacha>b__88_0(Output)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonController : PageSingleComponent, ICompDialogCallBack, IPlayerDataListener, IHotfixable
{
	private static readonly Type[] DONT_SHOW_MSG_STATES; // 0x0
	private RoguelikeCommonTopMenu _commonTopMenuPrefab; // 0x20
	private StateEngine _stateEngine; // 0x28
	private RoguelikeDungeonZoneView _zoneView; // 0x30
	private RoguelikeFocusNodeView _focusNodeView; // 0x38
	private RoguelikeCameraController _cameraController; // 0x40
	private RoguelikeCustomNotifyController _customNotifyController; // 0x48
	private EventTrigger _backGroundEventTrigger; // 0x50
	private RectTransform _menuHolder; // 0x58
	private PrefabInstHolder _dungeonFloatHolder; // 0x60
	private RectTransform _mapPreviewRoot; // 0x68
	private RectTransform _panelRaycastBlock; // 0x70
	private RectTransform _dialogContainer; // 0x78
	private RoguelikeDungeonZoneViewProperty m_dungeonZoneProp; // 0x80
	private RoguelikeFocusViewProperty m_focusProp; // 0x88
	private RoguelikeRewardViewProperty m_rewardProp; // 0x90
	private EventPool`1 m_eventPool; // 0x98
	private OnStateChangeListener m_stateEngineListener; // 0xa0
	private Boolean m_isGachaShowing; // 0xa8
	private List`1 m_modules; // 0xb0
	private Boolean m_inited; // 0xb8
	private Boolean m_accessedInitState; // 0xb9
	private RoguelikeMenu m_menu; // 0xc0
	private RoguelikeSingleTopicResHolder m_resHolder; // 0xc8
	private String m_topicId; // 0xd0
	private PendingEventHandler m_pendingEvtHandler; // 0xd8
	private StateStackContext m_stateStackContext; // 0xe0
	private Dictionary`2 m_compDialogCallBackList; // 0xe8
	private Boolean isBinding; // 0xf0
	private UICompDialogMgr m_dialogMgr; // 0xf8
	private RoguelikeDungeonFloatView <dungeonFloat>k__BackingField; // 0x100
	public Input input; // 0x108
	private Coroutine m_interDialogCoro; // 0x110
	private Boolean m_coroAvail; // 0x118
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x8
	private static DelegateBridge __Hotfix0_get_commonTopMenuPrefab; // 0x10
	private static DelegateBridge __Hotfix0_get_dungeonZoneProp; // 0x18
	private static DelegateBridge __Hotfix0_get_focusProp; // 0x20
	private static DelegateBridge __Hotfix0_get_rewardProp; // 0x28
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x30
	private static DelegateBridge __Hotfix0_get_stateEngine; // 0x38
	private static DelegateBridge __Hotfix0_get_backGroundEventTrigger; // 0x40
	private static DelegateBridge __Hotfix0_get_mapPreviewRoot; // 0x48
	private static DelegateBridge __Hotfix0_get_cameraController; // 0x50
	private static DelegateBridge __Hotfix0_get_dungeonFloat; // 0x58
	private static DelegateBridge __Hotfix0_set_dungeonFloat; // 0x60
	private static DelegateBridge __Hotfix0_get_zoneView; // 0x68
	private static DelegateBridge __Hotfix0_get_resHolder; // 0x70
	private static DelegateBridge __Hotfix0_get_topicId; // 0x78
	private static DelegateBridge __Hotfix0_get_pendingEvtHandler; // 0x80
	private static DelegateBridge __Hotfix0_OnStart; // 0x88
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x90
	private static DelegateBridge __Hotfix0_GetCurrentTopicId; // 0x98
	private static DelegateBridge __Hotfix0_GetDetailData; // 0xa0
	private static DelegateBridge __Hotfix0__InitController; // 0xa8
	private static DelegateBridge __Hotfix0__OnNodeClicked; // 0xb0
	private static DelegateBridge __Hotfix0__OnZoneCreated; // 0xb8
	private static DelegateBridge __Hotfix0__OnMenuCreated; // 0xc0
	private static DelegateBridge __Hotfix0__OnDungeonFloatCreated; // 0xc8
	private static DelegateBridge __Hotfix0__OnStateEnter; // 0xd0
	private static DelegateBridge __Hotfix0__OnStateResume; // 0xd8
	private static DelegateBridge __Hotfix0__OnBeforeTransition; // 0xe0
	private static DelegateBridge __Hotfix0__OnStatePause; // 0xe8
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0xf0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0xf8
	private static DelegateBridge __Hotfix0_CreateTicketCharSelectInput; // 0x100
	private static DelegateBridge __Hotfix0_SelectRecruitChar; // 0x108
	private static DelegateBridge __Hotfix0_OnCommonSelectRecruitChar; // 0x110
	private static DelegateBridge __Hotfix0_ConsumeRecruitUpgradeTicket; // 0x118
	private static DelegateBridge __Hotfix0_CheckIfHaveActiveRecruitAndOpen; // 0x120
	private static DelegateBridge __Hotfix0_OpenDialog; // 0x128
	private static DelegateBridge __Hotfix0_BindDialogCallBack; // 0x130
	private static DelegateBridge __Hotfix0__CheckNeedToBind; // 0x138
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x140
	private static DelegateBridge __Hotfix0__UpdateGacha; // 0x148
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0x150
	private static DelegateBridge __Hotfix0_ReloadDungeon; // 0x158
	private static DelegateBridge __Hotfix0_TryLoadFocusStage; // 0x160
	private static DelegateBridge __Hotfix0_CheckIfCanLoadShopState; // 0x168
	private static DelegateBridge __Hotfix0_HandlerRelicGetPushMsg; // 0x170
	private static DelegateBridge __Hotfix0_TryProcessTicket; // 0x178
	private static DelegateBridge __Hotfix0_RequestGiveUpNodeMission; // 0x180
	private static DelegateBridge __Hotfix0_NeedZoneTransition; // 0x188
	private static DelegateBridge __Hotfix0_SetZoneTransitionViewed; // 0x190
	private static DelegateBridge __Hotfix0_SetRaycastBlock; // 0x198
	private static DelegateBridge __Hotfix0_RegisterMenuAdapter; // 0x1a0
	private static DelegateBridge __Hotfix1_RegisterMenuAdapter; // 0x1a8
	private static DelegateBridge __Hotfix0_AttachRoguelikeEffect; // 0x1b0
	private static DelegateBridge __Hotfix0_ShowDungeon; // 0x1b8
	private static DelegateBridge __Hotfix0_RequestExitRoguelike; // 0x1c0
	private static DelegateBridge __Hotfix0_CleanEffect; // 0x1c8
	private static DelegateBridge __Hotfix0_CheckDialogCoroActive; // 0x1d0
	private static DelegateBridge __Hotfix0__OpenAvailInterDialogCoro; // 0x1d8
	private static DelegateBridge __Hotfix0_OpenAvailInterDialog; // 0x1e0
	private static DelegateBridge __Hotfix0_SetModuleState; // 0x1e8
	private static DelegateBridge __Hotfix0_CheckIfStateDirectOpenByDungeon; // 0x1f0
	private static DelegateBridge __Hotfix0_CheckFrontStateDontShowMsg; // 0x1f8
	private static DelegateBridge __Hotfix0_TriggerRoguelikeCustomNotify; // 0x200
	private static DelegateBridge __Hotfix0_SceneParamToRoguelike; // 0x208
	private static DelegateBridge __Hotfix0_SceneParamToActivity; // 0x210
	private static DelegateBridge __Hotfix0_BattleFinishRedirection; // 0x218
	private static DelegateBridge _c__Hotfix0_ctor; // 0x220

	public UICompDialogMgr dialogMgr { get; }
	public RoguelikeCommonTopMenu commonTopMenuPrefab { get; }
	public RoguelikeDungeonZoneViewProperty dungeonZoneProp { get; }
	public RoguelikeFocusViewProperty focusProp { get; }
	public RoguelikeRewardViewProperty rewardProp { get; }
	public EventPool`1 eventPool { get; }
	public StateEngine stateEngine { get; }
	public EventTrigger backGroundEventTrigger { get; }
	public RectTransform mapPreviewRoot { get; }
	public RoguelikeCameraController cameraController { get; }
	public RoguelikeDungeonFloatView dungeonFloat { get; set; }
	public RoguelikeDungeonZoneView zoneView { get; }
	public RoguelikeSingleTopicResHolder resHolder { get; }
	public String topicId { get; }
	public PendingEventHandler pendingEvtHandler { get; }

	// RVA: 0x2aa6b14 VA: 0x75950beb14
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2aa6b8c VA: 0x75950beb8c
	public RoguelikeCommonTopMenu get_commonTopMenuPrefab() { }
	// RVA: 0x2aa6c04 VA: 0x75950bec04
	public RoguelikeDungeonZoneViewProperty get_dungeonZoneProp() { }
	// RVA: 0x2aa6c7c VA: 0x75950bec7c
	public RoguelikeFocusViewProperty get_focusProp() { }
	// RVA: 0x2aa6cf4 VA: 0x75950becf4
	public RoguelikeRewardViewProperty get_rewardProp() { }
	// RVA: 0x2aa689c VA: 0x75950be89c
	public EventPool`1 get_eventPool() { }
	// RVA: 0x2aa6d6c VA: 0x75950bed6c
	public StateEngine get_stateEngine() { }
	// RVA: 0x2aa6de4 VA: 0x75950bede4
	public EventTrigger get_backGroundEventTrigger() { }
	// RVA: 0x2aa6e5c VA: 0x75950bee5c
	public RectTransform get_mapPreviewRoot() { }
	// RVA: 0x2aa6ed4 VA: 0x75950beed4
	public RoguelikeCameraController get_cameraController() { }
	// RVA: 0x2aa6f4c VA: 0x75950bef4c
	public RoguelikeDungeonFloatView get_dungeonFloat() { }
	// RVA: 0x2aa6fc4 VA: 0x75950befc4
	private Void set_dungeonFloat(RoguelikeDungeonFloatView value) { }
	// RVA: 0x2aa7058 VA: 0x75950bf058
	public RoguelikeDungeonZoneView get_zoneView() { }
	// RVA: 0x2aa70d0 VA: 0x75950bf0d0
	public RoguelikeSingleTopicResHolder get_resHolder() { }
	// RVA: 0x2aa7148 VA: 0x75950bf148
	public String get_topicId() { }
	// RVA: 0x2aa71c0 VA: 0x75950bf1c0
	public PendingEventHandler get_pendingEvtHandler() { }
	// RVA: 0x2aa7238 VA: 0x75950bf238
	protected override Void OnStart() { }
	// RVA: 0x2aa7b40 VA: 0x75950bfb40
	protected override Void OnDestroy() { }
	// RVA: 0x2aa7c60 VA: 0x75950bfc60
	public static String GetCurrentTopicId() { }
	// RVA: 0x2aa7d3c VA: 0x75950bfd3c
	public static RoguelikeTopicDetail GetDetailData(String topicId) { }
	// RVA: 0x2aa7304 VA: 0x75950bf304
	private Void _InitController() { }
	// RVA: 0x2aa8478 VA: 0x75950c0478
	private Void _OnNodeClicked(RoguelikeDungeonNode node) { }
	// RVA: 0x2aa8b3c VA: 0x75950c0b3c
	private Void _OnZoneCreated(RoguelikeOnDungeonZoneCreatedArgs args) { }
	// RVA: 0x2aa82d0 VA: 0x75950c02d0
	private Void _OnMenuCreated(RoguelikeMenu menuPanel) { }
	// RVA: 0x2aa8bf0 VA: 0x75950c0bf0
	private Void _OnDungeonFloatCreated(GameObject obj) { }
	// RVA: 0x2aa8d18 VA: 0x75950c0d18
	private Void _OnStateEnter(Type stateType, Additions additions) { }
	// RVA: 0x2aa8e3c VA: 0x75950c0e3c
	private Void _OnStateResume(Type stateType, Boolean isBack, Additions additions) { }
	// RVA: 0x2aa8f70 VA: 0x75950c0f70
	private Void _OnBeforeTransition(Type stateType, Type toType, Additions additions) { }
	// RVA: 0x2aa9140 VA: 0x75950c1140
	private Void _OnStatePause(Type stateType, Additions additions) { }
	// RVA: 0x2aa9264 VA: 0x75950c1264
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2aa9314 VA: 0x75950c1314
	public Void OnPlayerDataChanged() { }
	// RVA: 0x2aa93f0 VA: 0x75950c13f0
	public static Input CreateTicketCharSelectInput(String tickedId, Action`3 resultCallback, Action onQuit) { }
	// RVA: 0x2aa9acc VA: 0x75950c1acc
	public Void SelectRecruitChar(String ticketIndex, Action`3 resultCallback, Action onQuit) { }
	// RVA: 0x2aa9ca4 VA: 0x75950c1ca4
	public Void OnCommonSelectRecruitChar(String ticketIndex, Action onQuit) { }
	// RVA: 0x2aa9d90 VA: 0x75950c1d90
	public Void ConsumeRecruitUpgradeTicket(String ticketIndex, Int32 selectedInstId, Action onFinished) { }
	// RVA: 0x2aaa2d0 VA: 0x75950c22d0
	public Boolean CheckIfHaveActiveRecruitAndOpen(Action onQuit) { }
	// RVA: 0x VA: 0x0
	public Void OpenDialog(UICompBuilder`2 builder, out Int32 instId) { }
	// RVA: 0x VA: 0x0
	public Void BindDialogCallBack(CallBackHandler handler, Int32 instId) { }
	// RVA: 0x2aaa4fc VA: 0x75950c24fc
	private Void _CheckNeedToBind() { }
	// RVA: 0x2aaa628 VA: 0x75950c2628
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2aaa9d8 VA: 0x75950c29d8
	private IEnumerator _UpdateGacha(List`1 chars, Action onFinished) { }
	// RVA: 0x2aaaaf8 VA: 0x75950c2af8
	private Int64 _GetBGMInstId() { }
	// RVA: 0x2aaa7cc VA: 0x75950c27cc
	public Void ReloadDungeon(Boolean notifyFromInitState) { }
	// RVA: 0x2aa8918 VA: 0x75950c0918
	public Boolean TryLoadFocusStage() { }
	// RVA: 0x2aaab7c VA: 0x75950c2b7c
	public Boolean CheckIfCanLoadShopState() { }
	// RVA: 0x2aaacec VA: 0x75950c2cec
	public Void HandlerRelicGetPushMsg(List`1 idList) { }
	// RVA: 0x2aaae50 VA: 0x75950c2e50
	public Boolean TryProcessTicket() { }
	// RVA: 0x2aaaefc VA: 0x75950c2efc
	public Void RequestGiveUpNodeMission(String missionId) { }
	// RVA: 0x2aab2b4 VA: 0x75950c32b4
	public Boolean NeedZoneTransition() { }
	// RVA: 0x2aab36c VA: 0x75950c336c
	public Void SetZoneTransitionViewed() { }
	// RVA: 0x2aab428 VA: 0x75950c3428
	public Void SetRaycastBlock(Boolean flag) { }
	// RVA: 0x VA: 0x0
	public Void RegisterMenuAdapter(RoguelikeMenuAdapter adapter, Type adapterType) { }
	// RVA: 0x2aab4cc VA: 0x75950c34cc
	public Void RegisterMenuAdapter(State state, RoguelikeMenuAdapter adapter, Type adapterType) { }
	// RVA: 0x VA: 0x0
	public TEffect AttachRoguelikeEffect(TEffect effectPrefab) { }
	// RVA: 0x2aab5f0 VA: 0x75950c35f0
	public Void ShowDungeon(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2aab6c0 VA: 0x75950c36c0
	public Boolean RequestExitRoguelike() { }
	// RVA: 0x2aab7a8 VA: 0x75950c37a8
	public Void CleanEffect() { }
	// RVA: 0x2aab82c VA: 0x75950c382c
	public Boolean CheckDialogCoroActive() { }
	// RVA: 0x2aab8a4 VA: 0x75950c38a4
	private IEnumerator _OpenAvailInterDialogCoro() { }
	// RVA: 0x2aab988 VA: 0x75950c3988
	public Void OpenAvailInterDialog() { }
	// RVA: 0x VA: 0x0
	public Boolean SetModuleState(Boolean running) { }
	// RVA: 0x2aabad0 VA: 0x75950c3ad0
	public Boolean CheckIfStateDirectOpenByDungeon(Type stateType) { }
	// RVA: 0x2aabd24 VA: 0x75950c3d24
	public Boolean CheckFrontStateDontShowMsg() { }
	// RVA: 0x2aabe84 VA: 0x75950c3e84
	public Void TriggerRoguelikeCustomNotify(String path, ValueBundle options) { }
	// RVA: 0x2aabf5c VA: 0x75950c3f5c
	public static UIPageControllerParam SceneParamToRoguelike(DataBundle dataBundle) { }
	// RVA: 0x2aac538 VA: 0x75950c4538
	public static UIPageControllerParam SceneParamToActivity(DataBundle dataBundle) { }
	// RVA: 0x2aac830 VA: 0x75950c4830
	public static Void BattleFinishRedirection() { }
	// RVA: 0x2aaca84 VA: 0x75950c4a84
	public Void .ctor() { }
	// RVA: 0x2aacdf4 VA: 0x75950c4df4
	private static Void .cctor() { }
	// RVA: 0x2aacf0c VA: 0x75950c4f0c
	private Void <OnCommonSelectRecruitChar>b__81_0(String ticketId, Int32 selectInst, Action callback) { }
	// RVA: 0x2aacff4 VA: 0x75950c4ff4
	private Void <_UpdateGacha>b__88_0(Output output) { }
	// RVA: 0x2aacffc VA: 0x75950c4ffc
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2aad004 VA: 0x75950c5004
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```