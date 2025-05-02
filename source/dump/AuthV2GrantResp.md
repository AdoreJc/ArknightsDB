# AuthV2GrantResp

**Namespace:** ` `


## Fields

- `Int32 status`

- `String msg`

- `String type`

- `String uid`

- `String code`

- `String token`

- `Int64 banStartTs`

- `Int64 banEndTs`


## Methods

- `Boolean LoadFromJSON(String)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : 
protected class AuthV2GrantResp : IFromJSON
{
	public Int32 status; // 0x10
	public String msg; // 0x18
	public String type; // 0x20
	public String uid; // 0x28
	public String code; // 0x30
	public String token; // 0x38
	public Int64 banStartTs; // 0x40
	public Int64 banEndTs; // 0x48
	public Dictionary`2 captcha; // 0x50


	// RVA: 0x67d8474 VA: 0x7598df0474
	public Boolean LoadFromJSON(String json) { }
	// RVA: 0x67d8764 VA: 0x7598df0764
	public Void .ctor() { }
}
```