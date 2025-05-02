# Rl01OuterBuffSkillMainNode

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `MainNode _mainNode`

- `ProgressNode _progressNode`

- `ProgressBar _progressBar`

- `Int32 _layerIndex`

- `Rl01OuterBuffSkillTreeLine _innerLine`


## Properties

- `Int32 layerIndex`

- `Rl01OuterBuffSkillTreeLine innerLine`


## Methods

- `Int32 get_layerIndex()`

- `Void set_layerIndex(Int32)`

- `Rl01OuterBuffSkillTreeLine get_innerLine()`

- `Void set_innerLine(Rl01OuterBuffSkillTreeLine)`

- `Void <>xLuaBaseProxy_Init(Rl01TopicOuterBuffController, Rl01OuterBuffSkillTreeView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffSkillMainNode : Rl01OuterBuffSkillTreeNode
{
	private MainNode _mainNode; // 0x48
	private ProgressNode _progressNode; // 0x50
	private ProgressBar _progressBar; // 0x58
	private Int32 _layerIndex; // 0x60
	private Rl01OuterBuffSkillTreeLine _innerLine; // 0x68
	private static DelegateBridge __Hotfix0_get_layerIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_layerIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_innerLine; // 0x10
	private static DelegateBridge __Hotfix0_set_innerLine; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0__DoInitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__DoRenderFrontNodeUpgradedStatus; // 0x30
	private static DelegateBridge __Hotfix0__DoRenderIsUpgraded; // 0x38
	private static DelegateBridge __Hotfix0__DoRenderSelection; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Int32 layerIndex { get; set; }
	private Rl01OuterBuffSkillTreeLine innerLine { get; set; }

	// RVA: 0x26cca94 VA: 0x7594ce4a94
	private Int32 get_layerIndex() { }
	// RVA: 0x26ccafc VA: 0x7594ce4afc
	public Void set_layerIndex(Int32 value) { }
	// RVA: 0x26ccb78 VA: 0x7594ce4b78
	private Rl01OuterBuffSkillTreeLine get_innerLine() { }
	// RVA: 0x26ccbe0 VA: 0x7594ce4be0
	public Void set_innerLine(Rl01OuterBuffSkillTreeLine value) { }
	// RVA: 0x26ccc64 VA: 0x7594ce4c64
	public override Void Init(Rl01TopicOuterBuffController controller, Rl01OuterBuffSkillTreeView outerView) { }
	// RVA: 0x26ccf44 VA: 0x7594ce4f44
	protected override Void _DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel nodeModel) { }
	// RVA: 0x26cd42c VA: 0x7594ce542c
	protected override Void _DoRenderFrontNodeUpgradedStatus(Boolean[] frontIsUpgraded, Int32 changedFrontNodeIndex, RoguelikeTopicDevNodeType changedFrontNodeType, Boolean isInit) { }
	// RVA: 0x26cdae0 VA: 0x7594ce5ae0
	protected override Void _DoRenderIsUpgraded(Boolean isUpgraded, Boolean isInit) { }
	// RVA: 0x26cdc64 VA: 0x7594ce5c64
	protected override Void _DoRenderSelection(Boolean isSelected, Boolean isInit) { }
	// RVA: 0x26cddec VA: 0x7594ce5dec
	public Void .ctor() { }
	// RVA: 0x26cde58 VA: 0x7594ce5e58
	private Void <>xLuaBaseProxy_Init(Rl01TopicOuterBuffController P0, Rl01OuterBuffSkillTreeView P1) { }
}
```