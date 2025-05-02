# RoguelikeStatusBarHpObjectWithMaxHp

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textHp`

- `Text _textMaxHp`

- `Text _textShield`

- `GameObject _pnlShield`

- `Button _btnHpDetail`

- `GameObject _panelNormal`

- `GameObject _panelHidden`

- `RoguelikeStatusBarTextTweener m_hpTweener`

- `RoguelikeStatusBarTextTweener m_maxHpTweener`

- `RoguelikeStatusBarTextTweener m_shieldTweener`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void _RenderNormal(RoguelikeStatusBarHpWithMaxHpViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarHpObjectWithMaxHp : RoguelikeMenuObject`1
{
	private static readonly Color COLOR_INCREASE; // 0x0
	private static readonly Color COLOR_DECREASE; // 0x10
	private static readonly Color COLOR_NORMAL; // 0x20
	private static readonly Color COLOR_SHIELD; // 0x30
	private Text _textHp; // 0x28
	private Text _textMaxHp; // 0x30
	private Text _textShield; // 0x38
	private GameObject _pnlShield; // 0x40
	private Button _btnHpDetail; // 0x48
	private GameObject _panelNormal; // 0x50
	private GameObject _panelHidden; // 0x58
	private RoguelikeStatusBarTextTweener m_hpTweener; // 0x60
	private RoguelikeStatusBarTextTweener m_maxHpTweener; // 0x68
	private RoguelikeStatusBarTextTweener m_shieldTweener; // 0x70
	private Boolean m_inited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_get_menuType; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x50
	private static DelegateBridge __Hotfix0__RenderNormal; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a700dc VA: 0x75950880dc
	private Void _InitIfNot() { }
	// RVA: 0x2a70344 VA: 0x7595088344
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a703bc VA: 0x75950883bc
	public override Void Render(RoguelikeStatusBarHpWithMaxHpViewModel viewModel) { }
	// RVA: 0x2a70508 VA: 0x7595088508
	private Void _RenderNormal(RoguelikeStatusBarHpWithMaxHpViewModel viewModel) { }
	// RVA: 0x2a70624 VA: 0x7595088624
	public Void .ctor() { }
	// RVA: 0x2a706c4 VA: 0x75950886c4
	private static Void .cctor() { }
}
```