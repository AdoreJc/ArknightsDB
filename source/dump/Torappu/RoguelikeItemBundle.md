# RoguelikeItemBundle

**Namespace:** `Torappu`


## Fields

- `Int32 sub`

- `String id`

- `Int32 count`


## Methods

- `ItemType GetItemType()`

- `String GetItemId()`

- `Int32 GetItemCount()`

- `Void SetItemCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeItemBundle : ISharedItemModel
{
	public Int32 sub; // 0x10
	public String id; // 0x18
	public Int32 count; // 0x20


	// RVA: 0x34a7d74 VA: 0x7595abfd74
	public ItemType GetItemType() { }
	// RVA: 0x34a7d7c VA: 0x7595abfd7c
	public String GetItemId() { }
	// RVA: 0x34a7d84 VA: 0x7595abfd84
	public Int32 GetItemCount() { }
	// RVA: 0x34a7d8c VA: 0x7595abfd8c
	public Void SetItemCount(Int32 count) { }
	// RVA: 0x34a7d94 VA: 0x7595abfd94
	public Void .ctor() { }
}
```