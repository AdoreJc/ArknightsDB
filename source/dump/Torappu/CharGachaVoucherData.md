# CharGachaVoucherData

**Namespace:** `Torappu`


## Fields

- `String voucherId`

- `Int32 pickNum`

- `Boolean hasSecurity`

- `Int32 securityRarity`

- `Int64 startTime`

- `Int64 endTime`

- `GachaVoucherType voucherType`

- `GachaDetailData detailData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharGachaVoucherData
{
	public String voucherId; // 0x10
	public Int32 pickNum; // 0x18
	public Boolean hasSecurity; // 0x1c
	public Int32 securityRarity; // 0x20
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	public GachaVoucherType voucherType; // 0x38
	public List`1 rarityRateList; // 0x40
	public List`1 pool; // 0x48
	public GachaDetailData detailData; // 0x50


	// RVA: 0x32cbb84 VA: 0x75958e3b84
	public Void .ctor() { }
}
```