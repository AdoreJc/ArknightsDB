# RoguelikeCommonOuterBuffContentView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Single _paddingRight`


## Methods

- `Void Init(RoguelikeCommonOuterBuffViewModel)`

- `Void Render(RoguelikeCommonOuterBuffViewModel)`

- `Void _InactiveNode(RoguelikeCommonOuterBuffNodeBase)`

- `Void _InitContentWidth(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffContentView : MonoBehaviour, IHotfixable
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

	// RVA: 0x265d9a8 VA: 0x7594c759a8
	public List`1 get_nodes() { }
	// RVA: 0x265da10 VA: 0x7594c75a10
	public Void Init(RoguelikeCommonOuterBuffViewModel viewModel) { }
	// RVA: 0x265e284 VA: 0x7594c76284
	public Void Render(RoguelikeCommonOuterBuffViewModel viewModel) { }
	// RVA: 0x265dd8c VA: 0x7594c75d8c
	private Void _InactiveNode(RoguelikeCommonOuterBuffNodeBase nodeView) { }
	// RVA: 0x265e1a4 VA: 0x7594c761a4
	private Void _InitContentWidth(Single maxAnchorX) { }
	// RVA: 0x265e674 VA: 0x7594c76674
	public Void .ctor() { }
}
```