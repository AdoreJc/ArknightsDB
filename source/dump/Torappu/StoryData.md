# StoryData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Boolean needCommit`

- `Boolean repeatable`

- `Boolean disabled`

- `Boolean videoResource`

- `Trigger trigger`

- `Condition condition`

- `Int32 setProgress`

- `Boolean forceOmitCommit`


## Methods

- `Boolean CheckNeedCommit()`

- `Boolean CheckCommittedOrDontNeedCommit()`

- `Boolean NeedTrig(TriggerType, String)`

- `Boolean NeedTrigWithoutCheckTrigger(Boolean)`

- `Boolean NeedTrigCanIgnoreStageCond(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryData
{
	public String id; // 0x10
	public Boolean needCommit; // 0x18
	public Boolean repeatable; // 0x19
	public Boolean disabled; // 0x1a
	public Boolean videoResource; // 0x1b
	public Trigger trigger; // 0x20
	public Condition condition; // 0x40
	public Int32 setProgress; // 0x48
	public String[] setFlags; // 0x50
	public ItemBundle[] completedRewards; // 0x58
	public Boolean forceOmitCommit; // 0x60


	// RVA: 0x34f77f0 VA: 0x7595b0f7f0
	public Boolean CheckNeedCommit() { }
	// RVA: 0x34f7810 VA: 0x7595b0f810
	public Boolean CheckCommittedOrDontNeedCommit() { }
	// RVA: 0x34f788c VA: 0x7595b0f88c
	public Boolean NeedTrig(TriggerType type, String key) { }
	// RVA: 0x34f7c64 VA: 0x7595b0fc64
	public Boolean NeedTrigWithoutCheckTrigger(Boolean forceRepeatableAndIgnoreStageCond) { }
	// RVA: 0x34f7d18 VA: 0x7595b0fd18
	public Boolean NeedTrigCanIgnoreStageCond(Boolean IgnoreStageCond) { }
	// RVA: 0x34f7dc8 VA: 0x7595b0fdc8
	public Void .ctor() { }
}
```