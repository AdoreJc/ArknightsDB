# RoguelikeClassicEndingStatsCharGroupView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textCharNum`

- `SimpleLayoutContent _charLayoutContent`

- `GridLayoutGroup _charLayout`

- `Single _minHeight`

- `EndingCharAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingStatsCharGroupView : RoguelikeClassicEndingStatsViewComponent`1
{
	private Text _textCharNum; // 0x20
	private SimpleLayoutContent _charLayoutContent; // 0x28
	private GridLayoutGroup _charLayout; // 0x30
	private Single _minHeight; // 0x38
	private EndingCharAdapter m_adapter; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0_CreateVirtualView; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__CalcPrefabHeight; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2a2a410 VA: 0x7595042410
	public override IVirtualView CreateVirtualView(RoguelikeClassicEndingStatsViewComponentBase compPrefab, RoguelikeClassicEndingStatsViewComponentModel model, UIPage page) { }
	// RVA: 0x2a2a5a8 VA: 0x75950425a8
	protected override Void Render(RoguelikeClassicEndingStatsCharGroupModel viewModel) { }
	// RVA: 0x2a2a7b8 VA: 0x75950427b8
	private static Single _CalcPrefabHeight(RoguelikeClassicEndingStatsCharGroupView prefab, RoguelikeClassicEndingStatsCharGroupModel viewModel) { }
	// RVA: 0x2a2a6a0 VA: 0x75950426a0
	private Void _InitIfNot() { }
	// RVA: 0x2a2a904 VA: 0x7595042904
	public Void .ctor() { }
}
```