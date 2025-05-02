# RoguelikeTopicActivityPrefabHolder

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity`


## Fields

- `RoguelikeTopicActivityEntryComp _entryComp`

- `RoguelikeTopicActivityPanel _activityPanel`


## Methods

- `RoguelikeTopicActivityEntryComp GetEntryComp()`

- `RoguelikeTopicActivityPanel GetActivityPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity
public class RoguelikeTopicActivityPrefabHolder : MonoBehaviour, IHotfixable
{
	private RoguelikeTopicActivityEntryComp _entryComp; // 0x18
	private RoguelikeTopicActivityPanel _activityPanel; // 0x20
	private static DelegateBridge __Hotfix0_GetEntryComp; // 0x0
	private static DelegateBridge __Hotfix0_GetActivityPanel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26dd3a0 VA: 0x7594cf53a0
	public RoguelikeTopicActivityEntryComp GetEntryComp() { }
	// RVA: 0x26dd408 VA: 0x7594cf5408
	public RoguelikeTopicActivityPanel GetActivityPanel() { }
	// RVA: 0x26dd470 VA: 0x7594cf5470
	public Void .ctor() { }
}
```