# ActivityViewEntryShop

**Namespace:** ` `


## Fields

- `String spriteId`

- `ShopRouteTarget shopTarget`

- `String goodId`

- `Int32 index`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ActivityViewEntryShop : ActivityViewEntry
{
	public String spriteId; // 0x10
	public ShopRouteTarget shopTarget; // 0x18
	public String goodId; // 0x20
	public Int32 index; // 0x28


	// RVA: 0x2826df0 VA: 0x7594e3edf0
	public override Sprite GetImage() { }
	// RVA: 0x2826ed4 VA: 0x7594e3eed4
	public override ActivityEntryType EntryType() { }
	// RVA: 0x2826edc VA: 0x7594e3eedc
	public override Void OnClick() { }
	// RVA: 0x2826f94 VA: 0x7594e3ef94
	public override Int32 SubOrder() { }
	// RVA: 0x2826f9c VA: 0x7594e3ef9c
	public override Boolean CheckAvail() { }
	// RVA: 0x2827028 VA: 0x7594e3f028
	public Void .ctor() { }
}
```