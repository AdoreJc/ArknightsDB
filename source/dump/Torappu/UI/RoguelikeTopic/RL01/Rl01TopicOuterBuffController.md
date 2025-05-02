# Rl01TopicOuterBuffController

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `Rl01OuterBuffTokenView _tokenView`

- `Rl01OuterBuffView _outerBuffView`

- `RectTransform _topMenuContainer`

- `Rl01TopicOuterBuffViewModel m_viewModel`

- `String m_topicId`


## Methods

- `Void SetNodeSelected(String)`

- `Void UpgradeNode(String)`

- `Void <UpgradeNode>b__9_0(RoguelikeTopicUnlockBuffResponse)`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_OnEnter(String)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01TopicOuterBuffController : RoguelikeTopicOuterBuffController
{
	private Rl01OuterBuffTokenView _tokenView; // 0x28
	private Rl01OuterBuffView _outerBuffView; // 0x30
	private RectTransform _topMenuContainer; // 0x38
	private Rl01TopicOuterBuffViewModel m_viewModel; // 0x40
	private String m_topicId; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_SetNodeSelected; // 0x18
	private static DelegateBridge __Hotfix0_UpgradeNode; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26d3f8c VA: 0x7594cebf8c
	public override Void Init() { }
	// RVA: 0x26d4108 VA: 0x7594cec108
	public override Void OnEnter(String topicId) { }
	// RVA: 0x26d4360 VA: 0x7594cec360
	public override Void OnResume(Boolean isResumeFromStack) { }
	// RVA: 0x26cbef8 VA: 0x7594ce3ef8
	public Void SetNodeSelected(String nodeId) { }
	// RVA: 0x26d43f4 VA: 0x7594cec3f4
	public Void UpgradeNode(String nodeId) { }
	// RVA: 0x26d4600 VA: 0x7594cec600
	public Void .ctor() { }
	// RVA: 0x26d46ac VA: 0x7594cec6ac
	private Void <UpgradeNode>b__9_0(RoguelikeTopicUnlockBuffResponse response) { }
	// RVA: 0x26d47a4 VA: 0x7594cec7a4
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x26d47ac VA: 0x7594cec7ac
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x26d47b4 VA: 0x7594cec7b4
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
}
```