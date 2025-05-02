# RoguelikeCommonOuterBuffViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


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

- `Void LoadData(String, RoguelikeCommonDevelopmentData)`

- `Void UpdateNodesStatus()`

- `Void UpdateNodeStatus(String)`

- `Void _LoadNodes(Buff, Dictionary`2, Dictionary`2)`

- `Void _UpdateNode(String, Buff)`

- `Void _UpdateDiffNode(RoguelikeCommonOuterBuffDifficultyNodeViewModel, Dictionary`2)`

- `Void _UpdateCount(Buff)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffViewModel : IHotfixable
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

	// RVA: 0x2660bd0 VA: 0x7594c78bd0
	public String get_topicId() { }
	// RVA: 0x266926c VA: 0x7594c8126c
	public String get_tokenId() { }
	// RVA: 0x2660b68 VA: 0x7594c78b68
	public String get_tokenName() { }
	// RVA: 0x265dcbc VA: 0x7594c75cbc
	public ListDict`2 get_nodes() { }
	// RVA: 0x26671ec VA: 0x7594c7f1ec
	public Dictionary`2 get_locationGroups() { }
	// RVA: 0x26692d4 VA: 0x7594c812d4
	public Int32 get_activeDiffCount() { }
	// RVA: 0x265d528 VA: 0x7594c75528
	public Int32 get_tokenCount() { }
	// RVA: 0x2666fcc VA: 0x7594c7efcc
	public Int32 get_nodeCount() { }
	// RVA: 0x2667034 VA: 0x7594c7f034
	public Int32 get_activeNodeCount() { }
	// RVA: 0x265ee08 VA: 0x7594c76e08
	public Void LoadData(String topicId, RoguelikeCommonDevelopmentData developmentData) { }
	// RVA: 0x266007c VA: 0x7594c7807c
	public Void UpdateNodesStatus() { }
	// RVA: 0x2660f78 VA: 0x7594c78f78
	public Void UpdateNodeStatus(String nodeId) { }
	// RVA: 0x266933c VA: 0x7594c8133c
	private Void _LoadNodes(Buff playerOuterBuff, Dictionary`2 developments, Dictionary`2 difficultyInfos) { }
	// RVA: 0x2669b58 VA: 0x7594c81b58
	private Void _UpdateNode(String nodeId, Buff playerOuterBuff) { }
	// RVA: 0x2669dd8 VA: 0x7594c81dd8
	private Void _UpdateDiffNode(RoguelikeCommonOuterBuffDifficultyNodeViewModel diffModel, Dictionary`2 playerNodeStatus) { }
	// RVA: 0x2669820 VA: 0x7594c81820
	private Void _UpdateCount(Buff playerOuterBuff) { }
	// RVA: 0x2669f48 VA: 0x7594c81f48
	public Void .ctor() { }
}
```