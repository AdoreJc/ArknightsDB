# RoguelikeTopicOuterBuffSkillTreeNodeModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `String buffId`

- `String buffName`

- `String buffIcon`

- `RoguelikeTopicDevNodeType nodeType`

- `String buffTypeName`

- `Int32 tokenCost`

- `Boolean isUpgraded`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class RoguelikeTopicOuterBuffSkillTreeNodeModel : IHotfixable
{
	public String buffId; // 0x10
	public String buffName; // 0x18
	public String buffIcon; // 0x20
	public RoguelikeTopicDevNodeType nodeType; // 0x28
	public List`1 frontNodeList; // 0x30
	public String buffTypeName; // 0x38
	public List`1 buffDisplayInfo; // 0x40
	public Int32 tokenCost; // 0x48
	public Boolean isUpgraded; // 0x4c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x26d3424 VA: 0x7594ceb424
	public Void .ctor() { }
}
```