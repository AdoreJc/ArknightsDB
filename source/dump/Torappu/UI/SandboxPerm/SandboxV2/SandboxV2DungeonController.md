# SandboxV2DungeonController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `StateEngine _stateEngine`

- `SandboxV2DungeonCameraController _cameraController`

- `SandboxV2DungeonMapView _dungeonMapView`

- `SandboxV2DungeonView _dungeonView`

- `SandboxV2StateBindingPanelManager _stateBindingPanelMgr`

- `GameObject _tutorialLeftSliderGo`

- `RectTransform _backPressRt`

- `Boolean m_inited`

- `String m_topicId`

- `SandboxV2DungeonProperty m_dungeonProperty`

- `SandboxV2DungeonViewConfig m_dungeonViewConfig`

- `AsyncGameObjectLoader m_objLoader`

- `Int32 m_pendingAsyncTaskCount`

- `Coroutine m_enterCoroutine`

- `Boolean m_isPlayingEnterAnim`

- `SeqNumChecker m_dungeonConstructChecker`

- `SandboxV2DungeonCameraRTHolder m_cameraRTHolder`


## Properties

- `String topicId`

- `SandboxV2DungeonProperty dungeonProperty`

- `SandboxV2DungeonViewConfig dungeonViewConfig`

- `Boolean isAsyncLoading`

- `SandboxV2DungeonCameraRTHolder cameraRTHolder`


## Methods

- `String get_topicId()`

- `SandboxV2DungeonProperty get_dungeonProperty()`

- `SandboxV2DungeonViewConfig get_dungeonViewConfig()`

- `Boolean get_isAsyncLoading()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void UpdateTime(Single)`

- `Void StartAsyncTask(Int32, Handler)`

- `Void OnGameObjectLoaded(GameObject)`

- `SandboxV2DungeonCameraRTHolder get_cameraRTHolder()`

- `Void _InitController()`

- `Boolean _CheckUIStable()`

- `Void _FocusNode(String, SandboxV2DungeonNodeFocusType, Boolean)`

- `Void _OnCameraCancelSelectedNodeDetail()`

- `Void _CancelSelectedNodeDetail()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnNodeClicked(String)`

- `Void _OnFloatClicked(String)`

- `Void _OnNodeSupplyClicked(String)`

- `Void _OnNodeUpgradeClicked(String)`

- `Void _OnNodeMapClicked(String)`

- `Void _OnNodeEnemyDetailClicked(String)`

- `Void _OnNodeDropDetailClicked(String)`

- `Void _OnNodeStartBattleClicked(String)`

- `Void _StartSelectionStage()`

- `Void _OnOpenAdminPageClicked(SandboxV2AdminMainPanelType)`

- `Void _OnOpenRiftPage()`

- `Void _OnTrackerClicked()`

- `Void _OnDiscardApClicked()`

- `Void _HandleDiscardApService()`

- `IEnumerator _TryOpenCrossDayPage()`

- `IEnumerator _TryOpenRiftSettle()`

- `IEnumerator _TryOpenChallengeSettle()`

- `Void _OnGameflowPanelClicked()`

- `Void _HandleChallengeSettleService()`

- `Void _OnRiftLeaveDirectlyClicked()`

- `Void _HandleNextDayService()`

- `Void _HandleRiftSettleService()`

- `Void _OnOpenProduceDrink()`

- `Boolean TutorialOnly_IsDungeonStable()`

- `Void TriggerNodeSelection()`

- `Void ReloadDungeon(LoadDataParam)`

- `IEnumerator _CoroutinePlayEnterAnim()`

- `Void _StopEnterAnimCoroutine()`

- `Void OnCancelSelectedNodeClicked()`

- `Void OnBackClicked()`

- `Void OnBtnCharRepoClicked()`

- `Void OnBtnInventoryClicked()`

- `Void OnBtnCookClicked()`

- `Void OnBtnWorkbenchClicked()`

- `Void OnBtnShopClicked()`

- `Void OnBtnScienceClicked()`

- `Void OnBtnEnemyRushTrackerClicked()`

- `Void OnBtnOtherTrackerClicked()`

- `Void OnBtnQuestTrackerClicked()`

- `Void OnBtnLogisticsClicked()`

- `Void OnBtnArchiveClicked()`

- `Void OnBtnMilestoneClicked()`

- `Void OnBtnSettleGameClicked()`

- `Void OnBtnLoadArchiveClicked()`

- `Void _HandleSettleGameService()`

- `Void _HandleLoadArchiveService()`

- `Void TutorialOnly_FocusOnNode(String)`

- `Void TutorialOnly_CameraZoom(ZoomType, String)`

- `Void TutorialOnly_RegisterTutorialGo()`

- `Void <_StartSelectionStage>b__64_0()`

- `Void <_OnDiscardApClicked>b__68_0()`

- `Void <_HandleDiscardApService>b__69_0(SandboxV2DiscardApResponse)`

- `Void <_HandleChallengeSettleService>b__74_0(SandboxV2ChallengeSettleResponse)`

- `Void <_OnRiftLeaveDirectlyClicked>b__75_0()`

- `Void <_HandleNextDayService>b__76_0(SandboxV2NextDayResponse)`

- `Void <_HandleRiftSettleService>b__77_0(SandboxV2RiftSettleResponse)`

- `Void <OnBtnSettleGameClicked>b__98_0()`

- `Void <OnBtnSettleGameClicked>b__98_1()`

- `Void <_HandleSettleGameService>b__100_0(SandboxV2SettleGameResponse)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonController : PageSingleComponent, IValueMsgReceiver, ITimeWatcher, IAsyncObjectListener
{
	private const UInt32 PER_FRAME_TOTAL_COST; // 0x0
	public const Int32 ON_NODE_CLICKED; // 0x0
	public const Int32 ON_NODE_SUPPLY_CLICKED; // 0x0
	public const Int32 ON_NODE_UPGRADE_CLICKED; // 0x0
	public const Int32 ON_NODE_MAP_CLICKED; // 0x0
	public const Int32 ON_NODE_ENEMY_DETAIL_CLICKED; // 0x0
	public const Int32 ON_NODE_DROP_DETAIL_CLICKED; // 0x0
	public const Int32 ON_NODE_START_BATTLE_CLICKED; // 0x0
	public const Int32 ON_FLOAT_CLICKED; // 0x0
	public const Int32 ON_DISCARD_AP_CLICKED; // 0x0
	public const Int32 ON_GAMEFLOW_PANEL_CLICKED; // 0x0
	public const Int32 ON_PRODUCE_DRINK; // 0x0
	public const Int32 ON_RIFT_LEAVE_DIRECTLY_CLICKED; // 0x0
	public const Int32 ON_OPEN_RIFT_RESERVE_CLICKED; // 0x0
	public const Int32 ON_LOAD_ARCHIVE_CLICKED; // 0x0
	public const Int32 ON_DELETE_ARCHIVE_CLICKED; // 0x0
	private StateEngine _stateEngine; // 0x20
	private SandboxV2DungeonCameraController _cameraController; // 0x28
	private SandboxV2DungeonMapView _dungeonMapView; // 0x30
	private SandboxV2DungeonView _dungeonView; // 0x38
	private SandboxV2StateBindingPanelManager _stateBindingPanelMgr; // 0x40
	private GameObject _tutorialLeftSliderGo; // 0x48
	private RectTransform _backPressRt; // 0x50
	private Boolean m_inited; // 0x58
	private String m_topicId; // 0x60
	private SandboxV2DungeonProperty m_dungeonProperty; // 0x68
	private SandboxV2DungeonViewConfig m_dungeonViewConfig; // 0x70
	private AsyncGameObjectLoader m_objLoader; // 0x78
	private Int32 m_pendingAsyncTaskCount; // 0x80
	private Coroutine m_enterCoroutine; // 0x88
	private Boolean m_isPlayingEnterAnim; // 0x90
	private SeqNumChecker m_dungeonConstructChecker; // 0x98
	private SandboxV2DungeonCameraRTHolder m_cameraRTHolder; // 0xa8
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_dungeonProperty; // 0x8
	private static DelegateBridge __Hotfix0_get_dungeonViewConfig; // 0x10
	private static DelegateBridge __Hotfix0_get_isAsyncLoading; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0_StartAsyncTask; // 0x40
	private static DelegateBridge __Hotfix0_OnGameObjectLoaded; // 0x48
	private static DelegateBridge __Hotfix0_get_cameraRTHolder; // 0x50
	private static DelegateBridge __Hotfix0_OnCreate; // 0x58
	private static DelegateBridge __Hotfix0__InitController; // 0x60
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0x68
	private static DelegateBridge __Hotfix0__FocusNode; // 0x70
	private static DelegateBridge __Hotfix0__OnCameraCancelSelectedNodeDetail; // 0x78
	private static DelegateBridge __Hotfix0__CancelSelectedNodeDetail; // 0x80
	private static DelegateBridge __Hotfix0_OnMessage; // 0x88
	private static DelegateBridge __Hotfix0__OnNodeClicked; // 0x90
	private static DelegateBridge __Hotfix0__OnFloatClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnNodeSupplyClicked; // 0xa0
	private static DelegateBridge __Hotfix0__OnNodeUpgradeClicked; // 0xa8
	private static DelegateBridge __Hotfix0__OnNodeMapClicked; // 0xb0
	private static DelegateBridge __Hotfix0__OnNodeEnemyDetailClicked; // 0xb8
	private static DelegateBridge __Hotfix0__OnNodeDropDetailClicked; // 0xc0
	private static DelegateBridge __Hotfix0__OnNodeStartBattleClicked; // 0xc8
	private static DelegateBridge __Hotfix0__StartSelectionStage; // 0xd0
	private static DelegateBridge __Hotfix0__OnOpenAdminPageClicked; // 0xd8
	private static DelegateBridge __Hotfix0__OnOpenRiftPage; // 0xe0
	private static DelegateBridge __Hotfix0__OnTrackerClicked; // 0xe8
	private static DelegateBridge __Hotfix0__OnDiscardApClicked; // 0xf0
	private static DelegateBridge __Hotfix0__HandleDiscardApService; // 0xf8
	private static DelegateBridge __Hotfix0__TryOpenCrossDayPage; // 0x100
	private static DelegateBridge __Hotfix0__TryOpenRiftSettle; // 0x108
	private static DelegateBridge __Hotfix0__TryOpenChallengeSettle; // 0x110
	private static DelegateBridge __Hotfix0__OnGameflowPanelClicked; // 0x118
	private static DelegateBridge __Hotfix0__HandleChallengeSettleService; // 0x120
	private static DelegateBridge __Hotfix0__OnRiftLeaveDirectlyClicked; // 0x128
	private static DelegateBridge __Hotfix0__HandleNextDayService; // 0x130
	private static DelegateBridge __Hotfix0__HandleRiftSettleService; // 0x138
	private static DelegateBridge __Hotfix0__OnOpenProduceDrink; // 0x140
	private static DelegateBridge __Hotfix0_TutorialOnly_IsDungeonStable; // 0x148
	private static DelegateBridge __Hotfix0_TriggerNodeSelection; // 0x150
	private static DelegateBridge __Hotfix0_ReloadDungeon; // 0x158
	private static DelegateBridge __Hotfix0__CoroutinePlayEnterAnim; // 0x160
	private static DelegateBridge __Hotfix0__StopEnterAnimCoroutine; // 0x168
	private static DelegateBridge __Hotfix0_OnCancelSelectedNodeClicked; // 0x170
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x178
	private static DelegateBridge __Hotfix0_OnBtnCharRepoClicked; // 0x180
	private static DelegateBridge __Hotfix0_OnBtnInventoryClicked; // 0x188
	private static DelegateBridge __Hotfix0_OnBtnCookClicked; // 0x190
	private static DelegateBridge __Hotfix0_OnBtnWorkbenchClicked; // 0x198
	private static DelegateBridge __Hotfix0_OnBtnShopClicked; // 0x1a0
	private static DelegateBridge __Hotfix0_OnBtnScienceClicked; // 0x1a8
	private static DelegateBridge __Hotfix0_OnBtnEnemyRushTrackerClicked; // 0x1b0
	private static DelegateBridge __Hotfix0_OnBtnOtherTrackerClicked; // 0x1b8
	private static DelegateBridge __Hotfix0_OnBtnQuestTrackerClicked; // 0x1c0
	private static DelegateBridge __Hotfix0_OnBtnLogisticsClicked; // 0x1c8
	private static DelegateBridge __Hotfix0_OnBtnArchiveClicked; // 0x1d0
	private static DelegateBridge __Hotfix0_OnBtnMilestoneClicked; // 0x1d8
	private static DelegateBridge __Hotfix0_OnBtnSettleGameClicked; // 0x1e0
	private static DelegateBridge __Hotfix0_OnBtnLoadArchiveClicked; // 0x1e8
	private static DelegateBridge __Hotfix0__HandleSettleGameService; // 0x1f0
	private static DelegateBridge __Hotfix0__HandleLoadArchiveService; // 0x1f8
	private static DelegateBridge __Hotfix0_TutorialOnly_FocusOnNode; // 0x200
	private static DelegateBridge __Hotfix0_TutorialOnly_CameraZoom; // 0x208
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGo; // 0x210
	private static DelegateBridge _c__Hotfix0_ctor; // 0x218

	public String topicId { get; }
	public SandboxV2DungeonProperty dungeonProperty { get; }
	public SandboxV2DungeonViewConfig dungeonViewConfig { get; }
	public Boolean isAsyncLoading { get; }
	public SandboxV2DungeonCameraRTHolder cameraRTHolder { get; }

	// RVA: 0x25314f8 VA: 0x7594b494f8
	public String get_topicId() { }
	// RVA: 0x252ea6c VA: 0x7594b46a6c
	public SandboxV2DungeonProperty get_dungeonProperty() { }
	// RVA: 0x2535e5c VA: 0x7594b4de5c
	public SandboxV2DungeonViewConfig get_dungeonViewConfig() { }
	// RVA: 0x25355ec VA: 0x7594b4d5ec
	public Boolean get_isAsyncLoading() { }
	// RVA: 0x2535ec4 VA: 0x7594b4dec4
	private Void OnEnable() { }
	// RVA: 0x2535f34 VA: 0x7594b4df34
	private Void OnDisable() { }
	// RVA: 0x2535fa4 VA: 0x7594b4dfa4
	public Void UpdateTime(Single delta) { }
	// RVA: 0x2536038 VA: 0x7594b4e038
	protected override Void OnDestroy() { }
	// RVA: 0x2536190 VA: 0x7594b4e190
	public Void StartAsyncTask(Int32 index, Handler handler) { }
	// RVA: 0x253629c VA: 0x7594b4e29c
	public Void OnGameObjectLoaded(GameObject obj) { }
	// RVA: 0x2536320 VA: 0x7594b4e320
	public SandboxV2DungeonCameraRTHolder get_cameraRTHolder() { }
	// RVA: 0x2536388 VA: 0x7594b4e388
	protected override Void OnCreate() { }
	// RVA: 0x25363fc VA: 0x7594b4e3fc
	private Void _InitController() { }
	// RVA: 0x25366dc VA: 0x7594b4e6dc
	private Boolean _CheckUIStable() { }
	// RVA: 0x25367e4 VA: 0x7594b4e7e4
	private Void _FocusNode(String nodeId, SandboxV2DungeonNodeFocusType focusType, Boolean fastMode) { }
	// RVA: 0x25368fc VA: 0x7594b4e8fc
	private Void _OnCameraCancelSelectedNodeDetail() { }
	// RVA: 0x253697c VA: 0x7594b4e97c
	private Void _CancelSelectedNodeDetail() { }
	// RVA: 0x2536a6c VA: 0x7594b4ea6c
	public Void OnMessage(Int32 msg, ValueBundle data) { }
	// RVA: 0x2536d50 VA: 0x7594b4ed50
	private Void _OnNodeClicked(String nodeId) { }
	// RVA: 0x2538334 VA: 0x7594b50334
	private Void _OnFloatClicked(String nodeId) { }
	// RVA: 0x2536f94 VA: 0x7594b4ef94
	private Void _OnNodeSupplyClicked(String nodeId) { }
	// RVA: 0x2537218 VA: 0x7594b4f218
	private Void _OnNodeUpgradeClicked(String nodeId) { }
	// RVA: 0x25373b0 VA: 0x7594b4f3b0
	private Void _OnNodeMapClicked(String nodeId) { }
	// RVA: 0x2537548 VA: 0x7594b4f548
	private Void _OnNodeEnemyDetailClicked(String nodeId) { }
	// RVA: 0x2537c98 VA: 0x7594b4fc98
	private Void _OnNodeDropDetailClicked(String nodeId) { }
	// RVA: 0x2537e30 VA: 0x7594b4fe30
	private Void _OnNodeStartBattleClicked(String nodeId) { }
	// RVA: 0x25398c4 VA: 0x7594b518c4
	private Void _StartSelectionStage() { }
	// RVA: 0x2539c2c VA: 0x7594b51c2c
	private Void _OnOpenAdminPageClicked(SandboxV2AdminMainPanelType pnlType) { }
	// RVA: 0x25390e4 VA: 0x7594b510e4
	private Void _OnOpenRiftPage() { }
	// RVA: 0x VA: 0x0
	private Void _OnTrackerClicked() { }
	// RVA: 0x253866c VA: 0x7594b5066c
	private Void _OnDiscardApClicked() { }
	// RVA: 0x2539d38 VA: 0x7594b51d38
	private Void _HandleDiscardApService() { }
	// RVA: 0x2539f20 VA: 0x7594b51f20
	private IEnumerator _TryOpenCrossDayPage() { }
	// RVA: 0x2539fcc VA: 0x7594b51fcc
	private IEnumerator _TryOpenRiftSettle() { }
	// RVA: 0x253a078 VA: 0x7594b52078
	private IEnumerator _TryOpenChallengeSettle() { }
	// RVA: 0x2538960 VA: 0x7594b50960
	private Void _OnGameflowPanelClicked() { }
	// RVA: 0x253a4f4 VA: 0x7594b524f4
	private Void _HandleChallengeSettleService() { }
	// RVA: 0x2538d14 VA: 0x7594b50d14
	private Void _OnRiftLeaveDirectlyClicked() { }
	// RVA: 0x253a30c VA: 0x7594b5230c
	private Void _HandleNextDayService() { }
	// RVA: 0x253a124 VA: 0x7594b52124
	private Void _HandleRiftSettleService() { }
	// RVA: 0x2538ab0 VA: 0x7594b50ab0
	private Void _OnOpenProduceDrink() { }
	// RVA: 0x2534fc8 VA: 0x7594b4cfc8
	public Boolean TutorialOnly_IsDungeonStable() { }
	// RVA: 0x2539760 VA: 0x7594b51760
	public Void TriggerNodeSelection() { }
	// RVA: 0x253a6dc VA: 0x7594b526dc
	public Void ReloadDungeon(LoadDataParam loadParam) { }
	// RVA: 0x253a894 VA: 0x7594b52894
	private IEnumerator _CoroutinePlayEnterAnim() { }
	// RVA: 0x25360ac VA: 0x7594b4e0ac
	private Void _StopEnterAnimCoroutine() { }
	// RVA: 0x253a940 VA: 0x7594b52940
	public Void OnCancelSelectedNodeClicked() { }
	// RVA: 0x253a9c0 VA: 0x7594b529c0
	public Void OnBackClicked() { }
	// RVA: 0x253ab18 VA: 0x7594b52b18
	public Void OnBtnCharRepoClicked() { }
	// RVA: 0x253ab84 VA: 0x7594b52b84
	public Void OnBtnInventoryClicked() { }
	// RVA: 0x253abf0 VA: 0x7594b52bf0
	public Void OnBtnCookClicked() { }
	// RVA: 0x253ac5c VA: 0x7594b52c5c
	public Void OnBtnWorkbenchClicked() { }
	// RVA: 0x253acc8 VA: 0x7594b52cc8
	public Void OnBtnShopClicked() { }
	// RVA: 0x253ad7c VA: 0x7594b52d7c
	public Void OnBtnScienceClicked() { }
	// RVA: 0x253ade8 VA: 0x7594b52de8
	public Void OnBtnEnemyRushTrackerClicked() { }
	// RVA: 0x253ae68 VA: 0x7594b52e68
	public Void OnBtnOtherTrackerClicked() { }
	// RVA: 0x253aee8 VA: 0x7594b52ee8
	public Void OnBtnQuestTrackerClicked() { }
	// RVA: 0x253afbc VA: 0x7594b52fbc
	public Void OnBtnLogisticsClicked() { }
	// RVA: 0x253b194 VA: 0x7594b53194
	public Void OnBtnArchiveClicked() { }
	// RVA: 0x253b3bc VA: 0x7594b533bc
	public Void OnBtnMilestoneClicked() { }
	// RVA: 0x25393e4 VA: 0x7594b513e4
	public Void OnBtnSettleGameClicked() { }
	// RVA: 0x2539278 VA: 0x7594b51278
	public Void OnBtnLoadArchiveClicked() { }
	// RVA: 0x253b6bc VA: 0x7594b536bc
	private Void _HandleSettleGameService() { }
	// RVA: 0x253b5bc VA: 0x7594b535bc
	private Void _HandleLoadArchiveService() { }
	// RVA: 0x253565c VA: 0x7594b4d65c
	public Void TutorialOnly_FocusOnNode(String nodeId) { }
	// RVA: 0x25358d8 VA: 0x7594b4d8d8
	public Void TutorialOnly_CameraZoom(ZoomType zoomType, String nodeId) { }
	// RVA: 0x2535170 VA: 0x7594b4d170
	public Void TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x253b8a4 VA: 0x7594b538a4
	public Void .ctor() { }
	// RVA: 0x253b9c4 VA: 0x7594b539c4
	private Void <_StartSelectionStage>b__64_0() { }
	// RVA: 0x253ba14 VA: 0x7594b53a14
	private Void <_OnDiscardApClicked>b__68_0() { }
	// RVA: 0x253ba18 VA: 0x7594b53a18
	private Void <_HandleDiscardApService>b__69_0(SandboxV2DiscardApResponse response) { }
	// RVA: 0x253baac VA: 0x7594b53aac
	private Void <_HandleChallengeSettleService>b__74_0(SandboxV2ChallengeSettleResponse response) { }
	// RVA: 0x253bb84 VA: 0x7594b53b84
	private Void <_OnRiftLeaveDirectlyClicked>b__75_0() { }
	// RVA: 0x253bb88 VA: 0x7594b53b88
	private Void <_HandleNextDayService>b__76_0(SandboxV2NextDayResponse response) { }
	// RVA: 0x253bc28 VA: 0x7594b53c28
	private Void <_HandleRiftSettleService>b__77_0(SandboxV2RiftSettleResponse response) { }
	// RVA: 0x253bcc8 VA: 0x7594b53cc8
	private Void <OnBtnSettleGameClicked>b__98_0() { }
	// RVA: 0x253bf00 VA: 0x7594b53f00
	private Void <OnBtnSettleGameClicked>b__98_1() { }
	// RVA: 0x253bf04 VA: 0x7594b53f04
	private Void <_HandleSettleGameService>b__100_0(SandboxV2SettleGameResponse response) { }
	// RVA: 0x253bf98 VA: 0x7594b53f98
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x253bfa0 VA: 0x7594b53fa0
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```