# RoguelikeTopicChallenge

**Namespace:** `Torappu`


## Fields

- `String challengeId`

- `Int32 sortId`

- `String challengeName`

- `Int32 challengeGroup`

- `Int32 challengeGroupSortId`

- `String challengeGroupName`

- `String challengeUnlockDesc`

- `String challengeUnlockToastDesc`

- `String challengeDes`

- `String defaultTaskId`

- `String challengeStoryId`


## Methods

- `Boolean ShouldSerializechallengeStoryId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeTopicChallenge
{
	public String challengeId; // 0x10
	public Int32 sortId; // 0x18
	public String challengeName; // 0x20
	public Int32 challengeGroup; // 0x28
	public Int32 challengeGroupSortId; // 0x2c
	public String challengeGroupName; // 0x30
	public String challengeUnlockDesc; // 0x38
	public String challengeUnlockToastDesc; // 0x40
	public String challengeDes; // 0x48
	public List`1 challengeConditionDes; // 0x50
	public Dictionary`2 challengeTasks; // 0x58
	public String defaultTaskId; // 0x60
	public List`1 rewards; // 0x68
	public String challengeStoryId; // 0x70


	// RVA: 0x34ab424 VA: 0x7595ac3424
	public Boolean ShouldSerializechallengeStoryId() { }
	// RVA: 0x34ab444 VA: 0x7595ac3444
	public Void .ctor() { }
}
```