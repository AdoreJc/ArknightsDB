# Rl03OuterBuffNormalNodeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `String m_topicId`

- `String m_buffId`

- `String m_buffName`

- `String m_buffDesc`

- `String m_iconId`

- `String m_groupId`

- `RL03DevelopmentNodeType m_nodeType`

- `Boolean m_isUnlock`

- `Boolean m_isActive`

- `Boolean m_isInGame`

- `Int32 m_tokenCost`


## Properties

- `String buffDesc`

- `Boolean isUnlock`

- `Boolean isInGame`

- `Int32 tokenCost`


## Methods

- `String get_buffDesc()`

- `Boolean get_isUnlock()`

- `Boolean get_isInGame()`

- `Int32 get_tokenCost()`

- `Void _AddDiffFrontNode(RL03DevDifficultyNodeInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffNormalNodeViewModel : Rl03OuterBuffNodeBaseViewModel
{
	private String m_topicId; // 0x10
	private String m_buffId; // 0x18
	private String m_buffName; // 0x20
	private String m_buffDesc; // 0x28
	private String m_iconId; // 0x30
	private String m_groupId; // 0x38
	private RL03DevelopmentNodeType m_nodeType; // 0x40
	private Boolean m_isUnlock; // 0x44
	private Boolean m_isActive; // 0x45
	private Boolean m_isInGame; // 0x46
	private List`1 m_frontNodeIds; // 0x48
	private List`1 m_nextNodeIds; // 0x50
	private Int32 m_tokenCost; // 0x58
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_buffId; // 0x8
	private static DelegateBridge __Hotfix0_get_buffName; // 0x10
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x18
	private static DelegateBridge __Hotfix0_get_iconId; // 0x20
	private static DelegateBridge __Hotfix0_get_groupId; // 0x28
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x30
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x38
	private static DelegateBridge __Hotfix0_get_isActive; // 0x40
	private static DelegateBridge __Hotfix0_get_isInGame; // 0x48
	private static DelegateBridge __Hotfix0_get_viewType; // 0x50
	private static DelegateBridge __Hotfix0_get_nextNodeIds; // 0x58
	private static DelegateBridge __Hotfix0_get_tokenCost; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x70
	private static DelegateBridge __Hotfix0__AddDiffFrontNode; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public override String topicId { get; }
	public override String buffId { get; }
	public override String buffName { get; }
	public String buffDesc { get; }
	public override String iconId { get; }
	public override String groupId { get; }
	public override RL03DevelopmentNodeType nodeType { get; }
	public Boolean isUnlock { get; }
	public override Boolean isActive { get; }
	public Boolean isInGame { get; }
	public override Rl03OuterBuffViewType viewType { get; }
	public List`1 nextNodeIds { get; }
	public Int32 tokenCost { get; }

	// RVA: 0x26b18e4 VA: 0x7594cc98e4
	public override String get_topicId() { }
	// RVA: 0x26b194c VA: 0x7594cc994c
	public override String get_buffId() { }
	// RVA: 0x26b19b4 VA: 0x7594cc99b4
	public override String get_buffName() { }
	// RVA: 0x26a714c VA: 0x7594cbf14c
	public String get_buffDesc() { }
	// RVA: 0x26b1a1c VA: 0x7594cc9a1c
	public override String get_iconId() { }
	// RVA: 0x26b1a84 VA: 0x7594cc9a84
	public override String get_groupId() { }
	// RVA: 0x26b1aec VA: 0x7594cc9aec
	public override RL03DevelopmentNodeType get_nodeType() { }
	// RVA: 0x26a7014 VA: 0x7594cbf014
	public Boolean get_isUnlock() { }
	// RVA: 0x26b1b54 VA: 0x7594cc9b54
	public override Boolean get_isActive() { }
	// RVA: 0x26a6fac VA: 0x7594cbefac
	public Boolean get_isInGame() { }
	// RVA: 0x26b1bbc VA: 0x7594cc9bbc
	public override Rl03OuterBuffViewType get_viewType() { }
	// RVA: 0x26b1c20 VA: 0x7594cc9c20
	public List`1 get_nextNodeIds() { }
	// RVA: 0x26a707c VA: 0x7594cbf07c
	public Int32 get_tokenCost() { }
	// RVA: 0x26b1c88 VA: 0x7594cc9c88
	public override Void LoadData(String topicId, RL03Development buffData, Dictionary`2 diffData) { }
	// RVA: 0x26b20e4 VA: 0x7594cca0e4
	public override Void RefreshStatus(Dictionary`2 playerNodeStatus) { }
	// RVA: 0x26b1f58 VA: 0x7594cc9f58
	private Void _AddDiffFrontNode(RL03DevDifficultyNodeInfo diffInfo) { }
	// RVA: 0x26b22bc VA: 0x7594cca2bc
	public Void .ctor() { }
}
```