# RL01MenuCapsuleObject

**Namespace:** `Torappu.UI.Roguelike.RL01`


## Fields

- `CanvasGroup _canvasActive`

- `CanvasGroup _pnlContent`

- `Image _imageIcon`

- `UIAtlasImage _imageMask`

- `UIAtlasImage _imageLight`

- `Text _textName`

- `RoguelikeCapsuleViewModel m_cachedModel`

- `String m_cachedItemId`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `ActiveShowSwitchTween m_activeShowSwitchTween`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL01
public class RL01MenuCapsuleObject : RoguelikeMenuObject`1
{
	private static Vector2 HIDE_POS; // 0x0
	private static Vector2 SHOW_POS; // 0x8
	private CanvasGroup _canvasActive; // 0x28
	private CanvasGroup _pnlContent; // 0x30
	private Image _imageIcon; // 0x38
	private UIAtlasImage _imageMask; // 0x40
	private UIAtlasImage _imageLight; // 0x48
	private Text _textName; // 0x50
	private RoguelikeCapsuleViewModel m_cachedModel; // 0x58
	private String m_cachedItemId; // 0x60
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x68
	private ActiveShowSwitchTween m_activeShowSwitchTween; // 0x70
	private static DelegateBridge __Hotfix0_get_menuType; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b78da4 VA: 0x7595190da4
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b78e1c VA: 0x7595190e1c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b79038 VA: 0x7595191038
	public override Void Render(RL01CapsuleViewModel viewModel) { }
	// RVA: 0x2b792a4 VA: 0x75951912a4
	public Void .ctor() { }
	// RVA: 0x2b79344 VA: 0x7595191344
	private static Void .cctor() { }
	// RVA: 0x2b793a0 VA: 0x75951913a0
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```