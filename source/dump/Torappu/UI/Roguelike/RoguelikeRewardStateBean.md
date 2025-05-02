# RoguelikeRewardStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardStateBean : IStateBean, IHotfixable
{
	private static DelegateBridge __Hotfix0_InitWithViewModel; // 0x0
	private static DelegateBridge __Hotfix0_CreateRewardItemViewStruct; // 0x8
	private static DelegateBridge __Hotfix0_InitRewardWithViewModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a985e4 VA: 0x75950b05e4
	public static RoguelikeRewardEarnViewModel InitWithViewModel(String topicId, RoguelikeStageEarn earn) { }
	// RVA: 0x2aa5360 VA: 0x75950bd360
	public static RoguelikeSortItemViewStruct CreateRewardItemViewStruct(String topicId, RoguelikeItemBundle item, RoguelikeRewardExtraInfoFactory factory, out RoguelikeRewardShowType singleShowType) { }
	// RVA: 0x2a9dd68 VA: 0x75950b5d68
	public static RoguelikeRewardListViewModel InitRewardWithViewModel(String topicId, List`1 rewardList, RoguelikeRewardExtraInfoFactory factory, Boolean showReceiptBtn, Boolean showStoreInfo) { }
	// RVA: 0x2a9407c VA: 0x75950ac07c
	public Void .ctor() { }
}
```