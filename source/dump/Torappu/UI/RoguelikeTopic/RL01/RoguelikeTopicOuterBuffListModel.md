# RoguelikeTopicOuterBuffListModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `String outerBuffItemId`

- `String outerBuffItemName`

- `Boolean isInit`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class RoguelikeTopicOuterBuffListModel : IHotfixable
{
	public List`1 items; // 0x10
	public String outerBuffItemId; // 0x18
	public String outerBuffItemName; // 0x20
	public Boolean isInit; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26d2dd0 VA: 0x7594ceadd0
	public Void LoadData(String topicId) { }
	// RVA: 0x26d32a4 VA: 0x7594ceb2a4
	public Void .ctor() { }
}
```