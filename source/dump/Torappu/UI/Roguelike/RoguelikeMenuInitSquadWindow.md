# RoguelikeMenuInitSquadWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _imageIcon`

- `Text _textName`

- `Text _textUsage`

- `RoguelikeMenuInitDifficultyView _diffView`

- `RoguelikeRelicViewModel m_cachedModel`

- `String m_cachedItemId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuInitSquadWindow : RoguelikeMenuWindow`1
{
	private Image _imageIcon; // 0x28
	private Text _textName; // 0x30
	private Text _textUsage; // 0x38
	private RoguelikeMenuInitDifficultyView _diffView; // 0x40
	private RoguelikeRelicViewModel m_cachedModel; // 0x48
	private String m_cachedItemId; // 0x50
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a733cc VA: 0x759508b3cc
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a73430 VA: 0x759508b430
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a736a8 VA: 0x759508b6a8
	public Void .ctor() { }
}
```