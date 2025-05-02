# RoguelikeStatusBarSpLevelObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textLevel`

- `Text _textExp`

- `Image _imageExp`

- `GameObject _gameObjectNextLevel`

- `Color _colorCurExpText`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarSpLevelObject : RoguelikeMenuObject`1
{
	private const String RICH_TEXT_EXP; // 0x0
	private Text _textLevel; // 0x28
	private Text _textExp; // 0x30
	private Image _imageExp; // 0x38
	private GameObject _gameObjectNextLevel; // 0x40
	private Color _colorCurExpText; // 0x48
	private static DelegateBridge __Hotfix0_get_menuType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a70fa8 VA: 0x7595088fa8
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a71010 VA: 0x7595089010
	public override Void Render(RoguelikeMenuLevelViewModel viewModel) { }
	// RVA: 0x2a711f4 VA: 0x75950891f4
	public Void .ctor() { }
}
```