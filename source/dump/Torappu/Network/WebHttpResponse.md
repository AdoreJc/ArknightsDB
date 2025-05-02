# WebHttpResponse

**Namespace:** `Torappu.Network`


## Fields

- `Boolean isTimeout`

- `Boolean isError`

- `Int64 responseCode`

- `String text`

- `String error`


## Methods

- `Void ClonePublicFields(WebHttpResponse)`

- `Int64 GetErrorCode()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class WebHttpResponse
{
	public Boolean isTimeout; // 0x10
	public Boolean isError; // 0x11
	public Int64 responseCode; // 0x18
	public Dictionary`2 header; // 0x20
	public String text; // 0x28
	public Byte[] data; // 0x30
	public String error; // 0x38


	// RVA: 0x67b04c4 VA: 0x7598dc84c4
	public Void ClonePublicFields(WebHttpResponse target) { }
	// RVA: 0x67b455c VA: 0x7598dcc55c
	public Int64 GetErrorCode() { }
	// RVA: 0x67b04bc VA: 0x7598dc84bc
	public Void .ctor() { }
}
```