# RoguelikeItemChoiceModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeTopicItemModel m_itemModel`


## Properties

- `String topicId`

- `RoguelikeTopicItemModel itemModel`


## Methods

- `String get_topicId()`

- `RoguelikeTopicItemModel get_itemModel()`

- `Void _GetItemModelIfNecessary()`

- `Void _GetDifficultyUpgradeRelicItemModelIfNecessary()`

- `Void <>xLuaBaseProxy_OnDataUpdated()`

- `String <>xLuaBaseProxy_get_itemName()`

- `String <>xLuaBaseProxy_get_itemDesc()`

- `String <>xLuaBaseProxy_get_itemId()`

- `RoguelikeGameItemType <>xLuaBaseProxy_get_itemType()`

- `IRoguelikeChoiceHintContext <>xLuaBaseProxy_GetChoiceHintContext()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeItemChoiceModel : RoguelikeDefaultChoiceModel
{
	private RoguelikeTopicItemModel m_itemModel; // 0x50
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_itemModel; // 0x8
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x10
	private static DelegateBridge __Hotfix0__GetItemModelIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0__GetDifficultyUpgradeRelicItemModelIfNecessary; // 0x20
	private static DelegateBridge __Hotfix0_get_itemName; // 0x28
	private static DelegateBridge __Hotfix0_get_itemDesc; // 0x30
	private static DelegateBridge __Hotfix0_get_itemId; // 0x38
	private static DelegateBridge __Hotfix0_get_itemType; // 0x40
	private static DelegateBridge __Hotfix0_GetChoiceHintContext; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected String topicId { get; }
	protected RoguelikeTopicItemModel itemModel { get; }
	public override String itemName { get; }
	public override String itemDesc { get; }
	public override String itemId { get; }
	public override RoguelikeGameItemType itemType { get; }

	// RVA: 0x29eb864 VA: 0x7595003864
	protected String get_topicId() { }
	// RVA: 0x29eb8cc VA: 0x75950038cc
	protected RoguelikeTopicItemModel get_itemModel() { }
	// RVA: 0x29eb970 VA: 0x7595003970
	protected override Void OnDataUpdated() { }
	// RVA: 0x29eb9e8 VA: 0x75950039e8
	private Void _GetItemModelIfNecessary() { }
	// RVA: 0x29eba8c VA: 0x7595003a8c
	private Void _GetDifficultyUpgradeRelicItemModelIfNecessary() { }
	// RVA: 0x29ebc20 VA: 0x7595003c20
	public override String get_itemName() { }
	// RVA: 0x29ebce4 VA: 0x7595003ce4
	public override String get_itemDesc() { }
	// RVA: 0x29ebdc4 VA: 0x7595003dc4
	public override String get_itemId() { }
	// RVA: 0x29ebe6c VA: 0x7595003e6c
	public override RoguelikeGameItemType get_itemType() { }
	// RVA: 0x29ebf14 VA: 0x7595003f14
	protected override IRoguelikeChoiceHintContext GetChoiceHintContext() { }
	// RVA: 0x29eb14c VA: 0x759500314c
	public Void .ctor() { }
	// RVA: 0x29ec040 VA: 0x7595004040
	private Void <>xLuaBaseProxy_OnDataUpdated() { }
	// RVA: 0x29ec044 VA: 0x7595004044
	private String <>xLuaBaseProxy_get_itemName() { }
	// RVA: 0x29ec0cc VA: 0x75950040cc
	private String <>xLuaBaseProxy_get_itemDesc() { }
	// RVA: 0x29ec154 VA: 0x7595004154
	private String <>xLuaBaseProxy_get_itemId() { }
	// RVA: 0x29ec1bc VA: 0x75950041bc
	private RoguelikeGameItemType <>xLuaBaseProxy_get_itemType() { }
	// RVA: 0x29ec224 VA: 0x7595004224
	private IRoguelikeChoiceHintContext <>xLuaBaseProxy_GetChoiceHintContext() { }
}
```