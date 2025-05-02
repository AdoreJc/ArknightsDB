# SandboxV2EventViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `String m_nodeId`

- `Int32 m_instId`

- `String m_eventId`

- `String m_eventSceneId`

- `String m_title`

- `String m_desc`

- `String m_iconId`

- `String m_nodeTypeIconId`

- `SandboxV2EventType m_type`

- `Int32 m_animSequence`

- `Int32 m_enterSequence`

- `String selectedChoiceId`

- `String confirmedChoiceId`


## Properties

- `String topicId`

- `String nodeId`

- `Int32 instId`

- `String eventId`

- `String eventSceneId`

- `String title`

- `String desc`

- `String iconId`

- `String nodeTypeIconId`

- `SandboxV2EventType type`

- `Int32 animSeq`

- `Int32 enterSeq`


## Methods

- `String get_topicId()`

- `String get_nodeId()`

- `Int32 get_instId()`

- `String get_eventId()`

- `String get_eventSceneId()`

- `String get_title()`

- `String get_desc()`

- `String get_iconId()`

- `String get_nodeTypeIconId()`

- `SandboxV2EventType get_type()`

- `Int32 get_animSeq()`

- `Int32 get_enterSeq()`

- `Void InitData(String, SandboxV2DungeonNodeViewModel)`

- `Void LoadData(String, SandboxV2DungeonNodeViewModel, Int32)`

- `SandboxV2EventChoiceViewModel GetSelectedChoiceViewModel()`

- `Void NotifyAnimSeq()`

- `Void NotifyEnterSeq()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EventViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private String m_nodeId; // 0x18
	private Int32 m_instId; // 0x20
	private String m_eventId; // 0x28
	private String m_eventSceneId; // 0x30
	private String m_title; // 0x38
	private String m_desc; // 0x40
	private String m_iconId; // 0x48
	private String m_nodeTypeIconId; // 0x50
	private SandboxV2EventType m_type; // 0x58
	private ListDict`2 m_choices; // 0x60
	private Int32 m_animSequence; // 0x68
	private Int32 m_enterSequence; // 0x6c
	public String selectedChoiceId; // 0x70
	public String confirmedChoiceId; // 0x78
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_nodeId; // 0x8
	private static DelegateBridge __Hotfix0_get_instId; // 0x10
	private static DelegateBridge __Hotfix0_get_eventId; // 0x18
	private static DelegateBridge __Hotfix0_get_eventSceneId; // 0x20
	private static DelegateBridge __Hotfix0_get_choices; // 0x28
	private static DelegateBridge __Hotfix0_get_title; // 0x30
	private static DelegateBridge __Hotfix0_get_desc; // 0x38
	private static DelegateBridge __Hotfix0_get_iconId; // 0x40
	private static DelegateBridge __Hotfix0_get_nodeTypeIconId; // 0x48
	private static DelegateBridge __Hotfix0_get_type; // 0x50
	private static DelegateBridge __Hotfix0_get_animSeq; // 0x58
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x60
	private static DelegateBridge __Hotfix0_InitData; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge __Hotfix0_GetSelectedChoiceViewModel; // 0x78
	private static DelegateBridge __Hotfix0_NotifyAnimSeq; // 0x80
	private static DelegateBridge __Hotfix0_NotifyEnterSeq; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public String topicId { get; }
	public String nodeId { get; }
	public Int32 instId { get; }
	public String eventId { get; }
	public String eventSceneId { get; }
	public ListDict`2 choices { get; }
	public String title { get; }
	public String desc { get; }
	public String iconId { get; }
	public String nodeTypeIconId { get; }
	public SandboxV2EventType type { get; }
	public Int32 animSeq { get; }
	public Int32 enterSeq { get; }

	// RVA: 0x25c76e8 VA: 0x7594bdf6e8
	public String get_topicId() { }
	// RVA: 0x25c7750 VA: 0x7594bdf750
	public String get_nodeId() { }
	// RVA: 0x25c77b8 VA: 0x7594bdf7b8
	public Int32 get_instId() { }
	// RVA: 0x25c7820 VA: 0x7594bdf820
	public String get_eventId() { }
	// RVA: 0x25c7888 VA: 0x7594bdf888
	public String get_eventSceneId() { }
	// RVA: 0x25c78f0 VA: 0x7594bdf8f0
	public ListDict`2 get_choices() { }
	// RVA: 0x25c7958 VA: 0x7594bdf958
	public String get_title() { }
	// RVA: 0x25c79c0 VA: 0x7594bdf9c0
	public String get_desc() { }
	// RVA: 0x25c7a28 VA: 0x7594bdfa28
	public String get_iconId() { }
	// RVA: 0x25c7a90 VA: 0x7594bdfa90
	public String get_nodeTypeIconId() { }
	// RVA: 0x25c7af8 VA: 0x7594bdfaf8
	public SandboxV2EventType get_type() { }
	// RVA: 0x25c7b60 VA: 0x7594bdfb60
	public Int32 get_animSeq() { }
	// RVA: 0x25c7bc8 VA: 0x7594bdfbc8
	public Int32 get_enterSeq() { }
	// RVA: 0x25c7c30 VA: 0x7594bdfc30
	public Void InitData(String topicId, SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x25c7d78 VA: 0x7594bdfd78
	public Void LoadData(String topicId, SandboxV2DungeonNodeViewModel nodeViewModel, Int32 currAp) { }
	// RVA: 0x25c81d0 VA: 0x7594be01d0
	public SandboxV2EventChoiceViewModel GetSelectedChoiceViewModel() { }
	// RVA: 0x25c827c VA: 0x7594be027c
	public Void NotifyAnimSeq() { }
	// RVA: 0x25c82ec VA: 0x7594be02ec
	public Void NotifyEnterSeq() { }
	// RVA: 0x25c835c VA: 0x7594be035c
	public Void .ctor() { }
}
```