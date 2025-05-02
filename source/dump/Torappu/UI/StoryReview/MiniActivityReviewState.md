# MiniActivityReviewState

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `RectTransform _reviewPanelParent`

- `RectTransform _trialPanelParent`

- `MiniActDisplayBinderView _displayBinder`

- `MiniActTrialBinderView _trailBinderViewPrefab`

- `MiniActReviewBinderView _reviewBinderViewPrefab`

- `MiniActReviewStateBean m_stateBean`

- `MiniActReviewBinderView m_reviewBinderView`

- `MiniActTrialBinderView m_trialBinderView`

- `String m_cachedChapterId`

- `Boolean m_isInited`

- `Boolean m_backToStage`

- `FastExit m_fastExit`


## Methods

- `Void _SetViewAsTrail()`

- `Void _SetViewAsNormal()`

- `Void _InitPanelIfNot()`

- `Void _OnJumpBackFromMiniActivityDetailState(ActivityReviewDetailStateBean)`

- `Void _OnJumpToActivityDetailState(ActivityReviewDetailStateBean)`

- `Void _UpdateProp()`

- `Void _UpdateCollectTrialTrackPoint()`

- `Void _SetAvailTrialVisited()`

- `Void _OnBtnRule()`

- `Void _OnBtnTrial()`

- `Void _OnBtnReview()`

- `Void _OnBackClick()`

- `Void _OnChapterClicked(String)`

- `Void _OnChapterRewardGain(String)`

- `Void _OnTrialRewardCollect(String, List`1)`

- `Void _SendCollectTrialReward(String, List`1, Action)`

- `Void _RefreshStoryReviewData()`

- `Void <get_cacheHandler>b__16_1(StateRuntime)`

- `IEnumerator <>n__0()`

- `Void <OnEnter>b__21_0(GameObject)`

- `Void <RegisterToDataListener>b__22_0(IStateBean)`

- `Void <RegisterFromDataListener>b__24_0(IStateBean)`

- `Void <_OnChapterRewardGain>b__35_0()`

- `Void <_OnTrialRewardCollect>b__36_0()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `IEnumerator <>xLuaBaseProxy_OnPreload()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActivityReviewState : PopupFadeState
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private RectTransform _reviewPanelParent; // 0x78
	private RectTransform _trialPanelParent; // 0x80
	private MiniActDisplayBinderView _displayBinder; // 0x88
	private MiniActTrialBinderView _trailBinderViewPrefab; // 0x90
	private MiniActReviewBinderView _reviewBinderViewPrefab; // 0x98
	private MiniActReviewStateBean m_stateBean; // 0xa0
	private MiniActReviewBinderView m_reviewBinderView; // 0xa8
	private MiniActTrialBinderView m_trialBinderView; // 0xb0
	private String m_cachedChapterId; // 0xb8
	private Boolean m_isInited; // 0xc0
	private StateCacheHandler`1 m_cacheHandler; // 0xc8
	private Boolean m_backToStage; // 0xd0
	private FastExit m_fastExit; // 0xd4
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x8
	private static DelegateBridge __Hotfix0__SetViewAsTrail; // 0x10
	private static DelegateBridge __Hotfix0__SetViewAsNormal; // 0x18
	private static DelegateBridge __Hotfix0_OnPreload; // 0x20
	private static DelegateBridge __Hotfix0__InitPanelIfNot; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x38
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x40
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x48
	private static DelegateBridge __Hotfix0__OnJumpBackFromMiniActivityDetailState; // 0x50
	private static DelegateBridge __Hotfix0__OnJumpToActivityDetailState; // 0x58
	private static DelegateBridge __Hotfix0__UpdateProp; // 0x60
	private static DelegateBridge __Hotfix0__UpdateCollectTrialTrackPoint; // 0x68
	private static DelegateBridge __Hotfix0__SetAvailTrialVisited; // 0x70
	private static DelegateBridge __Hotfix0__OnBtnRule; // 0x78
	private static DelegateBridge __Hotfix0__OnBtnTrial; // 0x80
	private static DelegateBridge __Hotfix0__OnBtnReview; // 0x88
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x90
	private static DelegateBridge __Hotfix0__OnChapterClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnChapterRewardGain; // 0xa0
	private static DelegateBridge __Hotfix0__OnTrialRewardCollect; // 0xa8
	private static DelegateBridge __Hotfix0__SendCollectTrialReward; // 0xb0
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0__RefreshStoryReviewData; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2752af0 VA: 0x7594d6aaf0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2752b58 VA: 0x7594d6ab58
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2752d48 VA: 0x7594d6ad48
	private Void _SetViewAsTrail() { }
	// RVA: 0x2752f14 VA: 0x7594d6af14
	private Void _SetViewAsNormal() { }
	// RVA: 0x27530d8 VA: 0x7594d6b0d8
	protected override IEnumerator OnPreload() { }
	// RVA: 0x27531ac VA: 0x7594d6b1ac
	private Void _InitPanelIfNot() { }
	// RVA: 0x27532cc VA: 0x7594d6b2cc
	protected override Void OnEnter() { }
	// RVA: 0x2753aac VA: 0x7594d6baac
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2753c24 VA: 0x7594d6bc24
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2753c9c VA: 0x7594d6bc9c
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2753e14 VA: 0x7594d6be14
	private Void _OnJumpBackFromMiniActivityDetailState(ActivityReviewDetailStateBean statebean) { }
	// RVA: 0x2754054 VA: 0x7594d6c054
	private Void _OnJumpToActivityDetailState(ActivityReviewDetailStateBean targetBean) { }
	// RVA: 0x2753ea4 VA: 0x7594d6bea4
	private Void _UpdateProp() { }
	// RVA: 0x2753904 VA: 0x7594d6b904
	private Void _UpdateCollectTrialTrackPoint() { }
	// RVA: 0x275415c VA: 0x7594d6c15c
	private Void _SetAvailTrialVisited() { }
	// RVA: 0x2754248 VA: 0x7594d6c248
	private Void _OnBtnRule() { }
	// RVA: 0x2754350 VA: 0x7594d6c350
	private Void _OnBtnTrial() { }
	// RVA: 0x2754610 VA: 0x7594d6c610
	private Void _OnBtnReview() { }
	// RVA: 0x2754690 VA: 0x7594d6c690
	private Void _OnBackClick() { }
	// RVA: 0x2754764 VA: 0x7594d6c764
	private Void _OnChapterClicked(String chapterId) { }
	// RVA: 0x27548a8 VA: 0x7594d6c8a8
	private Void _OnChapterRewardGain(String chapterId) { }
	// RVA: 0x27549b8 VA: 0x7594d6c9b8
	private Void _OnTrialRewardCollect(String storyId, List`1 rewardIdList) { }
	// RVA: 0x2754a94 VA: 0x7594d6ca94
	private Void _SendCollectTrialReward(String groupId, List`1 rewardIdList, Action onSucc) { }
	// RVA: 0x2754d38 VA: 0x7594d6cd38
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x2754e0c VA: 0x7594d6ce0c
	private Void _RefreshStoryReviewData() { }
	// RVA: 0x2754eb0 VA: 0x7594d6ceb0
	public Void .ctor() { }
	// RVA: 0x2754f98 VA: 0x7594d6cf98
	private Void <get_cacheHandler>b__16_1(StateRuntime runtime) { }
	// RVA: 0x2755008 VA: 0x7594d6d008
	private IEnumerator <>n__0() { }
	// RVA: 0x2755010 VA: 0x7594d6d010
	private Void <OnEnter>b__21_0(GameObject gameObj) { }
	// RVA: 0x275510c VA: 0x7594d6d10c
	private Void <RegisterToDataListener>b__22_0(IStateBean targetBean) { }
	// RVA: 0x275518c VA: 0x7594d6d18c
	private Void <RegisterFromDataListener>b__24_0(IStateBean statebean) { }
	// RVA: 0x275520c VA: 0x7594d6d20c
	private Void <_OnChapterRewardGain>b__35_0() { }
	// RVA: 0x2755210 VA: 0x7594d6d210
	private Void <_OnTrialRewardCollect>b__36_0() { }
	// RVA: 0x2755214 VA: 0x7594d6d214
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x275521c VA: 0x7594d6d21c
	private IEnumerator <>xLuaBaseProxy_OnPreload() { }
	// RVA: 0x2755224 VA: 0x7594d6d224
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x275522c VA: 0x7594d6d22c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2755234 VA: 0x7594d6d234
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x275523c VA: 0x7594d6d23c
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```