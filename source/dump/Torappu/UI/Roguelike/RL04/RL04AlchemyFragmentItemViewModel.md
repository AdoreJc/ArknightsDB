# RL04AlchemyFragmentItemViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `String <instId>k__BackingField`

- `String <fragmentId>k__BackingField`

- `RoguelikeFragmentType <type>k__BackingField`

- `Int32 <weight>k__BackingField`

- `Int32 <value>k__BackingField`

- `String <name>k__BackingField`

- `String <iconId>k__BackingField`

- `String <desc>k__BackingField`

- `String <usage>k__BackingField`

- `Boolean <isSelected>k__BackingField`

- `Int32 sortId`

- `Int64 ts`


## Properties

- `String instId`

- `String fragmentId`

- `RoguelikeFragmentType type`

- `Int32 weight`

- `Int32 value`

- `String name`

- `String iconId`

- `String desc`

- `String usage`

- `Boolean isSelected`


## Methods

- `String get_instId()`

- `Void set_instId(String)`

- `String get_fragmentId()`

- `Void set_fragmentId(String)`

- `RoguelikeFragmentType get_type()`

- `Void set_type(RoguelikeFragmentType)`

- `Int32 get_weight()`

- `Void set_weight(Int32)`

- `Int32 get_value()`

- `Void set_value(Int32)`

- `String get_name()`

- `Void set_name(String)`

- `String get_iconId()`

- `Void set_iconId(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `String get_usage()`

- `Void set_usage(String)`

- `Boolean get_isSelected()`

- `Void set_isSelected(Boolean)`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyFragmentItemViewModel : IRoguelikeFragmentItemModel, IHotfixable, IComparable
{
	private String <instId>k__BackingField; // 0x10
	private String <fragmentId>k__BackingField; // 0x18
	private RoguelikeFragmentType <type>k__BackingField; // 0x20
	private Int32 <weight>k__BackingField; // 0x24
	private Int32 <value>k__BackingField; // 0x28
	private String <name>k__BackingField; // 0x30
	private String <iconId>k__BackingField; // 0x38
	private String <desc>k__BackingField; // 0x40
	private String <usage>k__BackingField; // 0x48
	private Boolean <isSelected>k__BackingField; // 0x50
	public Int32 sortId; // 0x54
	public Int64 ts; // 0x58
	private static DelegateBridge __Hotfix0_get_instId; // 0x0
	private static DelegateBridge __Hotfix0_set_instId; // 0x8
	private static DelegateBridge __Hotfix0_get_fragmentId; // 0x10
	private static DelegateBridge __Hotfix0_set_fragmentId; // 0x18
	private static DelegateBridge __Hotfix0_get_type; // 0x20
	private static DelegateBridge __Hotfix0_set_type; // 0x28
	private static DelegateBridge __Hotfix0_get_weight; // 0x30
	private static DelegateBridge __Hotfix0_set_weight; // 0x38
	private static DelegateBridge __Hotfix0_get_value; // 0x40
	private static DelegateBridge __Hotfix0_set_value; // 0x48
	private static DelegateBridge __Hotfix0_get_name; // 0x50
	private static DelegateBridge __Hotfix0_set_name; // 0x58
	private static DelegateBridge __Hotfix0_get_iconId; // 0x60
	private static DelegateBridge __Hotfix0_set_iconId; // 0x68
	private static DelegateBridge __Hotfix0_get_desc; // 0x70
	private static DelegateBridge __Hotfix0_set_desc; // 0x78
	private static DelegateBridge __Hotfix0_get_usage; // 0x80
	private static DelegateBridge __Hotfix0_set_usage; // 0x88
	private static DelegateBridge __Hotfix0_get_isSelected; // 0x90
	private static DelegateBridge __Hotfix0_set_isSelected; // 0x98
	private static DelegateBridge __Hotfix0_CompareTo; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String instId { get; set; }
	public String fragmentId { get; set; }
	public RoguelikeFragmentType type { get; set; }
	public Int32 weight { get; set; }
	public Int32 value { get; set; }
	public String name { get; set; }
	public String iconId { get; set; }
	public String desc { get; set; }
	public String usage { get; set; }
	public Boolean isSelected { get; set; }

	// RVA: 0x2b0026c VA: 0x759511826c
	public String get_instId() { }
	// RVA: 0x2b008a0 VA: 0x75951188a0
	public Void set_instId(String value) { }
	// RVA: 0x2b00924 VA: 0x7595118924
	public String get_fragmentId() { }
	// RVA: 0x2b0098c VA: 0x759511898c
	public Void set_fragmentId(String value) { }
	// RVA: 0x2b004f4 VA: 0x75951184f4
	public RoguelikeFragmentType get_type() { }
	// RVA: 0x2b00a10 VA: 0x7595118a10
	public Void set_type(RoguelikeFragmentType value) { }
	// RVA: 0x2b00a8c VA: 0x7595118a8c
	public Int32 get_weight() { }
	// RVA: 0x2b00af4 VA: 0x7595118af4
	public Void set_weight(Int32 value) { }
	// RVA: 0x2b00b70 VA: 0x7595118b70
	public Int32 get_value() { }
	// RVA: 0x2b00bd8 VA: 0x7595118bd8
	public Void set_value(Int32 value) { }
	// RVA: 0x2b00c54 VA: 0x7595118c54
	public String get_name() { }
	// RVA: 0x2b00cbc VA: 0x7595118cbc
	public Void set_name(String value) { }
	// RVA: 0x2b00d40 VA: 0x7595118d40
	public String get_iconId() { }
	// RVA: 0x2b00da8 VA: 0x7595118da8
	public Void set_iconId(String value) { }
	// RVA: 0x2b00e2c VA: 0x7595118e2c
	public String get_desc() { }
	// RVA: 0x2b00e94 VA: 0x7595118e94
	public Void set_desc(String value) { }
	// RVA: 0x2b00f18 VA: 0x7595118f18
	public String get_usage() { }
	// RVA: 0x2b00f80 VA: 0x7595118f80
	public Void set_usage(String value) { }
	// RVA: 0x2b00158 VA: 0x7595118158
	public Boolean get_isSelected() { }
	// RVA: 0x2b01004 VA: 0x7595119004
	public Void set_isSelected(Boolean value) { }
	// RVA: 0x2b00624 VA: 0x7595118624
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2b01084 VA: 0x7595119084
	public Void .ctor() { }
}
```