# Rl03OuterBuffViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `String m_topicId`

- `String m_tokenId`

- `String m_tokenName`

- `Int32 m_activeDiffCount`

- `Int32 m_tokenCount`

- `Int32 m_nodeCount`

- `Int32 m_activeNodeCount`

- `String selectedBuffId`


## Properties

- `String topicId`

- `String tokenId`

- `String tokenName`

- `Int32 activeDiffCount`

- `Int32 tokenCount`

- `Int32 nodeCount`

- `Int32 activeNodeCount`


## Methods

- `String get_topicId()`

- `String get_tokenId()`

- `String get_tokenName()`

- `Int32 get_activeDiffCount()`

- `Int32 get_tokenCount()`

- `Int32 get_nodeCount()`

- `Int32 get_activeNodeCount()`

- `Void LoadData(String)`

- `Void UpdateNodesStatus()`

- `Void UpdateNodeStatus(String)`

- `Void _LoadNodes(Buff, Dictionary`2, Dictionary`2)`

- `Void _UpdateNode(String, Buff)`

- `Void _UpdateDiffNode(Rl03OuterBuffDifficultyNodeViewModel, Dictionary`2)`

- `Void _UpdateCount(Buff)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private String m_tokenId; // 0x18
	private String m_tokenName; // 0x20
	private ListDict`2 m_nodes; // 0x28
	private Dictionary`2 m_locationGroups; // 0x30
	private Int32 m_activeDiffCount; // 0x38
	private Int32 m_tokenCount; // 0x3c
	private Int32 m_nodeCount; // 0x40
	private Int32 m_activeNodeCount; // 0x44
	public String selectedBuffId; // 0x48
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_tokenId; // 0x8
	private static DelegateBridge __Hotfix0_get_tokenName; // 0x10
	private static DelegateBridge __Hotfix0_get_nodes; // 0x18
	private static DelegateBridge __Hotfix0_get_locationGroups; // 0x20
	private static DelegateBridge __Hotfix0_get_activeDiffCount; // 0x28
	private static DelegateBridge __Hotfix0_get_tokenCount; // 0x30
	private static DelegateBridge __Hotfix0_get_nodeCount; // 0x38
	private static DelegateBridge __Hotfix0_get_activeNodeCount; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_UpdateNodesStatus; // 0x50
	private static DelegateBridge __Hotfix0_UpdateNodeStatus; // 0x58
	private static DelegateBridge __Hotfix0__LoadNodes; // 0x60
	private static DelegateBridge __Hotfix0__UpdateNode; // 0x68
	private static DelegateBridge __Hotfix0__UpdateDiffNode; // 0x70
	private static DelegateBridge __Hotfix0__UpdateCount; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public String topicId { get; }
	public String tokenId { get; }
	public String tokenName { get; }
	public ListDict`2 nodes { get; }
	public Dictionary`2 locationGroups { get; }
	public Int32 activeDiffCount { get; }
	public Int32 tokenCount { get; }
	public Int32 nodeCount { get; }
	public Int32 activeNodeCount { get; }

	// RVA: 0x26aa3fc VA: 0x7594cc23fc
	public String get_topicId() { }
	// RVA: 0x26b2cf0 VA: 0x7594ccacf0
	public String get_tokenId() { }
	// RVA: 0x26aa394 VA: 0x7594cc2394
	public String get_tokenName() { }
	// RVA: 0x26a7adc VA: 0x7594cbfadc
	public ListDict`2 get_nodes() { }
	// RVA: 0x26b0c70 VA: 0x7594cc8c70
	public Dictionary`2 get_locationGroups() { }
	// RVA: 0x26aff70 VA: 0x7594cc7f70
	public Int32 get_activeDiffCount() { }
	// RVA: 0x26a70e4 VA: 0x7594cbf0e4
	public Int32 get_tokenCount() { }
	// RVA: 0x26b08bc VA: 0x7594cc88bc
	public Int32 get_nodeCount() { }
	// RVA: 0x26b0924 VA: 0x7594cc8924
	public Int32 get_activeNodeCount() { }
	// RVA: 0x26a87e8 VA: 0x7594cc07e8
	public Void LoadData(String topicId) { }
	// RVA: 0x26a9a20 VA: 0x7594cc1a20
	public Void UpdateNodesStatus() { }
	// RVA: 0x26aa6b8 VA: 0x7594cc26b8
	public Void UpdateNodeStatus(String nodeId) { }
	// RVA: 0x26b2d58 VA: 0x7594ccad58
	private Void _LoadNodes(Buff playerOuterBuff, Dictionary`2 developments, Dictionary`2 difficultyInfos) { }
	// RVA: 0x26b356c VA: 0x7594ccb56c
	private Void _UpdateNode(String nodeId, Buff playerOuterBuff) { }
	// RVA: 0x26b37f0 VA: 0x7594ccb7f0
	private Void _UpdateDiffNode(Rl03OuterBuffDifficultyNodeViewModel diffModel, Dictionary`2 playerNodeStatus) { }
	// RVA: 0x26b3238 VA: 0x7594ccb238
	private Void _UpdateCount(Buff playerOuterBuff) { }
	// RVA: 0x26b3968 VA: 0x7594ccb968
	public Void .ctor() { }
}
```