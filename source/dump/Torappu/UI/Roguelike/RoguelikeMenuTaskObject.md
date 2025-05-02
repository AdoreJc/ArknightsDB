# RoguelikeMenuTaskObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `Text _textName`

- `Text _textProgress`

- `RectTransform _lineProgress`

- `CanvasGroup _lightProgress`

- `CanvasGroup _iconTask`

- `CanvasGroup _iconTaskComplete`

- `UIAnimationLocation _animShow`

- `CanvasGroup _canvasValid`

- `CanvasGroup _canvasOuterLight`

- `AnimationSwitchTween m_showSwitchTween`

- `CompleteSwitchTween m_completeSwitchTween`

- `ValidSwitchTween m_validSwitchTween`

- `OuterLightShowTween m_outerLightShowTween`

- `Tween m_progressTween`

- `RoguelikeStatusBarTextTweener m_progressTextTweener`

- `RoguelikeMenuTaskViewModel m_cachedModel`

- `Boolean m_cachedStateShow`

- `Boolean m_cachedStateValid`


## Methods

- `Void _RenderShow(Boolean, Boolean)`

- `Void _RenderProgress(Int32, Boolean)`

- `Void _RenderComplete(Boolean, Boolean)`

- `Void _RenderValid(Boolean, Boolean)`

- `Void _RenderOuterLight(Boolean, Boolean)`

- `Void _UpdateRenderers()`

- `Void _Render(Boolean)`

- `Void _OnReceiveTaskRewardClicked()`

- `Boolean <Init>b__35_0()`

- `Int32 <Init>b__35_1()`

- `Boolean <Init>b__35_2()`

- `Boolean <Init>b__35_3()`

- `Boolean <Init>b__35_4()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuTaskObject : RoguelikeMenuObject`1
{
	private const Single PROGRESS_CHANGE_TWEEN_DURATION; // 0x0
	private const Int32 PROGRESS_MASK_BAR_WIDTH; // 0x0
	private const Int32 PROGRESS_MASK_BAR_HEIGHT; // 0x0
	private const Single CANVAS_ALPHA_INVALID; // 0x0
	private const Single OUTER_LIGHT_ALPHA_BREATH_DOWN; // 0x0
	private const Single OUTER_LIGHT_ALPHA_BREATH_UP; // 0x0
	private const Single OUTER_LIGHT_LOOP_DURATION; // 0x0
	private static readonly Type[] STATES_NOT_SHOW; // 0x0
	private static readonly Type[] STATE_CAN_RECEIVE_TASK_REWARD; // 0x8
	private CanvasGroup _pnlContent; // 0x28
	private Text _textName; // 0x30
	private Text _textProgress; // 0x38
	private RectTransform _lineProgress; // 0x40
	private CanvasGroup _lightProgress; // 0x48
	private CanvasGroup _iconTask; // 0x50
	private CanvasGroup _iconTaskComplete; // 0x58
	private UIAnimationLocation _animShow; // 0x60
	private CanvasGroup _canvasValid; // 0x70
	private CanvasGroup _canvasOuterLight; // 0x78
	private AnimationSwitchTween m_showSwitchTween; // 0x80
	private CompleteSwitchTween m_completeSwitchTween; // 0x88
	private ValidSwitchTween m_validSwitchTween; // 0x90
	private OuterLightShowTween m_outerLightShowTween; // 0x98
	private Tween m_progressTween; // 0xa0
	private RoguelikeStatusBarTextTweener m_progressTextTweener; // 0xa8
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0xb0
	private List`1 m_renderers; // 0xb8
	private RoguelikeMenuTaskViewModel m_cachedModel; // 0xc0
	private Boolean m_cachedStateShow; // 0xc8
	private Boolean m_cachedStateValid; // 0xc9
	private static DelegateBridge __Hotfix0_get_menuType; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0__RenderShow; // 0x20
	private static DelegateBridge __Hotfix0__RenderProgress; // 0x28
	private static DelegateBridge __Hotfix0__RenderComplete; // 0x30
	private static DelegateBridge __Hotfix0__RenderValid; // 0x38
	private static DelegateBridge __Hotfix0__RenderOuterLight; // 0x40
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x60
	private static DelegateBridge __Hotfix0_OnClick; // 0x68
	private static DelegateBridge __Hotfix0__OnReceiveTaskRewardClicked; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a6b7d4 VA: 0x75950837d4
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a6b84c VA: 0x759508384c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a6c2e0 VA: 0x75950842e0
	private Void _RenderShow(Boolean show, Boolean fastMode) { }
	// RVA: 0x2a6c398 VA: 0x7595084398
	private Void _RenderProgress(Int32 currValue, Boolean fastMode) { }
	// RVA: 0x2a6c9ac VA: 0x75950849ac
	private Void _RenderComplete(Boolean completed, Boolean fastMode) { }
	// RVA: 0x2a6cab4 VA: 0x7595084ab4
	private Void _RenderValid(Boolean valid, Boolean fastMode) { }
	// RVA: 0x2a6cb6c VA: 0x7595084b6c
	private Void _RenderOuterLight(Boolean show, Boolean fastMode) { }
	// RVA: 0x2a6cc24 VA: 0x7595084c24
	private Void _UpdateRenderers() { }
	// RVA: 0x2a6ce3c VA: 0x7595084e3c
	private Void _Render(Boolean fastMode) { }
	// RVA: 0x2a6d0b8 VA: 0x75950850b8
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a6d218 VA: 0x7595085218
	public override Void Render(RoguelikeMenuTaskViewModel viewModel) { }
	// RVA: 0x2a6d2d4 VA: 0x75950852d4
	public override Void OnClick() { }
	// RVA: 0x2a6d3cc VA: 0x75950853cc
	private Void _OnReceiveTaskRewardClicked() { }
	// RVA: 0x2a6d5ec VA: 0x75950855ec
	public Void .ctor() { }
	// RVA: 0x2a6d68c VA: 0x759508568c
	private static Void .cctor() { }
	// RVA: 0x2a6d87c VA: 0x759508587c
	private Boolean <Init>b__35_0() { }
	// RVA: 0x2a6d8a8 VA: 0x75950858a8
	private Int32 <Init>b__35_1() { }
	// RVA: 0x2a6d8c4 VA: 0x75950858c4
	private Boolean <Init>b__35_2() { }
	// RVA: 0x2a6d8e0 VA: 0x75950858e0
	private Boolean <Init>b__35_3() { }
	// RVA: 0x2a6d91c VA: 0x759508591c
	private Boolean <Init>b__35_4() { }
	// RVA: 0x2a6d958 VA: 0x7595085958
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a6d95c VA: 0x759508595c
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
	// RVA: 0x2a6d964 VA: 0x7595085964
	private Void <>xLuaBaseProxy_OnClick() { }
}
```