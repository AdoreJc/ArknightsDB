# UnhandledExceptionEventArgs

**Namespace:** `System`


## Fields

- `Object _exception`

- `Boolean _isTerminating`


## Properties

- `Object ExceptionObject`

- `Boolean IsTerminating`


## Methods

- `Object get_ExceptionObject()`

- `Boolean get_IsTerminating()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class UnhandledExceptionEventArgs : EventArgs
{
	private Object _exception; // 0x10
	private Boolean _isTerminating; // 0x18

	public Object ExceptionObject { get; }
	public Boolean IsTerminating { get; }

	// RVA: 0x60d0adc VA: 0x75986e8adc
	public Void .ctor(Object exception, Boolean isTerminating) { }
	// RVA: 0x60d0b5c VA: 0x75986e8b5c
	public Object get_ExceptionObject() { }
	// RVA: 0x60d0b64 VA: 0x75986e8b64
	public Boolean get_IsTerminating() { }
}
```