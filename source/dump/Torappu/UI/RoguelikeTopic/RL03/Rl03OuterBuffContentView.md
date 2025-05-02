# Rl03OuterBuffContentView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Single _paddingRight`


## Methods

- `Void Init(Rl03OuterBuffViewModel)`

- `Void Render(Rl03OuterBuffViewModel)`

- `Void _InactiveNode(Rl03OuterBuffNodeBase)`

- `Void _InitContentWidth(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffContentView : MonoBehaviour, IHotfixable
{
	private List`1 _nodes; // 0x18
	private Single _paddingRight; // 0x20
	public Action`1 onNodeClick; // 0x28
	private const Single MIN_NODE_POS; // 0x0
	private static DelegateBridge __Hotfix0_get_nodes; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InactiveNode; // 0x18
	private static DelegateBridge __Hotfix0__InitContentWidth; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public List`1 nodes { get; }

	// RVA: 0x26a77b8 VA: 0x7594cbf7b8
	public List`1 get_nodes() { }
	// RVA: 0x26a7820 VA: 0x7594cbf820
	public Void Init(Rl03OuterBuffViewModel viewModel) { }
	// RVA: 0x26a7f64 VA: 0x7594cbff64
	public Void Render(Rl03OuterBuffViewModel viewModel) { }
	// RVA: 0x26a7bac VA: 0x7594cbfbac
	private Void _InactiveNode(Rl03OuterBuffNodeBase nodeView) { }
	// RVA: 0x26a7e84 VA: 0x7594cbfe84
	private Void _InitContentWidth(Single maxAnchorX) { }
	// RVA: 0x26a8240 VA: 0x7594cc0240
	public Void .ctor() { }
}
```