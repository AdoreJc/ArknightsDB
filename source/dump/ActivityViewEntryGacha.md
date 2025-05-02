# ActivityViewEntryGacha

**Namespace:** ` `


## Fields

- `String spriteId`

- `String gachaPoolId`

- `Int32 index`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ActivityViewEntryGacha : ActivityViewEntry
{
	public String spriteId; // 0x10
	public String gachaPoolId; // 0x18
	public Int32 index; // 0x20


	// RVA: 0x2825d88 VA: 0x7594e3dd88
	public override Sprite GetImage() { }
	// RVA: 0x2825e6c VA: 0x7594e3de6c
	public override ActivityEntryType EntryType() { }
	// RVA: 0x2825e74 VA: 0x7594e3de74
	public override Void OnClick() { }
	// RVA: 0x2825f28 VA: 0x7594e3df28
	public override Int32 SubOrder() { }
	// RVA: 0x2825f30 VA: 0x7594e3df30
	public override Boolean CheckAvail() { }
	// RVA: 0x2825fbc VA: 0x7594e3dfbc
	public Void .ctor() { }
}
```