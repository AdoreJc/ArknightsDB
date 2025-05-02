# CreateOrderU1Resp

**Namespace:** ` `


## Fields

- `Int32 status`

- `String msg`

- `String type`

- `Data data`


## Methods

- `Boolean LoadFromJSON(String)`

- `U8OrderInfo ToOrderInfo()`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : 
protected class CreateOrderU1Resp : IFromJSON
{
	public Int32 status; // 0x10
	public String msg; // 0x18
	public String type; // 0x20
	public Data data; // 0x28


	// RVA: 0x67d8838 VA: 0x7598df0838
	public Boolean LoadFromJSON(String json) { }
	// RVA: 0x67d8b34 VA: 0x7598df0b34
	public U8OrderInfo ToOrderInfo() { }
	// RVA: 0x67d8c78 VA: 0x7598df0c78
	public Void .ctor() { }
}
```