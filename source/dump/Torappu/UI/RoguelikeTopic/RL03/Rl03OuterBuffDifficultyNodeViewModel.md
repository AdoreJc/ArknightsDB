# Rl03OuterBuffDifficultyNodeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `String m_topicId`

- `String m_buffId`

- `String m_buffName`

- `String m_iconId`

- `String m_groupId`

- `String m_effectTips`

- `RL03DevelopmentNodeType m_nodeType`

- `Boolean m_isActive`

- `Boolean m_canEffect`

- `RL03DevDifficultyNodeInfo m_difficultyInfo`


## Properties

- `String effectTips`

- `Boolean canEffect`

- `RL03DevDifficultyNodeInfo difficultyInfo`


## Methods

- `String get_effectTips()`

- `Boolean get_canEffect()`

- `RL03DevDifficultyNodeInfo get_difficultyInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffDifficultyNodeViewModel : Rl03OuterBuffNodeBaseViewModel
{
	private String m_topicId; // 0x10
	private String m_buffId; // 0x18
	private String m_buffName; // 0x20
	private String m_iconId; // 0x28
	private String m_groupId; // 0x30
	private String m_effectTips; // 0x38
	private List`1 m_descs; // 0x40
	private RL03DevelopmentNodeType m_nodeType; // 0x48
	private Boolean m_isActive; // 0x4c
	private Boolean m_canEffect; // 0x4d
	private List`1 m_unlockedSocket; // 0x50
	private RL03DevDifficultyNodeInfo m_difficultyInfo; // 0x58
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_buffId; // 0x8
	private static DelegateBridge __Hotfix0_get_buffName; // 0x10
	private static DelegateBridge __Hotfix0_get_iconId; // 0x18
	private static DelegateBridge __Hotfix0_get_groupId; // 0x20
	private static DelegateBridge __Hotfix0_get_effectTips; // 0x28
	private static DelegateBridge __Hotfix0_get_descs; // 0x30
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x38
	private static DelegateBridge __Hotfix0_get_isActive; // 0x40
	private static DelegateBridge __Hotfix0_get_canEffect; // 0x48
	private static DelegateBridge __Hotfix0_get_unlockedSocket; // 0x50
	private static DelegateBridge __Hotfix0_get_viewType; // 0x58
	private static DelegateBridge __Hotfix0_get_difficultyInfo; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override String topicId { get; }
	public override String buffId { get; }
	public override String buffName { get; }
	public override String iconId { get; }
	public override String groupId { get; }
	public String effectTips { get; }
	public List`1 descs { get; }
	public override RL03DevelopmentNodeType nodeType { get; }
	public override Boolean isActive { get; }
	public Boolean canEffect { get; }
	public List`1 unlockedSocket { get; }
	public override Rl03OuterBuffViewType viewType { get; }
	public RL03DevDifficultyNodeInfo difficultyInfo { get; }

	// RVA: 0x26b2328 VA: 0x7594cca328
	public override String get_topicId() { }
	// RVA: 0x26b2390 VA: 0x7594cca390
	public override String get_buffId() { }
	// RVA: 0x26b23f8 VA: 0x7594cca3f8
	public override String get_buffName() { }
	// RVA: 0x26b2460 VA: 0x7594cca460
	public override String get_iconId() { }
	// RVA: 0x26b24c8 VA: 0x7594cca4c8
	public override String get_groupId() { }
	// RVA: 0x26a6978 VA: 0x7594cbe978
	public String get_effectTips() { }
	// RVA: 0x26a69e0 VA: 0x7594cbe9e0
	public List`1 get_descs() { }
	// RVA: 0x26b2530 VA: 0x7594cca530
	public override RL03DevelopmentNodeType get_nodeType() { }
	// RVA: 0x26b2598 VA: 0x7594cca598
	public override Boolean get_isActive() { }
	// RVA: 0x26a6848 VA: 0x7594cbe848
	public Boolean get_canEffect() { }
	// RVA: 0x26aaba8 VA: 0x7594cc2ba8
	public List`1 get_unlockedSocket() { }
	// RVA: 0x26b2600 VA: 0x7594cca600
	public override Rl03OuterBuffViewType get_viewType() { }
	// RVA: 0x26b2668 VA: 0x7594cca668
	public RL03DevDifficultyNodeInfo get_difficultyInfo() { }
	// RVA: 0x26b26d0 VA: 0x7594cca6d0
	public override Void LoadData(String topicId, RL03Development buffData, Dictionary`2 diffData) { }
	// RVA: 0x26b2894 VA: 0x7594cca894
	public override Void RefreshStatus(Dictionary`2 playerNodeStatus) { }
	// RVA: 0x26b2c14 VA: 0x7594ccac14
	public Void .ctor() { }
}
```