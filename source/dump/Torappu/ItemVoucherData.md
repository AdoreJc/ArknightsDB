# ItemVoucherData

**Namespace:** `Torappu`


## Fields

- `String voucherId`

- `Int32 pickNum`

- `String picId`

- `Int64 startTime`

- `Int64 endTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ItemVoucherData
{
	public String voucherId; // 0x10
	public Int32 pickNum; // 0x18
	public String picId; // 0x20
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	public List`1 pool; // 0x38


	// RVA: 0x32cbb9c VA: 0x75958e3b9c
	public List`1 GetList() { }
	// RVA: 0x32cc0d4 VA: 0x75958e40d4
	public Void .ctor() { }
}
```