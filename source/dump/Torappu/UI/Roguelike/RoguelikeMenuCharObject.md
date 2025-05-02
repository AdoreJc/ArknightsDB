# RoguelikeMenuCharObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `GameObject _pnlBack`

- `Text _textCharCount`

- `UIAnimationLocation _animStatusHide`

- `UIAnimationLocation _animStatusForbidden`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `RoguelikeMenuCharViewModel m_cachedModel`

- `RoguelikeMenuCharObjectStatus m_cachedStatus`

- `Boolean m_cachedStateShow`


## Methods

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderPanelBack(Boolean, Boolean)`

- `Void _RenderValid(Boolean, Boolean)`

- `Void _RenderForbidden(Boolean, Boolean)`

- `Void _UpdateRenderers()`

- `Void _Render(Boolean)`

- `Void _OnCharRepoClicked()`

- `Boolean <Init>b__14_0()`

- `Boolean <Init>b__14_1()`

- `Boolean <Init>b__14_2()`

- `Boolean <Init>b__14_3()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`

- `Void <>xLuaBaseProxy_OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuCharObject : RoguelikeMenuObject`1
{
	private static Vector2 HIDE_POS; // 0x0
	private static Vector2 SHOW_POS; // 0x8
	private static readonly Type[] STATES_NOT_SHOW; // 0x10
	private CanvasGroup _pnlContent; // 0x28
	private GameObject _pnlBack; // 0x30
	private Text _textCharCount; // 0x38
	private UIAnimationLocation _animStatusHide; // 0x40
	private UIAnimationLocation _animStatusForbidden; // 0x50
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x60
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0x68
	private List`1 m_renderers; // 0x70
	private RoguelikeMenuCharViewModel m_cachedModel; // 0x78
	private RoguelikeMenuCharObjectStatus m_cachedStatus; // 0x80
	private Boolean m_cachedStateShow; // 0x84
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_get_menuType; // 0x20
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x28
	private static DelegateBridge __Hotfix0__RenderPanelBack; // 0x30
	private static DelegateBridge __Hotfix0__RenderValid; // 0x38
	private static DelegateBridge __Hotfix0__RenderForbidden; // 0x40
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x58
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x68
	private static DelegateBridge __Hotfix0_OnClick; // 0x70
	private static DelegateBridge __Hotfix0__OnCharRepoClicked; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a3e73c VA: 0x759505673c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a3ecb0 VA: 0x7595056cb0
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a3ed28 VA: 0x7595056d28
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2a3ede0 VA: 0x7595056de0
	private Void _RenderPanelBack(Boolean show, Boolean fastMode) { }
	// RVA: 0x2a3ee7c VA: 0x7595056e7c
	private Void _RenderValid(Boolean valid, Boolean fastMode) { }
	// RVA: 0x2a3ef34 VA: 0x7595056f34
	private Void _RenderForbidden(Boolean forbidden, Boolean fastMode) { }
	// RVA: 0x2a3f048 VA: 0x7595057048
	private Void _UpdateRenderers() { }
	// RVA: 0x2a3f260 VA: 0x7595057260
	private Void _Render(Boolean fastMode) { }
	// RVA: 0x2a3f4b0 VA: 0x75950574b0
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2a3f580 VA: 0x7595057580
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a3f6c0 VA: 0x75950576c0
	public override Void Render(RoguelikeMenuCharViewModel viewModel) { }
	// RVA: 0x2a3f7ac VA: 0x75950577ac
	public override Void OnClick() { }
	// RVA: 0x2a3f8e8 VA: 0x75950578e8
	private Void _OnCharRepoClicked() { }
	// RVA: 0x2a3fab4 VA: 0x7595057ab4
	public Void .ctor() { }
	// RVA: 0x2a3fb54 VA: 0x7595057b54
	private static Void .cctor() { }
	// RVA: 0x2a3fcdc VA: 0x7595057cdc
	private Boolean <Init>b__14_0() { }
	// RVA: 0x2a3fd2c VA: 0x7595057d2c
	private Boolean <Init>b__14_1() { }
	// RVA: 0x2a3fd50 VA: 0x7595057d50
	private Boolean <Init>b__14_2() { }
	// RVA: 0x2a3fd60 VA: 0x7595057d60
	private Boolean <Init>b__14_3() { }
	// RVA: 0x2a3fd70 VA: 0x7595057d70
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a3fd78 VA: 0x7595057d78
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
	// RVA: 0x2a3fd84 VA: 0x7595057d84
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
	// RVA: 0x2a3fd90 VA: 0x7595057d90
	private Void <>xLuaBaseProxy_OnClick() { }
}
```