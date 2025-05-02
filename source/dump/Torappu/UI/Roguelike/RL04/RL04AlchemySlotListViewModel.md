# RL04AlchemySlotListViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `SlotListStatus <listStatus>k__BackingField`

- `Int32 <slotMaxCount>k__BackingField`


## Properties

- `SlotListStatus listStatus`

- `Int32 slotMaxCount`


## Methods

- `SlotListStatus get_listStatus()`

- `Void set_listStatus(SlotListStatus)`

- `Int32 get_slotMaxCount()`

- `Void set_slotMaxCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemySlotListViewModel : IHotfixable
{
	private SlotListStatus <listStatus>k__BackingField; // 0x10
	private Int32 <slotMaxCount>k__BackingField; // 0x14
	public List`1 slotItemViewModels; // 0x18
	private static DelegateBridge __Hotfix0_get_listStatus; // 0x0
	private static DelegateBridge __Hotfix0_set_listStatus; // 0x8
	private static DelegateBridge __Hotfix0_get_slotMaxCount; // 0x10
	private static DelegateBridge __Hotfix0_set_slotMaxCount; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public SlotListStatus listStatus { get; set; }
	public Int32 slotMaxCount { get; set; }

	// RVA: 0x2afe06c VA: 0x759511606c
	public SlotListStatus get_listStatus() { }
	// RVA: 0x2afe0d4 VA: 0x75951160d4
	public Void set_listStatus(SlotListStatus value) { }
	// RVA: 0x2afe150 VA: 0x7595116150
	public Int32 get_slotMaxCount() { }
	// RVA: 0x2afe1b8 VA: 0x75951161b8
	public Void set_slotMaxCount(Int32 value) { }
	// RVA: 0x2afe234 VA: 0x7595116234
	public Void .ctor() { }
}
```