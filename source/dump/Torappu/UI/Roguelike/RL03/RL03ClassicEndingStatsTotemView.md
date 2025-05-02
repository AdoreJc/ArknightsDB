# RL03ClassicEndingStatsTotemView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Text _textTotemNum`

- `SimpleLayoutContent _totemLayoutContent`

- `GridLayoutGroup _totemLayout`

- `Single _minHeight`

- `Single _totemScale`

- `EndingTotemAdapter m_adapter`

- `RL03ClassicEndingStatsTotemViewModel m_cachedModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ClassicEndingStatsTotemView : RoguelikeClassicEndingStatsViewComponent`1
{
	private Text _textTotemNum; // 0x20
	private SimpleLayoutContent _totemLayoutContent; // 0x28
	private GridLayoutGroup _totemLayout; // 0x30
	private Single _minHeight; // 0x38
	private Single _totemScale; // 0x3c
	private EndingTotemAdapter m_adapter; // 0x40
	private RL03ClassicEndingStatsTotemViewModel m_cachedModel; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_CreateVirtualView; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__CalcPrefabHeight; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b92c48 VA: 0x75951aac48
	public override IVirtualView CreateVirtualView(RoguelikeClassicEndingStatsViewComponentBase compPrefab, RoguelikeClassicEndingStatsViewComponentModel model, UIPage page) { }
	// RVA: 0x2b92de0 VA: 0x75951aade0
	protected override Void Render(RL03ClassicEndingStatsTotemViewModel viewModel) { }
	// RVA: 0x2b92fa8 VA: 0x75951aafa8
	private static Single _CalcPrefabHeight(RL03ClassicEndingStatsTotemView prefab, RL03ClassicEndingStatsTotemViewModel viewModel) { }
	// RVA: 0x2b92ed8 VA: 0x75951aaed8
	private Void _InitIfNot() { }
	// RVA: 0x2b93188 VA: 0x75951ab188
	public Void .ctor() { }
}
```