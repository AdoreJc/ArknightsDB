# Act12D6GameEndState

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `AnimationWrapper _animationWrapper`

- `AnimationWrapper _modeFactorWrapper`

- `Act12D6GameEndScoreObjView _totalScoreObjView`

- `Act12D6GameEndScoreObjView _outbuffTokenCountView`

- `Act12D6GameEndScoreObjView _milestoneTokenCountView`

- `Act12d6GameEndTitleView _titleView`

- `Act12D6GameEndStatsView _statsView`

- `Act12D6GameEndRewardView _rewardView`

- `Act12D6GameEndUnlockView _unlockView`

- `Image _imageBkg`

- `UIFullScreenImage _imageBlurBkg`

- `Image _imageCornerSuc`

- `Image _imageCornerFail`

- `Act12D6GameEndStateBean m_stateBean`

- `InternalState m_state`

- `Coroutine m_updateCoroutine`

- `Boolean m_isNextClicked`

- `Boolean m_isBackClicked`


## Methods

- `Void EventOnNextClicked()`

- `Void EventOnBackClicked()`

- `Void _AnimationEventOnPlayAudio(String)`

- `Void _AnimationEventOnShotBlurBkg()`

- `Void _AnimationEventOnEnableRewardView()`

- `Void _AnimationEventOnPlayScoreObjAnim(Int32)`

- `Void _AnimationEventOnPlayModeFactor()`

- `Void _AnimationEventOnPlayTotalScore()`

- `Void _AnimationEventOnPlayOutbuffCount()`

- `Void _AnimationEventOnPlayMilestoneCount()`

- `Void _Render()`

- `IEnumerator _UpdateState()`

- `IEnumerator _TryDismissSelf()`

- `Void _Reset()`

- `Void _ResetAnim()`

- `Void _PlayAnim(String, Action)`

- `Void _SkipStatsShowAnim()`

- `Void _SkipRewardShowAnim()`

- `Boolean _CanClick()`

- `Boolean _HasUnprocessedCommand()`

- `Boolean _ConsumeNextCommand()`

- `Boolean _ConsumeBackCommand()`

- `Void _SendFinishGameRequest(Action)`

- `Void _ShowGainedTokens(Int32, Int32, Action)`

- `Void _ShowUnlockToast()`

- `Void <_UpdateState>b__41_0()`

- `Void <_UpdateState>b__41_1()`

- `Void <_UpdateState>b__41_2()`

- `Void <_UpdateState>b__41_3()`

- `Void <_UpdateState>b__41_4()`

- `Void <_UpdateState>b__41_5()`

- `Void <_UpdateState>b__41_6()`

- `Void <>n__0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6GameEndState : PopupFadeState
{
	private const String STATS_SHOW_ANIM; // 0x0
	private const String STATS_HIDE_ANIM; // 0x0
	private const String REWARD_SHOW_ANIM; // 0x0
	private const String REWARD_HIDE_ANIM; // 0x0
	private const String UNLOCK_SHOW_ANIM; // 0x0
	private const String FACTOR_OBJ_SHOW_ANIM; // 0x0
	private const Single UNLOCK_TOAST_INTERVAL; // 0x0
	private AnimationWrapper _animationWrapper; // 0x70
	private List`1 _scoreObjViews; // 0x78
	private AnimationWrapper _modeFactorWrapper; // 0x80
	private Act12D6GameEndScoreObjView _totalScoreObjView; // 0x88
	private Act12D6GameEndScoreObjView _outbuffTokenCountView; // 0x90
	private Act12D6GameEndScoreObjView _milestoneTokenCountView; // 0x98
	private Act12d6GameEndTitleView _titleView; // 0xa0
	private Act12D6GameEndStatsView _statsView; // 0xa8
	private Act12D6GameEndRewardView _rewardView; // 0xb0
	private Act12D6GameEndUnlockView _unlockView; // 0xb8
	private Image _imageBkg; // 0xc0
	private UIFullScreenImage _imageBlurBkg; // 0xc8
	private Image _imageCornerSuc; // 0xd0
	private Image _imageCornerFail; // 0xd8
	private Act12D6GameEndStateBean m_stateBean; // 0xe0
	private InternalState m_state; // 0xe8
	private Coroutine m_updateCoroutine; // 0xf0
	private Boolean m_isNextClicked; // 0xf8
	private Boolean m_isBackClicked; // 0xf9
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_EventOnNextClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x20
	private static DelegateBridge __Hotfix0__AnimationEventOnPlayAudio; // 0x28
	private static DelegateBridge __Hotfix0__AnimationEventOnShotBlurBkg; // 0x30
	private static DelegateBridge __Hotfix0__AnimationEventOnEnableRewardView; // 0x38
	private static DelegateBridge __Hotfix0__AnimationEventOnPlayScoreObjAnim; // 0x40
	private static DelegateBridge __Hotfix0__AnimationEventOnPlayModeFactor; // 0x48
	private static DelegateBridge __Hotfix0__AnimationEventOnPlayTotalScore; // 0x50
	private static DelegateBridge __Hotfix0__AnimationEventOnPlayOutbuffCount; // 0x58
	private static DelegateBridge __Hotfix0__AnimationEventOnPlayMilestoneCount; // 0x60
	private static DelegateBridge __Hotfix0__Render; // 0x68
	private static DelegateBridge __Hotfix0__UpdateState; // 0x70
	private static DelegateBridge __Hotfix0__TryDismissSelf; // 0x78
	private static DelegateBridge __Hotfix0__Reset; // 0x80
	private static DelegateBridge __Hotfix0__ResetAnim; // 0x88
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x90
	private static DelegateBridge __Hotfix0__SkipStatsShowAnim; // 0x98
	private static DelegateBridge __Hotfix0__SkipRewardShowAnim; // 0xa0
	private static DelegateBridge __Hotfix0__CanClick; // 0xa8
	private static DelegateBridge __Hotfix0__HasUnprocessedCommand; // 0xb0
	private static DelegateBridge __Hotfix0__ConsumeNextCommand; // 0xb8
	private static DelegateBridge __Hotfix0__ConsumeBackCommand; // 0xc0
	private static DelegateBridge __Hotfix0__SendFinishGameRequest; // 0xc8
	private static DelegateBridge __Hotfix0__ShowGainedTokens; // 0xd0
	private static DelegateBridge __Hotfix0__ShowUnlockToast; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0


	// RVA: 0x346d67c VA: 0x7595a8567c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x346d6e0 VA: 0x7595a856e0
	protected override Void OnEnter() { }
	// RVA: 0x346da80 VA: 0x7595a85a80
	protected override Void OnExit() { }
	// RVA: 0x346daf4 VA: 0x7595a85af4
	public Void EventOnNextClicked() { }
	// RVA: 0x346dc9c VA: 0x7595a85c9c
	public Void EventOnBackClicked() { }
	// RVA: 0x346dd2c VA: 0x7595a85d2c
	private Void _AnimationEventOnPlayAudio(String soundId) { }
	// RVA: 0x346ddd4 VA: 0x7595a85dd4
	private Void _AnimationEventOnShotBlurBkg() { }
	// RVA: 0x346df7c VA: 0x7595a85f7c
	private Void _AnimationEventOnEnableRewardView() { }
	// RVA: 0x346e0b4 VA: 0x7595a860b4
	private Void _AnimationEventOnPlayScoreObjAnim(Int32 index) { }
	// RVA: 0x346e198 VA: 0x7595a86198
	private Void _AnimationEventOnPlayModeFactor() { }
	// RVA: 0x346e224 VA: 0x7595a86224
	private Void _AnimationEventOnPlayTotalScore() { }
	// RVA: 0x346e298 VA: 0x7595a86298
	private Void _AnimationEventOnPlayOutbuffCount() { }
	// RVA: 0x346e30c VA: 0x7595a8630c
	private Void _AnimationEventOnPlayMilestoneCount() { }
	// RVA: 0x346d7b4 VA: 0x7595a857b4
	private Void _Render() { }
	// RVA: 0x346d9d4 VA: 0x7595a859d4
	private IEnumerator _UpdateState() { }
	// RVA: 0x346e380 VA: 0x7595a86380
	private IEnumerator _TryDismissSelf() { }
	// RVA: 0x346d92c VA: 0x7595a8592c
	private Void _Reset() { }
	// RVA: 0x346e42c VA: 0x7595a8642c
	private Void _ResetAnim() { }
	// RVA: 0x346e508 VA: 0x7595a86508
	private Void _PlayAnim(String stateName, Action onFinished) { }
	// RVA: 0x346e6b4 VA: 0x7595a866b4
	private Void _SkipStatsShowAnim() { }
	// RVA: 0x346e758 VA: 0x7595a86758
	private Void _SkipRewardShowAnim() { }
	// RVA: 0x346db84 VA: 0x7595a85b84
	private Boolean _CanClick() { }
	// RVA: 0x346dc1c VA: 0x7595a85c1c
	private Boolean _HasUnprocessedCommand() { }
	// RVA: 0x346e8e8 VA: 0x7595a868e8
	private Boolean _ConsumeNextCommand() { }
	// RVA: 0x346e964 VA: 0x7595a86964
	private Boolean _ConsumeBackCommand() { }
	// RVA: 0x346e9e0 VA: 0x7595a869e0
	private Void _SendFinishGameRequest(Action onFinished) { }
	// RVA: 0x346ec40 VA: 0x7595a86c40
	private Void _ShowGainedTokens(Int32 outBuffTokenCnt, Int32 milestoneTokenCnt, Action onFinished) { }
	// RVA: 0x346efc0 VA: 0x7595a86fc0
	private Void _ShowUnlockToast() { }
	// RVA: 0x346f200 VA: 0x7595a87200
	public Void .ctor() { }
	// RVA: 0x346f2b0 VA: 0x7595a872b0
	private Void <_UpdateState>b__41_0() { }
	// RVA: 0x346f2bc VA: 0x7595a872bc
	private Void <_UpdateState>b__41_1() { }
	// RVA: 0x346f2c8 VA: 0x7595a872c8
	private Void <_UpdateState>b__41_2() { }
	// RVA: 0x346f2d4 VA: 0x7595a872d4
	private Void <_UpdateState>b__41_3() { }
	// RVA: 0x346f40c VA: 0x7595a8740c
	private Void <_UpdateState>b__41_4() { }
	// RVA: 0x346f418 VA: 0x7595a87418
	private Void <_UpdateState>b__41_5() { }
	// RVA: 0x346f424 VA: 0x7595a87424
	private Void <_UpdateState>b__41_6() { }
	// RVA: 0x346f430 VA: 0x7595a87430
	private Void <>n__0() { }
	// RVA: 0x346f438 VA: 0x7595a87438
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x346f440 VA: 0x7595a87440
	private Void <>xLuaBaseProxy_OnExit() { }
}
```