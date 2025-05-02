# RoguelikeTopicChallengeEndingViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String theme`

- `String predefined`

- `GameSettleChallenge challenge`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeEndingViewModel : RoguelikeClassicEndingPageViewModel
{
	public String theme; // 0x10
	public String predefined; // 0x18
	public GameSettleChallenge challenge; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadFromResponse; // 0x8
	private static DelegateBridge __Hotfix0_CheckNeedBpView; // 0x10
	private static DelegateBridge __Hotfix0_GeneEndingBpAndGpViewModel; // 0x18
	private static DelegateBridge __Hotfix0_GetRewardItemList; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2646d50 VA: 0x7594c5ed50
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2646e14 VA: 0x7594c5ee14
	public override Void LoadFromResponse(String topicId, RoguelikeTopicGameSettleResponse response) { }
	// RVA: 0x2646ebc VA: 0x7594c5eebc
	public override Boolean CheckNeedBpView() { }
	// RVA: 0x2646f20 VA: 0x7594c5ef20
	public override Model GeneEndingBpAndGpViewModel() { }
	// RVA: 0x2646fb0 VA: 0x7594c5efb0
	public override List`1 GetRewardItemList() { }
	// RVA: 0x2647028 VA: 0x7594c5f028
	public Void .ctor() { }
}
```