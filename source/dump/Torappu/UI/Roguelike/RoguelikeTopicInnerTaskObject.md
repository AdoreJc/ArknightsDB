# RoguelikeTopicInnerTaskObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIAnimationLocation _animExpand`

- `GameObject _taskContentBkg`

- `Button _buttonExpand`

- `SimpleLayoutContent _taskLayoutContent`

- `Graphic _graphicLight`

- `GameObject _panelListDeco`

- `GameObject _panelListDecoNormal`

- `GameObject _panelListDecoCompleted`

- `Color _monthTaskThemeColor`

- `Color _monthTaskCurColor`

- `GameObject _pnlMonthCompleted`

- `GameObject _pnlMonthNormal`

- `Color _challengeTaskThemeColor`

- `Color _challengeTaskCurColor`

- `GameObject _pnlChallengeCompleted`

- `GameObject _pnlChallengeNormal`

- `UISwitchTween m_expandSwitchTween`

- `TaskAdapter m_taskAdapter`

- `RoguelikeTopicInnerTaskViewModel m_viewModel`

- `Color m_themeColor`

- `Color m_curColor`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTopicInnerTaskObject : RoguelikeMenuObject`1
{
	private const Single EXPAND_ANIM_DURATION; // 0x0
	private UIAnimationLocation _animExpand; // 0x28
	private GameObject _taskContentBkg; // 0x38
	private Button _buttonExpand; // 0x40
	private SimpleLayoutContent _taskLayoutContent; // 0x48
	private Graphic _graphicLight; // 0x50
	private GameObject _panelListDeco; // 0x58
	private GameObject _panelListDecoNormal; // 0x60
	private GameObject _panelListDecoCompleted; // 0x68
	private Color _monthTaskThemeColor; // 0x70
	private Color _monthTaskCurColor; // 0x80
	private GameObject _pnlMonthCompleted; // 0x90
	private GameObject _pnlMonthNormal; // 0x98
	private Color _challengeTaskThemeColor; // 0xa0
	private Color _challengeTaskCurColor; // 0xb0
	private GameObject _pnlChallengeCompleted; // 0xc0
	private GameObject _pnlChallengeNormal; // 0xc8
	private UISwitchTween m_expandSwitchTween; // 0xd0
	private TaskAdapter m_taskAdapter; // 0xd8
	private RoguelikeTopicInnerTaskViewModel m_viewModel; // 0xe0
	private Color m_themeColor; // 0xe8
	private Color m_curColor; // 0xf8
	private static DelegateBridge __Hotfix0_get_menuType; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x10
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a71e14 VA: 0x7595089e14
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a71e7c VA: 0x7595089e7c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a720f8 VA: 0x759508a0f8
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a721a0 VA: 0x759508a1a0
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2a72260 VA: 0x759508a260
	public override Void Render(RoguelikeTopicInnerTaskViewModel viewModel) { }
	// RVA: 0x2a72488 VA: 0x759508a488
	public Void .ctor() { }
	// RVA: 0x2a72518 VA: 0x759508a518
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a7251c VA: 0x759508a51c
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
	// RVA: 0x2a72524 VA: 0x759508a524
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
}
```