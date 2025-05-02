# RoguelikeTopicBPPrizeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBPGrandPrize roguelikeTopicBpGrandPrize`

- `RoguelikeTopicBP roguelikeTopicBp`

- `RoguelikeTopicBattlePassStyle style`

- `Boolean isValid`

- `Boolean bpPurchaseAvailable`

- `RoguelikeTopicBPPrizeState state`


## Properties

- `Boolean isItemDetailRewardAvail`

- `String itemId`

- `ItemType itemType`


## Methods

- `Boolean get_isItemDetailRewardAvail()`

- `String get_itemId()`

- `ItemType get_itemType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBPPrizeViewModel : IHotfixable
{
	public static readonly List`1 SHOW_BTN_ITEM_TYPE; // 0x0
	public RoguelikeTopicBPGrandPrize roguelikeTopicBpGrandPrize; // 0x10
	public RoguelikeTopicBP roguelikeTopicBp; // 0x18
	public RoguelikeTopicBattlePassStyle style; // 0x20
	public Boolean isValid; // 0x28
	public Boolean bpPurchaseAvailable; // 0x29
	public RoguelikeTopicBPPrizeState state; // 0x2c
	private static DelegateBridge __Hotfix0_get_isItemDetailRewardAvail; // 0x8
	private static DelegateBridge __Hotfix0_get_itemId; // 0x10
	private static DelegateBridge __Hotfix0_get_itemType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isItemDetailRewardAvail { get; }
	public String itemId { get; }
	public ItemType itemType { get; }

	// RVA: 0x2676e5c VA: 0x7594c8ee5c
	public Boolean get_isItemDetailRewardAvail() { }
	// RVA: 0x2676f40 VA: 0x7594c8ef40
	public String get_itemId() { }
	// RVA: 0x2676fec VA: 0x7594c8efec
	public ItemType get_itemType() { }
	// RVA: 0x2676ad0 VA: 0x7594c8ead0
	public Void .ctor() { }
	// RVA: 0x267707c VA: 0x7594c8f07c
	private static Void .cctor() { }
}
```