# SandboxV2DungeonPage

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonController _dungeonController`

- `SandboxV2DungeonCameraController _cameraController`

- `SandboxV2DungeonAVGAdapter _avgAdapter`

- `GameObject _cameraHolder`

- `GameObject _cameraUIHolder`

- `CanvasGroup _canvasUI`

- `CanvasGroup _canvasMask`

- `RectTransform _dialogContainer`

- `Boolean m_inited`

- `Param m_param`

- `DataBundle m_savedInst`

- `UISwitchTween m_maskShowTween`

- `UICompDialogMgr m_dialogMgr`

- `Boolean m_skipDungeonPage`

- `Int32 m_cachedDungeonDay`

- `Int64 m_cachedDungeonReadArchiveTs`

- `Int32 m_cameraInactiveFlag`

- `Boolean m_isPlayerDataReady`


## Properties

- `String topicId`

- `Boolean isMonth`

- `Boolean fromReadArchive`

- `String monthlyRushId`

- `UICompDialogMgr dialogMgr`


## Methods

- `String get_topicId()`

- `Boolean get_isMonth()`

- `Boolean get_fromReadArchive()`

- `String get_monthlyRushId()`

- `UICompDialogMgr get_dialogMgr()`

- `Void _InitIfNot()`

- `Void SetCameraActiveByStateTransition(Boolean, Type)`

- `Void _SetCameraActive(Boolean, CameraActiveSrc)`

- `Void _DisplayDungeon(Boolean)`

- `Void _ReloadDungeon(Boolean)`

- `String GetTopicId()`

- `IEnumerator _RouteToMonthModeState()`

- `IEnumerator _RouteToCrossDayPage(Boolean, Boolean, Boolean)`

- `Void _ClearDungeonIfNecessary()`

- `Void _TrySendTutorialOnlyLoadArchiveRequest(String)`

- `Void _TriggerSandboxV2BGM()`

- `Void _ClearBGM()`

- `Int32 _GetBGMInstId()`

- `Void _TriggerTutorial()`

- `Boolean _ValidateSandboxV2GuideQuest(String, Story)`

- `Void _TriggerSandboxV2DungeonGuideQuest()`

- `Void _OnSandboxV2DungeonGuideQuestCompleted(Story)`

- `Void EnableMobileTouch(Boolean)`

- `IEnumerator <>n__0()`

- `Boolean <EffectsOnShow>b__43_0()`

- `Boolean <EffectsOnHide>b__44_0()`

- `Boolean <EffectsOnHide>b__44_1()`

- `Void <_TrySendTutorialOnlyLoadArchiveRequest>b__48_0(SandboxV2GuideLoadResponse)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Boolean <>xLuaBaseProxy_CustomSetActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonPage : StateEnginePage, ISandboxV2TopicIdHolder, IMobileTouchPage, IHotfixable, ISandboxV2DialogHolder
{
	private SandboxV2DungeonController _dungeonController; // 0xe8
	private SandboxV2DungeonCameraController _cameraController; // 0xf0
	private SandboxV2DungeonAVGAdapter _avgAdapter; // 0xf8
	private GameObject _cameraHolder; // 0x100
	private GameObject _cameraUIHolder; // 0x108
	private CanvasGroup[] _rootCanvasGroups; // 0x110
	private CanvasGroup _canvasUI; // 0x118
	private CanvasGroup _canvasMask; // 0x120
	private RectTransform _dialogContainer; // 0x128
	private Boolean m_inited; // 0x130
	private Param m_param; // 0x138
	private DataBundle m_savedInst; // 0x140
	private UISwitchTween m_maskShowTween; // 0x148
	private UICompDialogMgr m_dialogMgr; // 0x150
	private Boolean m_skipDungeonPage; // 0x158
	private Int32 m_cachedDungeonDay; // 0x15c
	private Int64 m_cachedDungeonReadArchiveTs; // 0x160
	private List`1 m_cameraActiveHandlers; // 0x168
	private Int32 m_cameraInactiveFlag; // 0x170
	private Boolean m_isPlayerDataReady; // 0x174
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_isMonth; // 0x8
	private static DelegateBridge __Hotfix0_get_fromReadArchive; // 0x10
	private static DelegateBridge __Hotfix0_get_monthlyRushId; // 0x18
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_SetCameraActiveByStateTransition; // 0x30
	private static DelegateBridge __Hotfix0__SetCameraActive; // 0x38
	private static DelegateBridge __Hotfix0__DisplayDungeon; // 0x40
	private static DelegateBridge __Hotfix0__ReloadDungeon; // 0x48
	private static DelegateBridge __Hotfix0_GetTopicId; // 0x50
	private static DelegateBridge __Hotfix0_OnCreate; // 0x58
	private static DelegateBridge __Hotfix0_OnStart; // 0x60
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x68
	private static DelegateBridge __Hotfix0__RouteToMonthModeState; // 0x70
	private static DelegateBridge __Hotfix0__RouteToCrossDayPage; // 0x78
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x80
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x88
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x90
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x98
	private static DelegateBridge __Hotfix0__ClearDungeonIfNecessary; // 0xa0
	private static DelegateBridge __Hotfix0__TrySendTutorialOnlyLoadArchiveRequest; // 0xa8
	private static DelegateBridge __Hotfix0__TriggerSandboxV2BGM; // 0xb0
	private static DelegateBridge __Hotfix0__ClearBGM; // 0xb8
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0xc0
	private static DelegateBridge __Hotfix0__TriggerTutorial; // 0xc8
	private static DelegateBridge __Hotfix0__ValidateSandboxV2GuideQuest; // 0xd0
	private static DelegateBridge __Hotfix0__TriggerSandboxV2DungeonGuideQuest; // 0xd8
	private static DelegateBridge __Hotfix0__OnSandboxV2DungeonGuideQuestCompleted; // 0xe0
	private static DelegateBridge __Hotfix0_EnableMobileTouch; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public String topicId { get; }
	public Boolean isMonth { get; }
	public Boolean fromReadArchive { get; }
	public String monthlyRushId { get; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x253c858 VA: 0x7594b54858
	public String get_topicId() { }
	// RVA: 0x253c92c VA: 0x7594b5492c
	public Boolean get_isMonth() { }
	// RVA: 0x253c9e0 VA: 0x7594b549e0
	public Boolean get_fromReadArchive() { }
	// RVA: 0x253ca78 VA: 0x7594b54a78
	public String get_monthlyRushId() { }
	// RVA: 0x253cb30 VA: 0x7594b54b30
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x253cb98 VA: 0x7594b54b98
	private Void _InitIfNot() { }
	// RVA: 0x253cc68 VA: 0x7594b54c68
	public Void SetCameraActiveByStateTransition(Boolean active, Type stateType) { }
	// RVA: 0x253ce08 VA: 0x7594b54e08
	private Void _SetCameraActive(Boolean active, CameraActiveSrc src) { }
	// RVA: 0x253ceb8 VA: 0x7594b54eb8
	private Void _DisplayDungeon(Boolean isShow) { }
	// RVA: 0x253cf60 VA: 0x7594b54f60
	private Void _ReloadDungeon(Boolean isFromStack) { }
	// RVA: 0x253d0a8 VA: 0x7594b550a8
	public String GetTopicId() { }
	// RVA: 0x253d110 VA: 0x7594b55110
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x253d218 VA: 0x7594b55218
	protected override Void OnStart() { }
	// RVA: 0x253d76c VA: 0x7594b5576c
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x253d840 VA: 0x7594b55840
	private IEnumerator _RouteToMonthModeState() { }
	// RVA: 0x253d914 VA: 0x7594b55914
	private IEnumerator _RouteToCrossDayPage(Boolean isReadArchive, Boolean isRiftSettle, Boolean isChallengeSettle) { }
	// RVA: 0x253da30 VA: 0x7594b55a30
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x253db20 VA: 0x7594b55b20
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x253dc10 VA: 0x7594b55c10
	protected override Void OnDestroy() { }
	// RVA: 0x253dd2c VA: 0x7594b55d2c
	public override Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x253de88 VA: 0x7594b55e88
	private Void _ClearDungeonIfNecessary() { }
	// RVA: 0x253d2f8 VA: 0x7594b552f8
	private Void _TrySendTutorialOnlyLoadArchiveRequest(String topicId) { }
	// RVA: 0x253d548 VA: 0x7594b55548
	private Void _TriggerSandboxV2BGM() { }
	// RVA: 0x253dc84 VA: 0x7594b55c84
	private Void _ClearBGM() { }
	// RVA: 0x253e0f4 VA: 0x7594b560f4
	private Int32 _GetBGMInstId() { }
	// RVA: 0x253dff8 VA: 0x7594b55ff8
	private Void _TriggerTutorial() { }
	// RVA: 0x253e2e8 VA: 0x7594b562e8
	private Boolean _ValidateSandboxV2GuideQuest(String topicId, Story story) { }
	// RVA: 0x253e160 VA: 0x7594b56160
	private Void _TriggerSandboxV2DungeonGuideQuest() { }
	// RVA: 0x253e4c4 VA: 0x7594b564c4
	private Void _OnSandboxV2DungeonGuideQuestCompleted(Story story) { }
	// RVA: 0x253e5b0 VA: 0x7594b565b0
	public Void EnableMobileTouch(Boolean enable) { }
	// RVA: 0x253e644 VA: 0x7594b56644
	public Void .ctor() { }
	// RVA: 0x253e718 VA: 0x7594b56718
	private IEnumerator <>n__0() { }
	// RVA: 0x253e720 VA: 0x7594b56720
	private Boolean <EffectsOnShow>b__43_0() { }
	// RVA: 0x253e73c VA: 0x7594b5673c
	private Boolean <EffectsOnHide>b__44_0() { }
	// RVA: 0x253e758 VA: 0x7594b56758
	private Boolean <EffectsOnHide>b__44_1() { }
	// RVA: 0x253e774 VA: 0x7594b56774
	private Void <_TrySendTutorialOnlyLoadArchiveRequest>b__48_0(SandboxV2GuideLoadResponse response) { }
	// RVA: 0x253e794 VA: 0x7594b56794
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x253e79c VA: 0x7594b5679c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x253e7a4 VA: 0x7594b567a4
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x253e7ac VA: 0x7594b567ac
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x253e7b8 VA: 0x7594b567b8
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x253e7c4 VA: 0x7594b567c4
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x253e7cc VA: 0x7594b567cc
	private Boolean <>xLuaBaseProxy_CustomSetActive(Boolean P0) { }
}
```