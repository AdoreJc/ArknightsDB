# ItemBundle

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 count`

- `ItemType type`


## Properties

- `Boolean isEmpty`


## Methods

- `Void _Init(String, ItemType, Int32)`

- `Boolean IsSameItem(ItemBundle)`

- `Boolean get_isEmpty()`

- `ItemType GetItemType()`

- `String GetItemId()`

- `Int32 GetItemCount()`

- `Void SetItemCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ItemBundle : ISharedItemModel
{
	public String id; // 0x10
	public Int32 count; // 0x18
	public ItemType type; // 0x1c

	public Boolean isEmpty { get; }

	// RVA: 0x34a3894 VA: 0x7595abb894
	public Void .ctor(String itemId, ItemType itemType, Int32 count) { }
	// RVA: 0x34a390c VA: 0x7595abb90c
	public Void .ctor() { }
	// RVA: 0x34a38dc VA: 0x7595abb8dc
	private Void _Init(String itemId_, ItemType itemType_, Int32 count_) { }
	// RVA: 0x34a3914 VA: 0x7595abb914
	public override Int32 GetHashCode() { }
	// RVA: 0x34a3964 VA: 0x7595abb964
	public Boolean IsSameItem(ItemBundle other) { }
	// RVA: 0x34a39b0 VA: 0x7595abb9b0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x34a3a60 VA: 0x7595abba60
	public Boolean get_isEmpty() { }
	// RVA: 0x34a3a94 VA: 0x7595abba94
	public ItemType GetItemType() { }
	// RVA: 0x34a3a9c VA: 0x7595abba9c
	public String GetItemId() { }
	// RVA: 0x34a3aa4 VA: 0x7595abbaa4
	public Int32 GetItemCount() { }
	// RVA: 0x34a3aac VA: 0x7595abbaac
	public Void SetItemCount(Int32 count_) { }
}
```