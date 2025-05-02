# AsyncProtocolResult

**Namespace:** `Mono.Net.Security`


## Properties

- `Int32 UserResult`

- `ExceptionDispatchInfo Error`


## Methods

- `Int32 get_UserResult()`

- `ExceptionDispatchInfo get_Error()`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Net.Security
internal class AsyncProtocolResult
{
	private readonly Int32 <UserResult>k__BackingField; // 0x10
	private readonly ExceptionDispatchInfo <Error>k__BackingField; // 0x18

	public Int32 UserResult { get; }
	public ExceptionDispatchInfo Error { get; }

	// RVA: 0x625a1a0 VA: 0x75988721a0
	public Int32 get_UserResult() { }
	// RVA: 0x625a1a8 VA: 0x75988721a8
	public ExceptionDispatchInfo get_Error() { }
	// RVA: 0x625a1b0 VA: 0x75988721b0
	public Void .ctor(Int32 result) { }
	// RVA: 0x625a1d8 VA: 0x75988721d8
	public Void .ctor(ExceptionDispatchInfo error) { }
}
```