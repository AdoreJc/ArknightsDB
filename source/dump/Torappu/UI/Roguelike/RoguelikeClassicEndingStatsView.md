# RoguelikeClassicEndingStatsView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasGroup`

- `UIRecycleLayoutGroup _content`

- `AnimationWrapper _animationWrapper`

- `Adapter m_adapter`

- `Boolean m_hasAnimPlayed`

- `Tween m_cacheTween`

- `FadeSwitchTween m_displayTween`

- `Boolean m_inited`

- `Action m_forwardAction`


## Methods

- `Void _InitIfNot()`

- `Void _SetupContent(RoguelikeEndingControllerBase, RoguelikeClassicEndingStatsViewModel)`

- `Void _ClearCacheTween()`

- `IEnumerator _ApplyInAnim(Boolean)`

- `Void OnForwardClicked()`

- `Void <ApplyOutAnim>b__30_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingStatsView : RoguelikeClassicEndingPageView`1
{
	private const String STATS_IN_ANIM; // 0x0
	private const String STATS_OUT_ANIM; // 0x0
	private const Single FADE_DURATION; // 0x0
	private const Single SWEEP_SOUND_DELAY; // 0x0
	private CanvasGroup _canvasGroup; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	private AnimationWrapper _animationWrapper; // 0x28
	private RoguelikeClassicEndingStatsViewComponentBase[] _viewComponentPrefabs; // 0x30
	private Adapter m_adapter; // 0x38
	private Boolean m_hasAnimPlayed; // 0x40
	private Tween m_cacheTween; // 0x48
	private FadeSwitchTween m_displayTween; // 0x50
	private Boolean m_inited; // 0x58
	private Action m_forwardAction; // 0x60
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_set_onForward; // 0x8
	private static DelegateBridge __Hotfix0_set_onBack; // 0x10
	private static DelegateBridge __Hotfix0_set_onConfirm; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__CreateViewList; // 0x28
	private static DelegateBridge __Hotfix0__SetupContent; // 0x30
	private static DelegateBridge __Hotfix0_ConstructViewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge __Hotfix0__ClearCacheTween; // 0x48
	private static DelegateBridge __Hotfix0__ApplyInAnim; // 0x50
	private static DelegateBridge __Hotfix0_ApplyOutAnim; // 0x58
	private static DelegateBridge __Hotfix0_OnForwardClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override ViewType viewType { get; }
	public override Action onForward { set; }
	public override Action onBack { set; }
	public override Action onConfirm { set; }

	// RVA: 0x2a2885c VA: 0x759504085c
	public override ViewType get_viewType() { }
	// RVA: 0x2a288c4 VA: 0x75950408c4
	public override Void set_onForward(Action value) { }
	// RVA: 0x2a28948 VA: 0x7595040948
	public override Void set_onBack(Action value) { }
	// RVA: 0x2a289c0 VA: 0x75950409c0
	public override Void set_onConfirm(Action value) { }
	// RVA: 0x2a28a38 VA: 0x7595040a38
	private Void _InitIfNot() { }
	// RVA: 0x2a28b04 VA: 0x7595040b04
	private IList`1 _CreateViewList(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingStatsViewModel viewModel) { }
	// RVA: 0x2a28e7c VA: 0x7595040e7c
	private Void _SetupContent(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingStatsViewModel viewModel) { }
	// RVA: 0x2a290e4 VA: 0x75950410e4
	public override RoguelikeClassicEndingPageViewModel ConstructViewModel() { }
	// RVA: 0x2a29490 VA: 0x7595041490
	protected override Void Render(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingStatsViewModel viewModel) { }
	// RVA: 0x2a2965c VA: 0x759504165c
	private Void _ClearCacheTween() { }
	// RVA: 0x2a29594 VA: 0x7595041594
	private IEnumerator _ApplyInAnim(Boolean fastMode) { }
	// RVA: 0x2a29704 VA: 0x7595041704
	public override Void ApplyOutAnim() { }
	// RVA: 0x2a29850 VA: 0x7595041850
	public Void OnForwardClicked() { }
	// RVA: 0x2a298d4 VA: 0x75950418d4
	public Void .ctor() { }
	// RVA: 0x2a29964 VA: 0x7595041964
	private Void <ApplyOutAnim>b__30_0() { }
}
```