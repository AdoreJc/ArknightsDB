# OptionalVoucherInfo

**Namespace:** `Torappu`


## Fields

- `OptionalVoucherType voucherType`

- `Int32 pickNum`

- `String voucherBgDec`

- `OptionalVoucherValidInfo validTimeInfo`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class OptionalVoucherInfo
{
	public OptionalVoucherType voucherType; // 0x10
	public Int32 pickNum; // 0x14
	public String voucherBgDec; // 0x18
	public Dictionary`2 extraDataDic; // 0x20
	public List`1 itemList; // 0x28
	public OptionalVoucherValidInfo validTimeInfo; // 0x30


	// RVA: 0x34a618c VA: 0x7595abe18c
	public Void .ctor() { }
}
```