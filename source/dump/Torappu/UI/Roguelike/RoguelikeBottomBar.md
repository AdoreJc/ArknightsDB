# RoguelikeBottomBar

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIAnimationLocation _animFold`

- `RectTransform _pnlBottomBar`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeDungeonController, StateEngine, RoguelikeMenu, RoguelikeMenuViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeBottomBar : RoguelikeMenuBar
{
	private const String FOLD_ANIM_PARAM; // 0x0
	private static readonly Type[] SMALL_MENU_STATES; // 0x0
	private UIAnimationLocation _animFold; // 0x70
	private RectTransform _pnlBottomBar; // 0x80
	private static DelegateBridge __Hotfix0_GenerateUISwitchTween; // 0x8
	private static DelegateBridge __Hotfix0_RefreshMenuBar; // 0x10
	private static DelegateBridge __Hotfix0_AchieveShowStatus; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2a3d2dc VA: 0x75950552dc
	protected override UISwitchTween GenerateUISwitchTween() { }
	// RVA: 0x2a3d418 VA: 0x7595055418
	protected override Void RefreshMenuBar(StateTransitionParam transitionParam, RoguelikeMenuAdapter topAdapter, Boolean fastMode) { }
	// RVA: 0x2a3d58c VA: 0x759505558c
	protected override Boolean AchieveShowStatus(StateTransitionParam transitionParam, RoguelikeMenuAdapter topAdapter) { }
	// RVA: 0x2a3d630 VA: 0x7595055630
	public override Void Init(RoguelikeDungeonController controller, StateEngine stateEngine, RoguelikeMenu menu, RoguelikeMenuViewModel viewModel) { }
	// RVA: 0x2a3d708 VA: 0x7595055708
	public Void .ctor() { }
	// RVA: 0x2a3d788 VA: 0x7595055788
	private static Void .cctor() { }
	// RVA: 0x2a3d8a0 VA: 0x75950558a0
	private Void <>xLuaBaseProxy_Init(RoguelikeDungeonController P0, StateEngine P1, RoguelikeMenu P2, RoguelikeMenuViewModel P3) { }
}
```