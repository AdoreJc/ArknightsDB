# RoguelikeCommonOuterBuffNormalNodeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String m_topicId`

- `String m_buffId`

- `String m_buffName`

- `String m_buffDesc`

- `String m_activeIconId`

- `String m_inactiveIconId`

- `String m_bottomIconId`

- `String m_groupId`

- `RoguelikeCommonDevelopmentNodeType m_nodeType`

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


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffNormalNodeViewModel : RoguelikeCommonOuterBuffNodeBaseViewModel
{
	private String m_topicId; // 0x10
	private String m_buffId; // 0x18
	private String m_buffName; // 0x20
	private String m_buffDesc; // 0x28
	private String m_activeIconId; // 0x30
	private String m_inactiveIconId; // 0x38
	private String m_bottomIconId; // 0x40
	private String m_groupId; // 0x48
	private RoguelikeCommonDevelopmentNodeType m_nodeType; // 0x50
	private Boolean m_isUnlock; // 0x54
	private Boolean m_isActive; // 0x55
	private Boolean m_isInGame; // 0x56
	private List`1 m_frontNodeIds; // 0x58
	private List`1 m_nextNodeIds; // 0x60
	private Int32 m_tokenCost; // 0x68
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_buffId; // 0x8
	private static DelegateBridge __Hotfix0_get_buffName; // 0x10
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x18
	private static DelegateBridge __Hotfix0_get_activeIconId; // 0x20
	private static DelegateBridge __Hotfix0_get_inactiveIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_bottomIconId; // 0x30
	private static DelegateBridge __Hotfix0_get_groupId; // 0x38
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x40
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x48
	private static DelegateBridge __Hotfix0_get_isActive; // 0x50
	private static DelegateBridge __Hotfix0_get_isInGame; // 0x58
	private static DelegateBridge __Hotfix0_get_viewType; // 0x60
	private static DelegateBridge __Hotfix0_get_nextNodeIds; // 0x68
	private static DelegateBridge __Hotfix0_get_tokenCost; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x78
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public override String topicId { get; }
	public override String buffId { get; }
	public override String buffName { get; }
	public String buffDesc { get; }
	public override String activeIconId { get; }
	public override String inactiveIconId { get; }
	public override String bottomIconId { get; }
	public override String groupId { get; }
	public override RoguelikeCommonDevelopmentNodeType nodeType { get; }
	public Boolean isUnlock { get; }
	public override Boolean isActive { get; }
	public Boolean isInGame { get; }
	public override RoguelikeCommonOuterBuffViewType viewType { get; }
	public List`1 nextNodeIds { get; }
	public Int32 tokenCost { get; }

	// RVA: 0x2667dd8 VA: 0x7594c7fdd8
	public override String get_topicId() { }
	// RVA: 0x2667e40 VA: 0x7594c7fe40
	public override String get_buffId() { }
	// RVA: 0x2667ea8 VA: 0x7594c7fea8
	public override String get_buffName() { }
	// RVA: 0x265d590 VA: 0x7594c75590
	public String get_buffDesc() { }
	// RVA: 0x2667f10 VA: 0x7594c7ff10
	public override String get_activeIconId() { }
	// RVA: 0x2667f78 VA: 0x7594c7ff78
	public override String get_inactiveIconId() { }
	// RVA: 0x2667fe0 VA: 0x7594c7ffe0
	public override String get_bottomIconId() { }
	// RVA: 0x2668048 VA: 0x7594c80048
	public override String get_groupId() { }
	// RVA: 0x26680b0 VA: 0x7594c800b0
	public override RoguelikeCommonDevelopmentNodeType get_nodeType() { }
	// RVA: 0x265d458 VA: 0x7594c75458
	public Boolean get_isUnlock() { }
	// RVA: 0x2668118 VA: 0x7594c80118
	public override Boolean get_isActive() { }
	// RVA: 0x265d3f0 VA: 0x7594c753f0
	public Boolean get_isInGame() { }
	// RVA: 0x2668180 VA: 0x7594c80180
	public override RoguelikeCommonOuterBuffViewType get_viewType() { }
	// RVA: 0x26681e4 VA: 0x7594c801e4
	public List`1 get_nextNodeIds() { }
	// RVA: 0x265d4c0 VA: 0x7594c754c0
	public Int32 get_tokenCost() { }
	// RVA: 0x266824c VA: 0x7594c8024c
	public override Void LoadData(String topicId, RoguelikeCommonDevelopment buffData, Dictionary`2 diffData) { }
	// RVA: 0x266843c VA: 0x7594c8043c
	public override Void RefreshStatus(Dictionary`2 playerNodeStatus) { }
	// RVA: 0x2668614 VA: 0x7594c80614
	public Void .ctor() { }
}
```