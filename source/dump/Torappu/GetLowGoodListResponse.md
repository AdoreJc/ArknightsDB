# GetLowGoodListResponse

**Namespace:** `Torappu`


## Fields

- `Int64 shopEndTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GetLowGoodListResponse : PlayerDeltaResponse, IQCShopGetResponse, IShopGetResposne
{
	public List`1 goodList; // 0x28
	public List`1 groups; // 0x30
	public Int64 shopEndTime; // 0x38
	public List`1 newFlag; // 0x40


	// RVA: 0x32ccf38 VA: 0x75958e4f38
	public List`1 GetNewFlag() { }
	// RVA: 0x32ccf40 VA: 0x75958e4f40
	public Void .ctor() { }
}
```