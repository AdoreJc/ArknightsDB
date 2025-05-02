# RoguelikeCommonOuterBuffDifficultyNodeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String m_topicId`

- `String m_buffId`

- `String m_buffName`

- `String m_activeIconId`

- `String m_inactiveIconId`

- `String m_bottomIconId`

- `String m_decoId`

- `String m_groupId`

- `String m_enableDesc`

- `RoguelikeCommonDevelopmentNodeType m_nodeType`

- `Boolean m_isActive`

- `Boolean m_canEffect`

- `RoguelikeCommonDevDifficultyNodeInfo m_difficultyInfo`


## Properties

- `String decoId`

- `String enableDesc`

- `Boolean canEffect`

- `RoguelikeCommonDevDifficultyNodeInfo difficultyInfo`


## Methods

- `String get_decoId()`

- `String get_enableDesc()`

- `Boolean get_canEffect()`

- `RoguelikeCommonDevDifficultyNodeInfo get_difficultyInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffDifficultyNodeViewModel : RoguelikeCommonOuterBuffNodeBaseViewModel
{
	private String m_topicId; // 0x10
	private String m_buffId; // 0x18
	private String m_buffName; // 0x20
	private String m_activeIconId; // 0x28
	private String m_inactiveIconId; // 0x30
	private String m_bottomIconId; // 0x38
	private String m_decoId; // 0x40
	private String m_groupId; // 0x48
	private String m_enableDesc; // 0x50
	private List`1 m_descs; // 0x58
	private RoguelikeCommonDevelopmentNodeType m_nodeType; // 0x60
	private Boolean m_isActive; // 0x64
	private Boolean m_canEffect; // 0x65
	private List`1 m_unlockedSocket; // 0x68
	private RoguelikeCommonDevDifficultyNodeInfo m_difficultyInfo; // 0x70
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_buffId; // 0x8
	private static DelegateBridge __Hotfix0_get_buffName; // 0x10
	private static DelegateBridge __Hotfix0_get_activeIconId; // 0x18
	private static DelegateBridge __Hotfix0_get_inactiveIconId; // 0x20
	private static DelegateBridge __Hotfix0_get_bottomIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_decoId; // 0x30
	private static DelegateBridge __Hotfix0_get_groupId; // 0x38
	private static DelegateBridge __Hotfix0_get_enableDesc; // 0x40
	private static DelegateBridge __Hotfix0_get_descs; // 0x48
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x50
	private static DelegateBridge __Hotfix0_get_isActive; // 0x58
	private static DelegateBridge __Hotfix0_get_canEffect; // 0x60
	private static DelegateBridge __Hotfix0_get_unlockedSocket; // 0x68
	private static DelegateBridge __Hotfix0_get_viewType; // 0x70
	private static DelegateBridge __Hotfix0_get_difficultyInfo; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override String topicId { get; }
	public override String buffId { get; }
	public override String buffName { get; }
	public override String activeIconId { get; }
	public override String inactiveIconId { get; }
	public override String bottomIconId { get; }
	public String decoId { get; }
	public override String groupId { get; }
	public String enableDesc { get; }
	public List`1 descs { get; }
	public override RoguelikeCommonDevelopmentNodeType nodeType { get; }
	public override Boolean isActive { get; }
	public Boolean canEffect { get; }
	public List`1 unlockedSocket { get; }
	public override RoguelikeCommonOuterBuffViewType viewType { get; }
	public RoguelikeCommonDevDifficultyNodeInfo difficultyInfo { get; }

	// RVA: 0x2668680 VA: 0x7594c80680
	public override String get_topicId() { }
	// RVA: 0x26686e8 VA: 0x7594c806e8
	public override String get_buffId() { }
	// RVA: 0x2668750 VA: 0x7594c80750
	public override String get_buffName() { }
	// RVA: 0x26687b8 VA: 0x7594c807b8
	public override String get_activeIconId() { }
	// RVA: 0x2668820 VA: 0x7594c80820
	public override String get_inactiveIconId() { }
	// RVA: 0x2668888 VA: 0x7594c80888
	public override String get_bottomIconId() { }
	// RVA: 0x265c8f0 VA: 0x7594c748f0
	public String get_decoId() { }
	// RVA: 0x26688f0 VA: 0x7594c808f0
	public override String get_groupId() { }
	// RVA: 0x265c9f0 VA: 0x7594c749f0
	public String get_enableDesc() { }
	// RVA: 0x265ca58 VA: 0x7594c74a58
	public List`1 get_descs() { }
	// RVA: 0x2668958 VA: 0x7594c80958
	public override RoguelikeCommonDevelopmentNodeType get_nodeType() { }
	// RVA: 0x26689c0 VA: 0x7594c809c0
	public override Boolean get_isActive() { }
	// RVA: 0x265c888 VA: 0x7594c74888
	public Boolean get_canEffect() { }
	// RVA: 0x2661618 VA: 0x7594c79618
	public List`1 get_unlockedSocket() { }
	// RVA: 0x2668a28 VA: 0x7594c80a28
	public override RoguelikeCommonOuterBuffViewType get_viewType() { }
	// RVA: 0x2668a90 VA: 0x7594c80a90
	public RoguelikeCommonDevDifficultyNodeInfo get_difficultyInfo() { }
	// RVA: 0x2668af8 VA: 0x7594c80af8
	public override Void LoadData(String topicId, RoguelikeCommonDevelopment buffData, Dictionary`2 diffData) { }
	// RVA: 0x2668cd0 VA: 0x7594c80cd0
	public override Void RefreshStatus(Dictionary`2 playerNodeStatus) { }
	// RVA: 0x2669190 VA: 0x7594c81190
	public Void .ctor() { }
}
```