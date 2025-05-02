# RoguelikeMenuInitSquadObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `Image _imageIcon`

- `UIAtlasImage _imageUpgradeRank`

- `UIAtlasObject _squadUpgradeRankAtlas`

- `RoguelikeRelicViewModel m_cachedModel`

- `String m_cachedItemId`

- `FadeTranslationSwitchTween m_showSwitchTween`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuInitSquadObject : RoguelikeMenuObject`1
{
	private static Vector2 HIDE_POS; // 0x0
	private static Vector2 SHOW_POS; // 0x8
	private static Color NORMAL_SQUAD_ICON_COLOR; // 0x10
	private static Color UPGRADABLE_SQUAD_ICON_COLOR; // 0x20
	private CanvasGroup _pnlContent; // 0x28
	private Image _imageIcon; // 0x30
	private UIAtlasImage _imageUpgradeRank; // 0x38
	private UIAtlasObject _squadUpgradeRankAtlas; // 0x40
	private String[] _squadUpgradeRankImageName; // 0x48
	private RoguelikeRelicViewModel m_cachedModel; // 0x50
	private String m_cachedItemId; // 0x58
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_get_menuType; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a3fd98 VA: 0x7595057d98
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a3fee4 VA: 0x7595057ee4
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a3ff58 VA: 0x7595057f58
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a4030c VA: 0x759505830c
	public Void .ctor() { }
	// RVA: 0x2a403ac VA: 0x75950583ac
	private static Void .cctor() { }
	// RVA: 0x2a40428 VA: 0x7595058428
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```