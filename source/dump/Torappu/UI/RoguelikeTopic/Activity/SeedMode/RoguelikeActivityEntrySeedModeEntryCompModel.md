# RoguelikeActivityEntrySeedModeEntryCompModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `Boolean isEnabled`

- `Boolean isNew`

- `Boolean isLock`

- `String timeStr`

- `RoguelikeTopicMode validMode`

- `RoguelikeActivitySeedModeConstData constData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivityEntrySeedModeEntryCompModel : RoguelikeTopicActivityEntryCompBaseModel
{
	public Boolean isEnabled; // 0x20
	public Boolean isNew; // 0x21
	public Boolean isLock; // 0x22
	public String timeStr; // 0x28
	public RoguelikeTopicMode validMode; // 0x30
	public RoguelikeActivitySeedModeConstData constData; // 0x38


	// RVA: 0x26ddcd4 VA: 0x7594cf5cd4
	protected override Void _LoadModel(String inputTopicId, String inputRlActId) { }
	// RVA: 0x26ddfb8 VA: 0x7594cf5fb8
	public override Boolean CheckIsActivityEnabledForCreateGame() { }
	// RVA: 0x26de0e0 VA: 0x7594cf60e0
	public override RoguelikeTopicMode GetActivityValidMode() { }
	// RVA: 0x26de0e8 VA: 0x7594cf60e8
	public Void .ctor() { }
}
```