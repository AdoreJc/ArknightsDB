# ResponseDescription

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class ResponseDescription
{
	internal Boolean Multiline; // 0x10
	internal Int32 Status; // 0x14
	internal String StatusDescription; // 0x18
	internal StringBuilder StatusBuffer; // 0x20
	internal String StatusCodeString; // 0x28

	internal Boolean PositiveIntermediate { get; }
	internal Boolean PositiveCompletion { get; }
	internal Boolean TransientFailure { get; }
	internal Boolean PermanentFailure { get; }
	internal Boolean InvalidStatusCode { get; }

	// RVA: 0x641b27c VA: 0x7598a3327c
	internal Boolean get_PositiveIntermediate() { }
	// RVA: 0x641b290 VA: 0x7598a33290
	internal Boolean get_PositiveCompletion() { }
	// RVA: 0x641b2a4 VA: 0x7598a332a4
	internal Boolean get_TransientFailure() { }
	// RVA: 0x641b2b8 VA: 0x7598a332b8
	internal Boolean get_PermanentFailure() { }
	// RVA: 0x641b2cc VA: 0x7598a332cc
	internal Boolean get_InvalidStatusCode() { }
	// RVA: 0x641b2e0 VA: 0x7598a332e0
	public Void .ctor() { }
}
```