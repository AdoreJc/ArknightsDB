# RoguelikeStatusBarGoldObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textGold`

- `RoguelikeStatusBarTextTweener m_goldTweener`

- `Int32 m_cachedGold`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarGoldObject : RoguelikeMenuObject`1
{
	private static readonly Color COLOR_INCREASE; // 0x0
	private static readonly Color COLOR_DECREASE; // 0x10
	private static readonly Color COLOR_NORMAL; // 0x20
	private Text _textGold; // 0x28
	private RoguelikeStatusBarTextTweener m_goldTweener; // 0x30
	private Int32 m_cachedGold; // 0x38
	private Boolean m_inited; // 0x3c
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_get_menuType; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a6f868 VA: 0x7595087868
	private Void _InitIfNot() { }
	// RVA: 0x2a6fa00 VA: 0x7595087a00
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a6fa78 VA: 0x7595087a78
	public override Void Render(RoguelikeMenuGoldViewModel viewModel) { }
	// RVA: 0x2a6fb88 VA: 0x7595087b88
	public Void .ctor() { }
	// RVA: 0x2a6fc30 VA: 0x7595087c30
	private static Void .cctor() { }
}
```