# GetExtraGoodListResponse

**Namespace:** `Torappu`


## Fields

- `Int64 lastClick`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GetExtraGoodListResponse : PlayerDeltaResponse, IQCShopGetResponse, IShopGetResposne
{
	public List`1 goodList; // 0x28
	public Int64 lastClick; // 0x30
	public List`1 newFlag; // 0x38


	// RVA: 0x32ccf24 VA: 0x75958e4f24
	public List`1 GetNewFlag() { }
	// RVA: 0x32ccf2c VA: 0x75958e4f2c
	public Void .ctor() { }
}
```