# RoguelikeStatusBarKeyObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textKey`

- `RoguelikeStatusBarTextTweener m_keyTweener`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarKeyObject : RoguelikeMenuObject`1
{
	private static readonly Color COLOR_INCREASE; // 0x0
	private static readonly Color COLOR_DECREASE; // 0x10
	private static readonly Color COLOR_NORMAL; // 0x20
	private Text _textKey; // 0x28
	private RoguelikeStatusBarTextTweener m_keyTweener; // 0x30
	private Boolean m_inited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_get_menuType; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a70740 VA: 0x7595088740
	private Void _InitIfNot() { }
	// RVA: 0x2a708d8 VA: 0x75950888d8
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a70950 VA: 0x7595088950
	public override Void Render(RoguelikeMenuKeyViewModel viewModel) { }
	// RVA: 0x2a70a04 VA: 0x7595088a04
	public Void .ctor() { }
	// RVA: 0x2a70aa4 VA: 0x7595088aa4
	private static Void .cctor() { }
}
```