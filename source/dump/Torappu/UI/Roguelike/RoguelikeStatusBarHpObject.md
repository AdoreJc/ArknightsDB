# RoguelikeStatusBarHpObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textHp`

- `Text _textShieldHp`

- `Button _btnHpDetail`

- `GameObject _pnlShieldHp`

- `RoguelikeStatusBarTextTweener m_hpTweener`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarHpObject : RoguelikeMenuObject`1
{
	private static readonly Color COLOR_INCREASE; // 0x0
	private static readonly Color COLOR_DECREASE; // 0x10
	private static readonly Color COLOR_NORMAL; // 0x20
	private Text _textHp; // 0x28
	private Text _textShieldHp; // 0x30
	private Button _btnHpDetail; // 0x38
	private GameObject _pnlShieldHp; // 0x40
	private RoguelikeStatusBarTextTweener m_hpTweener; // 0x48
	private Boolean m_inited; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_get_menuType; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a6fc98 VA: 0x7595087c98
	private Void _InitIfNot() { }
	// RVA: 0x2a6fe30 VA: 0x7595087e30
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a6fea8 VA: 0x7595087ea8
	public override Void Render(RoguelikeMenuHpViewModel viewModel) { }
	// RVA: 0x2a6ffd0 VA: 0x7595087fd0
	public Void .ctor() { }
	// RVA: 0x2a70070 VA: 0x7595088070
	private static Void .cctor() { }
}
```