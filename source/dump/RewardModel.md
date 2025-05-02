# RewardModel

**Namespace:** ` `


## Fields

- `String id`

- `ItemType type`

- `Int32 count`

- `GachaResult charGet`


## Methods

- `ItemType GetItemType()`

- `String GetItemId()`

- `Int32 GetItemCount()`

- `Void SetItemCount(Int32)`

- `GachaResult GetGachaResult()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewardModel : ISharedItemModel, IGachaResultHolder
{
	public String id; // 0x10
	public ItemType type; // 0x18
	public Int32 count; // 0x1c
	public GachaResult charGet; // 0x20


	// RVA: 0x32cb780 VA: 0x75958e3780
	public ItemType GetItemType() { }
	// RVA: 0x32cb788 VA: 0x75958e3788
	public String GetItemId() { }
	// RVA: 0x32cb790 VA: 0x75958e3790
	public Int32 GetItemCount() { }
	// RVA: 0x32cb798 VA: 0x75958e3798
	public Void SetItemCount(Int32 count_) { }
	// RVA: 0x32cb7a0 VA: 0x75958e37a0
	public GachaResult GetGachaResult() { }
	// RVA: 0x32cb7a8 VA: 0x75958e37a8
	public Void .ctor() { }
}
```