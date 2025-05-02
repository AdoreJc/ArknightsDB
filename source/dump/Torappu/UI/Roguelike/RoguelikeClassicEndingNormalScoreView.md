# RoguelikeClassicEndingNormalScoreView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasGroup`

- `RoguelikeEndingScoreObjConfig _zoneScoreViewConfig`

- `RoguelikeEndingScoreObjConfig _stepScoreViewConfig`

- `RoguelikeEndingScoreObjConfig _battleScoreViewConfig`

- `RoguelikeEndingScoreObjConfig _charScoreViewConfig`

- `RoguelikeEndingScoreObjConfig _itemScoreViewConfig`

- `RoguelikeEndingScoreObjConfig _bossScoreViewConfig`

- `RoguelikeEndingScoreObjConfig _eliteScoreViewConfig`

- `UIAtlasImage _imgModeGrow`

- `UIAtlasImage _imgModeBkg`

- `Text _textModeName`

- `Text _textGrade`

- `Text _textFactor`

- `Text _textTotalScore`

- `AnimationWrapper _animationWrapper`

- `RectTransform _bpViewContainer`

- `RoguelikeTopicEndingAddBPView _bpView`

- `RoguelikeClassicEndingNormalScoreGpView _gpView`

- `Boolean m_hasAnimPlayed`

- `FadeSwitchTween m_displayTween`

- `Boolean m_inited`

- `Tween m_cacheTween`

- `RoguelikeTopicEndingAddBPView m_bpView`

- `WeakReference m_renderCoroutineRef`

- `Action m_backAction`

- `Action m_confirmAction`


## Methods

- `Void _InitIfNot()`

- `Void _ClearCacheTween()`

- `IEnumerator _ApplyInAnim(Boolean)`

- `Void OnBackClicked()`

- `Void OnConfirmClicked()`

- `Void <ApplyOutAnim>b__46_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingNormalScoreView : RoguelikeClassicEndingPageView`1
{
	private const String SCORE_IN_ANIM; // 0x0
	private const String SCORE_OUT_ANIM; // 0x0
	private const Single SCORE_VIEW_WAIT_DELAY; // 0x0
	private const Single FADE_DURATION; // 0x0
	private const Single SCORE_SOUND_DELAY; // 0x0
	private const Single GP_VIEW_PROGRESS_DELAY; // 0x0
	private CanvasGroup _canvasGroup; // 0x18
	private RoguelikeEndingScoreObjConfig _zoneScoreViewConfig; // 0x20
	private RoguelikeEndingScoreObjConfig _stepScoreViewConfig; // 0x28
	private RoguelikeEndingScoreObjConfig _battleScoreViewConfig; // 0x30
	private RoguelikeEndingScoreObjConfig _charScoreViewConfig; // 0x38
	private RoguelikeEndingScoreObjConfig _itemScoreViewConfig; // 0x40
	private RoguelikeEndingScoreObjConfig _bossScoreViewConfig; // 0x48
	private RoguelikeEndingScoreObjConfig _eliteScoreViewConfig; // 0x50
	private UIAtlasImage _imgModeGrow; // 0x58
	private UIAtlasImage _imgModeBkg; // 0x60
	private Text _textModeName; // 0x68
	private Text _textGrade; // 0x70
	private Text _textFactor; // 0x78
	private Text _textTotalScore; // 0x80
	private AnimationWrapper _animationWrapper; // 0x88
	private RectTransform _bpViewContainer; // 0x90
	private RoguelikeTopicEndingAddBPView _bpView; // 0x98
	private RoguelikeClassicEndingNormalScoreGpView _gpView; // 0xa0
	private List`1 m_scoreViewList; // 0xa8
	private Boolean m_hasAnimPlayed; // 0xb0
	private FadeSwitchTween m_displayTween; // 0xb8
	private Boolean m_inited; // 0xc0
	private Tween m_cacheTween; // 0xc8
	private RoguelikeTopicEndingAddBPView m_bpView; // 0xd0
	private WeakReference m_renderCoroutineRef; // 0xd8
	private Action m_backAction; // 0xe0
	private Action m_confirmAction; // 0xe8
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_set_onForward; // 0x8
	private static DelegateBridge __Hotfix0_set_onBack; // 0x10
	private static DelegateBridge __Hotfix0_set_onConfirm; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__ClearCacheTween; // 0x30
	private static DelegateBridge __Hotfix0__ApplyInAnim; // 0x38
	private static DelegateBridge __Hotfix0_ApplyOutAnim; // 0x40
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override ViewType viewType { get; }
	public override Action onForward { set; }
	public override Action onBack { set; }
	public override Action onConfirm { set; }

	// RVA: 0x2a26a20 VA: 0x759503ea20
	public override ViewType get_viewType() { }
	// RVA: 0x2a26a88 VA: 0x759503ea88
	public override Void set_onForward(Action value) { }
	// RVA: 0x2a26b00 VA: 0x759503eb00
	public override Void set_onBack(Action value) { }
	// RVA: 0x2a26b84 VA: 0x759503eb84
	public override Void set_onConfirm(Action value) { }
	// RVA: 0x2a26c08 VA: 0x759503ec08
	protected override Void Render(RoguelikeEndingControllerBase endingController, RoguelikeClassicEndingNormalViewModel viewModel) { }
	// RVA: 0x2a2722c VA: 0x759503f22c
	private Void _InitIfNot() { }
	// RVA: 0x2a2787c VA: 0x759503f87c
	private Void _ClearCacheTween() { }
	// RVA: 0x2a276c0 VA: 0x759503f6c0
	private IEnumerator _ApplyInAnim(Boolean fastMode) { }
	// RVA: 0x2a27924 VA: 0x759503f924
	public override Void ApplyOutAnim() { }
	// RVA: 0x2a27a70 VA: 0x759503fa70
	public Void OnBackClicked() { }
	// RVA: 0x2a27af4 VA: 0x759503faf4
	public Void OnConfirmClicked() { }
	// RVA: 0x2a27b78 VA: 0x759503fb78
	public Void .ctor() { }
	// RVA: 0x2a27c5c VA: 0x759503fc5c
	private Void <ApplyOutAnim>b__46_0() { }
}
```