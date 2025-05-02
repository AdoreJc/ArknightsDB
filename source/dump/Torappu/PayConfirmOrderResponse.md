# PayConfirmOrderResponse

**Namespace:** `Torappu`


## Fields

- `Int32 result`

- `String goodId`

- `Good receiveItems`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PayConfirmOrderResponse : PlayerDeltaResponse
{
	public Int32 result; // 0x28
	public String goodId; // 0x30
	public Good receiveItems; // 0x38


	// RVA: 0x32ccfe8 VA: 0x75958e4fe8
	public Void .ctor() { }
}
```