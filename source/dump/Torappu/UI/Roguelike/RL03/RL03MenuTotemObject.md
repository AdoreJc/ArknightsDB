# RL03MenuTotemObject

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `CanvasGroup _pnlContent`

- `GameObject _panelCanUse`

- `GameObject _panelHaveDivination`

- `GameObject _panelBack`

- `UIAnimationLocation _animCanUse`

- `UIAnimationLocation _animStatusForbidden`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `AnimationSwitchTween m_forbiddenTween`

- `RL03MenuTotemViewModel m_cachedModel`

- `RoguelikeMenuTotemObjectStatus m_cachedStatus`

- `Boolean m_cachedStateShow`

- `Boolean m_isInShowUsePartState`

- `Tween m_useTween`


## Methods

- `Void _UpdateRenderers()`

- `Void _Render(Boolean)`

- `Void _TryToShowCanUseAnim()`

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderPanelBack(Boolean, Boolean)`

- `Void _RenderForbidden(Boolean, Boolean)`

- `Void _RenderCanUsePart(Boolean, Boolean)`

- `Void _EventOnShowUseAnim(Object)`

- `Void _OnTotemClick()`

- `Boolean <Init>b__21_0()`

- `Boolean <Init>b__21_1()`

- `Boolean <Init>b__21_2()`

- `Boolean <Init>b__21_3()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnClick()`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MenuTotemObject : RoguelikeMenuObject`1
{
	private static Vector2 HIDE_POS; // 0x0
	private static Vector2 SHOW_POS; // 0x8
	private static readonly Type[] STATES_NOT_SHOW; // 0x10
	private static readonly Type[] STATES_SHOW_CAN_USE; // 0x18
	private CanvasGroup _pnlContent; // 0x28
	private GameObject _panelCanUse; // 0x30
	private GameObject _panelHaveDivination; // 0x38
	private GameObject _panelBack; // 0x40
	private UIAnimationLocation _animCanUse; // 0x48
	private UIAnimationLocation _animStatusForbidden; // 0x58
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x68
	private AnimationSwitchTween m_forbiddenTween; // 0x70
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0x78
	private List`1 m_renderers; // 0x80
	private RL03MenuTotemViewModel m_cachedModel; // 0x88
	private RoguelikeMenuTotemObjectStatus m_cachedStatus; // 0x90
	private Boolean m_cachedStateShow; // 0x94
	private Boolean m_isInShowUsePartState; // 0x95
	private Tween m_useTween; // 0x98
	private static DelegateBridge __Hotfix0_get_menuType; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x38
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x40
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0__TryToShowCanUseAnim; // 0x58
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x60
	private static DelegateBridge __Hotfix0__RenderPanelBack; // 0x68
	private static DelegateBridge __Hotfix0__RenderForbidden; // 0x70
	private static DelegateBridge __Hotfix0__RenderCanUsePart; // 0x78
	private static DelegateBridge __Hotfix0__EventOnShowUseAnim; // 0x80
	private static DelegateBridge __Hotfix0__OnTotemClick; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b9bac0 VA: 0x75951b3ac0
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b9bb38 VA: 0x75951b3b38
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b9c194 VA: 0x75951b4194
	public override Void Render(RL03MenuTotemViewModel viewModel) { }
	// RVA: 0x2b9c6c8 VA: 0x75951b46c8
	public override Void OnClick() { }
	// RVA: 0x2b9c974 VA: 0x75951b4974
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2b9c260 VA: 0x75951b4260
	private Void _UpdateRenderers() { }
	// RVA: 0x2b9c478 VA: 0x75951b4478
	private Void _Render(Boolean fastMode) { }
	// RVA: 0x2b9caf4 VA: 0x75951b4af4
	private Void _TryToShowCanUseAnim() { }
	// RVA: 0x2b9cbfc VA: 0x75951b4bfc
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b9ccb4 VA: 0x75951b4cb4
	private Void _RenderPanelBack(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b9cd50 VA: 0x75951b4d50
	private Void _RenderForbidden(Boolean forbidden, Boolean fastMode) { }
	// RVA: 0x2b9cdf4 VA: 0x75951b4df4
	private Void _RenderCanUsePart(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b9ce90 VA: 0x75951b4e90
	private Void _EventOnShowUseAnim(Object arg) { }
	// RVA: 0x2b9c7c0 VA: 0x75951b47c0
	private Void _OnTotemClick() { }
	// RVA: 0x2b9cf40 VA: 0x75951b4f40
	public Void .ctor() { }
	// RVA: 0x2b9cfe0 VA: 0x75951b4fe0
	private static Void .cctor() { }
	// RVA: 0x2b9d1e8 VA: 0x75951b51e8
	private Boolean <Init>b__21_0() { }
	// RVA: 0x2b9d21c VA: 0x75951b521c
	private Boolean <Init>b__21_1() { }
	// RVA: 0x2b9d22c VA: 0x75951b522c
	private Boolean <Init>b__21_2() { }
	// RVA: 0x2b9d23c VA: 0x75951b523c
	private Boolean <Init>b__21_3() { }
	// RVA: 0x2b9d270 VA: 0x75951b5270
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2b9d278 VA: 0x75951b5278
	private Void <>xLuaBaseProxy_OnClick() { }
	// RVA: 0x2b9d280 VA: 0x75951b5280
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
}
```