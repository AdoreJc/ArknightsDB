# AuthV2SessionTokenResp

**Namespace:** ` `


## Fields

- `Int32 status`

- `String msg`

- `String type`

- `String token`


## Methods

- `Boolean LoadFromJSON(String)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : 
protected class AuthV2SessionTokenResp : IFromJSON
{
	public Int32 status; // 0x10
	public String msg; // 0x18
	public String type; // 0x20
	public String token; // 0x28


	// RVA: 0x67d8298 VA: 0x7598df0298
	public Boolean LoadFromJSON(String json) { }
	// RVA: 0x67d846c VA: 0x7598df046c
	public Void .ctor() { }
}
```