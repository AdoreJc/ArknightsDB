# RoguelikeClassicEndingNormalViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String theme`

- `RoguelikeTopicMode mode`

- `Int32 modeGrade`

- `RoguelikeTopicDifficulty difficulty`

- `Int32 gpRatio`

- `RoguelikeEndingScoreViewModel scoreViewModel`

- `Single scoreFactor`

- `Int32 totalScore`

- `Int32 gpCount`

- `Single bpBuff`

- `GameSettleBpInfo bpInfo`

- `Int32 maxAccumulation`


## Methods

- `RoguelikeTopicDifficulty _GetCurrentDifficultyModel(RoguelikeTopicDetail, RoguelikeTopicMode, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingNormalViewModel : RoguelikeClassicEndingPageViewModel
{
	private const Int32 DETAIL_COUNT; // 0x0
	public String theme; // 0x10
	public RoguelikeTopicMode mode; // 0x18
	public Int32 modeGrade; // 0x1c
	public RoguelikeTopicDifficulty difficulty; // 0x20
	public Int32 gpRatio; // 0x28
	public RoguelikeEndingScoreViewModel scoreViewModel; // 0x30
	public Single scoreFactor; // 0x38
	public Int32 totalScore; // 0x3c
	public Int32 gpCount; // 0x40
	public Single bpBuff; // 0x44
	public GameSettleBpInfo bpInfo; // 0x48
	public Int32[] accumulation; // 0x50
	public Int32 maxAccumulation; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadFromResponse; // 0x8
	private static DelegateBridge __Hotfix0__GetCurrentDifficultyModel; // 0x10
	private static DelegateBridge __Hotfix0_CheckNeedBpView; // 0x18
	private static DelegateBridge __Hotfix0_GeneEndingBpAndGpViewModel; // 0x20
	private static DelegateBridge __Hotfix0_GetRewardItemList; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2a2d5b4 VA: 0x75950455b4
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2a2d8a4 VA: 0x75950458a4
	public override Void LoadFromResponse(String topicId, RoguelikeTopicGameSettleResponse response) { }
	// RVA: 0x2a2d770 VA: 0x7595045770
	private RoguelikeTopicDifficulty _GetCurrentDifficultyModel(RoguelikeTopicDetail topicDetail, RoguelikeTopicMode mode, Int32 modeGrade) { }
	// RVA: 0x2a2daa8 VA: 0x7595045aa8
	public override Boolean CheckNeedBpView() { }
	// RVA: 0x2a2db34 VA: 0x7595045b34
	public override Model GeneEndingBpAndGpViewModel() { }
	// RVA: 0x2a2dc08 VA: 0x7595045c08
	public override List`1 GetRewardItemList() { }
	// RVA: 0x2a2dc6c VA: 0x7595045c6c
	public Void .ctor() { }
}
```