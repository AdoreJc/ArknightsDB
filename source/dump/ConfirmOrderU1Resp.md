# ConfirmOrderU1Resp

**Namespace:** ` `


## Fields

- `Int32 status`


## Methods

- `Boolean LoadFromJSON(String)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : 
protected class ConfirmOrderU1Resp : IFromJSON
{
	public const Int32 STATUS_ORDER_NOT_EXIST; // 0x0
	public const Int32 STATUS_THIRD_PARTY_PENDING; // 0x0
	public const Int32 STATUS_GAME_SERVER_PENDING; // 0x0
	public Int32 status; // 0x10


	// RVA: 0x67d876c VA: 0x7598df076c
	public Boolean LoadFromJSON(String json) { }
	// RVA: 0x67d8830 VA: 0x7598df0830
	public Void .ctor() { }
}
```