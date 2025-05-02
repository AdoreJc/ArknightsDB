# WeightItemBundle

**Namespace:** `Torappu`


## Fields

- `String id`

- `ItemType type`

- `StageDropType dropType`

- `Int32 count`

- `Int32 weight`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class WeightItemBundle
{
	public String id; // 0x10
	public ItemType type; // 0x18
	public StageDropType dropType; // 0x1c
	public Int32 count; // 0x20
	public Int32 weight; // 0x24


	// RVA: 0x34a3ab4 VA: 0x7595abbab4
	public Void .ctor() { }
	// RVA: 0x34a3abc VA: 0x7595abbabc
	public Void .ctor(String itemId_, ItemType itemType_, Int32 count_, Int32 weight_, StageDropType dropType_) { }
}
```