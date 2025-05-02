# AsyncCompletedEventArgs

**Namespace:** `System.ComponentModel`


## Properties

- `Boolean Cancelled`

- `Exception Error`

- `Object UserState`


## Methods

- `Boolean get_Cancelled()`

- `Exception get_Error()`

- `Object get_UserState()`

- `Void RaiseExceptionIfNecessary()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class AsyncCompletedEventArgs : EventArgs
{
	private readonly Exception error; // 0x10
	private readonly Boolean cancelled; // 0x18
	private readonly Object userState; // 0x20

	public Boolean Cancelled { get; }
	public Exception Error { get; }
	public Object UserState { get; }

	// RVA: 0x63db94c VA: 0x75989f394c
	public Void .ctor() { }
	// RVA: 0x63db9a4 VA: 0x75989f39a4
	public Void .ctor(Exception error, Boolean cancelled, Object userState) { }
	// RVA: 0x63dba3c VA: 0x75989f3a3c
	public Boolean get_Cancelled() { }
	// RVA: 0x63dba44 VA: 0x75989f3a44
	public Exception get_Error() { }
	// RVA: 0x63dba4c VA: 0x75989f3a4c
	public Object get_UserState() { }
	// RVA: 0x63dba54 VA: 0x75989f3a54
	protected Void RaiseExceptionIfNecessary() { }
}
```