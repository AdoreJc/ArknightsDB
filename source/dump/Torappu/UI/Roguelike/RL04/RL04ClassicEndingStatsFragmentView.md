# RL04ClassicEndingStatsFragmentView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GridLayoutGroup _layoutGroup`

- `SimpleLayoutContent _content`

- `Text _fragmentCntTxt`

- `Single _minHeight`

- `EndingFragmentAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ClassicEndingStatsFragmentView : RoguelikeClassicEndingStatsViewComponent`1
{
	private GridLayoutGroup _layoutGroup; // 0x20
	private SimpleLayoutContent _content; // 0x28
	private Text _fragmentCntTxt; // 0x30
	private Single _minHeight; // 0x38
	private ListDict`2 m_cachedFragmentItemModelList; // 0x40
	private EndingFragmentAdapter m_adapter; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_CreateVirtualView; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__CalcPrefabHeight; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b111c4 VA: 0x75951291c4
	public override IVirtualView CreateVirtualView(RoguelikeClassicEndingStatsViewComponentBase compPrefab, RoguelikeClassicEndingStatsViewComponentModel viewModel, UIPage page) { }
	// RVA: 0x2b1135c VA: 0x759512935c
	protected override Void Render(RL04ClassicEndingStatsFragmentViewModel viewModel) { }
	// RVA: 0x2b11444 VA: 0x7595129444
	private Void _InitIfNot() { }
	// RVA: 0x2b115a8 VA: 0x75951295a8
	private static Single _CalcPrefabHeight(RL04ClassicEndingStatsFragmentView prefab, RL04ClassicEndingStatsFragmentViewModel viewModel) { }
	// RVA: 0x2b116f4 VA: 0x75951296f4
	public Void .ctor() { }
}
```