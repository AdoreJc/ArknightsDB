# RoguelikeTopicChallengeModeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Boolean isValid`

- `String topicId`

- `String currExploringChallengeId`

- `String currSelectedChallengeId`

- `String tipButtonName`

- `String collectionButtonName`

- `String medalGroupName`

- `String taskTargetTitleName`

- `String taskConditionName`

- `String taskRewardName`

- `String taskTitleName`

- `String taskModeTitleName`

- `Boolean challengeBookAccessible`

- `Boolean challengeBookHasNewItem`


## Methods

- `Void LoadData(String, RoguelikeTopicModeViewModel)`

- `Boolean SetSelectedChallenge(String)`

- `PlayerRoguelikeChallengeStatus GetSelectedChallengeStatus()`

- `PlayerRoguelikeChallengeStatus GetChallengeStatus(String)`

- `Void _InitSelectedChallengeId()`

- `Void _LoadChallengeBookRelated(RoguelikeTopicDetail, OuterData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeModeViewModel : IHotfixable
{
	public Boolean isValid; // 0x10
	public String topicId; // 0x18
	public String currExploringChallengeId; // 0x20
	public String currSelectedChallengeId; // 0x28
	public ListDict`2 challengeList; // 0x30
	public String tipButtonName; // 0x38
	public String collectionButtonName; // 0x40
	public String medalGroupName; // 0x48
	public String taskTargetTitleName; // 0x50
	public String taskConditionName; // 0x58
	public String taskRewardName; // 0x60
	public String taskTitleName; // 0x68
	public String taskModeTitleName; // 0x70
	public Boolean challengeBookAccessible; // 0x78
	public Boolean challengeBookHasNewItem; // 0x79
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedChallenge; // 0x8
	private static DelegateBridge __Hotfix0_GetSelectedChallengeStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetChallengeStatus; // 0x18
	private static DelegateBridge __Hotfix0__InitSelectedChallengeId; // 0x20
	private static DelegateBridge __Hotfix0__LoadChallengeBookRelated; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2677860 VA: 0x7594c8f860
	public Void LoadData(String topic, RoguelikeTopicModeViewModel outerModel) { }
	// RVA: 0x26787c8 VA: 0x7594c907c8
	public Boolean SetSelectedChallenge(String challengeId) { }
	// RVA: 0x26788b0 VA: 0x7594c908b0
	public PlayerRoguelikeChallengeStatus GetSelectedChallengeStatus() { }
	// RVA: 0x267891c VA: 0x7594c9091c
	public PlayerRoguelikeChallengeStatus GetChallengeStatus(String challengeId) { }
	// RVA: 0x2678388 VA: 0x7594c90388
	private Void _InitSelectedChallengeId() { }
	// RVA: 0x267850c VA: 0x7594c9050c
	private Void _LoadChallengeBookRelated(RoguelikeTopicDetail topicDetail, OuterData playerData) { }
	// RVA: 0x2678a14 VA: 0x7594c90a14
	public Void .ctor() { }
}
```