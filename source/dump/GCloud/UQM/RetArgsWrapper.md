# RetArgsWrapper

**Namespace:** `GCloud.UQM`


## Properties

- `Int32 MethodId`

- `String RetJson`

- `Int32 CrashType`

- `Int32 LogUploadResult`


## Methods

- `Int32 get_MethodId()`

- `String get_RetJson()`

- `Int32 get_CrashType()`

- `Int32 get_LogUploadResult()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : GCloud.UQM
public class RetArgsWrapper
{
	private readonly Int32 methodId; // 0x10
	private readonly String retJson; // 0x18
	private readonly Int32 crashType; // 0x20
	private readonly Int32 logUploadResult; // 0x24

	public Int32 MethodId { get; }
	public String RetJson { get; }
	public Int32 CrashType { get; }
	public Int32 LogUploadResult { get; }

	// RVA: 0x66ddc60 VA: 0x7598cf5c60
	public Int32 get_MethodId() { }
	// RVA: 0x66ddc68 VA: 0x7598cf5c68
	public String get_RetJson() { }
	// RVA: 0x66ddc70 VA: 0x7598cf5c70
	public Int32 get_CrashType() { }
	// RVA: 0x66ddc78 VA: 0x7598cf5c78
	public Int32 get_LogUploadResult() { }
	// RVA: 0x66ddc80 VA: 0x7598cf5c80
	public Void .ctor(Int32 _methodId, String _retJson, Int32 _crashType, Int32 _logUploadResult) { }
}
```