# RoguelikeMenuInitSquadWithDifficultyObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _pnlContent`

- `Image _imgIcon`

- `GameObject _panelDifficulty`

- `UIAtlasImage _imgDifficulty`

- `UIAtlasObject _difficultyAtlasObject`

- `Text _txtDifficulty`

- `GameObject _panelBandRank`

- `UIAtlasImage _imgBandRank`

- `UIAtlasObject _bandRankAtlasObject`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `String m_cachedInitItemId`

- `Int32 m_cachedDifficultyLevel`

- `Int32 m_cachedBandRank`


## Methods

- `Void _RenderInitSquadWithDifficulty(RoguelikeMenuRelicViewModel)`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuInitSquadWithDifficultyObject : RoguelikeMenuObject`1
{
	private const String BAND_RANK_FORMAT; // 0x0
	private static Vector2 HIDE_POS; // 0x0
	private static Vector2 SHOW_POS; // 0x8
	private CanvasGroup _pnlContent; // 0x28
	private Image _imgIcon; // 0x30
	private GameObject _panelDifficulty; // 0x38
	private UIAtlasImage _imgDifficulty; // 0x40
	private UIAtlasObject _difficultyAtlasObject; // 0x48
	private Text _txtDifficulty; // 0x50
	private GameObject _panelBandRank; // 0x58
	private UIAtlasImage _imgBandRank; // 0x60
	private UIAtlasObject _bandRankAtlasObject; // 0x68
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x70
	private String m_cachedInitItemId; // 0x78
	private Int32 m_cachedDifficultyLevel; // 0x80
	private Int32 m_cachedBandRank; // 0x84
	private static DelegateBridge __Hotfix0_get_menuType; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__RenderInitSquadWithDifficulty; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a40430 VA: 0x7595058430
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a404a4 VA: 0x75950584a4
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a405f0 VA: 0x75950585f0
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a406e4 VA: 0x75950586e4
	private Void _RenderInitSquadWithDifficulty(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a40af8 VA: 0x7595058af8
	public Void .ctor() { }
	// RVA: 0x2a40b98 VA: 0x7595058b98
	private static Void .cctor() { }
	// RVA: 0x2a40bf4 VA: 0x7595058bf4
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```