# RL04FragmentItemViewModel

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

- `Boolean isUsed`

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

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentItemViewModel : IRoguelikeFragmentItemModel, IHotfixable, IComparable
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
	public Boolean isUsed; // 0x50
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
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98
	private static DelegateBridge _c__Hotfix1_ctor; // 0xa0
	private static DelegateBridge __Hotfix0_CompareTo; // 0xa8

	public String instId { get; set; }
	public String fragmentId { get; set; }
	public RoguelikeFragmentType type { get; set; }
	public Int32 weight { get; set; }
	public Int32 value { get; set; }
	public String name { get; set; }
	public String iconId { get; set; }
	public String desc { get; set; }
	public String usage { get; set; }
	public Boolean isSelected { get; }

	// RVA: 0x2b24cec VA: 0x759513ccec
	public String get_instId() { }
	// RVA: 0x2b26d60 VA: 0x759513ed60
	public Void set_instId(String value) { }
	// RVA: 0x2b26de4 VA: 0x759513ede4
	public String get_fragmentId() { }
	// RVA: 0x2b26e4c VA: 0x759513ee4c
	public Void set_fragmentId(String value) { }
	// RVA: 0x2b26ed0 VA: 0x759513eed0
	public RoguelikeFragmentType get_type() { }
	// RVA: 0x2b26f38 VA: 0x759513ef38
	public Void set_type(RoguelikeFragmentType value) { }
	// RVA: 0x2b26fb4 VA: 0x759513efb4
	public Int32 get_weight() { }
	// RVA: 0x2b2701c VA: 0x759513f01c
	public Void set_weight(Int32 value) { }
	// RVA: 0x2b27098 VA: 0x759513f098
	public Int32 get_value() { }
	// RVA: 0x2b27100 VA: 0x759513f100
	public Void set_value(Int32 value) { }
	// RVA: 0x2b2717c VA: 0x759513f17c
	public String get_name() { }
	// RVA: 0x2b271e4 VA: 0x759513f1e4
	public Void set_name(String value) { }
	// RVA: 0x2b27268 VA: 0x759513f268
	public String get_iconId() { }
	// RVA: 0x2b272d0 VA: 0x759513f2d0
	public Void set_iconId(String value) { }
	// RVA: 0x2b27354 VA: 0x759513f354
	public String get_desc() { }
	// RVA: 0x2b273bc VA: 0x759513f3bc
	public Void set_desc(String value) { }
	// RVA: 0x2b27440 VA: 0x759513f440
	public String get_usage() { }
	// RVA: 0x2b274a8 VA: 0x759513f4a8
	public Void set_usage(String value) { }
	// RVA: 0x2b2752c VA: 0x759513f52c
	public Boolean get_isSelected() { }
	// RVA: 0x2b27590 VA: 0x759513f590
	public Void .ctor() { }
	// RVA: 0x2b27600 VA: 0x759513f600
	public Void .ctor(RL04FragmentItemViewModel other) { }
	// RVA: 0x2b2774c VA: 0x759513f74c
	public Int32 CompareTo(Object obj) { }
}
```