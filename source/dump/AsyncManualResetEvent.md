# AsyncManualResetEvent

**Namespace:** ` `


## Methods

- `Void Set()`

- `Void Reset()`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class AsyncManualResetEvent
{
	private TaskCompletionSource`1 m_tcs; // 0x10


	// RVA: 0x633416c VA: 0x759894c16c
	public Task`1 WaitAsync(Int32 millisecondTimeout) { }
	// RVA: 0x633212c VA: 0x759894a12c
	public Void Set() { }
	// RVA: 0x6332834 VA: 0x759894a834
	public Void Reset() { }
	// RVA: 0x6331e74 VA: 0x7598949e74
	public Void .ctor(Boolean state) { }
}
```