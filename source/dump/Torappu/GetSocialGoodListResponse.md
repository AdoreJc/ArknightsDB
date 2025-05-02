# GetSocialGoodListResponse

**Namespace:** `Torappu`


## Fields

- `Int32 costSocialPoint`

- `String creditGroup`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GetSocialGoodListResponse : PlayerDeltaResponse, IShopGetResposne
{
	public List`1 goodList; // 0x28
	public Dictionary`2 charPurchase; // 0x30
	public Int32 costSocialPoint; // 0x38
	public String creditGroup; // 0x40


	// RVA: 0x32ccfa8 VA: 0x75958e4fa8
	public Void .ctor() { }
}
```