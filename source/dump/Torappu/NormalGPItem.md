# NormalGPItem

**Namespace:** `Torappu`


## Fields

- `String goodId`

- `String giftPackageId`

- `Int32 priority`

- `String displayName`

- `ShopCurrencyUnit currencyUnit`

- `Int32 availCount`

- `Int32 buyCount`

- `Int32 price`

- `Int32 originPrice`

- `Single discount`

- `Int64 startDateTime`

- `Int64 endDateTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class NormalGPItem
{
	public String goodId; // 0x10
	public String giftPackageId; // 0x18
	public Int32 priority; // 0x20
	public String displayName; // 0x28
	public ShopCurrencyUnit currencyUnit; // 0x30
	public Int32 availCount; // 0x34
	public Int32 buyCount; // 0x38
	public Int32 price; // 0x3c
	public Int32 originPrice; // 0x40
	public Single discount; // 0x44
	public ItemBundle[] items; // 0x48
	public Dictionary`2 specialItemInfos; // 0x50
	public Int64 startDateTime; // 0x58
	public Int64 endDateTime; // 0x60
	public List`1 tab; // 0x68


	// RVA: 0x32ccffc VA: 0x75958e4ffc
	public Void .ctor() { }
}
```