# RoguelikeStatusBarLevelWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textNextLevel`

- `Text _textPopulationUp`

- `Text _textSquadUp`

- `Text _textMaxHpUp`

- `RectTransform _panelPopulationUp`

- `RectTransform _panelSquadUp`

- `RectTransform _panelMaxHpUp`


## Methods

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarLevelWindow : RoguelikeMenuWindow`1
{
	private static Vector2 WINDOW_HIDE_POS; // 0x0
	private static Vector2 WINDOW_SHOW_POS; // 0x8
	private Text _textNextLevel; // 0x28
	private Text _textPopulationUp; // 0x30
	private Text _textSquadUp; // 0x38
	private Text _textMaxHpUp; // 0x40
	private RectTransform _panelPopulationUp; // 0x48
	private RectTransform _panelSquadUp; // 0x50
	private RectTransform _panelMaxHpUp; // 0x58
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a76aa4 VA: 0x759508eaa4
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a76b1c VA: 0x759508eb1c
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2a76c68 VA: 0x759508ec68
	public override Void Render(RoguelikeMenuLevelViewModel viewModel) { }
	// RVA: 0x2a77038 VA: 0x759508f038
	public Void .ctor() { }
	// RVA: 0x2a770d8 VA: 0x759508f0d8
	private static Void .cctor() { }
	// RVA: 0x2a77134 VA: 0x759508f134
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```