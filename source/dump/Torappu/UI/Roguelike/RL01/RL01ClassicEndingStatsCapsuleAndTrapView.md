# RL01ClassicEndingStatsCapsuleAndTrapView

**Namespace:** `Torappu.UI.Roguelike.RL01`


## Fields

- `Text _textCapsuleNum`

- `SimpleLayoutContent _capsuleLayoutContent`

- `GridLayoutGroup _capsuleLayout`

- `Single _capsuleMinHeight`

- `Text _textTrapNum`

- `SimpleLayoutContent _trapLayoutContent`

- `GridLayoutGroup _trapLayout`

- `Single _trapMinHeight`

- `EndingCapsuleAdapter m_capsuleAdapter`

- `EndingTrapAdapter m_trapAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL01
public class RL01ClassicEndingStatsCapsuleAndTrapView : RoguelikeClassicEndingStatsViewComponent`1
{
	private Text _textCapsuleNum; // 0x20
	private SimpleLayoutContent _capsuleLayoutContent; // 0x28
	private GridLayoutGroup _capsuleLayout; // 0x30
	private Single _capsuleMinHeight; // 0x38
	private Text _textTrapNum; // 0x40
	private SimpleLayoutContent _trapLayoutContent; // 0x48
	private GridLayoutGroup _trapLayout; // 0x50
	private Single _trapMinHeight; // 0x58
	private EndingCapsuleAdapter m_capsuleAdapter; // 0x60
	private EndingTrapAdapter m_trapAdapter; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0_CreateVirtualView; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__CalcPrefabHeight; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b75530 VA: 0x759518d530
	public override IVirtualView CreateVirtualView(RoguelikeClassicEndingStatsViewComponentBase compPrefab, RoguelikeClassicEndingStatsViewComponentModel model, UIPage page) { }
	// RVA: 0x2b756c8 VA: 0x759518d6c8
	protected override Void Render(RL01ClassicEndingStatsCapsuleAndTrapViewModel viewModel) { }
	// RVA: 0x2b759e4 VA: 0x759518d9e4
	private static Single _CalcPrefabHeight(RL01ClassicEndingStatsCapsuleAndTrapView prefab, RL01ClassicEndingStatsCapsuleAndTrapViewModel viewModel) { }
	// RVA: 0x2b75834 VA: 0x759518d834
	private Void _InitIfNot() { }
	// RVA: 0x2b75cb4 VA: 0x759518dcb4
	public Void .ctor() { }
}
```