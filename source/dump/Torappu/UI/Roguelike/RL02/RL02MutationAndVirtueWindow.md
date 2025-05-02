# RL02MutationAndVirtueWindow

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `SimpleLayoutContent _mutationGroup`

- `SimpleLayoutContent _virtueGroup`

- `GameObject _mutationTitle`

- `GameObject _virtueTitle`

- `RL02MutationAndVirtueViewModel m_cachedModel`

- `MutationAdapter m_mutationAdapter`

- `VirtueAdapter m_virtueAdapter`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MutationAndVirtueWindow : RoguelikeMenuWindow`1
{
	private SimpleLayoutContent _mutationGroup; // 0x28
	private SimpleLayoutContent _virtueGroup; // 0x30
	private GameObject _mutationTitle; // 0x38
	private GameObject _virtueTitle; // 0x40
	private RL02MutationAndVirtueViewModel m_cachedModel; // 0x48
	private MutationAdapter m_mutationAdapter; // 0x50
	private VirtueAdapter m_virtueAdapter; // 0x58
	private Boolean m_inited; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_selectType; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b6f390 VA: 0x7595187390
	private Void _InitIfNot() { }
	// RVA: 0x2b6f5dc VA: 0x75951875dc
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b6f644 VA: 0x7595187644
	public override Void Render(RL02MutationAndVirtueViewModel viewModel) { }
	// RVA: 0x2b6f7bc VA: 0x75951877bc
	public Void .ctor() { }
}
```