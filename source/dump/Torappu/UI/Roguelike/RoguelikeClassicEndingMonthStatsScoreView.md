# RoguelikeClassicEndingMonthStatsScoreView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasGroup`

- `AnimationWrapper _animationWrapper`

- `SimpleLayoutContent _chatUnlockProgressContent`

- `Text _chatUnlockStatus`

- `RoguelikeClassicEndingMonthEndInfoBaseView _endInfoView`

- `Transform _rewardContainer`

- `RoguelikeTopicMonthSquadRewardView _rewardView`

- `Transform _charViewContainer`

- `RoguelikeClassicEndingMonthStatsCharView _charViewPrefab`

- `Color _bpViewColor`

- `RoguelikeTopicMonthSquadRewardView m_rewardView`

- `ProgressAdapter m_unlockProgressAdapter`

- `Boolean m_hasInited`

- `Int32 m_unlockChatNum`

- `Int32 m_chatCount`

- `Color m_teamColor`

- `Boolean m_hasAnimPlayed`

- `FadeSwitchTween m_displayTween`

- `Tween m_cacheTween`

- `RoguelikeClassicEndingMonthStatsCharView m_charView`

- `Action m_backAction`

- `Action m_confirmAction`


## Methods

- `Void _InitIfNot()`

- `Void _RenderEndInfoView(RoguelikeClassicEndingMonthViewModel)`

- `Void _ClearCacheTween()`

- `IEnumerator _ApplyInAnim(Boolean)`

- `Void OnBackClicked()`

- `Void OnConfirmClicked()`

- `Void <ApplyOutAnim>b__39_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingMonthStatsScoreView : RoguelikeClassicEndingPageView`1
{
	private const String MONTH_STATS_IN_ANIM; // 0x0
	private const String MONTH_STATS_OUT_ANIM; // 0x0
	private const Single FADE_DURATION; // 0x0
	private CanvasGroup _canvasGroup; // 0x18
	private AnimationWrapper _animationWrapper; // 0x20
	private SimpleLayoutContent _chatUnlockProgressContent; // 0x28
	private Text _chatUnlockStatus; // 0x30
	private RoguelikeClassicEndingMonthEndInfoBaseView _endInfoView; // 0x38
	private Transform _rewardContainer; // 0x40
	private RoguelikeTopicMonthSquadRewardView _rewardView; // 0x48
	private Transform _charViewContainer; // 0x50
	private RoguelikeClassicEndingMonthStatsCharView _charViewPrefab; // 0x58
	private Color _bpViewColor; // 0x60
	private RoguelikeTopicMonthSquadRewardView m_rewardView; // 0x70
	private ProgressAdapter m_unlockProgressAdapter; // 0x78
	private Boolean m_hasInited; // 0x80
	private Int32 m_unlockChatNum; // 0x84
	private Int32 m_chatCount; // 0x88
	private Color m_teamColor; // 0x8c
	private Boolean m_hasAnimPlayed; // 0x9c
	private FadeSwitchTween m_displayTween; // 0xa0
	private Tween m_cacheTween; // 0xa8
	private RoguelikeClassicEndingMonthStatsCharView m_charView; // 0xb0
	private Action m_backAction; // 0xb8
	private Action m_confirmAction; // 0xc0
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_set_onForward; // 0x8
	private static DelegateBridge __Hotfix0_set_onBack; // 0x10
	private static DelegateBridge __Hotfix0_set_onConfirm; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__RenderEndInfoView; // 0x30
	private static DelegateBridge __Hotfix0__ClearCacheTween; // 0x38
	private static DelegateBridge __Hotfix0__ApplyInAnim; // 0x40
	private static DelegateBridge __Hotfix0_ApplyOutAnim; // 0x48
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override ViewType viewType { get; }
	public override Action onForward { set; }
	public override Action onBack { set; }
	public override Action onConfirm { set; }

	// RVA: 0x2a24e40 VA: 0x759503ce40
	public override ViewType get_viewType() { }
	// RVA: 0x2a24ea8 VA: 0x759503cea8
	public override Void set_onForward(Action value) { }
	// RVA: 0x2a24f20 VA: 0x759503cf20
	public override Void set_onBack(Action value) { }
	// RVA: 0x2a24fa4 VA: 0x759503cfa4
	public override Void set_onConfirm(Action value) { }
	// RVA: 0x2a25028 VA: 0x759503d028
	private Void _InitIfNot() { }
	// RVA: 0x2a252c0 VA: 0x759503d2c0
	protected override Void Render(RoguelikeEndingControllerBase endingController, RoguelikeClassicEndingMonthViewModel viewModel) { }
	// RVA: 0x2a25618 VA: 0x759503d618
	private Void _RenderEndInfoView(RoguelikeClassicEndingMonthViewModel viewModel) { }
	// RVA: 0x2a257bc VA: 0x759503d7bc
	private Void _ClearCacheTween() { }
	// RVA: 0x2a256f4 VA: 0x759503d6f4
	private IEnumerator _ApplyInAnim(Boolean fastMode) { }
	// RVA: 0x2a25864 VA: 0x759503d864
	public override Void ApplyOutAnim() { }
	// RVA: 0x2a259b0 VA: 0x759503d9b0
	public Void OnBackClicked() { }
	// RVA: 0x2a25a34 VA: 0x759503da34
	public Void OnConfirmClicked() { }
	// RVA: 0x2a25ab8 VA: 0x759503dab8
	public Void .ctor() { }
	// RVA: 0x2a25b54 VA: 0x759503db54
	private Void <ApplyOutAnim>b__39_0() { }
}
```