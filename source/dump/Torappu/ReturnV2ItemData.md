# ReturnV2ItemData

**Namespace:** `Torappu`


## Fields

- `String id`

- `ItemType type`

- `Int32 count`

- `Int32 sortId`


## Methods

- `ItemType GetItemType()`

- `Int32 GetItemCount()`

- `String GetItemId()`

- `Void SetItemCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ReturnV2ItemData : ISharedItemModel
{
	public String id; // 0x10
	public ItemType type; // 0x18
	public Int32 count; // 0x1c
	public Int32 sortId; // 0x20


	// RVA: 0x34a799c VA: 0x7595abf99c
	public ItemType GetItemType() { }
	// RVA: 0x34a79a4 VA: 0x7595abf9a4
	public Int32 GetItemCount() { }
	// RVA: 0x34a79ac VA: 0x7595abf9ac
	public String GetItemId() { }
	// RVA: 0x34a79b4 VA: 0x7595abf9b4
	public Void SetItemCount(Int32 count) { }
	// RVA: 0x34a79bc VA: 0x7595abf9bc
	public Void .ctor() { }
}
```