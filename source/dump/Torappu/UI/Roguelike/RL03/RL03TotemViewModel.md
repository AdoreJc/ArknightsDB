# RL03TotemViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String iconId`

- `Boolean isUsed`

- `Boolean canSacrifice`

- `RL03TotemAffixBuffViewModel affixBuff`

- `RoguelikeTotemPosType posType`

- `RoguelikeTotemColorType colorType`

- `String normalDesc`

- `String synergyDesc`

- `String combineGroupName`

- `String bgIconId`

- `String rhythm`

- `Boolean isManual`

- `RoguelikeTotemLinkedNodeTypeData linkedNodeTypeData`

- `Int32 distanceMin`

- `Int32 distanceMax`

- `Boolean vertPassable`

- `Int32 expandLength`

- `Boolean onlyForVert`

- `RoguelikeTotemLinkedNodeTypeData portalLinkedNodeTypeData`

- `String <instId>k__BackingField`

- `String <itemId>k__BackingField`

- `String <name>k__BackingField`

- `Int64 <ts>k__BackingField`

- `String <topicId>k__BackingField`


## Properties

- `String instId`

- `String itemId`

- `String name`

- `String usage`

- `Int64 ts`

- `String topicId`

- `RoguelikeGameItemType itemType`


## Methods

- `String get_instId()`

- `Void set_instId(String)`

- `String get_itemId()`

- `Void set_itemId(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_usage()`

- `Int64 get_ts()`

- `Void set_ts(Int64)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `RoguelikeGameItemType get_itemType()`

- `Void LoadData(String, InventoryTotem, RoguelikeGameItemType)`

- `Void LoadData(String, String, RoguelikeGameItemType)`

- `Boolean CanCombine(RL03TotemViewModel)`

- `Boolean CanResonance(RL03TotemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemViewModel : IHotfixable, IRoguelikeSacrifice
{
	public String iconId; // 0x10
	public Boolean isUsed; // 0x18
	public Boolean canSacrifice; // 0x19
	public RL03TotemAffixBuffViewModel affixBuff; // 0x20
	public RoguelikeTotemPosType posType; // 0x28
	public RoguelikeTotemColorType colorType; // 0x2c
	public String normalDesc; // 0x30
	public String synergyDesc; // 0x38
	public String combineGroupName; // 0x40
	public String bgIconId; // 0x48
	public String rhythm; // 0x50
	public Boolean isManual; // 0x58
	public RoguelikeTotemLinkedNodeTypeData linkedNodeTypeData; // 0x60
	public Int32 distanceMin; // 0x68
	public Int32 distanceMax; // 0x6c
	public Boolean vertPassable; // 0x70
	public Int32 expandLength; // 0x74
	public Boolean onlyForVert; // 0x78
	public RoguelikeTotemLinkedNodeTypeData portalLinkedNodeTypeData; // 0x80
	private String <instId>k__BackingField; // 0x88
	private String <itemId>k__BackingField; // 0x90
	private String <name>k__BackingField; // 0x98
	private Int64 <ts>k__BackingField; // 0xa0
	private String <topicId>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_instId; // 0x0
	private static DelegateBridge __Hotfix0_set_instId; // 0x8
	private static DelegateBridge __Hotfix0_get_itemId; // 0x10
	private static DelegateBridge __Hotfix0_set_itemId; // 0x18
	private static DelegateBridge __Hotfix0_get_name; // 0x20
	private static DelegateBridge __Hotfix0_set_name; // 0x28
	private static DelegateBridge __Hotfix0_get_usage; // 0x30
	private static DelegateBridge __Hotfix0_get_ts; // 0x38
	private static DelegateBridge __Hotfix0_set_ts; // 0x40
	private static DelegateBridge __Hotfix0_get_topicId; // 0x48
	private static DelegateBridge __Hotfix0_set_topicId; // 0x50
	private static DelegateBridge __Hotfix0_get_itemType; // 0x58
	private static DelegateBridge __Hotfix0_Create; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge __Hotfix1_Create; // 0x70
	private static DelegateBridge __Hotfix1_LoadData; // 0x78
	private static DelegateBridge __Hotfix0_CanCombine; // 0x80
	private static DelegateBridge __Hotfix0_CanResonance; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public String instId { get; set; }
	public String itemId { get; set; }
	public String name { get; set; }
	public String usage { get; }
	public Int64 ts { get; set; }
	public String topicId { get; set; }
	public RoguelikeGameItemType itemType { get; }

	// RVA: 0x2b969b0 VA: 0x75951ae9b0
	public String get_instId() { }
	// RVA: 0x2b96a18 VA: 0x75951aea18
	public Void set_instId(String value) { }
	// RVA: 0x2b950c8 VA: 0x75951ad0c8
	public String get_itemId() { }
	// RVA: 0x2b96a9c VA: 0x75951aea9c
	public Void set_itemId(String value) { }
	// RVA: 0x2b96b20 VA: 0x75951aeb20
	public String get_name() { }
	// RVA: 0x2b96b88 VA: 0x75951aeb88
	public Void set_name(String value) { }
	// RVA: 0x2b96c0c VA: 0x75951aec0c
	public String get_usage() { }
	// RVA: 0x2b96c78 VA: 0x75951aec78
	public Int64 get_ts() { }
	// RVA: 0x2b96ce0 VA: 0x75951aece0
	public Void set_ts(Int64 value) { }
	// RVA: 0x2b96d5c VA: 0x75951aed5c
	public String get_topicId() { }
	// RVA: 0x2b96dc4 VA: 0x75951aedc4
	public Void set_topicId(String value) { }
	// RVA: 0x2b96e48 VA: 0x75951aee48
	public RoguelikeGameItemType get_itemType() { }
	// RVA: 0x2b90858 VA: 0x75951a8858
	public static RL03TotemViewModel Create(String topicId, InventoryTotem totem, RoguelikeGameItemType itemType) { }
	// RVA: 0x2b96eb0 VA: 0x75951aeeb0
	public Void LoadData(String topicId, InventoryTotem totem, RoguelikeGameItemType itemType) { }
	// RVA: 0x2b9118c VA: 0x75951a918c
	public static RL03TotemViewModel Create(String topicId, String id, RoguelikeGameItemType itemType) { }
	// RVA: 0x2b94208 VA: 0x75951ac208
	public Void LoadData(String topicId, String id, RoguelikeGameItemType itemType) { }
	// RVA: 0x2b94810 VA: 0x75951ac810
	public Boolean CanCombine(RL03TotemViewModel totemViewModel) { }
	// RVA: 0x2b94bc4 VA: 0x75951acbc4
	public Boolean CanResonance(RL03TotemViewModel totemViewModel) { }
	// RVA: 0x2b94198 VA: 0x75951ac198
	public Void .ctor() { }
}
```