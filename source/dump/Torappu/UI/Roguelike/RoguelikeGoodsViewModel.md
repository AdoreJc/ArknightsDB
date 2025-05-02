# RoguelikeGoodsViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GoodsItemType goodsType`

- `String topicId`

- `Int32 index`

- `String instId`

- `String itemId`

- `String name`

- `String usage`

- `String description`

- `RoguelikeGameItemType type`

- `RoguelikeGameItemRarity rarity`

- `Int32 price`

- `String iconId`

- `Boolean isAffordable`

- `Boolean isSoldout`

- `Boolean displayPriceChange`

- `Boolean isRecycleGoods`

- `Int32 originPrice`

- `Boolean canPut`

- `Boolean isBankOpen`

- `Int32 typeSortPriority`

- `Int32 typeGoodPriority`


## Properties

- `Boolean isBankEntry`

- `Boolean isItem`

- `Boolean isLockSlot`


## Methods

- `Boolean get_isBankEntry()`

- `Boolean get_isItem()`

- `Boolean get_isLockSlot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGoodsViewModel : IHotfixable
{
	public GoodsItemType goodsType; // 0x10
	public String topicId; // 0x18
	public Int32 index; // 0x20
	public String instId; // 0x28
	public String itemId; // 0x30
	public String name; // 0x38
	public String usage; // 0x40
	public String description; // 0x48
	public RoguelikeGameItemType type; // 0x50
	public RoguelikeGameItemRarity rarity; // 0x54
	public Int32 price; // 0x58
	public String iconId; // 0x60
	public Boolean isAffordable; // 0x68
	public Boolean isSoldout; // 0x69
	public Boolean displayPriceChange; // 0x6a
	public Boolean isRecycleGoods; // 0x6b
	public Int32 originPrice; // 0x6c
	public Boolean canPut; // 0x70
	public Boolean isBankOpen; // 0x71
	public Int32 typeSortPriority; // 0x74
	public Int32 typeGoodPriority; // 0x78
	private static DelegateBridge __Hotfix0_get_isBankEntry; // 0x0
	private static DelegateBridge __Hotfix0_get_isItem; // 0x8
	private static DelegateBridge __Hotfix0_get_isLockSlot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isBankEntry { get; }
	public Boolean isItem { get; }
	public Boolean isLockSlot { get; }

	// RVA: 0x2ae2074 VA: 0x75950fa074
	public Boolean get_isBankEntry() { }
	// RVA: 0x2ae20e4 VA: 0x75950fa0e4
	public Boolean get_isItem() { }
	// RVA: 0x2ae2154 VA: 0x75950fa154
	public Boolean get_isLockSlot() { }
	// RVA: 0x2ae21c4 VA: 0x75950fa1c4
	public Void .ctor() { }
}
```