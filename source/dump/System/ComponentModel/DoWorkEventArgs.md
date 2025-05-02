# DoWorkEventArgs

**Namespace:** `System.ComponentModel`


## Fields

- `Object result`

- `Object argument`


## Properties

- `Object Argument`

- `Object Result`


## Methods

- `Object get_Argument()`

- `Object get_Result()`

- `Void set_Result(Object)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class DoWorkEventArgs : CancelEventArgs
{
	private Object result; // 0x18
	private Object argument; // 0x20

	public Object Argument { get; }
	public Object Result { get; set; }

	// RVA: 0x63e041c VA: 0x75989f841c
	public Void .ctor(Object argument) { }
	// RVA: 0x63e0448 VA: 0x75989f8448
	public Object get_Argument() { }
	// RVA: 0x63e0450 VA: 0x75989f8450
	public Object get_Result() { }
	// RVA: 0x63e0458 VA: 0x75989f8458
	public Void set_Result(Object value) { }
}
```