# RoguelikeMenuTrapObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `Image _imageIcon`

- `UIAnimationLocation _showAnim`

- `RoguelikeTrapViewModel m_cachedModel`

- `String m_cachedItemId`

- `ShowSwitchTween m_showSwitchTween`

- `Tween m_refreshTween`


## Methods

- `Void _RefreshTrap(String, Boolean)`

- `Void _RenderTrap(String)`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuTrapObject : RoguelikeMenuObject`1
{
	private const Single SHOW_ANIM_DURATION; // 0x0
	private const Int32 IMAGE_ICON_ORIG_Y; // 0x0
	private const Int32 IMAGE_ICON_DOWN_Y; // 0x0
	private const Int32 IMAGE_ICON_UP_Y; // 0x0
	private const Single IMAGE_ICON_ALPHA; // 0x0
	private const Single SWITCH_ANIM_DURATION; // 0x0
	private CanvasGroup _pnlContent; // 0x28
	private Image _imageIcon; // 0x30
	private UIAnimationLocation _showAnim; // 0x38
	private RoguelikeTrapViewModel m_cachedModel; // 0x48
	private String m_cachedItemId; // 0x50
	private ShowSwitchTween m_showSwitchTween; // 0x58
	private Tween m_refreshTween; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_get_menuType; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RefreshTrap; // 0x18
	private static DelegateBridge __Hotfix0__RenderTrap; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a6eb4c VA: 0x7595086b4c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a6eca0 VA: 0x7595086ca0
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a6ed08 VA: 0x7595086d08
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a6ee0c VA: 0x7595086e0c
	private Void _RefreshTrap(String itemId, Boolean isInit) { }
	// RVA: 0x2a6f26c VA: 0x759508726c
	private Void _RenderTrap(String itemId) { }
	// RVA: 0x2a6f32c VA: 0x759508732c
	public Void .ctor() { }
	// RVA: 0x2a6f3bc VA: 0x75950873bc
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```