# RoguelikeTopicChallengeModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String challengeId`

- `Int32 sortId`

- `String challengeName`

- `String challengeDesc`

- `PlayerRoguelikeChallengeStatus <challengeStatus>k__BackingField`

- `String challengeUnlockTips`

- `String challengeUnlockToast`

- `Int32 challengeGroupId`

- `String challengeGroupName`

- `Int32 initialHp`

- `Int32 initialPopulation`

- `Int32 initialGold`

- `Int32 initialSquadCapacity`

- `Int32 initialKey`

- `Int32 initialDiceCount`

- `Boolean isExploring`


## Properties

- `Boolean isCompleted`

- `PlayerRoguelikeChallengeStatus challengeStatus`


## Methods

- `Boolean get_isCompleted()`

- `PlayerRoguelikeChallengeStatus get_challengeStatus()`

- `Void set_challengeStatus(PlayerRoguelikeChallengeStatus)`

- `Void LoadData(String, RoguelikeTopicChallenge, Challenge, RoguelikeGameInitData, RoguelikeDiceModuleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeModel : IHotfixable
{
	public String challengeId; // 0x10
	public Int32 sortId; // 0x18
	public String challengeName; // 0x20
	public String challengeDesc; // 0x28
	public List`1 challengeConditionDesc; // 0x30
	public List`1 taskInfos; // 0x38
	private PlayerRoguelikeChallengeStatus <challengeStatus>k__BackingField; // 0x40
	public List`1 rewards; // 0x48
	public String challengeUnlockTips; // 0x50
	public String challengeUnlockToast; // 0x58
	public Int32 challengeGroupId; // 0x60
	public String challengeGroupName; // 0x68
	public Int32 initialHp; // 0x70
	public Int32 initialPopulation; // 0x74
	public Int32 initialGold; // 0x78
	public Int32 initialSquadCapacity; // 0x7c
	public Int32 initialKey; // 0x80
	public Int32 initialDiceCount; // 0x84
	public Boolean isExploring; // 0x88
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x0
	private static DelegateBridge __Hotfix0_get_challengeStatus; // 0x8
	private static DelegateBridge __Hotfix0_set_challengeStatus; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isCompleted { get; }
	public PlayerRoguelikeChallengeStatus challengeStatus { get; set; }

	// RVA: 0x26771f4 VA: 0x7594c8f1f4
	public Boolean get_isCompleted() { }
	// RVA: 0x2677268 VA: 0x7594c8f268
	public PlayerRoguelikeChallengeStatus get_challengeStatus() { }
	// RVA: 0x26772d0 VA: 0x7594c8f2d0
	private Void set_challengeStatus(PlayerRoguelikeChallengeStatus value) { }
	// RVA: 0x267734c VA: 0x7594c8f34c
	public Void LoadData(String topicId, RoguelikeTopicChallenge challengeData, Challenge playerChallengeData, RoguelikeGameInitData initData, RoguelikeDiceModuleData diceModuleData) { }
	// RVA: 0x267779c VA: 0x7594c8f79c
	public Void .ctor() { }
}
```