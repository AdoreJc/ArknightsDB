# EventWaitHandle

**Namespace:** `System.Threading`


## Methods

- `Boolean Reset()`

- `Boolean Set()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public class EventWaitHandle : WaitHandle
{


	// RVA: 0x6118220 VA: 0x7598730220
	public Void .ctor(Boolean initialState, EventResetMode mode) { }
	// RVA: 0x611f7c4 VA: 0x75987377c4
	public Void .ctor(Boolean initialState, EventResetMode mode, String name) { }
	// RVA: 0x611d6a8 VA: 0x75987356a8
	public Boolean Reset() { }
	// RVA: 0x6119d90 VA: 0x7598731d90
	public Boolean Set() { }
}
```