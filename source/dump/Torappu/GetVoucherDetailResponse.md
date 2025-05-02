# GetVoucherDetailResponse

**Namespace:** `Torappu`


## Fields

- `Int32 pickNum`

- `String voucherBgDec`

- `OptionalVoucherType voucherType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GetVoucherDetailResponse
{
	public Int32 pickNum; // 0x10
	public String voucherBgDec; // 0x18
	public List`1 itemList; // 0x20
	public Dictionary`2 extraDataDic; // 0x28
	public OptionalVoucherType voucherType; // 0x30


	// RVA: 0x32cc284 VA: 0x75958e4284
	public Void .ctor() { }
}
```