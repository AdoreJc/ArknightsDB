# RunWorkerCompletedEventArgs

**Namespace:** `System.ComponentModel`


## Fields

- `Object result`


## Properties

- `Object Result`

- `Object UserState`


## Methods

- `Object get_Result()`

- `Object get_UserState()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class RunWorkerCompletedEventArgs : AsyncCompletedEventArgs
{
	private Object result; // 0x28

	public Object Result { get; }
	public Object UserState { get; }

	// RVA: 0x63f28b8 VA: 0x7598a0a8b8
	public Void .ctor(Object result, Exception error, Boolean cancelled) { }
	// RVA: 0x63f28f8 VA: 0x7598a0a8f8
	public Object get_Result() { }
	// RVA: 0x63f2914 VA: 0x7598a0a914
	public Object get_UserState() { }
}
```