# ProgressChangedEventArgs

**Namespace:** `System.ComponentModel`


## Properties

- `Int32 ProgressPercentage`

- `Object UserState`


## Methods

- `Int32 get_ProgressPercentage()`

- `Object get_UserState()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ProgressChangedEventArgs : EventArgs
{
	private readonly Int32 progressPercentage; // 0x10
	private readonly Object userState; // 0x18

	public Int32 ProgressPercentage { get; }
	public Object UserState { get; }

	// RVA: 0x63e3b60 VA: 0x75989fbb60
	public Void .ctor(Int32 progressPercentage, Object userState) { }
	// RVA: 0x63e3bdc VA: 0x75989fbbdc
	public Int32 get_ProgressPercentage() { }
	// RVA: 0x63e3be4 VA: 0x75989fbbe4
	public Object get_UserState() { }
}
```