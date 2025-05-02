# RoguelikeTopicOuterBuffSkillTreeModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `String topicId`

- `String selectedBuffId`

- `Boolean currentInExploration`

- `Int32 currOuterBuffToken`

- `String outerBuffItemId`

- `String outerBuffItemName`

- `Boolean allCompleted`

- `String focusedOuterBuffItem`

- `Boolean isInit`


## Methods

- `Void LoadData(String)`

- `Boolean CanNodeUpgrade(String)`

- `Boolean IsNodeUpgraded(String)`

- `Boolean IsNodeSelected(String)`

- `Boolean SetNodeSelected(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class RoguelikeTopicOuterBuffSkillTreeModel : IHotfixable
{
	public String topicId; // 0x10
	public String selectedBuffId; // 0x18
	public Boolean currentInExploration; // 0x20
	public Int32 currOuterBuffToken; // 0x24
	public String outerBuffItemId; // 0x28
	public String outerBuffItemName; // 0x30
	public Boolean allCompleted; // 0x38
	public String focusedOuterBuffItem; // 0x40
	public Dictionary`2 nodes; // 0x48
	public Boolean isInit; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CanNodeUpgrade; // 0x8
	private static DelegateBridge __Hotfix0_IsNodeUpgraded; // 0x10
	private static DelegateBridge __Hotfix0_IsNodeSelected; // 0x18
	private static DelegateBridge __Hotfix0_SetNodeSelected; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26d3494 VA: 0x7594ceb494
	public Void LoadData(String topic) { }
	// RVA: 0x26d3970 VA: 0x7594ceb970
	public Boolean CanNodeUpgrade(String buffId) { }
	// RVA: 0x26d0020 VA: 0x7594ce8020
	public Boolean IsNodeUpgraded(String buffId) { }
	// RVA: 0x26d032c VA: 0x7594ce832c
	public Boolean IsNodeSelected(String buffId) { }
	// RVA: 0x26d3b44 VA: 0x7594cebb44
	public Boolean SetNodeSelected(String buffId) { }
	// RVA: 0x26d3c10 VA: 0x7594cebc10
	public Void .ctor() { }
}
```