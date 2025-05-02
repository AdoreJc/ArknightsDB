# RL01MenuCapsuleWindow

**Namespace:** `Torappu.UI.Roguelike.RL01`


## Fields

- `Image _imageIcon`

- `Text _textName`

- `Text _textUsage`

- `Image _imageBkg`

- `RoguelikeCapsuleViewModel m_cachedModel`

- `String m_cachedItemId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL01
public class RL01MenuCapsuleWindow : RoguelikeMenuWindow`1
{
	private Image _imageIcon; // 0x28
	private Text _textName; // 0x30
	private Text _textUsage; // 0x38
	private Image _imageBkg; // 0x40
	private RoguelikeCapsuleViewModel m_cachedModel; // 0x48
	private String m_cachedItemId; // 0x50
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b7aaa0 VA: 0x7595192aa0
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b7ab08 VA: 0x7595192b08
	public override Void Render(RL01CapsuleViewModel viewModel) { }
	// RVA: 0x2b7ad04 VA: 0x7595192d04
	public Void .ctor() { }
}
```