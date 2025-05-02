# RoguelikeTopicChallengeEndingScoreView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `CanvasGroup _canvasGroup`

- `AnimationWrapper _animationWrapper`

- `Image _cover`

- `Text _name`

- `GameObject _completeTag`

- `GameObject _incompletePanel`

- `GameObject _completePanel`

- `GameObject _normalPanel`

- `GameObject _repeatPanel`

- `RoguelikeTopicChallengeEndingExpView _expView`

- `GameObject _splitPanel`

- `RectTransform _rewardsRoot`

- `GameObject _rewardItemHolder`

- `Color _taskThemeColor`

- `Single _rewardCardScale`

- `Boolean m_hasAnimPlayed`

- `FadeSwitchTween m_displayTween`

- `Tween m_cacheTween`

- `Action m_backAction`

- `Action m_confirmAction`


## Methods

- `Void _InitIfNot()`

- `Void _RenderChallengeCard(RoguelikeTopicChallengeEndingViewModel, RoguelikeTopicChallenge)`

- `Void _RenderTasks(RoguelikeTopicChallengeEndingViewModel, RoguelikeTopicChallenge)`

- `Void _RenderDownSide(RoguelikeTopicChallengeEndingViewModel)`

- `Void _ClearCacheTween()`

- `IEnumerator _ApplyInAnim(Boolean)`

- `Void OnBackClicked()`

- `Void OnConfirmClicked()`

- `Void <ApplyOutAnim>b__39_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeEndingScoreView : RoguelikeClassicEndingPageView`1
{
	private CanvasGroup _canvasGroup; // 0x18
	private AnimationWrapper _animationWrapper; // 0x20
	private Image _cover; // 0x28
	private Text _name; // 0x30
	private GameObject _completeTag; // 0x38
	private RoguelikeTopicChallengeEndingTaskView[] _tasks; // 0x40
	private GameObject _incompletePanel; // 0x48
	private GameObject _completePanel; // 0x50
	private GameObject _normalPanel; // 0x58
	private GameObject _repeatPanel; // 0x60
	private RoguelikeTopicChallengeEndingExpView _expView; // 0x68
	private GameObject _splitPanel; // 0x70
	private RectTransform _rewardsRoot; // 0x78
	private GameObject _rewardItemHolder; // 0x80
	private Color _taskThemeColor; // 0x88
	private Single _rewardCardScale; // 0x98
	private const String CHALLENGE_STATS_IN_ANIM; // 0x0
	private const String CHALLENGE_STATS_OUT_ANIM; // 0x0
	private const Single FADE_DURATION; // 0x0
	private Boolean m_hasAnimPlayed; // 0x9c
	private FadeSwitchTween m_displayTween; // 0xa0
	private Tween m_cacheTween; // 0xa8
	private Action m_backAction; // 0xb0
	private Action m_confirmAction; // 0xb8
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_set_onForward; // 0x8
	private static DelegateBridge __Hotfix0_set_onBack; // 0x10
	private static DelegateBridge __Hotfix0_set_onConfirm; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__RenderChallengeCard; // 0x30
	private static DelegateBridge __Hotfix0__RenderTasks; // 0x38
	private static DelegateBridge __Hotfix0__RenderDownSide; // 0x40
	private static DelegateBridge __Hotfix0__ClearCacheTween; // 0x48
	private static DelegateBridge __Hotfix0__ApplyInAnim; // 0x50
	private static DelegateBridge __Hotfix0_ApplyOutAnim; // 0x58
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override ViewType viewType { get; }
	public override Action onForward { set; }
	public override Action onBack { set; }
	public override Action onConfirm { set; }

	// RVA: 0x2645858 VA: 0x7594c5d858
	public override ViewType get_viewType() { }
	// RVA: 0x26458c0 VA: 0x7594c5d8c0
	public override Void set_onForward(Action value) { }
	// RVA: 0x2645938 VA: 0x7594c5d938
	public override Void set_onBack(Action value) { }
	// RVA: 0x26459bc VA: 0x7594c5d9bc
	public override Void set_onConfirm(Action value) { }
	// RVA: 0x2645a40 VA: 0x7594c5da40
	private Void _InitIfNot() { }
	// RVA: 0x2645b08 VA: 0x7594c5db08
	protected override Void Render(RoguelikeEndingControllerBase endingController, RoguelikeTopicChallengeEndingViewModel viewModel) { }
	// RVA: 0x2645cc0 VA: 0x7594c5dcc0
	private Void _RenderChallengeCard(RoguelikeTopicChallengeEndingViewModel viewModel, RoguelikeTopicChallenge challengeData) { }
	// RVA: 0x2645e50 VA: 0x7594c5de50
	private Void _RenderTasks(RoguelikeTopicChallengeEndingViewModel viewModel, RoguelikeTopicChallenge challengeData) { }
	// RVA: 0x2646284 VA: 0x7594c5e284
	private Void _RenderDownSide(RoguelikeTopicChallengeEndingViewModel viewModel) { }
	// RVA: 0x26467b0 VA: 0x7594c5e7b0
	private Void _ClearCacheTween() { }
	// RVA: 0x26465f8 VA: 0x7594c5e5f8
	private IEnumerator _ApplyInAnim(Boolean fastMode) { }
	// RVA: 0x2646858 VA: 0x7594c5e858
	public override Void ApplyOutAnim() { }
	// RVA: 0x26469a4 VA: 0x7594c5e9a4
	public Void OnBackClicked() { }
	// RVA: 0x2646a28 VA: 0x7594c5ea28
	public Void OnConfirmClicked() { }
	// RVA: 0x2646aac VA: 0x7594c5eaac
	public Void .ctor() { }
	// RVA: 0x2646b48 VA: 0x7594c5eb48
	private Void <ApplyOutAnim>b__39_0() { }
}
```