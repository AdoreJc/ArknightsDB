# RL02ClassicEndingStatsInfoView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Single _preferHeight`

- `Image _imageRelicIcon`

- `Text _textBasicInfo`

- `Text _textEndInfo`

- `Text _textEndDesc`

- `Color _highlightColor`

- `UIAtlasImage _imageUpgradeRank`

- `UIAtlasObject _squadUpgradeRankAtlas`

- `Image _imageIcon`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ClassicEndingStatsInfoView : RoguelikeClassicEndingStatsViewComponent`1
{
	private static Color NORMAL_SQUAD_ICON_COLOR; // 0x0
	private static Color UPGRADABLE_SQUAD_ICON_COLOR; // 0x10
	private Single _preferHeight; // 0x20
	private Image _imageRelicIcon; // 0x28
	private Text _textBasicInfo; // 0x30
	private Text _textEndInfo; // 0x38
	private Text _textEndDesc; // 0x40
	private Color _highlightColor; // 0x48
	private UIAtlasImage _imageUpgradeRank; // 0x58
	private UIAtlasObject _squadUpgradeRankAtlas; // 0x60
	private String[] _squadUpgradeRankImageName; // 0x68
	private Image _imageIcon; // 0x70
	private static DelegateBridge __Hotfix0_CreateVirtualView; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2b5d784 VA: 0x7595175784
	public override IVirtualView CreateVirtualView(RoguelikeClassicEndingStatsViewComponentBase compPrefab, RoguelikeClassicEndingStatsViewComponentModel model, UIPage page) { }
	// RVA: 0x2b5d924 VA: 0x7595175924
	protected override Void Render(RoguelikeClassicEndingStatsInfoViewModel viewModel) { }
	// RVA: 0x2b5dea8 VA: 0x7595175ea8
	public Void .ctor() { }
	// RVA: 0x2b5df48 VA: 0x7595175f48
	private static Void .cctor() { }
}
```