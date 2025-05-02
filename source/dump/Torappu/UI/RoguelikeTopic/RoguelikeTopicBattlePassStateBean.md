# RoguelikeTopicBattlePassStateBean

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassProperty battlePassProperty`

- `RoguelikeTopicBPGreatPrizeProperty greatRewardProperty`

- `String topicId`

- `Boolean bpPurchaseSystemUnlocked`

- `String selectedPurchaseGrandPrizeId`


## Methods

- `Void LoadData(String, RoguelikeTopicBattlePassStyle)`

- `Void _FocusOnNextGrandPrize()`

- `Void _LoadGrandPrizeData(RoguelikeTopicDetail, Dictionary`2, Int32, BattlePass, Int32, RoguelikeTopicBattlePassStyle, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public RoguelikeTopicBattlePassProperty battlePassProperty; // 0x10
	public RoguelikeTopicBPGreatPrizeProperty greatRewardProperty; // 0x18
	public String topicId; // 0x20
	public Boolean bpPurchaseSystemUnlocked; // 0x28
	public String selectedPurchaseGrandPrizeId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__FocusOnNextGrandPrize; // 0x8
	private static DelegateBridge __Hotfix0__LoadGrandPrizeData; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfRewardGot; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfRewardValid; // 0x20
	private static DelegateBridge __Hotfix0_CheckBpDataWithinLimit; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x267585c VA: 0x7594c8d85c
	public Void LoadData(String topicId, RoguelikeTopicBattlePassStyle style) { }
	// RVA: 0x267679c VA: 0x7594c8e79c
	private Void _FocusOnNextGrandPrize() { }
	// RVA: 0x26763ec VA: 0x7594c8e3ec
	private Void _LoadGrandPrizeData(RoguelikeTopicDetail topicData, Dictionary`2 rewardIdDataMap, Int32 bpLimitPoint, BattlePass playerBattlePass, Int32 currBpPoint, RoguelikeTopicBattlePassStyle style, Boolean bpPurchaseAvailable) { }
	// RVA: 0x2674800 VA: 0x7594c8c800
	public static Boolean CheckIfRewardGot(BattlePass playerBattlePass, String id) { }
	// RVA: 0x26748ec VA: 0x7594c8c8ec
	public static Boolean CheckIfRewardValid(RoguelikeTopicBP targetBpData, Int32 currBpPoint) { }
	// RVA: 0x267627c VA: 0x7594c8e27c
	public static Boolean CheckBpDataWithinLimit(RoguelikeTopicBP bpData, Int32 bpLimitPoint) { }
	// RVA: 0x2676b50 VA: 0x7594c8eb50
	public Void .ctor() { }
}
```