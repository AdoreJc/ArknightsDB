# RL04MenuFragmentObject

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `CanvasGroup _pnlContent`

- `GameObject _pnlBack`

- `Image _weightProgressImg`

- `Text _curWeightText`

- `Text _limitWeightText`

- `GameObject _lightWeightFragmentObj`

- `GameObject _mediumWeightFragmentObj`

- `GameObject _heavyWeightFragmentObj`

- `CanvasGroup _fragmentWeightCharNotFullTipsGroup`

- `UIAnimationLocation _weightFragmentEntryAnimLocation`

- `UIAnimationLocation _fragmentForbiddenAnimLocation`

- `Text _ideaCnt`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `AnimationSwitchTween m_forbiddenSwitchTween`

- `FadeSwitchTween m_fragmentCharNotNullTipsFadeSwitchTween`

- `RL04MenuFragmentViewModel m_cachedModel`

- `RL04FragmentObjectStatus m_cachedStatus`

- `Boolean m_cachedIsCanUse`

- `Boolean m_cachedStateShow`

- `Tween m_weightFragmentEntryTween`

- `Tween m_progressChangeTween`

- `Tween m_curWeightTextTween`

- `Tween m_limitWeightTextTween`

- `FragmentBagStatus m_cachedFragmentBagStatus`

- `Single m_cachedWeightProgress`

- `Int32 m_cachedCurWeight`

- `Int32 m_cachedLimitWeight`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _UpdateRenderers()`

- `Void _RenderRenderers(Boolean)`

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderPanelBack(Boolean, Boolean)`

- `Void _RenderForbidden(Boolean, Boolean)`

- `Void _RenderForTips(Boolean, Boolean)`

- `Void _PlayWeightFragmentEntryAnim(FragmentBagStatus)`

- `Void _PlayWeightProgressTween(Single)`

- `Void _PlayCurWeightTextTween(Int32)`

- `Void _PlayLimitWeightTextTween(Int32)`

- `Void _OnFragmentClicked()`

- `Boolean <Init>b__48_0()`

- `Boolean <Init>b__48_1()`

- `Boolean <Init>b__48_2()`

- `Boolean <Init>b__48_3()`

- `Single <_PlayWeightProgressTween>b__59_0()`

- `Void <_PlayWeightProgressTween>b__59_1(Single)`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuFragmentObject : RoguelikeMenuObject`1, IHotfixable
{
	private static readonly Vector2 HIDE_POS; // 0x0
	private static readonly Vector2 SHOW_POS; // 0x8
	private static readonly Type[] STATES_NOT_SHOW; // 0x10
	private static readonly Type[] STATES_SHOW_CAN_USE; // 0x18
	private static readonly Type[] STATES_SELECTED; // 0x20
	private static readonly Type[] STATES_FORBIDDEN; // 0x28
	private static readonly Color LIGHT_WEIGHT_TEXT_COLOR; // 0x30
	private static readonly Color MEDIUM_WEIGHT_TEXT_COLOR; // 0x40
	private static readonly Color HEAVY_WEIGHT_TEXT_COLOR; // 0x50
	private static readonly Color LIGHT_WEIGHT_PROGRESS_COLOR; // 0x60
	private static readonly Color MEDIUM_WEIGHT_PROGRESS_COLOR; // 0x70
	private static readonly Color HEAVY_WEIGHT_PROGRESS_COLOR; // 0x80
	private const Single PROGRESS_CHANGE_DURATION; // 0x0
	private const Single CUR_WEIGHT_CHANGE_DURATION; // 0x0
	private const Single LIMIT_WEIGHT_CHANGE_DURATION; // 0x0
	private CanvasGroup _pnlContent; // 0x28
	private GameObject _pnlBack; // 0x30
	private Image _weightProgressImg; // 0x38
	private Text _curWeightText; // 0x40
	private Text _limitWeightText; // 0x48
	private GameObject _lightWeightFragmentObj; // 0x50
	private GameObject _mediumWeightFragmentObj; // 0x58
	private GameObject _heavyWeightFragmentObj; // 0x60
	private CanvasGroup _fragmentWeightCharNotFullTipsGroup; // 0x68
	private UIAnimationLocation _weightFragmentEntryAnimLocation; // 0x70
	private UIAnimationLocation _fragmentForbiddenAnimLocation; // 0x80
	private Text _ideaCnt; // 0x90
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0x98
	private List`1 m_renderers; // 0xa0
	private FadeTranslationSwitchTween m_showSwitchTween; // 0xa8
	private AnimationSwitchTween m_forbiddenSwitchTween; // 0xb0
	private FadeSwitchTween m_fragmentCharNotNullTipsFadeSwitchTween; // 0xb8
	private RL04MenuFragmentViewModel m_cachedModel; // 0xc0
	private RL04FragmentObjectStatus m_cachedStatus; // 0xc8
	private Boolean m_cachedIsCanUse; // 0xcc
	private Boolean m_cachedStateShow; // 0xcd
	private Tween m_weightFragmentEntryTween; // 0xd0
	private Tween m_progressChangeTween; // 0xd8
	private Tween m_curWeightTextTween; // 0xe0
	private Tween m_limitWeightTextTween; // 0xe8
	private FragmentBagStatus m_cachedFragmentBagStatus; // 0xf0
	private Single m_cachedWeightProgress; // 0xf4
	private Int32 m_cachedCurWeight; // 0xf8
	private Int32 m_cachedLimitWeight; // 0xfc
	private UIPageFinder m_pageFinder; // 0x100
	private static DelegateBridge __Hotfix0_get_menuType; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0xa0
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0xa8
	private static DelegateBridge __Hotfix0_RenderSelection; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0xb8
	private static DelegateBridge __Hotfix0__RenderRenderers; // 0xc0
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0xc8
	private static DelegateBridge __Hotfix0__RenderPanelBack; // 0xd0
	private static DelegateBridge __Hotfix0__RenderForbidden; // 0xd8
	private static DelegateBridge __Hotfix0__RenderForTips; // 0xe0
	private static DelegateBridge __Hotfix0__PlayWeightFragmentEntryAnim; // 0xe8
	private static DelegateBridge __Hotfix0__PlayWeightProgressTween; // 0xf0
	private static DelegateBridge __Hotfix0__PlayCurWeightTextTween; // 0xf8
	private static DelegateBridge __Hotfix0__PlayLimitWeightTextTween; // 0x100
	private static DelegateBridge __Hotfix0__OnFragmentClicked; // 0x108
	private static DelegateBridge __Hotfix0_OnClick; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b2aaa4 VA: 0x7595142aa4
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b2ab1c VA: 0x7595142b1c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b2b154 VA: 0x7595143154
	public override Void Render(RL04MenuFragmentViewModel viewModel) { }
	// RVA: 0x2b2c23c VA: 0x759514423c
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2b2c400 VA: 0x7595144400
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2b2bdd4 VA: 0x7595143dd4
	private Void _UpdateRenderers() { }
	// RVA: 0x2b2bfec VA: 0x7595143fec
	private Void _RenderRenderers(Boolean fastMode) { }
	// RVA: 0x2b2c4d0 VA: 0x75951444d0
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b2c588 VA: 0x7595144588
	private Void _RenderPanelBack(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b2c624 VA: 0x7595144624
	private Void _RenderForbidden(Boolean isShowForbidden, Boolean fastMode) { }
	// RVA: 0x2b2c6c8 VA: 0x75951446c8
	private Void _RenderForTips(Boolean isShow, Boolean isFastMode) { }
	// RVA: 0x2b2b61c VA: 0x759514361c
	private Void _PlayWeightFragmentEntryAnim(FragmentBagStatus fragmentBagStatus) { }
	// RVA: 0x2b2b74c VA: 0x759514374c
	private Void _PlayWeightProgressTween(Single weightProgress) { }
	// RVA: 0x2b2b95c VA: 0x759514395c
	private Void _PlayCurWeightTextTween(Int32 curWeight) { }
	// RVA: 0x2b2bb98 VA: 0x7595143b98
	private Void _PlayLimitWeightTextTween(Int32 limitWeight) { }
	// RVA: 0x2b2c790 VA: 0x7595144790
	private Void _OnFragmentClicked() { }
	// RVA: 0x2b2cab0 VA: 0x7595144ab0
	public override Void OnClick() { }
	// RVA: 0x2b2cbe8 VA: 0x7595144be8
	public Void .ctor() { }
	// RVA: 0x2b2cc88 VA: 0x7595144c88
	private static Void .cctor() { }
	// RVA: 0x2b2d0f8 VA: 0x75951450f8
	private Boolean <Init>b__48_0() { }
	// RVA: 0x2b2d198 VA: 0x7595145198
	private Boolean <Init>b__48_1() { }
	// RVA: 0x2b2d1bc VA: 0x75951451bc
	private Boolean <Init>b__48_2() { }
	// RVA: 0x2b2d1cc VA: 0x75951451cc
	private Boolean <Init>b__48_3() { }
	// RVA: 0x2b2d278 VA: 0x7595145278
	private Single <_PlayWeightProgressTween>b__59_0() { }
	// RVA: 0x2b2d294 VA: 0x7595145294
	private Void <_PlayWeightProgressTween>b__59_1(Single val) { }
	// RVA: 0x2b2d2b0 VA: 0x75951452b0
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2b2d2b8 VA: 0x75951452b8
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
	// RVA: 0x2b2d2c4 VA: 0x75951452c4
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
	// RVA: 0x2b2d2d0 VA: 0x75951452d0
	private Void <>xLuaBaseProxy_OnClick() { }
}
```