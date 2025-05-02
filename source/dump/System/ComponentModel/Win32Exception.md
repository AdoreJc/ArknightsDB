# Win32Exception

**Namespace:** `System.ComponentModel`


## Properties

- `Int32 NativeErrorCode`


## Methods

- `Int32 get_NativeErrorCode()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class Win32Exception : ExternalException, ISerializable
{
	private readonly Int32 nativeErrorCode; // 0x8c

	public Int32 NativeErrorCode { get; }

	// RVA: 0x6407700 VA: 0x7598a1f700
	public Void .ctor() { }
	// RVA: 0x6407774 VA: 0x7598a1f774
	public Void .ctor(Int32 error) { }
	// RVA: 0x64080a0 VA: 0x7598a200a0
	public Void .ctor(Int32 error, String message) { }
	// RVA: 0x64080cc VA: 0x7598a200cc
	public Void .ctor(String message) { }
	// RVA: 0x6408148 VA: 0x7598a20148
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x64081c8 VA: 0x7598a201c8
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6408250 VA: 0x7598a20250
	public Int32 get_NativeErrorCode() { }
	// RVA: 0x6408258 VA: 0x7598a20258
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x64077ac VA: 0x7598a1f7ac
	internal static String GetErrorMessage(Int32 error) { }
}
```