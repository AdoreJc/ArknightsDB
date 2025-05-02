# ActivityStoryDetailState

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `ActivityReviewDetailBinder _activityStoryDetailBinder`

- `LoopVerticalScrollRect _scrollRect`

- `GameObject _maskPanel`

- `Image _blurBackground`

- `Image _chapterImage`

- `ActivityReviewDetailStateBean m_stateBean`

- `UIPageFinder m_pageFinder`

- `Single m_startScrollPos`

- `Boolean m_backToStage`

- `FastExit m_fastExit`


## Methods

- `Void _OnScrollRectTween(Single)`

- `Void _OnBackClick()`

- `Void _OnStoryRead(String)`

- `Void _OnStoryReadSuc()`

- `Void _OnStoryClicked(String)`

- `Void _OnUnlockClicked(String)`

- `Void _OnStoryUnlock(StoryReviewViewModel)`

- `Void _OnStoryUnlocked()`

- `Void _OnBlurShot()`

- `Void _OnScrollReset()`

- `Void <get_cacheHandler>b__15_1(StateRuntime)`

- `Void <OnEnter>b__16_0(GameObject)`

- `Single <_OnScrollRectTween>b__17_0()`

- `Void <_OnScrollRectTween>b__17_1(Single)`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityStoryDetailState : PopupFadeState
{
	private const Single DEFAULT_SCROLL_POS; // 0x0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private ActivityReviewDetailBinder _activityStoryDetailBinder; // 0x78
	private LoopVerticalScrollRect _scrollRect; // 0x80
	private GameObject _maskPanel; // 0x88
	private Image _blurBackground; // 0x90
	private Image _chapterImage; // 0x98
	private ActivityReviewDetailStateBean m_stateBean; // 0xa0
	private UIPageFinder m_pageFinder; // 0xa8
	private StateCacheHandler`1 m_cacheHandler; // 0xb8
	private Single m_startScrollPos; // 0xc0
	private Boolean m_backToStage; // 0xc4
	private FastExit m_fastExit; // 0xc8
	private const Single SCROLL_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__OnScrollRectTween; // 0x18
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x20
	private static DelegateBridge __Hotfix0__OnStoryRead; // 0x28
	private static DelegateBridge __Hotfix0__OnStoryReadSuc; // 0x30
	private static DelegateBridge __Hotfix0__OnStoryClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnUnlockClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnStoryUnlock; // 0x48
	private static DelegateBridge __Hotfix0__OnStoryUnlocked; // 0x50
	private static DelegateBridge __Hotfix0__OnBlurShot; // 0x58
	private static DelegateBridge __Hotfix0__OnScrollReset; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x274de5c VA: 0x7594d65e5c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x274dec4 VA: 0x7594d65ec4
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x274e0b4 VA: 0x7594d660b4
	protected override Void OnEnter() { }
	// RVA: 0x274e340 VA: 0x7594d66340
	private Void _OnScrollRectTween(Single pos) { }
	// RVA: 0x274e4b4 VA: 0x7594d664b4
	private Void _OnBackClick() { }
	// RVA: 0x274e5b8 VA: 0x7594d665b8
	private Void _OnStoryRead(String storyId) { }
	// RVA: 0x274e8ac VA: 0x7594d668ac
	private Void _OnStoryReadSuc() { }
	// RVA: 0x274e974 VA: 0x7594d66974
	private Void _OnStoryClicked(String storyId) { }
	// RVA: 0x274ee1c VA: 0x7594d66e1c
	private Void _OnUnlockClicked(String storyId) { }
	// RVA: 0x274f034 VA: 0x7594d67034
	private Void _OnStoryUnlock(StoryReviewViewModel viewModel) { }
	// RVA: 0x274f430 VA: 0x7594d67430
	private Void _OnStoryUnlocked() { }
	// RVA: 0x274f4f8 VA: 0x7594d674f8
	private Void _OnBlurShot() { }
	// RVA: 0x274f5ac VA: 0x7594d675ac
	private Void _OnScrollReset() { }
	// RVA: 0x274f624 VA: 0x7594d67624
	public Void .ctor() { }
	// RVA: 0x274f6dc VA: 0x7594d676dc
	private Void <get_cacheHandler>b__15_1(StateRuntime runtime) { }
	// RVA: 0x274f6f0 VA: 0x7594d676f0
	private Void <OnEnter>b__16_0(GameObject gameObj) { }
	// RVA: 0x274f7ec VA: 0x7594d677ec
	private Single <_OnScrollRectTween>b__17_0() { }
	// RVA: 0x274f808 VA: 0x7594d67808
	private Void <_OnScrollRectTween>b__17_1(Single val) { }
	// RVA: 0x274f824 VA: 0x7594d67824
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x274f82c VA: 0x7594d6782c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```