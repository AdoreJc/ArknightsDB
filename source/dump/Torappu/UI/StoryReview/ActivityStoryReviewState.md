# ActivityStoryReviewState

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `ActivityReviewBinder _activityReviewBinder`

- `StoryReviewStateBean m_stateBean`

- `String m_cachedChapterId`

- `FastExit m_fastExit`


## Methods

- `Void _OnJumpToActivityDetailState(ActivityReviewDetailStateBean)`

- `Void _OnJumpBackFromMiniActivityDetailState(ActivityReviewDetailStateBean)`

- `Void _OnBackClick()`

- `Void _OnChapterClicked(String)`

- `Void _OnChapterRewardGain(String)`

- `Void _RefreshStoryReviewData()`

- `Void <get_cacheHandler>b__8_1(StateRuntime)`

- `Void <OnEnter>b__9_0(GameObject)`

- `Void <RegisterToDataListener>b__10_0(IStateBean)`

- `Void <RegisterFromDataListener>b__12_0(IStateBean)`

- `Void <_OnChapterRewardGain>b__17_0()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityStoryReviewState : PopupFadeState
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private ActivityReviewBinder _activityReviewBinder; // 0x78
	private StoryReviewStateBean m_stateBean; // 0x80
	private String m_cachedChapterId; // 0x88
	private StateCacheHandler`1 m_cacheHandler; // 0x90
	private FastExit m_fastExit; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToActivityDetailState; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpBackFromMiniActivityDetailState; // 0x38
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x40
	private static DelegateBridge __Hotfix0__OnChapterClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnChapterRewardGain; // 0x50
	private static DelegateBridge __Hotfix0__RefreshStoryReviewData; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x274f8d8 VA: 0x7594d678d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x274f940 VA: 0x7594d67940
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x274fb30 VA: 0x7594d67b30
	protected override Void OnEnter() { }
	// RVA: 0x274fd18 VA: 0x7594d67d18
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x274fe90 VA: 0x7594d67e90
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x274ff08 VA: 0x7594d67f08
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2750080 VA: 0x7594d68080
	private Void _OnJumpToActivityDetailState(ActivityReviewDetailStateBean targetBean) { }
	// RVA: 0x2750190 VA: 0x7594d68190
	private Void _OnJumpBackFromMiniActivityDetailState(ActivityReviewDetailStateBean statebean) { }
	// RVA: 0x27502cc VA: 0x7594d682cc
	private Void _OnBackClick() { }
	// RVA: 0x2750398 VA: 0x7594d68398
	private Void _OnChapterClicked(String chapterId) { }
	// RVA: 0x27504d8 VA: 0x7594d684d8
	private Void _OnChapterRewardGain(String chapterId) { }
	// RVA: 0x275086c VA: 0x7594d6886c
	private Void _RefreshStoryReviewData() { }
	// RVA: 0x275097c VA: 0x7594d6897c
	public Void .ctor() { }
	// RVA: 0x2750a64 VA: 0x7594d68a64
	private Void <get_cacheHandler>b__8_1(StateRuntime runtime) { }
	// RVA: 0x2750aac VA: 0x7594d68aac
	private Void <OnEnter>b__9_0(GameObject gameObj) { }
	// RVA: 0x2750ba8 VA: 0x7594d68ba8
	private Void <RegisterToDataListener>b__10_0(IStateBean targetBean) { }
	// RVA: 0x2750c28 VA: 0x7594d68c28
	private Void <RegisterFromDataListener>b__12_0(IStateBean statebean) { }
	// RVA: 0x2750ca8 VA: 0x7594d68ca8
	private Void <_OnChapterRewardGain>b__17_0() { }
	// RVA: 0x2750cac VA: 0x7594d68cac
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x2750cb4 VA: 0x7594d68cb4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2750cbc VA: 0x7594d68cbc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2750cc4 VA: 0x7594d68cc4
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2750ccc VA: 0x7594d68ccc
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```