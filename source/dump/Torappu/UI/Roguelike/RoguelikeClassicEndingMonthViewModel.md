# RoguelikeClassicEndingMonthViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String theme`

- `String predefined`

- `Boolean isBpMax`

- `Boolean isAlreadyMax`

- `Boolean isFullStored`

- `Int32 endFloor`

- `GameSettleMonthTeam monthTeam`

- `RoguelikeTopicMonthSquadModel squadModel`

- `Int32 unlockChatNum`

- `Int32 totalChatNum`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingMonthViewModel : RoguelikeClassicEndingPageViewModel
{
	public String theme; // 0x10
	public String predefined; // 0x18
	public Boolean isBpMax; // 0x20
	public Boolean isAlreadyMax; // 0x21
	public Boolean isFullStored; // 0x22
	public Int32 endFloor; // 0x24
	public GameSettleMonthTeam monthTeam; // 0x28
	public RoguelikeTopicMonthSquadModel squadModel; // 0x30
	public Int32 unlockChatNum; // 0x38
	public Int32 totalChatNum; // 0x3c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadFromResponse; // 0x8
	private static DelegateBridge __Hotfix0_CheckNeedBpView; // 0x10
	private static DelegateBridge __Hotfix0_GeneEndingBpAndGpViewModel; // 0x18
	private static DelegateBridge __Hotfix0_GetRewardItemList; // 0x20
	private static DelegateBridge __Hotfix0__CalculateUnlockChatNum; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2a2ca20 VA: 0x7595044a20
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2a2cb40 VA: 0x7595044b40
	public override Void LoadFromResponse(String topicId, RoguelikeTopicGameSettleResponse response) { }
	// RVA: 0x2a2cefc VA: 0x7595044efc
	public override Boolean CheckNeedBpView() { }
	// RVA: 0x2a2cf84 VA: 0x7595044f84
	public override Model GeneEndingBpAndGpViewModel() { }
	// RVA: 0x2a2d078 VA: 0x7595045078
	public override List`1 GetRewardItemList() { }
	// RVA: 0x2a2cc4c VA: 0x7595044c4c
	private static Void _CalculateUnlockChatNum(RoguelikeClassicEndingMonthViewModel viewModel, RoguelikeTopicMonthSquadModel squadModel, out Int32 unlockChatNum, out Int32 chatCount) { }
	// RVA: 0x2a2d0f0 VA: 0x75950450f0
	public Void .ctor() { }
}
```