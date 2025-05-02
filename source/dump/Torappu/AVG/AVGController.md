# AVGController

**Namespace:** `Torappu.AVG`


## Fields

- `Camera _avgSceneCamera`

- `Camera _avgUICamera`

- `GameObject _skipBtn`

- `AVGAutoButton _autoBtn`

- `GameObject _speedBtn`

- `GameObject _playbackBtn`

- `GameObject _hideuiBtn`

- `PlaybackPanel _playbackPanel`

- `GameObject _hideUiMask`

- `GameObject _dialogPanel`

- `SkipBriefPanel _briefPanel`

- `AVGButton _clickBtn`

- `AutoSpeed _dialogDefaultSpeed`

- `RectTransform _cullMask`

- `AVGQuickPlay _quickPlayPanel`

- `Int32 _toastHoldOnInterval`

- `Int32 _clickToastHoldOnInterval`

- `Int32 _tipClickTimes`

- `Int32 _tipPerClickInterval`

- `Int32 _tipClickTotalInterval`

- `QuickPlayKnownNotifyView _quickPlayKnownNotifyPrefab`

- `AVGCanvasLayerHolder _canvasHolder`

- `Int32 m_skipToIndex`

- `ResourceRouter m_router`

- `Story m_story`

- `Int32 m_executeIndex`

- `Coroutine m_coroutine`

- `Coroutine m_autoPlayingCoroutine`

- `AVGAssetLoader m_assetLoader`

- `Int32 m_decisionValue`

- `Boolean m_needResumeAuto`

- `Boolean m_needResumeAutoStatus`

- `AVGAutoMode autoPlayModeCache`

- `Int32 btnAutoModeCache`

- `AVGStoryCache m_storyCache`

- `AVGCompBridge m_compBridge`

- `IAVGEvents m_avgEvents`

- `AVGSceneEffectManager m_sceneEffectMgr`

- `ICommandPredicator m_commandPredicator`

- `ICommandFlowController m_commandFlowController`

- `ICommandSkipController m_commandSkipController`


## Properties

- `String storyId`

- `AVGStoryCache storyCache`

- `Boolean toastQuickPlay`

- `Boolean isSkippable`

- `AVGAutoMode autoPlayMode`

- `Single autoWaitBaseTime`

- `Single autoWaitTimePerText`

- `Single typeWriterDelay`

- `Single animateRatio`

- `Boolean isTheaterMode`

- `Boolean isAutoClickRaised`

- `Boolean isRunning`

- `Boolean isRunningTutorial`

- `Int32 decisionIndex`

- `StoryParam storyParam`

- `AVGCanvasLayerHolder canvasHolder`

- `ILoadAsset assetLoader`

- `ResourceRouter router`

- `Camera sceneCamera`


## Methods

- `AVGCompBridge _EnsureCompBridge()`

- `AVGSceneEffectManager _GetOrCreateSceneEffectMgr()`

- `String get_storyId()`

- `AVGStoryCache get_storyCache()`

- `Boolean get_toastQuickPlay()`

- `Boolean get_isSkippable()`

- `AVGAutoMode get_autoPlayMode()`

- `Void set_autoPlayMode(AVGAutoMode)`

- `Single get_autoWaitBaseTime()`

- `Single get_autoWaitTimePerText()`

- `Single get_typeWriterDelay()`

- `Single get_animateRatio()`

- `Boolean get_isTheaterMode()`

- `Boolean get_isAutoClickRaised()`

- `Boolean get_isRunning()`

- `Boolean get_isRunningTutorial()`

- `Int32 get_decisionIndex()`

- `Void set_decisionIndex(Int32)`

- `StoryParam get_storyParam()`

- `Void SetCommandPredicator(ICommandPredicator)`

- `Void SetCommandFlowController(ICommandFlowController)`

- `Void SetCommandSkipController(ICommandSkipController)`

- `AVGCanvasLayerHolder get_canvasHolder()`

- `ILoadAsset get_assetLoader()`

- `ResourceRouter get_router()`

- `Camera get_sceneCamera()`

- `Void RunStory(Story)`

- `Void StopStory(String, Boolean)`

- `Void SkipStory()`

- `Void EndStory(String, Boolean)`

- `Void OnStoryCommitted(Boolean, StoryOutPut)`

- `Void SetQuickSpeed(Int32)`

- `Void RaiseAutoClick(Int32)`

- `Void RaiseAutoClick(Single)`

- `Void RaiseSignal(String, String)`

- `Void RaiseSignal(Command)`

- `Void RegisterExecutor(ICommandExecutor)`

- `Void UnregisterExecutor(ICommandExecutor)`

- `Void RegisterComponent(AVGComponent)`

- `Void UnregisterComponent(AVGComponent)`

- `Void RegisterCommandPostChecker(ICommandPostChecker)`

- `Void UnregisterCommandPostChecker(ICommandPostChecker)`

- `T GetAVGComponentOrNull()`

- `Void RegisterExtraGameObject(String, GameObject)`

- `Void UnregisterExtraGameObject(String)`

- `GameObject GetExtraGameObject(String)`

- `TComponent GetExtraGameObject(String)`

- `Boolean TryGetCharSortType(out)`

- `Void _TryShowQuickPlayTip()`

- `Boolean IsTutorialWaitSignalMatchedStringParam(String, String, String)`

- `Boolean _IsTutorialAndWaitSignal(String, out)`

- `IEnumerator DoExecuteCommands()`

- `Void DoEndStory()`

- `IEnumerator DoAutoClick(Single)`

- `Void _PreprocessCommands(IList`1)`

- `Void _InitExecutors()`

- `Void _StopAutoClick()`

- `Void _ResetCache()`

- `Void _CacheOriginSizeDeltaOfFitTargetsIfNot()`

- `Void _SetupFitMode(FitMode)`

- `Void OnCommandFinishedCallback(ICommandExecutor)`

- `Void OnStoryBegin(Story)`

- `Void OnStoryEnd(Boolean, Story, Boolean)`

- `Void _UnloadUnusedAssets(Story)`

- `Void OnReset()`

- `Void OnSkipBtnClicked()`

- `Void OnAutoBtnClicked()`

- `Void OnSpeedBtnClicked()`

- `Void _ShowSpeedImage()`

- `Void OnPlaybackBtnClicked()`

- `Void OnClickPress()`

- `Void OnLongPress(Vector2)`

- `Void SetTheaterMode(Boolean)`

- `String TryGetStoryBriefContent(String)`

- `Void _SetTheaterModeStatus()`

- `Void _SaveAutoStatus()`

- `Void _OnUIInputCommandEnter()`

- `Void _OnUIInputCommandExit()`

- `Void _LoadAutoStatus()`

- `Void UpdateStorySkipMode(SkipNodeLabel)`

- `Void _UpdateSkipStatus()`

- `Void _ShowBriefPanel(String)`

- `Void _PauseAuto()`

- `Void ResumeAuto()`

- `Void OnHideuiBtnClicked()`

- `Void OnHideuiResumeClicked()`

- `Void _DoCacheOriginActiveStates()`

- `Void OnEnable()`

- `Void OnDisable()`

- `T LoadAsset(String)`

- `Object LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Void EditorOnlySetAVGEvents(IAVGEvents)`

- `Void _EditorOnlyNotifyCommandExecuted(Command)`

- `Void _EditorOnlyNotifyCommandFinished(Command)`

- `Void EditorOnlyAbortRemaineCommands()`

- `Void <EndStory>b__115_0(FinishStoryResponse)`

- `Boolean <EndStory>b__115_1(ResponseError)`

- `Boolean <DoAutoClick>b__139_0()`

- `Boolean <DoAutoClick>b__139_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ILoadAsset
{
	private const Int32 SCENECAMERA_DEPTH; // 0x0
	private const Int32 UICAMERA_DEPTH; // 0x0
	private const Single FINISH_STORY_DELAY; // 0x0
	private const Int32 MIN_ASSETS_CNT_TO_UNLOAD_ALL; // 0x0
	private Camera _avgSceneCamera; // 0x18
	private Camera _avgUICamera; // 0x20
	private GameObject _skipBtn; // 0x28
	private AVGAutoButton _autoBtn; // 0x30
	private GameObject _speedBtn; // 0x38
	private GameObject _playbackBtn; // 0x40
	private GameObject _hideuiBtn; // 0x48
	private PlaybackPanel _playbackPanel; // 0x50
	private GameObject _hideUiMask; // 0x58
	private GameObject[] _hideObjects; // 0x60
	private GameObject _dialogPanel; // 0x68
	private SkipBriefPanel _briefPanel; // 0x70
	private AVGButton _clickBtn; // 0x78
	private AutoSpeed _dialogDefaultSpeed; // 0x80
	private AutoSpeed[] _btnAutoSpeed; // 0x98
	private AutoSpeed[] _quickAutoSpeed; // 0xa0
	private RectTransform _cullMask; // 0xa8
	private RectTransform[] _fitTargets; // 0xb0
	private AVGQuickPlay _quickPlayPanel; // 0xb8
	private Int32 _toastHoldOnInterval; // 0xc0
	private Int32 _clickToastHoldOnInterval; // 0xc4
	private Int32 _tipClickTimes; // 0xc8
	private Int32 _tipPerClickInterval; // 0xcc
	private Int32 _tipClickTotalInterval; // 0xd0
	private QuickPlayKnownNotifyView _quickPlayKnownNotifyPrefab; // 0xd8
	private AVGCanvasLayerHolder _canvasHolder; // 0xe0
	private Vector2[] m_originSizeDeltaOfFitTargets; // 0xe8
	private Int32 m_skipToIndex; // 0xf0
	private AVGComponent[] m_components; // 0xf8
	private EventPool`1 m_eventPool; // 0x100
	private ResourceRouter m_router; // 0x108
	private Story m_story; // 0x110
	private Dictionary`2 m_commandExecutorsMap; // 0x118
	private Int32 m_executeIndex; // 0x120
	private List`1 m_blockingExecutors; // 0x128
	private readonly List`1 m_activeCheckers; // 0x130
	private Dictionary`2 m_commandPostCheckerMap; // 0x138
	private Coroutine m_coroutine; // 0x140
	private Coroutine m_autoPlayingCoroutine; // 0x148
	private AVGAssetLoader m_assetLoader; // 0x150
	private Int32 m_decisionValue; // 0x158
	private Boolean m_needResumeAuto; // 0x15c
	private Boolean m_needResumeAutoStatus; // 0x15d
	public AVGAutoMode autoPlayModeCache; // 0x160
	public Int32 btnAutoModeCache; // 0x164
	private Dictionary`2 m_gameObjectPool; // 0x168
	private Boolean[] m_prevActiveStates; // 0x170
	private Boolean[] m_originActiveStates; // 0x178
	private AVGStoryCache m_storyCache; // 0x180
	private AVGCompBridge m_compBridge; // 0x1c0
	private IAVGEvents m_avgEvents; // 0x1c8
	private AVGSceneEffectManager m_sceneEffectMgr; // 0x1d0
	private ICommandPredicator m_commandPredicator; // 0x1d8
	private ICommandFlowController m_commandFlowController; // 0x1e0
	private ICommandSkipController m_commandSkipController; // 0x1e8
	private static DelegateBridge __Hotfix0__EnsureCompBridge; // 0x0
	private static DelegateBridge __Hotfix0__GetOrCreateSceneEffectMgr; // 0x8
	private static DelegateBridge __Hotfix0_get_storyId; // 0x10
	private static DelegateBridge __Hotfix0_get_storyCache; // 0x18
	private static DelegateBridge __Hotfix0_get_toastQuickPlay; // 0x20
	private static DelegateBridge __Hotfix0_get_isSkippable; // 0x28
	private static DelegateBridge __Hotfix0_get_autoPlayMode; // 0x30
	private static DelegateBridge __Hotfix0_set_autoPlayMode; // 0x38
	private static DelegateBridge __Hotfix0_get_autoWaitBaseTime; // 0x40
	private static DelegateBridge __Hotfix0_get_autoWaitTimePerText; // 0x48
	private static DelegateBridge __Hotfix0_get_typeWriterDelay; // 0x50
	private static DelegateBridge __Hotfix0_get_animateRatio; // 0x58
	private static DelegateBridge __Hotfix0_get_isTheaterMode; // 0x60
	private static DelegateBridge __Hotfix0_get_isAutoClickRaised; // 0x68
	private static DelegateBridge __Hotfix0_get_isRunning; // 0x70
	private static DelegateBridge __Hotfix0_get_isRunningTutorial; // 0x78
	private static DelegateBridge __Hotfix0_get_decisionIndex; // 0x80
	private static DelegateBridge __Hotfix0_set_decisionIndex; // 0x88
	private static DelegateBridge __Hotfix0_get_storyParam; // 0x90
	private static DelegateBridge __Hotfix0_SetCommandPredicator; // 0x98
	private static DelegateBridge __Hotfix0_SetCommandFlowController; // 0xa0
	private static DelegateBridge __Hotfix0_SetCommandSkipController; // 0xa8
	private static DelegateBridge __Hotfix0_get_canvasHolder; // 0xb0
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0xb8
	private static DelegateBridge __Hotfix0_get_eventPool; // 0xc0
	private static DelegateBridge __Hotfix0_get_router; // 0xc8
	private static DelegateBridge __Hotfix0_get_sceneCamera; // 0xd0
	private static DelegateBridge __Hotfix0_RunStory; // 0xd8
	private static DelegateBridge __Hotfix0_StopStory; // 0xe0
	private static DelegateBridge __Hotfix0_SkipStory; // 0xe8
	private static DelegateBridge __Hotfix0_EndStory; // 0xf0
	private static DelegateBridge __Hotfix0_OnStoryCommitted; // 0xf8
	private static DelegateBridge __Hotfix0_SetQuickSpeed; // 0x100
	private static DelegateBridge __Hotfix0_RaiseAutoClick; // 0x108
	private static DelegateBridge __Hotfix1_RaiseAutoClick; // 0x110
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x118
	private static DelegateBridge __Hotfix1_RaiseSignal; // 0x120
	private static DelegateBridge __Hotfix0_RegisterExecutor; // 0x128
	private static DelegateBridge __Hotfix0_UnregisterExecutor; // 0x130
	private static DelegateBridge __Hotfix0_RegisterComponent; // 0x138
	private static DelegateBridge __Hotfix0_UnregisterComponent; // 0x140
	private static DelegateBridge __Hotfix0_RegisterCommandPostChecker; // 0x148
	private static DelegateBridge __Hotfix0_UnregisterCommandPostChecker; // 0x150
	private static DelegateBridge __Hotfix0_GetAVGComponentOrNull; // 0x158
	private static DelegateBridge __Hotfix0_RegisterExtraGameObject; // 0x160
	private static DelegateBridge __Hotfix0_UnregisterExtraGameObject; // 0x168
	private static DelegateBridge __Hotfix0_GetExtraGameObject; // 0x170
	private static DelegateBridge __Hotfix1_GetExtraGameObject; // 0x178
	private static DelegateBridge __Hotfix0_TryGetCharSortType; // 0x180
	private static DelegateBridge __Hotfix0__TryShowQuickPlayTip; // 0x188
	private static DelegateBridge __Hotfix0_IsTutorialWaitSignalMatchedStringParam; // 0x190
	private static DelegateBridge __Hotfix0__IsTutorialAndWaitSignal; // 0x198
	private static DelegateBridge __Hotfix0_DoExecuteCommands; // 0x1a0
	private static DelegateBridge __Hotfix0_DoEndStory; // 0x1a8
	private static DelegateBridge __Hotfix0_DoAutoClick; // 0x1b0
	private static DelegateBridge __Hotfix0__GetCommandExecutors; // 0x1b8
	private static DelegateBridge __Hotfix0__GetCommandPostCheckers; // 0x1c0
	private static DelegateBridge __Hotfix0__PreprocessCommands; // 0x1c8
	private static DelegateBridge __Hotfix0__InitExecutors; // 0x1d0
	private static DelegateBridge __Hotfix0__StopAutoClick; // 0x1d8
	private static DelegateBridge __Hotfix0__ResetCache; // 0x1e0
	private static DelegateBridge __Hotfix0__CacheOriginSizeDeltaOfFitTargetsIfNot; // 0x1e8
	private static DelegateBridge __Hotfix0__SetupFitMode; // 0x1f0
	private static DelegateBridge __Hotfix0_OnCommandFinishedCallback; // 0x1f8
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0x200
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0x208
	private static DelegateBridge __Hotfix0__UnloadUnusedAssets; // 0x210
	private static DelegateBridge __Hotfix0_OnReset; // 0x218
	private static DelegateBridge __Hotfix0_OnSkipBtnClicked; // 0x220
	private static DelegateBridge __Hotfix0_OnAutoBtnClicked; // 0x228
	private static DelegateBridge __Hotfix0_OnSpeedBtnClicked; // 0x230
	private static DelegateBridge __Hotfix0__ShowSpeedImage; // 0x238
	private static DelegateBridge __Hotfix0_OnPlaybackBtnClicked; // 0x240
	private static DelegateBridge __Hotfix0_OnClickPress; // 0x248
	private static DelegateBridge __Hotfix0__CreateQuickPlayNotifyOptions; // 0x250
	private static DelegateBridge __Hotfix0_OnLongPress; // 0x258
	private static DelegateBridge __Hotfix0_SetTheaterMode; // 0x260
	private static DelegateBridge __Hotfix0_TryGetStoryBriefContent; // 0x268
	private static DelegateBridge __Hotfix0__SetTheaterModeStatus; // 0x270
	private static DelegateBridge __Hotfix0__SaveAutoStatus; // 0x278
	private static DelegateBridge __Hotfix0__OnUIInputCommandEnter; // 0x280
	private static DelegateBridge __Hotfix0__OnUIInputCommandExit; // 0x288
	private static DelegateBridge __Hotfix0__LoadAutoStatus; // 0x290
	private static DelegateBridge __Hotfix0_UpdateStorySkipMode; // 0x298
	private static DelegateBridge __Hotfix0__UpdateSkipStatus; // 0x2a0
	private static DelegateBridge __Hotfix0__ShowBriefPanel; // 0x2a8
	private static DelegateBridge __Hotfix0__PauseAuto; // 0x2b0
	private static DelegateBridge __Hotfix0_ResumeAuto; // 0x2b8
	private static DelegateBridge __Hotfix0_OnHideuiBtnClicked; // 0x2c0
	private static DelegateBridge __Hotfix0_OnHideuiResumeClicked; // 0x2c8
	private static DelegateBridge __Hotfix0__DoCacheOriginActiveStates; // 0x2d0
	private static DelegateBridge __Hotfix0_OnInit; // 0x2d8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x2e0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x2e8
	private static DelegateBridge __Hotfix0_TryFetchAndAddCameras; // 0x2f0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x2f8
	private static DelegateBridge __Hotfix1_LoadAsset; // 0x300
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x308
	private static DelegateBridge __Hotfix0_EditorOnlySetAVGEvents; // 0x310
	private static DelegateBridge __Hotfix0__EditorOnlyNotifyCommandExecuted; // 0x318
	private static DelegateBridge __Hotfix0__EditorOnlyNotifyCommandFinished; // 0x320
	private static DelegateBridge __Hotfix0_EditorOnlyAbortRemaineCommands; // 0x328
	private static DelegateBridge _c__Hotfix0_ctor; // 0x330

	public String storyId { get; }
	public AVGStoryCache storyCache { get; }
	public Boolean toastQuickPlay { get; }
	public Boolean isSkippable { get; }
	public AVGAutoMode autoPlayMode { get; set; }
	public Single autoWaitBaseTime { get; }
	public Single autoWaitTimePerText { get; }
	public Single typeWriterDelay { get; }
	public Single animateRatio { get; }
	public Boolean isTheaterMode { get; }
	public Boolean isAutoClickRaised { get; }
	public Boolean isRunning { get; }
	public Boolean isRunningTutorial { get; }
	public Int32 decisionIndex { get; set; }
	public StoryParam storyParam { get; }
	public AVGCanvasLayerHolder canvasHolder { get; }
	public ILoadAsset assetLoader { get; }
	public EventPool`1 eventPool { get; }
	public ResourceRouter router { get; }
	public Camera sceneCamera { get; }

	// RVA: 0x3e4a4c4 VA: 0x75964624c4
	private AVGCompBridge _EnsureCompBridge() { }
	// RVA: 0x3e4a57c VA: 0x759646257c
	private AVGSceneEffectManager _GetOrCreateSceneEffectMgr() { }
	// RVA: 0x3e4a69c VA: 0x759646269c
	public String get_storyId() { }
	// RVA: 0x3e4a730 VA: 0x7596462730
	public AVGStoryCache get_storyCache() { }
	// RVA: 0x3e4a7c8 VA: 0x75964627c8
	public Boolean get_toastQuickPlay() { }
	// RVA: 0x3e4aa08 VA: 0x7596462a08
	public Boolean get_isSkippable() { }
	// RVA: 0x3e4aae4 VA: 0x7596462ae4
	public AVGAutoMode get_autoPlayMode() { }
	// RVA: 0x3e4ab78 VA: 0x7596462b78
	public Void set_autoPlayMode(AVGAutoMode value) { }
	// RVA: 0x3e4aeec VA: 0x7596462eec
	public Single get_autoWaitBaseTime() { }
	// RVA: 0x3e4b038 VA: 0x7596463038
	public Single get_autoWaitTimePerText() { }
	// RVA: 0x3e4b184 VA: 0x7596463184
	public Single get_typeWriterDelay() { }
	// RVA: 0x3e4b2d0 VA: 0x75964632d0
	public Single get_animateRatio() { }
	// RVA: 0x3e4b41c VA: 0x759646341c
	public Boolean get_isTheaterMode() { }
	// RVA: 0x3e4b484 VA: 0x7596463484
	public Boolean get_isAutoClickRaised() { }
	// RVA: 0x3e47c34 VA: 0x759645fc34
	public Boolean get_isRunning() { }
	// RVA: 0x3e4b4f4 VA: 0x75964634f4
	public Boolean get_isRunningTutorial() { }
	// RVA: 0x3e4b574 VA: 0x7596463574
	public Int32 get_decisionIndex() { }
	// RVA: 0x3e4b5dc VA: 0x75964635dc
	public Void set_decisionIndex(Int32 value) { }
	// RVA: 0x3e4b658 VA: 0x7596463658
	public StoryParam get_storyParam() { }
	// RVA: 0x3e4b700 VA: 0x7596463700
	public Void SetCommandPredicator(ICommandPredicator pred) { }
	// RVA: 0x3e4b784 VA: 0x7596463784
	public Void SetCommandFlowController(ICommandFlowController controller) { }
	// RVA: 0x3e4b808 VA: 0x7596463808
	public Void SetCommandSkipController(ICommandSkipController controller) { }
	// RVA: 0x3e4b88c VA: 0x759646388c
	public AVGCanvasLayerHolder get_canvasHolder() { }
	// RVA: 0x3e4a03c VA: 0x759646203c
	public ILoadAsset get_assetLoader() { }
	// RVA: 0x3e48740 VA: 0x7596460740
	public EventPool`1 get_eventPool() { }
	// RVA: 0x3e4a118 VA: 0x7596462118
	public ResourceRouter get_router() { }
	// RVA: 0x3e4b8f4 VA: 0x75964638f4
	public Camera get_sceneCamera() { }
	// RVA: 0x3e47ef0 VA: 0x759645fef0
	public Void RunStory(Story story) { }
	// RVA: 0x3e479e0 VA: 0x759645f9e0
	public Void StopStory(String errorMsg, Boolean isInterrupt) { }
	// RVA: 0x3e4c2fc VA: 0x75964642fc
	protected Void SkipStory() { }
	// RVA: 0x3e4bfc8 VA: 0x7596463fc8
	protected Void EndStory(String errorMsg, Boolean isInterrupt) { }
	// RVA: 0x3e4c838 VA: 0x7596464838
	protected Void OnStoryCommitted(Boolean isOk, StoryOutPut outPut) { }
	// RVA: 0x3e4cbf8 VA: 0x7596464bf8
	public Void SetQuickSpeed(Int32 speed) { }
	// RVA: 0x3e4cca4 VA: 0x7596464ca4
	public Void RaiseAutoClick(Int32 messageLength) { }
	// RVA: 0x3e4cd4c VA: 0x7596464d4c
	public Void RaiseAutoClick(Single delay) { }
	// RVA: 0x3e4cef8 VA: 0x7596464ef8
	public Void RaiseSignal(String command, String signal) { }
	// RVA: 0x3e4d004 VA: 0x7596465004
	public Void RaiseSignal(Command command) { }
	// RVA: 0x3e4d2bc VA: 0x75964652bc
	public Void RegisterExecutor(ICommandExecutor executor) { }
	// RVA: 0x3e4d480 VA: 0x7596465480
	public Void UnregisterExecutor(ICommandExecutor executor) { }
	// RVA: 0x3e4d5d0 VA: 0x75964655d0
	public Void RegisterComponent(AVGComponent component) { }
	// RVA: 0x3e4d784 VA: 0x7596465784
	public Void UnregisterComponent(AVGComponent component) { }
	// RVA: 0x3e4d918 VA: 0x7596465918
	public Void RegisterCommandPostChecker(ICommandPostChecker checker) { }
	// RVA: 0x3e4db08 VA: 0x7596465b08
	public Void UnregisterCommandPostChecker(ICommandPostChecker checker) { }
	// RVA: 0x VA: 0x0
	public T GetAVGComponentOrNull() { }
	// RVA: 0x3e4dc80 VA: 0x7596465c80
	public Void RegisterExtraGameObject(String name, GameObject go) { }
	// RVA: 0x3e4dd2c VA: 0x7596465d2c
	public Void UnregisterExtraGameObject(String name) { }
	// RVA: 0x3e4ddcc VA: 0x7596465dcc
	public GameObject GetExtraGameObject(String name) { }
	// RVA: 0x VA: 0x0
	public TComponent GetExtraGameObject(String name) { }
	// RVA: 0x3e4de7c VA: 0x7596465e7c
	public Boolean TryGetCharSortType(out CharacterSortType charSortType) { }
	// RVA: 0x3e4df20 VA: 0x7596465f20
	private Void _TryShowQuickPlayTip() { }
	// RVA: 0x3e4e1ec VA: 0x75964661ec
	public Boolean IsTutorialWaitSignalMatchedStringParam(String waitSignal, String paramKey, String targetValue) { }
	// RVA: 0x3e4e2ec VA: 0x75964662ec
	protected Boolean _IsTutorialAndWaitSignal(String waitSignal, out Command command) { }
	// RVA: 0x3e4bf1c VA: 0x7596463f1c
	protected IEnumerator DoExecuteCommands() { }
	// RVA: 0x3e4beac VA: 0x7596463eac
	protected Void DoEndStory() { }
	// RVA: 0x3e4ce34 VA: 0x7596464e34
	protected IEnumerator DoAutoClick(Single delay) { }
	// RVA: 0x3e4d1fc VA: 0x75964651fc
	private HashSet`1 _GetCommandExecutors(String command) { }
	// RVA: 0x3e4e490 VA: 0x7596466490
	private HashSet`1 _GetCommandPostCheckers(String command) { }
	// RVA: 0x3e4e54c VA: 0x759646654c
	private Void _PreprocessCommands(IList`1 commands) { }
	// RVA: 0x3e4e858 VA: 0x7596466858
	private Void _InitExecutors() { }
	// RVA: 0x3e4c6ec VA: 0x75964646ec
	private Void _StopAutoClick() { }
	// RVA: 0x3e4b95c VA: 0x759646395c
	private Void _ResetCache() { }
	// RVA: 0x3e4e924 VA: 0x7596466924
	private Void _CacheOriginSizeDeltaOfFitTargetsIfNot() { }
	// RVA: 0x3e4ea40 VA: 0x7596466a40
	private Void _SetupFitMode(FitMode fitMode) { }
	// RVA: 0x3e4ecec VA: 0x7596466cec
	protected Void OnCommandFinishedCallback(ICommandExecutor executor) { }
	// RVA: 0x3e4bccc VA: 0x7596463ccc
	protected Void OnStoryBegin(Story story) { }
	// RVA: 0x3e4ca14 VA: 0x7596464a14
	protected Void OnStoryEnd(Boolean isCommitOk, Story story, Boolean needUnloadAssets) { }
	// RVA: 0x3e4ed8c VA: 0x7596466d8c
	private Void _UnloadUnusedAssets(Story story) { }
	// RVA: 0x3e4bb74 VA: 0x7596463b74
	protected Void OnReset() { }
	// RVA: 0x3e4f040 VA: 0x7596467040
	public Void OnSkipBtnClicked() { }
	// RVA: 0x3e4f368 VA: 0x7596467368
	public Void OnAutoBtnClicked() { }
	// RVA: 0x3e4f400 VA: 0x7596467400
	public Void OnSpeedBtnClicked() { }
	// RVA: 0x3e4ad30 VA: 0x7596462d30
	private Void _ShowSpeedImage() { }
	// RVA: 0x3e4f4fc VA: 0x75964674fc
	public Void OnPlaybackBtnClicked() { }
	// RVA: 0x3e4f66c VA: 0x759646766c
	public Void OnClickPress() { }
	// RVA: 0x3e4e054 VA: 0x7596466054
	private NotifyViewOptions`2 _CreateQuickPlayNotifyOptions(Single duration, Boolean isShowBtn) { }
	// RVA: 0x3e4f7b8 VA: 0x75964677b8
	public Void OnLongPress(Vector2 pos) { }
	// RVA: 0x3e4f940 VA: 0x7596467940
	public Void SetTheaterMode(Boolean value) { }
	// RVA: 0x3e4f9e0 VA: 0x75964679e0
	public String TryGetStoryBriefContent(String storyInfoId) { }
	// RVA: 0x3e4ba14 VA: 0x7596463a14
	private Void _SetTheaterModeStatus() { }
	// RVA: 0x3e4fe18 VA: 0x7596467e18
	private Void _SaveAutoStatus() { }
	// RVA: 0x3e4fed4 VA: 0x7596467ed4
	private Void _OnUIInputCommandEnter() { }
	// RVA: 0x3e4ff6c VA: 0x7596467f6c
	private Void _OnUIInputCommandExit() { }
	// RVA: 0x3e4fc98 VA: 0x7596467c98
	private Void _LoadAutoStatus() { }
	// RVA: 0x3e4c780 VA: 0x7596464780
	public Void UpdateStorySkipMode(SkipNodeLabel node) { }
	// RVA: 0x3e4fbf0 VA: 0x7596467bf0
	private Void _UpdateSkipStatus() { }
	// RVA: 0x3e4f0ec VA: 0x75964670ec
	private Void _ShowBriefPanel(String storyId) { }
	// RVA: 0x3e4f5d4 VA: 0x75964675d4
	private Void _PauseAuto() { }
	// RVA: 0x3e4fd60 VA: 0x7596467d60
	public Void ResumeAuto() { }
	// RVA: 0x3e50004 VA: 0x7596468004
	public Void OnHideuiBtnClicked() { }
	// RVA: 0x3e501ac VA: 0x75964681ac
	public Void OnHideuiResumeClicked() { }
	// RVA: 0x3e4ee98 VA: 0x7596466e98
	private Void _DoCacheOriginActiveStates() { }
	// RVA: 0x3e502a8 VA: 0x75964682a8
	protected override Void OnInit() { }
	// RVA: 0x3e50664 VA: 0x7596468664
	private Void OnEnable() { }
	// RVA: 0x3e506f4 VA: 0x75964686f4
	private Void OnDisable() { }
	// RVA: 0x3e5086c VA: 0x759646886c
	public static Void TryFetchAndAddCameras(List`1 cameras) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x3e50a5c VA: 0x7596468a5c
	public Object LoadAsset(String path) { }
	// RVA: 0x3e50b7c VA: 0x7596468b7c
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x3e50c78 VA: 0x7596468c78
	public Void EditorOnlySetAVGEvents(IAVGEvents avgEvents) { }
	// RVA: 0x3e50cfc VA: 0x7596468cfc
	private Void _EditorOnlyNotifyCommandExecuted(Command cmd) { }
	// RVA: 0x3e50df8 VA: 0x7596468df8
	private Void _EditorOnlyNotifyCommandFinished(Command cmd) { }
	// RVA: 0x3e50ef8 VA: 0x7596468ef8
	public Void EditorOnlyAbortRemaineCommands() { }
	// RVA: 0x3e50f70 VA: 0x7596468f70
	public Void .ctor() { }
	// RVA: 0x3e51340 VA: 0x7596469340
	private Void <EndStory>b__115_0(FinishStoryResponse finishStoryResponse) { }
	// RVA: 0x3e51384 VA: 0x7596469384
	private Boolean <EndStory>b__115_1(ResponseError _) { }
	// RVA: 0x3e513a0 VA: 0x75964693a0
	private Boolean <DoAutoClick>b__139_0() { }
	// RVA: 0x3e513b8 VA: 0x75964693b8
	private Boolean <DoAutoClick>b__139_1() { }
}
```