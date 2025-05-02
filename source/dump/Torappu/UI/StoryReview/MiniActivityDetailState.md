# MiniActivityDetailState

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `MiniReviewDetailBinder _miniStoryDetailBinder`

- `ScrollRect _scrollRect`

- `GameObject _maskPanel`

- `Image _chapterTitleImage`

- `Image _chapterBg`

- `GameObject _trialPanelGo`

- `GameObject _trialWaitingGo`

- `GameObject _trialOpenGo`

- `Text _textTrialCountDown`

- `Text _textTrialCaption`

- `UICommonTrackPoint _newTrialTrackPoint`

- `UICommonTrackPoint _collectTrialTrackPoint`

- `ActivityReviewDetailStateBean m_stateBean`

- `Boolean m_backToStage`

- `FastExit m_fastExit`


## Methods

- `Void _RegisterToReviewState(IStateBean)`

- `Void _OnBackToReviewState(Nullable`1)`

- `Void _UpdateTrialPanel()`

- `Boolean _IsRewardAllCollected(String)`

- `Void OnBtnNavTrial()`

- `Void OnBtnRule()`

- `Void _OnScrollRectTween(Single)`

- `Void _OnBackClick()`

- `Void _OnStoryRead(String)`

- `Void _OnStoryReadSuc()`

- `Void _OnStoryClicked(String)`

- `Void _OnUnlockClicked(String)`

- `Void _OnStoryUnlock(StoryReviewViewModel)`

- `Void _OnStoryUnlocked()`

- `Void <get_cacheHandler>b__20_1(StateRuntime)`

- `Void <OnEnter>b__21_0(GameObject)`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActivityDetailState : PopupFadeState
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private MiniReviewDetailBinder _miniStoryDetailBinder; // 0x78
	private ScrollRect _scrollRect; // 0x80
	private GameObject _maskPanel; // 0x88
	private Image _chapterTitleImage; // 0x90
	private Image _chapterBg; // 0x98
	private GameObject _trialPanelGo; // 0xa0
	private GameObject _trialWaitingGo; // 0xa8
	private GameObject _trialOpenGo; // 0xb0
	private Text _textTrialCountDown; // 0xb8
	private Text _textTrialCaption; // 0xc0
	private UICommonTrackPoint _newTrialTrackPoint; // 0xc8
	private UICommonTrackPoint _collectTrialTrackPoint; // 0xd0
	private ActivityReviewDetailStateBean m_stateBean; // 0xd8
	private Nullable`1 m_showTrial; // 0xe0
	private StateCacheHandler`1 m_cacheHandler; // 0xe8
	private Boolean m_backToStage; // 0xf0
	private FastExit m_fastExit; // 0xf4
	private const Single SCROLL_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__RegisterToReviewState; // 0x20
	private static DelegateBridge __Hotfix0__OnBackToReviewState; // 0x28
	private static DelegateBridge __Hotfix0__UpdateTrialPanel; // 0x30
	private static DelegateBridge __Hotfix0__IsRewardAllCollected; // 0x38
	private static DelegateBridge __Hotfix0_OnBtnNavTrial; // 0x40
	private static DelegateBridge __Hotfix0_OnBtnRule; // 0x48
	private static DelegateBridge __Hotfix0__OnScrollRectTween; // 0x50
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x58
	private static DelegateBridge __Hotfix0__OnStoryRead; // 0x60
	private static DelegateBridge __Hotfix0__OnStoryReadSuc; // 0x68
	private static DelegateBridge __Hotfix0__OnStoryClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnUnlockClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnStoryUnlock; // 0x80
	private static DelegateBridge __Hotfix0__OnStoryUnlocked; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2750d58 VA: 0x7594d68d58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2750dc0 VA: 0x7594d68dc0
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2750fb0 VA: 0x7594d68fb0
	protected override Void OnEnter() { }
	// RVA: 0x2751778 VA: 0x7594d69778
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27518f0 VA: 0x7594d698f0
	private Void _RegisterToReviewState(IStateBean stateBean) { }
	// RVA: 0x2751a5c VA: 0x7594d69a5c
	private Void _OnBackToReviewState(Nullable`1 showTrial) { }
	// RVA: 0x27513f8 VA: 0x7594d693f8
	private Void _UpdateTrialPanel() { }
	// RVA: 0x2751b50 VA: 0x7594d69b50
	private Boolean _IsRewardAllCollected(String actId) { }
	// RVA: 0x2751db4 VA: 0x7594d69db4
	public Void OnBtnNavTrial() { }
	// RVA: 0x2751e58 VA: 0x7594d69e58
	public Void OnBtnRule() { }
	// RVA: 0x2751f60 VA: 0x7594d69f60
	private Void _OnScrollRectTween(Single pos) { }
	// RVA: 0x2751fe8 VA: 0x7594d69fe8
	private Void _OnBackClick() { }
	// RVA: 0x2752080 VA: 0x7594d6a080
	private Void _OnStoryRead(String storyId) { }
	// RVA: 0x275214c VA: 0x7594d6a14c
	private Void _OnStoryReadSuc() { }
	// RVA: 0x2752214 VA: 0x7594d6a214
	private Void _OnStoryClicked(String storyTextId) { }
	// RVA: 0x27523bc VA: 0x7594d6a3bc
	private Void _OnUnlockClicked(String storyId) { }
	// RVA: 0x27526a0 VA: 0x7594d6a6a0
	private Void _OnStoryUnlock(StoryReviewViewModel viewModel) { }
	// RVA: 0x275276c VA: 0x7594d6a76c
	private Void _OnStoryUnlocked() { }
	// RVA: 0x2752844 VA: 0x7594d6a844
	public Void .ctor() { }
	// RVA: 0x27528f4 VA: 0x7594d6a8f4
	private Void <get_cacheHandler>b__20_1(StateRuntime runtime) { }
	// RVA: 0x2752938 VA: 0x7594d6a938
	private Void <OnEnter>b__21_0(GameObject gameObj) { }
	// RVA: 0x2752a34 VA: 0x7594d6aa34
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x2752a3c VA: 0x7594d6aa3c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2752a44 VA: 0x7594d6aa44
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```