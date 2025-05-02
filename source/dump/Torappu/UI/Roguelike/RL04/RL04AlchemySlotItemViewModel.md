# RL04AlchemySlotItemViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 <index>k__BackingField`

- `SlotItemStatus <status>k__BackingField`

- `String <fragmentInstId>k__BackingField`

- `RL04AlchemyFragmentItemViewModel <fragmentItemViewModel>k__BackingField`


## Properties

- `Int32 index`

- `SlotItemStatus status`

- `String fragmentInstId`

- `RL04AlchemyFragmentItemViewModel fragmentItemViewModel`


## Methods

- `Int32 get_index()`

- `Void set_index(Int32)`

- `SlotItemStatus get_status()`

- `Void set_status(SlotItemStatus)`

- `String get_fragmentInstId()`

- `Void set_fragmentInstId(String)`

- `RL04AlchemyFragmentItemViewModel get_fragmentItemViewModel()`

- `Void set_fragmentItemViewModel(RL04AlchemyFragmentItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemySlotItemViewModel : IHotfixable
{
	private Int32 <index>k__BackingField; // 0x10
	private SlotItemStatus <status>k__BackingField; // 0x14
	private String <fragmentInstId>k__BackingField; // 0x18
	private RL04AlchemyFragmentItemViewModel <fragmentItemViewModel>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_set_index; // 0x8
	private static DelegateBridge __Hotfix0_get_status; // 0x10
	private static DelegateBridge __Hotfix0_set_status; // 0x18
	private static DelegateBridge __Hotfix0_get_fragmentInstId; // 0x20
	private static DelegateBridge __Hotfix0_set_fragmentInstId; // 0x28
	private static DelegateBridge __Hotfix0_get_fragmentItemViewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_fragmentItemViewModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 index { get; set; }
	public SlotItemStatus status { get; set; }
	public String fragmentInstId { get; set; }
	public RL04AlchemyFragmentItemViewModel fragmentItemViewModel { get; set; }

	// RVA: 0x2afdc5c VA: 0x7595115c5c
	public Int32 get_index() { }
	// RVA: 0x2afdcc4 VA: 0x7595115cc4
	public Void set_index(Int32 value) { }
	// RVA: 0x2afdd40 VA: 0x7595115d40
	public SlotItemStatus get_status() { }
	// RVA: 0x2afdda8 VA: 0x7595115da8
	public Void set_status(SlotItemStatus value) { }
	// RVA: 0x2afde24 VA: 0x7595115e24
	public String get_fragmentInstId() { }
	// RVA: 0x2afde8c VA: 0x7595115e8c
	public Void set_fragmentInstId(String value) { }
	// RVA: 0x2afdf10 VA: 0x7595115f10
	public RL04AlchemyFragmentItemViewModel get_fragmentItemViewModel() { }
	// RVA: 0x2afdf78 VA: 0x7595115f78
	public Void set_fragmentItemViewModel(RL04AlchemyFragmentItemViewModel value) { }
	// RVA: 0x2afdffc VA: 0x7595115ffc
	public Void .ctor() { }
}
```