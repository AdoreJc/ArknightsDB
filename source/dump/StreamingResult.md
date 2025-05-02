# StreamingResult

**Namespace:** ` `


## Fields

- `Int64 <respCode>k__BackingField`

- `String <text>k__BackingField`

- `Boolean <isError>k__BackingField`

- `String <errorInfo>k__BackingField`


## Properties

- `Int64 respCode`

- `String text`

- `Boolean isError`

- `String errorInfo`


## Methods

- `Int64 get_respCode()`

- `Void set_respCode(Int64)`

- `Void set_bytes(Byte[])`

- `String get_text()`

- `Void set_text(String)`

- `Boolean get_isError()`

- `Void set_isError(Boolean)`

- `String get_errorInfo()`

- `Void set_errorInfo(String)`

- `Boolean FileNotExists()`

- `Void MarkAsError(Int64, String)`

- `Void MarkAsSucceed(DownloadHandler)`

- `Void Clear()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class StreamingResult
{
	private Int64 <respCode>k__BackingField; // 0x10
	private Byte[] <bytes>k__BackingField; // 0x18
	private String <text>k__BackingField; // 0x20
	private Boolean <isError>k__BackingField; // 0x28
	private String <errorInfo>k__BackingField; // 0x30

	public Int64 respCode { get; set; }
	public Byte[] bytes { get; set; }
	public String text { get; set; }
	public Boolean isError { get; set; }
	public String errorInfo { get; set; }

	// RVA: 0x676bdc0 VA: 0x7598d83dc0
	public Int64 get_respCode() { }
	// RVA: 0x676bdc8 VA: 0x7598d83dc8
	private Void set_respCode(Int64 value) { }
	// RVA: 0x676bdd0 VA: 0x7598d83dd0
	public Byte[] get_bytes() { }
	// RVA: 0x676bdd8 VA: 0x7598d83dd8
	private Void set_bytes(Byte[] value) { }
	// RVA: 0x676bde0 VA: 0x7598d83de0
	public String get_text() { }
	// RVA: 0x676bde8 VA: 0x7598d83de8
	private Void set_text(String value) { }
	// RVA: 0x676bdf0 VA: 0x7598d83df0
	public Boolean get_isError() { }
	// RVA: 0x676bdf8 VA: 0x7598d83df8
	private Void set_isError(Boolean value) { }
	// RVA: 0x676be04 VA: 0x7598d83e04
	public String get_errorInfo() { }
	// RVA: 0x676be0c VA: 0x7598d83e0c
	private Void set_errorInfo(String value) { }
	// RVA: 0x676ba80 VA: 0x7598d83a80
	public Boolean FileNotExists() { }
	// RVA: 0x676be14 VA: 0x7598d83e14
	public Void MarkAsError(Int64 responseCode, String error) { }
	// RVA: 0x676be68 VA: 0x7598d83e68
	public Void MarkAsSucceed(DownloadHandler downloadHandler) { }
	// RVA: 0x676bed0 VA: 0x7598d83ed0
	public Void Clear() { }
	// RVA: 0x676b994 VA: 0x7598d83994
	public Void .ctor() { }
}
```