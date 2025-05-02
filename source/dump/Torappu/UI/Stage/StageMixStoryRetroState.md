# StageMixStoryRetroState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageMixStoryRetroView _view`

- `CanvasGroup _rootCanvasGroup`

- `UIAnimationLocation _inAnimation`

- `GameObject _tutorialContentPanel`

- `GameObject _tutorialSwitchPanel`

- `RectTransform _topMenuContainer`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `StageStateBean m_stageStateBean`

- `StagePageGameMusicController m_musicController`

- `MixStoryGroupViewProperty m_mixStoryProperty`

- `AnimationSwitchTween m_inTween`

- `StageStorylineSSViewModel m_cachedUnlockRetroModel`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnToStoriesEvent()`

- `Void _OnToReopenActEvent()`

- `Void _OnToRetroTrailEvent()`

- `Void _OpenRetroTrailAsSS(StageStorylineSSViewModel)`

- `Void _OpenRetroTrailAsCollect(StageStorylineCollectViewModel)`

- `Void _OnToZoneMapEvent()`

- `Void _OnUnlockRetro()`

- `Void _SendUnlockRetroService()`

- `Void _UnlockRetroServiceProceed(RetroUnlockRetroBlockResponse)`

- `Void _OnToRetroCoinDetail()`

- `Void _OnSwitchRetro(String)`

- `Void _CacheHandleOnLoad(StateRuntime)`

- `Void _Tutorial_RegisterGO()`

- `Int64 _GetBGMInstId()`

- `Void _RefreshBGM()`

- `Void _ClearBGM()`

- `String _FindMusicId()`

- `Void _InitIfNot()`

- `Void _EventOnBackBtnClicked()`

- `Void _TutorialTriggerSignalIfNeed()`

- `IEnumerator _Tutorial_WaitToTriggerSignal()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMixStoryRetroState : UIPopupState, IValueMsgReceiver
{
	private const Single FADE_DURATION; // 0x0
	public const Int32 MSG_TO_STORIES; // 0x0
	public const Int32 MSG_TO_REOPEN_ACT; // 0x0
	public const Int32 MSG_TO_RETRO_TRAIL; // 0x0
	public const Int32 MSG_TO_ZONE_MAP; // 0x0
	public const Int32 MSG_UNLOCK_RETRO; // 0x0
	public const Int32 MSG_TO_RETRO_COIN_DETAIL; // 0x0
	public const Int32 MSG_SWITCH_RETRO; // 0x0
	private StageMixStoryRetroView _view; // 0x60
	private CanvasGroup _rootCanvasGroup; // 0x68
	private UIAnimationLocation _inAnimation; // 0x70
	private GameObject _tutorialContentPanel; // 0x80
	private GameObject _tutorialSwitchPanel; // 0x88
	private RectTransform _topMenuContainer; // 0x90
	private Boolean m_hasInited; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private StageStateBean m_stageStateBean; // 0xb0
	private StagePageGameMusicController m_musicController; // 0xb8
	private MixStoryGroupViewProperty m_mixStoryProperty; // 0xc0
	private AnimationSwitchTween m_inTween; // 0xc8
	private StageStorylineSSViewModel m_cachedUnlockRetroModel; // 0xd0
	private StateCacheHandler`1 m_cacheHandler; // 0xd8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x0
	private static DelegateBridge __Hotfix0__OnToStoriesEvent; // 0x8
	private static DelegateBridge __Hotfix0__OnToReopenActEvent; // 0x10
	private static DelegateBridge __Hotfix0__OnToRetroTrailEvent; // 0x18
	private static DelegateBridge __Hotfix0__OpenRetroTrailAsSS; // 0x20
	private static DelegateBridge __Hotfix0__OpenRetroTrailAsCollect; // 0x28
	private static DelegateBridge __Hotfix0__OnToZoneMapEvent; // 0x30
	private static DelegateBridge __Hotfix0__OnUnlockRetro; // 0x38
	private static DelegateBridge __Hotfix0__SendUnlockRetroService; // 0x40
	private static DelegateBridge __Hotfix0__UnlockRetroServiceProceed; // 0x48
	private static DelegateBridge __Hotfix0__OnToRetroCoinDetail; // 0x50
	private static DelegateBridge __Hotfix0__OnSwitchRetro; // 0x58
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x60
	private static DelegateBridge __Hotfix0__CacheHandleOnLoad; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x70
	private static DelegateBridge __Hotfix0_OnEnter; // 0x78
	private static DelegateBridge __Hotfix0_OnPause; // 0x80
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x88
	private static DelegateBridge __Hotfix0_OnResume; // 0x90
	private static DelegateBridge __Hotfix0_OnExit; // 0x98
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0xa0
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0xa8
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0xb0
	private static DelegateBridge __Hotfix0_HideImmediately; // 0xb8
	private static DelegateBridge __Hotfix0__Tutorial_RegisterGO; // 0xc0
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0xc8
	private static DelegateBridge __Hotfix0__RefreshBGM; // 0xd0
	private static DelegateBridge __Hotfix0__ClearBGM; // 0xd8
	private static DelegateBridge __Hotfix0__FindMusicId; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xe8
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0xf0
	private static DelegateBridge __Hotfix0__TutorialTriggerSignalIfNeed; // 0xf8
	private static DelegateBridge __Hotfix0__Tutorial_WaitToTriggerSignal; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2f671d0 VA: 0x759557f1d0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f67324 VA: 0x759557f324
	private Void _OnToStoriesEvent() { }
	// RVA: 0x2f675cc VA: 0x759557f5cc
	private Void _OnToReopenActEvent() { }
	// RVA: 0x2f6778c VA: 0x759557f78c
	private Void _OnToRetroTrailEvent() { }
	// RVA: 0x2f68494 VA: 0x7595580494
	private Void _OpenRetroTrailAsSS(StageStorylineSSViewModel model) { }
	// RVA: 0x2f685b4 VA: 0x75955805b4
	private Void _OpenRetroTrailAsCollect(StageStorylineCollectViewModel model) { }
	// RVA: 0x2f6795c VA: 0x759557f95c
	private Void _OnToZoneMapEvent() { }
	// RVA: 0x2f67eac VA: 0x759557feac
	private Void _OnUnlockRetro() { }
	// RVA: 0x2f686d0 VA: 0x75955806d0
	private Void _SendUnlockRetroService() { }
	// RVA: 0x2f688cc VA: 0x75955808cc
	private Void _UnlockRetroServiceProceed(RetroUnlockRetroBlockResponse response) { }
	// RVA: 0x2f6827c VA: 0x759558027c
	private Void _OnToRetroCoinDetail() { }
	// RVA: 0x2f6835c VA: 0x759558035c
	private Void _OnSwitchRetro(String storySetId) { }
	// RVA: 0x2f68b1c VA: 0x7595580b1c
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2f68d0c VA: 0x7595580d0c
	private Void _CacheHandleOnLoad(StateRuntime runtime) { }
	// RVA: 0x2f68e88 VA: 0x7595580e88
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f68eec VA: 0x7595580eec
	protected override Void OnEnter() { }
	// RVA: 0x2f69434 VA: 0x7595581434
	protected override Void OnPause() { }
	// RVA: 0x2f6954c VA: 0x759558154c
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2f69678 VA: 0x7595581678
	protected override Void OnResume() { }
	// RVA: 0x2f6978c VA: 0x759558178c
	protected override Void OnExit() { }
	// RVA: 0x2f698b0 VA: 0x75955818b0
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2f69a28 VA: 0x7595581a28
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2f69ba0 VA: 0x7595581ba0
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2f69ddc VA: 0x7595581ddc
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2f69338 VA: 0x7595581338
	private Void _Tutorial_RegisterGO() { }
	// RVA: 0x2f69f0c VA: 0x7595581f0c
	private Int64 _GetBGMInstId() { }
	// RVA: 0x2f68a78 VA: 0x7595580a78
	private Void _RefreshBGM() { }
	// RVA: 0x2f69828 VA: 0x7595581828
	private Void _ClearBGM() { }
	// RVA: 0x2f69f80 VA: 0x7595581f80
	private String _FindMusicId() { }
	// RVA: 0x2f68fd0 VA: 0x7595580fd0
	private Void _InitIfNot() { }
	// RVA: 0x2f6a07c VA: 0x759558207c
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x2f69cd8 VA: 0x7595581cd8
	private Void _TutorialTriggerSignalIfNeed() { }
	// RVA: 0x2f6a120 VA: 0x7595582120
	private IEnumerator _Tutorial_WaitToTriggerSignal() { }
	// RVA: 0x2f6a1f4 VA: 0x75955821f4
	public Void .ctor() { }
	// RVA: 0x2f6a264 VA: 0x7595582264
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x2f6a26c VA: 0x759558226c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f6a274 VA: 0x7595582274
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2f6a27c VA: 0x759558227c
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2f6a288 VA: 0x7595582288
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2f6a290 VA: 0x7595582290
	private Void <>xLuaBaseProxy_OnExit() { }
}
```