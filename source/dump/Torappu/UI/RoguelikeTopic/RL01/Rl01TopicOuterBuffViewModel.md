# Rl01TopicOuterBuffViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `String topicId`

- `RoguelikeTopicOuterBuffListProperty buffListProperty`

- `RoguelikeTopicOuterBuffSkillTreeProperty skillTreeProperty`


## Methods

- `Void LoadData()`

- `Void SetNodeSelected(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01TopicOuterBuffViewModel : IHotfixable
{
	public String topicId; // 0x10
	public RoguelikeTopicOuterBuffListProperty buffListProperty; // 0x18
	public RoguelikeTopicOuterBuffSkillTreeProperty skillTreeProperty; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetNodeSelected; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26d3cec VA: 0x7594cebcec
	public Void LoadData() { }
	// RVA: 0x26d3db0 VA: 0x7594cebdb0
	public Void SetNodeSelected(String buffId) { }
	// RVA: 0x26d3ea8 VA: 0x7594cebea8
	public Void .ctor() { }
}
```