# RoguelikeMenuSquadObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `Color _upgradeColor`

- `UIAnimationLocation _animStatusForbidden`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `RoguelikeMenuSquadViewModel m_cachedModel`

- `RoguelikeMenuSquadObjectStatus m_cachedStatus`

- `Boolean m_cachedStateShow`


## Methods

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderForbiddenStatus(Boolean, Boolean)`

- `Void _UpdateRenderers()`

- `Void _Render(Boolean)`

- `Void _OnSquadClicked()`

- `Boolean <Init>b__13_0()`

- `Boolean <Init>b__13_1()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuSquadObject : RoguelikeMenuObject`1
{
	private static Vector2 HIDE_POS; // 0x0
	private static Vector2 SHOW_POS; // 0x8
	private static readonly Type[] STATES_NOT_SHOW; // 0x10
	private CanvasGroup _pnlContent; // 0x28
	private List`1 _squadSlots; // 0x30
	private Color _upgradeColor; // 0x38
	private UIAnimationLocation _animStatusForbidden; // 0x48
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x58
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0x60
	private List`1 m_renderers; // 0x68
	private RoguelikeMenuSquadViewModel m_cachedModel; // 0x70
	private RoguelikeMenuSquadObjectStatus m_cachedStatus; // 0x78
	private Boolean m_cachedStateShow; // 0x7c
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_get_menuType; // 0x20
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x28
	private static DelegateBridge __Hotfix0__RenderForbiddenStatus; // 0x30
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x38
	private static DelegateBridge __Hotfix0__Render; // 0x40
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x50
	private static DelegateBridge __Hotfix0_OnClick; // 0x58
	private static DelegateBridge __Hotfix0__OnSquadClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a69b2c VA: 0x7595081b2c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a69ec0 VA: 0x7595081ec0
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a69f38 VA: 0x7595081f38
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2a69ff0 VA: 0x7595081ff0
	private Void _RenderForbiddenStatus(Boolean forbidden, Boolean fastMode) { }
	// RVA: 0x2a6a104 VA: 0x7595082104
	private Void _UpdateRenderers() { }
	// RVA: 0x2a6a31c VA: 0x759508231c
	private Void _Render(Boolean fastMode) { }
	// RVA: 0x2a6a56c VA: 0x759508256c
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a6a6a4 VA: 0x75950826a4
	public override Void Render(RoguelikeMenuSquadViewModel viewModel) { }
	// RVA: 0x2a6aad0 VA: 0x7595082ad0
	public override Void OnClick() { }
	// RVA: 0x2a6ae84 VA: 0x7595082e84
	private Void _OnSquadClicked() { }
	// RVA: 0x2a6b0c4 VA: 0x75950830c4
	public Void .ctor() { }
	// RVA: 0x2a6b170 VA: 0x7595083170
	private static Void .cctor() { }
	// RVA: 0x2a6b2f8 VA: 0x75950832f8
	private Boolean <Init>b__13_0() { }
	// RVA: 0x2a6b32c VA: 0x759508332c
	private Boolean <Init>b__13_1() { }
	// RVA: 0x2a6b33c VA: 0x759508333c
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a6b340 VA: 0x7595083340
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
	// RVA: 0x2a6b348 VA: 0x7595083348
	private Void <>xLuaBaseProxy_OnClick() { }
}
```