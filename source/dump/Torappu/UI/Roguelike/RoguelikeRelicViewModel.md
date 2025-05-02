# RoguelikeRelicViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String indexId`

- `Int32 viewIndex`

- `Boolean isUsed`

- `Boolean canSacrifice`

- `Int32 layer`

- `Boolean isUpgradable`

- `Int32 upgradeRank`

- `String originalItemId`

- `String <itemId>k__BackingField`

- `String <name>k__BackingField`

- `String <usage>k__BackingField`

- `Int64 <ts>k__BackingField`

- `String <topicId>k__BackingField`

- `RoguelikeGameItemType <itemType>k__BackingField`


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

- `String get_itemId()`

- `Void set_itemId(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_usage()`

- `Void set_usage(String)`

- `Int64 get_ts()`

- `Void set_ts(Int64)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `RoguelikeGameItemType get_itemType()`

- `Void set_itemType(RoguelikeGameItemType)`

- `String GetItemId()`

- `String GetId()`

- `RoguelikeMenuRelicItemType GetRelicItemType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRelicViewModel : IHotfixable, IRoguelikeSacrifice, IRoguelikeRelicViewModel
{
	public String indexId; // 0x10
	public Int32 viewIndex; // 0x18
	public Boolean isUsed; // 0x1c
	public Boolean canSacrifice; // 0x1d
	public Int32 layer; // 0x20
	public Boolean isUpgradable; // 0x24
	public Int32 upgradeRank; // 0x28
	public String originalItemId; // 0x30
	private String <itemId>k__BackingField; // 0x38
	private String <name>k__BackingField; // 0x40
	private String <usage>k__BackingField; // 0x48
	private Int64 <ts>k__BackingField; // 0x50
	private String <topicId>k__BackingField; // 0x58
	private RoguelikeGameItemType <itemType>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_instId; // 0x0
	private static DelegateBridge __Hotfix0_get_itemId; // 0x8
	private static DelegateBridge __Hotfix0_set_itemId; // 0x10
	private static DelegateBridge __Hotfix0_get_name; // 0x18
	private static DelegateBridge __Hotfix0_set_name; // 0x20
	private static DelegateBridge __Hotfix0_get_usage; // 0x28
	private static DelegateBridge __Hotfix0_set_usage; // 0x30
	private static DelegateBridge __Hotfix0_get_ts; // 0x38
	private static DelegateBridge __Hotfix0_set_ts; // 0x40
	private static DelegateBridge __Hotfix0_get_topicId; // 0x48
	private static DelegateBridge __Hotfix0_set_topicId; // 0x50
	private static DelegateBridge __Hotfix0_get_itemType; // 0x58
	private static DelegateBridge __Hotfix0_set_itemType; // 0x60
	private static DelegateBridge __Hotfix0_Create; // 0x68
	private static DelegateBridge __Hotfix1_Create; // 0x70
	private static DelegateBridge __Hotfix0_GetItemId; // 0x78
	private static DelegateBridge __Hotfix0_GetId; // 0x80
	private static DelegateBridge __Hotfix0_GetRelicItemType; // 0x88
	private static DelegateBridge __Hotfix0__ProcessRoguelikeBand; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public String instId { get; }
	public String itemId { get; set; }
	public String name { get; set; }
	public String usage { get; set; }
	public Int64 ts { get; set; }
	public String topicId { get; set; }
	public RoguelikeGameItemType itemType { get; set; }

	// RVA: 0x29f70c0 VA: 0x759500f0c0
	public String get_instId() { }
	// RVA: 0x29f7128 VA: 0x759500f128
	public String get_itemId() { }
	// RVA: 0x29f7190 VA: 0x759500f190
	public Void set_itemId(String value) { }
	// RVA: 0x29f7214 VA: 0x759500f214
	public String get_name() { }
	// RVA: 0x29f727c VA: 0x759500f27c
	public Void set_name(String value) { }
	// RVA: 0x29f7300 VA: 0x759500f300
	public String get_usage() { }
	// RVA: 0x29f7368 VA: 0x759500f368
	public Void set_usage(String value) { }
	// RVA: 0x29f73ec VA: 0x759500f3ec
	public Int64 get_ts() { }
	// RVA: 0x29f7454 VA: 0x759500f454
	public Void set_ts(Int64 value) { }
	// RVA: 0x29f74d0 VA: 0x759500f4d0
	public String get_topicId() { }
	// RVA: 0x29f7538 VA: 0x759500f538
	public Void set_topicId(String value) { }
	// RVA: 0x29f75bc VA: 0x759500f5bc
	public RoguelikeGameItemType get_itemType() { }
	// RVA: 0x29f7624 VA: 0x759500f624
	public Void set_itemType(RoguelikeGameItemType value) { }
	// RVA: 0x29f76a0 VA: 0x759500f6a0
	public static RoguelikeRelicViewModel Create(String topicId, Relic relic, RoguelikeGameItemType itemType) { }
	// RVA: 0x29f7774 VA: 0x759500f774
	public static RoguelikeRelicViewModel Create(String topicId, String id, RoguelikeGameItemType itemType) { }
	// RVA: 0x29f7ae4 VA: 0x759500fae4
	public String GetItemId() { }
	// RVA: 0x29f7b4c VA: 0x759500fb4c
	public String GetId() { }
	// RVA: 0x29f7bb4 VA: 0x759500fbb4
	public RoguelikeMenuRelicItemType GetRelicItemType() { }
	// RVA: 0x29f79a8 VA: 0x759500f9a8
	private static Void _ProcessRoguelikeBand(RoguelikeRelicViewModel ret) { }
	// RVA: 0x29f7938 VA: 0x759500f938
	public Void .ctor() { }
}
```