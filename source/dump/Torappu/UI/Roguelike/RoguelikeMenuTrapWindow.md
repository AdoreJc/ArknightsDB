# RoguelikeMenuTrapWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _imageIcon`

- `Text _textName`

- `Text _textUsage`

- `RoguelikeTrapViewModel m_cachedModel`

- `String m_cachedItemId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuTrapWindow : RoguelikeMenuWindow`1
{
	private Image _imageIcon; // 0x28
	private Text _textName; // 0x30
	private Text _textUsage; // 0x38
	private RoguelikeTrapViewModel m_cachedModel; // 0x40
	private String m_cachedItemId; // 0x48
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a760b0 VA: 0x759508e0b0
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a76118 VA: 0x759508e118
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a762fc VA: 0x759508e2fc
	public Void .ctor() { }
}
```