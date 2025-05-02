# RoguelikeMenuRelicObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `GameObject _pnlBack`

- `Text _textNum`

- `UIAnimationLocation _animNewRelic`

- `UIAnimationLocation _animShow`

- `Boolean _showTrap`

- `GameObject _invalidRaycastBlocker`

- `AnimationSwitchTween m_showSwitchTween`

- `Tween m_newRelicTween`

- `RoguelikeMenuRelicViewModel m_cachedModel`

- `Boolean m_cachedStateShow`

- `Int32 m_cachedRelicCount`


## Methods

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Int32 _GetRelicCount(RoguelikeMenuRelicViewModel)`

- `Void _RenderNewRelic()`

- `Boolean <Init>b__15_0()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicObject : RoguelikeMenuObject`1
{
	private const Single ANIM_NEW_RELIC_DURATION; // 0x0
	private static readonly Type[] STATES_NOT_SHOW; // 0x0
	private CanvasGroup _pnlContent; // 0x28
	private GameObject _pnlBack; // 0x30
	private Text _textNum; // 0x38
	private UIAnimationLocation _animNewRelic; // 0x40
	private UIAnimationLocation _animShow; // 0x50
	private Boolean _showTrap; // 0x60
	private GameObject _invalidRaycastBlocker; // 0x68
	private AnimationSwitchTween m_showSwitchTween; // 0x70
	private Tween m_newRelicTween; // 0x78
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0x80
	private RoguelikeMenuRelicViewModel m_cachedModel; // 0x88
	private Boolean m_cachedStateShow; // 0x90
	private Int32 m_cachedRelicCount; // 0x94
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_get_menuType; // 0x10
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x18
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x20
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__GetRelicCount; // 0x38
	private static DelegateBridge __Hotfix0__RenderNewRelic; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a68cf8 VA: 0x7595080cf8
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a68f5c VA: 0x7595080f5c
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a68fd4 VA: 0x7595080fd4
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2a6908c VA: 0x759508108c
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2a691d8 VA: 0x75950811d8
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a69420 VA: 0x7595081420
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a695b8 VA: 0x75950815b8
	private Int32 _GetRelicCount(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a69658 VA: 0x7595081658
	private Void _RenderNewRelic() { }
	// RVA: 0x2a698b8 VA: 0x75950818b8
	public Void .ctor() { }
	// RVA: 0x2a69958 VA: 0x7595081958
	private static Void .cctor() { }
	// RVA: 0x2a69ac8 VA: 0x7595081ac8
	private Boolean <Init>b__15_0() { }
	// RVA: 0x2a69b18 VA: 0x7595081b18
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a69b1c VA: 0x7595081b1c
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
	// RVA: 0x2a69b24 VA: 0x7595081b24
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
}
```