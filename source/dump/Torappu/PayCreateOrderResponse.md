# PayCreateOrderResponse

**Namespace:** `Torappu`


## Fields

- `Int32 result`

- `String orderId`

- `String extension`

- `Boolean alertMinor`

- `String errMsg`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PayCreateOrderResponse
{
	public Int32 result; // 0x10
	public String orderId; // 0x18
	public String extension; // 0x20
	public List`1 orderIdList; // 0x28
	public Boolean alertMinor; // 0x30
	public String errMsg; // 0x38


	// RVA: 0x32ccfc8 VA: 0x75958e4fc8
	public Void .ctor() { }
}
```