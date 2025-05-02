# RoguelikeClassicEndingStatsRelicGroupView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textRelicNum`

- `SimpleLayoutContent _relicLayoutContent`

- `GridLayoutGroup _relicLayout`

- `Single _minHeight`

- `Boolean _showTrap`

- `EndingRelicAdapter m_adapter`

- `RoguelikeClassicEndingStatsRelicGroupViewModel m_cachedModel`

- `Boolean m_isInited`


## Properties

- `Boolean showTrap`


## Methods

- `Boolean get_showTrap()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingStatsRelicGroupView : RoguelikeClassicEndingStatsViewComponent`1
{
	private Text _textRelicNum; // 0x20
	private SimpleLayoutContent _relicLayoutContent; // 0x28
	private GridLayoutGroup _relicLayout; // 0x30
	private Single _minHeight; // 0x38
	private Boolean _showTrap; // 0x3c
	private EndingRelicAdapter m_adapter; // 0x40
	private RoguelikeClassicEndingStatsRelicGroupViewModel m_cachedModel; // 0x48
	private List`1 m_wholeRelicViewModels; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0_get_showTrap; // 0x0
	private static DelegateBridge __Hotfix0_CreateVirtualView; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__CalcPrefabHeight; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean showTrap { get; }

	// RVA: 0x2a2b6d8 VA: 0x75950436d8
	public Boolean get_showTrap() { }
	// RVA: 0x2a2b740 VA: 0x7595043740
	public override IVirtualView CreateVirtualView(RoguelikeClassicEndingStatsViewComponentBase compPrefab, RoguelikeClassicEndingStatsViewComponentModel model, UIPage page) { }
	// RVA: 0x2a2b8d8 VA: 0x75950438d8
	protected override Void Render(RoguelikeClassicEndingStatsRelicGroupViewModel viewModel) { }
	// RVA: 0x2a2badc VA: 0x7595043adc
	private static Single _CalcPrefabHeight(RoguelikeClassicEndingStatsRelicGroupView prefab, RoguelikeClassicEndingStatsRelicGroupViewModel viewModel) { }
	// RVA: 0x2a2ba0c VA: 0x7595043a0c
	private Void _InitIfNot() { }
	// RVA: 0x2a2bcbc VA: 0x7595043cbc
	public Void .ctor() { }
}
```