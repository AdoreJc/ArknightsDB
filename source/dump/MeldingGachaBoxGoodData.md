# MeldingGachaBoxGoodData

**Namespace:** ` `


## Fields

- `String goodId`

- `String gachaBoxId`

- `Int32 orderId`

- `String itemId`

- `ItemType itemType`

- `MeldingGoodDisplayType displayType`

- `Int32 perCount`

- `Int32 totalCount`

- `MeldingGoodGachaType gachaType`

- `Int32 weight`

- `Int32 gachaOrderId`

- `Int32 gachaNum`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MeldingGachaBoxGoodData
{
	public String goodId; // 0x10
	public String gachaBoxId; // 0x18
	public Int32 orderId; // 0x20
	public String itemId; // 0x28
	public ItemType itemType; // 0x30
	public MeldingGoodDisplayType displayType; // 0x34
	public Int32 perCount; // 0x38
	public Int32 totalCount; // 0x3c
	public MeldingGoodGachaType gachaType; // 0x40
	public Int32 weight; // 0x44
	public Int32 gachaOrderId; // 0x48
	public Int32 gachaNum; // 0x4c


	// RVA: 0x33b635c VA: 0x75959ce35c
	public virtual Boolean ShouldSerializeweight() { }
	// RVA: 0x33b636c VA: 0x75959ce36c
	public virtual Boolean ShouldSerializegachaOrderId() { }
	// RVA: 0x33b637c VA: 0x75959ce37c
	public virtual Boolean ShouldSerializegachaNum() { }
	// RVA: 0x33b638c VA: 0x75959ce38c
	public Void .ctor() { }
}
```