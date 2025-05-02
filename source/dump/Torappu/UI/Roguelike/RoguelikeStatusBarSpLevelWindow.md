# RoguelikeStatusBarSpLevelWindow

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
public class RoguelikeStatusBarSpLevelWindow : RoguelikeMenuWindow`1
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

	// RVA: 0x2a77138 VA: 0x759508f138
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a771b0 VA: 0x759508f1b0
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2a772fc VA: 0x759508f2fc
	public override Void Render(RoguelikeMenuLevelViewModel viewModel) { }
	// RVA: 0x2a776cc VA: 0x759508f6cc
	public Void .ctor() { }
	// RVA: 0x2a7776c VA: 0x759508f76c
	private static Void .cctor() { }
	// RVA: 0x2a777c8 VA: 0x759508f7c8
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```